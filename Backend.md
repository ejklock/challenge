# Backend Programming challenge

## Critério de avaliação
 - Solução funcional
 - Organização do projeto
 - Clean code
 - Deployment

## Descrição
  O desafio consiste em construir um API para servir os dados para a aplicação Front-end. Para isso, você deverá um conjunto de dados (solar_data.json) no banco de dados de sua escolha. Você deverá expor esses dados através da API.
  
  **Você deverá implementar controle de acesso com o objetivo de expor os dados apenas para usuários logados**. Você pode implementar isso usando o mecanismo que preferir (JWT ou OAuth, por exemplo).
  A tabela de usuários deverá conter pelos menos os seguintes atributos: `name`, `email`, e `state`.
  Como requisito, cada usuário só pode ter acesso a dados de instalações solares do seu estado. Em hipótese algum ele deve deve ter acesso a dados de outro estado. Caso um usuário tente acessar dados de um estado que não seja o seu, a API deve retornar o [status HTTP 401 Unauthorized](https://httpstatuses.com/401).
  Como parte do desafio você deverá também criar o endpoinst `/users`. O que queremos avaliar aqui é como você pensa sobre a modelagem desde endpoint e o porquê de você ter definido ele da forma escolhida. Nós esperamos que você se coloque no lugar do cliente da sua API.

## Requisitos
  - Crie um README mostrando como executar sua aplicação
  - Deploy em um cloud provider de sua escolha (Heroku, AWS, Azure, Google)
  - Projeto deve ser versionado com Git
  - A API deve retornar os dados apenas para usuário logados
  - Usar **node.js**
  - ### BONUS
    - Implementar testes
    - Documentar a API
 
