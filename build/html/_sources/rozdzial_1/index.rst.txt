Rozdział 1: Wprowadzenie
========================

**Autor:** Dawid Szokało

Niniejszy rozdział stanowi wstęp do sprawozdania końcowego z przedmiotu Bazy Danych, realizowanego w semestrze letnim roku akademickiego 2025/2026 na kierunku informatyka techniczna.

Wprowadzenie tematyczne
-----------------------

Niniejsza dokumentacja przedstawia proces tworzenia systemu bazodanowego – od podstaw teoretycznych, przez projektowanie, aż po wdrożenie i testy. W pierwszej części zgromadzono najważniejsze informacje dotyczące systemów zarządzania bazami danych (DBMS), zasad normalizacji oraz języka SQL, co posłużyło jako fundament do dalszych prac inżynierskich.

Praktyczna część projektu obejmuje budowę bazy danych dla sklepu internetowego dystrybuującego sprzęt elektroniczny. Główną uwagę poświęcono takim elementom jak: zarządzanie kontami klientów, ewidencja asortymentu, cykl życia zamówień, płatności oraz obsługa recenzji. W ramach etapu projektowego przygotowano model konceptualny i logiczny (spełniający wymogi trzeciej postaci normalnej – 3NF), a ostatecznie opracowano modele fizyczne dostosowane do specyfiki silników PostgreSQL oraz SQLite.

Końcowa część raportu zawiera szczegółowy opis procesu wdrożenia utworzonych struktur. W celu optymalizacji ładowania danych wykorzystano skrypty w języku Python, które wydajnie zasilają bazę przy użyciu techniki wprowadzania wsadowego (*batch insert*). Poprawność i stabilność działania całego systemu zweryfikowano za pomocą złożonych zapytań SQL. Finalna dokumentacja techniczna została wygenerowana w sposób automatyczny przy użyciu narzędzia Sphinx.

Spis wszystkich użytych w raporcie repozytoriów
----------------------------------------------

**Repozytoria tematyczne**

* `Sprzęt dla bazy danych <https://github.com/karaskamil/Sprzet-dla-bazy-danych.git>`_
* `Konfiguracja bazy danych PostgreSQL <https://github.com/Youarecheck/Bazy_Danych_Tematyczne_Repo_MK.git>`_
* `Kontrola i konserwacja bazy danych <https://github.com/pawlos1337/Bazy-danych-temat.git>`_
* `Monitorowanie i diagnostyka <https://github.com/OskarProgrammer/monitorowanie_i_diagnostyka.git>`_
* `Wydajność, skalowanie i replikacja danych <https://github.com/KMachoK/Tematyczne.git>`_
* `Partycjonowanie danych <https://github.com/domino0472/Partycjonowani-Danych.git>`_
* `Bezpieczeństwo baz danych <https://github.com/oski486/BazyDanych-Subject.git>`_
* `Kopie zapasowe i odzyskiwanie danych <https://github.com/Koko9077/Kopie-zapasowe-i-odzyskiwanie-danych.git>`_

**Repozytorium główne**

* `Repozytorium główne <https://github.com/dawszo21/Bazy-Danych.git>`_