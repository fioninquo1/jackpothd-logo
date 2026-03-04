# JackpotHD Brand Redesign — Roadmap

## Fázis 1: Logó irány kiválasztása ✅
- 6 különböző stílus, mindegyikhez 6 variáció (36 opció)
- Kollégák megnézik a GitHub Pages oldalon
- **Kiválasztanak egy konkrét irányt** (pl. #2.3 Royal Gold, text-domináns)

## Fázis 2: Logó finomhangolás
A kiválasztott irány alapján iterálunk:
- Háttér lekerekítés / sarok rádiusz finomítás
- Méretarányok, padding, spacing tökéletesítés
- Ikonok/szimbólumok részletesebb kidolgozása
- Szöveg kerning, font-weight, letter-spacing csiszolás
- Színárnyalatok véglegesítése
- Sötét és világos háttéren is jól működő verzió
- Kör alakú (Discord, Telegram) és négyzetes (Twitch) változat
- Favicon / kis méretű ikon verzió (egyszerűsített, olvasható marad 32x32-en is)

## Fázis 3: Teljes Brand Kit
A végleges logó alapján elkészítjük:

### Közösségi felületek
- **Twitch**: Profilkép, offline banner, panel ikonok
- **Discord**: Szerver ikon, banner, role ikonok
- **Telegram**: Csoport profilkép
- **YouTube / egyéb**: Banner, thumbnail template

### Stream design
- Overlay elemek (webcam keret, alert box stílus)
- Starting soon / BRB / ending screen
- Chat widget stílus ajánlás

### Brand guide
- Színpaletta (elsődleges, másodlagos, akcentus színek, hex kódok)
- Tipográfia (betűtípusok, használati útmutató)
- Logó használati szabályok (min. méret, tiltott használat, clear zone)
- Sötét/világos háttér verziók

## Technikai megvalósítás
- Minden asset SVG + PNG exporttal
- HTML+CSS+JS alapú előnézeti oldal (mint a jelenlegi logó választó)
- GitHub Pages-en elérhető a csapat számára
- Verziózva Git-ben, minden fázis backupolva
