# SM1 Storyboard: risorse / resources

**Italiano.** Questo archivio contiene i file che il modulo Storyboard 3D di **SM1 CinemaTools** (Sanmartinouno Srl, Bologna)
scarica la prima volta che servono: le persone (corpi, pelli, capelli, barbe, vestiti, comparse, miniature: 253 file) e gli alberi
veri alleggeriti (5 file). Il programma li prende da `https://raw.githubusercontent.com/trovatodaniele95-bit/sm1-storyboard-risorse/v2/` + il percorso del file e controlla l'impronta SHA-256 di
ognuno (elenco in `IMPRONTE.sha256`, uguale a quello scritto nel programma). I file si servono **dal tag** (`v1`): un
aggiornamento sarà un tag nuovo e i programmi già installati continueranno a trovare i loro file.

Tutti i file sono **CC0 1.0** (dominio pubblico): da dove viene ognuno, chi l'ha fatto e cosa abbiamo cambiato è in `LICENZE.md`.
In tutto 258 file, 175,3 MB; il più grande è `alberi/island_tree_02.glb` (9,9 MB). Nessun file supera i 50 MB.

Per controllare una copia: `shasum -a 256 -c IMPRONTE.sha256` (Mac) oppure `sha256sum -c IMPRONTE.sha256` (Linux).

**English.** This archive holds the files that the 3D Storyboard module of **SM1 CinemaTools** (Sanmartinouno Srl, Bologna, Italy)
downloads the first time they are needed: people (bodies, skins, hair, beards, clothes, extras, thumbnails: 253 files) and
lightened real trees (5 files). The program fetches them from `https://raw.githubusercontent.com/trovatodaniele95-bit/sm1-storyboard-risorse/v2/` + the file path and checks each SHA-256 hash
(list in `IMPRONTE.sha256`, identical to the one built into the program). Files are served **from the tag** (`v1`): an update
will be a new tag, so installed programs keep finding their files.

Every file is **CC0 1.0** (public domain): source, author and our changes for each file are in `LICENZE.md`.
258 files, 175,3 MB in total; the largest is `alberi/island_tree_02.glb` (9,9 MB). No file is larger than 50 MB.

To check a copy: `shasum -a 256 -c IMPRONTE.sha256` (macOS) or `sha256sum -c IMPRONTE.sha256` (Linux).
