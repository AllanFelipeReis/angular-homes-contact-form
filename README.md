# Angular Homes - Formulário de Contato

Este repositório contém um tutorial inicial do Angular que mostra um projeto para listar residências, recuperar detalhes específicos da residência e implementar um formulário de contato para usuários interessados. Além disso, inclui uma configuração de API mock usando o JSON Server para simular interações com o backend.

## Recursos

1. **Listagem de Residências:** Uma página inicial lista as residências disponíveis, exibindo informações básicas como título, preço e localização.

2. **Detalhes da Residência:** Os usuários podem visualizar detalhes específicos de uma residência selecionada, incluindo descrição completa, imagens e recursos adicionais.

3. **Formulário de Contato:** Implementação de um formulário de contato que permite aos usuários interessados enviar mensagens diretamente aos proprietários das residências.

4. **API Mock:** O JSON Server é utilizado para fornecer uma API REST mock para gerenciar listagens de residências e envios de formulários de contato.

## Pré-requisitos

Antes de começar, certifique-se de ter o Node.js e o Angular CLI instalados em sua máquina.

## Instalação

1. Clone este repositório.
2. Navegue até o diretório clonado.
3. Instale as dependências usando npm:

`npm install`

## Executando o Projeto

1. Inicie o JSON Server executando o seguinte comando:

`json-server --watch db.json`

Isso iniciará o servidor mock da API.

2. Em um terminal separado, inicie o servidor de desenvolvimento do Angular:

`ng serve`

Isso iniciará o servidor de desenvolvimento. Navegue até `http://localhost:4200/` em seu navegador para visualizar o projeto.
