#  Projeto de Análise de Dados – Abandono do Tratamento da Tuberculose no Brasil

Este projeto foi desenvolvido como parte da parceria entre **EBAC** e a empresa **Semantix**, com o objetivo de aplicar conceitos de Análise de Dados na resolução de uma problemática real: o abandono do tratamento da tuberculose no Brasil.

---

##  Tema do Projeto

Análise do comportamento e distribuição dos casos de **abandono do tratamento da tuberculose**, com foco **nacional (base SINAN)** e **regional (estado de Minas Gerais)**, identificando padrões por **ano**, **gênero** e **município**.

---

## 🗂 Coleta de Dados

###  Banco de Dados do SINAN – Ministério da Saúde

- **Fonte:** https://datasus.saude.gov.br  
- **Conteúdo:** Casos confirmados de tuberculose e abandonos de tratamento no Brasil (2001–2024)  
- **Formato:** CSV exportado diretamente via TABNET  
- **Tipo de dados:** Estruturados  

###  Secretaria Estadual de Saúde de Minas Gerais (SES-MG)

- **Fonte:** http://www.saude.mg.gov.br  
- **Conteúdo:** Casos de tuberculose registrados em MG, com dados por município e gênero  
- **Formato:** CSV  
- **Tipo de dados:** Estruturados  

---

##  Modelagem e Análise

As etapas de pré-processamento e análise foram realizadas utilizando ferramentas como **Python** (`pandas`, `matplotlib`, `seaborn`) e **Looker Studio** para visualizações finais.

### Etapas realizadas:

1. **Limpeza dos Dados**
   - Remoção de rodapés e totais incorretos  
   - Conversão de colunas para tipos numéricos  
   - Padronização de nomes de colunas  

2. **Análise Exploratória**
   - Tendência de abandono ao longo dos anos  
   - Comparação por gênero (dados SES-MG)  
   - Identificação dos 10 municípios com mais casos de abandono (dados SES-MG)  

3. **Visualização**
   - Dashboards separados para Brasil e Minas Gerais (Looker Studio)  
   - Gráficos de linha, barras e pizza para explorar os dados  

---

## 📊 Conclusões

- O abandono do tratamento apresenta **tendência oscilante** no Brasil, com aumento entre **2015 e 2019**, seguido de queda a partir de **2020** (possível relação com a pandemia).
- **Homens** são significativamente mais propensos ao abandono do tratamento em **Minas Gerais**.
- A maior concentração de casos ocorre em **grandes centros urbanos**: *Belo Horizonte, Uberlândia e Contagem*.
- Reforça-se a **necessidade de políticas públicas** mais direcionadas a **grupos vulneráveis** e **regiões críticas**.

---



---



Desenvolvido por
José Lucas Aguilera Cardoso Curso de Análise de Dados – EBAC
Projeto em parceria com a Semantix
