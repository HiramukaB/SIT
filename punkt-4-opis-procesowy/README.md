# Punkt 4. Procesowy opis organizacji według ISO 9001

Opis przedstawia działalność MediHealth Sp. z o.o. przez procesy, a nie przez strukturę działów. Zgodnie z ISO 9001:2015 podejście procesowe pozwala lepiej zarządzać jakością, ryzykiem i ciągłym doskonaleniem. Pokazuje też, jak powstaje wartość dla pacjenta, jakie systemy IT wspierają poszczególne działania i gdzie mierzyć skuteczność. Opis jest podstawą do identyfikacji zasobów, zagrożeń i analizy ryzyka w kolejnych etapach projektu.

## Metodyka

1. Identyfikacja procesów i podział na główne (tworzące wartość dla pacjenta), wspierające i zarządcze.
2. Określenie celu każdego procesu.
3. Określenie wejść i wyjść procesu.
4. Wskazanie odpowiedzialności za realizację procesu.
5. Dobór mierników skuteczności (KPI).
6. Opis interakcji między procesami.
7. Powiązanie procesów z systemami IT z diagramu DFD (punkt 3).

## 1. Identyfikacja procesów

Procesy główne, tworzące wartość dla pacjenta:

- Rejestracja i obsługa pacjenta
- Świadczenie usług medycznych w placówkach
- Realizacja e-wizyt (telemedycyna)
- Prowadzenie elektronicznej dokumentacji medycznej (EDM)

Procesy wspierające:

- Rozliczenia i płatności
- Współpraca z partnerami zewnętrznymi (laboratorium, platforma P1, operator płatności)
- Zarządzanie infrastrukturą IT i bezpieczeństwem
- Zarządzanie personelem i kompetencjami

Procesy zarządcze:

- Planowanie strategiczne i cele biznesowe
- Monitorowanie i analiza wyników
- Zarządzanie ryzykiem, zgodnością i ciągłością działania

## 2. Mapa procesów organizacji

Mapa pokazuje przepływ wartości od zgłoszenia pacjenta do zrealizowanego świadczenia oraz procesy, które dostarczają zasobów i nadzorują całość.

| Poziom | Proces | Wejścia | Wyjścia | Systemy IT |
|---|---|---|---|---|
| Główny | Rejestracja i obsługa pacjenta | Potrzeba zdrowotna, dane pacjenta, grafik lekarzy | Umówiona wizyta lub e-wizyta, konto w portalu | Portal pacjenta, System HIS, Microsoft 365 |
| Główny | Świadczenie usług medycznych | Umówiona wizyta, historia leczenia, wyniki badań | Wykonane świadczenie, rozpoznanie, zlecenia, e-recepty | System HIS, Baza medyczna |
| Główny | Realizacja e-wizyt | Umówiona e-wizyta, wywiad i załączniki od pacjenta | Porada zdalna, e-recepta, zalecenia | Platforma e-wizyt, System HIS |
| Główny | Prowadzenie EDM | Wpisy z wizyt i e-wizyt, wyniki z laboratorium | Kompletna dokumentacja, dokumenty w portalu, zdarzenia w P1 | System HIS, Baza medyczna, Platforma P1 |
| Wspierający | Rozliczenia i płatności | Wykonane świadczenia, potwierdzenia płatności | Faktury, raporty finansowe | System billingowy, Operator płatności |
| Wspierający | Współpraca z partnerami | Zlecenia badań, dokumenty do P1, umowy | Wyniki badań, potwierdzenia z P1, statusy płatności | System HIS, Portal pacjenta |
| Wspierający | Zarządzanie IT i bezpieczeństwem | Wymagania biznesowe, zgłoszenia, alerty | Dostępne systemy, kopie zapasowe, obsłużone incydenty | Logi i SIEM, Kopie zapasowe, wszystkie systemy |
| Wspierający | Zarządzanie personelem | Plan zatrudnienia, wymagane kwalifikacje | Przeszkolony personel, nadane i odebrane uprawnienia | Microsoft 365 (Entra ID), System HIS |
| Zarządczy | Planowanie strategiczne | Cele biznesowe, wyniki, wymagania prawne | Strategia, cele roczne, budżet | Microsoft 365 |
| Zarządczy | Monitorowanie i analiza wyników | Mierniki ze wszystkich procesów, skargi, wyniki audytów | Raporty, decyzje, działania korygujące | Microsoft 365, System HIS |
| Zarządczy | Ryzyko, zgodność i ciągłość działania | Analiza ryzyka, incydenty, przepisy (RODO, KSC) | Plan postępowania z ryzykiem, zgłoszenia naruszeń, plan ciągłości | Logi i SIEM, Microsoft 365 |

