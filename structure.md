# Concessionario

## (Table) cars:

- id | BIGINT - PRIMARY KEY, AUTO_INCREMENT, UNIQUE
- marca | VARCHAR(30) - NOTNULL
- modello | VARCHAR(255) - NOTNULL
- allestimento | VARCHAR(255) - NULL
- anno | YEAR - NOTNULL
- chilometraggio | FLOAT (7,3) - NOTNULL
- potenza | INT - NOTNULL
- colore | VARCHAR(20) - NOTNULL
- tipo_vernice | VARCHAR(20) - NULL  
- rivestimenti | VARCHAR(255) - NULL
- carrozzeria (berlina, monovolume ecc.) | VARCHAR(20) - NOTNULL  
- porte | TINYINT - NOTNULL
- posti | TINYINT - NOTNULL
- prezzo | DECIMAL(10,2) - NOTNULL
- condizioni | VARCHAR(20) - NOTNULL
- neopatentati | TINYINT (vero/falso | 1/0) - NULL
- proprietari | TINYINT - NOTNULL
- ultimo_tagliando | DATE - NULL
- cambio | VARCHAR(20) - NOTNULL 
- numero_rapporti | TINYINT - NOTNULL
- cilindrata | INT - NOTNULL
- numero_cilindri | TINYINT - NULL
- peso | INT - NULL
- trazione | VARCHAR(20) - NOTNULL
- alimentazione | VARCHAR(20) - NOTNULL
- consumi | TINYINT - NULL
- emissioni | MEDIUMINT - NULL
- classe emissioni | TINYINT - NOTNULL
- optional | TEXT - NULL
- note | TEXT - NULL