# Ransomware TTPs Analysis

## Descrizione

Questo progetto esegue un'analisi delle Tecniche, Tattiche e Procedure (TTP) utilizzate dai gruppi ransomware. Utilizzando un dataset Excel che contiene informazioni sui gruppi di ransomware, gli attacchi e le TTP associate, il progetto genera statistiche trimestrali e settoriali sulle TTP più utilizzate.

### Funzionalità principali

- **Classifica delle TTP:** Identifica le TTP più utilizzate da vari gruppi ransomware.
- **Analisi per trimestre:** Raggruppa e visualizza l'uso delle TTP per trimestre.
- **Analisi settoriale:** Mostra le TTP più utilizzate nei diversi settori industriali.
- **Visualizzazione:** Crea grafici delle TTP più frequenti per trimestre e settore industriale.
- **Esportazione dei risultati:** Esporta le statistiche in un file CSV.

## Struttura dei file

- `Dataset Ransomware.xlsx`: Il file Excel contenente i dati di attacchi ransomware, TTP e profili dei gruppi.
- `ransomware_analysis.py`: Script Python per eseguire l'analisi e generare i grafici.
- `PlotTTPS/`: Cartella dove vengono salvati i grafici generati.
- `ransomware_analysis_optimized.csv`: File CSV con i risultati finali dell'analisi.

## Requisiti

- Python 3.x
- Pandas
- Matplotlib
- Seaborn

Puoi installare tutte le dipendenze necessarie eseguendo il seguente comando:

```bash
pip install -r requirements.txt
```
## License
This software is released under the GPL-3 license, which allows for its use, modification and distribution according to the terms of this license. In compliance with the GPL-3 license, any distribution or modification of this software must give credit to Pietro Melillo, the original author.
