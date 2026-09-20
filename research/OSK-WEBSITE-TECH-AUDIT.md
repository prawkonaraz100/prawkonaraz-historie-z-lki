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


---

# 8. Przebieg ogólnopolski — pokrycie 16 województw

Drugi przebieg rozszerza badanie z luźnej próbki na **systematyczne pokrycie całej Polski**. Jednostką pokrycia jest województwo, a punktem startowym miasta wojewódzkie oraz duże ośrodki egzaminacyjne. To nadal nie oznacza, że każda istniejąca domena OSK została już odnaleziona: oficjalny rejestr działalności regulowanej prowadzony jest przez właściwych starostów/prezydentów miast, a nie jako jedna kompletna lista domen internetowych.

| Województwo | Miasta / obszary objęte wyszukiwaniem | Przykładowy aktywny serwis OSK znaleziony w przebiegu | Stan |
|---|---|---|---|
| dolnośląskie | Wrocław | https://drivewars.pl/ | pokryte |
| kujawsko-pomorskie | Bydgoszcz, Toruń, Inowrocław | https://inowroclawosk.pl/ | pokryte |
| lubelskie | Lublin, Opole Lubelskie | https://luz.lublin.pl/ ; https://dario-lublin.pl/ ; https://www.naukajazdy.ns48.pl/ | pokryte |
| lubuskie | Zielona Góra, Gorzów Wlkp. | wyszukiwanie wykonane; lista domen wymaga dalszej enumeracji | pokryte wyszukiwaniem |
| łódzkie | Łódź | wyszukiwanie wykonane; lista domen wymaga dalszej enumeracji | pokryte wyszukiwaniem |
| małopolskie | Kraków, Niepołomice, Chrzanów | https://www.osknavigator.pl/ ; https://makart.pl/ | pokryte |
| mazowieckie | Warszawa, Radzymin | https://warszawa.szkola-oes.pl/ ; https://osk.malibu.auto.pl/ ; https://www.osk-classic.pl/ | pokryte |
| opolskie | Opole, Kluczbork | https://ocsk.pl/ ; https://oskopole.pl/ ; https://www.osk-atut.pl/ | pokryte |
| podkarpackie | Rzeszów, Krosno, Jasło, Sanok, Tarnobrzeg | https://www.zubrzycki.osk.info.pl/ ; https://duetosk.pl/ ; https://www.naukajazdy-upiotra.pl/ | pokryte |
| podlaskie | Białystok | https://szal.bialystok.pl/ | pokryte |
| pomorskie | Gdańsk, Gdynia | https://osklevelgdansk.pl/ ; https://www.osk-oskar.pl/ | pokryte |
| śląskie | Katowice, Cieszyn, Skoczów | https://www.osk.katowice.pl/ ; https://lbrudny.pl/osk/ | pokryte |
| świętokrzyskie | Kielce, Ostrowiec Świętokrzyski | https://dobrejazdy.pl/ ; https://superkursy.com.pl/ | pokryte |
| warmińsko-mazurskie | Olsztyn | https://www.jkk.olsztyn.pl/ | pokryte |
| wielkopolskie | Poznań i powiat poznański | https://www.osk.poznan.pl/ | pokryte |
| zachodniopomorskie | Szczecin | https://oskar.szczecin.pl/ ; https://oskbisszczecin.pl/ | pokryte |

## Oficjalne źródło populacji OSK

Dla kompletnej enumeracji nie wystarczy wyszukiwarka. Rejestry przedsiębiorców prowadzących OSK są jawne i prowadzone przez właściwych starostów / prezydentów miast. Przykłady znalezione w tym przebiegu:

- Kielce: miejski wykaz OSK wskazuje również centralny serwis rejestrowy PWPW `starosta.osk.pwpw.pl`;
- Wrocław: BIP podaje bezpośredni rejestr OSK w systemie PWPW;
- Poznań: miejski BIP publikuje jawny rejestr OSK, a powiat poznański publikuje aktualizowane wykazy;
- Białystok: BIP prowadzi jawny rejestr przedsiębiorców prowadzących OSK;
- Szczecin: e-Urząd publikuje szczegółowy rejestr wraz z biurem, salą, placem, kategoriami i pojazdami.

