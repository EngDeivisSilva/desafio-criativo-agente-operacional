# Agente de Atendimento Operacional | Logística Florestal

**Desafio Criativo — Projetando o Prompt de um Agente de Atendimento ao Cliente | DIO**

## Sobre o projeto

Este projeto apresenta o desenvolvimento de um Agente de Atendimento Operacional para uma empresa de transporte e logística florestal, com atuação simulada por meio de um canal de atendimento via WhatsApp corporativo.

A proposta é utilizar Engenharia de Prompt para estruturar um agente capaz de interpretar solicitações operacionais, consultar informações de uma base de dados e fornecer respostas objetivas, respeitando regras de negócio, limites de autonomia e critérios de segurança.

O cenário foi inspirado em rotinas de um Centro de Controle Operacional (CCO), considerando situações comuns na gestão de transporte florestal.

## Objetivo

Desenvolver um prompt estruturado para orientar o comportamento de um agente de IA no atendimento de motoristas, encarregados de campo e equipes operacionais, facilitando o acesso às informações e contribuindo para a agilidade da comunicação operacional.

## Funcionalidades propostas

- Consulta de viagens programadas por veículo, motorista, composição ou frente operacional.
- Identificação de horários previstos e locais de carregamento.
- Consulta de status das viagens, conforme os registros disponíveis.
- Tratamento de múltiplas viagens realizadas pelo mesmo veículo no mesmo dia.
- Validação das datas e dos critérios de consulta.
- Orientação inicial em situações de atrasos, indisponibilidade de veículos e ocorrências operacionais.
- Encaminhamento para atendimento humano quando a solicitação ultrapassar os limites de atuação do agente.

## Estrutura do projeto

| Arquivo | Descrição |
|---|---|
| `prompt-agente-atendimento-operacional.md` | Prompt principal, contendo contexto, instruções, regras de consulta e limites de atuação do agente. |
| `base_dados_agente_operacional.xlsx` | Base de dados fictícia utilizada para simular consultas de programação e status de viagens. |

## Tecnologias e recursos utilizados

- **Inteligência Artificial Generativa:** interpretação de solicitações e geração de respostas.
- **Engenharia de Prompt:** definição de contexto, instruções, regras e restrições de comportamento.
- **Markdown (.md):** documentação e estruturação do prompt.
- **Microsoft Excel (.xlsx):** organização da base de dados utilizada nos testes.

## Regras e limites de atuação

O agente foi projetado considerando princípios importantes para aplicações em ambientes operacionais:

- Utilizar exclusivamente os dados disponíveis na base fornecida.
- Não inventar informações ou presumir dados ausentes.
- Verificar todos os registros correspondentes aos critérios da consulta.
- Não realizar alterações na programação ou na base de dados.
- Não executar decisões que dependam de autorização da liderança.
- Encaminhar situações críticas ou fora de sua autonomia para atendimento humano.

## Como testar

1. Disponibilize o arquivo `base_dados_agente_operacional.xlsx` no ambiente de execução do agente.
2. Utilize o conteúdo de `prompt-agente-atendimento-operacional.md` como instrução principal.
3. Realize consultas simuladas sobre viagens, veículos, motoristas, datas e ocorrências.
4. Verifique se as respostas respeitam os registros da base e as regras definidas no prompt.

**Observação:** os arquivos deste repositório constituem os materiais do projeto. A presença da planilha no GitHub não estabelece, por si só, uma integração automática com o agente. A base deve ser disponibilizada no ambiente de execução.

## Considerações finais

O projeto demonstra como a Engenharia de Prompt pode ser aplicada a um contexto operacional realista, estruturando um agente de IA com foco em atendimento, consulta de informações, padronização de respostas e respeito aos limites de autonomia.

A proposta também evidencia o potencial de aplicação da Inteligência Artificial Generativa como apoio à comunicação e à eficiência dos processos logísticos.
