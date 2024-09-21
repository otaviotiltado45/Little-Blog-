# Little Blog

Little Blog é uma aplicação simples de blog construída com React! Aqui você pode criar, visualizar e deletar posts com facilidade. Este projeto é um ótimo ponto de partida para quem deseja aprender sobre gerenciamento de estado e componentes funcionais no React.

## Estrutura do Projeto

O projeto é dividido em vários componentes principais, cada um responsável por uma parte da funcionalidade da aplicação:

- **App.js**: O componente principal que gerencia o estado dos posts.
- **PostForm.js**: Um formulário para adicionar novos posts.
- **PostList.js**: Uma lista que renderiza todos os posts.
- **PostItem.js**: Um componente que representa um post individual, com opção de visualizar o conteúdo completo em um modal.
- **Modal.js**: Um componente que exibe o conteúdo completo do post em uma janela modal.
- **PostStyles.js**: Um arquivo que contém os estilos globais e específicos da aplicação, usando styled-components.

## Como Usar

### Instalação

Certifique-se de ter o Node.js instalado. Clone este repositório e, em seguida, instale as dependências:

npm install
Execução
A aplicação será iniciada em http://localhost:3000.

npm start
Componentes
## App.js
Gerencia o estado dos posts.
Possui funções para adicionar e deletar posts.
## PostForm.js
Permite ao usuário adicionar um novo post.
Valida o título para garantir que não exceda 50 caracteres.
## PostList.js
Renderiza uma lista de PostItem com todos os posts disponíveis.
## PostItem.js
Exibe um post individual, incluindo título, conteúdo truncado e uma imagem.
Possui um botão "Leia mais" que abre um modal com o conteúdo completo do post.
## Modal.js
Exibe o conteúdo completo do post em uma janela modal.
Inclui um botão para fechar o modal.
## PostStyles.js
Define estilos globais e para os componentes da aplicação usando styled-components.
```
