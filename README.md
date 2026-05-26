# 🔍 Sistema de Detecção de Fraudes com IaC

Pipeline completo de detecção de fraudes desenvolvido na PUC Minas,
cobrindo desde a infraestrutura em nuvem até o modelo de ML.

## 📋 Descrição

Este repositório contém a infraestrutura como código e o pipeline de ML do projeto acadêmico da PUC Minas, explorando conceitos de DevOps, Big Data e Machine Learning aplicados à detecção de fraudes.

## 🛠️ Stack

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![IaC](https://img.shields.io/badge/IaC-Infrastructure_as_Code-orange?style=for-the-badge)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Infraestrutura**
* Terraform — provisionamento IaC
* AWS EC2 — hospedagem da aplicação Flask
* AWS S3 — armazenamento de dados
* AWS CloudWatch — logs, métricas e alarmes
* Prefect — orquestração do pipeline ETL



## 📁 Estrutura do Projeto
puc_infra/
├── Dockerfile # Configuração do container
├── IaC/ # Arquivos de Infrastructure as Code
└── README.md


## 🚀 Como Usar

### Pré-requisitos
- Docker instalado
- Git

### Executando o projeto

```bash
# Clone o repositório
git clone https://github.com/andressachaves/puc_infra.git

# Entre na pasta
cd puc_infra

# Build da imagem Docker
docker build -t puc_infra .

# Execute o container
docker run puc_infra

Projeto acadêmico — Big Data Analytics / Banco de Dados, PUC Minas