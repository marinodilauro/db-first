# Description
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

DB name: carDealer

Table name: cars
- id | INDEX | INT or BIGINT | PK | NOTNULL | UNIQUE | AI
- manufacturer | VARCHAR(20) | NOTNULL
- model | VARCHAR(20) | NOTNULL
- tier | VARCHAR(20) | NULL
- year | YEAR | NOTNULL
- fuel_type | ENUM(Benzina, Diesel, Ibrida, Elettrica, GPL, Idrogeno) | NULL      
- transmission | ENUM(Manuale, Automatico, Semi-automatico, CVT, DCT) | NULL
- engine_size | SMALLINT | NULL
- horse_power | SMALLINT | NULL
- mileage | MEDIUMINT | NULL
- color | VARCHAR(25) | NULL
- condition | ENUM(Nuovo, Usato, Km0) | NULL
- location | VARCHAR(50) | NOTNULL
- is_available | TINYINT | NOTNULL | DEFAULT (1)
- image | NULL | DEFAULT ('default image link')
- price | MEDIUMINT | NOTNULL
- note | TEXT | NULL

id | manufacturer | model | tier | year | fuel_type | transmission | engine_size | horse_power | mileage | color | condition | location | is_available | image | price | note | id | manufacturer | model
:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---
1
2
3