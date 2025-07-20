
# Evasão de Consultas Médicas - Análise de Dados

Bem-vindo ao repositório do projeto de análise de evasão de consultas médicas! :hospital:

Este projeto tem como objetivo analisar os fatores que influenciam a ausência dos pacientes às consultas agendadas no sistema público de saúde de Vitória-ES, utilizando o conjunto de dados `KaggleV2-May-2016.csv`.

Autores: Matheus Moura, Matheus Oliveira e Matheus Lopes

## Sobre o Projeto

O dataset contém informações sobre consultas médicas agendadas, incluindo variáveis como:
- `PatientId`: Identificador do paciente
- `AppointmentID`: Identificador da consulta
- `Gender`: Gênero do paciente
- `ScheduledDay`: Data/hora do agendamento
- `AppointmentDay`: Data da consulta
- `Age`: Idade do paciente
- `Neighbourhood`: Bairro de residência
- `Scholarship`: Indica se o paciente possui bolsa assistencial (1) ou não (0)
- `Hipertension`, `Diabetes`, `Alcoholism`, `Handcap`: Condições de saúde (1 para sim, 0 para não)
- `SMS_received`: Se o paciente recebeu SMS de lembrete (1) ou não (0)
- `No-show`: Se o paciente faltou à consulta (`Yes`) ou compareceu (`No`)

O objetivo é identificar padrões e fatores associados à evasão, utilizando técnicas de análise exploratória, visualização e modelos preditivos.

## Como executar

1. Instale as dependências:
   ```commandline
   pip install -r requirements.txt
   ```
2. Execute o notebook `main.ipynb` para acompanhar toda a análise, desde a exploração dos dados até os resultados finais.

## Estrutura do Projeto

- `KaggleV2-May-2016.csv`: Base de dados principal
- `main.ipynb`: Notebook com toda a análise e visualizações
- `README.md`: Este arquivo
- `requirements.txt`: Bibliotecas necessárias

## Metodologia

O projeto segue as etapas:
1. Carregamento e limpeza dos dados
2. Análise exploratória (distribuições, correlações, visualizações)
3. Modelagem preditiva para identificar fatores relevantes
4. Discussão dos resultados e possíveis recomendações

## Referências

- [No-show appointments: Kaggle dataset](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
- Pacheco, André GC. Exemplos e metodologia de análise de dados em saúde pública

## Contato

Para dúvidas, sugestões ou contribuições, entre em contato com os autores ou abra uma issue.

---

Projeto desenvolvido para a disciplina de Inteligência Computacional Aplicada à Saúde (UFES, 2025).

