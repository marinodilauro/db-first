# Description
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB name: carDealer

Table name: cars
- id | INDEX | INT or BIGINT
- manufacturer | VARCHAR(20)
- model | VARCHAR(20)
- tier | VARCHAR(20)
- year | YEAR
- fuel_type | VARCHAR(20)
- transmission | VARCHAR(20)
- engine_size | SMALLINT
- horse_power | SMALLINT
- mileage | MEDIUMINT
- color | VARCHAR(25)
- condition | VARCHAR(20)
- location | VARCHAR(50)
- price | MEDIUMINT