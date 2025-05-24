Напишите тренировочный код для задания. Код (ВЕСЬ) в одном файле:
Выберите из таблицы products все товары в порядке возрастания цены (price).\
![image](https://github.com/user-attachments/assets/fe73b2bf-4479-4e2b-9529-0f4c365d9dec)

CREATE TABLE products(
 id INT PRIMARY KEY,
 name VARCHAR(100) NOT NULL,
 count INT DEFAULT 0,
 price DECIMAL(10,2) NOT NULL
);

INSERT INTO products (id, name, count, price) VALUES
(1, 'Стиральная машина', 5, 10000),
(2, 'Холодильник', 0, 10000),
(3, 'Микроволновка', 3, 4000),
(4, 'Пылесос', 2, 4500),
(5, 'Вентилятор', 0, 700),
(6, 'Телевизор', 7, 31740),
(7, 'Тостер', 2, 2500),
(8, 'Принтер', 4, 3000);

![image](https://github.com/user-attachments/assets/97f46550-2ce7-4299-89ed-f5d07f8b4d67)

![image](https://github.com/user-attachments/assets/905fe04a-c049-4e5e-821a-636b79e73ad0)

SELECT *
FROM products
ORDER BY price;


![image](https://github.com/user-attachments/assets/be6def3e-7212-495a-819a-7f6ef9f5ec06)

