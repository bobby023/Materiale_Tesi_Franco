# Analisi del trade-off tra accuratezza, fairness e sostenibilità ambientale
Materiale prodotto durante il percorso di tesi 
# Contenuto
Contiene materiali prodotti durante l'analisi del trade-off tra accuratezza, fairness e sostenibilità ambientale nei Recommender Systems.
## Struttura della repository
├── File_Config/ # File YAML di configurazione degli esperimenti
├── log_results/ # Log e metriche dei risultati degli esperimenti
├── emissions.csv # Dati sulle emissioni energetiche/CO₂ generate durante gli esperimenti
├── README.md # Documentazione della repository


### Dettaglio contenuti

- **File_Config/**  
  Contiene file `.yaml` che definiscono le configurazioni per l'esecuzione degli esperimenti con i diversi modelli e parametri.  
  Esempi di file:  
  - `test_FOCF.yaml` — configurazione per il modello FOCF
  - `test_nfccf.yaml` — configurazione per il modello NFCF  
  - `test_originale.yaml` — configurazione di riferimento  
  - `test_pfcn.yaml` — configurazione per il modello PFCN_DMF  

- **log_results/**  
  Contiene i log degli esperimenti eseguiti, con metriche di accuratezza, fairness e tempi di esecuzione.

- **emissions.csv**  
  File CSV che riporta le emissioni energetiche e stima della CO₂ prodotta durante gli esperimenti.


