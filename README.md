# Python podstawy - ćwiczenia

## Zadanie 1.

Stwórz program o nazwie `pole_kola.py`, który oblicza pole koła w oparciu
o promień *r* podany przez użytkownika. Załóż, że *pi = 3.14*.

Przykładowy output:
```
r = 1.1 
pole = 3.7994
```

*Bonus* - zaokrąglij wynik do 2 miejsc po przecinku wykorzystująć wbudowaną funkcję `round()`.

*Zaawansowane* - zdefiniuj funckję *oblicz_pole_kola*, która zwraca *pole* używając `print()`, a jako argument
przyjmuje zmienną *r*.

#### Źródła:

- [Funkcje - podstawy](https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-functions/cheatsheet)
- [round()](https://www.programiz.com/python-programming/methods/built-in/round)

## Zadanie 2.

Stwórz program o nazwie `lista_kolorow.py`, który zwraca pierwszy i ostatni kolor z listy:
```
lista_kolorow = ["czerwony", "zielony", "biały", "czarny"]
```

*Bonus* - dodaj do listy kolor niebieski wykorzystująć wbudowaną funkcję `append()`.

*Zaawansowane* - wykorzystaj wbudowaną funkcję `reverse()` aby stworzyć nową listę o nazwie
*odwrocona_lista_kolorow*.

#### Źródła:

- [Listy - podstawy](https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-lists/cheatsheet)
- [append()](https://www.programiz.com/python-programming/methods/list/append)
- [reverse()](https://www.programiz.com/python-programming/methods/list/reverse)

## Zadanie 3.

Stwórz program o nazwie `roznica.py`, który oblicza różnicę pomiędzy daną liczbą a 17.
Jeśli dana liczba jest większa od 17, zwróć podwójną bezwzględną różnicę.
Np. dla liczby 5 różnica = 12, a dla liczby 20 różnica = 6, ponieważ 2*3 = 6.

#### Źródła:
- [if / else - podstawy](https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-control-flow/cheatsheet)

## Zadanie 4.

Stwórz program o nazwie `przedrostek.py`, który na podstawie danego słowa generuje nowe
z dodatkiem "ls" na początku. Jeżeli "ls" występuje już na początku danego słowa, zwróć
słowo w niezmienionej formie.

#### Źródła:
- [Strings - podstawy](https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-strings/cheatsheet)

## Zadanie 5.

Stwórz program o nazwie `reszta.py`, który decyduje czy dana liczba jest parzysta bądź nieparzysta
i drukuje odpowiednią wiadomość dla użytkownika. *Podpowiedź*: wykorzystaj operator `%`.

#### Źródła:
- [Operator modulo (%)](https://www.codecademy.com/learn/learn-python-3/modules/learn-python3-hello-world/cheatsheet)

## Zadanie 6.

Stwórz program o nazwie `lista_cyfr.py`, który drukuje wszystkie parzyste cyfry z poniższej listy
w kolejności ich występowania, które znajdują się w liscie przed liczbą 237.

```
numbers = [    
    386, 462, 47, 418, 907, 344, 236, 375, 823, 566, 597, 978, 328, 615, 953, 345, 
    399, 162, 758, 219, 918, 237, 412, 566, 826, 248, 866, 950, 626, 949, 687, 217, 
    815, 67, 104, 58, 512, 24, 892, 894, 767, 553, 81, 379, 843, 831, 445, 742, 717, 
    958,743, 527
    ]
```