# docker-vue-express-psql
Docker-composed files for vue(2), express, postgres

Docker化したVue、Express、Postgresの例  

## Command
`docker-compose up --build`  

## Test
http://localhost:3000 //express api server  
http://localhost:8080 //vue app

```
DBの方は、DB containerのCLI接続後

# psql -U postgres
psql (13.4 (Debian 13.4-4.pgdg110+1))
Type "help" for help.

postgres=# SELECT * FROM test_table;
 test_column
-------------
(0 rows)
```

