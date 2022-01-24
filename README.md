# Zadanie z Metody Elementów Skończonych na laboratoria z Równań różniczkowych i różnicowych
### Łukasz Wala, semestr 2021/22
---
W tym repozytorium znajduje się [opis problemu, wstępne obliczenia](mes_opracowanie.pdf) oraz program napisany w języku Julia przygotowujący macierz (tzn. obliczający jej elementy) układu równań, a następnie go rozwiązujący.

Do uruchomieniu potrzebny jest [kompilator Julii](https://julialang.org/downloads/) oraz pakiet [Plots](https://docs.juliaplots.org/latest/), który można pobrać przez Julia REPL (interaktywne narzędzie do ewaluacji kodu w konsoli):
```
[user@$host ~]$ julia
julia> using Pkg
julia> Pkg.add("Plots")
```
Program uruchomić można przez:
```
[user@$host ~/AGH-RRIR-MES]$ julia mes_solver.jl
```
Wymagane jest podanie jednego parametru: liczby elementów (punktów podziałowych - 1) na które zostanie podzielony przedział:
```
>>> 100
```
