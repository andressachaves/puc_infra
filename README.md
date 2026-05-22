# 🔍 Sistema de Detecção de Fraudes com IaC

Pipeline completo de detecção de fraudes desenvolvido na PUC Minas,
cobrindo desde a infraestrutura em nuvem até o modelo de ML.

## Stack

**Infraestrutura**
* Terraform — provisionamento IaC
* AWS EC2 — hospedagem da aplicação Flask
* AWS S3 — armazenamento de dados
* AWS CloudWatch — logs, métricas e alarmes
* Prefect — orquestração do pipeline ETL

**Modelo**
* Python · scikit-learn
* LinearSVC + TF-IDF

## Resultado

| Métrica | Valor |
|---|---|
| Acurácia | 92,33% |
| F1-macro | 0,92 |

Maior acurácia entre de todos da equipe do projeto.



**Andressa Chaves**

> Projeto acadêmico — Big Data Analytics / Engenharia de Dados, PUC Minas
