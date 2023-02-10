CAR|TYPES|INDICI|ATTRIBUTI
---|---|---|---|
ID|INT|PRIMARY KEY|NOT NULL, AUTO INCREMENT
Quando è arrivata in azienda|DATE||NOT NULL
Targa|CHAR(7)||NOT NULL
Usata|TINYINT(1)||NOT NULL(1)
Costo|FLOAT(7,3)||NOT NULL
Marca|VARCHAR(50)||NOT NULL
Modello|VARCHAR(50)||NOT NULL
Classe del veicolo|VARCHAR(50)||NOT NULL
Km percorsi|FLOAT(6,3)||NOT NULL
Anno di fabbricazione|YEAR||NOT NULL
Tipo di motore|CHAR(2)||NOT NULL
Cilindrata|FLOAT(5,3)||NOT NULL
Tipo di trasimissione|CHAR(2)||NOT NULL (0)
Colore|CHAR(7)||NULL
Full optional|CHAR(1)|| DEFAULT(0)
Numero di sedili|TINYINT(10)||NULL
Tappezzeria|CHAR(3)||NULL
Paese di origine|CHAR(3)||NULL
Numero di chiavi|TINYINT(10)||NULL
Auto incidentata|TINYINT(1)||DEFAULT(0)
Revisione valida fino al |DATE||NULL



