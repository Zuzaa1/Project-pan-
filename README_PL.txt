PROJECT PAN — instrukcja uruchomienia na iPhone 12
=====================================================

Co zawiera paczka
- index.html: aplikacja
- manifest.json: ustawienia dodawania do ekranu początkowego
- sw.js: pamięć podręczna aplikacji do uruchamiania offline po pierwszym otwarciu

WAŻNE
Dane produktów i zdjęcia są zapisywane lokalnie w pamięci przeglądarki (IndexedDB) na urządzeniu. Nie są wysyłane na serwer. To nie jest kopia zapasowa — eksportuj kopię w aplikacji przez zakładkę „Więcej”. Nie czyść danych witryny Safari, bo możesz usunąć lokalną bazę. Korzystaj z tego samego adresu i tej samej przeglądarki.

BEZPŁATNE URUCHOMIENIE — GitHub Pages
1. Na komputerze lub iPhonie otwórz https://github.com i utwórz bezpłatne konto, jeśli go nie masz.
2. Utwórz nowe repozytorium (New repository), nazwij np. project-pan, ustaw Public i utwórz.
3. Dodaj pliki z tej paczki do repozytorium: Add file → Upload files. Wgraj index.html, manifest.json i sw.js, a następnie Commit changes.
4. Wejdź w Settings repozytorium → Pages.
5. W sekcji Build and deployment wybierz Deploy from a branch, Branch: main, folder: /(root), kliknij Save.
6. Poczekaj chwilę, aż GitHub Pages pokaże adres w rodzaju https://TWOJLOGIN.github.io/project-pan/ . Otwórz ten adres w Safari na iPhonie.
7. W Safari naciśnij Udostępnij (kwadrat ze strzałką w górę) → Dodaj do ekranu początkowego → Dodaj.
8. Uruchamiaj Project Pan z nowej ikony. Pierwsze otwarcie wymaga internetu; po załadowaniu aplikacja może otwierać się offline. Nie kasuj danych witryny.

JAK KORZYSTAĆ
- „＋ Dodaj”: nazwa, kategoria, ilość początkowa i pozostała, jednostka i opcjonalne zdjęcie z galerii.
- „− Zużycie”: wpisz ilość, którą zużyłaś; aplikacja odejmie ją od pozostałej ilości i dopisze historię.
- „Historia”: zobacz wpisy dotyczące danego produktu.
- „Statystyki”: podsumowanie kolekcji i postępu.
- „Więcej” → „Pobierz kopię”: regularnie zapisuj plik kopii w aplikacji Pliki.

Jeśli wgrywasz zmiany w plikach po wcześniejszym uruchomieniu, zamknij aplikację i odśwież stronę w Safari. Dane zapisane w bazie lokalnej pozostają niezależne od aktualizacji plików aplikacji.
