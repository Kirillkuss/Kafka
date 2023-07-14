# Kafka
 ** End points:  **

  ** http://localhost:8082/webjars/swagger-ui/index.html#/  **
  ** http://127.0.0.1:8081/swagger-ui/index.html#/ **

 ** Тестовый проект, где 1 REST - FebFlux, 2 REST - SpringMVC **

 БД - jdbc:postgresql://localhost:5432/postgres
 password = admin
 login    = postgres


 CREATE TABLE Animal(
	id serial PRIMARY KEY,
	name VARCHAR( 20 ) NOT NULL,
	amount int8 NOT NULL,
	count int
);

CREATE TABLE Person(
	id serial PRIMARY KEY,
	name VARCHAR( 20 ) NOT NULL,
	login VARCHAR( 20 ) NOT NULL,
	phone VARCHAR( 13 ) NOT NULL,
	wallet int8 NOT NULL
);

CREATE TABLE Car(
	id serial PRIMARY KEY,
	model VARCHAR( 20 ) NOT NULL,
	timeBuy timestamp,
	coast bigserial NOT NULL,
	number int4 NOT NULL
);  
