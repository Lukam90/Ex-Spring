# Ex-Spring

## ex-boot

### Docker

**Download**

docker compose up -d

**Containers List**

docker compose ps

**PostgreSQL Logs**

docker logs postgres -f

**Bash Console**

docker exec -it postgres bash

### PostgreSQL

**Connexion**

psql -U lukas

**List Databases**

\l

**Quit**

\q

exit

**Connect to DB**

\c customer

**List Relations**

\dt

### SQL Commands

**Create**

create database customer;

**Select**

select * from customer;

**Insert**

insert into customer(id, name, email, age) values(nextval('customer_id_sequence'), 'Alex', 'alex@test.com', 22);

insert into customer(id, name, email, age) values(nextval('customer_id_sequence'), 'Kid', 'kid@test.com', 33);