**Wniosek metodologiczny:** aby uczciwie nazwać wynik „cała Polska”, trzeba najpierw wyciągnąć populację OSK z rejestrów administracyjnych dla wszystkich powiatów/miast na prawach powiatu, a dopiero później dla każdego podmiotu odnaleźć domenę i sklasyfikować technologię. Sam Google/Bing nie daje gwarancji kompletności.

---

# 9. Nowe serwisy i klasyfikacje z przebiegu ogólnopolskiego

## WordPress — dodatkowo potwierdzone

### MAKART — Chrzanów
- URL: https://makart.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: liczne zasoby `/wp-content/uploads/`.

### OSK DUET — Krosno / Jasło / Sanok
- URL: https://duetosk.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: materiały wideo i media pod `/wp-content/uploads/`.

### Superkursy / powiązane ośrodki — Ostrowiec Świętokrzyski
- URL: https://superkursy.com.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: aktualności i obrazy pod `/wp-content/uploads/`.

### OSK Michał
- URL: https://www.oskmichal.pl/
- Technologia: **WordPress**
- Pewność: **wysoka**
- Dowód: publiczny kod treści zawiera shortcode'y buildera oraz media `/wp-content/uploads/`.

## Joomla — potwierdzone

### OSK Tomasz Kocon — Opole Lubelskie
- URL: https://www.naukajazdy.ns48.pl/index.php
- Technologia: **Joomla**
- Pewność: **bardzo wysoka**
- Dowód: publicznie indeksowana strona zawiera jawny ślad modułu „google maps module for joomla 3”.

### NOT — Ośrodek Szkolenia Kierowców — Opole
- Technologia historycznie wykryta: **Joomla**
- Pewność: **wysoka dla zindeksowanej wersji**
- Dowód: zindeksowany opis serwisu zawiera jawne „joomla! - the dynamic portal engine and content management system”.
- Uwaga: przed zaliczeniem do aktualnie aktywnych domen trzeba ponownie zweryfikować bieżący adres strony; wynik pochodzi z profilu/katalogu szkoły.

---

# 10. Aktualny bilans technologii

| Technologia | Potwierdzone przykłady | Stan dowodowy |
|---|---:|---|
| WordPress | **12** | bezpośrednie ślady WP w publicznych zasobach |
| Wix | **1** | bezpośrednie assety Wix |
| Joomla | **1 aktywna domena + 1 historycznie wykryty serwis** | jawne sygnatury Joomla |
| Custom / inny CMS / framework | jeszcze bez uczciwego potwierdzenia | wymaga inspekcji |
| Nierozpoznane | wiele | nie przypisujemy technologii bez dowodu |

Liczby nie są jeszcze udziałem procentowym całego rynku. Są liczbą **potwierdzonych technologicznie przypadków** w obecnym audycie.

---

# 11. Kryterium ukończenia „całej Polski”

Audyt można oznaczyć jako **COMPLETE — POLSKA** dopiero, gdy spełnione będą łącznie:

1. zebrane zostaną aktualne rejestry OSK ze wszystkich powiatów i miast na prawach powiatu albo równoważny kompletny zbiór PWPW;
2. każdy aktywny podmiot zostanie znormalizowany i zdeduplikowany;
3. dla każdego podmiotu zostanie ustalone: `ma stronę / brak strony / strona nieaktywna / domena nierozpoznana`;
4. każda aktywna domena zostanie sprawdzona technicznie;
5. technologia będzie przypisana tylko z dowodem;
6. wynik będzie zawierał licznik pokrycia: `sklasyfikowane / wszystkie aktywne domeny`;
7. dopiero przy 100% rozpoznanych domen lub jawnie opisanych wyjątkach dokument zmieni status na COMPLETE.

**Aktualny status: IN PROGRESS — wszystkie 16 województw objęte wyszukiwaniem, ale enumeracja wszystkich powiatowych rejestrów i wszystkich domen jeszcze nie jest kompletna.**
