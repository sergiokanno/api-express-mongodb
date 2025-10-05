# Curso de Node.js: criando uma API Rest com Express e MongoDB

## Link GitHub do Repositório do curso de API com Node.js, Express e MongoDB:
https://github.com/alura-cursos/3266-express-mongo.git

## Link do curso na ALURA:
https://cursos.alura.com.br/course/node-js-api-rest-express-mongodb


## Aula-1 - Criando o projeto com Node.js
 
    1.  Preparando o ambiente:

        - Instalando Node.js versão 18.16.0
          nvm install 18.16.0

    2.  Criando o servidor

        npm init -y

    3.  Instalando nodemon@3.0.1

        npm install nodemon@3.0.1

    4.  Testando
        
        -   Testando API:

            npm run dev

        -   Acessando rotas:

            http://localhost:3000/
            http://localhost:3000/livros
            http://localhost:3000/autores
            http://localhost:3000/busca?editora=


## Aula-2 - Express e primeiras rotas

    1.  Instalar Framework Express no projeto:

	    npm install express@4.18.1

    2.  Framework Express:

	    Os métodos do Framework Express são utilizados para criação de um servidor HTTP e também para gerenciamento de requisições, respostas e criação de rotas

    3.  Implementar um CRUD com os métodos HTTP GET, POST, PUT e DELETE

	4.  Testar a aplicação utilizando Postman


## Aula-3 - Persistindo dados

    1.  Persistir dados em banco MongoDB hospedado na nuvem

    2.  Instalar o Driver do MongoDB

	    npm install mongodb

	    Obs.: Este Driver é a biblioteca que permite que API com Node.js se conectem e interajam com bancos de dados MongoDB

    3.  Instalar o Mongoose

	    npm install mongoose@7.3.4

	    Obs.: Mongoose é uma ferramenta de modelagem de objetos do MongoDB

    4.  Instalar Dotenv

        npm install dotenv

	    Obs.: biblioteca Dotenv é utilizada para gerenciar as variáveis de ambiente


## Aula-4 - Evoluindo a API

	1.	Implementando controller e rotas para livro

	2.	implementação do CRUD (Create, Read, Update e Delete) com as respostas HTTP e as rotas correspondentes


## Aula-5 - Adicionando funcionalidades

    1.  Implementando controller e rotas para autor

    2.  Usar modelo de embedding para unir as entidades livro e autor na base de dados MongoDB

    3.  Implementar busca utilizando parâmetros de query na nossa API
