# SQL-practice
Практика разных запросов

SQL Fiddler: https://competent-shaw-8b7294.netlify.app/

Валидатор запросов: https://ru.piliapp.com/mysql-syntax-check/

Дана таблица customers

____________________________________customers_______________________________
| customer_id|    customer_name    | contact_name |.... |  city  | country |
|      1     | Alfreds Futterkiste | Maria Ander  |.... | Berlin | Germany |
............................................................................
|      18    |    Ernst Handel     | Roland Mendel|.... |  Graz  | Austria |
Подсчитайте количество клиентов из Лондона (London). Задайте временное название для результирующей колонки - amount_of_customers.

SELECT COUNT(*) AS amount_of_customers
FROM customers
WHERE city = "London";

Дана таблица customers

______________________________________customers_________________________________
| customer_id|    customer_name    | contact_name |.... |    city    | country |
|      1     | Alfreds Futterkiste | Maria Ander  |.... |   Berlin   | Germany |
|      2     | Ana Trujillo Empa.. | Ana Trujill  |.... | México D.F.|  Mexico |
................................................................................
|      18    |    Ernst Handel     | Roland Mendel|.... |    Graz    | Austria |
Отобразить всю информацию обо всех клиентах из Германии, Мексики или Австрии.

