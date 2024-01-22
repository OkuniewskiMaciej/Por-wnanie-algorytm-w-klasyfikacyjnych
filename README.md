# Porównanie algorytmów klasyfikcyjnych

## Charakterystyka oprogramowania 

**a. Nazwa skrócona** 

Porównanie algorytmow klasyfikacyjnych

**b. Nazwa pełna**

Porównanie działania i jakości predykcji wybranych algorytmów klasyfikacyjnych 

**c. Krótki opis ze wskazaniem celów**

Celem projektu jest porównanie działania oraz jakości predykcji wybranych algorytmów klasyfikacyjnych (drzewa klasyfikacyjne, random forest, knn, naive bayes) na przykładzie zróżnicowanych zbiorów danych.

## Prawa autorkie

**a. Autorzy**

* Dominika Weltrowska
* Maciej Okuniewski

**b. Warunki licencyjne oprogramowania**

Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)

Darmowe użytkowanie, kopiowanie, rozpowszechnianie i modyfikowanie oprogramowania są dozwolone pod warunkiem przypisania odpowiedniego uznanie autorstwa, braku użycia komercyjnego oraz udostępnienia utworów pochodnych na tych samych warunkach.

## Specyfikacja wymagań

| Identyfikator | Nazwa                 | Opis                                                                                           | Priorytet | Kategoria       |
|---------------|-----------------------|----------------------------------------------------------------------------------------------- |-----------|-----------------|
| WF1           | Biblioteki            | System powinien załadować biblioteki wymagane do działania programu.                           | 1         | Funkcjonalne    |
| WF2           | Załadowanie danych    | System powinien załadować dane potrzebne do dalszej analizy                                    | 1        | Funkcjonalne    |
| WF3           | Przygotowanie danych  | System powinien wstępnie przygotować dane do dalszej analizy (sprawdzenie i zamiana typów danych). | 1         | Funkcjonalne    |
| WF4           | Eksploracja danych    | System powinien przeprowadzić wstępną eksplorację danych i wyświetlić podstawowe statystyki.   | 1         | Funkcjonalne    |
| WF4.1         | Podstawowe statystyki | System powinien wyświetlać podstawowe statystyki zmiennych w zbiorze danych.                   | 1         | Funkcjonalne    |
| WF4.2         | Wizualizacja          | System powinien wyświetlać wizualizacje dotyczące zmiennych w zbiorze danych.                  | 1         | Funkcjonalne    |
| WF5           | Modele                | System powinien tworzyć modele służące do klasyfikacji.                                        | 1         | Funkcjonalne    |
| WF5.1         | Drzewo klasyfikacyjne | System powinien tworzyć optymalny model drzewa klasyfikacyjnego.                               | 1         | Funkcjonalne    |
| WF5.2         | Randoom Forest        | System powinien tworzyć optymalny model Random Forest.                                        | 1         | Funkcjonalne    |
| WF5.3         | KNN                   | System powinien tworzyć optymalny model KNN.                                                  | 1         | Funkcjonalne    |
| WF5.4         | Naive Bayes           | System powienien tworzyć optymalny model Naive Bayes.                                         | 1         | Funkcjonalne    |
| WF6           | Ważność zmiennych     | System powienien wyświetlać ważność zmiennych dla każdego modelu.                              | 2        | Funkcjonalne   |
| WF7           | Ocena predykcji       | System powinien wyświetlać oceny jakości predykcji dla każdego z modeli i zasugerować najlepszy model                      | 1         | Funkcjonalne    |
| WF8           | Interfejs użytkownika | System powienien posiadać interfejs użytkownika z przejrzystymi wynikami analizy               | 2        | Funkcjonalne    |
| WNF1          | Dokumentacja          | System powinien posiadać przejrzystą dokumentację oraz opisy kodu aby ułatwić korzystanie.    | 1         | Niefunkcjonalne |
| WNF2              | Skalowalność      | System powinien umożliwiać dodanie kolejnych metod klasyfikacji                               | 2           | Niefunkcjonalne |

## Architektura systemu / oprogramowania

**a. Architektura rozwoju - stos technologiczny**

* Język programowania: Python
* Pakiety: Pandas, Numpy, SciKit Learn, Seaborn


## Testy 

**a. Scenariusz testów**

Wyliczenie ocen jakości predykcji modeli wraz z wizualizacją wyników.



**b. Sprawozdaie z wykonania scenariuszy testów**

Raport z interpretacjami wyników.
