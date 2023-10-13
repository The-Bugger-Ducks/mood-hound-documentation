<span id="topo">

![mood hound header sprint 2](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/e5188155-320e-4cd6-bf54-7fe80e95ac92)

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a>  &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#analise">Métricas de análise estática </a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

[inserir objetivo da sprint]

<br />

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:

- :heavy_check_mark: **RF 03:** Análise de sentimentos
- :heavy_check_mark: **RF 03:** Dashboard
- :heavy_check_mark: **RNF 08:** Documentação no GitHub com mapeamento das entregas
- :heavy_check_mark: **RNF 09:** Utilização de Typescript e Python

<br />

<span id="entregas">
        
## 📲 Entregas
Para as entregas da sprint, tivemos os artefatos SCRUM validados, como Backlog do Produto, Backlog das Sprints, Épicos e User Stories, através de comunicação direta entre o P.O. e o cliente. Para observar esses artefatos, acesse [este link](https://github.com/The-Bugger-Ducks/mood-hound-documentation#backlogs).

Para extrair e entender os desejos do cliente, foi construído um protótipo inicial no Figma, criando a identidade visual e design do sistema e apresentando para validação com o cliente, onde o resultado deste protótipo foi traduzido para uma aplicação em React e com as devidas integrações das funcionalidades acordadas para esta sprint.

### RF 03: Análise de sentimentos
    
A análise de sentimentos é um processo em que o texto dos comentários é analisado para determinar se o tom emocional da mensagem é positivo, negativo ou neutro. Para realizarmos essa análise, iniciamos os procedimentos com a separação das amostras das *reviews* feitas pelos clientes para o treinamento do modelo, em seguida foi efetuada a classificação manual das amostras para que o treinamento fosse realizado. Após a separação e a classificação, foi iniciada a criação do modelo de classificação (utilizando KNN) e o treinamento desse modelo para que fosse possível serem trazidas informações sobre acurácia, precisão e matriz de confusão; e então podemos integrar essa análise de sentimentos na pipeline responsável pela captação dos resultados entregues para o sistema.

### RF 04: Dashboard

[inserir descrição da atividade]

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

[inserir gráfico do burndown]

<!-- <img src="https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/97e96bb5-aa59-497a-b439-f3e045dab9f5" alt="Gráfico Burndown" /> -->

</div>

→ [Voltar ao topo](#topo)

<br />

<span id="analise">

## 🐞 Métricas de análise estática do código

<div align="center">

|               Modalidade                |                                                Repositório web                                                |                                               Repositório back                                                |                                                Repositório nlp                                                |
| :-------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------: |
| Blocker, Critical, Major e Minor Issues |                                                       -                                                       |                                                       -                                                       |                                                       -                                                       |
|                  Bugs                   |                                                       -                                                       |                                                       -                                                       |                                                       -                                                       |
|               Code Smells               |                                                       -                                                       |                                                       -                                                       |                                                       -                                                       |
|             Vulnerabilities             |                                                       -                                                       |                                                       -                                                       |                                                       -                                                       |
|             Security Review             |                                                       -                                                       |                                                       -                                                       |                                                       -                                                       |
|          Duplicidade de Código          |                                                     -.-%                                                      |                                                     -.-%                                                      |                                                     -.-%                                                      |
|              Quality Gate               | <img src="https://img.shields.io/badge/Waiting-000000?style=for-the-badge&logoColor=white" alt="Passed Badge"> | <img src="https://img.shields.io/badge/Waiting-000000?style=for-the-badge&logoColor=white" alt="Failed Badge"> | <img src="https://img.shields.io/badge/Waiting-000000?style=for-the-badge&logoColor=white" alt="Passed Badge"> |

</div>

**Estratégias de correção:** [inserir estratégias]

<details>
<summary>Imagens do resumo das análises do repositório web</summary>

[inserir imagens]

<!-- ![sonarqube web quality gate](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/13a57cbd-7d9d-48f6-979c-91de96ad56a5)
![sonarqube web findings](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/1e18698d-c683-4471-9e18-327012e3555a)
![sonarqube web duplications](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/b23f5a1c-9a62-4484-9049-5eac8fb26ebb) -->

</details>

<details>
<summary>Imagens do resumo das análises do repositório backend</summary>

[inserir imagens]

<!-- ![sonarqube back quality gate](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/aa986733-34d5-426d-b226-3124f71a9669)
![sonarqube back findings](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/c901297b-d013-4bc7-a174-c1959556de14)
![sonarqube back duplications](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/170f0a75-a40d-4b00-bb8d-96fa28fca891) -->

</details>

<details>
<summary>Imagens do resumo das análises do repositório NLP</summary>

[inserir imagens]

<!-- ![sonarqube nlp quality gate](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/b87ce4b2-3fd6-4d0a-b817-b33283041378)
![sonarqube nlp findings](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/0e9d4bca-8754-437b-a6aa-404fe82e503b)
![sonarqube nlp duplications](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/c5d76b0f-05b9-4f43-908f-7554a17687cc) -->

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
