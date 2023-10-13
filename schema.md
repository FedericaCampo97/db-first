<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

## Table Name 
- Used cars

## Table columns
- id |  PK  BIGINT AUTO_INCREMENTO UNIQUE NOT NULL
- Brand |  TEXT  NOT NULL
- Model |  TEXT  NOT NULL
- Year |  YEAR NULL
- km |  DECIMAL (6, 0) NOT NULL
- Feeding_car |  TEXT  NOT NULL
- Revision |   DATETIME NULL
- Price |  DECIMAL (9, 2) NOT NULL
- Cover_image |  VARCHAR (255)  NOT NULL
- Location_concessionaire |   VARCHAR NOT NULL
- Change_type |  TEXT  NULL