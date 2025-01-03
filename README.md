# Solar for You - Telepítési útmutató

## Rendszerkövetelmények

- Node.js 16.x vagy újabb
- npm 7.x vagy újabb
- Visual Studio Code (ajánlott)

## Telepítés lépései

1. Klónozd le a projektet:
   <<<<<<< HEAD

=======

> > > > > > > 3da900c (Initial commit)

```bash
git clone [projekt URL]
cd solar-website
```

2. Futtasd a telepítő scriptet:
   <<<<<<< HEAD

=======

> > > > > > > 3da900c (Initial commit)

```bash
node setup.js
```

Ez automatikusan:
<<<<<<< HEAD

=======

> > > > > > > 3da900c (Initial commit)

- Telepíti a függőségeket
- Létrehozza a szükséges konfigurációs fájlokat
- Beállítja a VS Code környezetet

3. Indítsd el a fejlesztői szervert:
   <<<<<<< HEAD

=======

> > > > > > > 3da900c (Initial commit)

```bash
npm run dev
```

## Projekt struktúra

```
solar-website/
├── src/
│   ├── components/     # Újrafelhasználható komponensek
│   ├── pages/         # Oldal komponensek
│   ├── styles/        # CSS és animációk
│   ├── i18n/          # Többnyelvű támogatás
│   └── hooks/         # React hooks
├── public/            # Statikus fájlok
└── setup.js          # Telepítő script
```

## Ajánlott VS Code bővítmények

- ESLint
- Prettier
- Tailwind CSS IntelliSense
- Auto Rename Tag
- Path Intellisense
- ES7+ React/Redux/React-Native snippets

## Fejlesztői parancsok

- `npm run dev` - Fejlesztői szerver indítása
- `npm run build` - Projekt építése
- `npm run preview` - Építési verzió előnézete

## Hibaelhárítás

Ha a `npm run dev` parancs után nem indul el a projekt:

1. Ellenőrizd, hogy minden függőség telepítve van-e:
   <<<<<<< HEAD

=======

> > > > > > > 3da900c (Initial commit)

```bash
npm install
```

2. Töröld a cache-t és node_modules mappát:
   <<<<<<< HEAD

=======

> > > > > > > 3da900c (Initial commit)

```bash
rm -rf node_modules
rm -rf .cache
npm install
```

3. Ellenőrizd a Node.js verzióját:
   <<<<<<< HEAD

=======

> > > > > > > 3da900c (Initial commit)

```bash
node --version
```

## Támogatás

<<<<<<< HEAD
Ha kérdésed vagy problémád van, kérlek nyiss egy új issue-t a GitHub repositoryban.
=======
Ha kérdésed vagy problémád van, kérlek nyiss egy új issue-t a GitHub repositoryban.

> > > > > > > 3da900c (Initial commit)
