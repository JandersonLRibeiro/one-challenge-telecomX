# 📊 Análise de Evasão de Clientes - TelecomX

Este projeto tem como objetivo analisar o comportamento de churn (evasão) de clientes da empresa fictícia TelecomX. A partir de um conjunto de dados disponibilizado em formato JSON, foram realizadas etapas de extração, limpeza, análise exploratória e geração de insights para apoiar estratégias de retenção.

## 🛠️ Etapas do Projeto

### 1. Extração e Tratamento de Dados
- Importação e normalização dos dados provenientes de diferentes níveis (cliente, telefone, internet e conta).
- Conversão de tipos de dados, padronização de variáveis e criação de novas colunas, como gasto diário médio.
- Remoção de registros inconsistentes e codificação de variáveis binárias para facilitar a análise.

### 2. Análise Exploratória
- Avaliação da distribuição do churn na base de clientes.
- Visualizações categóricas por gênero, tipo de contrato, método de pagamento, idade e presença de dependentes.
- Análise numérica com foco em `tenure` (tempo de contrato) e `ChargesTotal` (gasto total do cliente).

### 3. Principais Insights
- Churn é mais frequente entre clientes com contrato mensal e pagamento por fatura eletrônica.
- A taxa de cancelamento é mais alta nos primeiros meses de contrato.
- Clientes que cancelam tendem a ter um gasto total mais baixo.

## 💡 Recomendações
- Focar na retenção nos primeiros meses com ofertas e suporte personalizado.
- Incentivar contratos de maior duração.
- Monitorar clientes com perfil de risco para ações preventivas.

---

🔍 Projeto desenvolvido com Python, utilizando as bibliotecas **Pandas**, **Seaborn** e **Matplotlib**.

