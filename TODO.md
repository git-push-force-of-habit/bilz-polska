# Bilz Polska — TODO na koniec

## Obrazy
- [ ] Kompresja PNG produktowych (obecnie 400-800KB każdy) — rozważyć konwersję do WebP
- [ ] Konwersja headerów PNG/JPG do WebP (opcjonalnie z fallbackiem `<picture>`)
- [ ] Usunąć `assets/images/wave-mid.png` — nieużywany plik
- [ ] Rozważyć usunięcie nieużywanych headerów z `assets/images/headers/` (np. bilz-service-*, bilz-unternehmen-*, bilz-aktuelles-*)

## Favicons
- [ ] Dodać `apple-touch-icon` (180x180) dla iOS
- [ ] Dodać `manifest.json` (PWA manifest z ikonami i theme-color)

## SEO / Indeksowanie
- [x] ~~Utworzyć `robots.txt`~~ ✅
- [x] ~~Utworzyć `sitemap.xml`~~ ✅
- [ ] Zarejestrować stronę w Google Search Console
- [ ] Zarejestrować w Bing Webmaster Tools (opcjonalnie)

## Strony — ukończone
- [x] index.html (strona główna)
- [x] produkty.html (przegląd produktów)
- [x] kontakt.html
- [x] rozwiazania.html
- [x] produkty/maty-antywibracyjne.html
- [x] produkty/stopy-poziomujace.html
- [x] produkty/kliny-ustawcze.html
- [x] produkty/elementy-poziomujace.html
- [x] produkty/wibroizolatory-pneumatyczne.html
- [x] produkty/systemy-poziomowania-mechaniczne.html
- [x] produkty/systemy-poziomowania-elektroniczne.html
- [x] produkty/aktywna-wibroizolacja.html
- [x] produkty/platformy-stolowe.html
- [x] produkty/stoly-antywibracyjne.html

## Walidacja końcowa
- [ ] Przepuścić wszystkie strony przez https://validator.w3.org/
- [ ] Sprawdzić Lighthouse (Performance, SEO, Accessibility, Best Practices)
- [ ] Przetestować na mobile (responsywność)
- [ ] Sprawdzić wszystkie linki wewnętrzne (czy nie ma 404)

## Inne
- [ ] Sprawdzić czy fonty Halvar ładują się poprawnie (CORS na GitHub Pages)
- [ ] Rozważyć dodanie prostego cookie bannera (RODO) jeśli będą analityki
- [ ] Opcjonalnie: Google Analytics / Plausible / inne analityki
- [ ] Rozważyć dodanie strony 404.html (GitHub Pages obsługuje custom 404)
