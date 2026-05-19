# Documento de Requisitos do Projeto: API de Séries e Filmes

A tabela abaixo apresenta os requisitos funcionais detalhados para uma **API de gerenciamento de listas de séries e filmes**.

| ID do Requisito | Descrição | História do Usuário | Comportamento/Resultado Esperado |
|----------------|-----------|----------------------|-----------------------------------|
| RF01 | Criar uma nova lista | Como consumidor da API, quero criar uma nova lista vazia para começar a adicionar séries ou filmes. | A API deve disponibilizar um endpoint para criação de uma nova lista e retornar um identificador único da lista criada. |
| RF02 | Adicionar séries/filmes à lista | Como consumidor da API, quero adicionar séries ou filmes informando seus nomes ou IDs para organizar minha lista. | A API deve permitir inserir itens (séries/filmes) em uma lista existente via requisição, retornando confirmação da inclusão. |
| RF03 | Consultar itens da lista | Como consumidor da API, quero listar todas as séries ou filmes de uma lista para visualizar seu conteúdo. | A API deve retornar todos os itens associados a uma lista específica, incluindo nome e metadados quando disponíveis. |
| RF04 | Atualizar item da lista | Como consumidor da API, quero editar informações de uma série ou filme na lista caso haja erro ou atualização. | A API deve permitir a atualização de um item específico dentro da lista. |
| RF05 | Remover item da lista | Como consumidor da API, quero remover uma série ou filme da lista quando não desejar mais mantê-lo. | A API deve permitir a exclusão de itens individuais da lista. |
| RF06 | Publicar lista | Como consumidor da API, quero publicar uma lista para torná-la acessível publicamente. | A API deve alterar o status da lista para pública e gerar um link de acesso compartilhável. |
| RF07 | Compartilhar lista | Como consumidor da API, quero obter um link de compartilhamento da lista para uso externo. | A API deve retornar uma URL pública da lista com possibilidade de acesso externo. |
| RF08 | Acessar lista pública | Como usuário externo, quero acessar uma lista publicada para visualizar seus conteúdos. | A API deve permitir a leitura de listas públicas via endpoint sem necessidade de autenticação. |
| RF09 | Listar todas as listas do usuário | Como consumidor da API, quero recuperar todas as listas que criei para gerenciamento. | A API deve retornar todas as listas associadas a um usuário autenticado. |
| RF10 | Excluir lista | Como consumidor da API, quero excluir uma lista inteira quando não precisar mais dela. | A API deve remover a lista e todos os seus itens associados permanentemente. |