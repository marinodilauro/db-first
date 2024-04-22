# Description
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB name: carDealer

Table name: cars
- id | INDEX | INT or BIGINT | PK | NOTNULL | UNIQUE | AI
- manufacturer | VARCHAR(20) | NOTNULL
- model | VARCHAR(20) | NOTNULL
- tier | VARCHAR(20) | NULL
- year | YEAR | NOTNULL
- fuel_type | VARCHAR(20) | NULL
- transmission | VARCHAR(20) | NULL
- engine_size | SMALLINT | NULL
- horse_power | SMALLINT | NULL
- mileage | MEDIUMINT | NULL
- color | VARCHAR(25) | NULL
- condition | VARCHAR(20) | NULL
- location | VARCHAR(50) | NOTNULL
- is_available | TINYINT | NOTNULL | DEFAULT (1)
- price | MEDIUMINT | NOTNULL