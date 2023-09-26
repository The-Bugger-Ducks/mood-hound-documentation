<span id="topo">

![mood hound header sprint 1](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/8ee60896-5d07-4367-9583-f0d65b6c1f13)

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a>  &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#analise">Métricas de análise estática </a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Para o início do desenvolvimento de uma aplicação para a visualização da proeminência de temas ao classificar as experiências de usuários a partir de suas avaliações, nesta primeira sprint, tendo em mente o MVP, o time trabalhou nas funcionalidades mais valiosas, como a captura dos dados (a partir da base de comentários fornecida), a limpeza e formatação desses dados, e então seu armazenamento após o processamento. Na "frente web" tem-se o desenvolvimento de uma interface com a integração de autenticação e autorização de usuários, bem como o motor de busca para pesquisa em comentários.

<br />

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:

- :heavy_check_mark: **RF 01:** Processamento de dados
- :heavy_check_mark: **RF 02:** Classificação de temas
- :heavy_check_mark: **RF 05:** Motor de busca
- :heavy_check_mark: **RF 06:** CRUD de usuários
- :heavy_check_mark: **RNF 08:** Documentação no GitHub com mapeamento das entregas
- :heavy_check_mark: **RNF 09:** Utilização de Typescript e Python

<br />

<span id="entregas">
        
