# 🏗️ Infraestrutura como Código — PUC Minas

Provisionamento de ambiente com Docker e Terraform na AWS,
desenvolvido como projeto acadêmico na PUC Minas.

## Stack
- Docker · Terraform · AWS CLI
- Infrastructure as Code (HCL)

## Estrutura
puc_infra/
├── Dockerfile
├── IaC/         # arquivos Terraform
└── LEIAME.txt

## Como usar

```bash
# Build da imagem
docker build -t puc-terraform-image:eixo4 .

# Subir container com volume IaC montado
docker run -dit --name container-iac \
  -v /caminho/local/IaC:/iac \
  puc-terraform-image:eixo4 /bin/bash

# Verificar dependências
terraform version
aws --version

## Resultado
![Matriz de Confusão](confusion_matrix.png)
�PNG


```
