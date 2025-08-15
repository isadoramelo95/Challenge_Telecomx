# 📊 Análise de cancelamento - TelecomX

Este projeto foi desenvolvido como parte do programa Oracle Next Education (ONE), uma iniciativa educacional promovida pela Oracle em parceria com a Alura, 
tendo como objetivo analisar os dados de clientes da empresa TelecomX
a fim de identificar os principais fatores que levam ao cancelamento de contrato (Churn) e propor recomendações para melhorar a retenção de clientes.

## 🎯 Objetivo
1. Coletar e tratar os dados de clientes no JSON.
2. Explorar e entender o comportamento dos clientes.
3. Identificar padrões e possíveis causas de evasão de clientes.
4. Oferecer insights estratégicos para redução da evasão de clientes.


## 🔧 Metodologia

1. **Extração dos Dados**  
   - Dados importados de arquivo `.json`.

2. **Transformação**  
   - Normalização da estrutura em um DataFrame.
   - Tradução do das colunas para o portugês.
   - Mapeamento binário de variáveis textuais (Yes/No → 1/0).
   - 

3. **Análise Exploratória**  
   - Análise de churn por tempo de contrato, tipo de serviço, método de pagamento, etc.
   - A análise exploratória revelou importantes padrões de comportamento entre os clientes.

Visualizações com gráficos de barras, histograma, boxplot e heatmap.
Análise de churn por tempo de contrato, tipo de serviço, método de pagamento, etc.

## ✅ Sugestão ao TelecomX

- Desenvolver um modelo preditivo de churn para identificar clientes em risco.
- Acompanhar a taxa de churn trimestralmente e ajustar ações com base em feedback e KPIs.
- Oferecer planos familiares com um descconto.
- Incluir o serviço de internet
- melhorar o atendimento no pós além de a hora da venda
- reavliar o método de pagamento

# ▶️ Instruções para Execução

1. Clone este repositório:

```
git clone [https://github.com/isadoramelo95/Challenge_Telecomx/]
```
2. Instale os pacotes necessários (utilizando virtualenv recomendado):

```
pip install pandas matplotlib seaborn
```

Aluna: Isadora Melo
Challenge TelecomX - ONE
3. Execute o notebook:

```
jupyter notebook TelecomX_BR.ipynb
```
