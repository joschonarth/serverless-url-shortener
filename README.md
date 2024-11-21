# 🔗 Encurtador de URL Serverless

Este repositório contém a implementação da funcionalidade de **Encurtamento de URLs**, desenvolvido em **Java** e utilizando uma arquitetura **serverless** com serviços da **AWS**.

## 📜 Visão Geral do Projeto

O **Encurtador de URL Serverless** é um sistema de encurtamento de URLs simples e eficiente, desenvolvido com uma arquitetura totalmente serverless, utilizando **AWS Lambda**, **AWS API Gateway**, **AWS S3** e **AWS IAM** para garantir escalabilidade, baixo custo e segurança. O projeto inclui tanto a funcionalidade de encurtamento de URLs quanto a configuração de um redirecionador de URLs para reverter os links curtos.

## 🛠️ Tecnologias Utilizadas

- ☕ **Java**: Linguagem de programação utilizada. 
- ⚡ **AWS Lambda**: Para execução das funções serverless. 
- 📂 **AWS S3**: Para armazenar as URLs originais e os códigos curtos gerados.
- 🌐 **AWS API Gateway**: Para expor as APIs do sistema. 
- 🔒 **AWS IAM**: Para definição de políticas que controlam o acesso das funções Lambda.  

## ⚙️ Funcionalidades

- 🌐 Receber uma URL original via API.
- 🔑 Gerar um código curto único para a URL. 
- 📦 Armazenar o código curto e a URL original em um bucket S3.  

## 🔄 Redirecionamento de URL

Este projeto de encurtamento de URL trabalha em conjunto com o **[Redirecionador de URL Serverless](https://github.com/joschonarth/serverless-url-redirect)**, que é responsável por redirecionar os usuários para as URLs originais a partir do código curto gerado aqui.

➡️ Consulte o repositório do **[Redirecionador de URL Serverless](https://github.com/joschonarth/serverless-url-redirect)** para configurar a parte do redirecionamento e fazer uso da URL encurtada criada por este serviço.

## 📚 Links Úteis

- 🔧 [AWS Lambda](https://aws.amazon.com/lambda/)
- 🗄️ [AWS S3](https://aws.amazon.com/s3/)
- 🌐 [AWS API Gateway](https://aws.amazon.com/api-gateway/)
- 🛠️ [AWS Serverless Application Model (SAM)](https://aws.amazon.com/serverless/sam/)