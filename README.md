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

## 142. Retrieving Data

### Intro

Mengambil data

## 143. Fetching Products

### Intro

Menampilkan produk

### SQL

```
insert into new_table(title,price,description,imageUrl) values('buku baru',35000,'buku bagus','https://i.picsum.photos/id/2/300/300.jpg?hmac=18v9hYebAqcHuhqDo_PgGIHxZ5Ay-8Di7TqUUS5ZvXY');
```
