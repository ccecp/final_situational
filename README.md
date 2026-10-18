# Simulări situaționale pentru management școlar

10 teste distincte, fiecare cu 20 de cazuri și 60 de minute. Material de pregătire, nu subiect oficial.

Distribuția fiecărui test: 5 Legea nr. 198/2023 (25%), 5 ROFUIP (25%), 4 Tony Bush (20%), 2 John Hattie (10%), 2 Profilul profesional al managerului școlar (10%), 2 CRCNR (10%). Total: 200 de itemi diferiți.

Patru variante în ordine alfabetică, un singur răspuns corect. Mod simulare cu rezultate la final sau mod învățare cu verificare imediată. Fiecare soluție are explicație, articol/pagină/competență, extras și link către resursă. Răspunsurile nu se păstrează între sesiuni. Sunt disponibile reluarea integrală, recapitularea greșelilor, tipărirea fără soluții și semnal sonor opțional la trei minute.

Bibliografie: Legea nr. 198/2023, ROFUIP aprobat prin OME nr. 5.726/2024, Tony Bush capitolele I–III, John Hattie capitolul 9, Profilul profesional aprobat prin OMEC nr. 3.934/2026, CRCNR capitolul 10 (OMEC nr. 4.137/2026). Trimiterile individuale se găsesc în `bank.json`. Selecția urmează materialele bibliografice folosite la redactare, versiunea 18.10.2026; aceste zece teste nu reprezintă o acoperire integrală a tuturor prevederilor legislative.

## Rulare

Site static, fără instalare: `index.html`, `app.css`, `app.js`, `bank.js`. Pentru GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root).

## Verificări

`node verify.cjs` verifică ascunderea soluțiilor, punctajul, reluarea, limita de timp și tipărirea. `node finalize_bank.cjs` reconstruiește variantele alfabetice și validează distribuția, unicitatea și structura băncii. `bank.unsorted.json` este sursa editabilă, cu răspunsul corect în prima poziție; nu schimbați direct pozițiile din `bank.js`.
