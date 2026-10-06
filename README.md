# ✈️ Aviação ANAC — VoeBem Analytics

Projeto desenvolvido durante a **Imersão Engenharia de Dados da Alura — setembro/2026**, com o objetivo de aplicar, na prática, conceitos fundamentais de Engenharia de Dados utilizando dados reais da **ANAC (Agência Nacional de Aviação Civil)**.

O projeto simula o trabalho da **VoeBem Analytics**, uma consultoria fictícia que busca analisar dados da aviação brasileira para identificar padrões relacionados a **atrasos, cancelamentos e pontualidade dos voos**, transformando dados brutos em informações úteis para análises e tomada de decisão.

## 🎯 Objetivo

Durante o projeto, explorei diferentes etapas de um fluxo de Engenharia de Dados, desde a ingestão e organização dos dados até sua transformação, tratamento, governança e disponibilização para análise.

Além de desenvolver as etapas técnicas, o projeto me permitiu entender melhor como uma arquitetura de dados pode ser estruturada para transformar grandes volumes de dados brutos em informações confiáveis e prontas para consumo.

## 🛠️ Tecnologias e conceitos

* **Python**
* **PySpark**
* **SQL**
* **Databricks**
* **Data Lake / Lakehouse**
* **Arquitetura Medalhão**

  * 🥉 **Bronze:** ingestão e armazenamento dos dados brutos
  * 🥈 **Silver:** tratamento, padronização e aplicação de regras de qualidade
  * 🥇 **Gold:** dados refinados e estruturados para análise
* **Data Pipelines**
* **Data Quality**
* **Data Governance**
* **Data Lineage**
* **Quarentena de dados**
* **Agentes de IA para análise de dados**

## 📊 Dados

O projeto utiliza dados públicos disponibilizados pela **ANAC**, incluindo registros de voos e dados de referência relacionados à aviação brasileira.

Os dados foram utilizados para construir uma estrutura que permite investigar questões como:

* Quais aeroportos apresentam maior concentração de atrasos?
* Quais períodos possuem maior ocorrência de cancelamentos?
* Como se comporta a pontualidade dos voos?
* Quais padrões podem ser identificados nos dados de aviação?

## 🏗️ Arquitetura

O projeto utiliza a **Arquitetura Medalhão**, organizando os dados em diferentes níveis de processamento:

**Bronze → Silver → Gold**

A camada Bronze mantém os dados em seu estado original, garantindo maior rastreabilidade. Na Silver, os dados passam por processos de tratamento e validação. Por fim, a Gold organiza os dados de forma estruturada para responder às perguntas de negócio e facilitar análises.

Também foram explorados mecanismos de **qualidade e governança**, incluindo regras de validação, identificação de dados problemáticos e rastreabilidade do fluxo dos dados.

## 🤖 IA aplicada aos dados

Uma das partes que mais me chamou atenção durante a imersão foi a utilização de **agentes de IA para interação com os dados**.

A partir de perguntas em linguagem natural, foi possível explorar os dados e obter respostas sem depender exclusivamente da construção manual de consultas, mostrando algumas das possibilidades de integração entre **Engenharia de Dados e Inteligência Artificial**.

## 📚 Sobre o projeto

Este projeto foi desenvolvido como parte da minha participação na **Imersão Engenharia de Dados da Alura**. A experiência foi uma oportunidade de colocar em prática conceitos que venho estudando e, principalmente, de ter uma visão mais concreta de como diferentes componentes de uma arquitetura de dados se conectam em um fluxo completo.

Foi também meu primeiro contato mais aprofundado com ferramentas como **Databricks e PySpark**, despertando ainda mais meu interesse pela área de **Dados e Inteligência Artificial**.

## 🔗 Referências

* **Dados:** Agência Nacional de Aviação Civil (ANAC)
* **Imersão:** Alura — Imersão Engenharia de Dados, setembro/2026

> Projeto desenvolvido para fins educacionais durante a Imersão Engenharia de Dados da Alura.
