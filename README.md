
# Table of Contents

1.  [Ćwiczenia 1](#org77be820)
    1.  [Dokumentacja projektu](#org5ae0c47)
    2.  [Projekt tablicy kanban](#orgba5d442)
    3.  [Cel](#org7ecf698)
    4.  [Podział zespołów](#org662483f)
    5.  [Analiza ryzyka](#orgccc994e)
        1.  [Prawdopodobieństwo](#orgf021907)
        2.  [Wpływ na projekt](#orgb28d91f)
        3.  [Sposób ograniczenia ryzyka](#org537ac5d)
        4.  [Reakcja](#org2689b0c)
2.  [Ćwiczenia 2](#org3fe3862)
    1.  [Epic](#orgad50ea8)
    2.  [Feature](#orgaf366e8)
    3.  [User story/task](#org46857bb)
3.  [Ćwiczenia 3](#orgd911e60)
    1.  [Analiza SWOT (dla opisu przypadku)](#org40e5e1b)
        1.  [Strenghts](#org6fd2dd3)
        2.  [Weakness](#orgd45ec3b)
        3.  [Occasions](#org3575829)
        4.  [Threats](#org650b2ea)
    2.  [Zadanie 2](#org6e8cc97)
4.  [Ćwiczenia 4](#orgac723d6)
    1.  [Schemat blokowy](#orgc53d07f)
        1.  [Zmiana hasła](#orgb8bfb97)
        2.  [Logowanie](#orgd8f4218)
        3.  [Rejestacja](#org4161550)
    2.  [Konflikty](#orgcd23a63)
        1.  [Przypadek 1](#org970b092)
        2.  [Przypadek 2](#org4985f5b)
        3.  [Przypadek 3](#org94af3e3)
5.  [Ćwiczenia 5](#org4d62983)
    1.  [Rejestr udziałowców](#org5d777a6)
6.  [Ćwiczenia 6](#orge4f071a)
    1.  [DoD (Definition of Done)](#org8f06e08)
    2.  [Kryteria akceptacji](#org6141ed7)
7.  [Ćwiczenia 7](#orgeaa950c)
    1.  [Burn up](#org5666f4c)
    2.  [Burn down](#org15d5eb4)
8.  [Ćwiczenia 8](#org1ea6a36)
    1.  [Wymagania sprzętowe](#orgab40d29)
    2.  [Instrukcja instalacji postregsql](#orgc0c6eaa)
    3.  [Tworzenie bazy danych](#org5e4d78f)
    4.  [Backup bazy danych](#orgba6622a)
9.  [Ćwiczenia 9](#org00ab91f)
    1.  [Zadanie 1](#org9e21750)
        1.  [Wyższy](#org0b789a2)
        2.  [Średni](#org2940c00)
        3.  [Operacyjny](#orge9b26c3)
    2.  [Zadanie 2](#org3754b65)



<a id="org77be820"></a>

# Ćwiczenia 1


<a id="org5ae0c47"></a>

## Dokumentacja projektu

Dokumentacja z zajęć z przedmiotu fakultatywnego, prowadzonego przez firmę Visimind.


<a id="orgba5d442"></a>

## Projekt tablicy kanban

Na tworzenie aplikacji codziennie każdy powinien przeznaczyć 1,5h, a w czwartek dodatkowe 2,25h, ponieważ mamy planowo w tym czasie zajęcia przeznaczone do tworzenia tego projektu. Projekt i działająca aplikacja powinny być ukończone 25.05.2022r, więc mamy jako zespół 12 tygodni (117 godzin) pracy nad projektem.


<a id="org7ecf698"></a>

## Cel

Celem naszego projektu jest stworzenie działającej tablicy kanban, w której zadania będą przypisywane do osób, możliwe będą rejestracja i logowanie, ułożenie ich wg progresu danego zadania.


<a id="org662483f"></a>

## Podział zespołów

za front-end odpowiadają 2 osoby, za back-end 3 osoby, które znają biegle technologie, z których zdecydowaliśmy się korzystać.
W momencie pojawienia się problemów będziemy ustalać, kto zajmie się czymś dodatkowo. 
Kazdy swoje poszczególne zadania i terminy ma już przypisane na specjalnie założonej tablicy kanban.
Co tydzień w poniedziałek jest spotkanie, na którym kontrolujemy postęp i ustalamy czego jeszcze brakuje.


<a id="orgccc994e"></a>

## Analiza ryzyka


<a id="orgf021907"></a>

### Prawdopodobieństwo

-   będzie tak dużo pracy własnej związanej ze studiami, że nie będziemy mogli poświęcić tak dużo czasu na tworzenie projektu.


<a id="orgb28d91f"></a>

### Wpływ na projekt

-   Jest to najbardzej prawdopodobna możliwość, która opóźniłaby powstawanie aplikacji,


<a id="org537ac5d"></a>

### Sposób ograniczenia ryzyka

-   dlatego jest zaplanowane codzienna praca, żeby teraz, póki semestr dopiero się zaczyna, zrobić więcej, ewentualnie szybciej skończyć. Jeżeli mimo to będą opóźnienia, to poszukamy pomocy, a jeżeli jej nie znajdziemy, to będziemy też poświęcać na to czas w sobotę i niedzielę.


<a id="org2689b0c"></a>

### Reakcja

-   w przypadku choroby któregoś z współuczestników projektu, pozostałe osoby rozdzielą między siebie jego zadania, by nie opóźnić progresu, ale też by nie obciążyć znacznie większą ilością zadań tylko jednej osoby.

**\*zajęcia 04.03**


<a id="org3fe3862"></a>

# Ćwiczenia 2


<a id="orgad50ea8"></a>

## Epic

Aplikacja webowa tablicy kanban, w której zalogowani użytkownicy mogą planować swoje projekty rozbijając je na zadania i przypisując konkretne osoby i daty.


<a id="orgaf366e8"></a>

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


<a id="org46857bb"></a>

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


<a id="orgd911e60"></a>

# Ćwiczenia 3


<a id="org40e5e1b"></a>

## Analiza SWOT (dla opisu przypadku)


<a id="org6fd2dd3"></a>

### Strenghts

-   senior w ekipie
-   zespół może płynnie pracować, bo najsłabsi mają się od kogo uczyć
-   w razie błędów senior może zareagować szybko
-   developerzy Full Stack
-   stały dochód
-   własne biuro i sprzęt
-   pozostałe osoby z firmy umożliwiające prawidłowe funkcjonowanie firmy


<a id="orgd45ec3b"></a>

### Weakness

-   dwóch juniorów
-   czy pracują osobno i każdy ma na głowie swój projekt czy współpracują przy tworzeniu projektów
-   praca stacjonarna
-   praca w małym mieście może oznaczać, że przyszli pracownicy będą musieli być wybierani z wąskiego grona chętnych
-   indywidualizm (ja w zespole)
-   w biurze mogą znajdować się przestarzałe komputery
-   możliwość odejścia seniora


<a id="org3575829"></a>

### Occasions

-   mała konkurencja w mieście
-   możliwość wyboru pracowników spośród potencjalnych kandydatów w mieście


<a id="org650b2ea"></a>

### Threats

-   lokalizacja biura (Morąg) może nie każdemu odpowiadać
-   zmieniające się podatki i regulacje prawne
-   brak możliwości rozwinięcia się w pracy nad dużym projektem


<a id="org6e8cc97"></a>

## Zadanie 2

Harmonogram / Wykres Ganta
![img](./images/harmonogram.png)


<a id="orgac723d6"></a>

# Ćwiczenia 4


<a id="orgc53d07f"></a>

## Schemat blokowy


<a id="orgb8bfb97"></a>

### Zmiana hasła

![img](./images/zmiana_hasla.drawio.svg)


<a id="orgd8f4218"></a>

### Logowanie

![img](./images/logowanie.drawio.svg)


<a id="org4161550"></a>

### Rejestacja

![img](./images/rejestracja.drawio.svg)


<a id="orgcd23a63"></a>

## Konflikty


<a id="org970b092"></a>

### Przypadek 1

> Piotr zachowuje się agresywnie w stosunku do innych uczestników.

-   Przeciwdziałania
    -   zapytać Piotra jaki jest powód jego agresji
    -   rozmowa z innymi członkami projektu na temat zaistniałej sytuacji i wytłumaczenie wszelkich niepewności
    -   zafundować wizytę u psychologa lub urlop
    -   zwolnić w razie konieczności


<a id="org4985f5b"></a>

### Przypadek 2

> Przełożony wymaga przygotowania demo, które nie było zaplanowane w sprincie co powoduje opóźnienie w projekcie.

-   Przeciwdziałania
    -   zrobić miejsce na demo kosztem jednego z punktów sprintu
    -   przekonać przełożonego, że strata wynikająca z niedotrzymania terminów jest większa niż z braku przygotowania demo
    -   poproszenie o przesunięcie dęadline'a projektu
    -   doprecyzowanie w jakim celu jest potrzebne wykonanie tego demo
    -   doprecyzowanie jakie efekty przyniesie realizacja dema, by zrozumiec jego potrzebę


<a id="org94af3e3"></a>

### Przypadek 3

> Maciek jest wspaniałym analitykiem i jego wiedza pomogłaby w realizacji projektu. Niestety zespół z równolegle prowadzonego projektu rówhież potrzebuje jego wsparcia.

-   Przeciwdziałania
    -   zapytać Maćka czy jest w stanie nadzorować dwa projekty jednocześnie
    -   wydzielenie Maćkowi po dniu dla każdego zespołu
    -   zlecić pracę analityka z zewnątrz
    -   ustalenie który projekt jest ważniejszy
    -   ustalenie czasu poświęconego przez Maćka na każdy projekt


<a id="org4d62983"></a>

# Ćwiczenia 5


<a id="org5d777a6"></a>

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


<a id="orge4f071a"></a>

# Ćwiczenia 6


<a id="org8f06e08"></a>

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


<a id="org6141ed7"></a>

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


<a id="orgeaa950c"></a>

# Ćwiczenia 7


<a id="org5666f4c"></a>

## Burn up

![img](./images/burn_up.png "Diagram Burn Up (chyba)")


<a id="org15d5eb4"></a>

## Burn down

![img](./images/burn_down.png "Diagram Burn Down (chyba)")


<a id="org1ea6a36"></a>

# Ćwiczenia 8


<a id="orgab40d29"></a>

## Wymagania sprzętowe

<https://www.postgresql.org/docs/current/install-requirements.html>
<https://www.postgresql.org/message-id/m3k75ewlwa.fsf@wolfe.cbbrowne.com>


<a id="orgc0c6eaa"></a>

## Instrukcja instalacji postregsql

Dystrybucje oparte na `Debianie`, czyli z manadzerem pakietów `apt`.

    sudo apt install postgresql

Po instalacji serwis/demon powinien rospocząć się automatycznie.

Sprawdzanie wersji zainstalowanej wersji

    apt list postgresql


<a id="org5e4d78f"></a>

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


<a id="orgba6622a"></a>

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


<a id="org00ab91f"></a>

# Ćwiczenia 9


<a id="org9e21750"></a>

## Zadanie 1

odpowiedzialność prawna, zarządcza, za organizowanie funkcji, ogarnięcie celów, regulaminu, kontrolowanie regulaminów
sr - 
planowanie operacyjne, nieobecności, org zastępstw, 


<a id="org0b789a2"></a>

### Wyższy

-   **rada nadzorcza, prezes zarzadu:** reguluje funkcjonowanie osoby prawnej oraz jej statut w oprarciu o właściwe przepisy prawne, przyznawanie określonych uprawnień w zakresie kierowania pracami zarządu


<a id="org2940c00"></a>

### Średni

-   **dyrektorzy, kierownicy:** koordynacja menedżerów niższego szczebla, pełnienie funkcji zgodnie z postanowieniami umowy spółki, statutu lub innymi obowiązującymi jednostkę przepisami prawa


<a id="orge9b26c3"></a>

### Operacyjny

-   **brygadziści, team leaderzy:** przydzielanie zadań, planowanie zastępst, planowanie operacyjne, organizacja zastępstw, wykonywanie zleceń dyrekcji niższego szczebla


<a id="org3754b65"></a>

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

