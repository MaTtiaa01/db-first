# database

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


##Cars:

    Column:
    - id | BIGINT AUTO_INCREMENT NOTNULL
    - km | SMALL/MEDIUMINT NOTNULL
    - year | YEAR NOTNULL
    - model | VARCHAR(200) NULL
    - price | FLOAT(I,D) (8,2) NULL
    - note | TEXT NULL
    - engine | TEXT NULL
    - gearbox | TEXT NULL
    - consumption | (10L/100KM) CHAR(15) NULL

