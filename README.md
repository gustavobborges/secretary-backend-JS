# Secretary Api REST

## Descrição do Projeto
<p align="center">API Rest de agenda de compromissos.</p>

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Interagindo com a API REST

## 🎲 Requisições HTTP:
#GET
    - LIST ALL
        https://the-secretary.herokuapp.com/api/appointments
    
    - LIST ONE
        https://the-secretary.herokuapp.com/api/appointments/{id}

#POST
    - CREATE
        https://the-secretary.herokuapp.com/api/appointments

#PUT
    - EDIT
        https://the-secretary.herokuapp.com/api/appointments/{id}

#DELETE
    - DELETE
        https://the-secretary.herokuapp.com/api/appointments/{id}


### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone <https://github.com/gustavobborges/secretary-backend>

# Acesse a pasta do projeto no terminal/cmd
$ cd secretary-backend

# Executar a aplicação
$ yarn dev


### 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
