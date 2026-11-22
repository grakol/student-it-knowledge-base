## Najważniejsze polecenia

| Polecenie | Przykład użycia | Opis |
| :--- | :--- | :--- |
| `git clone` | `git clone URL` | Pobiera zdalne repozytorium i tworzy jego lokalny katalog. |
| `git status` | `git status` | Sprawdza aktualną gałąź oraz stan zmodyfikowanych i dodanych plików. |
| `git add` | `git add docs/warp/git.md` | Dodaje wskazany plik do obszaru staging przed commitem. |
| `git commit` | `git commit -m "docs: add Git cheatsheet"` | Zapisuje przygotowane zmiany w historii repozytorium z opisem. |
| `git push` | `git push -u origin feature/git-cheatsheet` | Wysyła lokalny branch na zdalny serwer i ustawia śledzenie. |
| `git pull` | `git pull --ff-only origin main` | Pobiera najnowsze zmiany ze zdalnej gałęzi bez zbędnego merge commita. |
| `git fetch` | `git fetch origin` | Pobiera informacje o zmianach na serwerze bez modyfikowania plików. |
| `git branch` | `git branch` | Wyświetla listę lokalnych gałęzi i oznacza aktywną. |
| `git switch` | `git switch -c feature/nazwa` | Tworzy nową gałąź roboczą i od razu na nią przełącza. |
| `git log` | `git log --oneline -5` | Wyświetla skróconą historię pięciu ostatnich commitów. |