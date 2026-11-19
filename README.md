# Agente de Atendimento Operacional | Logística Florestal

<p align="center">
  <img src="capa-agente-atendimento-operacional%20(2).jpg"
       alt="Agente de Atendimento Operacional"
       width="100%"
       height="350">
</p>

**Desafio Criativo — Projetando o Prompt de um Agente de Atendimento ao Cliente | DIO**

## 🎯 Visão geral

Este projeto apresenta a concepção de um agente de Inteligência Artificial voltado ao atendimento operacional de uma empresa de transporte e logística florestal.

O agente foi projetado para atuar como um canal de consulta via WhatsApp corporativo, auxiliando motoristas, encarregados de campo e equipes operacionais na obtenção de informações sobre viagens programadas e situações da operação.

## 💡 Objetivo do projeto

Desenvolver um prompt estruturado para orientar o comportamento de um agente de IA em um cenário operacional realista, considerando a necessidade de respostas rápidas, consistentes e fundamentadas em uma base de dados.

A proposta busca demonstrar como a Engenharia de Prompt pode ser aplicada para apoiar processos operacionais, reduzir consultas repetitivas e facilitar o acesso às informações.

## ⚙️ Funcionalidades propostas

- Consulta de viagens programadas por motorista, veículo ou composição.
- Identificação de horários, locais de carregamento e frentes de operação.
- Consulta da situação das viagens conforme os dados disponíveis.
- Orientação inicial sobre atrasos, indisponibilidade de veículos e problemas nas rotas.
- Coleta de informações sobre ocorrências operacionais.
- Encaminhamento de situações que exigem avaliação ou decisão humana.

## 📁 Estrutura do projeto

```text
desafio-criativo-agente-operacional/
│
├── README.md
├── prompt-agente-atendimento-operacional.md
├── base_dados_agente_operacional.xlsx
└── capa-agente-atendimento-operacional (2).jpg
```

## 🛠️ Tecnologias e recursos

- **Inteligência Artificial generativa:** interpretação de solicitações e geração de respostas.
- **Engenharia de Prompt:** definição de instruções, regras e limites de atuação do agente.
- **Microsoft Excel:** estruturação da base de dados utilizada nas consultas.
- **GitHub:** armazenamento e documentação do projeto.

## 🔒 Regras e limitações

O agente foi projetado considerando princípios de confiabilidade e controle operacional:

- Utilizar a base de dados disponibilizada como fonte das consultas.
- Não inventar informações ou presumir dados ausentes.
- Não misturar registros de datas diferentes sem solicitação.
- Não alterar programações ou tomar decisões de responsabilidade da liderança.
- Encaminhar situações críticas ou que excedam sua autonomia para avaliação humana.

**Importante:** a base de dados utilizada no projeto contém informações fictícias, criadas exclusivamente para demonstração e testes. O projeto não possui integração automatizada com sistemas corporativos ou plataformas de transporte.

## 🧪 Testes e validação

Foram considerados cenários de consulta para avaliar o comportamento do agente, incluindo:

- Consulta de viagens por veículo.
- Consulta de programação por motorista.
- Verificação de múltiplas viagens para o mesmo veículo.
- Solicitações envolvendo datas diferentes.
- Consultas sobre informações inexistentes na base.
- Tratamento de ocorrências e situações que exigem encaminhamento humano.

## 📌 Considerações finais

O projeto demonstra uma aplicação prática de Engenharia de Prompt em um contexto de logística florestal, aproximando Inteligência Artificial das necessidades de atendimento e suporte operacional.

A proposta reforça a importância de estruturar instruções claras, estabelecer limites de autonomia e utilizar dados como fundamento para respostas confiáveis.

---

**Projeto desenvolvido para o desafio da DIO — Projetando o Prompt de um Agente de Atendimento ao Cliente.**
