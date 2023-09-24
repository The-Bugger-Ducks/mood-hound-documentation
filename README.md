<span id="topo">

![mood hound header sprint 1](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/8ee60896-5d07-4367-9583-f0d65b6c1f13)

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a>  &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#analise">Métricas de análise estática </a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Para início do desenvolvimento de uma aplicação para a visualização da proeminência de temas ao classificar as experiências de usuários a partir de seus comentários, nesta primeira sprint, tendo em mente o MVP, o time trabalhou nas funcionalidades mais valiosas, como a captura dos dados a partir da base de comentários fornecida, a limpeza desses dados, a formatação desses comentários e então seu armazenamento após o processamento. Houve também o desenvolvimento de uma interface web aonde há a autenticação e autorização de usuários, assim como o motor de busca para pesquisa dos comentários.

<br />

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:

- :heavy_check_mark: **RF 01:** Processamento de dados
- :heavy_check_mark: **RF 02:** Classificação de temas
- :heavy_check_mark: **RF 05:** Motor de busca
- :heavy_check_mark: **RF 06:** CRUD de usuários
- :heavy_check_mark: **RNF 08:** Documentação no GitHub com mapeamento das entregas
- :heavy_check_mark: **RNF 09:** Utilização de TypeScript e Python

<br />

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

<br />

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Nesta sprint o time se dividiu entre mobile e backend, onde o mobile se responsabilizou pela criação da interface e integrações das funcionalidades e o backend pela estruturação do banco de dados e rotas a serem consumidas. 
- Abaixo se encontra o gráfico Burndown gerado pela equipe nesta sprint, onde o eixo X são os dias trabalhados e o eixo Y representa as entregas de cada dia:
    
<div align="center">

<img src="https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/97e96bb5-aa59-497a-b439-f3e045dab9f5" alt="Gráfico Burndown" />

</div>

→ [Voltar ao topo](#topo)

<br />

<span id="analise">

## 🐞 Métricas de análise estática do código

<div align="center">

|               Modalidade                |                                                Repositório web                                                |                                               Repositório back                                                |                                                Repositório nlp                                                |
| :-------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
| Blocker, Critical, Major e Minor Issues |                                                       0                                                       |                                                       0                                                       |                                                       0                                                       |
|                  Bugs                   |                                                       0                                                       |                                                       0                                                       |                                                       0                                                       |
|               Code Smells               |                                                       2                                                       |                                                       0                                                       |                                                       2                                                       |
|             Vulnerabilities             |                                                       0                                                       |                                                       0                                                       |                                                       0                                                       |
|             Security Review             |                                                       0                                                       |                                                       0                                                       |                                                       0                                                       |
|          Duplicidade de Código          |                                                     0.0%                                                      |                                                     0.0%                                                      |                                                     0.0%                                                      |
|              Quality Gate               | <img src="https://img.shields.io/badge/Passed-25D366?style=for-the-badge&logoColor=white" alt="Passed Badge"> | <img src="https://img.shields.io/badge/Passed-25D366?style=for-the-badge&logoColor=white" alt="Passed Badge"> | <img src="https://img.shields.io/badge/Passed-25D366?style=for-the-badge&logoColor=white" alt="Passed Badge"> |

</div>

**Estratégias de correção:** Aos itens apresentados, a estratégia de correção aderida será a inicialização de testes unitários para cada um dos repositórios na sprint 02. Será necessário também, mediante a implementação dos testes unitários, determinar uma porcentagem de cobertura de testes, inicialmente pensamos em 40%.Para solucionar os code smells existentes e vitar que esses números aumentem, definiremos para a sprint 02 (e continuaremos implementando nas seguintes sprints) atividades de refatoração para que os débitos técnicos presentes sejam sanados e durante as code reviews, trazer também a correção de pequenos débitos técnicos a fim de evitar maiores dificuldades futuras.

<details>
<summary>Imagem do resumo das análises do repositório web</summary>

![sonarqube web quality gate](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/13a57cbd-7d9d-48f6-979c-91de96ad56a5)
![sonarqube web findings](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/8cb5ca97-bd6e-404a-93c7-8454b71de4b8)
![sonarqube web duplications](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/2e22d4fa-b65e-42b6-b5f2-7a4fef9d7e2f)

</details>

<details>
<summary>Imagem do resumo das análises do repositório backend</summary>

![sonarqube back quality gate](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/5af2ab3f-26cd-44aa-bd43-db638c53d8b9)
![sonarqube back findings](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/3da7b269-8a57-4480-8e9a-9ffa4e9ccc79)
![sonarqube back duplications](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/bcdfa0ee-3e4c-4538-8bb4-debaeda13a96)

</details>

<details>
<summary>Imagem do resumo das análises do repositório NLP</summary>

![sonarqube nlp quality gate](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/b87ce4b2-3fd6-4d0a-b817-b33283041378)
![sonarqube nlp findings](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/a13901eb-8c72-4b87-8591-484d16c0e214)
![sonarqube nlp duplications](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/b00d0800-15e0-4c29-bba8-1606bc100320)

</details>

→ [Voltar ao topo](#topo)

<span id="links">

<br/>
    
## :link: Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 1ª sprint:
  - Repositório da aplicação: [clique aqui para acessar "mood-hound-web"](https://github.com/The-Bugger-Ducks/mood-hound-web)
  - Repositório da API: [clique aqui para acessar "mood-hound-back"](https://github.com/The-Bugger-Ducks/mood-hound-back)
  - Repositório de PLN: [clique aqui para acessar "mood-hound-nlp"](https://github.com/The-Bugger-Ducks/mood-hound-nlp)

→ [Voltar ao topo](#topo)
