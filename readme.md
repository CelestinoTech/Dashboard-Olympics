# 🏅 Olympic Analytics — Dashboard Power BI

## 📌 Visão Geral

O projeto **Olympic Analytics** é um dashboard analítico desenvolvido no Power BI com foco na exploração histórica dos Jogos Olímpicos modernos.

O objetivo principal é transformar dados históricos olímpicos em informações estratégicas, visuais e interativas, permitindo análises sobre:

* desempenho de países
* evolução das Olimpíadas
* atletas históricos
* modalidades esportivas
* distribuição de medalhas
* participação feminina
* cidades-sede
* tendências históricas

O dashboard foi construído utilizando técnicas modernas de:

* Business Intelligence (BI)
* Data Visualization
* Data Storytelling
* Modelagem Dimensional
* DAX
* Power Query

---

# 🎯 Objetivos do Projeto

* Construir um dashboard profissional e interativo no Power BI
* Aplicar conceitos de modelagem de dados
* Criar visualizações estratégicas e executivas
* Desenvolver métricas analíticas relevantes
* Gerar insights históricos sobre os Jogos Olímpicos
* Trabalhar com tratamento e transformação de dados reais

---

# 📊 Dataset Utilizado

## Dataset Principal

Olympic Athletes Historical Dataset

### Informações do Dataset

* Mais de 270 mil registros
* Dados históricos dos Jogos Olímpicos
* Cobertura de 1896 até 2016/2020
* Summer Olympics e Winter Olympics
* Dados de atletas, países, esportes e medalhas

---

# 🧱 Estrutura dos Dados

Cada linha do dataset representa:

> Um atleta participando de um evento olímpico específico.

---

# 📁 Colunas Disponíveis

| Coluna | Descrição               |
| ------ | ----------------------- |
| ID     | Identificador do atleta |
| Name   | Nome do atleta          |
| Gender | Gênero                  |
| Age    | Idade                   |
| Height | Altura                  |
| Weight | Peso                    |
| Team   | País/Equipe             |
| NOC    | Código Olímpico do país |
| Games  | Nome da edição olímpica |
| Year   | Ano                     |
| Season | Summer ou Winter        |
| City   | Cidade-sede             |
| Sport  | Modalidade esportiva    |
| Event  | Evento esportivo        |
| Medal  | Medalha conquistada     |

---

# 🧹 Tratamento de Dados

O projeto utiliza Power Query para:

* limpeza de dados
* tradução de colunas
* substituição de valores
* tratamento de nulos
* padronização
* filtragem de registros
* transformação de tipos de dados

---

# 🌎 Traduções Aplicadas

| Inglês | Português |
| ------ | --------- |
| Name   | Atleta    |
| Gender | Gênero    |
| Age    | Idade     |
| Height | Altura    |
| Weight | Peso      |
| Team   | País      |
| Games  | Jogos     |
| Year   | Ano       |
| Season | Temporada |
| City   | Cidade    |
| Sport  | Esporte   |
| Event  | Evento    |
| Medal  | Medalha   |

---

# 🔧 Tratamentos Importantes

## Medalhas Nulas

Valores nulos na coluna Medal foram tratados como:

```text
Sem Medalha
```

---

## Filtro Principal

O dashboard utiliza prioritariamente:

```text
Summer Olympics
```

para manter:

* consistência visual
* clareza analítica
* melhor storytelling

---

# ⭐ Modelagem de Dados

O projeto utiliza modelo dimensional do tipo:

## Star Schema (Modelo Estrela)

### Tabela Fato

* Participações Olímpicas

### Dimensões

* Atletas
* Países
* Esportes
* Tempo
* Medalhas
* Cidades

---

# 📈 Funcionalidades do Dashboard

## ✅ Página Overview

Visão executiva geral das Olimpíadas.

### Recursos:

* KPIs
* mapa mundial
* evolução histórica
* ranking de países
* filtros globais

---

## ✅ Página Países

Análise de desempenho entre nações.

### Recursos:

* ranking histórico
* medalhas por país
* comparação entre países
* participação olímpica
* evolução temporal

---

## ✅ Página Atletas

Exploração individual dos atletas.

### Recursos:

* atletas mais medalhistas
* distribuição de idade
* gênero
* esportes praticados
* participação histórica

---

## ✅ Página Modalidades

Análise esportiva das Olimpíadas.

### Recursos:

* esportes mais populares
* eventos olímpicos
* distribuição de medalhas
* crescimento das modalidades

---

## ✅ Página História Olímpica

Evolução histórica das Olimpíadas.

### Recursos:

* cidades-sede
* linha do tempo
* evolução de participação
* expansão olímpica

---

# 📊 Indicadores (KPIs)

O dashboard possui indicadores estratégicos como:

* Total de atletas
* Total de países
* Total de esportes
* Total de medalhas
* Medalhas de ouro
* Participações olímpicas
* País líder histórico
* Crescimento da participação feminina

---

# 📉 Visualizações Utilizadas

| Visual       | Objetivo                |
| ------------ | ----------------------- |
| Cards KPI    | métricas rápidas        |
| Bar Chart    | rankings                |
| Line Chart   | evolução temporal       |
| Map          | distribuição geográfica |
| Treemap      | modalidades             |
| Donut Chart  | proporções              |
| Matrix       | análise detalhada       |
| Scatter Plot | correlações             |
| Slicers      | filtros interativos     |

---

# 🎨 Design e UX

O dashboard segue princípios modernos de UI/UX:

* layout limpo
* design minimalista
* hierarquia visual
* cores padronizadas
* navegação intuitiva
* experiência responsiva

---

# 🧠 Insights Possíveis

O dashboard permite responder perguntas como:

* Quais países dominaram historicamente as Olimpíadas?
* Qual esporte possui mais medalhas?
* A participação feminina aumentou ao longo do tempo?
* Quais cidades mais sediaram os jogos?
* Existe relação entre participação e quantidade de medalhas?
* Quais atletas possuem mais conquistas?

---

# ⚡ Recursos Avançados

## Implementados ou planejados:

* Drillthrough
* Tooltips customizados
* Bookmarks
* Navegação entre páginas
* Interatividade avançada
* Medidas DAX
* Segmentações dinâmicas

---

# 🧮 Medidas DAX Planejadas

* Total Medalhas
* Total Ouro
* Ranking País
* Medalhas por Esporte
* Participação Feminina %
* Crescimento Histórico
* Medalhas por Ano
* Total Atletas
* País Líder

---

# 🛠️ Tecnologias Utilizadas

| Ferramenta  | Uso              |
| ----------- | ---------------- |
| Power BI    | Dashboard        |
| Power Query | ETL              |
| DAX         | Métricas         |
| Excel/CSV   | Fonte de dados   |
| Figma       | Protótipo visual |

---

# 📌 Diferenciais do Projeto

* Dataset histórico real
* Grande volume de dados
* Dashboard interativo
* Storytelling analítico
* Visual profissional
* Estrutura corporativa
* Aplicação de BI moderno

---

# 🚀 Objetivo Acadêmico

Este projeto foi desenvolvido com foco educacional e profissional, visando aplicar conceitos de:

* Business Intelligence
* Data Analytics
* Visualização de Dados
* UX para dashboards
* Análise histórica esportiva

---

# 👥 Equipe

Projeto desenvolvido em dupla para a disciplina de Business Intelligence / Power BI.

---

# 🏁 Resultado Esperado

Um dashboard profissional capaz de:

* apresentar dados históricos olímpicos
* gerar insights relevantes
* facilitar análises estratégicas
* demonstrar domínio técnico em Power BI

---
