
# Table of Contents

1.  [Ćwiczenia 1](#org85c12d7)
    1.  [Dokumentacja projektu](#org64a735f)
    2.  [Projekt tablicy kanban](#orgec31dc5)
    3.  [Cel](#org2d50e68)
    4.  [Podział zespołów](#org2fcb312)
    5.  [Analiza ryzyka](#orgdbfbf01)
        1.  [Prawdopodobieństwo](#org239c5af)
        2.  [Wpływ na projekt](#orgf9efb28)
        3.  [Sposób ograniczenia ryzyka](#org8f71f7a)
        4.  [Reakcja](#org44872cc)
2.  [Ćwiczenia 2](#org81c71e5)
    1.  [Epic](#org241b0d5)
    2.  [Feature](#org698817b)
    3.  [User story/task](#org54bb22f)
3.  [Ćwiczenia 3](#org7a0f447)
    1.  [Analiza SWOT (dla opisu przypadku)](#orgac4ecfb)
        1.  [Strenghts](#org0bc40fa)
        2.  [Weakness](#orgd05ddbb)
        3.  [Occasions](#orga1a952d)
        4.  [Threats](#orgf054080)
    2.  [Zadanie 2](#org8e325e2)
4.  [Ćwiczenia 4](#org858fb31)
    1.  [Schemat blokowy](#org6c1c7b5)
        1.  [Zmiana hasła](#orgd78d253)
        2.  [Logowanie](#org9db5b17)
        3.  [Rejestacja](#orgc54e885)
    2.  [Konflikty](#orgfdf31bc)
        1.  [Przypadek 1](#org75ce6a9)
        2.  [Przypadek 2](#orgcbe13dd)
        3.  [Przypadek 3](#org3ee400b)
5.  [Ćwiczenia 5](#org828a6d1)
    1.  [Rejestr udziałowców](#orgc15c3a1)
6.  [Ćwiczenia 6](#org5758dc1)
    1.  [DoD (Definition of Done)](#org4111547)
    2.  [Kryteria akceptacji](#org1b5ea71)
7.  [Ćwiczenia 7](#orgf3ffa1d)
    1.  [Burn up](#orgd6109b9)
    2.  [Burn down](#org71f5b7f)
8.  [Ćwiczenia 8](#org9ca0fca)
    1.  [Wymagania sprzętowe](#org1a88ffa)
    2.  [Instrukcja instalacji postregsql](#org1d85c05)
    3.  [Tworzenie bazy danych](#org974b6fe)
    4.  [Backup bazy danych](#orge6d9a45)
9.  [Ćwiczenia 9](#org10327d5)
    1.  [Zadanie 1](#orge40a4a4)
        1.  [Wyższy](#org7774215)
        2.  [Średni](#org8edaa18)
        3.  [Operacyjny](#orge356aac)
    2.  [Zadanie 2](#orgf7cb414)
10. [Ćwiczenie 10](#org42f8515)
    1.  [Plan komunikacji](#org9a6768f)



<a id="org85c12d7"></a>

# Ćwiczenia 1


<a id="org64a735f"></a>

## Dokumentacja projektu

Dokumentacja z zajęć z przedmiotu fakultatywnego, prowadzonego przez firmę Visimind.


<a id="orgec31dc5"></a>

## Projekt tablicy kanban

Na tworzenie aplikacji codziennie każdy powinien przeznaczyć 1,5h, a w czwartek dodatkowe 2,25h, ponieważ mamy planowo w tym czasie zajęcia przeznaczone do tworzenia tego projektu. Projekt i działająca aplikacja powinny być ukończone 25.05.2022r, więc mamy jako zespół 12 tygodni (117 godzin) pracy nad projektem.


<a id="org2d50e68"></a>

## Cel

Celem naszego projektu jest stworzenie działającej tablicy kanban, w której zadania będą przypisywane do osób, możliwe będą rejestracja i logowanie, ułożenie ich wg progresu danego zadania.


<a id="org2fcb312"></a>

## Podział zespołów

za front-end odpowiadają 2 osoby, za back-end 3 osoby, które znają biegle technologie, z których zdecydowaliśmy się korzystać.
W momencie pojawienia się problemów będziemy ustalać, kto zajmie się czymś dodatkowo. 
Kazdy swoje poszczególne zadania i terminy ma już przypisane na specjalnie założonej tablicy kanban.
Co tydzień w poniedziałek jest spotkanie, na którym kontrolujemy postęp i ustalamy czego jeszcze brakuje.


<a id="orgdbfbf01"></a>

## Analiza ryzyka


<a id="org239c5af"></a>

### Prawdopodobieństwo

-   będzie tak dużo pracy własnej związanej ze studiami, że nie będziemy mogli poświęcić tak dużo czasu na tworzenie projektu.


<a id="orgf9efb28"></a>

### Wpływ na projekt

-   Jest to najbardzej prawdopodobna możliwość, która opóźniłaby powstawanie aplikacji,


<a id="org8f71f7a"></a>

### Sposób ograniczenia ryzyka

-   dlatego jest zaplanowane codzienna praca, żeby teraz, póki semestr dopiero się zaczyna, zrobić więcej, ewentualnie szybciej skończyć. Jeżeli mimo to będą opóźnienia, to poszukamy pomocy, a jeżeli jej nie znajdziemy, to będziemy też poświęcać na to czas w sobotę i niedzielę.


<a id="org44872cc"></a>

### Reakcja

-   w przypadku choroby któregoś z współuczestników projektu, pozostałe osoby rozdzielą między siebie jego zadania, by nie opóźnić progresu, ale też by nie obciążyć znacznie większą ilością zadań tylko jednej osoby.

**\*zajęcia 04.03**


<a id="org81c71e5"></a>

# Ćwiczenia 2


<a id="org241b0d5"></a>

## Epic

Aplikacja webowa tablicy kanban, w której zalogowani użytkownicy mogą planować swoje projekty rozbijając je na zadania i przypisując konkretne osoby i daty.


<a id="org698817b"></a>

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


<a id="org54bb22f"></a>

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


<a id="org7a0f447"></a>

# Ćwiczenia 3


<a id="orgac4ecfb"></a>

## Analiza SWOT (dla opisu przypadku)


<a id="org0bc40fa"></a>

### Strenghts

-   senior w ekipie
-   zespół może płynnie pracować, bo najsłabsi mają się od kogo uczyć
-   w razie błędów senior może zareagować szybko
-   developerzy Full Stack
-   stały dochód
-   własne biuro i sprzęt
-   pozostałe osoby z firmy umożliwiające prawidłowe funkcjonowanie firmy


<a id="orgd05ddbb"></a>

### Weakness

-   dwóch juniorów
-   czy pracują osobno i każdy ma na głowie swój projekt czy współpracują przy tworzeniu projektów
-   praca stacjonarna
-   praca w małym mieście może oznaczać, że przyszli pracownicy będą musieli być wybierani z wąskiego grona chętnych
-   indywidualizm (ja w zespole)
-   w biurze mogą znajdować się przestarzałe komputery
-   możliwość odejścia seniora


<a id="orga1a952d"></a>

### Occasions

-   mała konkurencja w mieście
-   możliwość wyboru pracowników spośród potencjalnych kandydatów w mieście


<a id="orgf054080"></a>

### Threats

-   lokalizacja biura (Morąg) może nie każdemu odpowiadać
-   zmieniające się podatki i regulacje prawne
-   brak możliwości rozwinięcia się w pracy nad dużym projektem


<a id="org8e325e2"></a>

## Zadanie 2

Harmonogram / Wykres Ganta
![img](./images/harmonogram.png)


<a id="org858fb31"></a>

# Ćwiczenia 4


<a id="org6c1c7b5"></a>

## Schemat blokowy


<a id="orgd78d253"></a>

### Zmiana hasła

![img](./images/zmiana_hasla.drawio.svg)


<a id="org9db5b17"></a>

### Logowanie

![img](./images/logowanie.drawio.svg)


<a id="orgc54e885"></a>

### Rejestacja

![img](./images/rejestracja.drawio.svg)


<a id="orgfdf31bc"></a>

## Konflikty


<a id="org75ce6a9"></a>

### Przypadek 1

> Piotr zachowuje się agresywnie w stosunku do innych uczestników.

-   Przeciwdziałania
    -   zapytać Piotra jaki jest powód jego agresji
    -   rozmowa z innymi członkami projektu na temat zaistniałej sytuacji i wytłumaczenie wszelkich niepewności
    -   zafundować wizytę u psychologa lub urlop
    -   zwolnić w razie konieczności


<a id="orgcbe13dd"></a>

### Przypadek 2

> Przełożony wymaga przygotowania demo, które nie było zaplanowane w sprincie co powoduje opóźnienie w projekcie.

-   Przeciwdziałania
    -   zrobić miejsce na demo kosztem jednego z punktów sprintu
    -   przekonać przełożonego, że strata wynikająca z niedotrzymania terminów jest większa niż z braku przygotowania demo
    -   poproszenie o przesunięcie dęadline'a projektu
    -   doprecyzowanie w jakim celu jest potrzebne wykonanie tego demo
    -   doprecyzowanie jakie efekty przyniesie realizacja dema, by zrozumiec jego potrzebę


<a id="org3ee400b"></a>

### Przypadek 3

> Maciek jest wspaniałym analitykiem i jego wiedza pomogłaby w realizacji projektu. Niestety zespół z równolegle prowadzonego projektu rówhież potrzebuje jego wsparcia.

-   Przeciwdziałania
    -   zapytać Maćka czy jest w stanie nadzorować dwa projekty jednocześnie
    -   wydzielenie Maćkowi po dniu dla każdego zespołu
    -   zlecić pracę analityka z zewnątrz
    -   ustalenie który projekt jest ważniejszy
    -   ustalenie czasu poświęconego przez Maćka na każdy projekt


<a id="org828a6d1"></a>

# Ćwiczenia 5


<a id="orgc15c3a1"></a>

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


<a id="org5758dc1"></a>

# Ćwiczenia 6


<a id="org4111547"></a>

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


<a id="org1b5ea71"></a>

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


<a id="orgf3ffa1d"></a>

# Ćwiczenia 7


<a id="orgd6109b9"></a>

## Burn up

![img](./images/burn_up.png "Diagram Burn Up (chyba)")


<a id="org71f5b7f"></a>

## Burn down

![img](./images/burn_down.png "Diagram Burn Down (chyba)")


<a id="org9ca0fca"></a>

# Ćwiczenia 8


<a id="org1a88ffa"></a>

## Wymagania sprzętowe

<https://www.postgresql.org/docs/current/install-requirements.html>
<https://www.postgresql.org/message-id/m3k75ewlwa.fsf@wolfe.cbbrowne.com>


<a id="org1d85c05"></a>

## Instrukcja instalacji postregsql

Dystrybucje oparte na `Debianie`, czyli z manadzerem pakietów `apt`.

    sudo apt install postgresql

Po instalacji serwis/demon powinien rospocząć się automatycznie.

Sprawdzanie wersji zainstalowanej wersji

    apt list postgresql


<a id="org974b6fe"></a>

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


<a id="orge6d9a45"></a>

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


<a id="org10327d5"></a>

# Ćwiczenia 9


<a id="orge40a4a4"></a>

## Zadanie 1

odpowiedzialność prawna, zarządcza, za organizowanie funkcji, ogarnięcie celów, regulaminu, kontrolowanie regulaminów
sr - 
planowanie operacyjne, nieobecności, org zastępstw, 


<a id="org7774215"></a>

### Wyższy

-   **rada nadzorcza, prezes zarzadu:** reguluje funkcjonowanie osoby prawnej oraz jej statut w oprarciu o właściwe przepisy prawne, przyznawanie określonych uprawnień w zakresie kierowania pracami zarządu


<a id="org8edaa18"></a>

### Średni

-   **dyrektorzy, kierownicy:** koordynacja menedżerów niższego szczebla, pełnienie funkcji zgodnie z postanowieniami umowy spółki, statutu lub innymi obowiązującymi jednostkę przepisami prawa


<a id="orge356aac"></a>

### Operacyjny

-   **brygadziści, team leaderzy:** przydzielanie zadań, planowanie zastępst, planowanie operacyjne, organizacja zastępstw, wykonywanie zleceń dyrekcji niższego szczebla


<a id="orgf7cb414"></a>

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


<a id="org42f8515"></a>

# Ćwiczenie 10


<a id="org9a6768f"></a>

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

