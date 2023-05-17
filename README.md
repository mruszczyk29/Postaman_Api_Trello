# Cel testów

Celem przeprowadzenia testów na podstawie dokumentacji API Trello jest weryfikacja poprawności działania interfejsu oprogramowania aplikacji Trello. Testy mają na celu sprawdzenie, czy API Trello działa zgodnie z oczekiwaniami i pozwala na realizację podstawowych funkcjonalności, takich jak tworzenie i modyfikowanie tablic, list i kart.

Konkretne cele poszczególnych testów to:

* Test poprawnej autoryzacji używając stworzonego API key oraz tokenu - sprawdzenie, czy autoryzacja do API Trello działa poprawnie.
* Test tworzenia nowej tablicy - sprawdzenie, czy możliwe jest utworzenie nowej tablicy w Trello poprzez API.
* Test pobierania stworzonych tablic - sprawdzenie, czy możliwe jest pobieranie utworzonych tablic z Trello poprzez API.
* Test modyfikowania istniejącej tablicy - sprawdzenie, czy możliwe jest modyfikowanie istniejącej tablicy w Trello poprzez API.
* Test usuwania tablicy - sprawdzenie, czy możliwe jest usunięcie tablicy z Trello poprzez API.
* Test tworzenia nowej listy w tablicy - sprawdzenie, czy możliwe jest utworzenie nowej listy w wybranej tablicy Trello poprzez API.
* Test pobierania listy z tablicy - sprawdzenie, czy możliwe jest pobieranie listy z wybranej tablicy Trello poprzez API.
* Test modyfikowania istniejącej listy - sprawdzenie, czy możliwe jest modyfikowanie istniejącej listy w Trello poprzez API.
* Test usuwania listy - sprawdzenie, czy możliwe jest usunięcie listy z Trello poprzez API.
* Test dodawania karty do listy - sprawdzenie, czy możliwe jest dodawanie nowej karty do wybranej listy Trello poprzez API.
* Test pobierania stworzonych kart z listy - sprawdzenie, czy możliwe jest pobieranie kart z wybranej listy Trello poprzez API.
* Test modyfikacji istniejącej karty - sprawdzenie, czy możliwe jest modyfikowanie istniejącej karty w Trello poprzez API.
* Test usuwania kart z listy - sprawdzenie, czy możliwe jest usunięcie karty z Trello poprzez API.

# Uruchomienie kolekcji w Postman

* Załóż konto na stronie Trello, które będziesz mógł użyć go jako konto testowe do uruchamiania kolekcji w aplikacji Postman.
* Wygeneruj swoje **API KEY** oraz **TOKEN**, korzystając z instrukcji dostępnej na stronie [YouTube](https://www.youtube.com/watch?v=ndLSAD3StH8) lub [dokumentacji](https://developer.atlassian.com/cloud/trello/guides/rest-api/authorization/).
* Pobierz plik [Colt - Trello.postman_collection.json](https://github.com/mruszczyk29/TrelloApi/blob/main/Colt%20-%20Trello.postman_collection.json).
* Uruchom aplikację Postman.
* Zainportuj plik z kolekcją, klikając **"Import"** i wybierając plik "Colt - Trello.postman_collection.json".
* Kliknij nazwę kolekcji, która się pojawiła i przejdź do zakładki **"Variables"**.
* Zmień wartości zmiennych o nazwie "token" oraz "key" na wygenerowane wcześniej wartości **API KEY** oraz **TOKEN** w polach Initial value oraz Current value.
* Kliknij prawym przyciskiem myszy na nazwę kolekcji i wybierz opcję "Run collection".

# Wyniki z testu tworzenia oraz usuwania tablicy

Poniżej pokazuję metody, które zastosowałem do stworzenia oraz usunięcia tablicy w aplikacji Trello.
![trellometody](https://imgur.com/prwhEVk.png)

Następnie po kliknięciu w "Run Colt - Trello" otrzymujemy następujące wyniki. 
![trellometody2](https://imgur.com/qfD2QjE.png)

Jak widać na powyższym zrzucie ekranu testy przeszły pomyślnie.
