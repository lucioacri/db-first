| name                | type                     | attributes               | index       |
| ------------------- | ------------------------ | ------------------------ | ----------- |
| id                  | INT                      | NOT NULL, AUTO INCREMENT | PRIMARY KEY |
| car_company         | VARCHAR(30)              | NOT NULL                 | INDEX       |
| km                  | INT                      | NOT NULL                 |             |
| model               | VARCHAR(50)              | NOT NULL                 | INDEX       |
| state               | ENUM( "perfect", "used") | NOT NULL                 |             |
| price               | INT                      | NOT NULL                 |             |
| color               | VARCHAR(20)              |                          |             |
| optionals           | TEXT                     |                          |             |
| engine_displacement | INT                      |                          |             |
| model_year          | YEAR                     |                          | INDEX       |