## 📲 Entregas
Para as entregas da sprint, tivemos os artefatos SCRUM validados, como Backlog do Produto, Backlog das Sprints, Épicos e User Stories, através de comunicação direta entre o P.O. e o cliente. Para observar esses artefatos, acesse [este link](https://github.com/The-Bugger-Ducks/mood-hound-documentation#backlogs).

Para extrair e entender os desejos do cliente, foi construído um protótipo inicial no Figma, criando a identidade visual e design do sistema e apresentando para validação com o cliente, onde o resultado deste protótipo foi traduzido para uma aplicação em React e com as devidas integrações das funcionalidades acordadas para esta sprint.

### RF 01: Processamento de dados

O processamento dos dados consiste na análise dos textos fornecidos para que sejam extraídas informações que possibilitem o estudo mais aprofundado desses dados. Com isso, nosso time teve como foco, nessa primeira sprint, realizar a captura dos dados disponibilizados (através [deste link](https://github.com/americanas-tech/b2w-reviews01), que foi previamente acordado com o parceiro acadêmico), fazendo a limpeza destes dados (removendo colunas que não serão utilizadas no processo de análise dos dados), mas também aplicando limpeza e formatação nos comentários das avaliações, removendo stop words (artigos e preposições) e palavras muito curtas, além de realizar outros passos de processamento como "lematização", "vetorização" e etc, preparando assim os dados para próximas etapas como a de classificação.

### RF 02: Classificação de temas

A classificação de temas, no contexto do processamento de linguagem natural (PLN), refere-se a tarefa de atribuir automaticamente um rótulo a um pedaço de texto com base em seu conteúdo e significado, assim extraindo o tema principal abordado. Nesse projeto, os temas encontrados para as classificações são oriundos do exercício de processamento de dados, onde a equipe apurou as principais categorias citadas nos comentários com análise das frases e palavras levando em conta atributos do produto, serviço e processos operacionais, além de agrupar as avaliações também por sentimento, que pode ser negativo, positivo ou neutro, baseado nas "estrelas" que a avaliação tem.

### RF 05: Motor de busca

Um motor de busca, também conhecido como mecanismo de busca ou buscador, é um sistema de software projetado para ajudar os usuários a encontrar informações. Foi desenvolvido pela equipe um motor de busca que permite que os usuários localizem rapidamente conteúdos a partir de palavras-chave que venham a existir nos comentários disponíveis previamente processados, classificados e armazenados. Através do que foi desenvolvido, é possível também que um usuário administrador realize pesquisas de usuários.

### RF 06: CRUD de usuários

Este requisito se trata do cadastro, listagem, edição e exclusão de usuários, onde, para isso, foi desenvolvido um fluxo básico de login e o acesso ao app, permitindo todas essas ações pelo usuário logado. A criação de contas, bem como outras ações relacionadas a contas de usuário serão desenvolvidas nas próximas sprints, assim como o gerenciamento de permissões dos usuários através de um usuário administrador.

### RNF 08: Documentação no GitHub

Este requisito não funcional se trata da documentação criada e armazenada no GitHub (como este arquivo). Para visualizar os artefatos da sprint, como backlogs (do produto e da sprint) acesse a [documentação geral do projeto](https://github.com/The-Bugger-Ducks/mood-hound-documentation).

### RNF 09: Utilzação de Typescript e Python

Este requisito não funcional se trata da utilização de Typescript e Python, que foi satisfeito ainda nesta sprint, dado que tanto no servidor, feito com Node, foi utilizado o Typescript quanto na aplicação web, feita com React. Python foi utilizado para as práticas de processamento de linguagem natural, em especial, com o uso das bibliotecas Pandas e NLTK.

→ [Voltar ao topo](#topo)

<br />

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Nesta sprint o time se dividiu entre frontend, backend e nlp, onde a "frente nlp" teve como foco o processamento dos dados disponibilizados, bem como sua classificação e armazenamento no banco, enquanto que a "frente backend" se ocupou com tarefas acerca de autenticação, autorização e CRUD de usuários, além de, claro, manipulação dos comentários previamente classificados no banco. Já a "frente web" ficou responsável pela integração de tais funcionalidades.  
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
|                  Bugs                   |                                                       0                                                       |                                                       1                                                       |                                                       0                                                       |
|               Code Smells               |                                                       25                                                       |                                                       2                                                       |                                                       0                                                       |
|             Vulnerabilities             |                                                       0                                                       |                                                       0                                                       |                                                       0                                                       |
|             Security Review             |                                                       0                                                       |                                                       2                                                       |                                                       0                                                       |
|          Duplicidade de Código          |                                                     0.0%                                                      |                                                     0.0%                                                      |                                                     0.0%                                                      |
|              Quality Gate               | <img src="https://img.shields.io/badge/Passed-25D366?style=for-the-badge&logoColor=white" alt="Passed Badge"> | <img src="https://img.shields.io/badge/Failed-FECDCA?style=for-the-badge&logoColor=white" alt="Failed Badge"> | <img src="https://img.shields.io/badge/Passed-25D366?style=for-the-badge&logoColor=white" alt="Passed Badge"> |

</div>

**Estratégias de correção:** Aos itens apresentados, a estratégia de correção aderida será a inicialização de testes unitários para cada um dos repositórios na sprint 02. Será necessário também, mediante a implementação dos testes unitários, determinar uma porcentagem de cobertura de testes (inicialmente pensamos em 40%). Para solucionar os code smells existentes e evitar que esses números aumentem, definiremos para a sprint 02 (e continuaremos implementando nas seguintes sprints) atividades de refatoração para que os débitos técnicos presentes sejam sanados e, durante as code reviews, trazer também a correção de pequenos débitos técnicos a fim de evitar maiores dificuldades futuras.

<details>
<summary>Imagens do resumo das análises do repositório web</summary>

![sonarqube web quality gate](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/13a57cbd-7d9d-48f6-979c-91de96ad56a5)
![sonarqube web findings](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/1e18698d-c683-4471-9e18-327012e3555a)
![sonarqube web duplications](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/b23f5a1c-9a62-4484-9049-5eac8fb26ebb)

</details>

<details>
<summary>Imagens do resumo das análises do repositório backend</summary>

![sonarqube back quality gate](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/aa986733-34d5-426d-b226-3124f71a9669)
![sonarqube back findings](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/c901297b-d013-4bc7-a174-c1959556de14)
![sonarqube back duplications](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/170f0a75-a40d-4b00-bb8d-96fa28fca891)

</details>

<details>
<summary>Imagens do resumo das análises do repositório NLP</summary>

![sonarqube nlp quality gate](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/b87ce4b2-3fd6-4d0a-b817-b33283041378)
![sonarqube nlp findings](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/0e9d4bca-8754-437b-a6aa-404fe82e503b)
![sonarqube nlp duplications](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/c5d76b0f-05b9-4f43-908f-7554a17687cc)

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
