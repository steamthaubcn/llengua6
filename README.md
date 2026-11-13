# Llengua catalana a sisè

Aplicació web educativa per treballar la llengua catalana amb alumnat de 6è de primària (11-12 anys). Funciona a l’ordinador, a l’iPad i al mòbil, amb ratolí o pantalla tàctil, i no demana cap dada personal.

Ha estat creada per a l’Escola Thau Barcelona.

## Què hi ha

### Ortografia (blocs 1 a 6)

| Bloc | Continguts |
|---|---|
| 1 | La formació del plural · Els sons de la essa |
| 2 | j/g, x/ix, tx/ig · Paraules que sonen igual |
| 3 | Les grafies b, v i h · La ela geminada |
| 4 | Els signes de puntuació |
| 5 | L’accentuació · La dièresi |
| 6 | L’apòstrof · El guionet · La combinació de pronoms febles |

Cada bloc té cinc apartats:

- **Normes:** regles breus amb exemples i la grafia clau marcada.
- **Practica:** sessions de 5, 8 o 12 exercicis triats a l’atzar d’un banc de 409 exercicis verificats, amb correcció immediata, segon intent amb pista i resum final.
- **Dictats:** 4 dictats per bloc (24 en total), per fragments de punt a punt, amb correcció paraula per paraula. Si el dispositiu no té veu en català, hi ha un mode docent perquè un adult llegeixi el text.
- **Fitxes:** fitxes DIN A4 en PDF, diferents cada vegada, amb el logotip de l’escola. Opcionalment poden incloure un recordatori de normes, espai per a un dictat, un solucionari i un format ampliat. Els exercicis no queden mai partits entre dues pàgines.
- **Passatemps:** sopa de lletres (dos nivells), síl·labes desordenades i relaciona, amb el vocabulari de cada tema i pistes.

### A més a més

- **Diccionari:** cerca paraules al DIEC2 de l’Institut d’Estudis Catalans. Els resultats s’obren a la web oficial, en una pestanya nova.
- **Pastorets:** què són, els tres mons de l’escenari, l’origen, els autors destacats, els tipus de Pastorets, la figura de Joaquim Vilà i Folch i els seus articles sobre els Pastorets, amb les fonts consultades.

### Disseny Universal per a l’Aprenentatge (DUA)

- Opcions de lectura: mida del text (normal, gran, molt gran) i més espai entre lletres i línies.
- Botons per escoltar i aturar l’àudio de les normes, els enunciats i els textos, si el dispositiu té veu en català.
- Desplegable «Recorda la norma» a cada exercici, que l’alumne obre només si el necessita.
- Segon intent amb pista abans de mostrar la solució.
- Controls grans, colors amb bon contrast, mode fosc automàtic i respecte per la preferència de reduir animacions.

Totes les regles segueixen la normativa vigent de l’Institut d’Estudis Catalans (Ortografia catalana, 2016–2017). Per exemple, *dona* (del verb *donar*) ja no porta accent.

## Com publicar-la a GitHub Pages

1. Crea un repositori nou a GitHub (per exemple, `llengua-catalana-sise`).
2. Puja-hi els fitxers `index.html` i `README.md` (botó **Add file → Upload files**).
3. Ves a **Settings → Pages**.
4. A **Build and deployment**, tria **Deploy from a branch**, la branca `main` i la carpeta `/ (root)`, i desa.
5. Al cap d’un o dos minuts, l’aplicació estarà disponible a `https://NOM-USUARI.github.io/llengua-catalana-sise/`.

No cal instal·lar res ni compilar res: tota l’aplicació és un sol fitxer `index.html`.

## Detalls tècnics

- **Un sol fitxer:** HTML, CSS i JavaScript sense marcs de treball. El logotip va incrustat dins del fitxer.
- **Dependències externes**, carregades des d’internet:
  - [jsPDF 2.5.1](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js) per generar les fitxes en PDF.
  - Les tipografies Atkinson Hyperlegible i Bricolage Grotesque, de Google Fonts.
- **Sense connexió:** l’aplicació funciona, però no es poden descarregar fitxes en PDF i es fan servir les tipografies del sistema.
- **Veu:** fa servir la síntesi de veu del navegador. A l’iPad, comprova que hi hagi una veu catalana a *Configuració → Accessibilitat → Contingut llegit → Veus*. Molts ordinadors amb Windows no en porten cap per defecte; en aquest cas, els botons d’escoltar no apareixen i els dictats es poden fer en mode docent.
- **Privacitat:** no es recullen dades. Només es guarden, al navegador de cada dispositiu, les opcions de lectura (mida del text, espaiat i àudio).

## Crèdits i drets

- **Contingut:** textos, exercicis, dictats i vocabulari originals, basats en la programació de l’Ortogrup lila i revisats segons la normativa de l’IEC.
- **Pastorets:** informació elaborada a partir de les fonts citades a l’aplicació (Tradicionari, Viquipèdia, Festes.org, Biblioteca Virtual Miguel de Cervantes i Universitas Tarraconensis).
- **Logotip:** el logotip d’Escola Thau Barcelona pertany a l’escola. Si el repositori és públic, comproveu que l’escola n’autoritza l’ús.
- **Llicència:** pendent de decidir per part de l’autor o l’escola. Sense llicència, el codi es pot veure però no reutilitzar lliurement.
