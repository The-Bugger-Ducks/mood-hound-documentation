<span id="topo">

![mood hound header sprint 3](https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/6b59b4fd-d5d9-4d6b-ab09-f90791c75c2e)

<p align="center">
    <a href="#objetivos">Objetivos da sprint</a>  &nbsp |&nbsp &nbsp
    <a href="#entregas">Entregas</a> &nbsp |&nbsp &nbsp
    <a href="#metricas">Métricas do time</a> &nbsp |&nbsp &nbsp
    <a href="#analise">Métricas de análise estática </a> &nbsp |&nbsp &nbsp
    <a href="#links">Links úteis</a>
</p>

Essa sprint apesar de ter apenas um épico como seu foco principal de desenvolvimento, teve também (mediante feedbacks dos clientes e análises de melhorias) seu foco dividido entre a melhoria da análise de sentimentos e refazer o frontend da nossa aplicação. As “frentes” backend e frontend se dispuseram novamente a trabalhar com a apresentação das informações em gráficos dinâmicos de acordo com os dados processados, trazendo novos gráficos sobre dados dos clientes também.  A “frente” nlp trabalhou com a modificação do modelo que previamente estava sendo utilizado para um novo, disponibilizando mais assertividade vinda dos dados disponibilizados pelo processamento de linguagem natural, trazendo também métricas que demonstram o monitoramento do desempenho do código executado.

<br />

<span id="objetivos">
    
## :dart: Objetivos da Sprint
Os requisitos (tanto do cliente como da instituição de ensino) abrangidos por essa sprint são:

- :heavy_check_mark: **RF 11:** Monitoramento de desempenho
- :heavy_check_mark: **RNF 08:** Documentação no GitHub com mapeamento das entregas
- :heavy_check_mark: **RNF 09:** Utilização de Typescript e Python

<br />

<span id="entregas">
        
## 📲 Entregas
Para as entregas da sprint, tivemos os artefatos SCRUM validados, como Backlog do Produto, Backlog das Sprints, Épicos e User Stories, através de comunicação direta entre o P.O. e o cliente. Para observar esses artefatos, acesse [este link](https://github.com/The-Bugger-Ducks/mood-hound-documentation#backlogs).

### RF 11: Monitoramento de desempenho

O requisito de monitoramento de desempenho diz respeito à mensuração do desempenho da atividade da aplicação na realização de suas estratégias e na obtenção dos resultados planejados. Para ser feito esse monitoramento foi realizado uma análise de métricas, onde foi realizada uma conversão das colunas de uma matriz de confusão e sua junção em um objeto com a acurácia e a precisão. Nesse mesmo objeto foi adicionado o tempo de execução da pipeline utilizando a nova lib com uma função para atualizar a colection no banco de dados. 

### RNF 08: Documentação no GitHub

Este requisito não funcional se trata da documentação criada e armazenada no GitHub (como este arquivo). Para visualizar os artefatos da sprint, como backlogs (do produto e da sprint) acesse a [documentação geral do projeto](https://github.com/The-Bugger-Ducks/mood-hound-documentation).

### RNF 09: Utilização de Typescript e Python

Este requisito não funcional se trata da utilização de Typescript e Python, que foi satisfeito ainda nesta sprint, dado que tanto no servidor, feito com Node, foi utilizado o Typescript quanto na aplicação web, feita com React. Python foi utilizado para as práticas de processamento de linguagem natural, em especial, com o uso das bibliotecas Pandas e NLTK.

→ [Voltar ao topo](#topo)

<br />

<span id="metricas">
    
## :chart_with_upwards_trend: Métricas do time
Nessa sprint o time se dividiu entre frontend, backend e nlp, onde a "frente nlp" teve como foco o início da aplicação da análise de sentimentos nos dados disponibilizados utilizando um novo modelo e monitoramento do desempenho. Enquanto isso, as “frentes” backend e frontend se prontificaram a refazer o desenvolvimento da dashboard com diversos gráficos mais intuitivos e filtragens.
- Abaixo se encontra o gráfico Burndown gerado pela equipe nesta sprint, onde o eixo X são os dias trabalhados e o eixo Y representa as entregas de cada dia:
    
<div align="center">
    
<img width="353" alt="mood hound sprint 3 burndown" src="https://github.com/The-Bugger-Ducks/mood-hound-documentation/assets/79321198/fabe4784-e9d4-42f9-9677-c1dd1817a435">

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
|               Code Smells               |                                                       0                                                       |                                                       0                                                       |                                                       0                                                       |
|             Vulnerabilities             |                                                       0                                                       |                                                       0                                                       |                                                       0                                                       |
|             Security Review             |                                                       0                                                       |                                                       0                                                       |                                                       0                                                       |
|          Duplicidade de Código          |                                                     0.0%                                                      |                                                     0.0%                                                      |                                                     0.0%                                                      |
|              Quality Gate               | <img src="https://img.shields.io/badge/Waiting-FFFFFF?style=for-the-badge&logoColor=white" alt="Waiting Badge"> | <img src="https://img.shields.io/badge/Waiting-FFFFFF?style=for-the-badge&logoColor=white" alt="Waiting Badge"> | <img src="https://img.shields.io/badge/Waiting-FFFFFF?style=for-the-badge&logoColor=white" alt="Waiting Badge"> |

</div>

**Estratégias de correção:** [inserir estratégias de correção]

<details>
<summary>Imagem do resumo das análises do repositório web</summary>

[inserir imagens]

</details>

<details>
<summary>Imagem do resumo das análises do repositório backend</summary>

[inserir imagens]

</details>

<details>
<summary>Imagem do resumo das análises do repositório NLP</summary>

[inserir imagens]

</details>

→ [Voltar ao topo](#topo)

<span id="links">

<br/>
    
## :link: Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 3ª sprint:
  - Repositório da aplicação: [clique aqui para acessar "mood-hound-web"](https://github.com/The-Bugger-Ducks/mood-hound-web)
  - Repositório da API: [clique aqui para acessar "mood-hound-back"](https://github.com/The-Bugger-Ducks/mood-hound-back)
  - Repositório de PLN: [clique aqui para acessar "mood-hound-nlp"](https://github.com/The-Bugger-Ducks/mood-hound-nlp)

→ [Voltar ao topo](#topo)
