# Audyt technologii stron polskich OSK — v1

> **Status:** research / materiał referencyjny, nie kanon świata
> **Data badania:** 2026-09-20
> **Zakres:** publicznie dostępne strony polskich ośrodków szkolenia kierowców (OSK) znalezione w wyszukiwaniu internetowym.
> **Cel:** zebrać realne przykłady stron szkół jazdy i podzielić je według wykrywalnej technologii wykonania, aby późniejsze decyzje wizualne i produktowe opierać na rzeczywistym rynku.
> **Ważne:** nie istnieje kompletna publiczna lista wszystkich domen OSK w Polsce, więc „wszystkie strony z sieci” nie może być traktowane jako matematycznie kompletne przeszukanie całego Internetu. Dokument obejmuje serwisy wykryte w audycie i ma być rozszerzany przy kolejnych przebiegach.

## Metoda klasyfikacji

Technologię przypisujemy wyłącznie wtedy, gdy istnieje publiczny ślad techniczny, np.:

- zasoby `/wp-content/`, `/wp-includes/` lub jawna stopka WordPress → **WordPress**;
- zasoby `static.wixstatic.com` / infrastruktura Wix → **Wix**;
- jawne sygnatury Joomla → **Joomla**;
- jawne assety/framework/runtime → odpowiednia technologia;
- brak wystarczającego śladu → **nierozpoznane / wymaga inspekcji HTML i nagłówków**.

Nie zgadujemy CMS-u na podstawie wyglądu strony.

---

# 1. WordPress

## OSK Waldemar Kawa — Inowrocław
- URL: https://inowroclawosk.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: publiczne obrazy są serwowane z `/wp-content/uploads/`.
- Charakter strony: klasyczna witryna lokalnego OSK; oferta kat. B, jazdy doszkalające, instruktor, kontakt.
- Wniosek referencyjny: typowy model małego OSK — strona pełni przede wszystkim rolę wizytówki i generatora kontaktów.

## OSK Malibu — Warszawa / Borowa Góra
- URL: https://osk.malibu.auto.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: zasoby `/wp-content/uploads/`.
- Charakter strony: landing sprzedażowy z wariantami kursów, cenami, formularzem i informacją o pojeździe.
- Wniosek referencyjny: mocniejsze eksponowanie pakietów kursu niż samej marki świata OSK.

## DriveWars — Wrocław
- URL: https://drivewars.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: liczne zasoby `/wp-content/uploads/`.
- Charakter strony: bardzo osobowościowa marka; mocno eksponowany zespół instruktorów i ich indywidualne opisy.
- Wniosek referencyjny: jeden z ciekawszych przykładów budowania OSK przez bohaterów/ludzi, a nie tylko tabelę cen.

## Dobre Jazdy / Instruktor Hozer — Kielce
- URL: https://dobrejazdy.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: media i logo z `/wp-content/uploads/`.
- Charakter strony: OSK + rozbudowany poradnik/blog.
- Wniosek referencyjny: treści edukacyjne i aktualności tworzą większy świat marki niż sama oferta kursu.

## OSK Navigator — Kraków / Niepołomice
- URL: https://www.osknavigator.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: obrazy ofertowe z `/wp-content/uploads/`.
- Charakter strony: kursy jako produkty, ceny, terminy, CTA „Zapisz się”.
- Wniosek referencyjny: klasyczny sprzedażowy układ OSK.

## L Brudny — Cieszyn / Skoczów
- URL: https://lbrudny.pl/osk/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: publiczne media z `/wp-content/uploads/`.
- Charakter strony: szeroka oferta, flota, symulatory, kilka lokalizacji.
- Wniosek referencyjny: większy OSK może komunikować zaplecze i sprzęt jako istotną część tożsamości.

## Szkoła OES — Warszawa
- URL: https://warszawa.szkola-oes.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: treści i filmy są publikowane pod `/wp-content/uploads/`.
- Charakter strony: rozbudowany serwis z kursami, kontem/logowaniem, koszykiem, aktualnościami i poradnikiem.
- Wniosek referencyjny: przykład OSK, którego witryna wychodzi poza prostą wizytówkę.

## AutoQ / treści o nauce jazdy — Lublin
- URL: https://autoq.pl/
- Technologia: **WordPress**
- Pewność: **bardzo wysoka**
- Dowód: jawna stopka „Powered by WordPress”.
- Uwaga: serwis ma szerszy charakter motoryzacyjny i nie jest czystym odpowiednikiem pojedynczego OSK; zachowany jako przykład technologiczny, nie jako główny benchmark OSK.

---

# 2. Wix

## OSK ATUT — Kluczbork
- URL: https://www.osk-atut.pl/
- Technologia: **Wix**
- Pewność: **bardzo wysoka**
- Dowód: obrazy i assety pochodzą z `static.wixstatic.com`.
- Charakter strony: jedna długa strona z ofertą, cenami, galerią i kontaktem.
- Wniosek referencyjny: typowy no-code/website-builder — łatwy w utrzymaniu, ale strukturalnie prosty.

---

# 3. CMS / technologia jeszcze nierozpoznana

## OSK Classic — Radzymin / Warszawa
- URL: https://www.osk-classic.pl/
- Technologia: **nierozpoznana w tym przebiegu**
- Pewność: **brak podstaw do uczciwego przypisania**
- Charakter strony: bardzo rozbudowany katalog kursów — prawo jazdy, kierowcy zawodowi, maszyny, UDT, spawanie, SEP i badania.
- Uwaga: sam wygląd i struktura nie są wystarczającym dowodem na WordPress/Joomla/inny CMS. Potrzebna inspekcja surowego HTML, assetów i nagłówków.

