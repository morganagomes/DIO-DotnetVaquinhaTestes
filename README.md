## Implementando sua stack de testes de unidade e integrados em um projeto .NET de Crowdfunding :cow:

Projeto desenvolvido pelo instrutor e arquiteto de software Eliézer Zarpelão como parte das atividades do **Bootcamp Decola Dev 2021**, uma parceria da Digital Innovation One e da Avanade. :orange:

-----

:writing_hand: <u>Pontos importantes</u>¹:

- A importância de testar o código e realizar esse procedimento como parte do desenvolvimento de software.
- Quando não realizamos testes, corremos o risco de ter:
  - um maior número de bugs;
  - menos qualidade;
  - mais atrasos;
  - menor confiança por parte do cliente;
  - maior desmotivação na equipe de desenvolvimento;
  - maior turnover;
  - mais prejuízos;
  - mais implicações legais. 
- Regra de 10 de Myers: ao encontrar um erro, multiplicá-lo por 10. Assim, podemos ter ideia do impacto dos problemas no desenvolvimento de aplicações. Quanto antes for detectado, menor o impacto.
- Tipos de teste
  - de unidade (UnitTest)
    - teste da menor parte testável de um software.
    - orientação a objetos: classe.
  - de integração
    - encontrar falhas de integração entre as unidades.
    - integração entre unidades ou sistemas.
  - automatizados
    - "simula" as ações do usuário;
    - também chamado de _caixa preta_;
    - teste de regressão que garante a integridade de versões passados;
    - por ser um processo caro, é preciso selecionar as funcionalidades que serão testadas.
- De acordo com a documentação da Microsoft, MVC (Model View Controller)
  - Model: armazena, manipula e gera os dados;
  - View: apresenta o conteúdo por meio da interface do usuário;
  - Controller: cuida da interação do usuário, trabalha com o _model_ e, em última análise, seleciona uma _view_ renderizada.

![Padrão MVC](https://docs.microsoft.com/pt-br/aspnet/core/mvc/overview/_static/mvc.png?view=aspnetcore-5.0)



Fonte: https://docs.microsoft.com/pt-br/aspnet/core/mvc/overview?view=aspnetcore-5.0

----

Link para o projeto original no Github: https://github.com/elizarp/dotnet-vaquinha-tests

[^1]: Breve fichamento do que foi apresentado durante a aula.