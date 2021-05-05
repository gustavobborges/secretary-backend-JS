# Secretary API

## Project description
<p>API Rest for appointments.</p>

## 🎲 Using API REST

### Appointment example:

<p>
    <b>name: </b>Consulta<br>
    <b>description: </b>Almoço<br>
    <b>place: </b>Centro<br>
    <b>date: </b>18/04/2021<br>
    <b>time: </b>12:30
</p>   

### 🎲 Requests HTTP:

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


## 🎲 Running backend (server)

### Pré-requisitos

Before begin, you must have the fallowing items installed on your computer: 
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/).
In addition, it is good to have an editor to work with the code as [VSCode](https://code.visualstudio.com/)

```bash
# Clone este repositório
$ git clone <https://github.com/gustavobborges/secretary-backend>

# Acesse a pasta do projeto no terminal/cmd
$ cd secretary-backend

# Executar a aplicação
$ yarn start

```

### 🛠 Tecnologias

The following technologies were used in this project:

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
