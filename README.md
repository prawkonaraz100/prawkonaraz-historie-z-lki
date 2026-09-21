# PrawkoNaRaz — Historie z L-ki

Repozytorium produkcyjne i kanoniczna dokumentacja animowanego uniwersum **„PrawkoNaRaz — Historie z L-ki”**.

To repozytorium jest celowo oddzielone od kodu aplikacji PrawkoNaRaz. Przechowujemy tutaj biblię świata, postacie, lokacje, pojazdy, zasady wizualne, scenariusze, storyboardy oraz materiały produkcyjne serii.

## Zasada kanonu

Pliki oznaczone jako `MASTER` są nadrzędnymi referencjami. Nowy scenariusz, grafika, animacja lub dialog nie może przypadkowo zmieniać ustalonego kanonu. Najpierw aktualizujemy odpowiednią referencję MASTER, a dopiero później wykorzystujemy zmianę w produkcji.

## Planowana struktura

- `characters/` — główne i drugoplanowe postacie wraz z kanonicznymi referencjami wizualnymi
- `world/` — zasady i biblia świata
- `locations/` — stałe lokacje
- `vehicles/` — samochody szkoleniowe i inne pojazdy
- `visual-style/` — język wizualny, paleta, zasady animacji
- `episodes/` — scenariusze i storyboardy odcinków
- `production/` — zasady produkcji, głosu, montażu i publikacji
- `assets/` — pozostałe zatwierdzone materiały produkcyjne

## Quality Gate

Repozytorium ma automatyczny Quality Gate w `.github/workflows/quality-gate.yml`. Uruchamia się dla pull requestów oraz pushy do `main`.

Gate sprawdza:
- obecność aktualnych plików kanonicznych MASTER i ich zatwierdzonych referencji,
- poprawne kodowanie UTF-8 plików tekstowych,
- brak pozostawionych markerów konfliktu merge,
- strukturę `research/OSK-WEBSITE-TECH-AUDIT.md` — każdy wpis ma dokładnie pola `URL`, `Technologia`, `Dowód`,
- brak zduplikowanych adresów URL w audycie OSK.

Zmiany nie są uznawane za ukończone bez zakończonego wynikiem PASS Quality Gate dla właściwego HEAD.

## Aktualny etap

Najpierw projektujemy kompletne uniwersum. Nie rozpoczynamy seryjnej produkcji odcinków, dopóki główne postacie, świat i zasady wizualne nie mają zatwierdzonych referencji.

### Główni bohaterowie

1. **Jacek** — instruktor, główny protagonista męski — MASTER v1 + kanoniczna referencja wizualna.
2. **Ola** — instruktorka, główna protagonistka żeńska — MASTER v1 + kanoniczna referencja wizualna.
3. **Pani Ilona** — właścicielka i menedżerka fikcyjnego OSK — MASTER v1 + kanoniczna referencja wizualna.

PrawkoNaRaz jest marką i wydawcą serii. Bohaterowie działają w fikcyjnym **OSK Kierunek**. Nazwa oraz geometria głównej lokacji są już kanoniczne; trwa projektowanie jej warstwy wizualnej.
