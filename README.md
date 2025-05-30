[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/1KoZzKx1)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19641822&assignment_repo_type=AssignmentRepo)

# Trabalho Prático - Semana 14

A partir dos dados cadastrados na etapa anterior, vamos trabalhar formas de apresentação que representem de forma clara e interativa as informações do seu projeto. Você poderá usar gráficos (barra, linha, pizza), mapas, calendários ou outras formas de visualização. Seu desafio é entregar uma página Web que organize, processe e exiba os dados de forma compreensível e esteticamente agradável.

Com base nos tipos de projetos escohidos, você deve propor **visualizações que estimulem a interpretação, agrupamento e exibição criativa dos dados**, trabalhando tanto a lógica quanto o design da aplicação.

Sugerimos o uso das seguintes ferramentas acessíveis: [FullCalendar](https://fullcalendar.io/), [Chart.js](https://www.chartjs.org/), [Mapbox](https://docs.mapbox.com/api/), para citar algumas.

## Informações do trabalho

- Nome: Vitor Oliveira Marquez
- Matricula: 897352
- Proposta de projeto escolhida: Diretório de Receitas
- Breve descrição sobre seu projeto: Um site que reúne receitas culinárias organizadas por categoria (entradas, pratos principais, sobremesas). Os usuários podem visualizar ingredientes e modo de preparo, além de buscar receitas por nome ou por ingredientes específicos.

**Print da tela com a implementação**

<< Coloque aqui uma breve explicação da implementação feita nessa etapa>>
Nesta etapa, foi criada uma página de estatísticas (public/estatisticas.html) que usa Chart.js para mostrar um gráfico de pizza. Este gráfico exibe o percentual de receitas por categoria, buscando dados dinamicamente do db.json via JSONServer. Alterações nas receitas (adicionar, editar categoria, excluir) na página de cadastro (cadastro_receitas.html) atualizam o gráfico na página de estatísticas após recarregá-la. Links para a nova página foram adicionados à navegação do site.

<<  COLOQUE A IMAGEM TELA 1 AQUI >>
![alt text](<Print 1.png>)
<<  COLOQUE A IMAGEM TELA 2 AQUI >>
![alt text](<Print 2.png>)