# Zadanie z Metody Elementów skończonych na labolatoria z Równań różniczkowych i różnicowych
### Łukasz Wala, semestr 2021/22
---

W tym repozytorium znajduje się [opis problemu oraz wstępne obliczenia](mes_opracowanie.pdf), oraz program napisan w języku Julia przygotowujący (tzn. wyliczający całki) macierz układu równań do metody Galerkina, a następnie go rozwiącujący.

Do uruchomieniu potrzebny jest kompilator Julii oraz pakiet Plots, który można pobrać przez Julia REPL (interaktywne narzędzie do ewaluacji kodu w konsoli):
```
using Pkg
Pkg.add("Plots")
```
Program uruchomić można przez:
```
julia mes_solver.jl
```