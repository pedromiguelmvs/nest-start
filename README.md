# Nest API

O projeto tem como objetivo registrar meus conceitos iniciais no uso do framework NestJS e, se for oportuno, ajudar a outros desenvolvedores no seu processo de aprendizado desse framework.

## Ferramentas utilizadas

Este projeto foi feito com __NestJS__, __TypeScript__ e __MongoDB__.

## Como rodar o projeto?

Primeiro, você deve clonar o repositório (recomendável sistema UNIX):

```
git clone https://github.com/pedromiguelmvs/nest-start
```

Entre na pasta do projeto:

```
cd nest-start
```

Feito isso, instale as dependências do projeto:

```
npm install
```

ou

```
yarn install
```

Para que o código reconheça sua base de dados, você deverá criar um arquivo chamado ```dev.env``` na raiz do projeto, e nele colar a seguinte instrução:

```
DB_URI=sua-uri-da-database
```

Se você não sabe como fazer isso, recomendo que veja um tutorial [clicando aqui](https://medium.com/reprogramabr/conectando-no-banco-de-dados-cloud-mongodb-atlas-bca63399693f).

_Done!_ O projeto está configurado e pode ser executado localmente:

```
npm run start:dev
```

ou

```
yarn start:dev
```

Rotas podem ser acessadas usando as ferramentas [Postman](https://www.postman.com/) ou [Insomnia](https://insomnia.rest/)