Procesy główne tworzą bezpośrednią wartość dla pacjenta. Procesy wspierające zapewniają zasoby, dane i systemy. Procesy zarządcze wyznaczają cele i kontrolują skuteczność całego systemu.

## 3. Szczegółowy opis kluczowych procesów

### 3.1. Rejestracja i obsługa pacjenta

| Element | Opis |
|---|---|
| Cel procesu | Szybkie i bezpieczne umówienie pacjenta na wizytę lub e-wizytę oraz rzetelna obsługa jego spraw |
| Wejścia | Zgłoszenie pacjenta (portal, aplikacja, infolinia, recepcja), dane osobowe, grafik lekarzy, cennik, zgody pacjenta |
| Wyjścia | Umówiona wizyta lub e-wizyta, konto w portalu, potwierdzenia i przypomnienia, rozpatrzone skargi |
| Odpowiedzialność | Kierownik Obsługi Pacjenta, rejestracja i infolinia, portal pacjenta |
| Mierniki skuteczności | Satysfakcja pacjentów (≥ 4,5/5), liczba skarg (≤ 2 na 1000 wizyt), czas oczekiwania na połączenie z infolinią (≤ 2 min) |

### 3.2. Świadczenie usług medycznych w placówkach

| Element | Opis |
|---|---|
| Cel procesu | Bezpieczne i skuteczne udzielanie świadczeń zdrowotnych zgodnie ze standardami medycznymi |
| Wejścia | Umówiona wizyta, historia leczenia i wyniki badań z EDM, procedury medyczne, sprawna aparatura |
| Wyjścia | Wykonane świadczenie, rozpoznanie i zalecenia, zlecenia badań, e-recepty i e-skierowania, wpis do EDM |
| Odpowiedzialność | Dyrektor Medyczny, lekarze i pielęgniarki, kierownicy placówek, system HIS |
| Mierniki skuteczności | Wizyty rozpoczęte do 15 min od planowanej godziny (≥ 90%), liczba zdarzeń niepożądanych, czas oczekiwania na wizytę u specjalisty |

### 3.3. Realizacja e-wizyt (telemedycyna)

| Element | Opis |
|---|---|
| Cel procesu | Udzielanie porad zdalnych z zachowaniem poufności i jakości porównywalnej z wizytą w placówce |
| Wejścia | Umówiona e-wizyta, wywiad i załączniki od pacjenta, historia leczenia z EDM |
| Wyjścia | Porada zdalna, e-recepta lub e-skierowanie, zalecenia, wpis do EDM |
| Odpowiedzialność | Koordynator Telemedycyny, lekarze prowadzący e-wizyty, platforma e-wizyt |
| Mierniki skuteczności | E-wizyty zakończone bez zerwania połączenia (≥ 98%), dostępność platformy (≥ 99,9% miesięcznie), satysfakcja pacjentów z e-wizyt (≥ 4,5/5) |

### 3.4. Prowadzenie elektronicznej dokumentacji medycznej

