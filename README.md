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

O processamento dos dados consiste na análise dos textos fornecidos para que sejam extraídas informações que possibilitem o estudo mais aprofundado desses dados. Com isso, nosso time teve como foco, nessa primeira sprint, realizar a captura dos dados disponibilizados (através [deste link](https://github.com/americanas-tech/b2w-reviews01), que foi previamente acordado com o parceiro acadêmico) fazendo também a limpeza que consiste em remover colunas que não serão utilizadas no processo de análise dos dados, mas também houve a limpeza e formatação dos próprios comentários das avaliações, removendo stop words (artigos e preposições) e palavras muito curtas, preparando assim os dados para próximas etapas como a de classificação.

### RF 02: Classificação de temas

A classificação de temas, no contexto do processamento de linguagem natural (PLN), refere-se a tarefa de atribuir automaticamente um rótulo a um pedaço de texto com base em seu conteúdo e significado, assim extraindo o tema principal abordado. Nesse projeto, os temas encontrados para as classificações são oriundos do exercício de processamento de dados, onde a equipe apurou as principais categorias citadas nos comentários com análise das frases e palavras levando em conta atributos do produto, serviço e processo, além de agrupar as avaliações também em negativas, positivas e neutras.

### RF 05: Motor de busca

Um motor de busca, também conhecido como mecanismo de busca ou buscador, é um sistema de software projetado para ajudar os usuários a encontrar informações. Foi desenvolvido pela equipe um motor de busca que permite que os usuários localizem rapidamente conteúdos a partir de palavras-chave que venham a existir em alguns comentários existentes na base de dados que foi previamente processada, classificada e armazenada. Através do que foi desenvolvido, é possível também que um usuário administrador realize pesquisas de usuários.

### RF 06: CRUD de usuários

Este requisito se trata do cadastro, listagem, edição e exclusão de usuários, onde, para isso, foi desenvolvido um fluxo básico de login e o acesso ao app, permitindo todas essas ações pelo usuário logado. A criação de contas, bem como outras ações relacionadas a contas de usuário serão desenvolvidas nas próximas sprints, assim como o gerenciamento de permissões dos usuários através de um usuário administrador.

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
| Blocker, Critical, Major e Minor Issues |         0        |         0         |                 |
|                  Bugs                   |         0        |         0         |                 |
|             Vulnerabilities             |         0        |         0         |                 |
|             Security Review             |         0        |         0         |                 |
|          Duplicidade de Código          |       -%         |        0.0%       |       -%        |
|              Quality Gate               |<img src="https://img.shields.io/badge/Passed-25D366?style=for-the-badge=white" alt="Passed Badge">|                  |                 |

<span id="links">
    
## :link: Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 1ª sprint:
  - Repositório da aplicação: [clique aqui para acessar "mood-hound-web"](https://github.com/The-Bugger-Ducks/mood-hound-web)
  - Repositório da API: [clique aqui para acessar "mood-hound-back"](https://github.com/The-Bugger-Ducks/mood-hound-back)
  - Repositório de PLN: [clique aqui para acessar "mood-hound-nlp"](https://github.com/The-Bugger-Ducks/mood-hound-nlp)

→ [Voltar ao topo](#topo)
