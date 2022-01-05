# node_basic_10_mysql

Mempelajari MySQL dengan node js

## 140. Connecting our App to the SQL Database

### Intro

Menghubungkan aplikasi ke database SQL

## 141. Basic SQL & Creating a Table

### Intro

Menciptakan Table

### SQL

```
CREATE TABLE `new_table` (
	`id` INT NOT NULL AUTO_INCREMENT,
	`title` VARCHAR(255) NOT NULL,
	`price` DOUBLE NOT NULL,
	`description` TEXT,
	`imageUrl` VARCHAR(255),
	KEY `id` (`id`) USING BTREE,
	PRIMARY KEY (`id`)
);
```
