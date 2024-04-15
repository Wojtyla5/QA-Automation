Witaj!
Poniżej krótka instrukacja dotycząca uruchomienia projektu:

1. Aby uruchomić znajdujące się w repozytorium zadanie domowe należy otworzyć cały projekt np. w Visual Studio Code klikając w zakładkę "File", a następnie "Open Folder..."
Należy wówczas wybrać folder zawierający wszystkie pliki.

2. Kolejnym krokiem będzie uruchomienie terminalu za pomocą zakładki "View", a kolejno "Terminal".

3. Należy teraz zainstalować pakiet npm, dlatego po otwarciu termianu należy wpisać w nim polecenie  "npm install"

4. Po ukończeniu instalacji pora na instalację Artillery w ten sam sposób, lecz używając do tego komendy "npm install -g artillery"

5. Aby upewnić się, że zainstalowano pomyślnie Artillery należy wpisać komendę "artillery dino" - w tym moencie powinien pojawić się dinozaur z symboli, który mówi “Artillery!”

6. Przygotowawszy całe środowisko można przejść do testów można je uruchomić - w tym celu wchodzimy w pasku bocznym znajdującym się w lewej stronie interfejsu i klikamy na folder "artillery"

7. Wybieramy plik API.yml

8. W otwartym wcześniej terminalu odpalamy test wydajnościowy, podając przy tym lokalizację wywoływanego pliku, komenda wygląda więc następująco: 
"artillery run artillery/API.yml" 
