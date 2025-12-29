# Racional de Visualização de Dados  
## Global Sales Dashboard – Power BI

## Objetivo do Documento
Este documento descreve o racional por trás da escolha de cada tipo de visualização utilizada no dashboard **Global Sales Dashboard**, 
explicando como cada gráfico contribui para responder perguntas de negócio específicas, apoiar a tomada de decisão e garantir clareza na comunicação dos dados.

O foco está em alinhar **tipo de dado**, **pergunta analítica** e **visualização adequada**, seguindo boas práticas de Data Visualization aplicadas ao contexto de Business Intelligence.

---

## Princípios Adotados
As visualizações foram definidas com base nos seguintes princípios:

- Clareza na comunicação
- Adequação ao tipo de variável (categórica, numérica, geográfica)
- Leitura rápida para tomadores de decisão
- Evitar sobrecarga cognitiva
- Consistência visual e semântica

---

## 1. KPI – Total de Vendas

**Pergunta de Negócio:**  
Qual o valor total vendido?

**Tipo de Visualização:**  
Indicador (KPI)

**Justificativa:**  
KPIs são ideais para apresentar métricas-chave de alto nível, permitindo que gestores tenham uma visão imediata do desempenho geral do negócio. 
O valor total de vendas é uma métrica financeira central e, por isso, deve ocupar posição de destaque no dashboard.

**Vantagens:**
- Leitura imediata
- Comunicação direta do desempenho global
- Forte apelo executivo

**Limitações:**
- Não fornece contexto ou detalhamento
- Deve sempre ser acompanhado por visualizações complementares

---

## 2. Gráfico de Pizza – Número de Vendas por Categoria

**Pergunta de Negócio:**  
Quantas vendas foram realizadas por categoria de produto?

**Tipo de Visualização:**  
Gráfico de Pizza

**Justificativa:**  
O gráfico de pizza foi utilizado para representar a participação proporcional das categorias de produto no total de vendas. 
Essa escolha é adequada devido ao **baixo número de categorias**, o que evita poluição visual e facilita a leitura percentual.

**Vantagens:**
- Boa percepção de proporção
- Comunicação intuitiva para públicos não técnicos
- Adequado para poucas categorias

**Limitações:**
- Não escala bem com muitas categorias
- Comparações muito próximas podem ser menos precisas

**Observação:**  
Em cenários com maior granularidade, um gráfico de barras seria mais apropriado.

---

## 3. Gráfico de Barras Horizontais – Média de Desconto por Subcategoria

**Pergunta de Negócio:**  
Qual foi a média de desconto aplicada por subcategoria de produto?

**Tipo de Visualização:**  
Gráfico de Barras Horizontais

**Justificativa:**  
Gráficos de barras são ideais para comparar valores entre múltiplas categorias. A orientação horizontal melhora a legibilidade dos rótulos, especialmente quando há várias subcategorias.

**Vantagens:**
- Facilita comparações diretas
- Permite ordenação por valor
- Alta precisão visual

**Limitações:**
- Pode ocupar mais espaço no layout
- Requer cuidado com excesso de categorias

---

## 4. Mapa – Média de Vendas por País

**Pergunta de Negócio:**  
Quais países apresentaram maior média de valor de vendas?

**Tipo de Visualização:**  
Mapa com bolhas proporcionais

**Justificativa:**  
A visualização geográfica permite identificar padrões espaciais e regiões com maior relevância comercial. O uso de bolhas facilita a comparação relativa entre países, 
ampliando a capacidade dos tomadores de decisão em avaliar oportunidades e direcionar estratégias regionais.

**Vantagens:**
- Forte impacto visual
- Identificação rápida de padrões geográficos
- Boa ferramenta para análises exploratórias

**Limitações:**
- Não é ideal para comparações exatas
- Pode induzir interpretações subjetivas se usado isoladamente

**Observação:**  
O mapa deve ser interpretado como apoio visual e não como única fonte de análise quantitativa.

---

## 5. Gráfico de Barras Empilhadas – Número de Pedidos por País e Prioridade

**Pergunta de Negócio:**  
Quantas vendas foram realizadas por país considerando a prioridade de entrega?

**Tipo de Visualização:**  
Gráfico de Barras Empilhadas

**Justificativa:**  
Esse tipo de gráfico permite analisar simultaneamente o volume total de pedidos por país e a composição por prioridade de entrega, sendo especialmente útil para análises operacionais e logísticas.

**Vantagens:**
- Visualização conjunta de volume e composição
- Facilita comparações entre países
- Boa leitura de distribuição por prioridade

**Limitações:**
- Comparações internas entre segmentos empilhados podem ser menos precisas
- Requer bom contraste de cores

---

## 6. Filtros Interativos (Ano, Segmento e País)

**Objetivo:**  
Permitir análise dinâmica e segmentada dos dados.

**Justificativa:**  
Os filtros aumentam a flexibilidade do dashboard, permitindo que diferentes públicos explorem os dados conforme suas necessidades específicas, sem comprometer a estrutura principal da análise.

**Vantagens:**
- Maior interatividade
- Personalização da análise
- Apoio a múltiplos cenários de negócio

---

## Considerações Finais
As visualizações escolhidas foram definidas com base na relação entre **pergunta de negócio**, **tipo de dado** e **clareza visual**, priorizando usabilidade e suporte à tomada de decisão. 
O conjunto de gráficos foi pensado para oferecer tanto uma visão executiva quanto capacidade de exploração analítica, respeitando as limitações do dataset disponível.

Este racional reforça a importância de que visualizações não sejam escolhidas apenas por estética, mas por sua capacidade de comunicar informações de forma eficaz e orientada a negócio.
