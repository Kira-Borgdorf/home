# Fonts lokal herunterladen – Anleitung

Die Website referenziert jetzt lokale Font-Dateien im Ordner `fonts/`.
Diese Dateien musst du einmalig herunterladen und in den Ordner legen.

## Schritt-für-Schritt

### 1. Cormorant Garamond

1. Gehe zu: https://gwfh.mranftl.com/fonts/cormorant-garamond?subsets=latin
2. Wähle die Stile: **regular**, **italic**, **500**, **600**
3. Klicke auf "Download" (das ZIP-Archiv)
4. Entpacke das ZIP
5. Benenne die Dateien um und kopiere sie in deinen `fonts/` Ordner:
   - `cormorant-garamond-v16-latin-regular.woff2` → `cormorant-garamond-400.woff2`
   - `cormorant-garamond-v16-latin-italic.woff2` → `cormorant-garamond-400i.woff2`
   - `cormorant-garamond-v16-latin-500.woff2` → `cormorant-garamond-500.woff2`
   - `cormorant-garamond-v16-latin-600.woff2` → `cormorant-garamond-600.woff2`

### 2. Source Sans 3

1. Gehe zu: https://gwfh.mranftl.com/fonts/source-sans-3?subsets=latin
2. Wähle die Stile: **regular**, **500**, **600**
3. Klicke auf "Download"
4. Entpacke das ZIP
5. Benenne die Dateien um und kopiere sie in deinen `fonts/` Ordner:
   - `source-sans-3-v15-latin-regular.woff2` → `source-sans-3-400.woff2`
   - `source-sans-3-v15-latin-500.woff2` → `source-sans-3-500.woff2`
   - `source-sans-3-v15-latin-600.woff2` → `source-sans-3-600.woff2`

## Ordnerstruktur danach

```
dein-repo/
├── index.html
├── impressum.html
├── datenschutz.html
├── favicon.svg
├── BorgdorfKira_web-AMU.jpg
└── fonts/
    ├── cormorant-garamond-400.woff2
    ├── cormorant-garamond-400i.woff2
    ├── cormorant-garamond-500.woff2
    ├── cormorant-garamond-600.woff2
    ├── source-sans-3-400.woff2
    ├── source-sans-3-500.woff2
    └── source-sans-3-600.woff2
```

## Testen

Öffne deine index.html im Browser. Wenn die Schriften genauso aussehen wie vorher,
hat alles geklappt. Falls Fallback-Schriften (Georgia/System) angezeigt werden,
prüfe, ob die Dateinamen exakt stimmen und die Dateien im richtigen Ordner liegen.
