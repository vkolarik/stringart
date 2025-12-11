# String Art Visualizer

Webová aplikace pro vizualizaci string art postupů.

## Nasazení na Vercel

1. **Import projektu z GitHubu** na [vercel.com](https://vercel.com)

2. **Při nastavení projektu:**
   - **Framework Preset:** Vyber `Other` nebo `Static Site`
   - **Root Directory:** `.` (nebo nechat prázdné)
   - **Build Command:** Nechat prázdné (nebo `echo "No build needed"`)
   - **Output Directory:** `.` (nebo nechat prázdné)

3. **Deploy** - Vercel automaticky nasadí statické soubory

## Lokální vývoj

```bash
# Spustit lokální server
npx serve .
```

## Použití

1. Otevři `index.html` v prohlížeči
2. Načti JSON soubor s postupem (drag & drop nebo klik)
3. Procházej kroky pomocí šipek nebo tlačítek
4. Generuj šablonu na tisk s popisky pinů
