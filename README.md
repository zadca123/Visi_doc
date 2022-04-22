
# Table of Contents

1.  [Ćwiczenia 1](#orgca6c5e1)
    1.  [Dokumentacja projektu](#orgd38a628)
    2.  [Projekt tablicy kanban](#org3d3bb18)
    3.  [Cel](#orge2c301d)
    4.  [Podział zespołów](#org65c46dd)
    5.  [Analiza ryzyka](#orgdb719c2)
        1.  [Prawdopodobieństwo](#orgd525834)
        2.  [Wpływ na projekt](#org6315286)
        3.  [Sposób ograniczenia ryzyka](#orgbbdee77)
        4.  [Reakcja](#orgbc9d735)
2.  [Ćwiczenia 2](#org223ae1c)
    1.  [Epic](#org7ff80d0)
    2.  [Feature](#org3af78f3)
    3.  [User story/task](#org5cb2dc8)
3.  [Ćwiczenia 3](#orgb235097)
    1.  [Analiza SWOT (dla opisu przypadku)](#org3d0daf5)
        1.  [Strenghts](#org235f138)
        2.  [Weakness](#org8009546)
        3.  [Occasions](#org83b52f0)
        4.  [Threats](#org1225104)
    2.  [Zadanie 2](#org5b868fc)
4.  [Ćwiczenia 4](#orgc12c00d)
    1.  [Schemat blokowy](#orgb4840d9)
        1.  [Zmiana hasła](#org5675dfb)
        2.  [Logowanie](#orgcd35387)
        3.  [Rejestacja](#org5be236f)
    2.  [Konflikty](#org8035f33)
        1.  [Przypadek 1](#orgf47705b)
        2.  [Przypadek 2](#org7c4db97)
        3.  [Przypadek 3](#orgfb3a005)
5.  [Ćwiczenia 5](#org3d5336b)
    1.  [Rejestr udziałowców](#org9d2e525)
6.  [Ćwiczenia 6](#orgb5d77fa)
    1.  [DoD (Definition of Done)](#orgd47d199)
    2.  [Kryteria akceptacji](#org5100e35)
7.  [Ćwiczenia 7](#org98adf0d)
    1.  [Burn up](#org8fb3eef)
    2.  [Burn down](#orgdd38e47)
8.  [Ćwiczenia 8](#org36c9988)
    1.  [Wymagania sprzętowe](#orgbdd032d)
    2.  [Instrukcja instalacji postregsql](#org1c8308b)
    3.  [Tworzenie bazy danych](#orge4968ef)
    4.  [Backup bazy danych](#org0cd00db)



<a id="orgca6c5e1"></a>

# Ćwiczenia 1


<a id="orgd38a628"></a>

## Dokumentacja projektu

Dokumentacja z zajęć z przedmiotu fakultatywnego, prowadzonego przez firmę Visimind.


<a id="org3d3bb18"></a>

## Projekt tablicy kanban

Na tworzenie aplikacji codziennie każdy powinien przeznaczyć 1,5h, a w czwartek dodatkowe 2,25h, ponieważ mamy planowo w tym czasie zajęcia przeznaczone do tworzenia tego projektu. Projekt i działająca aplikacja powinny być ukończone 25.05.2022r, więc mamy jako zespół 12 tygodni (117 godzin) pracy nad projektem.


<a id="orge2c301d"></a>

## Cel

Celem naszego projektu jest stworzenie działającej tablicy kanban, w której zadania będą przypisywane do osób, możliwe będą rejestracja i logowanie, ułożenie ich wg progresu danego zadania.


<a id="org65c46dd"></a>

## Podział zespołów

za front-end odpowiadają 2 osoby, za back-end 3 osoby, które znają biegle technologie, z których zdecydowaliśmy się korzystać.
W momencie pojawienia się problemów będziemy ustalać, kto zajmie się czymś dodatkowo. 
Kazdy swoje poszczególne zadania i terminy ma już przypisane na specjalnie założonej tablicy kanban.
Co tydzień w poniedziałek jest spotkanie, na którym kontrolujemy postęp i ustalamy czego jeszcze brakuje.


<a id="orgdb719c2"></a>

## Analiza ryzyka


<a id="orgd525834"></a>

### Prawdopodobieństwo

-   będzie tak dużo pracy własnej związanej ze studiami, że nie będziemy mogli poświęcić tak dużo czasu na tworzenie projektu.


<a id="org6315286"></a>

### Wpływ na projekt

-   Jest to najbardzej prawdopodobna możliwość, która opóźniłaby powstawanie aplikacji,


<a id="orgbbdee77"></a>

### Sposób ograniczenia ryzyka

-   dlatego jest zaplanowane codzienna praca, żeby teraz, póki semestr dopiero się zaczyna, zrobić więcej, ewentualnie szybciej skończyć. Jeżeli mimo to będą opóźnienia, to poszukamy pomocy, a jeżeli jej nie znajdziemy, to będziemy też poświęcać na to czas w sobotę i niedzielę.


<a id="orgbc9d735"></a>

### Reakcja

-   w przypadku choroby któregoś z współuczestników projektu, pozostałe osoby rozdzielą między siebie jego zadania, by nie opóźnić progresu, ale też by nie obciążyć znacznie większą ilością zadań tylko jednej osoby.

**\*zajęcia 04.03**


<a id="org223ae1c"></a>

# Ćwiczenia 2


<a id="org7ff80d0"></a>

## Epic

Aplikacja webowa tablicy kanban, w której zalogowani użytkownicy mogą planować swoje projekty rozbijając je na zadania i przypisując konkretne osoby i daty.


<a id="org3af78f3"></a>

## Feature

1.  w ciągu tygodni(?)
2.  zaloguj się 13
3.  Stwórz tablicę 50
4.  Dodaj kolumny i nazywaj je 13
5.  Stwórz zadania 8
6.  Dopisuj terminy do zadań 8
7.  Utwórz listę podzadań do zadania 20
8.  Przypisz zadania do poszczególnych osób z projektu 40
9.  Przenoś zadania między kolumnami 20
10. Wysyłaj powiadomienia o zmianach wprowadzonych przez pozostałych użytkowników tablicy 40


<a id="org5cb2dc8"></a>

## User story/task

-   ustalić technologie w których tworzymy projekt 1
-   podzielić się na front i back 1
-   zainicjować projekt 1
-   zainstalować pakiety 2
-   podpiąć bazę danych 5
    -   ****stworzyć:****
        -   modele 20
        -   views 13
        -   urls 13
        -   settings 8
-   Utworzyć index.html i pozostałe templatki 50
-   Stworzyć odpowiednie pliki js i css 50
-   Połączyć front i back 40


<a id="orgb235097"></a>

# Ćwiczenia 3


<a id="org3d0daf5"></a>

## Analiza SWOT (dla opisu przypadku)


<a id="org235f138"></a>

### Strenghts

-   senior w ekipie
-   zespół może płynnie pracować, bo najsłabsi mają się od kogo uczyć
-   w razie błędów senior może zareagować szybko
-   developerzy Full Stack
-   stały dochód
-   własne biuro i sprzęt
-   pozostałe osoby z firmy umożliwiające prawidłowe funkcjonowanie firmy


<a id="org8009546"></a>

### Weakness

-   dwóch juniorów
-   czy pracują osobno i każdy ma na głowie swój projekt czy współpracują przy tworzeniu projektów
-   praca stacjonarna
-   praca w małym mieście może oznaczać, że przyszli pracownicy będą musieli być wybierani z wąskiego grona chętnych
-   indywidualizm (ja w zespole)
-   w biurze mogą znajdować się przestarzałe komputery
-   możliwość odejścia seniora


<a id="org83b52f0"></a>

### Occasions

-   mała konkurencja w mieście
-   możliwość wyboru pracowników spośród potencjalnych kandydatów w mieście


<a id="org1225104"></a>

### Threats

-   lokalizacja biura (Morąg) może nie każdemu odpowiadać
-   zmieniające się podatki i regulacje prawne
-   brak możliwości rozwinięcia się w pracy nad dużym projektem


<a id="org5b868fc"></a>

## Zadanie 2

Harmonogram / Wykres Ganta
![img](./images/harmonogram.png)


<a id="orgc12c00d"></a>

# Ćwiczenia 4


<a id="orgb4840d9"></a>

## Schemat blokowy


<a id="org5675dfb"></a>

### Zmiana hasła

![img](./images/zmiana_hasla.drawio.svg)


<a id="orgcd35387"></a>

### Logowanie

![img](./images/logowanie.drawio.svg)


<a id="org5be236f"></a>

### Rejestacja

![img](./images/rejestracja.drawio.svg)


<a id="org8035f33"></a>

## Konflikty


<a id="orgf47705b"></a>

### Przypadek 1

> Piotr zachowuje się agresywnie w stosunku do innych uczestników.

-   Przeciwdziałania
    -   zapytać Piotra jaki jest powód jego agresji
    -   rozmowa z innymi członkami projektu na temat zaistniałej sytuacji i wytłumaczenie wszelkich niepewności
    -   zafundować wizytę u psychologa lub urlop
    -   zwolnić w razie konieczności


<a id="org7c4db97"></a>

### Przypadek 2

> Przełożony wymaga przygotowania demo, które nie było zaplanowane w sprincie co powoduje opóźnienie w projekcie.

-   Przeciwdziałania
    -   zrobić miejsce na demo kosztem jednego z punktów sprintu
    -   przekonać przełożonego, że strata wynikająca z niedotrzymania terminów jest większa niż z braku przygotowania demo
    -   poproszenie o przesunięcie dęadline'a projektu
    -   doprecyzowanie w jakim celu jest potrzebne wykonanie tego demo
    -   doprecyzowanie jakie efekty przyniesie realizacja dema, by zrozumiec jego potrzebę


<a id="orgfb3a005"></a>

### Przypadek 3

> Maciek jest wspaniałym analitykiem i jego wiedza pomogłaby w realizacji projektu. Niestety zespół z równolegle prowadzonego projektu rówhież potrzebuje jego wsparcia.

-   Przeciwdziałania
    -   zapytać Maćka czy jest w stanie nadzorować dwa projekty jednocześnie
    -   wydzielenie Maćkowi po dniu dla każdego zespołu
    -   zlecić pracę analityka z zewnątrz
    -   ustalenie który projekt jest ważniejszy
    -   ustalenie czasu poświęconego przez Maćka na każdy projekt


<a id="org3d5336b"></a>

# Ćwiczenia 5


<a id="org9d2e525"></a>

## Rejestr udziałowców

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-right" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-right">L.P.</th>
<th scope="col" class="org-left">Rodzaj</th>
<th scope="col" class="org-left">Nazwa</th>
<th scope="col" class="org-left">Opis</th>
<th scope="col" class="org-left">Rola</th>
<th scope="col" class="org-left">Oczekiwania</th>
<th scope="col" class="org-left">Wpływ</th>
<th scope="col" class="org-left">Komunikacja</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-right">1</td>
<td class="org-left">grupa</td>
<td class="org-left">administracja it</td>
<td class="org-left">administracja it</td>
<td class="org-left">przygotowanie infrastuktury</td>
<td class="org-left">przekazanie wymagań</td>
<td class="org-left">zapewnienie środowiska</td>
<td class="org-left">spotkania</td>
</tr>


<tr>
<td class="org-right">2</td>
<td class="org-left">grupa</td>
<td class="org-left">dewelperzy</td>
<td class="org-left">deweloperzy</td>
<td class="org-left">przygotowanie aplikacji</td>
<td class="org-left">przekazanie wymagań</td>
<td class="org-left">stworzenie aplikacji</td>
<td class="org-left">spotkania</td>
</tr>


<tr>
<td class="org-right">3</td>
<td class="org-left">osoba</td>
<td class="org-left">product owner</td>
<td class="org-left">product owner</td>
<td class="org-left">objaśnienie funkcji aplikacji (backlog)</td>
<td class="org-left">dostarczenie aplikacji</td>
<td class="org-left">objaśnienie deweloperom wymagań aplikacji</td>
<td class="org-left">spotkania</td>
</tr>


<tr>
<td class="org-right">4</td>
<td class="org-left">osoba</td>
<td class="org-left">project manager</td>
<td class="org-left">project manager</td>
<td class="org-left">nadzorowanie projektem</td>
<td class="org-left">zakończenie projektu w terminie</td>
<td class="org-left">rozwiązywanie problemów</td>
<td class="org-left">spotkania</td>
</tr>


<tr>
<td class="org-right">5</td>
<td class="org-left">organizacja</td>
<td class="org-left">firma zlecająca xyz</td>
<td class="org-left">firma zlecająca xyz</td>
<td class="org-left">wizjonerzy</td>
<td class="org-left">funkcjonalna aplikacja</td>
<td class="org-left">wysyła product ownera na rozmowy o aplikacji</td>
<td class="org-left">product</td>
</tr>


<tr>
<td class="org-right">6</td>
<td class="org-left">osoba</td>
<td class="org-left">prezes firmy xyz</td>
<td class="org-left">prezes firmy xyz</td>
<td class="org-left">sponsor</td>
<td class="org-left">funkcjonalna aplikacja</td>
<td class="org-left">wkład pieniężny</td>
<td class="org-left">product owner</td>
</tr>


<tr>
<td class="org-right">7</td>
<td class="org-left">organizacja</td>
<td class="org-left">UODO</td>
<td class="org-left">urząd ochrony danych osobowych</td>
<td class="org-left">monitorowanie</td>
<td class="org-left">zgodnosc z przepisami</td>
<td class="org-left">możlowiść nałożenia kar</td>
<td class="org-left">formalna</td>
</tr>


<tr>
<td class="org-right">8</td>
<td class="org-left">organizacja</td>
<td class="org-left">firma wykonująca xyz</td>
<td class="org-left">firma wykonująca xyz</td>
<td class="org-left">zespół produkcyjny</td>
<td class="org-left">zapłata</td>
<td class="org-left">dostarcza narzędzia oraz zespół do stworzenia aplikacji</td>
<td class="org-left">product manager</td>
</tr>
</tbody>
</table>


<a id="orgb5d77fa"></a>

# Ćwiczenia 6


<a id="orgd47d199"></a>

## DoD (Definition of Done)

    Dla portalu internetowego

-   Test ortografii
-   Test responsywności
-   Test czytelności
-   Czy wyświetla się w różnych przeglądarkach i systemach
-   Wszystkie testy jednostkowe zaliczone
-   Zaktualizowano rejestr produktów
-   Projekt wdrożony na środowisku testowym identycznym z platformą produkcyjną
-   Przeprowadzono testy na urządzeniach/przeglądarkach wymienionych w dokumentacji
-   Przeszły testy kompatybilności wstecznej
-   Testy wydajności przeszły pomyślnie
-   Naprawiono wszystkie błędy
-   Sprint oznaczony jako gotowy do wdrożenia produkcyjnego przez Właściciela Produktu


<a id="org5100e35"></a>

## Kryteria akceptacji

    indywidualne kryteria która musi spełnić każda poszczególna historyjka
    Dla przesyłania plików - Jako użytkownik chcę przesłać zdjęcie na serwer

-   możliwość drag'n'drop obrazka z przeglądarki plików do przeglądarki internetowej
-   opcja **Wybierz plik** pozwalająca przeszukiwać system
-   sprawdzenie typu pliku
-   poinformowanie użytkownika o niepoprawnym formacie pliku w razie wybrania innego typu niż obraz
-   możliwość pobrania obrazu z serwera
-   możliwość wyświetlenia obrazu na serwerze jako miniatura lub cały obraz
-   ustanowienie limitu wielkości pliku do xMB


<a id="org98adf0d"></a>

# Ćwiczenia 7


<a id="org8fb3eef"></a>

## Burn up

![img](./images/burn_up.png "Diagram Burn Up (chyba)")


<a id="orgdd38e47"></a>

## Burn down

![img](./images/burn_down.png "Diagram Burn Down (chyba)")


<a id="org36c9988"></a>

# Ćwiczenia 8


<a id="orgbdd032d"></a>

## Wymagania sprzętowe

<https://www.postgresql.org/docs/current/install-requirements.html>
<https://www.postgresql.org/message-id/m3k75ewlwa.fsf@wolfe.cbbrowne.com>


<a id="org1c8308b"></a>

## Instrukcja instalacji postregsql

Dystrybucje oparte na `Debianie`, czyli z manadzerem pakietów `apt`.

    sudo apt install postgresql

Po instalacji serwis/demon powinien rospocząć się automatycznie.

Sprawdzanie wersji zainstalowanej wersji

    apt list postgresql


<a id="orge4968ef"></a>

## Tworzenie bazy danych

1.  Otwórz terminal i uruchom poniższe polecenie, aby zalogować się do serwera PostgreSQL:
    
        sudo su postgres
2.  Teraz użyj poniższego polecenia, aby wejść do powłoki PostgreSQL:
    
        psql
3.  Stworz bazę *users* za pomocą:
    -   Wyświetl bazy danych
        
            \l
            SELECT current_database();
            CREATE DATABASE test;
            \connect test;
            SELECT current_database();
    -   Stwórz tabelę
        
            CREATE TABLE users(id SERIAL PRIMARY KEY,login VARCHAR(50), password VARCHAR(50));
    -   Wyświetl tabele
        
            \dt
    -   Wyświetl wszystkie rekordy z tabeli *users*
        
            SELECT * FROM users;
    -   Dodaj rekordy
        
            INSERT INTO users(login,password) VALUES('admin', 'admin');
            INSERT INTO users(login,password) VALUES('qwe', 'qwe');
            INSERT INTO users(login,password) VALUES('kaczka', 'eeee');


<a id="org0cd00db"></a>

## Backup bazy danych

-   Tworzenie
    Jest to bardzo prosta operacja, precyzujemy nazwę bazy do archiwizacji. W tym przypadku *test*.
    
        pg_dump test > testdb.backup
-   Przywrócenie
    Podobnie jak tworzenie, przywracanie działa analogicznie. Należy jednak wcześniej stworzyć bazę.
    
        psql
        CREATE DATABASE test;
    
    Importujemy za pomocą:
    
        psql test < testdb.backup
        psql
        \connect test
        SELECT * FROM users;

