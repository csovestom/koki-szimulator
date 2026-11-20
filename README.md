# Kőbánya-Kispest Forgalmi Szimulátor

Telepíthető, internet nélkül is működő webes változat.

## Közzététel GitHub Pages-en

1. GitHubon: **New repository**, név például `koki-szimulator`, **Public**, majd **Create repository**.
2. Az új repóban: **uploading an existing file**, és húzd be a mappa teljes tartalmát (`index.html`, `manifest.webmanifest`, `sw.js`, `xlsx.full.min.js`, `.nojekyll`, `README.md` és az `icons` mappa). **Commit changes**.
3. **Settings → Pages**: Source = **Deploy from a branch**, Branch = `main`, mappa = `/ (root)`, **Save**.
4. Egy-két perc múlva elérhető: `https://<felhasználónév>.github.io/koki-szimulator/`

## Telepítés

- **Android (Chrome):** nyisd meg a címet, menü (⋮) → **Alkalmazás telepítése** / **Hozzáadás a kezdőképernyőhöz**.
- **iPhone, iPad (Safari):** Megosztás gomb → **Főképernyőhöz adás**.
- **Számítógép (Chrome, Edge):** a címsor jobb szélén a telepítés ikon, vagy menü → **Telepítés**.

Az első megnyitás után internet nélkül is indul.

## Frissítés

Cseréld le a fájlt a repóban. Az `index.html` változását a játék a következő online indításkor magától átveszi. Ha más fájl is változik, írd át a `sw.js` elején a `koki-v1` értéket (pl. `koki-v2`-re).
