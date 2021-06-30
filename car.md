<!-- 
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
-->
#car:

## (table) car_used:

- casa produttrice          VARCHAR(30) NOT NULL
- modello                   VARCHAR(50) NOT NULL    
- numero porte              TINYINT     NOT NULL    
- colore                    VARCHAR(30) NOT NULL
- allestimento              VARCHAR(50) NOT NULL
- cilindrata                VARCHAR(50) NOT NULL
- alimentazione             VARCHAR(30) NOT NULL
- km percorsi               SMALL       NOT NULL
- anno immatricolazione     YEAR        NOT NULL
- numero proprietari        TINYINIT    NULL
- prezzo di vendita         MEDIUMINT   NOT NULL
- prezzo nuovo              MEDIUMINT   NULL
