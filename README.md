# E-Commerce-Task-PostgreSQL

## A short task for creating a dummy data for e-commerce website using PostgreSQL.

### 1) `create customers table`

```
create table customers (id serial primary key, username varchar(100) not null)
```

### 2) `insert customer into table`

```
insert into customers (username) values ('Muhammad Farooq')
```

### 3) `insert customer into table`

```
insert into customers (username) values ('Muhammad Farooq')
```

### 4) `create a orders table with give refernce to customerId`

```
create table orders (orderid INT Not null, orderdate date default CURRENT_DATE, customerid INT not null, foreign key (customerid) references customers(id))
```

### 5) `create a orders table with give refernce to customerId`

```
create table orders (orderid INT Not null, orderdate date default CURRENT_DATE, customerid INT not null, foreign key (customerid) references customers(id))
```

### 6) `create a products table`

````
create table products (productid serial primary key, productname varchar(100) not null, productprice int not null)```
````

### 7) `insert a products into products table`

`````
insert into products (productname, productprice) values ('mouse',100)
`````

### 8) `insert a products into products table`

`````
insert into products (productname, productprice) values ('mouse',100)````
`````