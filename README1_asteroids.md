# jQuery - Wczytywanie Danych

## Zadanie 1
Zapoznaj się z plikami HTML i  JavaScript. Zadanie polega na wczytaniu danych z adresu: http://swapi.co/api/films/.

Przydatne informacje:
* użyj odpowiedniej metody HTTP, jeśli jest potrzebna,
* użyj odpowiednich funkcji informujących użytkownika o statusie żądania (metody done(), fail()),
* jeśli dane zostaną poprawnie wczytane, to wywołaj odpowiednią funkcję np. insertConent(), do której jako argument przekaż wczytane dane (
  sprawdź w konsoli jak wyglądają wczytywane dane, czy jest to tablica, string, czy może JSON? ),
* wewnątrz funkcji insertConent(), wykorzystaj metodę jQuery.each(), aby przeiterować po każdym filmie (przeiteruj po prostu po tablicy wyników),
* wewnątz pętli stwórz dwa elementy ```li``` oraz ```h3```. Ustaw odpowiednią klasę dla elementu ```li```,
* do elementu ```h3``` dodaj tytu filmu,
* wstaw element ```h3``` do ```li```, a następnie wszystko do listy ```ul```.
