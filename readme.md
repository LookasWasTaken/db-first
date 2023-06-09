# DATABASE MANAGEMENT SYSTEM = DBMS

## Database INTRO

## Types

- Strings: VARCHAR(number), CHAR(number), TEXT, LONGTEXT
- Numbers: TINYINT, SMALLINT, MEDIUMINT, BIGINT, INT
- Decimals: FLOAT(index, decimal), DOUBLE(index, decimal), DECIMAL(index, decimal)
- Dates: DATETIME, DATE, YEAR, TIME, TIMESTAMP

## Entity Name: Used Cars Dealer

## Table Name: Used_Cars

## Table Columns:

- ID            | PRIMARY_KEY, AUTO_INCREMENT, BIGINT, NOTNULL, UNIQUE, INDEX
- CONSTRUCTOR   | VARCHAR(30), NOTNULL, INDEX
- MODEL         | VARCHAR(50), NOTNULL, INDEX
- VERSION       | VARCHAR(30), NULL, INDEX
- FUEL_TYPE     | VARCHAR(30), NOTNULL, INDEX
- CAR_BODY      | VARCHAR(50), NULL
- YEAR          | YEAR, NOTNULL, INDEX
- KM            | MEDIUMINT, NOTNULL, INDEX
- TRANSMISSION  | VARCHAR(20), NOTNULL, INDEX
- ENGINE_SIZE   | SMALLINT, NOTNULL, INDEX
- COUNTRY       | VARCHAR(20), NULL
- CITY          | VARCHAR(20), NULL
- PLATE         | CHAR(7), NOTNULL, UNIQUE
- DESCRIPTION   | TEXT, NULL
- LENGTH        | SMALLINT, NULL
- HEIGHT        | SMALLINT, NULL
- WIDTH         | SMALLINT, NULL
- AUTO_IMAGE    | VARCHAR(255), NOTNULL, UNIQUE
- PRICE         | DECIMAL(9, 2), NOTNULL, INDEX
- POWER_KW      | SMALLINT, NOTNULL
- COLOR         | VARCHAR(25), NOTNULL, INDEX
- DOORS         | TINYINT, DEFAULT(5), INDEX
- SEAT          | TINYINT, DEFAULT(5), INDEX
- OWNERS        | TINYINT, DEFAULT(1)
- CONDITIONS    | VARCHAR(25), NULL, INDEX
- EMISSIONS     | VARCHAR(25), NULL, INDEX
- OPTIONALS     | TEXT, NULL 
- SOLD          | TINYINT, DEFAULT(0)

##