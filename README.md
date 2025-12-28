# Catalogo Plugin QGIS - pigrecoinfinito-qgis 🗺️

Benvenuto nel **Catalogo di Plugin QGIS** di pigreco! Un repository centralizzato per scaricare e installare plugin QGIS specializzati per lavori con dati geografici e catastali italiani.

---

## 📋 Descrizione

Questo catalogo fornisce una raccolta curata di plugin QGIS per l'elaborazione di dati geografici italiani, con particolare attenzione a:

- ✅ Dati catastali italiani (confini e particelle)
- - ✅ Confini amministrativi ISTAT
  - - ✅ Griglie di popolazione censuaria
    - - ✅ Gestione e unione di file GML
     
      - ---

      ## 📦 Plugin Disponibili

      ### 1. Confini Amministrativi ISTAT

      **Versione:** 1.1.0
      **Autore:** Totò Fiandaca
      **Categoria:** Vector

      Plugin avanzato per scaricare confini amministrativi italiani dal sito ISTAT e la griglia di popolazione 2021 su standard europeo (Eurostat).

      #### Funzionalità:

      - 🔄 Download automatico dei file ZIP da ISTAT
      - - 🗺️ Selezione tra 4 tipi di confini (Regioni, Province, Comuni, Ripartizioni)
        - - 📊 Griglia di popolazione 2021 (celle 1 km², EPSG:3035)
          - - ⚙️ Download multipli simultanei
            - - 🇮🇹 Interfaccia completamente in italiano
             
              - **Requisiti:** QGIS 3.0+
             
              - ---

              ### 2. CatastoIT GML Merger Pro

              **Versione:** 0.3c
              **Autori:** Salvatore Fiandaca, Giulio Fattori
              **Categoria:** Plugins

              Plugin avanzato per scaricare, estrarre e unire file GML del catasto italiano con gestione ottimizzata della memoria.

              #### Funzionalità:

              - 📥 Download automatico dei file ZIP catastali
              - - 📦 Estrazione intelligente dei file
                - - 🔗 Unione di file GML in un unico dataset
                  - - 🔄 Conversione in formato GPKG
                    - - 🎯 Caricamento automatico in QGIS con stili predefiniti
                      - - 🗺️ Supporto per mappe (MAP) e particelle (PLE)
                       
                        - **Requisiti:** QGIS 3.22+
                       
                        - ---

                        ## 🚀 Come Installare

                        ### Metodo 1: Via Repository Manager di QGIS (Consigliato)

                        1. Apri QGIS
                        2. 2. Vai a **Estensioni → Gestisci e installa estensioni**
                           3. 3. Clicca su **Impostazioni**
                              4. 4. Clicca su **Aggiungi repository**
                                 5. 5. Incolla l'URL del catalogo:
                                    6.    ```
                                             https://pigreco.github.io/pigrecoinfinito-qgis/plugins.xml
                                             ```
                                          6. Dai un nome al repository (es: "Catalogo Pigreco")
                                          7. 7. Clicca **OK**
                                             8. 8. I plugin appariranno automaticamente nella scheda **Tutti** o **Non installati**
                                                9. 9. Seleziona il plugin desiderato e clicca **Installa plugin**
                                                  
                                                   10. ### Metodo 2: Download Manuale
                                                  
                                                   11. 1. Scarica il file `.zip` del plugin dalla sezione Plugin Disponibili
                                                       2. 2. Estrai il file nella cartella dei plugin QGIS
                                                          3. 3. Riavvia QGIS
                                                             4. 4. Attiva il plugin da **Estensioni → Gestisci e installa estensioni**
                                                               
                                                                5. ---
                                                               
                                                                6. ## 📁 Struttura del Repository
                                                               
                                                                7. ```
                                                                   pigrecoinfinito-qgis/
                                                                   ├── README.md              # Questo file
                                                                   ├── CONTRIBUTING.md        # Guida per i contributi
                                                                   ├── LICENSE               # Licenza GPL-2.0
                                                                   ├── plugins.xml           # Catalogo ufficiale dei plugin
                                                                   └── docs/                 # Documentazione aggiuntiva
                                                                   ```

                                                                   ---

                                                                   ## 🌐 Hosting

                                                                   Il catalogo è ospitato gratuitamente su **GitHub Pages** ed è accessibile a:

                                                                   **🔗 https://pigreco.github.io/pigrecoinfinito-qgis/**

                                                                   ---

                                                                   ## 📊 Statistiche

                                                                   | Metrica | Valore |
                                                                   |---------|--------|
                                                                   | Plugin Totali | 2 |
                                                                   | Versione QGIS Min | 3.0 |
                                                                   | Piattaforme | Windows, macOS, Linux |
                                                                   | Ultimo Aggiornamento | 28 Dicembre 2025 |
                                                                   | Versione Catalogo | 1.0.0 |

                                                                   ---

                                                                   ## 💡 Come Aggiungere Nuovi Plugin

                                                                   Per aggiungere un nuovo plugin a questo catalogo:

                                                                   1. Crea la cartella del plugin con la struttura standard QGIS
                                                                   2. 2. Aggiungi un file `metadata.txt` con i metadati
                                                                      3. 3. Crea un file `.zip` del plugin
                                                                         4. 4. Modifica il file `plugins.xml` con le informazioni del nuovo plugin
                                                                            5. 5. Carica il file `.zip` nel repository
                                                                               6. 6. Fai un commit e push su GitHub
                                                                                 
                                                                                  7. ### Esempio di entry nel plugins.xml:
                                                                                 
                                                                                  8. ```xml
                                                                                     <pyqgis_plugin name="Nome Plugin" version="1.0.0">
                                                                                       <description>Descrizione breve</description>
                                                                                       <about>Descrizione dettagliata</about>
                                                                                       <version>1.0.0</version>
                                                                                       <qgis_minimum_version>3.0</qgis_minimum_version>
                                                                                       <homepage>https://github.com/...</homepage>
                                                                                       <file_name>plugin-name.zip</file_name>
                                                                                       <icon>icons/icon.png</icon>
                                                                                       <author_name>Nome Autore</author_name>
                                                                                       <download_url>https://pigreco.github.io/pigrecoinfinito-qgis/plugin-name.zip</download_url>
                                                                                       <uploaded_by>username</uploaded_by>
                                                                                       <experimental>False</experimental>
                                                                                       <deprecated>False</deprecated>
                                                                                       <tracker>https://github.com/.../issues</tracker>
                                                                                       <repository>https://github.com/.../</repository>
                                                                                       <tags>tag1, tag2, tag3</tags>
                                                                                       <category>Vector</category>
                                                                                     </pyqgis_plugin>
                                                                                     ```

                                                                                     ---

                                                                                     ## 🤝 Contribuzioni

                                                                                     I contributi sono benvenuti! Se hai suggerimenti o vuoi aggiungere un plugin:

                                                                                     - 📝 **Apri una Issue** per discussioni
                                                                                     - - 🔄 **Crea una Pull Request** con i tuoi cambiamenti
                                                                                       - - 💬 **Contatta @pigreco** su GitHub
                                                                                        
                                                                                         - Consulta il file [CONTRIBUTING.md](CONTRIBUTING.md) per ulteriori dettagli.
                                                                                        
                                                                                         - ---

                                                                                         ## 📧 Contatti

                                                                                         - **GitHub:** [@pigreco](https://github.com/pigreco)
                                                                                         - - **Email:** pigrecoinfinito@gmail.com
                                                                                           - - **Issues:** [GitHub Issues](https://github.com/pigreco/pigrecoinfinito-qgis/issues)
                                                                                            
                                                                                             - ---

                                                                                             ## 📜 Licenza

                                                                                             Questo catalogo e i plugin al suo interno sono distribuiti con licenze open-source. Consulta i singoli repository per i dettagli della licenza.

                                                                                             I plugin in questo catalogo sono compatibili con la licenza **GPL-2.0** di QGIS.

                                                                                             ---

                                                                                             ## ⭐ Se Ti Piace

                                                                                             Se trovi utile questo catalogo, considera di mettere una stella ⭐ su GitHub!

                                                                                             ---

                                                                                             **Ultimo aggiornamento:** 28 Dicembre 2025
                                                                                             **Versione Catalogo:** 1.0.0
                                                                                             
