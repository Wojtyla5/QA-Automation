Witaj!
Poniżej krótka instrukacja dotycząca uruchomienia projektu:

1. Aby uruchomić znajdujące się w repozytorium zadanie domowe należy otworzyć cały projekt np. w Visual Studio Code klikając w zakładkę "File", a następnie "Open Folder..."
Należy wówczas wybrać folder zawierający wszystkie pliki.

2. Kolejnym krokiem będzie uruchomienie terminalu za pomocą zakładki "View", a kolejno "Terminal".

3. Przed uruchomieniem Cypressa należy go najpierw zainstalować, dlatego po otwarciu termianu należy wpisać w nim polecenie  "npm install" 

4. Kolejno wpisujemy komendę "npx cypress open", która korzysta z otworzy nam warstwę UI programu Cypress, który jest narzędziem do automatyzacji testów frontendowych w aplikacjach webowych.

5. Po otworzeniu się nowego okna Cypress należy wybrać zakładkę "E2E Testing"

6. Kolejno wybieramy przeglądarkę, na której to będziemy odpalać nasz projekt - rekomendowana to Google Chrome lub Mozilla Firefox.

7. Po otwarciu należy zlokalizwoać w zakładce "Specs"plik "firstTest.cy.js", a następnie kliknąc na niego.

8. Testy uruchamiają się prawidłowo logując się do strony internetowej https://www.edu.goit.global/account/login przy użyciu konkretncyh danych, a następnie następuje wylogowanie z każdego konta.
