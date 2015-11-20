# MongoDB - Aula 01 - Exercício
autor: César Augusto Marcelino dos Santos

## Importando os restaurantes

    ```
cesinha@vilaDoChaves:~/Downloads/Web+Mobile Dev/be-mean-instagram/apostila/module-mongodb/data$ mongoimport --db be-mean --collection restaurantes --drop --file restaurantes.json2015-11-19T22:02:32.562-0200	connected to: localhost
2015-11-19T22:02:32.572-0200	dropping: be-mean.restaurantes
2015-11-19T22:02:34.449-0200	imported 25359 documents

    ```

## Contando os restaurantes

    ```
MongoDB shell version: 3.0.7
connecting to: be-mean
Welcome to the MongoDB shell.
For interactive help, type "help".
For more comprehensive documentation, see
	http://docs.mongodb.org/
Questions? Try the support group
	http://groups.google.com/group/mongodb-user
2015-11-19T22:04:13.649-0200 I STORAGE  In File::open(), ::open for '/home/cesinha/.mongorc.js' failed with errno:2 No such file or directory
Server has startup warnings: 
2015-11-19T20:12:38.034-0200 I CONTROL  [initandlisten] 
2015-11-19T20:12:38.034-0200 I CONTROL  [initandlisten] ** WARNING: /sys/kernel/mm/transparent_hugepage/enabled is 'always'.
2015-11-19T20:12:38.034-0200 I CONTROL  [initandlisten] **        We suggest setting it to 'never'
2015-11-19T20:12:38.034-0200 I CONTROL  [initandlisten] 
2015-11-19T20:12:38.034-0200 I CONTROL  [initandlisten] ** WARNING: /sys/kernel/mm/transparent_hugepage/defrag is 'always'.
2015-11-19T20:12:38.034-0200 I CONTROL  [initandlisten] **        We suggest setting it to 'never'
2015-11-19T20:12:38.034-0200 I CONTROL  [initandlisten] 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> 
> db.restaurantes.find({}).count()
25359
> 

    ```
