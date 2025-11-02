# Implementando Infraestrutura Automatizada com AWS CloudFormation

## 📌 Descrição do Projeto
Este projeto foi realizado como parte do desafio da DIO para praticar **infraestrutura automatizada com AWS CloudFormation**.  
O objetivo foi criar uma Stack que provisiona automaticamente múltiplos recursos na AWS e documentar o processo.

A Stack criada neste laboratório inclui:

- Uma instância EC2 (`t2.micro`)  
- Um Security Group permitindo acesso SSH  
- Um Bucket S3 para armazenamento de dados  

---

## 🛠️ Tecnologias Utilizadas
- **AWS CloudFormation** – Provisionamento automatizado da infraestrutura  
- **AWS EC2** – Instância virtual para execução de workloads  
- **AWS Security Groups** – Controle de acesso à instância  
- **AWS S3** – Armazenamento de arquivos  
- **AWS Console** – Monitoramento e testes da Stack  

---

## 🏗️ Arquitetura da Infraestrutura

[Security Group] ←→ [EC2 Instance]
│
▼
[S3 Bucket]


### Explicação:

- **EC2 Instance**: Máquina virtual criada automaticamente  
- **Security Group**: Permite acesso SSH (porta 22)  
- **S3 Bucket**: Armazena arquivos e dados da aplicação  
- **CloudFormation**: Garante que todos os recursos sejam criados de forma **automatizada e replicável**  

---

## 📄 Arquivo JSON do Template
O template está no arquivo `infrastructure-stack.json`, pronto para ser usado no AWS CloudFormation.  
Inclui a criação de EC2, Security Group e S3, além de **Outputs** que retornam o ID da EC2 e o nome do bucket.

---

## 🧠 Insights e Aprendizados
- Entendi como criar **infraestrutura automatizada** usando templates declarativos  
- Aprendi a provisionar múltiplos recursos em uma Stack  
- Compreendi a importância de **Outputs e Tags** para identificação de recursos  
- Aprendi a organizar e documentar o template de forma clara para reuso futuro  

---

## 📂 Estrutura do Repositório
│── README.md

└── infrastructure-stack.json


---

## 👩‍💻 Autora
Projeto desenvolvido por **Amanda Justen** — Engenharia de Computação & IA  
LinkedIn: [linkedin.com/in/amanda-justen-80b17182](https://linkedin.com/in/amanda-justen-80b17182)
