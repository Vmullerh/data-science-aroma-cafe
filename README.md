# 📊 Análise de Dados | Estudo de caso da empresa Aroma Café

Este projeto apresenta uma análise de ponta a ponta da rede de cafeterias Aroma Café. O objetivo principal é diadnosticar as flutuações no faturamento e fazer recomendações baseadas em dados para fortalecer o crescimento da empresa, respondendo as seguintes perguntas de negócio:

- **Como está a saúde da rede de cafeterias, no geral?**
- **Existe algum motivo do porquê a rede está indo bem ou mal?**
- **Você poderia prever o faturamento da rede de cafeteria nos próximos 30 dias?**
- **Quais são as suas recomendações para alavancar ainda mais o negócio?**

# 📌 Metodologia
A análise está estruturada em quatro pontos chave:

- **Análise Descritiva:** Exploração histórica dos dados de vendas.
- **Análise Diagnóstica:** Identificação de correlações entre volume de itens, transações e faturamento.
- **Análise Preditiva:** Projeção de vendas utilizando séries temporais.
- **Análise Prescritiva:** Aplicação de Regressão Linear para determinar as variáveis de maior impacto no faturamento.

## 🛠️ Tecnologias Utilizadas
- **Python** (linguagem principal)
- **Pandas** (manipulação de dados)
- **NumPy** (cálculos numéricos)
- **Matplotlib/Seaborn/Potly** (visualização)
- **Sklearn** (regressão)
- **Jupyter Notebook** (análise exploratória)

## 💡 Principais Insights
- **Ticket Médio vs. Volume:** Identificou-se que o faturamento é fortemente impulsionado pela quantidade de itens por transação, mais do que pelo aumento isolado no número de clientes.
- **Sazonalidade:** O modelo de séries temporais revelou padrões sazonais que permitem antecipar períodos de baixa e planejar estoques e promoções.
- **Acurácia do Modelo:** A projeção de vendas atingiu um MAPE (Erro Médio Absoluto Percentual) de 9%, garantindo alta confiabilidade para o planejamento financeiro.

## 🚀 Recomendações Estratégicas
- **Focar em oferecer mais produtos:** A análise mostrou que a quantidade de itens é a variável que mais impacta no faturamento da empresa.
- **Analisar o preço médio de cada item:** As vendas são alavancadas quando a empresa consegue vendar produtos com preços maiores.
- **Fidelização:** Manter a base atual comprando mais frequentemente é mais efetivo, no curto prazo, do que o custo de aquisição de novos clientes em um cenário de alta concorrência.
