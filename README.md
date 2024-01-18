
# Database Auto Usate

### Colonne:

- **ID**: Identificatore unico per ogni auto (INT, AUTO_INCREMENT, NOT NULL, UNIQUE).
- **Marca**: Marca dell'auto (VARCHAR(50), NOT NULL).
- **Modello**: Modello dell'auto (VARCHAR(50), NOT NULL).
- **Anno**: Anno di produzione dell'auto (YEAR, NOT NULL).
- **Chilometraggio**: Chilometri percorsi dall'auto (INT, NOT NULL).
- **Tipo_Carburante**: Tipo di carburante dell'auto (VARCHAR(30)).
- **Prezzo**: Prezzo di vendita dell'auto (DECIMAL(10, 2), NOT NULL).
- **Descrizione**: Descrizione dettagliata dell'auto (TEXT).
- **Data_Inserimento**: Data e ora dell'inserimento dell'auto nel database (DATETIME, DEFAULT CURRENT_TIMESTAMP).
- **Stato**: Stato dell'auto, es. 'In vendita', 'Venduta' (VARCHAR(30)).

