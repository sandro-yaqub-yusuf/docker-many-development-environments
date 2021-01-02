# DOCKER - Ambiente de Desenvolvimento 007

* Web Service: NGINX (última versão disponivel no momento da criação do contêiner)
* Linguagem principal: PHP 7.4.13 com XDebug 2.9.8
* Framework para PHP: Laravel (a versão que for escolhida no momento da criação do projeto)
* Plataforma adicional: NODE JS 14.15.3
* Banco de dados: MySQL 5.7.31
* Instalações adicionais: composer (última versão disponivel no momento da criação do contêiner)

----

## Descrição:

Para instalar o LARAVEL mais atual, siga as instruções abaixo:
* Crie a pasta "SRC" digitando => mkdir src
* Entre na pasta "SRC" digitando => cd src
* Crie um projeto LARAVEL digitando => docker-compose run --rm composer create-project laravel/laravel .
* Utilize qualquer gerenciador de BD MySQL de sua preferência e crie um novo BD nele
* Configure o arquivo ".env" do LARAVEL com os dados de conexão com o seu BD criado
* Saia da pasta "SRC" digitando => cd ..
* Rode o "ARTISAN MIGRATE" digitando => docker-compose run --rm artisan migrate
* Veja com o seu gerenciador de BD MySQL se foi criado novas tabelas no BD configurado no ".env"

Este ambiente possui uns contêineres adicionais (Composer, NPM e Artisan) sem precisar possuir estas plataformas instaladas. Para rodá-los utilize:

* docker-compose run --rm composer [comandos e/ou opções]
* docker-compose run --rm npm [comandos e/ou opções]
* docker-compose run --rm artisan [comandos e/ou opções]

----

## Sobre o Autor:

SANDRO YAQUB YUSUF - Analista & Programador Sênior FULL-STACK - Trabalha com desenvolvimento de softwares desde 1990, passando pelas linguagens COBOL, CLIPPER, VISUAL BASIC 6, ASP Clássico, ASP.NET Framework, PHP e atualmente ASP.NET Core para desenvolvimento BACK-END. Possui conhecimentos em banco de dados como SQL-SERVER, ORACLE, MySQL, MariaDB e SQLite. Possui conhecimentos em HTML5, CSS3, TYPESCRIPT e JAVASCRIPT. Também possui conhecimentos em frameworks para desenvolvimento em FRONT-END como ANGULAR, VUEJS e REACT JS. Pratica o modelo CLEAN ARCHITECTURE usando os conhecimentos em DDD, SOLID e TDD.
