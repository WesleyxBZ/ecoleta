# NLW#1 Booster

Projeto desenvolvido durante a Next Level Week #1 Booster

## Sobre
Ecoleta é um sistema para descobrir pontos de coleta de resíduos mais perto de nós

## Tecnologias :computer:
* TypeScript
* React Native & React JS
* Express
* Knex (Query Builder)
* SQLite3
* Axios (API's)
* Celebrate (Validação no back-end)

## :wrench: Back-end
Para executar o back-end, entre no diretório `server`.
```
# Instalação das dependências
$ npm install

# Criar as tabelas do banco de dados
$ npm run knex:migrate

# Seed de itens de coleta
$ npm run knex:seed

# Rodar o back-end
$ npm run dev
```

## :computer: Front-end
Para executar o front-end, entre no diretório `web`.
```
# Instalação das dependências
$ npm install

# Rodar o front-end
$ npm start
```

## :iphone: Mobile
Para executar o front-end, entre no diretório `mobile`.
A execução do mobile é um pouco diferente porque precisamos que o Expo tenha instalado na nossa máquina, e em 
seguida no celular, caso queira rodar pelo celular físico. No celular físico é bem fácil, você precisa instalar o 
aplicativo Expo que está disponível da App Store ou na Play Store.
Para a utilização de um emulador com o Expo, você pode seguir o link guia para configuração </br>
[RocketSeat - Emulando React Native com Expo](https://www.youtube.com/watch?v=eSjFDWYkdxM&vl=en)
