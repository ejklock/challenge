# Frontend Programming challenge

## Critério de avaliação
 - Solução funcional
 - Organização do projeto
 - Clean code
 - UX/UI (use a imagem fornecida como ponto de partida)

## Descrição

O objetivo desse desafio é avaliar suas habilidades para construção de uma aplicação Single Page Application (SPA) usando [React.js](https://reactjs.org) para a construção da interface. Essa aplicação deverá se comunicar com a API descrita em [Backend.md](https://github.com/orbita-cc/challenge/blob/master/Backend.md#backend-programming-challenge).

 A aplicação deve ter três páginas:
  - Login
  - Criação de conta
  - Dashboard
  
Apenas usuários logados podem ter acesso à página de Dashboard. Use a imagem abaixo como um guia para sua aplicação.

![Dashboard look](https://github.com/sauloaguiar/orbita.cc/blob/master/data/dahsboard.jpg "Dashboard")

  
É esperado que você implemente as seguintes visualizações:
  - Timeline com o número de instalações agrupadas pelo estado (atributo `State` no conjunto de dados)
  - Capacidade instalada (atributo `System Size` no conjunto de dados) agrupada pelo ano de instalação
  - Custo agrupado pelo mês de instalção

Os 3 widgets disponíveis nas imagens devem mostrar:
  1. Número de instalações feitas *
  2. Mostrar a instalação com maior custo *
  3. Mostrar os 3 meses do ano com o maior número de instalações *. Deve ser mostrada as infomações:
    - CEP
    - Colocação
    - Total instalado
    
⚠️ Todas as informações mostradas no Dashboard devem abranger apenas o estado (`State`) do usuário logado.

## Requisitos obrigatórios
 - Crie um arquivo README mostrando como executar sua aplicação
 - Utilizar React para construção da UI. Se preferir, use o [create-react-app](https://github.com/facebook/create-react-app) como ponto de partida
 - Padronização do código: seguir algum styleguide de JavaScript e CSS. Se preferir utilize o [Prettier](https://prettier.io/)

## Bônus
 - Implementar testes
 - Gerenciar estado da aplicação utilizando [Redux](https://redux.js.org)
   - Nesse caso, utilizar [redux-thunk](https://github.com/reduxjs/redux-thunk) para chamadas assíncronas
   
 
