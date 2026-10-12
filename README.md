# AI Prompt Studio

Webová aplikace pro skládání filmových promptů pro Nano Banana (image) a Kling AI (video).

## Spuštění

```bash
npm install
npm run dev
```

Produkční build: `npm run build`.

## Funkce
- Model-specific výstup pro Nano Banana a Kling
- Kamera, úhel, objektiv, pohyb, světlo, filmový vzhled a reference
- Kontrola konfliktních kamerových parametrů
- Přednastavené profily
- Kopírování promptu a lokální historie (localStorage)

Aplikace nevolá AI API; výsledek sestavuje deterministicky z nastavení. Pro další verzi je plánována AI optimalizace.

## Online verze

GitHub Pages: https://masiknexus-ops.github.io/ai-prompt-studio/

Automatické nasazení probíhá prostřednictvím GitHub Actions po změnách v hlavní větvi.
