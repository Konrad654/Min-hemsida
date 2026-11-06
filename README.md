# Meritly

En statisk webbplats för GitHub Pages. Inga externa tjänster, scriptbibliotek eller webbfonter behövs.

## Bygg

Kräver Node.js 22 eller senare.

```sh
node scripts/build.mjs
node --test tests/*.test.cjs
```

Data redigeras i courses.js. Appkoden finns i src/app.js och stilar i src/style.css. Bygget skapar en enda hashmärkt appfil för att undvika kollisioner med gamla script, statiska detaljsidor, manifest och service worker. Commit måste innehålla byggda filer.

Publicering: GitHub Pages från main och rotkatalogen. [Funktioner](FEATURES.md). Lokala profiler är inga säkra konton. Egna betyg, recensioner, poäng och framsteg är privata och självrapporterade. Katalogutkast ändrar inte det publicerade innehållet.

Offline: välj Hämta för offlinebruk i inställningarna. Externa kurser fungerar inte offline. Ingen AI eller global besöksanalys ingår.
