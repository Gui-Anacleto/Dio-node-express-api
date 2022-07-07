# Introducão ao Node.JS com Express:

## Requisitos:
-Conhecer Javascript e seus fundamentos; ok
-Familiaridade com comandos no terminal; ok
-Conhecimento básico sobre protocolos HTTP(GET, POST, PUT, DELETE); ok
-Conhecer o conceito de RestAPI; ok

## Origem:
-Criado em 2009 por Ryan Dahl;
-Combina a máquina virtual Javascript V8, Event Loop e a libuv;
-Usa o Javascript como linguagem de programação;
-É guiado a eventos (Event Driven);

V8 + libuv = Node.js

## Características:
-É um ambiente de servidor de open source
-Assimcronicidade
-Processos de I/O não bloqueante
-Alta performance (quando bem estruturado)

## EVENT LOOP

EVENT LOOP(single thread) > Register callback > INTENSIVE OPERATION(fiel system, database, compution) > Operation Completo > Trigger Callback > REQUESTS, ETC  --LOOP--

## Instalar node:
https://nodejs.org/en/

# O que é o Express ?

## Framework web minimalista e rápido para Node.js
## Fornece uma estrutura e conjunto de recursos robustos para aplicações Web e mobile,

## Dispóe de métodos utilitários HTTP e middlewares para criar uma API rápida e segura.

## Instalar Express:
### No terminal dentro do diretório do projeto, digite: ** npm install express --save **
Extras:
Criar projeto - nmp init

# Atividade prática:
## Criar uma *endpoint* para *users*:
### Listar usuários: GET
### Criar usuário: POST
### Modificar usuário: PUT
### Remover usuário: DELETE

# CLI - command line interface

## O que é:
-Ferramenta que disponibiliza uma interface de linha de -Comando para executar tarefas no terminal.
-Normalmente são criadas em Shell
-Automatiza uma tarefa no terminal
-Pode ser facilmente distribuído em várias plataformas
