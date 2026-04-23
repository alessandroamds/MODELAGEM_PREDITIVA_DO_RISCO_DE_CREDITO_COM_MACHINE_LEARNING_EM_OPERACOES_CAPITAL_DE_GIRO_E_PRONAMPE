## 📖 Descrição | Description

**Português**

Este repositório contém o código utilizado no estudo *"Modelagem Preditiva do Risco de Crédito com Machine Learning em Operações de Capital de Giro e PRONAMPE"*. O estudo investiga a aplicação de modelos de Machine Learning na predição do risco de crédito corporativo em carteiras com características estruturais distintas, utilizando dados históricos de uma instituição financeira brasileira.

O desenho empírico contempla três abordagens: (i) modelos baseline dentro de cada carteira, (ii) generalização cruzada entre carteiras e (iii) modelo combinado (pooled). A avaliação de desempenho considera métricas adequadas a bases desbalanceadas, bem como técnicas de interpretabilidade baseadas em valores SHAP.

---

**English**

This repository contains the code used in the study *"Predictive Modeling of Credit Risk using Machine Learning in Working Capital and PRONAMPE Operations"*. The study investigates the application of Machine Learning models for corporate credit risk prediction across structurally distinct portfolios, using historical data from a Brazilian financial institution.

The empirical design comprises three approaches: (i) baseline models within each portfolio, (ii) cross-portfolio generalization, and (iii) a combined (pooled) model. Performance evaluation relies on metrics suitable for imbalanced datasets, along with explainability techniques based on SHAP values.

---

## ⚙️ Execução do Código | Code Execution

**Português**

Para a correta execução do notebook e reprodução dos resultados apresentados no estudo, é necessário realizar o download dos seguintes arquivos:

- `base_capitalgiro.parquet`
- `base_pronampe.parquet`
- `Artigo_MODELAGEM_PREDITIVA_DO_RISCO_DE_CRÉDITO_COM_MACHINE_LEARNING_EM_OPERAÇÕES_DE_CAPITAL_DE_GIRO_E_PRONAMPE_v22042026.ipynb`

Após o download:

1. Faça o upload dos arquivos no ambiente do Google Colab;
2. Certifique-se de que os arquivos `.parquet` estejam no mesmo diretório do notebook;
3. Execute o notebook sequencialmente para reproduzir todas as etapas do pipeline, incluindo:
   - preparação dos dados;
   - estimação dos modelos;
   - validação temporal (out-of-time);
   - avaliação de desempenho;
   - análise de interpretabilidade (SHAP).

---

**English**

To correctly execute the notebook and reproduce the results presented in the study, the following files must be downloaded:

- `base_capitalgiro.parquet`
- `base_pronampe.parquet`
- `Artigo_MODELAGEM_PREDITIVA_DO_RISCO_DE_CRÉDITO_COM_MACHINE_LEARNING_EM_OPERAÇÕES_DE_CAPITAL_DE_GIRO_E_PRONAMPE_v22042026.ipynb`

After downloading:

1. Upload the files to the Google Colab environment;
2. Ensure that the `.parquet` files are located in the same directory as the notebook;
3. Run the notebook sequentially to reproduce all stages of the pipeline, including:
   - data preprocessing;
   - model training;
   - out-of-time validation;
   - performance evaluation;
   - explainability analysis (SHAP).

---

## 🔁 Reprodutibilidade | Reproducibility

**Português**

O repositório foi estruturado com o objetivo de garantir a reprodutibilidade completa dos resultados empíricos apresentados no estudo, em conformidade com boas práticas de pesquisa em Machine Learning e risco de crédito.

---

**English**

This repository is designed to ensure full reproducibility of the empirical results presented in the study, in accordance with best practices in Machine Learning and credit risk research.
