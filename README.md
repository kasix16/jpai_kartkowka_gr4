# Kolokwium z Podstaw Konteneryzacji (Docker)

## Czas 15 min 
Na swoim kontenerze LXC musisz:
0. Zrób fork repozytorium. 
1. Sklonuj repozytorium na swoją wirtualną maszynę (`git clone <ADRES URL REPOZYTORIUM>`)
2. Przeanalizuj pliki w repozytorium i dostosuj je do swoich potrzeb. 
3. Z plików źródłowych zbuduj obraz o nazwie : `test:v2`.
4. Z obrazu uruchom kontener o nazwie `apka` na porcie `4532:3000` (host:4532 → kontener:3000).
5. Sprawdź, czy aplikacja odpowiada (`curl -f http://localhost:4532/`). Jeśli wszystko działa to powinien sie wyświetlić kod HTML. 
6. Zatrzymaj i usuń kontener oraz obraz.
7. Zapisz historię komend Docker w pliku `docker.log` (`history | tee docker.log`) i zrób push do swojego repozytorium. 
