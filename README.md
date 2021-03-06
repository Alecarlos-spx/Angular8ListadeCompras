# Projeto Lista de Compras

Este projeto foi criado com o [Angular CLI](https://github.com/angular/angular-cli) versão 8.3.18.

Você pode acessar ele pelo [Github Pages](https://github.com/Alecarlos-spx/Angular8ListadeCompras). Foi utilizado um Json-server para simular um backend e seus end-points e serviços.

## Escopo

O projeto foi desenvolvido em Angular 8, utilizando a abordagem SPA com as seguintes funcionalidades:

- Lista de locais para realização de compras, com funcionalidade de Adicionar/Editar/Excluir e inserir uma sublista de produtos a serem comprados no local.
- Relação de itens do local para compras, nela são colocados todos os itens que serão comprados no local. Nesta tela a opção de ticar o item como feito, exluir/editar/adicionar novo item.
Construir a estrutura do projeto utilizando o npm (gerenciador de pacotes do Node.js);

- Foi utilizado um design básico para páginas (foi utilizado bibliotecas/frameworks: bootstrap e Angular Material )

## Tecnologias

- Angular CLI 8.3.18
- Bootstrap 4.6.0
- Node.js 12.16.1
- JSON Server 0.16.3

## Como instalar

- Baixe ou clone este repositório usando `git clone https://github.com/Alecarlos-spx/Angular8ListadeCompras.git`;
- Dentro do diretório, instale as dependências usando `npm install`.

## Como executar

Execute `ng serve` para executar a versão de desenvolvimento. Depois acesse `http://localhost:4200/`.

Para executar o servidor de endpoints de API, em um outro terminal na mesma pasta execute `json-server --watch db.json`. A API poderá ser acessada via `http://localhost:3000/`.
## Como compilar/construir

Execute `ng build` para buildar o projeto. Para buildar a versão de produção adicione a flag `--prod`. Os arquivos serão armazenados do diretório `dist`.

