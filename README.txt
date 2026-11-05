# Generator paragonów — PWA

## Wdrożenie na GitHub Pages

1. Otwórz repozytorium GitHub, w którym chcesz opublikować aplikację.
2. Wgraj `index.html`, `manifest.json`, `service-worker.js` oraz folder `icons` (z trzema plikami PNG) do głównego katalogu repozytorium.
3. W ustawieniach repozytorium wybierz **Settings → Pages** i upewnij się, że publikowana jest gałąź `main` oraz folder `/(root)`.
4. Poczekaj na wdrożenie i otwórz adres GitHub Pages w Chrome na Androidzie.
5. W Chrome wybierz **⋮ → Install app** lub **Add to Home screen**.

## Ważne
- To jest PWA instalowane z opublikowanej strony HTTPS; nie jest to plik APK.
- Program korzysta z bibliotek `html2canvas` i `jsPDF` ładowanych z CDN. Funkcje eksportu PDF/JPG mogą wymagać internetu, dopóki te biblioteki nie zostały pobrane przez przeglądarkę.
- Generator jest przeznaczony do makiet/testów i demonstracji, a nie do tworzenia dokumentów fiskalnych używanych jako prawdziwe dowody zakupu.
