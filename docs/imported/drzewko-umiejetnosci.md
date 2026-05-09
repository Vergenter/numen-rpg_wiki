# Drzewko umiejętności

[alt=Drzewo umiejętności\|mały\|Przykładowe drzewo
umiejętności](Plik:Przykładowe_drzewo_umiejętności.png "wikilink")
**Drzewko umiejętności** - reprezentacja [umiejętności](umiejetnosc.md)
posiadanych przez postać.

## Budowa

Drzewko umiejętności budowane jest z unikalnych
umiejętności(umiejętności nie mogą się powtarzać) przy użyciu
następujących wzorców

### Awans

[alt=Awans z ataku i siły na fechtunek dla ataku\|mały\|Przykład
awansu](Plik:Awans.png "wikilink")

#### Cel

Uzyskanie umiejętności z wyższego poziomu

#### Metoda

Podstawa awansu - umiejętność, albo grupa umiejętności stworzona w
wyniku użycia wzorca rozbudowa.

Dwie różne podstawy awansu, które są jednego poziomu, podpierają
umiejętność o jeden poziom wyższą.

Podstawami awansu nie może być grupa umiejętności i umiejętność z tej
grupy.

#### Zasady

<span id="Różnice podstaw">Różnice podstaw</span> - podstawy jak i
podstawy podstaw i tak dalej, muszą posiadać co najmniej dwie różne
podstawy. Za wyjątkiem umiejętności pierwszego poziomu.

Spełnienie wymagań umiejętności - umiejętności wyższych poziomów niż
pierwszy, muszą mieć w podstawach umiejętność dodającą tę samą
statystykę.

<span id="Tematyczność umiejętności">Tematyczność umiejętności</span> -
obie umiejętności muszą logicznie tłumaczyć zdobycie umiejętności
wyższego poziomu.

#### Uwagi

Wielokrotny awans - te same podstawy mogą służyć jako podstawa do awansu
dla wielu zdolności

### Rozbudowa

[alt=Przykład niżej zdefiniowanej specjalizacji\|mały\|Przykład
rozbudowy](Plik:Nowa_specjalizacja_notacja.png "wikilink")

#### Cel

rozbudowanie umiejętności o jej wariacje

#### Metoda

ze zdolności z wariacją i innej poziomu o 1 niższego można uzyskać wiele
wariacji

#### Zasady

[Różnice podstaw](#roznice-podstaw)

[Tematyczność umiejętności](#tematycznosc-umiejetnosci)

Dzielenie podstaw - wszystkie wariacje tej samej umiejętności dzielą
podstawy.

### Wzmacnianie statystyk

#### Cel

zwiększenie statystyki

#### Metoda

Dwie umiejętności jednego poziomu wzmacniają umiejętność na pierwszym
poziomie

#### Zasady

Każda zdolność może wzmacniać tylko raz.

Każda zdolność może być wzmacniana raz na poziom

Zdolność nie może wzmacniać samej siebie

[Różnice podstaw](#roznice-podstaw)

[Tematyczność umiejętności](#tematycznosc-umiejetnosci)

#### Uwagi

Na pierwszym poziomie wszystkie umiejętności są w stanie wzmacniać
wszystkie inne.

## Zaawansowane wykorzystanie wzorców

### Rozdzielenie podstaw

[alt=Rozdzielenie podstaw\|mały\|Przykład rozdzielenia
podstaw](Plik:Rozdzielenie_podstaw.png "wikilink")

#### Cel

umożliwienie awansu dla zdolności o tej samej podstawie

#### Metoda

wykorzystując zdolność uzyskaną ze wzorca Rozbudowa oraz innej zdolności
o wspólnej podstawie można uzyskać zdolność wyższego poziomu

#### Uwagi

musi spełniać zasady wykorzystanych wzorców
