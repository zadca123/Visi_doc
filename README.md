
# Table of Contents

1.  [Ćwiczenia 1](#orgdd0cd1d)
    1.  [Dokumentacja projektu](#org394a779)
    2.  [Projekt tablicy kanban](#org9444176)
    3.  [Cel](#org5358ee3)
    4.  [Podział zespołów](#org2dffec8)
    5.  [Analiza ryzyka](#org35f223b)
        1.  [Prawdopodobieństwo](#orgb6f13dc)
        2.  [Wpływ na projekt](#orgb28a41a)
        3.  [Sposób ograniczenia ryzyka](#orgcdb1d62)
        4.  [Reakcja](#orgdb9f43e)
2.  [Ćwiczenia 2](#orgbba5df0)
    1.  [Epic](#org52264c7)
    2.  [Feature](#org7e94438)
    3.  [User story/task](#orgff2f5cc)
3.  [Ćwiczenia 3](#orgc294c8d)
    1.  [Analiza SWOT (dla opisu przypadku)](#orgaa3bf3b)
        1.  [Strenghts](#org3579c49)
        2.  [Weakness](#orgc462136)
        3.  [Occasions](#orgef16ebc)
        4.  [Threats](#org3501185)
    2.  [Zadanie 2](#org8a7f684)
4.  [Ćwiczenia 4](#org9c920a7)
    1.  [Schemat blokowy](#orgdb12238)
        1.  [Zmiana hasła](#org26e5696)
        2.  [Logowanie](#org2342d0f)
        3.  [Rejestacja](#orga3e170f)
    2.  [Konflikty](#org8ab5e6a)
        1.  [Przypadek 1](#org263e76d)
        2.  [Przypadek 2](#org4d300d9)
        3.  [Przypadek 3](#org8256994)
5.  [Ćwiczenia 5](#org5974d32)
    1.  [Rejestr udziałowców](#org0f2a4c0)
6.  [Ćwiczenia 6](#org5fc6685)
    1.  [DoD (Definition of Done)](#org801234f)
    2.  [Kryteria akceptacji](#orgbe0230a)
7.  [Ćwiczenia 7](#org0781a5f)
    1.  [Burn up](#org4a70eb3)
    2.  [Burn down](#orgf06e83f)
8.  [Ćwiczenia 8](#org1810f34)
    1.  [Wymagania sprzętowe](#orgc2a4cbf)
    2.  [Instrukcja instalacji postregsql](#org625b0e1)
    3.  [Tworzenie bazy danych](#org9d795df)
    4.  [Backup bazy danych](#org86a771c)
9.  [Ćwiczenia 9](#orgfff83f0)
    1.  [Zadanie 1](#org99ce594)
        1.  [Wyższy](#orgbc54c5b)
        2.  [Średni](#orge2e1485)
        3.  [Operacyjny](#orgf260bd0)
    2.  [Zadanie 2](#orgef62996)
10. [Ćwiczenie 10](#org15f1905)
    1.  [Plan komunikacji](#org27d702e)
11. [Ćwiczenie 11](#org51d5112)
    1.  [Hashe](#org2b59d03)



<a id="orgdd0cd1d"></a>

# Ćwiczenia 1


<a id="org394a779"></a>

## Dokumentacja projektu

Dokumentacja z zajęć z przedmiotu fakultatywnego, prowadzonego przez firmę Visimind.


<a id="org9444176"></a>

## Projekt tablicy kanban

Na tworzenie aplikacji codziennie każdy powinien przeznaczyć 1,5h, a w czwartek dodatkowe 2,25h, ponieważ mamy planowo w tym czasie zajęcia przeznaczone do tworzenia tego projektu. Projekt i działająca aplikacja powinny być ukończone 25.05.2022r, więc mamy jako zespół 12 tygodni (117 godzin) pracy nad projektem.


<a id="org5358ee3"></a>

## Cel

Celem naszego projektu jest stworzenie działającej tablicy kanban, w której zadania będą przypisywane do osób, możliwe będą rejestracja i logowanie, ułożenie ich wg progresu danego zadania.


<a id="org2dffec8"></a>

## Podział zespołów

za front-end odpowiadają 2 osoby, za back-end 3 osoby, które znają biegle technologie, z których zdecydowaliśmy się korzystać.
W momencie pojawienia się problemów będziemy ustalać, kto zajmie się czymś dodatkowo. 
Kazdy swoje poszczególne zadania i terminy ma już przypisane na specjalnie założonej tablicy kanban.
Co tydzień w poniedziałek jest spotkanie, na którym kontrolujemy postęp i ustalamy czego jeszcze brakuje.


<a id="org35f223b"></a>

## Analiza ryzyka


<a id="orgb6f13dc"></a>

### Prawdopodobieństwo

-   będzie tak dużo pracy własnej związanej ze studiami, że nie będziemy mogli poświęcić tak dużo czasu na tworzenie projektu.


<a id="orgb28a41a"></a>

### Wpływ na projekt

-   Jest to najbardzej prawdopodobna możliwość, która opóźniłaby powstawanie aplikacji,


<a id="orgcdb1d62"></a>

### Sposób ograniczenia ryzyka

-   dlatego jest zaplanowane codzienna praca, żeby teraz, póki semestr dopiero się zaczyna, zrobić więcej, ewentualnie szybciej skończyć. Jeżeli mimo to będą opóźnienia, to poszukamy pomocy, a jeżeli jej nie znajdziemy, to będziemy też poświęcać na to czas w sobotę i niedzielę.


<a id="orgdb9f43e"></a>

### Reakcja

-   w przypadku choroby któregoś z współuczestników projektu, pozostałe osoby rozdzielą między siebie jego zadania, by nie opóźnić progresu, ale też by nie obciążyć znacznie większą ilością zadań tylko jednej osoby.

**\*zajęcia 04.03**


<a id="orgbba5df0"></a>

# Ćwiczenia 2


<a id="org52264c7"></a>

## Epic

Aplikacja webowa tablicy kanban, w której zalogowani użytkownicy mogą planować swoje projekty rozbijając je na zadania i przypisując konkretne osoby i daty.


<a id="org7e94438"></a>

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


<a id="orgff2f5cc"></a>

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


<a id="orgc294c8d"></a>

# Ćwiczenia 3


<a id="orgaa3bf3b"></a>

## Analiza SWOT (dla opisu przypadku)


<a id="org3579c49"></a>

### Strenghts

-   senior w ekipie
-   zespół może płynnie pracować, bo najsłabsi mają się od kogo uczyć
-   w razie błędów senior może zareagować szybko
-   developerzy Full Stack
-   stały dochód
-   własne biuro i sprzęt
-   pozostałe osoby z firmy umożliwiające prawidłowe funkcjonowanie firmy


<a id="orgc462136"></a>

### Weakness

-   dwóch juniorów
-   czy pracują osobno i każdy ma na głowie swój projekt czy współpracują przy tworzeniu projektów
-   praca stacjonarna
-   praca w małym mieście może oznaczać, że przyszli pracownicy będą musieli być wybierani z wąskiego grona chętnych
-   indywidualizm (ja w zespole)
-   w biurze mogą znajdować się przestarzałe komputery
-   możliwość odejścia seniora


<a id="orgef16ebc"></a>

### Occasions

-   mała konkurencja w mieście
-   możliwość wyboru pracowników spośród potencjalnych kandydatów w mieście


<a id="org3501185"></a>

### Threats

-   lokalizacja biura (Morąg) może nie każdemu odpowiadać
-   zmieniające się podatki i regulacje prawne
-   brak możliwości rozwinięcia się w pracy nad dużym projektem


<a id="org8a7f684"></a>

## Zadanie 2

Harmonogram / Wykres Ganta
![img](./images/harmonogram.png)


<a id="org9c920a7"></a>

# Ćwiczenia 4


<a id="orgdb12238"></a>

## Schemat blokowy


<a id="org26e5696"></a>

### Zmiana hasła

![img](./images/zmiana_hasla.drawio.svg)


<a id="org2342d0f"></a>

### Logowanie

![img](./images/logowanie.drawio.svg)


<a id="orga3e170f"></a>

### Rejestacja

![img](./images/rejestracja.drawio.svg)


<a id="org8ab5e6a"></a>

## Konflikty


<a id="org263e76d"></a>

### Przypadek 1

> Piotr zachowuje się agresywnie w stosunku do innych uczestników.

-   Przeciwdziałania
    -   zapytać Piotra jaki jest powód jego agresji
    -   rozmowa z innymi członkami projektu na temat zaistniałej sytuacji i wytłumaczenie wszelkich niepewności
    -   zafundować wizytę u psychologa lub urlop
    -   zwolnić w razie konieczności


<a id="org4d300d9"></a>

### Przypadek 2

> Przełożony wymaga przygotowania demo, które nie było zaplanowane w sprincie co powoduje opóźnienie w projekcie.

-   Przeciwdziałania
    -   zrobić miejsce na demo kosztem jednego z punktów sprintu
    -   przekonać przełożonego, że strata wynikająca z niedotrzymania terminów jest większa niż z braku przygotowania demo
    -   poproszenie o przesunięcie dęadline'a projektu
    -   doprecyzowanie w jakim celu jest potrzebne wykonanie tego demo
    -   doprecyzowanie jakie efekty przyniesie realizacja dema, by zrozumiec jego potrzebę


<a id="org8256994"></a>

### Przypadek 3

> Maciek jest wspaniałym analitykiem i jego wiedza pomogłaby w realizacji projektu. Niestety zespół z równolegle prowadzonego projektu rówhież potrzebuje jego wsparcia.

-   Przeciwdziałania
    -   zapytać Maćka czy jest w stanie nadzorować dwa projekty jednocześnie
    -   wydzielenie Maćkowi po dniu dla każdego zespołu
    -   zlecić pracę analityka z zewnątrz
    -   ustalenie który projekt jest ważniejszy
    -   ustalenie czasu poświęconego przez Maćka na każdy projekt


<a id="org5974d32"></a>

# Ćwiczenia 5


<a id="org0f2a4c0"></a>

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


<a id="org5fc6685"></a>

# Ćwiczenia 6


<a id="org801234f"></a>

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


<a id="orgbe0230a"></a>

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


<a id="org0781a5f"></a>

# Ćwiczenia 7


<a id="org4a70eb3"></a>

## Burn up

![img](./images/burn_up.png "Diagram Burn Up (chyba)")


<a id="orgf06e83f"></a>

## Burn down

![img](./images/burn_down.png "Diagram Burn Down (chyba)")


<a id="org1810f34"></a>

# Ćwiczenia 8


<a id="orgc2a4cbf"></a>

## Wymagania sprzętowe

<https://www.postgresql.org/docs/current/install-requirements.html>
<https://www.postgresql.org/message-id/m3k75ewlwa.fsf@wolfe.cbbrowne.com>


<a id="org625b0e1"></a>

## Instrukcja instalacji postregsql

Dystrybucje oparte na `Debianie`, czyli z manadzerem pakietów `apt`.

    sudo apt install postgresql

Po instalacji serwis/demon powinien rospocząć się automatycznie.

Sprawdzanie wersji zainstalowanej wersji

    apt list postgresql


<a id="org9d795df"></a>

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


<a id="org86a771c"></a>

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


<a id="orgfff83f0"></a>

# Ćwiczenia 9


<a id="org99ce594"></a>

## Zadanie 1

odpowiedzialność prawna, zarządcza, za organizowanie funkcji, ogarnięcie celów, regulaminu, kontrolowanie regulaminów
sr - 
planowanie operacyjne, nieobecności, org zastępstw, 


<a id="orgbc54c5b"></a>

### Wyższy

-   **rada nadzorcza, prezes zarzadu:** reguluje funkcjonowanie osoby prawnej oraz jej statut w oprarciu o właściwe przepisy prawne, przyznawanie określonych uprawnień w zakresie kierowania pracami zarządu


<a id="orge2e1485"></a>

### Średni

-   **dyrektorzy, kierownicy:** koordynacja menedżerów niższego szczebla, pełnienie funkcji zgodnie z postanowieniami umowy spółki, statutu lub innymi obowiązującymi jednostkę przepisami prawa


<a id="orgf260bd0"></a>

### Operacyjny

-   **brygadziści, team leaderzy:** przydzielanie zadań, planowanie zastępst, planowanie operacyjne, organizacja zastępstw, wykonywanie zleceń dyrekcji niższego szczebla


<a id="orgef62996"></a>

## Zadanie 2

-   Spotkanie z zespołem
    -   Ustalenie na czym skupi się spotkanie.
    -   Ustalić, co chce się osiągnąć, zakładając spotkanie.
    -   Ustalić, co chce się, aby ludzie wynieśli ze spotkania.
    -   Poinformować uczestników o miejscu i czasie spotkania.
    -   Ustalić czy czas i miejsce pasują uczestnikom spotkania.
    -   Stworzyć harmonogram spotania.
    -   Przygotować materiały niezbędne do spotkania.
    -   Opisać cele spotkania według sporządzonego wcześniej harmonogramu.


<a id="org15f1905"></a>

# Ćwiczenie 10


<a id="org27d702e"></a>

## Plan komunikacji

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Uczestnik</th>
<th scope="col" class="org-left">Sposób komunikacji</th>
<th scope="col" class="org-left">Częstotliwość</th>
<th scope="col" class="org-left">Notatki</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">technik IT</td>
<td class="org-left">tickety</td>
<td class="org-left">przy interwencji działu IT</td>
<td class="org-left">każdy ticket otrzymuje odpowiedź</td>
</tr>


<tr>
<td class="org-left">użytkownik</td>
<td class="org-left">formularz</td>
<td class="org-left">przy wykonaniu zleceń</td>
<td class="org-left">formularz w formie elektronicznej</td>
</tr>


<tr>
<td class="org-left">UODO</td>
<td class="org-left">formularz, pismo</td>
<td class="org-left">przy incydentach ochrony praw osobowych</td>
<td class="org-left">pisma w formie elektronicznej</td>
</tr>


<tr>
<td class="org-left">grafik</td>
<td class="org-left">raport</td>
<td class="org-left">przy wykonaniu zleceń</td>
<td class="org-left">spotkania osobiste lub online na platformie google meets</td>
</tr>


<tr>
<td class="org-left">kierownik projektu</td>
<td class="org-left">spotkanie osobiste</td>
<td class="org-left">codzienne spotkania</td>
<td class="org-left">daily scrum</td>
</tr>


<tr>
<td class="org-left">programista</td>
<td class="org-left">spotkania zdalne</td>
<td class="org-left">codzienne spotkania</td>
<td class="org-left">daily scrum</td>
</tr>


<tr>
<td class="org-left">tester</td>
<td class="org-left">raport</td>
<td class="org-left">przy testowaniu funkcjonalności</td>
<td class="org-left">złożenie raportu podczas wykrycia błędów</td>
</tr>


<tr>
<td class="org-left">właściciel sklepu</td>
<td class="org-left">prezentacje, raporty, spotkania</td>
<td class="org-left">przy realizacji etapów</td>
<td class="org-left">spotkania online</td>
</tr>
</tbody>
</table>


<a id="org51d5112"></a>

# Ćwiczenie 11


<a id="org2b59d03"></a>

## Hashe

<./images/kot_postrach_wszystkich_dzieci.bmp>

-   **hash256:** 9489ECCC9541BA0BDA7792D3535EEC979B778185D5C66277D9BDA3BEDDB2AFAF

<./images/zmieniony_kot.bmp>

-   **hash256:** 57FF0DD1793A89F7400C5642F222FE1F30EDEB6DCF27E2A0647CFED303D2A0B6

