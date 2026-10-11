# configurator-aplicatii-distributie
Artefacte publice de distribuție pentru Configurator aplicații. Codul sursă și tichetele rămân în depozitul privat.

Directorul `descriptors/banii-mei/` conține descriptori semnați pentru pachetele istorice Banii mei. Un descriptor nu activează singur instalarea: Configuratorul folosește numai release-urile indicate de un `catalog.json` semnat și valid. Catalogul activ va fi publicat separat, după verificarea pachetelor și a fluxului de instalare.

`testing/catalog-stable-proposal-0.1.0.json` este propunerea semnată pentru primul catalog stabil. Rămâne inactivă: aplicația citește numai `catalog.json` din rădăcină. Pachetul Banii mei 2.1.2 din propunere este încă un release draft până la publicarea controlată.
