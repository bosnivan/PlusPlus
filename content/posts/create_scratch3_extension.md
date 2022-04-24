---
title: "Kako napraviti Scratch 3 ekstenziju"
date: 2022-03-09T22:00:00+02:00
categories: [Scratch]
tags: [Scratch, GitHub, Smart Lumies]
draft: false
---

U nastavku je opis izrade Scratch 3 ekstenzije za [Smart Lumies](https://smartlumies.com/). Ekstenzija s kockom uspostavlja BLE komunikaciju i pomoću nje izvršava naredbe te razmjenjuje informacije. Na sličan se način mogu izraditi i druge ekstenzije.

## Što sam prvo proučio
- [kako izraditi ekstenziju](https://www.instructables.com/Making-Scratch-30-Extensions/)
- [opis razvojnog okruženja](https://scratch.mit.edu/discuss/topic/336496/)
- [službene upute kako izraditi ekstenziju](https://github.com/LLK/scratch-vm/blob/develop/docs/extensions.md)
- [službene upute kako staviti Scratch na GitHub Pages](https://github.com/LLK/scratch-gui/wiki/Publishing-to-GitHub-Pages)

## Preduvjeti
- račun na [GitHubu](https://github.com/)
- instaliran [Git](https://gitforwindows.org/) i [Node.js](https://nodejs.org/)
- instaliran [Visual Studio Code](https://code.visualstudio.com/) ili neki drugi uređivač

## Koraci

### Priprema razvojnog okruženja
- na GitHubu sam forkao projekte:
https://github.com/LLK/scratch-gui
https://github.com/LLK/scratch-vm
- zatim sam na računalu napravio mapu `Scratch` i u nju klonirao oba projekta
```text
git clone https://github.com/bosnivan/scratch-gui
git clone https://github.com/bosnivan/scratch-vm
```
- u oba sam projekta zatim izvršio instalaciju
```text
npm install
```
- pa sam ih povezao
```text
cd scratch-vm
npm link
cd  scratch-gui
npm link scratch-vm
```
- iz mape `scratch-gui` pokrenuo sam Scratch pomoću naredbe
```text
npm start
```
- nakon pokretanja dostupan je na adresi http://localhost:8601/
- svaka pohrana promjene ponovno će ga pokrenuti (tzv. hot deploy), a zaustaviti ga možete kombinacijom tipki `Ctrl+C`

### Izrada ekstenzije
- u oba sam projekta napravio novi branch i učinio ga aktivnim
```text
git branch smart-lumies
git checkout smart-lumies
```
- izradu sam nadalje radio u Visual Studio Codu i pomoću njega sam commitao i pushao promjene na GitHub
- u commitu `init` ([scratch-gui](https://github.com/bosnivan/scratch-gui/commit/da04ffac14c8ad3fb8f57fbcaae58050a0f010e2), [scratch_vm](https://github.com/bosnivan/scratch-vm/commit/99d6342f799b15f04d9a39558a7606876fe050ba)) nalaze se promjene u projektu nastale iz razloga što koristim Node.js 17
sve je automatski izgenerirano, jedino sam ja ručno dodao
```text
SET NODE_OPTIONS=--openssl-legacy-provider && 
```
- budući da se Smart Lumies nije htio povezati preko Scratch Linka u commitu `added Web Bluetooth` ([scratch-vm](https://github.com/bosnivan/scratch-vm/commit/4060bc850c7a56e2dd74a75e92ffdf83f1d973cc)) dodao sam podršku za Web Bluetooth
ako vam internetski preglednik podržava Web Bluetooth, a većina ga danas podržava, onda vam Scratch Link više neće biti potreban
- sve promjene vezane za samu ekstenziju nalaze se u commitu `added Smart Lumies` ([scratch-gui](https://github.com/bosnivan/scratch-gui/commit/f4adc5ab41416c2c9cce3464ba51792e3e8d6d4e), [scratch-vm](https://github.com/bosnivan/scratch-vm/commit/333eb9ee80d79f596870e0acbc7e55174c0ad11e))
- Scratch s mojom ekstenzijom stavio sam na GitHub Pages pomoću naredbi
```text
npm run build
npm run deploy
```
- nakon što su se odradile, Scratch je postao dostupan na adresi https://bosnivan.github.io/scratch-gui/

### Detalji izrade ekstenzije
- kod izrade ekstenzije imitirao sam ekstenziju za LEGO WeDo 2.0 ili, da budem precizniji, tražio sam gdje se sve spominje WeDo i isto sam radio za Smart Lumies
- u mapu `scratch-gui/src/lib/libraries/extensions/` dodao sam mapu `smart-lumies` i sve što se u njoj nalazi
- u datoteku `scratch-gui/src/lib/libraries/extensions/index.jsx` dodao sam unos za ekstenziju
- dodao sam datoteku `scratch-vm/src/extensions/scratch3_smart_lumies/index.js` koja je mozak ekstenzije, sve u njoj je iskomentirano
- u datoteku `scratch-vm/src/extension-support/extension-manager.js` dodao sam unos za ekstenziju

### Dorade
- promijenjena je veličina ikonice u izborniku ekstenzija ([scratch-gui](https://github.com/bosnivan/scratch-gui/commit/182a29ad6abf61309d2712685020130cdda90ada))
- spremljeni projekti nisu se mogli otvoriti pa je ispravljen id ekstenzije ([scratch-vm](https://github.com/bosnivan/scratch-vm/commit/a37764cbe3aeeacf4616712503d27680f66c3c27))