# Projeto de Ciência de Dados — Minicurso de Visualização de Dados

Projeto desenvolvido para a disciplina de Ciência de Dados da Universidade de Fortaleza (UNIFOR), com foco na criação de um minicurso educacional sobre Visualização de Dados utilizando Python, Matplotlib e Seaborn.

---

## 📚 Sobre o Projeto

Este projeto tem como objetivo desenvolver um minicurso introdutório e prático sobre **Visualização de Dados**, abordando desde fundamentos teóricos até a construção de gráficos avançados utilizando Python no Google Colab.

O curso foi pensado para pessoas com pouco ou nenhum contato prévio com programação ou análise de dados, utilizando:

* Explicações passo a passo
* Exemplos visuais
* Notebooks práticos
* Exercícios aplicados
* Storytelling com dados

---

## 👥 Integrantes

| Nome                 | Responsabilidades                                                                          |
| -------------------- | ------------------------------------------------------------------------------------------ |
| Lucas Diniz Frota    | Gravação das aulas e desenvolvimento de conteúdos práticos                                 |
| Cauã Moreira         | Gravação das aulas e desenvolvimento de conteúdos práticos                                 |
| João Guilherme Braga | Elaboração de material de apoio, organização de conteúdos complementares e suporte teórico |
| Lucas Rangel         | Elaboração de material de apoio, organização de conteúdos complementares e suporte teórico |
| Fernanda Ortega      | Edição dos vídeos, organização das playlists e padronização                                |

---

## 🎯 Objetivos do Minicurso

O minicurso busca ensinar:

* Fundamentos de visualização de dados
* Percepção visual humana
* Atributos pré-atentivos
* Tipos de dados e escalas
* Criação de gráficos com Matplotlib e Seaborn
* Storytelling visual
* Comunicação clara e honesta com dados

Ao final, os participantes serão capazes de:

* Escolher gráficos adequados
* Construir visualizações claras
* Interpretar dados visualmente
* Comunicar insights de forma objetiva

---

## 🛠 Tecnologias Utilizadas

* Python
* Google Colab
* Pandas
* Matplotlib
* Seaborn
* Google Drive
* Ferramentas de edição de vídeo

---

# 📖 Estrutura do Curso

---

# 📦 Módulo 1 — Fundamentos e Percepção Visual

## Objetivo

Apresentar os fundamentos essenciais da visualização de dados, explorando percepção visual, atributos pré-atentivos e escolha adequada de gráficos.

---

## Aula 1 — A Ciência por Trás do Data Viz

### Conteúdos

* Por que visualizar dados
* Comparação entre tabela e gráfico
* Quarteto de Anscombe
* Estatística descritiva vs padrões visuais
* Ciclo de vida de uma visualização
* Dados brutos, limpeza, análise e comunicação

---

## Aula 2 — Atributos Pré-atentivos

### Conteúdos

* Conceito de atributos pré-atentivos
* Processamento visual automático e consciente
* Uso de:

  * Cor
  * Tamanho
  * Forma
  * Orientação
* Hierarquia de Cleveland e McGill
* Destaque visual de anomalias

---

## Aula 3 — Tipos de Dados e Escalas

### Conteúdos

* Dados nominais
* Dados ordinais
* Dados de intervalo
* Dados de razão
* Escolha correta de gráficos
* Escalas enganosas
* Eixo Y sem zero
* Escalas logarítmicas
* Dados exponenciais

---

# 📦 Módulo 2 — Visualização com Matplotlib

## Objetivo

Introduzir a construção de gráficos utilizando Matplotlib.

---

## Aula 1 — Pyplot Implícito e Orientação a Objetos

### Conteúdos

* Introdução ao Matplotlib
* `matplotlib.pyplot`
* `plt.plot()`
* Diferença entre abordagem implícita e explícita
* `plt.subplots()`
* Manipulação de eixos com `ax.plot()`

---

## Aula 2 — Grades Simples com `subplots()`

### Conteúdos

* Organização de múltiplos gráficos
* Grades 2x2
* Uso de `fig` e `axes`
* Iteração sobre eixos
* Personalização visual
* Comparação de gráficos

---

## Aula 3 — Layouts Assimétricos com GridSpec

### Conteúdos

* `matplotlib.gridspec`
* Diferença entre `subplots()` e `GridSpec`
* Layouts assimétricos
* Dashboards
* Organização espacial de gráficos

---

# 📦 Módulo 3 — Os 5 Gráficos Essenciais

## Objetivo

