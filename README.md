**TASK 1**
===============
Subtask 1

8/10 pkt

Subtask 3
Testowanie to coś czym interesuję się już od jakiegoś czasu. Zdecydowałam się na udział w wyzwaniu by poznać temat od praktycznej strony. 

Wierzę że poznam tu dobre praktyki które stanowiły będą bazę dla mojego dalszego rozwoju.

Subtask 4
Aplikacja służy do zarządzania profilami graczy, jest w niej także możliwość:

*tworzenia zapisów meczy wraz z dokładnym uzupełnieniem przeprowadzonych przez gracza akcji

*tworzenie opisowych raportów na temat zawodników

*przegądanie statystyk

*uzupełnienie profili graczy o zewnętrzne źródła (np. linki youtube. facebook, łączy nas piłka)

Wygląd aplikacji
Aplikacja jest prosta, zawiera minimum kolorów, grafik.
 
Co można zmienić?
-formularz gracza wygląda dość przytłaczająco - może warto podzielić dane na podstawowe i szczególy (jedne na górze, drugie na dole albo mniej istotne wrzucić do podstrony ze szczegółami)
-dodanie zdjęcia gracza w profilu znacznie wpłynęło by na wygląd strony
-w zakładcze "GRACZE" brakuje mi opcji dodaj gracza, szkoda że trzeba wracać do głównej strony by móc to zrobić


Błędem moim zdaniem jest brak walidacji w polu wagi zawodnika - można wprowadzić wartość ujemną

Task 2
=======
Subtask 1


https://docs.google.com/spreadsheets/d/1ftmMGKrdu8bxxfup2r8frxTgIXvudrhAJwVNmJ7g60c/edit#gid=0


Substask 2


https://docs.google.com/spreadsheets/d/1VSGYbe0m-PLeX4cDvV2Ms62GGXc8_bnBdfOzrvy-u4o/edit#gid=0


Subtask 3


Po co nam test case'y?
===========

