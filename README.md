# bi
-- criação das tabelas
BULK INSERT autor
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\autor.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT dias_atendimento
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\dias_atendimento.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT escultura
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\escultura.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT fornecedor
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\fornecedor.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT manutencao
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\manutencao.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT materiaprima
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\materiaprima.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT metal
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\metal.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT obra
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\obra.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT pais
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\pais.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT pedra
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\pedra.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT pintura
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\pintura.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT restaurador
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\restaurador.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);

BULK INSERT salao
FROM 'C:\Users\gusta\OneDrive\Documentos\dados\salao.csv'
WITH (
    FIELDTERMINATOR = ',',
    ROWTERMINATOR = '\n',
    FIRSTROW = 2
);
