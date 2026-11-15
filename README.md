# 🎮 Dashboard de Vendas Xbox com Excel

## 📖 Sobre o Projeto

Este projeto consiste na criação de um dashboard interativo no Microsoft Excel para análise de vendas e assinaturas do ecossistema Xbox. O objetivo é transformar dados brutos em informações visuais e estratégicas, facilitando o acompanhamento de indicadores de desempenho relacionados aos planos Xbox Game Pass e produtos adicionais.

O dashboard utiliza tabelas, gráficos dinâmicos e segmentações de dados para fornecer uma visão consolidada das assinaturas e receitas geradas ao longo do período analisado.

Baseado no arquivo [Criando um Dashboard de Vendas do Xbox com Excel.xlsx](https://onedrive.live.com/personal/612e3a1708280398/_layouts/15/doc.aspx?resid=1f4fa8ac-d1ce-46df-8362-a8109312494c&cid=612e3a1708280398&EntityRepresentationId=618678f7-c9a2-4357-98bc-cebc23927a9f).

---

## 🚀 Objetivos

- Consolidar dados de assinantes Xbox.
- Monitorar receitas provenientes de assinaturas.
- Analisar a adesão aos diferentes planos do Game Pass.
- Avaliar vendas de conteúdos adicionais como:
  - EA Play Season Pass
  - Minecraft Season Pass
- Facilitar a tomada de decisão por meio de visualizações intuitivas.

---

## 📊 Estrutura do Arquivo

### 1. Assets
Área utilizada para armazenar recursos visuais do projeto:

- Logos Xbox
- Ícones de apoio
- Paleta de cores utilizada no dashboard

### 2. Bases
Base principal contendo os registros de assinantes e vendas.

Principais campos:

| Campo | Descrição |
|---------|---------|
| Subscriber ID | Identificador do assinante |
| Name | Nome do cliente |
| Plan | Plano contratado |
| Start Date | Data de início da assinatura |
| Auto Renewal | Renovação automática |
| Subscription Price | Valor da assinatura |
| Subscription Type | Tipo da assinatura |
| EA Play Season Pass | Possui EA Play |
| EA Play Season Pass Price | Valor do EA Play |
| Minecraft Season Pass | Possui Minecraft Pass |
| Minecraft Season Pass Price | Valor do Minecraft Pass |
| Coupon Value | Valor do desconto aplicado |
| Total Value | Receita total gerada |

A base contém aproximadamente 295 registros de assinantes.

### 3. Cálculos
Planilha destinada à criação de métricas e tabelas dinâmicas.

Indicadores calculados:

- Receita total por tipo de assinatura.
- Receita gerada pelo EA Play.
- Receita gerada pelo Minecraft Season Pass.
- Consolidação de totais para exibição no dashboard.

### 4. Dashboard
Área visual do projeto.

Recursos utilizados:

- Gráfico de barras.
- Segmentação por tipo de assinatura.
- Indicadores de receita.
- Elementos visuais personalizados da marca Xbox.
- Layout focado em análise gerencial.

---

## 🛠 Tecnologias Utilizadas

- Microsoft Excel
- Tabelas Estruturadas
- Tabelas Dinâmicas
- Gráficos Dinâmicos
- Segmentação de Dados (Slicers)
- Fórmulas de agregação
- GETPIVOTDATA

---

## 📈 Indicadores Disponíveis

O dashboard permite analisar:

- Quantidade de assinantes por categoria.
- Receita total gerada.
- Assinaturas anuais, mensais e trimestrais.
- Receita adicional com EA Play.
- Receita adicional com Minecraft Season Pass.
- Impacto de descontos aplicados.

---

## 🎯 Benefícios do Projeto

- Centralização das informações de vendas.
- Visualização rápida dos principais KPIs.
- Redução do tempo de análise.
- Melhor acompanhamento do desempenho das assinaturas.
- Apoio à tomada de decisão baseada em dados.

---

## 📂 Estrutura de Dados

```text
Bases
│
├── Assinantes
├── Planos Xbox
├── Renovação Automática
├── EA Play
├── Minecraft Pass
├── Cupons
└── Receita Total

Calculos
│
├── Tabelas Dinâmicas
├── Consolidação de Indicadores
└── Métricas de Receita

Dashboard
│
├── KPIs
├── Gráficos
├── Filtros
└── Visualizações
```

---

## 👨‍💻 Autor

Henrique Carvalho

Projeto desenvolvido para fins de aprendizado e demonstração de técnicas de construção de dashboards analíticos no Excel utilizando dados de assinaturas do Xbox Game Pass.
