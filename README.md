Desafio Frontend Uolet
======================

## Bem-vindo

A Uolet é uma empresa de tecnologia com a missão de criar produtos que engagem consumidores em canais digitais estimulando-os a visitar as lojas físicas dos varejistas afiliados, e criando uma experiência customizada e enriquecida no ponto-de-venda. 

Para isso trabalhamos com soluções para diversos canais (mobile, web, IoT, physical web, chatbots, beacons entre outros) utlizando várias linguagens e frameworks.

## Como participar

Faça um fork deste repositório e crie um branch com seu nome-sobrenome, e desenvolva sua solução. Quando estiver concluído nos envie um pull-request seguido de um e-mail para vagas@uolet.com mencionando o pull-request acompanhado do seu currículou e/ou uma breve introdução sua.

## O Desafio

Para este desafio queremos que você construa uma aplicação SPA (Single Page Application) utilizando algum framework javascript à sua escolha (Angular, React, Amber, Vue, etc..) em conjunto com Twitter Bootstrap. Você pode usar geradores/scaffolds/boilerplates como ponto de partida do seu projeto, mas lembre-se: no final do dia é o seu código que nos interessa. Deixe sua marca!!

Este desafio não tem uma resposta certa ou errado. Através dele iremos avaliar diversos aspectos de sua solução. Para lhe dar uma idéia de onde caprichar no seus esforços listamos abaixo alguns exemplos.

- domíno da linguagem escolhida (ninguém disse que precisa se restringir ao JS. Prefere CLJS? Elm? vá em frente ;D ).
- integração com APIs de terceiros.
- comunicação síncrona x assíncrona.
- organização do projeto/folders.
- arquitetura e boas práticas (como você distribui/isolou as responsabilidades no seu código, reutilização, clareza).
- uso de html semântico.
- responsividade (mobile-first? offline-first? você escolhe).
- organização do css.
- rotinas de build uso de pré-processors.
- testes.
- clareza nos commits e seu uso como registro do desenvolvimento. Não use apenas um único commit afinal sua aplicação não saiu do zero a 100 de uma vez.
- Pensou em algo mais? inclua aqui o que você julga importante.

## A Aplicação

- A aplicação é uma aplicação SPA que permite ao usuário realizar buscas por nomes de artistas presentes no spotify. 
- Para acessar a tela de busca é preciso realizar uma autenticação de usuário e senha.
- A lista de usuários e senha válidos poderá estar hard-coded na própria aplicação (ou seja, não é necessário o uso de backend para autenticação do usuário).
- Uma vez autenticado os dados do usuário devem ser recuperados através de um GET http://uinames.com/api/
- A tela principal, composta de uma navbar e uma região container, deve exibir o nome completo do usuário à esquerda junto com um ícone indicando seu sexo, conforme os dados recebidos na chamada acima.
- Ao acessar pela primeira vez, um jumbotron deve ser exibido.
- Na barra de buscas o usuário pode digitar o nome de um artista para realizar uma busca junto à api do Spotify (https://api.spotify.com/v1/search?type=artist&q=nome-artista). O resultado deve ser exibido conforme o desenho do mock-up.

![Mockup tela](https://github.com/craftti/desafio-frontend/blob/master/wireframe.png "Mockup telas")

Seguem abaixo alguns links que podem te ajudar com informações sobre estas APIs e seus formatos de retorno:

- https://github.com/thm/uinames#the-api
- https://developer.spotify.com/web-api/search-item/
- https://any-api.com/spotify_com/spotify_com/docs/_artists/GET

