| **Proprietà**       | **Tipo**            | **Descrizione**                                                   |
|---------------------|---------------------|-------------------------------------------------------------------|
| `id`                | INT (PK)  NOTNULL   | Identificatore univoco per ogni auto                              |
| `make`              | VARCHAR(64)         | Marca del veicolo                                                 |
| `model`             | VARCHAR(64)         | Modello del veicolo                                               |
| `year`              | DATE                | Anno di fabbricazione                                                                                                   |
| `car_mileage`       | INT                 | Chilometraggio in chilometri                                                                                                      |
| `fuel_type`         | VARCHAR(32)         | Tipo di carburante                                                |
| `transmission`      | VARCHAR(32)         | Tipo di cambio/trasmissione                                       |
| `color`             | VARCHAR(32)         | Colore del veicolo                                                |
| `price_eur`         | DECIMAL(10, 2)      | Prezzo in euro                                                    |
| `description`       | TEXT                | Descrizione                                                       |
| `sold_date`         | DATE                | Indica se l'auto è già stata venduta con una data corrispettiva   |
| `listed_date`       | DATE                | Data in cui l'auto è stata messa in vendita|
| `dealer_id`         | INT (FK)            | Identificatore del concessionario (messa a FK nel caso servisse una tabella dedicata ai concessionari con le corrispettive info)
