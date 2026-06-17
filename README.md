# Nowoczesna Klimatyzacja - Tomasz Chrośniak

Responsywna strona firmy Nowoczesna Klimatyzacja. Prosty, szybki landing page z ofertą, realizacjami i kontaktem.

## Uruchomienie

Uruchom lokalny serwer w katalogu projektu, a następnie otwórz:

http://127.0.0.1:4174/index.html

Możesz też uruchomić serwer ręcznie:

```bash
python3 -m http.server 4174 --bind 127.0.0.1
```

Strona nie wymaga instalowania zależności ani procesu budowania.

## Publikacja

Repozytorium jest przygotowane pod GitHub Pages. Po włączeniu publikacji z
gałęzi `main` w ustawieniach repozytorium każdy `push` odświeża stronę.
W katalogu głównym znajdują się pliki statyczne, więc nie ma tu żadnego buildu
ani zależności od Netlify.

Plik `CNAME` wskazuje domenę `nowoczesnaklimatyzacja.com.pl`, a `.nojekyll`
wyłącza obsługę Jekylla, żeby GitHub Pages serwował pliki dokładnie tak, jak są
w repo.

## Pliki

- `index.html` - kompletna strona główna
- `assets/foto-1.jpeg` ... `assets/foto-6.jpeg` - zdjęcia i grafiki strony
