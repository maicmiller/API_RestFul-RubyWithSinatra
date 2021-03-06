# Criando do zero uma RestFul-API utilizando Ruby com Sinatra
Criando um API RestFul utilizando a linguagem Ruby com o framework Sinatra, para estudar com mais profundidade os Testes✓ nesse tipo requisições.

<div align="center">

![teste de api](https://user-images.githubusercontent.com/990877/131418510-0ff87b50-1e0d-4c9e-a368-a80afce062a9.png)
  
</div>
  
  ## Tecnologias
  
  * http://sinatrarb.com/
  * https://www.ruby-lang.org/en/ - ⇡ 2.5
  * https://rubygems.org/
  * https://github.com/rbenv/rbenv
  * https://insomnia.rest/
  * https://www.postman.com/
  * https://www.mongodb.com
  * https://robomongo.org

## Inicializando o Projeto
  
```shell script
gem install
```
```shell script
bundle init
```
```shell script
bundle install
```
```shell script
ruby app.rb
```

## MongoDB 🍃 | https://www.mongodb.com/pt-br

1º Criação de um Cluster

![createCluster](https://user-images.githubusercontent.com/990877/131267256-6f567f3f-fb86-4b05-bc0c-d5c017ce7160.png)

2º Definir o método de conexão

![connect](https://user-images.githubusercontent.com/990877/131269247-7d54b5b7-e70f-4cab-abee-c7cd0ca4dc8e.png)

3º Configurações da conexão

![Screen Shot 2021-08-29 at 20 43 09](https://user-images.githubusercontent.com/990877/131269288-a2996fa3-5d63-4c39-bf51-46bf255bf8fc.png)
```shell script
mongodb+srv://books:<password>@cluster0.cgi4m.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
```
4º Criar a Collection's ("Tabelas")

![collection](https://user-images.githubusercontent.com/990877/131267456-757061af-40e2-4ac0-b141-77924b74a85c.png)

5º Criar Document's ("Registros")

![document](https://user-images.githubusercontent.com/990877/131267502-c38b5440-6e97-4dc0-b3b3-9663986f065f.png)

6º Instalação do Mongo ID | https://rubygems.org/gems/mongoid

##

## Robo 3T | https://robomongo.org/ (Cliente para MongoDB)

![robo3t](https://user-images.githubusercontent.com/990877/131267550-711da47e-910b-4397-912e-ebc66e28d80b.png)

#### Configuração da conexão no Projeto Ruby | https://docs.mongodb.com/mongoid/current/tutorials/getting-started-sinatra/

## Faker 🎭

![fake](https://user-images.githubusercontent.com/990877/131378511-2fc7e0bf-3ac2-41e0-b22f-72a860595e14.png)

https://github.com/faker-ruby/faker

Random Book Title
```shell script
Faker::Book.title #=> "The Odd Sister"
```
Random Author
```shell script
Faker::Book.author #=> "Alysha Olsen"`shell script
```
Random Publisher
```shell script
Faker::Book.publisher #=> "Opus Reader"
```
Random Genre
```shell script
Faker::Book.genre #=> "Mystery"
```
ISBN randon
```shell script
Faker::Code.isbn #=> "759021701-8"
```
