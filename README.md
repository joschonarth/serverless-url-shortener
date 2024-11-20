# 🔗 Encurtador de URL Serverless

Este repositório contém a implementação da funcionalidade de **encurtamento de URLs** em **Java**, utilizando uma arquitetura **serverless** com serviços da **AWS**.

## 🛠️ Tecnologias Utilizadas

- ☕ **Java**: Linguagem de programação utilizada. 
- ⚡ **AWS Lambda**: Para execução de funções serverless. 
- 📂 **AWS S3**: Para armazenamento das URLs encurtadas e metadados. 
- 🌐 **AWS API Gateway**: Para expor as APIs do sistema. 
- 🔒 **AWS IAM**: Para controle de permissões e segurança.  

## ⚙️ Funcionalidades

- 🌐 Receber uma URL original via API.
- 🔑 Gerar um código curto único para a URL. 
- 📦 Armazenar o código curto e a URL original em um bucket S3.  

## 🌐 Redirecionador de URL

O **Encurtador de URL** é responsável por gerar URLs curtas e armazenar suas informações. Para que as URLs curtas funcionem corretamente, você deve também configurar o **Redirecionador de URL**.

➡️ **Confira o repositório do Redirecionador de URL [aqui](https://github.com/joschonarth/serverless-url-redirect)**.