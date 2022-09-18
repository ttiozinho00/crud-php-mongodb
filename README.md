# CRUD MONGODB E PHP

Um aplicativo CRUD simples e básico usando PHP & MongoDB Banco de Dados.


**Inciando o MongoDB**

```
sudo service mongod start
```

**Verificando se esta rodando o MongoDB**

```
sudo service mongod status
```

**Inicializando MongoDB shell**

```
mongod
```

**Mostrar bancos de dados**

```
show dbs
```

**Crie um banco de dados chamado "test"**

```
use test
```

**Criar coleção (tabela) nomeada "users"**

```
> db.users.insert({name:"Mukesh Chapagain", age:88, email:"mukesh@example.com"})
> db.users.insert({name:"Raju Sharma", age:77, email:"raju@example.com"})
> db.users.insert({name:"Krishna Yadav", age:65, email:"krishna@example.com"})
```

**Coleta de consultas**

```
> db.users.find().pretty()
{
	"_id" : ObjectId("5946517675f3fc671900a6c1"),
	"name" : "Mukesh Chapagain",
	"age" : 88,
	"email" : "mukesh@example.com"
}
{
	"_id" : ObjectId("5946517f75f3fc671900a6c2"),
	"name" : "Raju Sharma",
	"age" : 77,
	"email" : "raju@example.com"
}
{
	"_id" : ObjectId("5946518375f3fc671900a6c3"),
	"name" : "Krishna Yadav",
	"age" : 65,
	"email" : "krishna@example.com"
}
```
