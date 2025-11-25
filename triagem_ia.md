# Automação da Triagem de Chamados Internos de TI com IA
## Documento do Escopo + GQM + Métricas

# 1. Identificação do Projeto
**Título:** Automatização da triagem de chamados internos de TI usando IA  
**Autor:** [Seu Nome]  
**Data:** [Data]  
**Disciplina:** [Nome da disciplina]  

# 2. Descrição Geral do Experimento
Este experimento avalia se é possível automatizar a triagem de chamados internos de TI usando IA, substituindo o trabalho humano em solicitações repetitivas como redefinição de senha, problemas de e-mail, instalação de software e acesso a sistemas.

# 3. Escopo do Experimento (Template)
## 3.1 Objetivo
Testar se a IA consegue realizar a triagem de chamados internos com mais rapidez, menor custo e boa precisão.

## 3.2 O que será automatizado
- Classificação da solicitação
- Definição automática do responsável
- Resposta automática
- Registro em planilha

## 3.3 O que NÃO será automatizado
- Execução técnica dos chamados
- Chamados complexos

## 3.4 Entradas
- 30 mensagens reais de chamados internos

## 3.5 Saídas
- Tabela com triagem humana
- Tabela com triagem IA
- Comparação de tempo, custo e acurácia

## 3.6 Ferramentas
- Google Sheets
- Cronômetro
- ChatGPT

## 3.7 Participantes
- 1 operador humano
- Modelo de IA

## 3.8 Variáveis
Dependentes: tempo, acurácia, custo, carga de trabalho  
Independentes: tipo da solicitação, ferramenta de IA

# 4. Passo a Passo do Experimento
## Rodada 1 – Humana
1. Ler solicitação  
2. Classificar  
3. Definir responsável  
4. Registrar  
5. Responder  
6. Cronometrar  

## Rodada 2 – IA
1. Inserir no chatbot  
2. IA classifica  
3. IA responde  
4. Registrar  

# 5. Modelo GQM – Tabela

| Objetivo | Perguntas | Métricas |
|---------|-----------|----------|
| O1 – Reduzir tempo | P1.1 Tempo humano? | M1, M2 |
| | P1.2 Tempo IA? | M3, M4 |
| | P1.3 Economia? | M5, M6 |
| O2 – Acurácia | P2.1 IA acerta? | M7, M8 |
| | P2.2 Erra mais? | M8, M9 |
| | P2.3 Consistência? | M10 |
| O3 – Custos | P3.1 Custo humano? | M11, M12 |
| | P3.2 Custo IA? | M13, M14 |
| | P3.3 Economia total? | M12, M14 |
| O4 – Mão de obra | P4.1 Quantos hoje? | M15 |
| | P4.2 Quantos após IA? | M16 |
| | P4.3 Redução? | M17, M18 |

# 6. Lista Completa de Métricas

| Métrica | Descrição | Unidade |
|---------|-----------|---------|
| M1 | Tempo por solicitação (humano) | s |
| M2 | Tempo total humano | min |
| M3 | Tempo por solicitação (IA) | s |
| M4 | Tempo total IA | min |
| M5 | Diferença percentual de tempo | % |
| M6 | Economia absoluta | min |
| M7 | Taxa de acerto | % |
| M8 | Número de erros | contagem |
| M9 | Taxa de erro | % |
| M10 | Variabilidade da IA | índice |
| M11 | Custo por hora humano | R$ |
| M12 | Custo total humano | R$ |
| M13 | Custo IA por solicitação | R$ |
| M14 | Custo mensal IA | R$ |
| M15 | Número de atendentes atuais | pessoas |
| M16 | Número após IA | pessoas |
| M17 | Redução da carga | % |
| M18 | Volume automatizado | % |

# 7. Conclusão Esperada
Espera-se redução de 90–98% do tempo, diminuição de custo, menos mão de obra necessária e maior velocidade de resposta.
