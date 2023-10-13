# Dealer Database

## Table Name

- vehicles


## Table Columns

- id | PK, BIGINT, AUTO_INCREMENT, UNIQUE, NOT NULL
- type| VARCHAR(20), NOT NULL
- image | VARCHAR(255), NULL
- category | VARCHAR(20), NULL
- model_years | VARCHAR(20), NULL
- model_name | VARCHAR(20), NOT NULL
- description | TEXT, NULL
- price | DECIMAL(12, 2), NULL
- km | MEDIUMINT, NULL
- engine | VARCHAR(20), NULL
- exterior_color | VARCHAR(20), NULL
- interior_color | VARCHAR(20), NULL
- interior_material | VARCHAR(20), NULL
- features | TEXT, NULL
- registration_year | SMALL, NULL
- plate | VARCHAR(20), UNIQUE, NULL
- is_available | TINYINT, DEFAULT(0)
- shift | VARCHAR(30), NULL
- tank_capacity | VARCHAR(10), DEFAULT(0)
- seats | TINYINT, DEFAULT(0)
- notes | TEXT, NULL
