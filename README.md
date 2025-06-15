Projeto de Análise de Dados – Abandono do Tratamento da Tuberculose no Brasil

Este projeto foi desenvolvido como parte da parceria entre EBAC e a empresa Semantix, com o objetivo de aplicar conceitos de Análise de Dados na resolução de uma problemática real: o abandono do tratamento da tuberculose no Brasil.

Tema do Projeto
Análise do comportamento e distribuição dos casos de abandono do tratamento da tuberculose, com foco nacional (base SINAN) e regional (estado de Minas Gerais), identificando padrões por ano, gênero e município.

Coleta de Dados
Os dados utilizados foram obtidos a partir de fontes públicas e não confidenciais:

Banco de Dados do SINAN – Ministério da Saúde

Fonte: https://datasus.saude.gov.br
Conteúdo: Casos confirmados de tuberculose e abandonos de tratamento no Brasil entre 2001 e 2024
Formato: CSV exportado diretamente via TABNET
Tipo de dados: Estruturados
Secretaria Estadual de Saúde de Minas Gerais (SES-MG)

Fonte: http://www.saude.mg.gov.br
Conteúdo: Casos de tuberculose registrados no estado de Minas Gerais, com dados por município e gênero
Tipo de dados: Estruturados
Formato: CSV
Modelagem e Análise
As etapas de pré-processamento e análise foram realizadas utilizando ferramentas como Python (Pandas, Matplotlib, Seaborn) e Looker Studio para visualizações finais. O processo incluiu:

1. Limpeza dos Dados
Remoção de linhas de rodapé e totais incorretos
Conversão de colunas para tipos numéricos apropriados
Padronização de nomes de colunas
2. Análise Exploratória
Identificação de tendências ao longo dos anos (linha do tempo de abandono)
Análise de distribuição de abandono por gênero (dado SES-MG)
Identificação dos 10 municípios com mais casos de abandono (dado SES-MG)
3. Visualização
Criação de dashboards separados para Brasil e Minas Gerais no Looker Studio
Gráficos de linha, barras e pizza para explorar os dados
Conclusões
O abandono do tratamento da tuberculose apresenta tendência oscilante no Brasil, com aumento de casos entre 2015 e 2019, seguido de queda a partir de 2020 (potencialmente relacionada à pandemia).
Homens são significativamente mais propensos a abandonar o tratamento em Minas Gerais.
A maioria dos casos se concentra em grandes centros urbanos, como Belo Horizonte, Uberlândia e Contagem.
Reforça-se a necessidade de políticas públicas mais focadas em grupos vulneráveis e regiões críticas.
Estrutura do Projeto




Desenvolvido por
José Lucas Aguilera Cardoso Curso de Análise de Dados – EBAC
Projeto em parceria com a Semantix
