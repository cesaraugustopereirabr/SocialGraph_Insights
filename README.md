# SocialGraph Insights

## Visão Geral

O **SocialGraph Insights** é um projeto de análise de redes sociais baseado em grafos, desenvolvido em Python, que tem como objetivo gerar **insights estratégicos sobre engajamento, influência, comunidades e fluxos de interação** entre usuários.

O projeto demonstra como técnicas de **Teoria dos Grafos**, **Ciência de Dados** e **Análise de Redes** podem ser aplicadas para transformar interações sociais em **informação estruturada e acionável**, com potencial aplicação acadêmica, institucional e de produto.

Todo o projeto é compatível com **Google Colab** e utiliza dados fictícios para fins de prototipação.

---

## Objetivos do Projeto

- Modelar redes sociais como grafos direcionados e ponderados
- Identificar usuários influentes, ativos e populares
- Detectar comunidades de interesse
- Analisar intensidade e tipo de interações
- Criar queries analíticas explicáveis
- Demonstrar viabilidade de um produto analítico baseado em grafos

---

## Estrutura do Grafo

### Nós (Nodes)
Representam usuários da rede social, com os seguintes atributos:
- `name`: nome do usuário
- `interest`: interesse principal (ex.: Tecnologia, Direito, IA)

### Arestas (Edges)
Representam interações entre usuários:
- Direcionadas (quem interage com quem)
- Ponderadas (intensidade da interação)
- Tipos de interação:
  - `like`
  - `comment`
  - `share`

Cada tipo de interação possui um peso distinto, refletindo seu impacto estrutural.

---

## Tecnologias Utilizadas

- Python 3
- pandas
- numpy
- networkx
- matplotlib
- python-louvain (detecção de comunidades)

Todas as bibliotecas são compatíveis com o ambiente padrão do Google Colab.

---

## Funcionalidades Implementadas

- Construção de grafos direcionados e ponderados
- Cálculo de métricas de centralidade:
  - Grau de entrada e saída
  - PageRank
  - Betweenness Centrality
- Detecção de comunidades com algoritmo de Louvain
- Identificação de usuários ponte entre comunidades
- Análise de engajamento por tipo de interação
- Análise de engajamento por interesse
- Classificação comportamental de usuários
- Rankings por comunidade
- Geração de KPIs globais da rede
- Visualização avançada do grafo com:
  - Comunidades
  - Tipos de interação
  - Intensidade das relações

---

## Exemplos de Perguntas Respondidas

- Quem são os usuários mais influentes da rede?
- Quem atua como ponte entre comunidades?
- Quais interações geram maior impacto?
- Quais interesses concentram maior engajamento?
- Quem deve ser priorizado para difundir informação em uma comunidade específica?

---

## Estrutura do Projeto

```text
socialgraph-insights/
│
├── notebook/
│   └── socialgraph_insights.ipynb
│
├── README.md
└── requirements.txt
