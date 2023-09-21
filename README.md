<span id="topo">

<h1 align="center">Sprint 1: 04/09/2023 a 24/09/2023</h1>

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a> &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Para início do desenvolvimento de uma aplicação para a visualização da proeminência de temas ao classificar as experiências de usuários a partir de seus comentários, nesta primeira sprint, tendo em mente o MVP, o time trabalhou nas funcionalidades mais valiosas, como a captura dos dados a partir da base de comentários fornecida, a limpeza desses dados, a formatação desses comentários e então seu armazenamento após o processamento. Houve também o desenvolvimento de uma interface web aonde há a autenticação e autorização de usuários, assim como o motor de busca para pesquisa dos comentários.

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:

- :heavy_check_mark: **RF 01:** Processamento de dados
- :heavy_check_mark: **RF 02:** Classificação de temas
- :heavy_check_mark: **RF 05:** Motor de busca
- :heavy_check_mark: **RF 06:** CRUD de usuários
- :heavy_check_mark: **RNF 08:** Documentação no GitHub com mapeamento das entregas
- :heavy_check_mark: **RNF 09:** Utilização de TypeScript e Python

<span id="entregas">
        
## 📲 Entregas
Para entregas da sprint, tivemos os artefatos SCRUM validados, como Backlog do Produto, Backlog das Sprints, Épicos e User Stories, através de comunicação direta entre o P.O. e o cliente. Para observar esses artefatos, acesse [este link](https://github.com/The-Bugger-Ducks/mood-hound-documentation#backlogs).

Para extrair e entender os desejos do cliente, foi construído um protótipo inicial no Figma, criando a identidade visual e design do sistema e apresentando para validação com o cliente, onde o resultado deste protótipo foi traduzido para uma aplicação em React e com as devidas integrações das funcionalidades acordadas para esta sprint.

### RF 01: Processamento de dados

Sendo um processo fundamental para a preparação dos dados para maiores manuseios, o processamento dos dados consiste na análise dos textos fornecidos nos comentários de clientes sobre produtos, nos quais o processamento de linguagem natural (PLN) realiza um insight desses dados, fazendo que o acesso às informações extraídas possibilite o estudo e maiores compreensões das informações que possuímos.

### RF 02: Classificação de temas

A classificação de temas, no contexto do processamento de linguagem natural (PLN), refere-se a outra tarefa fundamental em que um sistema de PLN atribui automaticamente uma categoria ou rótulo a um pedaço de texto com base no conteúdo e no significado desse texto. Essa categoria ou “rótulo” representa o tópico, assunto ou tema principal abordado no texto. A classificação de temas é uma forma de análise de texto que ajuda a organizar e categorizar grandes volumes de informações textuais de maneira mais eficiente e automatizada.

### RF 05: Motor de busca

Um motor de busca, também conhecido como mecanismo de busca ou buscador, é um sistema de software projetado para ajudar os usuários a encontrar informações. O objetivo principal de um motor de busca é permitir que os usuários localizem rapidamente conteúdo relevante com base em palavras-chave, frases ou consultas de pesquisa. Nesse projeto ele está sendo utilizado para pesquisa de usuários e também de palavras-chave em comentários realizados.

### RF 06: CRUD de usuários

Este requisito se trata do cadastro, listagem, edição e exclusão de usuários, onde, para isso, foi desenvolvido um fluxo básico de login e o acesso ao app, permitindo todas essas ações pelo usuário logado. A criação de contas, bem como outras ações relacionadas a contas de usuário serão desenvolvidas em próximas sprints, ao passo que toda a manipulação de parcerias, a grosso modo, já está estruturada e em pleno funcionamento.

### RNF 08: Documentação no GitHub com mapeamento das regras de negócio do cliente

Este requisito não funcional se trata da documentação criada e armazenada no GitHub (como este arquivo). Para visualizar os artefatos da sprint, como backlogs (do produto e da sprint) acesse a [documentação geral do projeto](https://github.com/The-Bugger-Ducks/mood-hound-documentation).

### RNF 09: Utilzação de TypeScript e Python

Este requisito não funcional se trata da utilização de Typescript e Python, que foi satisfeito ainda nesta sprint, dado que tanto no servidor, feito com Node, foi utilizado o Typescript quanto na aplicação web, feita com React. Python foi utilizado para as práticas de processamento de linguagem natural, em especial, com o uso das bibliotecas NLTK e Spacy.

→ [Voltar ao topo](#topo)

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Nesta sprint o time se dividiu entre mobile e backend, onde o mobile se responsabilizou pela criação da interface e integrações das funcionalidades e o backend pela estruturação do banco de dados e rotas a serem consumidas. 
- Abaixo se encontra o gráfico Burndown gerado pela equipe nesta sprint, onde o eixo X são os dias trabalhados e o eixo Y representa as entregas de cada dia:
    
<div align="center">

[inserir imagem do burndown]

<!-- <img src="https://user-images.githubusercontent.com/79321198/235674242-e743ebe7-1de7-410e-98c2-4df5144b5fee.png" alt="Gráfico Burndown" /> -->

</div>

## 🐞 Métricas de análise estática do código

|               Modalidade                | Repositório web | Repositório back | Repositório nlp |
| :-------------------------------------: | :-------------: | :--------------: | :-------------: |
| Blocker, Critical, Major e Minor Issues |                 |                  |                 |
|                  Bugs                   |                 |                  |                 |
|             Vulnerabilities             |                 |                  |                 |
|             Security Review             |                 |                  |                 |
|          Duplicidade de Código          |       -%        |        -%        |       -%        |
|              Quality Gate               |                 |                  |                 |

<span id="links">
    
## :link: Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 1ª sprint:
  - Repositório da aplicação: [clique aqui para acessar "mood-hound-web"](https://github.com/The-Bugger-Ducks/mood-hound-web)
  - Repositório da API: [clique aqui para acessar "mood-hound-back"](https://github.com/The-Bugger-Ducks/mood-hound-back)
  - Repositório de PLN: [clique aqui para acessar "mood-hound-nlp"](https://github.com/The-Bugger-Ducks/mood-hound-nlp)

→ [Voltar ao topo](#topo)
