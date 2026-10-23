# Moja Lista — wersja webowa

Statyczna wersja przeglądarkowa aplikacji „Moja Lista” (anime i manga), przygotowana do GitHub Pages.

## Publikacja przez GitHub Pages
1. Utwórz na GitHubie nowe repozytorium, np. `moja-lista`.
2. Wypakuj ZIP i wgraj do głównego katalogu repozytorium pliki `index.html` oraz folder `assets`.
3. Otwórz **Settings → Pages**.
4. W sekcji **Build and deployment** wybierz **Deploy from a branch**.
5. Wybierz gałąź `main` i folder `/(root)`, a następnie kliknij **Save**.
6. Po zakończeniu publikacji GitHub pokaże adres strony.

## Funkcje
- osobne kolekcje Anime i Manga;
- statusy, wyszukiwanie, sortowanie, ulubione;
- widok listy i kafelków;
- dodawanie, edycja, usuwanie, okładki i ikony;
- szybkie zwiększanie/zmniejszanie postępu;
- automatyczne oznaczanie jako zakończone po osiągnięciu limitu;
- losowanie pozycji z planowanych;
- statystyki i import/eksport CSV.

## Ważne: przechowywanie danych
Dane są przechowywane w `localStorage` przeglądarki. Nie są automatycznie synchronizowane między urządzeniami ani przeglądarkami. Wyczyścić je można przez wyczyszczenie danych witryny, więc regularnie eksportuj kopię CSV. Okładki są zapisywane lokalnie w przeglądarce i warto używać obrazów do 5 MB.

To statyczna aplikacja bez serwera i kont użytkowników.
