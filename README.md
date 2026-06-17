# ☁️ Desafio DIO - Infraestrutura como Código com AWS CloudFormation

Repositório criado para o desafio prático de automação de infraestrutura na AWS utilizando o **CloudFormation**, desenvolvido no bootcamp da [DIO](https://www.dio.me/).

---

## 🎯 Objetivo
O objetivo deste laboratório foi aplicar os conceitos de Cultura DevOps e Infraestrutura como Código (IaC) para criar e gerenciar recursos na AWS de forma automatizada e segura.

## 🧠 Principais Aprendizados e Insights
* **Segurança na AWS:** Aprendi que o formato padrão para configurar políticas e permissões no IAM é o **JSON** e que boas práticas exigem bloquear o acesso público de buckets S3 sensíveis.
* **Criptografia:** Dados em repouso e em trânsito (utilizando HTTPS/TLS) devem ser protegidos para garantir a integridade das credenciais e dados dos usuários.
* **Ferramentas DevOps:** Compreendi que o Terraform utiliza o arquivo `.tfstate` para gerenciar o estado da nuvem e que ele nunca deve ser editado manualmente. Já para implantações automatizadas na AWS, o serviço ideal é o **AWS CodeDeploy**.
* **Cultura DevOps:** O foco principal é promover a colaboração contínua entre Desenvolvimento (Dev) e Operações (Ops) para acelerar as entregas com alta qualidade.

---

## 🚀 Comprovação Prática (Execução)

A stack foi criada e, em seguida, removida com sucesso no ambiente da AWS para seguir as boas práticas de gerenciamento de custos na nuvem.

Abra a imagem abaixo para conferir o status final do laboratório:

![Status do CloudFormation](./cloudformation-sucesso.png)

*(Nota: Caso sua imagem tenha outro nome, mude o trecho `cloudformation-sucesso.png` exato para o nome do seu arquivo de imagem)*