Ensinar os principais tipos de gráficos utilizados em análise de dados.

---

## Aula 1 — Gráfico de Barras

### Conteúdos

* Comparação entre categorias
* Rankings
* Ordenação de barras
* `sns.barplot()`
* Cuidados com eixo Y

---

## Aula 2 — Gráfico de Pizza

### Conteúdos

* Partes do todo
* `plt.pie()`
* Proporções
* Limitações do gráfico de pizza
* Comparação com gráfico de barras

---

## Aula 3 — Histograma

### Conteúdos

* Distribuição de dados
* Frequência
* `sns.histplot()`
* Número de bins
* Análise exploratória

---

## Aula 4 — Boxplot

### Conteúdos

* Mediana
* Quartis
* IQR
* Outliers
* `sns.boxplot()`
* Comparação entre grupos

---

## Aula 5 — Gráfico de Violino

### Conteúdos

* Distribuição completa
* `sns.violinplot()`
* Concentração e dispersão
* Comparação com boxplot

---

# 📦 Módulo 4 — Visualizações Avançadas com Matplotlib e Seaborn

## Objetivo

Explorar gráficos avançados e técnicas de análise visual.

---

## Aula 1 — Dispersão, Alpha e Hexbin

### Conteúdos

* Scatter plot
* Transparência (`alpha`)
* Sobreposição de pontos
* Hexbin
* Densidade visual

---

## Aula 2 — Regressão Visual com Regplot e Lmplot

### Conteúdos

* `sns.regplot()`
* Linha de tendência
* Intervalo de confiança
* `ci=None`
* `sns.lmplot()`
* Separação por categorias

---

## Aula 3 — Séries Temporais

### Conteúdos

* Gráficos de linha
* Datas com `pd.to_datetime()`
* Ordenação temporal
* `sns.lineplot()`
* Tendências temporais

---

## Aula 4 — Escalas e Distorções Visuais

### Conteúdos

* Manipulação de eixo Y
* `set_ylim()`
* Escalas honestas
* Distorções visuais
* Comunicação ética

---

## Aula 5 — FacetGrid e Comparação por Grupos

### Conteúdos

* `sns.FacetGrid()`
* Pequenos múltiplos
* Comparação entre regiões
* `fill_between()`
* Visualizações segmentadas

---

# 📦 Módulo 5 — Boas Práticas e Storytelling Visual

## Objetivo

Transformar gráficos em comunicações visuais claras, limpas e eficientes.

---

## Aula 1 — Gráfico Poluído vs Gráfico Limpo

### Conteúdos

* Excesso de informação
* Remoção de elementos desnecessários
* Destaque seletivo
* Clareza visual

---

## Aula 2 — Títulos, Rótulos e Anotações

### Conteúdos

* Títulos analíticos
* Rótulos descritivos
* `annotate()`
* Narrativa visual

---

## Aula 3 — Uso Estratégico de Cores

### Conteúdos

* Cores com significado
* Positivo vs negativo
* Linha de referência
* Barras horizontais

---

## Aula 4 — Escalas Proporcionais e Honestidade Visual

### Conteúdos

* Escalas proporcionais
* Escalas enganosas
* Transparência visual
* Comparação percentual

---

## Aula 5 — Adaptação para Apresentações

### Conteúdos

* Gráficos para slides
* Hierarquia visual
* Destaques
* Limpeza visual
* Comunicação executiva

---

# 📂 Materiais do Curso

## 📘 Repositório

[GitHub do Projeto](https://github.com/GuilhermeBrga/curso_cienciaDeDados?utm_source=chatgpt.com)

---

## 🎥 Vídeos das Aulas

[Google Drive das Aulas](https://drive.google.com/drive/folders/1Y0Bo2Q7h1-eYGNNbk7u4mGfXhJZm_rW9?usp=drive_link&utm_source=chatgpt.com)

---

# 🚀 Formato de Entrega

Cada módulo será disponibilizado em formato de playlist contendo:

* Videoaulas
* Materiais complementares
* Notebooks práticos
* Exemplos utilizados nas demonstrações

---

# ✅ Considerações Finais

A visualização de dados é uma das habilidades mais importantes dentro da Ciência de Dados. Este minicurso busca unir teoria, prática e comunicação visual para capacitar os participantes a:

* Interpretar dados com clareza
* Construir gráficos eficientes
* Comunicar insights corretamente
* Desenvolver pensamento analítico visual

---

## 📌 Universidade

**Universidade de Fortaleza — UNIFOR**
Disciplina: Ciência de Dados
