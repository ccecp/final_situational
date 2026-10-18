# Simulări situaționale pentru management școlar

20 de teste distincte, fiecare cu 20 de cazuri și 60 de minute. Material de pregătire, nu subiect oficial.

Distribuția fiecărui test: 5 Legea nr. 198/2023 (25%), 5 ROFUIP (25%), 4 Tony Bush (20%), 2 John Hattie (10%), 2 Profilul profesional al managerului școlar (10%), 2 CRCNR (10%). Total: 400 de itemi. Simulările 11–20 adaugă 100 de aspecte legislative distincte față de prima serie: 50 Legea 198 și 50 ROFUIP. Inventarul noilor aspecte este în `coverage.json`.

Patru variante în ordine alfabetică, un singur răspuns corect. Mod simulare cu rezultate la final sau mod învățare cu verificare imediată. Fiecare soluție are explicație, articol/pagină/competență, extras și link către resursă. Răspunsurile nu se păstrează între sesiuni. Sunt disponibile reluarea integrală, recapitularea greșelilor, tipărirea fără soluții și semnal sonor opțional la trei minute.

Bibliografie: Legea nr. 198/2023, ROFUIP aprobat prin OME nr. 5.726/2024, Tony Bush capitolele I–III, John Hattie capitolul 9, Profilul profesional aprobat prin OMEC nr. 3.934/2026, CRCNR capitolul 10 (OMEC nr. 4.137/2026). Trimiterile individuale se găsesc în `bank.json`. Selecția urmează materialele bibliografice folosite la redactare, versiunea 18.10.2026; aceste teste nu reprezintă o acoperire integrală a tuturor prevederilor legislative.

## Rulare

Site static, fără instalare: `index.html`, `app.css`, `app.js`, `bank.js`. Pentru GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root).

## Verificări

`node verify.cjs` verifică ascunderea soluțiilor, punctajul, reluarea, limita de timp și tipărirea. `node finalize_bank.cjs` reconstruiește variantele alfabetice și validează distribuția, unicitatea și structura băncii. `bank.unsorted.json` este sursa editabilă, cu răspunsul corect în prima poziție; nu schimbați direct pozițiile din `bank.js`.

Antrenamentul personalizat permite alegerea uneia sau mai multor resurse și a numărului de itemi (10, 20, 30, 40, 50). Fiecare întrebare afișează materialul de proveniență. Distribuția fixă 5/5/4/2/2/2 se aplică testelor numerotate; seturile personalizate folosesc exclusiv selecția utilizatorului.

Platformă: Prof. dr. Maria-Magdalena Dorcioman · Colegiul Național „Dinicu Golescu”.
