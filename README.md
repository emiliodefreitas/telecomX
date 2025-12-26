PROJETO: ANÁLISE DE CHURN DE CLIENTES - TELECOM X
==================================================

OBJETIVO
--------
Este projeto tem como objetivo realizar o processo completo de ETL (Extração, Transformação e Carregamento) e EDA (Análise Exploratória de Dados) para identificar os principais fatores que levam à evasão de clientes (Churn) na empresa Telecom X.

Os insights gerados servem como base para a equipe de Data Science desenvolver modelos preditivos e estratégias de retenção.

PROCESSO REALIZADO
------------------
1. Extração (E): Dados extraídos de uma API (arquivo JSON) hospedada em um repositório do GitHub.
2. Transformação e Limpeza (T):
    - Renomeação e simplificação das colunas.
    - Tratamento de valores nulos e conversão de tipos de dados (ex: Charges.Total para numérico).
    - Tradução de colunas e valores categóricos para o Português.
3. Análise Exploratória (EDA): Análise da distribuição de churn e correlação com variáveis como tipo de contrato, tempo de permanência (tenure) e serviço de internet.

ARQUIVOS DO PROJETO
-------------------
- Analise_Churn_Telecom_X.ipynb: Relatório principal. Contém todo o código Python, a documentação do processo de ETL, a análise exploratória completa (EDA) com gráficos e as conclusões/recomendações.
- telecom_churn_cleaned.csv: Conjunto de dados final, limpo e tratado, pronto para a modelagem preditiva.
- telco_churn.json: Cópia do arquivo JSON original extraído da API.
- plots/: Diretório contendo as imagens dos gráficos gerados durante a EDA.

PRINCIPAIS INSIGHTS
-------------------
A análise exploratória destacou que os clientes com contratos mensais e aqueles que utilizam o serviço de Fibra Óptica são os mais propensos a cancelar, especialmente nos primeiros meses de contrato.


