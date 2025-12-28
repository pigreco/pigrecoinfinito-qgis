# Catalogo Plugin QGIS 🗺️

Repository centralizzato per scaricare e installare plugin QGIS specializzati per l'elaborazione di dati geografici e catastali italiani.

## Indice

- [Catalogo Plugin QGIS 🗺️](#catalogo-plugin-qgis-️)
  - [Indice](#indice)
  - [📦 Plugin Disponibili](#-plugin-disponibili)
    - [Confini Amministrativi ISTAT](#confini-amministrativi-istat)
    - [CatastoIT GML Merger Pro](#catastoit-gml-merger-pro)
    - [ISTAT Boundaries Downloader](#istat-boundaries-downloader)
    - [GeoPackage Project Manager](#geopackage-project-manager)
  - [🚀 Installazione](#-installazione)
    - [Metodo 1: Repository Manager QGIS (Consigliato)](#metodo-1-repository-manager-qgis-consigliato)
    - [Metodo 2: Download Manuale](#metodo-2-download-manuale)
  - [📁 File del Repository](#-file-del-repository)
  - [🌐 Accesso](#-accesso)
  - [🤝 Contribuzioni](#-contribuzioni)
  - [📧 Contatti](#-contatti)
  - [📜 Licenza](#-licenza)
  - [⭐ Apprezzi?](#-apprezzi)

## 📦 Plugin Disponibili

### Confini Amministrativi ISTAT
**Versione:** 1.1.0 | **Autore:** Totò Fiandaca | **Categoria:** Vector

Plugin avanzato per scaricare confini amministrativi italiani dal sito ISTAT e griglia di popolazione 2021 su standard europeo.

**Funzionalità:** Download automatico ZIP da ISTAT • Selezione tra 4 tipi di confini • Griglia popolazione 2021 (1 km², EPSG:3035) • Download multipli • Interfaccia italiana

**Requisiti:** QGIS 3.0+

### CatastoIT GML Merger Pro
**Versione:** 0.3c | **Autori:** Salvatore Fiandaca, Giulio Fattori | **Categoria:** Plugins

Plugin avanzato per scaricare, estrarre e unire file GML del catasto italiano con gestione ottimizzata della memoria.

**Funzionalità:** Download automatico ZIP catastali • Estrazione intelligente file • Unione file GML • Conversione GPKG • Caricamento automatico con stili • Supporto MAP e PLE

**Requisiti:** QGIS 3.22+

### ISTAT Boundaries Downloader
**Versione:** 0.2 | **Autore:** Salvatore Fiandaca | **Categoria:** Vector

Plugin QGIS per scaricare confini amministrativi italiani tramite le API di onData con date di riferimento dal 1991 al 2025.

**Funzionalità:** Download confini in multipli formati (Shapefile, GeoPackage, CSV, KML, KMZ) • Filtri avanzati per regione e provincia • Caricamento automatico in QGIS • Supporto ripartizioni geografiche • Interfaccia semplice e intuitiva

**Requisiti:** QGIS 3.20+

### GeoPackage Project Manager
**Versione:** 3.7.1 | **Autore:** Salvatore Fiandaca | **Categoria:** Database

Plugin per gestione completa dei progetti QGIS all'interno di file GeoPackage con funzionalità avanzate.

**Funzionalità:** Salvataggio e caricamento progetti • Rinomina, duplica, elimina progetti • Clonazione GeoPackage con aggiornamento percorsi • Esportazione QGS/QGZ • Versioning automatico e timestamp • Gestione stili layer • Visualizzazione relazioni • Ottimizzazione database • Sistema metadati con tooltip • Protezione progetti con trigger SQLite

**Requisiti:** QGIS 3.0+

## 🚀 Installazione

### Metodo 1: Repository Manager QGIS (Consigliato)
- Apri QGIS → Estensioni → Gestisci e installa estensioni
- Clicca Impostazioni → Aggiungi repository
- Incolla: `https://pigreco.github.io/pigrecoinfinito-qgis/plugins.xml`
- Dai un nome al repository e clicca OK
- Seleziona il plugin e clicca Installa

### Metodo 2: Download Manuale
- Scarica il file .zip del plugin
- Estrai nella cartella dei plugin QGIS
- Riavvia QGIS
- Attiva da Estensioni → Gestisci e installa estensioni

## 📁 File del Repository
- `plugins.xml` - Catalogo ufficiale dei plugin
- `README.md` - Questo file
- `CONTRIBUTING.md` - Guida per i contributi
- `LICENSE` - Licenza GPL-2.0

## 🌐 Accesso
- **Repository:** https://github.com/pigreco/pigrecoinfinito-qgis
- **Sito:** https://pigreco.github.io/pigrecoinfinito-qgis/
- **Catalogo XML:** https://pigreco.github.io/pigrecoinfinito-qgis/plugins.xml

## 🤝 Contribuzioni
- Apri una Issue per discussioni
- Crea una Pull Request per cambiamenti
- Contatta [@pigreco](https://github.com/pigreco) su GitHub

Consulta [CONTRIBUTING.md](CONTRIBUTING.md) per dettagli.

## 📧 Contatti
- **GitHub:** [@pigreco](https://github.com/pigreco)
- **Email:** pigrecoinfinito@gmail.com
- **Issues:** [GitHub Issues](https://github.com/pigreco/pigrecoinfinito-qgis/issues)

## 📜 Licenza
Distribuito con licenza GPL-2.0, compatibile con QGIS.

## ⭐ Apprezzi?
Se trovi utile questo catalogo, metti una stella su GitHub!

---
**Ultimo aggiornamento:** 28 Dicembre 2025 | **Versione:** 1.0.0
                                                   
