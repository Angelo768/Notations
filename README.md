# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

### Specifications
```sh
* Ruby version 2.5.5
* Rails version 5.2.4
```

### Gems 
* System dependencies
- gem faker (for tests)

### Runing the app
```ruby
- bundle
- rails db:setup
- rails s
```

### System example HEROKU
<https://annotation-to-ives.herokuapp.com/>

### Criando uma notação

* Método GET - <https://annotation-to-ives.herokuapp.com/notes>
Basta fazer a requisão e vocẽ vai receber todas as anotações registradas.

* Método POST - <https://annotation-to-ives.herokuapp.com/notes>
Para registrar uma notação no banco de dados

```json
{
    title: "Reajustar o despertador",
    description: "Tenho um evento muito importante que não posso esquecer"
}
```

* Método PATCH/PUT - <https://annotation-to-ives.herokuapp.com/notes/1>
Para atualizar uma notação no banco de dados, você precisa passar na requisição o id referente ao dado que vocẽ quer atualizar

```json
{
    title: "Atualizando notação",
    description: "Tenho um evento muito importante que não posso esquecer"
}
```

* Método DELETE - <https://annotation-to-ives.herokuapp.com/notes/1>
Para remover uma notação do banco de dados, você precisa passar na requisição o id referente ao dado que vocẽ quer atualizar
