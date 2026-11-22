# Ściąga UKOS — Terminal Bash

Podstawowe polecenia do pracy w terminalu systemów Linux i macOS.

## Zasady bezpiecznej pracy
- Zawsze sprawdzaj bieżący katalog (`pwd`) przed usuwaniem lub przenoszeniem plików.
- Zachowaj szczególną ostrożność przy poleceniu `rm` — usuwa ono pliki trwale, bez przenoszenia do kosza.

## Najważniejsze polecenia

| Polecenie | Przykład użycia | Opis |
| :--- | :--- | :--- |
| `pwd` | `pwd` | Wyświetla pełną ścieżkę bieżącego katalogu. |
| `ls` | `ls -la` | Listuje pliki w katalogu, także ukryte, w formacie szczegółowym. |
| `cd` | `cd docs/ukos` / `cd ..` | Przechodzi do wskazanego katalogu lub katalogu nadrzędnego. |
| `mkdir` | `mkdir -p docs/ukos` | Tworzy nowy katalog wraz z brakującymi katalogami nadrzędnymi. |
| `touch` | `touch bash.md` | Tworzy pusty plik lub aktualizuje czas jego modyfikacji. |
| `cp` | `cp bash.md bash-backup.md` | Kopiuje plik (dla katalogów należy dodać opcję `-r`, np. `cp -r`). |
| `mv` | `mv bash-backup.md archive.md` | Przenosi plik w inne miejsce lub zmienia jego nazwę. |
| `rm` | `rm archive.md` | Usuwa plik (uwaga: operacja całkowicie omija kosz systemowy). |
| `cat` | `cat bash.md` | Wyświetla całą zawartość pliku tekstowego bezpośrednio w terminalu. |
| `clear` | `clear` | Czyści widok okna terminala bez usuwania historii wpisanych poleceń. |