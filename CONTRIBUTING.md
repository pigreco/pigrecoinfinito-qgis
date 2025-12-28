# Linee Guida per i Contributi 🤝

Grazie per il tuo interesse nel contribuire al **Catalogo Plugin QGIS**! Questo documento spiega come puoi aiutarci a migliorare il progetto.

---

## 📋 Come Iniziare

### Fork del Repository
```bash
git clone https://github.com/pigreco/pigrecoinfinito-qgis.git
cd pigrecoinfinito-qgis
```

### Crea un Branch
```bash
git checkout -b feature/nomedellafeature
```

### Apporta le Modifiche
Modifiche il codice o la documentazione localmente.

### Commit le Modifiche
```bash
git commit -m "Descrizione delle modifiche"
```

### Push del Branch
```bash
git push origin feature/nomedellafeature
```

### Crea una Pull Request
Vai su GitHub e crea una Pull Request verso il branch `main`.

---

## 📝 Linee Guida per i Contributi

### Aggiungere un Nuovo Plugin

- **Crea la struttura del plugin** seguendo lo standard QGIS
- **Aggiungi il file `metadata.txt`** con i metadati completi
- **Comprimi il plugin** in un file `.zip`
- **Modifica `plugins.xml`** con l'entry del nuovo plugin:

```xml
<pyqgis_plugin name="Nome Plugin" version="X.X.X">
    <description>Descrizione breve</description>
    <about>Descrizione dettagliata con tutte le funzionalità e caratteristiche</about>
    <version>X.X.X</version>
    <qgis_minimum_version>3.0</qgis_minimum_version>
    <homepage>https://github.com/...</homepage>
    <file_name>nome-plugin.zip</file_name>
    <icon>icons/icon.png</icon>
    <author_name>Nome Autore</author_name>
    <download_url>https://pigreco.github.io/pigrecoinfinito-qgis/nome-plugin.zip</download_url>
    <uploaded_by>username</uploaded_by>
    <experimental>False</experimental>
    <deprecated>False</deprecated>
    <tracker>https://github.com/.../issues</tracker>
    <repository>https://github.com/.../</repository>
    <tags>tag1, tag2, tag3</tags>
    <category>Vector</category>
</pyqgis_plugin>
```

- **Carica il file `.zip`** del plugin nel repository
- **Crea una Pull Request** con il nuovo plugin

---

## 📋 Requisiti per i Contributi

### Qualità del Plugin
- ✅ Il plugin deve funzionare correttamente con QGIS 3.0+
- ✅ Deve avere una descrizione chiara e completa
- ✅ Deve includere un'icona (png 24x24px o svg)
- ✅ Deve avere il file `metadata.txt` completo
- ✅ Deve essere open-source (GPL-2.0 o simile)

### Qualità della Documentazione
- ✅ README.md chiaro e ben strutturato
- ✅ Commenti nel codice dove necessario
- ✅ Requisiti di sistema ben documentati
- ✅ Esempi di utilizzo

### Standard di Codice
- ✅ Codice ben formattato e leggibile
- ✅ Nomi variabili e funzioni chiari
- ✅ Nessun codice commentato lungo
- ✅ Funzioni piccole e focalizzate

                                           ## 🚀 Tipi di Contributi

                                           ### Aggiungere un Nuovo Plugin
                                           Vedi sezione "Aggiungere un Nuovo Plugin" sopra.---

## 🚀 Tipi di Contributi

### Aggiungere un Nuovo Plugin
Vedi sezione "Aggiungere un Nuovo Plugin" sopra.

### Migliorare la Documentazione
- Correggi errori di battitura nel README.md
- Migliora le istruzioni di installazione
- Aggiungi esempi di utilizzo
- Traduci la documentazione

### Segnalare Bug
- Crea una **Issue** con il titolo descrittivo
- Includi:
  - Descrizione del bug
  - Versione di QGIS
  - Passi per riprodurre
  - Risultato atteso vs attuale
  - Possibile soluzione (opzionale)

### Suggerire Miglioramenti
- Crea una **Issue** con il titolo "Feature Request: ..."
- Spiega come il miglioramento aiuterebbe gli utenti
- Fornisci esempi di utilizzo se possibile

---

## ✅ Checklist Prima di Inviare una PR

- [ ] Ho testato il plugin/documentazione
- [ ] Ho seguito le linee guida del codice
- [ ] Ho aggiornato la documentazione
- [ ] Ho aggiunto commit messages descrittivi
- [ ] Ho controllato per errori di battitura
- [ ] Ho verificato che non ci siano conflitti con il branch `main`

---

## 📧 Domande?

Se hai domande sui contributi:
- Apri una **Issue** per discuterne
- Contatta [@pigreco](https://github.com/pigreco) su GitHub
- Invia un'email a: pigrecoinfinito@gmail.com

---

## 🙏 Codice di Condotta

Tutti i contribuenti devono rispettare:
- Tolleranza verso punti di vista diversi
- Critiche costruttive
- Gentilezza e rispetto
- Inclusione di tutti

Il comportamento offensivo non sarà tollerato.

---

**Grazie per contribuire al Catalogo Plugin QGIS!** ⭐
