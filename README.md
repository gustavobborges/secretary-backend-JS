# Secretary API

## Descrição do Projeto
<p>API Rest de agenda de compromissos.</p>

## 🎲 Interagindo com a API REST

### Appointment:

<p>
    <b>name: </b>Consulta<br>
    <b>description: </b>Almoço<br>
    <b>place: </b>Centro<br>
    <b>date: </b>18/04/2021<br>
    <b>time: </b>12:30
</p>   

### 🎲 Requisições HTTP:

<p>
    <b>GET</b><br>
    <b>- List all: </b>https://the-secretary.herokuapp.com/api/appointments<br>
    <b>- List one: </b>https://the-secretary.herokuapp.com/api/appointments/{id}<br>
</p>
<p>
    <b>POST</b><br>
    <b>- Create: </b>https://the-secretary.herokuapp.com/api/appointments<br>
</p>
<p>
    <b>PUT</b><br>
    <b>- Edit: </b>https://the-secretary.herokuapp.com/api/appointments/{id}<br>
</p>
<p>
    <b>DELETE</b><br>
    <b>- Delete: </b>https://the-secretary.herokuapp.com/api/appointments/{id}<br>
</p>


## 🎲 Rodando o Back End (servidor)

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

```bash
# Clone este repositório
$ git clone <https://github.com/gustavobborges/secretary-backend>

# Acesse a pasta do projeto no terminal/cmd
$ cd secretary-backend

# Executar a aplicação
$ yarn start

```

### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
