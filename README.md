# 📊 Projeto SCPC Agro — Análise de Crédito no Agronegócio

Este projeto foi desenvolvido como parte do curso em parceria com a **Semantix**.  
O objetivo é analisar a **inadimplência de crédito rural** e seus impactos no setor do agronegócio, utilizando dados públicos e ferramentas de análise de dados.

---

## 🔎 Problema

A inadimplência no crédito rural é um dos principais desafios do agronegócio.  
Ela compromete a capacidade de investimento, a expansão da produção e impacta toda a cadeia produtiva — desde o pequeno produtor até grandes cooperativas e instituições financeiras.  

---

## 📂 Estrutura do Projeto

projeto_scpc_agro/
├── data_raw/ # Dados brutos coletados (IBGE e Bacen)
├── data_cleaned/ # Dados tratados e prontos para análise
├── notebooks/ # Notebooks Jupyter (análise exploratória)
├── docs/ # Relatórios e PDF final
├── .gitignore
├── requirements.txt
└── README.md


---

## 📊 Coleta de Dados

- **Banco Central (BACEN)** → Séries históricas de inadimplência do crédito rural.  
- **IBGE / SIDRA (PAM)** → Produção agrícola municipal (valor de produção e área colhida).  

Ferramentas utilizadas:
- `requests` e `pandas` para consumo da API do Bacen.
- `sidrapy` para consulta de dados do IBGE.
- Google Colab para tratamento e organização.

---

## 🔍 Modelagem e Análise

1. **Tratamento de dados**: limpeza, padronização e integração das bases.  
2. **Exploração**: estatísticas descritivas, correlações e comparações regionais.  
3. **Visualizações**: evolução da produção e inadimplência, comparação entre municípios, distribuição por área.  

Ferramentas utilizadas:
- `Python`, `pandas`, `matplotlib`, `seaborn`
- Google Colab
- Looker Studio (dashboard interativo)

---

## 📈 Resultados e Conclusões

- Foi identificada uma relação entre **alta inadimplência** e **redução no valor de produção agrícola** em alguns municípios.  
- Pequenos e médios produtores são os mais impactados, pois dependem mais de crédito bancário.  
- A inadimplência eleva o **custo do dinheiro** e reduz a capacidade produtiva no campo, prejudicando a competitividade do setor.  

---

## 📊 Dashboard Interativo

👉 [Acesse o Dashboard no Looker Studio](COLE_AQUI_SEU_LINK_DO_LOOKER)

---

## 📚 Requisitos

As principais bibliotecas utilizadas estão listadas em [`requirements.txt`](requirements.txt).  
Para instalar:

```bash
pip install -r requirements.txt


👩‍💻 Autoria

Projeto desenvolvido por Luana Carvalho
GitHub: Lucarvalho123