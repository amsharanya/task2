# task2
inserting deleting and updating query
 INSERT INTO `ecommerce`.`customers` (`customer_id`, `name`, `email`) VALUES ('2', 'shreeja', 'srija14@gmail.com');
Query OK, 1 row affected (0.043 sec)

mysql> INSERT INTO `ecommerce`.`products` (`product_id`, `name`, `price`) VALUES ('1', 'basumati rice', '40.00');
Query OK, 1 row affected (0.048 sec)

mysql> INSERT INTO `ecommerce`.`products` (`product_id`, `name`, `price`) VALUES ('2', 'sugar', '42.00');
Query OK, 1 row affected (0.040 sec)

mysql> INSERT INTO `ecommerce`.`products` (`product_id`, `name`, `price`) VALUES ('3', 'egg', '5.00');
Query OK, 1 row affected (0.039 sec)

mysql> UPDATE `ecommerce`.`products` SET `price` = '45.00' WHERE (`product_id` = '1');
Query OK, 1 row affected (0.043 sec)
Rows matched: 1  Changed: 1  Warnings: 0

mysql> DELETE FROM `ecommerce`.`products` WHERE (`product_id` = '3');
Query OK, 1 row affected (0.047 sec)
