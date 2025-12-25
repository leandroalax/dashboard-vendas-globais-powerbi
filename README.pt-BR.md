# Dashboard Comercial – Vendas Globais (Power BI)

## Contexto de Negócio
Este projeto apresenta um dashboard analítico desenvolvido no Microsoft Power BI com o objetivo de analisar o **desempenho de vendas globais**, apoiando a tomada de decisão relacionada a faturamento, categorias de produtos, descontos e distribuição geográfica.

O dashboard foi desenvolvido como parte do curso *Microsoft Power BI para Business Intelligence e Data Science* da Data Science Academy, seguindo uma abordagem analítica orientada a negócio.

---

## Perguntas de Negócio Respondidas
O dashboard foi projetado para responder às seguintes perguntas estratégicas:

1. Qual o valor total vendido?
2. Quantas vendas foram realizadas por categoria de produto?
3. Quantas vendas foram realizadas por país considerando a prioridade de entrega?
4. Qual foi a média de desconto aplicada por subcategoria de produto?
5. Quais países apresentaram maior média de valor de vendas? (visualização geográfica)

Além disso, o usuário pode filtrar os dados dinamicamente por:
- Ano
- Segmento
- País

---

## Visão Geral do Dataset
- Fonte: Dataset fornecido pela Data Science Academy (uso educacional)
- Formato: CSV
- Total de registros: 51.290
- Qualidade dos dados: Não há valores nulos ou em branco

### Features Disponíveis
- ID_Pedido  
- Data_Pedido  
- ID_Cliente  
- Segmento  
- Região  
- País  
- ID_Produto  
- Categoria  
- SubCategoria  
- Total_Vendas  
- Quantidade  
- Desconto  
- Lucro  
- Prioridade de Entrega  

---

## Destaques do Dashboard
- **Indicador de Vendas Totais (KPI)** para visão executiva
- **Distribuição de vendas por categoria de produto**
- **Análise de volume de pedidos por país e prioridade**
- **Análise da média de desconto por subcategoria**
- **Mapa geográfico** com destaque para países com maior média de vendas

---

## Limitações dos Dados
Apesar de adequado para fins analíticos e educacionais, o dataset apresenta algumas limitações quando comparado a dados corporativos reais:
- Ausência de valores nulos
- Padronização elevada das categorias
- Ausência de outliers extremos
- Estrutura já preparada para análise

Esses pontos foram considerados ao longo da análise.

---

## Ferramentas Utilizadas
- Microsoft Power BI
- Power Query
- Dataset em formato CSV

---

## Autor
**Leandro Álax**  
Analista de Dados | Business Intelligence  
