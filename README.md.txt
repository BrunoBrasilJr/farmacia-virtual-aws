# 💊 Plataforma Virtual para Farmácia - AWS

## 📌 Descrição
Este projeto apresenta a modelagem de uma plataforma virtual para uma farmácia fictícia utilizando serviços da AWS.

O objetivo é aplicar conceitos de computação em nuvem em um cenário realista, envolvendo escalabilidade, segurança, alta disponibilidade e desempenho.

---

## 🎯 Objetivo
Desenvolver a arquitetura de uma farmácia virtual capaz de:

- cadastrar usuários
- exibir produtos
- processar pedidos
- armazenar receitas médicas
- escalar conforme demanda

---

## ☁️ Serviços AWS Utilizados

- Amazon S3
- Amazon CloudFront
- Amazon EC2
- Elastic Load Balancing
- Amazon EC2 Auto Scaling
- Amazon RDS
- Amazon VPC
- AWS IAM
- Amazon CloudWatch
- Amazon Route 53

---

## 🏗️ Arquitetura da Solução

A aplicação funciona da seguinte forma:

- O usuário acessa a aplicação via internet
- O Route 53 faz o direcionamento
- O CloudFront melhora a entrega do conteúdo
- O front-end pode ser hospedado no S3
- As requisições vão para um Load Balancer
- O Load Balancer distribui para instâncias EC2
- O banco de dados é gerenciado pelo Amazon RDS
- Arquivos são armazenados no S3
- CloudWatch monitora toda a aplicação

---

## 🔐 Segurança

- Uso de IAM para controle de acesso
- Security Groups para controle de tráfego
- Banco de dados em sub-rede privada
- Possibilidade de uso de HTTPS com CloudFront

---

## 📈 Escalabilidade

- Auto Scaling ajusta instâncias conforme demanda
- Load Balancer distribui requisições
- S3 escala automaticamente

---

## 🧠 Conclusão

Este projeto demonstra como a AWS pode ser utilizada para criar soluções modernas, escaláveis e seguras para aplicações reais como uma farmácia virtual.

---

## 🖼️ Diagrama da Arquitetura

![Diagrama](./arquitetura/diagrama-arquitetura.png)

---

## 👨‍💻 Autor

Bruno Brasil