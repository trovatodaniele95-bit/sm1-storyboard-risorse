# SM1 Storyboard: risorse / resources

**Italiano.** Questo archivio contiene i file che il modulo Storyboard 3D di **SM1 CinemaTools** (Sanmartinouno Srl, Bologna)
scarica la prima volta che servono: le persone (corpi, pelli, capelli, barbe, vestiti, comparse, miniature: 253 file), gli alberi
veri alleggeriti (5 file) e **128 modelli** di veicoli e oggetti (cartella `modelli/`, in otto pacchetti facoltativi: veicoli moderni, veicoli d'epoca,
altri mezzi, strada, natura, casa, locali, scena). Il programma li prende da `https://raw.githubusercontent.com/trovatodaniele95-bit/sm1-storyboard-risorse/v3/` + il percorso del file e controlla l'impronta SHA-256 di
ognuno (elenco in `IMPRONTE.sha256`, uguale a quello scritto nel programma). I file si servono **dal tag** (`v3`, che contiene anche tutti i file di `v1` e `v2`
con gli stessi percorsi): un aggiornamento sarà un tag nuovo e i programmi già installati continueranno a trovare i loro file.

**Licenze.** Persone e alberi: **CC0 1.0** (dominio pubblico). I modelli in `modelli/`: **CC-BY 4.0**, fatti da altri autori su Sketchfab e adattati da noi
(separati, alleggeriti, riscalati; targhe, stemmi e scritte tolti). **Chi li riusa deve citare l'autore**: titolo originale, autore, pagina e licenza di ogni file
sono in `LICENZE.md`; per citarli basta copiare la riga del file (per esempio: «Taxi» da «Generic civil service vehicles pack» di Comrade1280, CC-BY 4.0, modificato).
In tutto 386 file, 332,2 MB; il più grande è `alberi/island_tree_02.glb` (9,9 MB). Nessun file supera i 50 MB.

Per controllare una copia: `shasum -a 256 -c IMPRONTE.sha256` (Mac) oppure `sha256sum -c IMPRONTE.sha256` (Linux).

**English.** This archive holds the files that the 3D Storyboard module of **SM1 CinemaTools** (Sanmartinouno Srl, Bologna, Italy)
downloads the first time they are needed: people (bodies, skins, hair, beards, clothes, extras, thumbnails: 253 files), lightened real trees (5 files)
and **128 models** of vehicles and objects (folder `modelli/`, in eight optional packs: modern vehicles, vintage vehicles, other vehicles, street, nature, home, venues, stage).
The program fetches them from `https://raw.githubusercontent.com/trovatodaniele95-bit/sm1-storyboard-risorse/v3/` + the file path and checks each SHA-256 hash (list in `IMPRONTE.sha256`, identical to the one built into the program).
Files are served **from the tag** (`v3`, which also holds every `v1` and `v2` file at the same paths): an update will be a new tag, so installed programs keep finding their files.

**Licences.** People and trees: **CC0 1.0** (public domain). Models in `modelli/`: **CC-BY 4.0**, made by other authors on Sketchfab and adapted by us (separated, lightened,
rescaled; plates, badges and lettering removed). **Anyone reusing them must credit the author**: original title, author, page and licence of each file are in `LICENZE.md`.
386 files, 332,2 MB in total; the largest is `alberi/island_tree_02.glb` (9,9 MB). No file is larger than 50 MB.

To check a copy: `shasum -a 256 -c IMPRONTE.sha256` (macOS) or `sha256sum -c IMPRONTE.sha256` (Linux).