| Element | Opis |
|---|---|
| Cel procesu | Kompletna, poprawna i chroniona dokumentacja medyczna, dostępna dla uprawnionych osób przez wymagany okres |
| Wejścia | Wpisy z wizyt i e-wizyt, wyniki z laboratorium, wnioski pacjentów o udostępnienie dokumentacji |
| Wyjścia | Podpisana dokumentacja w EDM, dokumenty udostępnione w portalu, zdarzenia medyczne i indeksy w P1, archiwum przez 20 lat |
| Odpowiedzialność | Dyrektor Medyczny, Kierownik Działu Dokumentacji Medycznej, personel medyczny, system HIS |
| Mierniki skuteczności | Kompletność EDM w audycie losowej próby (≥ 98%), wyniki badań udostępnione w portalu do 24 h od zatwierdzenia (≥ 95%), zdarzenia przesłane do P1 bez błędów (≥ 99%) |

### 3.5. Rozliczenia i płatności

| Element | Opis |
|---|---|
| Cel procesu | Prawidłowe rozliczanie świadczeń, wystawianie faktur i kontrola płatności |
| Wejścia | Wykonane świadczenia z HIS, cennik, potwierdzenia płatności od operatora, dane pacjentów |
| Wyjścia | Faktury, potwierdzenia płatności, raporty finansowe, rozliczenia z partnerami |
| Odpowiedzialność | Dyrektor Finansowy, dział finansowy, rejestracja (płatności na miejscu), system billingowy |
| Mierniki skuteczności | Faktury wystawione do 1 dnia roboczego od świadczenia (≥ 98%), płatności online zakończone powodzeniem (≥ 97%), należności przeterminowane powyżej 30 dni |

### 3.6. Zarządzanie infrastrukturą IT i bezpieczeństwem

| Element | Opis |
|---|---|
| Cel procesu | Ciągła dostępność systemów medycznych i ochrona danych pacjentów przed utratą, wyciekiem i atakami |
| Wejścia | Wymagania biznesowe i prawne, zgłoszenia użytkowników, alerty z SIEM, wyniki analizy ryzyka |
| Wyjścia | Działające systemy, kopie zapasowe, obsłużone incydenty, wdrożone zmiany i poprawki |
| Odpowiedzialność | Kierownik IT, administratorzy IT, Inspektor Ochrony Danych, dostawcy usług IT |
| Mierniki skuteczności | Dostępność HIS i portalu (≥ 99,9% miesięcznie), udane testy odtworzenia kopii (100% testów), krytyczne poprawki wdrożone w ciągu 14 dni (≥ 95%) |

## 4. Interakcje między procesami

Numery w nawiasach wskazują przepływy z diagramu DFD (punkt 3.3).

1. Pacjent umawia wizytę lub e-wizytę w portalu, a rejestracja zapisuje termin w HIS (1, 2).
2. Lekarz udziela świadczenia w placówce lub podczas e-wizyty i dokumentuje je w EDM (3, 4, 5, 6).
3. Zlecenia badań trafiają do laboratorium, a wyniki wracają do HIS i do portalu pacjenta (7, 2).
4. E-recepty, e-skierowania i zdarzenia medyczne są przekazywane do platformy P1 (8).
5. Wykonane świadczenia przechodzą do systemu billingowego, a operator płatności potwierdza transakcje (9, 10, 11).
6. Procesy IT i bezpieczeństwa zapewniają ciągłość i ochronę danych we wszystkich pozostałych procesach (16, 17, 18, 19).
7. Monitorowanie wyników zbiera mierniki ze wszystkich procesów i przekazuje je do planowania strategicznego oraz zarządzania ryzykiem.

## 5. Wymagania wynikające z ISO 9001

- Cele jakościowe powiązane z celami biznesowymi CB1 do CB5: ciągłość działania 24/7, ochrona danych pacjentów, zgodność z przepisami.
- Monitorowanie i pomiar procesów za pomocą mierników skuteczności.
- Zarządzanie ryzykiem i szansami w każdym procesie.
- Udokumentowane procesy, odpowiedzialności i uprawnienia.
- Ciągłe doskonalenie na podstawie wyników mierników, skarg pacjentów i audytów.

Opis procesowy jest podstawą do dalszych etapów projektu: architektury IT, klasyfikacji informacji, identyfikacji zasobów i analizy ryzyka. Wskazuje powiązania między procesami biznesowymi MediHealth a systemami informatycznymi organizacji.
