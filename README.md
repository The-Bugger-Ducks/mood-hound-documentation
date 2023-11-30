<span id="topo">

![mood hound header sprint 4](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/e4b4528c-9b28-4fe5-a5fe-9c8728dfad35)

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a>  &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#analise">Métricas de análise estática </a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

A sprint teve como atividade principal o desenvolvimento de autorizações e autenticações de usuários, assim como também realizar as melhorias que foram levantadas ao longo do fechamento da sprint passada. A "frente" nlp esteve focada em viabilizar o processamento de toda a base de dados disponibilizada, melhorar a qualidade do código desenvolvido e trazer logs e alertas de desempenho. As "frentes" backend e frontend tiveram seus desenvolvimentos com foco voltado à interface de demonstração do desempenho da aplicação a ser exibida na dashboard.

<br />

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:

- :heavy_check_mark: **RF 07:** Autenticação e Autorização
- :heavy_check_mark: **RNF 08:** Documentação no GitHub com mapeamento das entregas
- :heavy_check_mark: **RNF 09:** Utilização de Typescript e Python

<br />

<span id="entregas">
        
## 📲 Entregas
Para as entregas da sprint, tivemos os artefatos SCRUM validados, como Backlog do Produto, Backlog das Sprints, Épicos e User Stories, através de comunicação direta entre o P.O. e o cliente. Para observar esses artefatos, acesse [este link](https://github.com/The-Bugger-Ducks/mood-hound-documentation#backlogs).

Para extrair e entender os desejos do cliente, foi construído um protótipo inicial no Figma, criando a identidade visual e design do sistema e apresentando para validação com o cliente, onde o resultado deste protótipo foi traduzido para uma aplicação em React e com as devidas integrações das funcionalidades acordadas para esta sprint.

### RF 07: Autenticação e Autorização

Autenticação é o ato de verificar a veracidade de um usuário que realiza seu login na aplicação e autorização é a forma com a qual são realizadas as permissões de acesso aos usuários. Durante essa sprint foi realizada a separação de visualização dos usuários entre "Gestor" e "Operador" através de uma regra inserida no frontend, onde o "Gestor" pode realizar acessos a dashboard, busca e informações do sistema; já o "Operador" realiza apenas buscas. 

### RNF 08: Documentação no GitHub

Este requisito não funcional se trata da documentação criada e armazenada no GitHub (como este arquivo). Para visualizar os artefatos da sprint, como backlogs (do produto e da sprint) acesse a [documentação geral do projeto](https://github.com/The-Bugger-Ducks/mood-hound-documentation).

### RNF 09: Utilização de Typescript e Python

Este requisito não funcional se trata da utilização de Typescript e Python, que foi satisfeito ainda nesta sprint, dado que tanto no servidor, feito com Node, foi utilizado o Typescript quanto na aplicação web, feita com React. Python foi utilizado para as práticas de processamento de linguagem natural, em especial, com o uso das bibliotecas Pandas e NLTK.

→ [Voltar ao topo](#topo)

<br />

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Nesta sprint o time se dividiu entre frontend, backend e nlp, onde a "frente nlp" teve como foco a melhoria dos códigos, logs e alertas de desempenho e processamento da base de dados completa. A "frente backend" se ocupou com tarefas acerca dos retornos de informações a serem exibidas na aba de "sistema" da dashboard, assim como a "frente web" ficou pela demonstração em gráficos das informações obtidas pelo backend.  
- Abaixo se encontra o gráfico Burndown gerado pela equipe nesta sprint, onde o eixo X são os dias trabalhados e o eixo Y representa as entregas de cada dia:
    
<div align="center">

![burndown sprint 4](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/35f03c64-c803-4739-91d2-d339ab196f1b)

</div>

→ [Voltar ao topo](#topo)

<br />

<span id="analise">

## 🐞 Métricas de análise estática do código

<div align="center">

|               Modalidade                |                                                Repositório web                                                 |                                                Repositório back                                                |                                                Repositório nlp                                                 |
| :-------------------------------------: | :------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------: |
| Blocker, Critical, Major e Minor Issues |                                                       0                                                        |                                                       0                                                        |                                                       0                                                        |
|                  Bugs                   |                                                       0                                                        |                                                       0                                                        |                                                       0                                                        |
|               Code Smells               |                                                       0                                                        |                                                       0                                                        |                                                       0                                                        |
|             Vulnerabilities             |                                                       0                                                        |                                                       0                                                        |                                                       0                                                        |
|             Security Review             |                                                       0                                                        |                                                       0                                                        |                                                       0                                                        |
|          Duplicidade de Código          |                                                      0.0%                                                      |                                                      0.0%                                                      |                                                      0.0%                                                      |
|              Quality Gate               | <img src="https://img.shields.io/badge/Waiting-FFFFFF?style=for-the-badge&logoColor=white" alt="Waiting Badge"> | <img src="https://img.shields.io/badge/Waiting-FFFFFF?style=for-the-badge&logoColor=white" alt="Waiting Badge"> | <img src="https://img.shields.io/badge/Waiting-FFFFFF?style=for-the-badge&logoColor=white" alt="Waiting Badge"> |

</div>

**Estratégias de correção:** [inserir estratégias]

<details>
<summary>Imagem do resumo das análises do repositório web</summary>

[inserir imagem]

</details>

<details>
<summary>Imagem do resumo das análises do repositório backend</summary>

[inserir imagem]

</details>

<details>
<summary>Imagem do resumo das análises do repositório NLP</summary>

[inserir imagem]

</details>

→ [Voltar ao topo](#topo)

<span id="links">

<br/>
    
## :link: Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 4ª sprint:
  - Repositório da aplicação: [clique aqui para acessar "mood-hound-web"](https://github.com/The-Bugger-Ducks/mood-hound-web)
  - Repositório da API: [clique aqui para acessar "mood-hound-back"](https://github.com/The-Bugger-Ducks/mood-hound-back)
  - Repositório de PLN: [clique aqui para acessar "mood-hound-nlp"](https://github.com/The-Bugger-Ducks/mood-hound-nlp)

→ [Voltar ao topo](#topo)
