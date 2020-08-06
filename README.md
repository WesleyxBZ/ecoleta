<p align="center">
   <img src="https://github.com/WesleyxBZ/ecoleta/blob/master/.github/logo.png" alt="Ecoleta" width="280"/>
</p>

# :page_facing_up: Sobre
Ecoleta é um sistema para descobrir pontos de coleta de resíduos mais perto de nós

# :computer: Tecnologias
* TypeScript
* React Native & React JS
* Express
* Knex (Query Builder)
* SQLite3
* Axios (API's)
* Celebrate (Validação no back-end)

# :construction_worker: Como executar
```bash
# Clone o repositório
$ git clone https://github.com/WesleyxBZ/ecoleta.git
```
### Executar a API

```bash
# Va para a pasta server
$ cd ecoleta/server

# Instale as dependências
$ npm install

# Rode as migrations
$ npm run knex:migrate

# Rode os seed de itens de coleta
$ npm run knex:seed

# Execute a aplicacao
$ npm run dev
```
Acesse http://localhost:3333/

### Executar o Projeto Web

```bash
# Va para a pasta web
$ cd ecoleta/web

# Instale as dependências
$ npm install

# Execute a aplicação
$ npm start
```
Acesse http://localhost:3000/

### Executar o Projeto Mobile

Para executar o projeto mobile você vai precisar de um celular com [expo](https://play.google.com/store/apps/details?id=host.exp.exponent) instalado ou um emulador android/ios.
<br />
Após, fork esse projeto e clone em sua máquina. Dentro da pasta do projeto, execute e siga os comandos:

```bash
# Va para a pasta mobile
$ cd ecoleta/mobile

# Instale as dependências
$ npm install

# Execute a aplicação
$ npm start
```
Após, leia o QRCode com o app [expo](https://play.google.com/store/apps/details?id=host.exp.exponent) ou execute o emulador.
