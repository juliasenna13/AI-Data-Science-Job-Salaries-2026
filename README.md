# AI & Data Science Job Salaries 2026

Dashboard interativa desenvolvida para análise exploratória de salários e características profissionais do mercado de Inteligência Artificial e Ciência de Dados, com foco em **Data Analytics, Business Intelligence e Data Visualization**.

O projeto transforma uma base de dados sobre profissionais da área em uma interface analítica que permite explorar **remuneração, experiência, modelo de trabalho, setor, localização, escolaridade e adoção de ferramentas de IA**.

> **Projeto de portfólio:** desenvolvido com finalidade educacional e prática para aplicação de conceitos de análise de dados, definição de KPIs, visualização de dados e desenvolvimento de dashboards.

---

## Dashboard
[![Preview da Dashboard IA Data Salaries](dashboard.png)](https://juliasenna13.github.io/AI-Data-Science-Job-Salaries-2026/)

---
## Sobre o projeto

A proposta foi partir de uma base com dados profissionais e salariais e desenvolver uma dashboard capaz de responder perguntas relevantes sobre o mercado de trabalho em Inteligência Artificial e Ciência de Dados.

Mais do que apresentar gráficos, o objetivo foi estruturar uma experiência de análise que permita comparar cargos, remuneração e níveis de experiência, além de explorar características como trabalho remoto, utilização de ferramentas de IA e satisfação profissional.

A base utilizada possui 5.000 registros e 27 campos.

---

## Objetivos

- Analisar a remuneração dos profissionais de IA e Ciência de Dados.
- Identificar quais cargos apresentam os maiores salários médios.
- Avaliar a relação entre experiência profissional e remuneração.
- Explorar a distribuição entre trabalho presencial, híbrido e remoto.
- Analisar a adoção de ferramentas de IA no ambiente profissional.
- Comparar características dos cargos para identificar oportunidades no mercado.
- Aplicar conceitos de Business Intelligence, Data Visualization e UX/UI.
- Desenvolver um projeto interativo para portfólio de Análise de Dados.

---

## Perguntas de negócio

A dashboard foi estruturada para apoiar principalmente as seguintes análises:

### 1. Quais cargos são mais valorizados?

O ranking por salário médio anual permite comparar os cargos da base e identificar quais funções apresentam maior remuneração média.

### 2. Onde está o trabalho remoto?

A distribuição por regime de trabalho permite visualizar a participação de profissionais presenciais, híbridos e 100% remotos.

### 3. Experiência realmente paga mais?

A comparação do salário médio por nível de experiência permite avaliar como a remuneração varia entre profissionais Júnior, Pleno, Sênior, Líder e Executivo.

### 4. Qual é a relação entre experiência e salário?

O gráfico de dispersão relaciona os anos de experiência com o salário anual em USD, permitindo observar padrões e diferenças de remuneração entre profissionais.

### 5. Como a adoção de IA se relaciona com a remuneração?

A dashboard compara o salário médio de profissionais que utilizam ferramentas de IA diariamente com aqueles que não utilizam diariamente.

### 6. Quais cargos apresentam oportunidades mais atrativas?

O Radar de Oportunidades combina informações de salário médio, uso diário de IA, satisfação profissional e trabalho remoto para facilitar a comparação entre cargos.

---

## KPIs

A dashboard apresenta seis indicadores principais:

| KPI | Objetivo |
|---|---|
|Salário médio anual|Apresentar a remuneração anual média em USD no recorte selecionado
|Salário mensal médio|Apresentar o equivalente mensal do salário médio anual, calculado pela divisão por 12
|100% remoto|Mostrar a participação de registros classificados como totalmente remotos
|Usam IA diariamente |Mostrar a participação de profissionais que utilizam ferramentas de IA diariamente
|Satisfação média|Apresentar a média do indicador de satisfação profissional disponível na base
|Medo de automação|Apresentar a média do indicador de receio em relação à automação por IA

Todos os indicadores são atualizados dinamicamente conforme os filtros selecionados.

---
## Recursos da dashboard

### Filtros

A dashboard permite segmentar a análise pelos seguintes campos:

- **Cargo**
- **Experiência**
- **Indústria**
- **País da empresa**
- **Modelo de trabalho**
- **Escolaridade**

As opções dos filtros são apresentadas em ordem alfabética e os dados categóricos exibidos na interface foram traduzidos para português quando aplicável.

---

## Visualizações

### Cargos mais valorizados

Ranking dos 8 cargos com maior salário médio anual.

### Distribuição do trabalho remoto

Composição entre trabalho presencial, híbrido e remoto.

### Salário por nível de experiência

Comparação do salário médio entre os diferentes níveis de experiência profissional.

### Experiência × salário

Gráfico de dispersão relacionando anos de experiência e salário anual em USD.

### IA no trabalho

Comparação do salário médio entre profissionais que utilizam IA diariamente e aqueles que não utilizam diariamente. A análise também apresenta a média de horas semanais de uso de ferramentas de IA e a média de horas mensais dedicadas ao desenvolvimento de novas habilidades.

### Radar de Oportunidades

Tabela comparativa dos cargos com maior salário médio, apresentando salário médio, uso diário de IA, satisfação média e percentual de profissionais 100% remotos.

### Leitura Executiva

Resumo dinâmico destacando cargo com maior salário médio, nível de experiência mais remunerado, adoção diária de IA e participação do trabalho 100% remoto.

---

## Insights dinâmicos

A dashboard destaca informações que se atualizam conforme os filtros selecionados, incluindo:

- cargo com maior salário médio;
- nível de experiência com maior remuneração média;
- participação do uso diário de ferramentas de IA;
- participação do trabalho totalmente remoto;
- comparação de oportunidades entre cargos.

---

## Preparação e qualidade dos dados

A estrutura do dataset foi verificada antes da definição das análises para garantir que os indicadores fossem compatíveis com os campos disponíveis.

A base utilizada possui:

- **5.000 registros**;
- **27 campos**;
- **12 cargos distintos**;
- **5 níveis de experiência**;
- **10 setores de atuação**;
- **nenhum valor nulo identificado**;
- **nenhuma linha totalmente duplicada identificada**.

O modelo de trabalho é representado pelo campo `remote_ratio`, com valores correspondentes a **0%, 50% e 100% de trabalho remoto**.

A remuneração utilizada nas análises é baseada no campo `salary_usd`, que representa o salário anual em dólares americanos.

---
## Uso de Inteligência Artificial no projeto

O ChatGPT foi utilizado como ferramenta de apoio durante o desenvolvimento, principalmente para:

- analisar a estrutura do dataset;
- estruturar e revisar perguntas de negócio;
- discutir KPIs compatíveis com os dados disponíveis;
- apoiar a construção e evolução do código HTML, CSS e JavaScript;
- implementar filtros e interatividade;
- revisar decisões de UX/UI;
- auxiliar na identificação de limitações analíticas da base;
- traduzir os dados categóricos exibidos na interface;
- iterar e aprimorar a dashboard;
- apoiar a documentação do projeto.

O uso de IA fez parte do processo como ferramenta de **assistência, experimentação e aprendizado**, e não como substituição da análise crítica dos dados.

---
## UX/UI

A identidade visual foi inspirada na estética tecnológica da imagem de referência utilizada durante o desenvolvimento do projeto.

A interface utiliza:

- fundo azul-marinho;
- tons de azul, ciano e roxo;
- alto contraste;
- cards de indicadores;
- elementos visuais com efeito neon discreto;
- hierarquia visual voltada à leitura rápida dos principais resultados;
- layout responsivo para diferentes tamanhos de tela.

A proposta visual busca combinar uma estética tecnológica com legibilidade e organização das informações.

## Fonte de dados
A base de dados utilizada neste projeto foi obtida no **Kaggle** e contém informações sobre filmes e séries disponíveis no catálogo da Netflix.

**Dataset:** AI & Data Science Job Salaries 2026 
**Fonte:** Kaggle  
**Autor:** Udit Jain
**Link:** [https://www.kaggle.com/datasets/uditjain13/ai-and-data-science-job-salaries-2026]

Os dados foram utilizados para fins educacionais, prática de análise de dados e desenvolvimento de portfólio.
---

## Tecnologias e ferramentas

### Desenvolvimento

- HTML5
- CSS3
- JavaScript

### Dados e análise

- CSV
- análise exploratória de dados
- definição de KPIs
- análise de salários e mercado de trabalho

### Conceitos aplicados

- Business Intelligence
- Data Analysis
- Data Visualization
- UX/UI para dashboards
- storytelling com dados
- análise de tendências e desempenho
- filtros e segmentação de dados

### Versionamento e publicação

- Git
- GitHub
- GitHub Pages

---

## Estrutura sugerida do repositório

```text
AI-Data-Science-Job-Salaries-2026/
│
├── ai_ds_job_salaries_2026.csv
├── Dashboard.png
├── index.html
└── README.md
```

---

## Como executar

### GitHub Pages

Pode ser acessada diretamente pelo navegador: https://juliasenna13.github.io/AI-Data-Science-Job-Salaries-2026/

### Localmente

1. Clone o repositório:

```bash
git clone https://github.com/juliasenna13/AI-Data-Science-Job-Salaries-2026.git
```

2. Entre na pasta do projeto:

```bash
cd AI-Data-Science-Job-Salaries-2026
```

3. Abra o arquivo:

```text
index.html
```

em um navegador.

---

## Dados utilizados

O dataset possui **5.000 registros** e **27 campos**.

Na verificação da base utilizada para a dashboard:

- não foram identificados valores nulos;
- não foram identificadas linhas totalmente duplicadas;
- existem 12 cargos distintos;
- existem 5 níveis de experiência;
- existem 10 setores de atuação;
- o modelo de trabalho é representado pelos valores 0%, 50% e 100% de trabalho remoto.

A remuneração utilizada nas análises é o campo **`salary_usd`**, que representa o salário anual convertido para dólares americanos.

---

## Principais aprendizados

O projeto permitiu aplicar um fluxo de análise orientado a perguntas de negócio:

**dados → análise → perguntas de negócio → KPIs → visualizações → interatividade → insights**

Durante o desenvolvimento foram praticados conceitos relacionados a:

- análise exploratória de dados;
- seleção de métricas relevantes;
- definição de KPIs;
- construção de rankings;
- análise de remuneração;
- análise de experiência profissional;
- segmentação por filtros;
- visualização de relações entre variáveis;
- desenvolvimento de dashboards interativos;
- organização da informação;
- UX/UI aplicada à visualização de dados;
- publicação de projetos no GitHub.

---

## Limitações e próximas melhorias

A dashboard apresenta uma análise descritiva e exploratória da base fornecida.

Como evolução do projeto, podem ser implementados:

- comparação salarial por país;
- análise por setor de atuação;
- análise de remuneração total considerando bônus e participação acionária;
- comparação entre tipo de contratação e salário;
- análise do impacto da escolaridade na remuneração;
- análise das linguagens de programação por cargo;
- indicadores de gestão de pessoas e tamanho das equipes;
- análise mais aprofundada da relação entre adoção de IA e remuneração;
- versão do projeto em Power BI;
- documentação detalhada da análise exploratória.

As relações apresentadas na dashboard devem ser interpretadas como **associações observadas no dataset**, e não como relações de causa e efeito.

---

## Autora

**Júlia Senna**

Projeto desenvolvido para estudo e construção de portfólio em **Análise de Dados e Business Intelligence**.

GitHub: https://github.com/juliasenna13
