# 📊 Dashboard Financeiro — Análise de Receitas, Custos e Lucratividade

> Dashboard interativo desenvolvido em Power BI para análise financeira completa de uma empresa,
> com foco em lucratividade, fluxo de caixa e padrões sazonais de desempenho.

---

## 🖥️ Visualizações do Dashboard

**Tela principal — Visão Geral**
![Visão Geral]()


---

## 📌 Contexto do Projeto

Este projeto nasceu da necessidade de responder perguntas financeiras estratégicas de forma visual e acessível. O objetivo foi transformar dados financeiros brutos em um painel interativo com scroll, permitindo que qualquer pessoa da organização entendesse rapidamente a saúde financeira do negócio.

**Perguntas que o dashboard responde:**
- Qual foi a receita total e como ela se distribui ao longo do ano?
- Quais são os principais custos e qual seu impacto na margem de lucro?
- Como impostos afetam o resultado final?
- Qual banco concentra o maior volume de transações?
- Qual meio de pagamento é mais utilizado pelos clientes?
- Existe algum padrão sazonal no lucro?

---

## 📈 Principais Resultados

| Indicador | Valor |
|-----------|-------|
| Receita Total | R$ 94,60 mi |
| Custos Totais | R$ 44,86 mi |
| Impostos | R$ 14,19 mi |
| **Lucro Líquido** | **R$ 35,55 mi** |
| Margem de Lucro | ~37,6% |

### 🔍 Insights encontrados

- **Sazonalidade de lucro:** O negócio apresentou crescimento consistente de janeiro (R$ 5 mi) até setembro (pico de R$ 13 mi), seguido de queda expressiva chegando a R$ 2 mi em dezembro. Esse padrão pode indicar sazonalidade anual — uma hipótese que pode ser validada com dados de anos anteriores ou posteriores.

- **Meio de pagamento dominante:** PIX foi o tipo de transação mais utilizado, o que pode orientar decisões sobre integração de sistemas de pagamento.

- **Análise por banco:** O dashboard identifica qual instituição financeira concentra maior volume de movimentação, relevante para decisões de relacionamento bancário.

---

## 🛠️ Ferramentas Utilizadas

| Ferramenta | Finalidade |
|-----------|-----------|
| Power BI Desktop | Desenvolvimento do dashboard e visualizações |
| Excel | Verificação e validação dos dados de origem |
| Power Query (M Language) | Transformação e carregamento dos dados |
| DAX | Criação de medidas e KPIs calculados |

---

## 📁 Estrutura do Projeto

```
dashboard-financeiro/
│
├── 📂 dados/
│   └── dados_financeiros.xlsx       # Fonte de dados (anonimizada)
│
├── 📂 dashboard/
│   └── dashboard_financeiro.pbix    # Arquivo Power BI
│
├── 📂 prints/
│   ├── visao_geral.png              # Print da tela principal
│   ├── analise_mensal.png           # Evolução mensal do lucro
│   └── analise_pagamentos.png       # Distribuição por tipo de pagamento
│
└── README.md
```

## ⚙️ Como Abrir o Dashboard

1. Faça o download do arquivo `dashboard_financeiro.pbix`
2. Abra o **Power BI Desktop** (gratuito — [download aqui](https://powerbi.microsoft.com/pt-br/desktop/))
3. Vá em `Arquivo > Abrir` e selecione o arquivo `.pbix`
4. O dashboard já estará conectado à base de dados local

> **Nota:** Os dados utilizados são fictícios/anonimizados para fins de demonstração.

---

## 👤 Autor

**[Seu Nome]**
Analista de Dados em formação | Power BI · Excel · SQL · Python

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mateus-junior-7ab55b144/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/MateusSjunior)

---

*Projeto desenvolvido como parte do meu portfólio de transição para a área de dados.*