[![marihuaninem](https://dareit.notion.site/image/https%3A%2F%2Fi.ytimg.com%2Fvi%2FOO3FANjwKHY%2Fhqdefault.jpg?table=block&id=59550964-8c6a-4d91-b424-c1994a2c2a1c&spaceId=732f0b1c-c96d-43d6-bb4c-c4556b1e2cd1&width=500&userId=&cache=v2)](https://www.youtube.com/watch?v=OO3FANjwKHY&t=1s)

[a komu to potrzebne](https://www.youtube.com/watch?v=OO3FANjwKHY&t=1s)

Przypadki testowe moim zdaniem w prosty sposób opowiadają o funkcjonalnosciach, dostepnych opcjach w aplikacji i sposobie ich działania. Czytając je można szybko poznać założenia aplikacji, jej przeznaczenie i dostępne dla uzytkownika opcje.


Subtask 4


https://docs.google.com/spreadsheets/d/1RcxiOCg1h_O_dJcYrzs5Qx1vKZNgiTcGGL63zI2hRA0/edit#gid=0


Task 3
=========

Subtask 1


https://docs.google.com/spreadsheets/d/1_UJ1hDGv4lDh9Wr5trY2DDC6N0YBHViEkloqpG4wkYc/edit#gid=0


Subtask 3

https://docs.google.com/spreadsheets/d/18RrmgXjuWb7Eww_BylPqu5zyFEXc5qjqBVM1KRFXdx0/edit#gid=0


Task 4
=========

Subtask 2

https://docs.google.com/spreadsheets/d/1fYNK12yV-Ttdx6frxoQo8sfMBfKyfOG82QlwRDf3OSk/edit#gid=0

Subtask 3


1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji? 


Aplikacja zawiera treści wspierające zdrowie mentalne, samoświadomość. rozwój, świadome oddychanie za pośrednictwem np. medytacji, odpowedniej muzyki, treściom stworzonym przez ekspertów z tego zakresu.


3. Kto ma być użytkownikiem końcowym aplikacji?


Osoby fizyczne czujące potrzebę zmiany w swoim życiu, chcące skupić się na sobie (swojej psychice, uważności)


3. Czy według Ciebie aplikacja jest user friendly?  


W moim odczuciu jest dosyć ciężka, mnogość opcji, ogromny wybór trochę mnie przytłaczał. Jednocześnie ciężko było mi znaleźć czytelny podział na jasno sprecyzowane kategorie.


4. Jak byś usprawnił aplikację? Co byś w niej poprawił. 


Wprowadziłabym jasny podział na dobrze opisane kategorie.


5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej?


Na tym etapie nie dostrzegam znaczących róźnic.


TAKSK 5
=========

Subtask 1

SELECT

WHERE

ORDER BY

ALL/ANY

AND

NOT

JOIN




Subtask 3

<b>1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.</b>

SELECT * FROM actors ORDER BY surname;
<img width="312" alt="Zrzut ekranu 2022-11-29 o 22 05 59" src="https://user-images.githubusercontent.com/116260341/204647549-9f879c87-29bd-4f0a-8613-6eca4300ffdd.png">


2. Wyświetl film, który powstał w 2019 roku.

SELECT * FROM `movies` WHERE `year_of_production`=2019;
<img width="393" alt="Zrzut ekranu 2022-11-29 o 22 10 25" src="https://user-images.githubusercontent.com/116260341/204648246-044a0259-c900-462e-a6ce-ebfa5ced0e76.png">

3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

SELECT * FROM `movies` WHERE `year_of_production`BETWEEN 1900 AND 1999;
<img width="504" alt="Zrzut ekranu 2022-11-29 o 22 12 48" src="https://user-images.githubusercontent.com/116260341/204648718-924258f6-897d-4f49-ad6b-7cf9fb90c1aa.png">

4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$ 
SELECT title,price FROM movies WHERE price<7;
<img width="310" alt="Zrzut ekranu 2022-11-29 o 22 30 11" src="https://user-images.githubusercontent.com/116260341/204651954-bd901a1a-04d5-480d-8a04-a8966f2361ea.png">

5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (4 i 7 powinny się wyświetlać). NIE UŻYWAJ operatora BETWEEN.
SELECT * FROM actors WHERE actor_id > 3 and actor_id < 8;
<img width="397" alt="Zrzut ekranu 2022-11-29 o 22 37 28" src="https://user-images.githubusercontent.com/116260341/204653302-7ea1069e-3f10-4619-9123-aaf8b1cbc01d.png">

6. Wyświetl klientów o id 2,4,6 wykorzystaj do tego warunek logiczny. 
SELECT * FROM customers WHERE (customer_id=2 OR customer_id=4 OR customer_id=6);
<img width="548" alt="Zrzut ekranu 2022-11-29 o 22 43 37" src="https://user-images.githubusercontent.com/116260341/204654416-ae11bb32-5dec-4cdf-b5fe-037dc4cb6f75.png">

7. Wyświetl klientów o id 1,3,5 wykorzystaj do tego operator IN. 
SELECT * FROM customers WHERE customer_id IN (1,3,5);
<img width="370" alt="Zrzut ekranu 2022-11-29 o 22 44 40" src="https://user-images.githubusercontent.com/116260341/204654597-5f6bc6f3-382e-4050-930a-08b6d566b949.png">

8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.
SELECT * FROM actors WHERE name LIKE "%An%";
<img width="307" alt="Zrzut ekranu 2022-11-29 o 22 48 19" src="https://user-images.githubusercontent.com/116260341/204655220-38945d46-fed2-4756-93b8-82822745f618.png">

9. Wyświetl dane klienta, który nie ma podanego adresu email.
SELECT * FROM customers WHERE email IS NULL;
<img width="308" alt="Zrzut ekranu 2022-11-29 o 22 51 01" src="https://user-images.githubusercontent.com/116260341/204655735-0f0e557a-55a5-4f08-81de-d544c95df810.png">

10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.
SELECT * FROM movies WHERE (price>9 AND movie_id BETWEEN 2 AND 8);
<img width="459" alt="Zrzut ekranu 2022-11-29 o 22 53 46" src="https://user-images.githubusercontent.com/116260341/204656554-caa9c726-8add-42a7-b606-28646c9144f4.png">

TASK 6
========
Subtask 1

11. Popełniłam błąd wpisując nazwisko Ani Miler – wpisałam Muler. Znajdź i zastosuj funkcję, która poprawi mój karkołomny błąd 🙈
<img width="539" alt="Zrzut ekranu 2022-12-6 o 20 26 04" src="https://user-images.githubusercontent.com/116260341/206003827-62237375-d595-48e8-b473-e25cecef9ce6.png">

12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji join sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej.
SELECT sale.movie_id, customers.name, customers.email FROM customers INNER JOIN sale ON customers.customer_id=sale.customer_id;
<img width="854" alt="Zrzut ekranu 2022-12-6 o 20 55 55" src="https://user-images.githubusercontent.com/116260341/206009694-5be96aad-876a-40da-b65b-f504b2ae6db4.png">

13. Na pewno zauważył_ś, że sprzedawca zapomniał wpisać emaila klientce Patrycji. Uzupełnij ten brak wpisując: pati@mail.com
UPDATE customers SET customers.email = 'pati@mail.com' WHERE customers.name = 'Patrycja'
<img width="616" alt="Zrzut ekranu 2022-12-6 o 21 03 21" src="https://user-images.githubusercontent.com/116260341/206011079-3e9d57ea-f4a8-4e55-8caa-bc918b42c113.png">


14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał wypożyczenia oraz tytuł wypożyczonego filmu. (wykorzystaj do tego funkcję inner join, zastanów się wcześniej, które tabele Ci się przydadzą do wykonania ćwiczenia).
SELECT customers.name, customers.surname, movies.title FROM ((sale INNER JOIN customers ON sale.customer_id-customers.customer_id) INNER JOIN movies ON sale.movie_id-movies.movie_id);
<img width="1157" alt="Zrzut ekranu 2022-12-6 o 21 27 59" src="https://user-images.githubusercontent.com/116260341/206015886-9ab1b930-5eb6-41e2-ad45-ea0e31529aab.png">


15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. - Dodaj kolumnę o nazwie ‘pseudonym’ do tabeli customer,- Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska. Np. Natalie Pilling → Nag


16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały.
SELECT DISTINCT movies.movie_id, movies.title FROM movies INNER JOIN sale ON movies.movie_id=sale.movie_id;
<img width="737" alt="Zrzut ekranu 2022-12-6 o 21 46 28" src="https://user-images.githubusercontent.com/116260341/206019376-c7f3dd95-f780-4ca3-bd50-e87a2dd68482.png">


17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. (Wykorzystaj do tego funkcji UNION)
SELECT name FROM customers UNION SELECT name FROM actors ORDER BY name;
<img width="563" alt="Zrzut ekranu 2022-12-6 o 21 49 53" src="https://user-images.githubusercontent.com/116260341/206020039-b02c2267-ef9a-4f17-b538-aba994d60059.png">




Subtask 2

14/15
<img width="534" alt="Zrzut ekranu 2022-12-6 o 22 05 53" src="https://user-images.githubusercontent.com/116260341/206022779-6683ea35-33d7-406e-85ac-b0450e330b7d.png">
