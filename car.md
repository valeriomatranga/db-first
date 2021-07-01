<!-- 
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
-->
#car:

## (table) car_used:

- id                        BIGINT AUTOINCEMENT PRIMARY KEY UNIQUE      NOT NULL        
- casa produttrice          VARCHAR(30) INDEX                           NOT NULL
- modello                   VARCHAR(50) INDEX                           NOT NULL    
- numero porte              TINYINT                                     NOT NULL    
- colore                    VARCHAR(30)                                 NOT NULL
- allestimento              VARCHAR(50)                                 NOT NULL
- cilindrata                VARCHAR(50)                                 NOT NULL
- alimentazione             VARCHAR(30)                                 NOT NULL
- km percorsi               MEDIUMINT                                   NOT NULL
- anno immatricolazione     YEAR INDEX                                  NOT NULL
- numero proprietari        TINYINIT                                    NULL
- condizione                VARCHAR(50) INDEX                           NULL
- FOTO                      VARCHAR(255)                                NULL
- prezzo di vendita         DECIMAL(8,2) INDEX                          NOT NULL
- prezzo nuovo              DECIMAL(9,2)                                NULL
- note                      TEXT                                        NULL