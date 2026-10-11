# configurator-aplicatii-distributie
Artefacte publice de distribuție pentru Configurator aplicații. Codul sursă și tichetele rămân în depozitul privat.

Directorul `descriptors/banii-mei/` conține descriptori semnați pentru pachetele Banii mei. Un descriptor nu activează singur instalarea: Configuratorul folosește numai release-urile indicate de `catalog.json` semnat și valid.

`catalog.json` din rădăcină este catalogul activ pentru proba inițială 0.1.0. `testing/catalog-stable-proposal-0.1.0.json` păstrează copia exactă verificată înainte de activare. Release-urile sunt marcate ca pre-release pentru această probă. Instalările Banii mei existente nu sunt actualizate automat; trecerea lor la noul Configurator va fi lansată separat.
