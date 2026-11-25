# AI WORKER FREE — PWA prototip

Acesta este un prototip instalabil de pe telefon, fără abonament și fără server pentru funcțiile locale.

## Funcții incluse
- Interfață mobilă neagră, futuristă.
- Planificator de episoade de 5, 7 sau 10 minute.
- Storyboard generat local, cu scene și indicații vizuale.
- Personaj predefinit Riko și posibilitatea de a salva alte personaje.
- Salvare locală în browser, listă de episoade, copiere și export text.
- Cache offline după prima încărcare.

## Limitări importante
Aplicația NU generează încă videoclipuri, voci sau imagini AI și NU rulează autonom în cloud. Planul/storyboard-ul este creat din șabloane locale. Generarea video nelimitată și serverul 24/7 nu pot fi promise gratuit; serviciile gratuite au cote, iar procesarea locală depinde de dispozitiv.

## Cum o folosești
1. Publică fișierele pe un hosting static HTTPS, de exemplu GitHub Pages (gratuit, dar necesită cont și configurare).
2. Deschide adresa site-ului în Safari pe iPhone sau Chrome pe Android.
3. iPhone: Share → Add to Home Screen. Android: meniul browserului → Install app / Add to Home screen.

Poți testa local deschizând index.html, dar instalarea PWA și service worker-ul necesită HTTPS sau localhost.

## Următoarea etapă
Conectăm un backend și un model AI cu nivel gratuit, verificând limitele curente înainte de integrare. Cheile API trebuie păstrate pe server, niciodată în fișierele publice ale aplicației.
