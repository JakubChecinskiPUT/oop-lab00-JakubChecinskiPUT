# Moje wykonanie Lab00

- Login GitHub / pseudonim: JakubChecinskiPUT
- System i terminal (np. Windows + WSL Ubuntu): Windows
- Edytor / IDE: VSC
- Wersja Git: 2.56.0.windows.1
- Wersja kompilatora C++: 16.2.0
- Wersje java i javac: "27" 2026-09-15 ; 27
- Link do pierwszego PR (uzupełnij w zadaniu 5): https://github.com/JakubChecinskiPUT/oop-lab00-JakubChecinskiPUT/pull/1

## Uruchomienie lokalne
Wynik programu C++:
```text
Hello from C++! Author: Jakub Checinski
```
Wynik programu Java:
```text
Hello from Java! Author: Jakub Checinski
```
 
## Błąd i poprawka (zadanie 5)
- Krótki fragment komunikatu błędu i numer linii: cpp/main.cpp:5:43: error: expected ‘;’ before ‘return’
- Przyczyna oraz sposób naprawy: brak srednika
- Commit z błędem (SHA lub link): 8fcdfd5
- Czy Actions pokazały błąd, a po naprawie sukces? Tak, Actions zgłosiło błąd na zepsutym commicie. Po wypchnięciu poprawki CI zwróci sukces.

## Krótkie odpowiedzi
1. Co różni commit od push? Commit zapisuje zmiany tylko lokalnie na dysku, a push wysyła te zapisane zmiany (commity) na zdalny serwer (np. GitHub).
2. Dlaczego po scaleniu PR wykonuję lokalnie pull? Ponieważ scalenie (merge) PR tworzy nowy commit na serwerze GitHub. Komenda pull pobiera ten commit do lokalnego repozytorium, aby było z nim zsynchronizowane.
3. Co potwierdza zielony wynik naszego CI, a czego nie potwierdza? Potwierdza, że kod poprawnie się kompiluje na zdalnej maszynie. Nie potwierdza jednak poprawności działania (np. czy dodaliśmy prawidłowe imię i nazwisko), bo do tego potrzebne byłyby testy jednostkowe/funkcjonalne.

## Ewentualne problemy środowiska
Brak / opis problemu i sposób rozwiązania: ...
