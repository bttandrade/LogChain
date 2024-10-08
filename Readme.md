# LogChain

LogChain é um sistema de gerenciamento logístico que permite o controle de produtos, boxes e envios.

## Funcionalidades

- Autenticação de usuários
- Gerenciamento de produtos
- Criação e gerenciamento de boxes
- Registro e acompanhamento de envios
- Visualização de rotas de entrega

## Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript
- Firebase (Autenticação e Firestore)
- Leaflet (para mapas e rotas)

## Estrutura do Projeto

- `index.html`: Página de login
- `src/pages/`: Contém as páginas HTML do sistema
  - `products.html`: Gerenciamento de produtos
  - `boxes.html`: Gerenciamento de boxes
  - `envio_screen.html`: Registro e acompanhamento de envios
- `src/js/`: Contém os scripts JavaScript
  - `login.js`: Lógica de autenticação
  - `produto.js`: Operações relacionadas a produtos
  - `boxes.js`: Operações relacionadas a boxes
  - `firebase/`: Configurações e operações do Firebase
- `src/css/`: Arquivos de estilo CSS
- `src/img/`: Imagens utilizadas no projeto

## Como Executar

1. Clone o repositório
2. Abra o arquivo `index.html` em um navegador web