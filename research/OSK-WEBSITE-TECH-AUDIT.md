# Lista technologii stron OSK — przekazanie dla kolejnego agenta

> **Cel pliku:** operacyjna lista wejściowa. Bez analiz rynku, opisów stron, wniosków, benchmarków i narracji.
>
> **Zasada:** jeden serwis = dokładnie trzy pola: URL, Technologia, Dowód.
>
> **Nie zgaduj technologii.** Jeśli nie ma technicznego dowodu, wpisz `Nierozpoznana` i opisz, czego brakuje.
>
> **Stan:** lista nie jest jeszcze kompletna dla całej Polski. Kolejny agent ma ją rozszerzać aż do sklasyfikowania wszystkich odnalezionych aktywnych domen OSK.

## Potwierdzone

### 1
URL: https://inowroclawosk.pl/  
Technologia: WordPress  
Dowód: publiczne obrazy są serwowane z `/wp-content/uploads/`.

### 2
URL: https://osk.malibu.auto.pl/  
Technologia: WordPress  
Dowód: publiczne zasoby są serwowane z `/wp-content/uploads/`.

### 3
URL: https://drivewars.pl/  
Technologia: WordPress  
Dowód: publiczne zasoby graficzne są serwowane z `/wp-content/uploads/`.

### 4
URL: https://dobrejazdy.pl/  
Technologia: WordPress  
Dowód: publiczne media i logo są serwowane z `/wp-content/uploads/`.

### 5
URL: https://www.osknavigator.pl/  
Technologia: WordPress  
Dowód: publiczne obrazy ofertowe są serwowane z `/wp-content/uploads/`.

### 6
URL: https://lbrudny.pl/osk/  
Technologia: WordPress  
Dowód: publiczne media są serwowane z `/wp-content/uploads/`.

### 7
URL: https://warszawa.szkola-oes.pl/  
Technologia: WordPress  
Dowód: publiczne treści i media są serwowane z `/wp-content/uploads/`.

### 8
URL: https://autoq.pl/  
Technologia: WordPress  
Dowód: publiczna strona zawierała jawną stopkę `Powered by WordPress`.

### 9
URL: https://www.osk-atut.pl/  
Technologia: Wix  
Dowód: publiczne assety strony są serwowane z infrastruktury `static.wixstatic.com`.

### 10
URL: https://makart.pl/  
Technologia: WordPress  
Dowód: publiczne zasoby są serwowane z `/wp-content/uploads/`.

### 11
URL: https://duetosk.pl/  
Technologia: WordPress  
Dowód: publiczne media są serwowane z `/wp-content/uploads/`.

### 12
URL: https://superkursy.com.pl/  
Technologia: WordPress  
Dowód: publiczne obrazy i aktualności wykorzystują zasoby z `/wp-content/uploads/`.

### 13
URL: https://www.oskmichal.pl/  
Technologia: WordPress  
Dowód: publiczny kod/treść zawiera ślady buildera WordPress oraz zasoby z `/wp-content/uploads/`.

### 14
URL: https://www.4-kolka.pl/  
Technologia: WordPress  
Dowód: publiczny materiał wideo jest serwowany z `/wp-content/uploads/2021/10/Katowicka.mp4`.

### 15
URL: https://www.naukajazdy.ns48.pl/index.php  
Technologia: Joomla  
Dowód: publicznie indeksowana strona zawiera jawny ślad modułu opisanego jako `google maps module for joomla 3`.

### 16
URL: https://szybkibill.net/  
Technologia: WordPress  
Dowód: publiczne dokumenty są serwowane z `/wp-content/uploads/2025/10/`. cite: turn1search0

### 17
URL: https://naukajazdy360.pl/  
Technologia: Joomla  
Dowód: publiczna strona renderuje komunikat modułu `OS Responsive Image Gallery Joomla module`. cite: turn0search9

## Historycznie potwierdzone — wymagają ponownej kontroli aktualnego stanu

### H1
URL: http://www.oskdanuta.pl/  
Technologia: WordPress  
Dowód: wcześniejszy publiczny audyt zasobów wykrywał `/wp-content/themes/`, `/wp-content/uploads/` oraz WordPress 4.7.12.

## Nierozpoznane — do sprawdzenia

### N1
URL: https://www.osk-classic.pl/  
Technologia: Nierozpoznana  
Dowód: brak wystarczającego technicznego śladu CMS/frameworka w dotychczasowym przebiegu.

### N2
URL: https://www.osk-kurzawa.pl/  
Technologia: Nierozpoznana  
Dowód: poprzednie pełne pobranie strony zakończyło się timeoutem; należy ponowić inspekcję HTML, assetów i nagłówków.

### N3
URL: https://www.zubrzycki.osk.info.pl/  
Technologia: Nierozpoznana  
Dowód: domena została odnaleziona, ale dotychczas nie potwierdzono publicznego śladu konkretnego CMS/frameworka.

### N4
URL: http://www.mikrus.net/  
Technologia: Nierozpoznana  
Dowód: domena OSK została odnaleziona w publicznym katalogu; technologia nie została jeszcze technicznie zweryfikowana.

### N5
URL: http://www.l-kierowca.pl/  
Technologia: Nierozpoznana  
Dowód: domena OSK została odnaleziona w publicznym katalogu; technologia nie została jeszcze technicznie zweryfikowana.

### N6
URL: http://www.oskjagodzinski.pl/  
Technologia: Nierozpoznana  
Dowód: domena OSK została odnaleziona w publicznym katalogu; technologia nie została jeszcze technicznie zweryfikowana.

## Format obowiązkowy dla kolejnych wpisów

```text
URL: https://domena.pl/
Technologia: WordPress
Dowód: publiczne zasoby są serwowane z /wp-content/uploads/.
```

Nie dodawaj opisu oferty, lokalizacji, charakteru strony, wniosków marketingowych ani rekomendacji. Ten plik ma być maszynowo i szybko czytelny dla kolejnego agenta.
