# ws-lambda-s3-automation
Repositório prático do desafio da DIO para automação de tarefas utilizando AWS Lambda, Amazon S3 e LocalStack.

# Executando Tarefas Automatizadas com Lambda Function e S3

Repositório criado para documentar o desafio prático do módulo de AWS da DIO, focado na criação de arquiteturas orientadas a eventos utilizando **AWS Lambda**, **Amazon S3**, **DynamoDB** e simulação local com **LocalStack**.

---

## 📋 Sobre o Desafio
O objetivo principal deste projeto é consolidar conhecimentos em automação baseada em eventos, configurando um gatilho (*trigger*) num bucket do S3 para disparar funções serverless no Lambda sempre que novos ficheiros ou uploads forem efetuados.

---

## 🚀 Tecnologias e Ferramentas Utilizadas
* **AWS Lambda:** Computação serverless orientada a eventos.
* **Amazon S3:** Armazenamento de objetos e disparo de notificações/eventos.
* **Amazon DynamoDB:** Registo e armazenamento estruturado dos dados processados.
* **LocalStack:** Simulação local de serviços da AWS para desenvolvimento e testes.
* **Git e GitHub:** Controlo de versão e documentação técnica.

---

## 🛠️ Arquitetura e Implementação
1. **Configuração do S3 e Lambda:**
   * Criação do bucket de origem para armazenamento de ficheiros.
   * Desenvolvimento da função Lambda responsável por processar os eventos de upload.
2. **Integração com DynamoDB:**
   * Registo dos metadados dos ficheiros processados na tabela do DynamoDB.
3. **Testes Locais (LocalStack):**
   * Validação do fluxo de automação num ambiente isolado antes da publicação.

---

## 📁 Estrutura do Repositório

```text
├── src/                # Código-fonte da função Lambda
├── template/           # Ficheiros de configuração e automação
├── images/             # Capturas de tela do funcionamento e arquitetura
└── README.md           # Documentação técnica do projeto