## OSK Kurzawa
- URL: https://www.osk-kurzawa.pl/
- Technologia: **nierozpoznana w tym przebiegu**
- Powód: strona została odnaleziona, ale pełne pobranie strony podczas audytu zakończyło się timeoutem.
- Charakter strony z indeksu: rozbudowana oferta kursu, teoria, praktyka, przygotowanie do egzaminu.
- Następny krok: ponowić inspekcję techniczną.

## OSK Zubrzycki
- URL: https://www.zubrzycki.osk.info.pl/
- Technologia: **nierozpoznana w tym przebiegu**
- Charakter strony: wielokategoryjna oferta prawa jazdy i kursów zawodowych.
- Uwaga: subdomena `osk.info.pl` może wskazywać na wspólną platformę dla OSK, ale bez dowodu technicznego nie przypisujemy konkretnego CMS/frameworka.

---

# 4. Podział rynku według wykrytej technologii

| Technologia | Potwierdzone serwisy w tej próbie | Obserwacja |
|---|---:|---|
| WordPress | 8 | Zdecydowanie najczęstszy wykryty stos w badanej próbie. |
| Wix | 1 | Prosty builder używany przez lokalny OSK. |
| Joomla | 0 potwierdzonych | W wynikach występują oferty/szablony dla branży OSK, ale w tej próbie nie znaleziono serwisu, który można uczciwie oznaczyć jako aktywny OSK na Joomla. |
| Webflow | 0 potwierdzonych | Brak potwierdzonego OSK w tej próbie. |
| Squarespace | 0 potwierdzonych | Brak potwierdzonego OSK w tej próbie. |
| Custom / framework | 0 potwierdzonych | Brak wystarczających danych w tej próbie. |
| Nierozpoznane | 3 | Wymagają głębszej inspekcji technicznej. |

> Liczby dotyczą **tej próby badawczej**, a nie całego rynku OSK w Polsce.

---

# 5. Co powtarza się na stronach OSK niezależnie od technologii

W przebadanych serwisach regularnie występują:

1. **Oferta kategorii prawa jazdy** — najczęściej B jako produkt główny.
2. **Cena i wariant kursu** — standard, weekendowy, ekspresowy, jazdy dodatkowe.
3. **Terminy / zapisy** — często najważniejsze CTA.
4. **Flota / samochód egzaminacyjny** — realny pojazd jest ważnym argumentem.
5. **Instruktorzy** — od krótkiej sekcji po rozbudowane profile.
6. **Kontakt i lokalizacja** — telefon nadal jest bardzo mocno eksponowany.
7. **Opinie / zdawalność / doświadczenie** — częsty mechanizm budowania zaufania.
8. **Materiały edukacyjne / blog** — obecne w bardziej rozwiniętych serwisach.
9. **Kursy zawodowe / Kod 95 / dodatkowe uprawnienia** — szczególnie w większych ośrodkach.
10. **Formularz online** — często prosty formularz kontaktowy zamiast pełnego systemu obsługi kursanta.

---

# 6. Wniosek dla projektu OSK Kierunek / Historie z L-ki

Ten research **nie zmienia kanonu OSK Kierunek**. Jest materiałem referencyjnym.

Najważniejsza obserwacja wizualno-światotwórcza: realne OSK bardzo często są zwykłymi, użytkowymi firmami lokalnymi. Ich strony eksponują ludzi, samochody, ceny, terminy, biuro i kontakt. Nie ma potrzeby projektować OSK Kierunek jak dużego kampusu lub korporacyjnej siedziby.

Dla naszego świata szczególnie użyteczne są trzy wzorce:

- **ludzie jako marka** — DriveWars;
- **edukacja + poradnik jako rozszerzenie świata** — Dobre Jazdy;
- **większy operacyjny OSK z flotą i zapleczem** — L Brudny / OES.

Nie kopiujemy ich identyfikacji, layoutów ani treści. Traktujemy je wyłącznie jako dowód, jak realne polskie OSK prezentują się i działają w Internecie.

---

# 7. Źródła i stan dalszego audytu

Publiczne serwisy sprawdzone w tym przebiegu:

- https://inowroclawosk.pl/
- https://osk.malibu.auto.pl/
- https://drivewars.pl/
- https://dobrejazdy.pl/
- https://www.osknavigator.pl/
- https://lbrudny.pl/osk/
- https://warszawa.szkola-oes.pl/
- https://autoq.pl/
- https://www.osk-atut.pl/
- https://www.osk-classic.pl/
- https://www.osk-kurzawa.pl/
- https://www.zubrzycki.osk.info.pl/

## Następny przebieg

Aby zbliżyć się do szerokiego obrazu całego polskiego rynku, kolejny etap powinien:
- zebrać OSK miasto po mieście dla wszystkich miast wojewódzkich i większych ośrodków egzaminacyjnych;
- deduplikować domeny;
- sprawdzić surowy HTML, assety, nagłówki i cookies;
- wykryć CMS/framework oraz dostawcę hostingu/CDN, jeśli publicznie rozpoznawalny;
- oddzielić aktywne strony OSK od katalogów, agregatorów i nieaktywnych domen;
- dopisywać wyniki do tego samego dokumentu zamiast tworzyć równoległe raporty.
