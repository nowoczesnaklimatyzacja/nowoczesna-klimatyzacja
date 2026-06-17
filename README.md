# FREE HOME Design - portfolio studia

Responsywna strona portfolio i oferty studia FREE HOME Design.

## Uruchomienie

Kliknij dwukrotnie `start.command`, a następnie otwórz:

http://127.0.0.1:4174/index.html

Możesz też uruchomić serwer ręcznie:

```bash
python3 -m http.server 4174 --bind 127.0.0.1
```

Strona nie wymaga instalowania zależności ani procesu budowania.

## Publikacja

Repozytorium jest przygotowane pod GitHub Pages. Po pushu na gałąź `main`
workflow `.github/workflows/pages.yml` publikuje statyczną stronę z katalogu
głównego.

## Pliki

- `index.html` - treść, portfolio, oferta, SEO i semantyczna struktura strony
- `styles.css` - pełny wygląd desktopowy i mobilny
- `app.js` - menu, FAQ, animacje i aktywna nawigacja
- `assets/free-home-design-logo.svg` - pełne logo poziome
- `assets/free-home-design-icon.svg` - sygnet używany na telefonie
- `assets/portfolio/` - zrzuty ekranów wybranych realizacji
- `app-preview.png` - podgląd desktopowy
- `app-preview-mobile.png` - podgląd mobilny
