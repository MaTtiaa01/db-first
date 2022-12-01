# database

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario


##Cars:

    Column:
    - id | BIGINT AUTO_INCREMENT 
    - km | SMALL/MEDIUMINT
    - year | YEAR
    - model | VARCHAR(200)
    - price | FLOAT(I,D) (8,2)
    - note | TEXT
    - engine | TEXT
    - gearbox | TEXT
    - consumption | (10L/100KM) CHAR(15)

