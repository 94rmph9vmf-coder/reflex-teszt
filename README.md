# ⚡ Reflexteszt

Reflexvizsgáló webalkalmazás: koppints a körre, várd meg amíg **pirosról zöldre** vált, majd koppints rá minél gyorsabban. Az időt századmásodpercben mutatja (pl. `0,27 s`).

## Funkciók
- **Korai koppintás figyelése** – ha zöld előtt koppintasz, „Túl korán!”, az nem számít
- **Profilok** – új profil, váltás, átnevezés, törlés (jobb felső gomb)
- **Statisztika** – legjobb idő, utolsó 5 átlaga, próbálkozások száma
- **Top 10 ranglista** – „Mindenki” (összes profil) vagy „Saját” nézet
- **Offline működés** – főképernyőre téve internet nélkül is fut
- Az eredmények az eszközön tárolódnak (böngésző localStorage)

## Közzététel (GitHub Pages)
1. Repository **Settings → Pages**
2. Source: **Deploy from a branch**, Branch: **main**, mappa: **/ (root)** → **Save**
3. 1-2 perc múlva elérhető: `https://94rmph9vmf-coder.github.io/reflex-teszt/`

## Hozzáadás iPhone főképernyőre
1. Nyisd meg a linket **Safariban**
2. **Megosztás** gomb → **Hozzáadás a főképernyőhöz** → **Hozzáadás**

## Fájlok
| Fájl | Leírás |
|------|--------|
| `index.html` | Az alkalmazás |
| `manifest.json` | PWA beállítások |
| `sw.js` | Offline működés |
| `icon.png` | Ikon |
