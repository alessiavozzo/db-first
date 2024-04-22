DB_name: car_dealer
Table_name: cars

- id | INDEX | PK | UNIQUE | BIGINT | NOTNULL |AI
- brand | VARCHAR(30) | NOTNULL
- model | VARCHAR(50) | NOTNULL
- year | YEAR | NOTNULL
- origin (italia, estero etc) | VARCHAR(20) | NULL
- fuel | VARCHAR(20) | NOTNULL
- plate_number | CHAR(7) | NULL
- image | VARCHAR(255) | NULL |DEFAULT("insert-default-pic-url")
- description | TEXT | NULL
- km | MEDIUMINT | NOTNULL
- engine | VARCHAR(50) | NULL
- cubic_capacity | VARCHAR(10) | NOTNULL
- horsepower | SMALLINT | NOTNULL
- seats_number | TINYINT | NULL
- trasmission_type | VARCHAR(20) | NOTNULL
- doors_number | CHAR(1) | NULL 
- optionals | VARCHAR(100) | NULL
- emissions_class | CHAR(5) | NOTNULL
- weight | SMALLINT | NULL | DEFAULT("N/A")
- length | FLOAT(4,2) | NULL | DEFAULT ("N/A")
- width | FLOAT(4,2) | NULL | DEFAULT ("N/A")
- height | FLOAT(4,2) | NULL | DEFAULT ("N/A")
- color | VARCHAR(20) | NOTNULL
- last_matriculation_date | DATE | NOTNULL
- matriculations_number | TINYINT | NULL | DEFAULT("N/A")
- conditions | VARCHAR(100) | NOTNULL
- price | DECIMAL(8,2) | NOTNULL
- is_available | TINYINT | NOTNULL | DEFAULT(1)
- notes | TEXT | NULL

