# Frontend Programming challenge

## Critério de avaliação
 - Solução funcional
 - Organização do projeto
 - Clean code
 - UX/UI (use a imagem fornecida como ponto de partida)
 - Deploy

## Descrição

O objetivo desse desafio é avaliar suas habilidades para construção de uma aplicação Single Page Application (SPA) usando React.js para a construção da interface. Nós provemos um [arquivo JSON]() contendo dados de instalação de painéis solares que você deve usar para construção de um gráfico. A tabela abaixo mostra a descrição de cada atributo.

| Nome  | Descrição |
| ------------- | ------------- |
| Data Provider  | TODO  |
| Installation Date  | TODO  |
| System Size  | TODO  |
| Zip Code  | TODO  |
| State | TODO  |
| Cost | TODO  |

 A aplicação deve ter três páginas:
  - Login
  - Criação de conta
  - Dashboard
  
Apenas usuários logados podem ter acesso à Página de Dashboard. Use a imagem abaixo como um guia para sua aplicação.

![Dashboard look](https://github.com/sauloaguiar/orbita.cc/blob/master/data/dahsboard.jpg "Dashboard")

  
  
É espera que você implemente as seguintes visualizações:
  - Timeline com o número de instalações agrupadas pelo mês de instalação
  - Capacidade instalada agrupada pelo ano de instalação
  - Custo agrupado pelo mês de instalção

  Também, os 3 widgets disponíveis nas imagens devem mostrar:
  - Número de instalação no período
  - Mostrar a instalação com maior custo
  - Mostrar as 3 maiores empresas com maior número de instalação
    Nome da empresa
    Total instalado

## Requisitos
 - Crie um README mostrando como executar sua aplicação
 - Deploy em um cloud provider de sua escolha (Heroku, AWS, Azure, Google)
 - Projeto deve ser versionado com Git
 - Usar um framework/lib JS para construção do SPA (preferenciamente React.js) 
 - ### Bonus
   - Implementar testes
