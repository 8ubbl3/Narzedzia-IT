# Narzedzia-IT
## Tematyka zbioru
Tematyką zbioru są różne filmy z przestrzeni wielu lat.
Do każdego filmu jest przypisane kilka cech:
- Rok wydania
- Gatunek
- Ocena w skali 1-10
- Główny aktor

## CSV
Dane przy użyciu CSV wypisywane są w formie tabelki.  
  
Wpisywane dane do CSV są oddzielone od siebie poprzez znak **","**.  
Przykład kodu:  
```
    Element 1,Element 2,Element 3
    nazwa 1,nazwa 2,nazwa 3
    nazwa 4,nazwa 5,nazwa 6
```
  
## JSON
W JSON dane przedstawiane są w formie struktury (obiekty mogą zawierać w sobie kolejne obiekty)  
  
Tablice (zapisywane przy pomocy nawiasu **"[ ]"**) mogą zawierać w sobie obiekty (zapisywane przy pomocy nawiasu **"{ }"**)  
Klucze (nazwy tablic, obiektów, pól) zapisywane są przy pomocy cudzysłowu **"nazwa"** oraz definiowane są przy pomocy znaku **":"**  
Wszystkie elementy obiektów oddzielone są od siebie znakiem **","**  
Przykład kodu:
```
    {
      "Przykład": [
        {
          "element 1": "nazwa 1",
          "element 2": "nazwa 2",
          "element 3": "nazwa 3"
        },
        {
          "element 1": "nazwa 4",
          "element 2": "nazwa 5",
          "element 3": "nazwa 6"
        }
      ]
    }
```
