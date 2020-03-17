## Descrição
Elabore uma aplicação para um Quizz que possua as características abaixo:
- Permita a criação de um banco de perguntas;
- Cada pergunta deve possuir N alternativas sendo **apenas uma correta**;
- Permita apenas uma resposta por usuário;
- Exibição do percentual de acerto após o envio;


## O que esperamos:

- Passo-a-passo de como rodar sua aplicação no README.md;
- Clean code;
- Commits semânticos;
- Tratamento de erros;
- Enviar um link para um repositório com a solução;

### Back-end:
- Que o desafio seja feito em Python 3+;
- Uma API REST com Django;
- Um admin para gestão dos usuários, questões e suas alternativas, podendo ser o nativo do próprio django;
- TDD;
- Princípios SOLID;
- 12Factor;
- PEP-8;

### Front-end:

Para o front, implemente uma interface que permita informar o nome do usuário, em seguida exiba a lista de perguntas e alternativas e mostre o resultado após repondê-las. Para isso é necessária a integração com os serviços do back-end.

- Utilize alguma biblioteca para criar interfaces baseadas em componentes (React, Vue, etc.);
- Pense que um time possa trabalhar nesse projeto, se atente à tudo que possa tornar o desenvolvimento mais ágil (lints, CI's, TDD, padrões de linguagem);
- Atente-se para acessibilidade;
- Faça uma interface simples de usar (Pode usar bibliotecas de UI);
- (Extra) Typescript;


## Desafios extras (não obrigatório):
- Utilizar o [Django Rest Framework](https://www.django-rest-framework.org/)
- Utilização de [Docker](https://www.docker.com/);
- Banco de dados [PostGreSQL](https://www.postgresql.org/) ou [MySQL](https://www.mysql.com/);
- Testes no backend com [pytest](https://docs.pytest.org/en/latest/);
- Integração com algum CI ([Travis](https://travis-ci.org/), [CircleCI](https://circleci.com/), etc);
- Deploy na nuvem ([AWS](https://aws.amazon.com/), [Heroku](https://www.heroku.com/), etc.)
