DB_name: car_dealer
Table_name: cars

- id | INDEX | PK | UNIQUE | BIGINT | NOTNULL | AI
- VIN | CHAR(17) | UNIQUE | NOTNULL | DEFAULT("N/A")
- brand | VARCHAR(30) | NOTNULL
- model | VARCHAR(50) | NOTNULL
- year | YEAR | NOTNULL
- origin | VARCHAR(20) | NULL
- fuel | VARCHAR(20) | NOTNULL
- plate_number | CHAR(7) | NULL
- image | VARCHAR(255) | NULL |DEFAULT("insert-default-pic-url")
- description | TEXT | NULL
- mileage | MEDIUMINT | NOTNULL
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


# TABLE

| ID | VIN | Brand | Model | Year | Origin | Fuel | plate_number | Image | Description | Mileage | Engine | Cubic_capacity | Horsepower | Seats_number | Trasmission_type | Doors_number | Optionals | Emissions_class | Weight | Length | Width | Height | Color | Matriculation_date | Matriculations_number | Condition | Price | Is_available | Notes
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|