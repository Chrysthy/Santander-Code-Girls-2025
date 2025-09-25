# Lab com AWS CloudFormation

Este repositório contém minhas anotações e experimentos práticos realizados no laboratório da [DIO](https://www.dio.me/) sobre **AWS CloudFormation**.

<br>

## 📌 Objetivo

O objetivo deste projeto foi criar uma Stack na AWS utilizando **CloudFormation**, entendendo como declarar e provisionar recursos de forma automatizada.

<br>

## 🛠️ Template YAML

Cria um bucket no S3 com nome único baseado no seu AccountId.

<br>

## 📊 Arquitetura do Lab

```mermaid
flowchart TD
    A[template.yaml] --> B[CloudFormation]
    B --> C[Stack criada]
    C --> D[S3 Bucket]
```

<br>

## 📎 Referências
- [Documentação AWS CloudFormation](https://docs.aws.amazon.com/cloudformation/)
- [Guia da DIO sobre CloudFormation](https://web.dio.me/)
