## data types:

- strings:

  - varchar(number) limite 255 caratteri,
  - char(number) \\
  - text 65.535 caratteri usato descrizione prodotto,
  - MediumTEXT 16MB
  - longtext 4.2GB usato per salvare porzioni HTML o lunghi testi

- numbers:

  - tinyint ( usa solo 1BYTE num da -128 a 127 boolean),
  - small/medium int ( occupano 2 E 3 BYTE),
  - int ( BYTE da MENO a PIU' 2 milioni),
  - bigint ( il DOPPIO di INT)

- decimals: float(i, d), double(i,d), decimal(i, d)

- dates: DATETIME (YYYY--MM-GG HH:II:SS), DATE, YEAR, TIME, TIMESTAMP ---> date nel database - tipi di dato per le date

## Attributes

- NULL/NOT NULL ( deve essere riempito non puó essere lasciato vuoto)
- DEFAULT ( setta il valore alla colonna qualora non ci fosse nessun valore)
- AUTO_INCREMENT (incrementa di +1 usato colonne tipo numero per gli ID )
- UNIQUE ( valore unico NO ripetizioni all'interno colonna)
