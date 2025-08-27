# CrimsonKiss-Investigativo

# 💄 Crimson Kiss — Investigação de Queda nas Vendas

Este projeto analisa a queda brusca nas vendas do batom *Crimson Kiss*, utilizando SQL para estruturação de dados e Power BI para visualização analítica. A investigação revela falhas operacionais, impacto de campanhas de influenciadores e sinais de reputação digital comprometida.

---

## 📊 Objetivo

Identificar os fatores que levaram à queda de vendas do produto *Crimson Kiss*, correlacionando dados de estoque, campanhas de marketing e avaliações de clientes.

---

## 🧠 Processo Investigativo

1. **Criação de base de dados**
   - Tabelas: `Estoque`, `Avaliacoes`, `CampanhasMarketing`
   - Inserção de dados simulados com inconsistências reais

2. **Análise de vendas**
   - Gráfico de linha mostra queda de 20 para 1 unidade/dia entre julho e agosto

3. **Campanhas de influenciadores**
   - Campanha da Duda Glow pausada no mesmo dia das primeiras reclamações
   - ROI baixo e possível desgaste de imagem
   - Campanha da Vivi Shine teve ROI superior mesmo em meio à crise

4. **Inconsistência de estoque**
   - Lojas 101 e 104 com 43 unidades disponíveis fisicamente, mas marcadas como “Zerado” no sistema

5. **Avaliações negativas**
   - Três reclamações registradas entre 01/08 e 03/08, todas com nota ≤ 2
   - Comentários indicam reações adversas e frustração

6. **Recomendações**
   - Auditoria no sistema de estoque
   - Verificação da fórmula do produto e rastreio de lotes
   - Reforço na comunicação com influenciadores e clientes

---

## 🖼️ Print do Dashboard

> _<img width="1334" height="737" alt="Power BI Desktop 26_08_2025 21_41_23" src="https://github.com/user-attachments/assets/f89c07ea-1201-4c70-bf77-56618db0517c" />
_
>
> 
---

## 🔗 Link para o Dashboard Interativo



[🔗 Acesse o Dashboard Crimson Kiss](https://app.powerbi.com/view?r=eyJrIjoiZTUwYjRjOTItZDAzZi00YWFhLWE2YjEtZGQwM2I2NWFiOTQyIiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9)

---

## 📁 Estrutura do Projeto

CrimsonKiss-Investigativo/
│
├── scripts/
│   ├── create_tables.sql
│   ├── insert_data.sql
│   ├── views.sql
│   ├── procedures.sql
│   ├── triggers.sql
│
├── dashboard/
│   ├── imagens/
│   │   ├── painel_geral.png
│   │   ├── roi_por_influencer.png
│   │   ├── vendas_por_mes.png
│   └── layout_pbi.pbix (se quiser incluir o arquivo do Power BI)
│
├── docs/
│   ├── README.md
│   ├── relatorio_investigativo.md
│   ├── insights_recomendacoes.md
│
├── LICENSE
└── .gitignore


---

## 🧪 Tecnologias Utilizadas

- SQL Server
- Power BI
- GitHub Codespaces
- Markdown

---

## ✨ Autoria

Projeto desenvolvido por **Debora**, com foco em análise investigativa de dados, storytelling visual e inteligência de mercado.

---




