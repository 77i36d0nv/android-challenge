# Android Challenge

## Desafio

O objetivo é implementar um app onde podemos ver uma lista de filmes usando a [API V3](https://developer.themoviedb.org/reference/getting-started) do [TheMovieDB](https://www.themoviedb.org).

### Requisitos:

- O app deve mostrar uma lista ou grid de na tela principal trazendo a lista de filmes populares da [API](https://developer.themoviedb.org/reference/movie-popular-list);

- Deve ser possível navegar para os detalhes de cada filme a partir da lista/grid;

- O filme poderá ser favoritado tanto na lista/grid quanto na tela de detalhes;

- Os filmes favoritados devem ser persistidos no device para que possam ser acessados offline e serem mostrados em uma aba própria;

- A Tela de detalhes do filme deve conter o gênero do filme por extenso (ex: Action, Horror, Aventure, etc). Use essa [request](https://developer.themoviedb.org/reference/genre-movie-list) da API para trazer a lista;

- Implementar uma forma de buscar filmes na tela inicial;

- Tratamento de erros e apresentação dos fluxos de exceção: Busca vazia, Error, Loading.

## API 
Para desenvolver o app utilize especificamente versão 3 da [API](https://developer.themoviedb.org/reference/getting-started) do [TheMovieDB](https://www.themoviedb.org), não usar a nova versão 4.

## Interface 
A interface do app é dividida em 3 partes e deve ser desenvolvida conforme os pontos abaixo.

### 1 Home - Filmes

- Listagem dos filmes;

- Botão para favoritar nas células;

- Barra de busca para filtrar lista de filmes por nome;

- Interface de lista vazia, erro ou sem internet.

### 2 Detalhes do filme

- Botão de favorito;

- Botão para compartilhar a imagem do filme;

- Poster em tamanho maior;

- Título do Filme;

- Gêneros do Filme (ex: Action, Horror, Aventure, etc);

- Descrição (se houver).

### 3 Favoritos

- Listagem dos filmes favoritados pelo usuário;

- Interface de lista vazia, erro ou sem internet.

### Requisitos Essenciais

- Usar Kotlin;

- Arquitetura MVVM;

- Tratamento para falha de conexão;

- Documentação da solução no *README*;

- Testes unitários.

### Requisitos Adicionais

- Testes de interface;

- A aplicação não apresentar crash;

- Componentes reutilizáveis UI;

- Estruturado dentro de um modelo de arquitetura/modular;

- Uso de Engenharia de Prompt.

# Importante

- Subir o desafio em um repositório no público e mandar o link;

- Não ter nenhuma mensão do Itaú no Repositório/Projeto;

- Você pode utilizar bibliotecas de terceiros e gerenciadores de dependências como preferir;

- Foque o desenvolvimento nos requisitos essenciais.

## Sobre a documentação

Nesta etapa do processo seletivo queremos entender as decisões por trás do código, portanto é fundamental que o *README* tenha algumas informações referentes a sua solução.

Algumas dicas do que esperamos ver são:

- Instruções básicas de como executar o projeto;
- Detalhes da descrição dos métodos;
- Caso algo não esteja claro e você precisou assumir alguma premissa, quais foram e o que te motivou a tomar essas decisões.

## Como esperamos receber sua solução

Esta etapa é eliminatória, e por isso esperamos que o código reflita essa importância.

Se tiver algum imprevisto, dúvida ou problema, por favor entre em contato com a gente, estamos aqui para ajudar.

Nos envie o *link de um repo público* com a sua solução
