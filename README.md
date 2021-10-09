# DOCKER - Vários Ambientes de Desenvolvimento

* Linguagem principal: docker-compose
* Fonte de pesquisa: https://github.com/aschmelyun/docker-compose-laravel
* Informações extras: estes scripts foram criados num WINDOWS 10 Professional, com WSL2 e Docker For Windows (Desktop).

----

## Descrição:

Uma coleção de scrips DOCKER para criar vários contêineres para formar ambientes de desenvolvimento. São elas até o presente momento:

* DEV-001 => NGINX + PHP7 + Composer + MySQL
* DEV-002 => NGINX + PHP7 + Composer + MariaDB
* DEV-003 => NGINX + PHP7 + Composer + NodeJS + MySQL
* DEV-004 => NGINX + PHP7 + Composer + NodeJS + MariaDB
* DEV-005 => NGINX + PHP7 + Composer + Artisan (Laravel) + MySQL
* DEV-006 => NGINX + PHP7 + Composer + Artisan (Laravel) + MariaDB
* DEV-007 => NGINX + PHP7 + Composer + Artisan (Laravel) + NodeJS + MySQL
* DEV-008 => NGINX + PHP7 + Composer + Artisan (Laravel) + NodeJS + MariaDB

Dependendo do ambiente que for escolhar, serão instalados contêineres adicionais (Composer, NPM e Artisan) sem precisar possuir estas plataformas instaladas. Para rodá-los utilize:

* docker-compose run --rm composer [comandos e/ou opções]
* docker-compose run --rm npm [comandos e/ou opções]
* docker-compose run --rm artisan [comandos e/ou opções]

Este repositório será sempre atualizado com novidades, atualizações e correções.

----

## Sobre o Autor:

SANDRO YAQUB YUSUF - Analista & Programador Sênior FULL-STACK - Trabalha com desenvolvimento de softwares desde 1990, passando pelas linguagens COBOL, CLIPPER, VISUAL BASIC 6, ASP Clássico, ASP.NET Framework, ASP.NET Core, PHP (Laravel) e NodeJS. Possui conhecimentos em banco de dados como SQL-SERVER, ORACLE, MySQL, MariaDB, MongoDB e SQLite. Também possui conhecimentos em HTML5, CSS3, TYPESCRIPT e JAVASCRIPT. Para as frameworks de desenvolvimento de FRONT-END, possui conhecimentos em ANGULAR, VUEJS e REACT JS. Pratica o modelo CLEAN ARCHITECTURE usando os conhecimentos em DDD, SOLID e TDD.
