# Olá, eu sou o Luiz 👋

Engenheiro de Produção em transição para dados.
Uso 10 anos de operação como vantagem — não como bagagem.

---

## O que eu faço

Construo análises orientadas a decisão — não apenas exploratórias.
O foco está em transformar dados em recomendações concretas, rastreáveis por evidência.

Cada projeto simula um problema real de negócio com um cliente fictício,
uma pergunta central e um veredito estruturado.

**A análise é o meio. A decisão é o fim.**

---

## Projetos

### 🔍 Fictus — Data-Driven M&A Simulation
> Due diligence de aquisição de e-commerce baseada em dados reais | Python

Simulei um processo completo de aquisição de empresa, integrando três frentes analíticas independentes — Vendas, Logística e Finanças — em um Veredito Estratégico gerado por IA a partir dos dados calculados.

**Pergunta central:** essa empresa deve ser adquirida — ou não?

| Frente | Score | Diagnóstico |
|---|---|---|
| Vendas | 3.0 / 3 | ✅ Motor de receita robusto |
| Logística | 2.0 / 3 | ⚠️ Modelo próximo do limite de escala |
| Financeiro | 2.2 / 3 | ⚠️ Pressão crescente sobre capital de giro |

**Decisão:** aquisição viável — condicionada a intervenção operacional e financeira.

🔗 [Ver projeto completo](https://github.com/DataLufi/fictus)

---

### 🏆 WorldCup2026 — Previsão de Resultados em Tempo Real
> Pipeline preditivo para a Copa do Mundo FIFA 2026 | Python · Streamlit · GitHub Actions

**Status: Projeto encerrado — Maio/2026**

O projeto foi descontinuado por decisão estratégica de cronograma: múltiplos problemas de autenticação e rate limit nas APIs de dados de futebol tornaram o pipeline instável dentro do tempo disponível. Os objetivos técnicos deste projeto — Streamlit público, GitHub Actions e modelo preditivo com dado real — foram consolidados no projeto Prisma, que já tinha essas camadas em desenvolvimento ativo.

>**Repositório mantido como registro público de decisão técnica.**
>**Pergunta central:** quem vai ganhar — e o que os dados dizem sobre isso?
>**Progresso atual:** dataset de 48 seleções com índice de força validado → modelo preditivo de Poisson implementado → dashboard Streamlit em construção

**Stack:** coleta via API → modelo de Poisson + Monte Carlo → Streamlit Cloud → GitHub Actions para atualização automática

🔗 [Ver projeto completo](https://github.com/DataLufi/worldcup2026)

---

### 🔬 Prisma — Investigação de Erosão de Margem
> Diagnóstico de profit leaks em varejo premium omnichannel | Python · SQL · PostgreSQL · Power BI

A ÍconeLab crescia em receita. A margem encolhia. O board não sabia onde estava o vazamento.
A Lufi Data Consulting foi contratada para descobrir — e encontrou 7 profit leaks estruturais invisíveis no faturamento bruto.

**Pergunta central:** onde está destruindo margem sem que ninguém perceba?

**Progresso atual:** dataset sintético gerado e validado em Python (120k pedidos, 9 tabelas) → banco PostgreSQL estruturado com schema e constraints → análise SQL em andamento

**Stack completa:** Python → PostgreSQL → Power BI (5 páginas)

🔗 [Acompanhar desenvolvimento](https://github.com/DataLufi/prisma)

---

### 🫀 Pulso — Sistema de Alerta de Risco em Saúde Suplementar
> Monitoramento de risco financeiro e reputacional de operadoras | BigQuery · dbt · Python · Power BI · Streamlit
> 🚧 Em desenvolvimento — início: Jul/2026

Em 2022, mais de 60 operadoras de saúde suplementar colapsaram. Os sinais estavam nos dados — 12 meses antes.
A Lufi Data Consulting foi contratada pela Meridian RH Consultoria para construir o que não existia: um modelo de alerta precoce mensal que antecipa deterioração antes que o regulador precise agir.

**Pergunta central:** a operadora que cuida dos seus funcionários vai existir daqui a dois anos?

**Stack:** FTP da ANS → BigQuery (raw/staging/marts) → dbt Core → Score Pulso (scikit-learn) → Power BI + Streamlit Cloud → GitHub Actions

🔗 [Ver repositório](https://github.com/DataLufi/pulso)

---

## Stack

### Análise & Dados
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

### Visualização
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)

### Banco de Dados & Engenharia
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat&logo=googlebigquery&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/filholuiz)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/DataLufi)
