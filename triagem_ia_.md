# Automação da Triagem de Chamados de TI com IA  
## Documento do Escopo + GQM + Métricas (Versão 100% Conforme Requisitos)

---

# 1. Identificação do Projeto
**Título:** Automatização da triagem de chamados internos de TI usando IA  
**Autor:** [Miguel Vieira]  
**Data:** [24/11]  
**Disciplina:** [Medição e Experimentação de Software]

---

# 2. Descrição Geral do Experimento
O experimento avalia se um sistema de IA consegue substituir o atendente humano na triagem inicial de chamados internos de TI, realizando classificação automática, resposta inicial e encaminhamento.

---

# 3. Escopo do Experimento (Template)

## 3.1 Objetivo Geral
Verificar se a IA reduz tempo, custo e erros na triagem de chamados internos.

## 3.2 O que será automatizado
- Leitura da mensagem  
- Classificação da solicitação  
- Definição do responsável  
- Resposta inicial ao usuário  
- Registro em planilha

## 3.3 O que não será automatizado
- Solução técnica dos chamados  
- Solicitações complexas

## 3.4 Entradas
- 30 mensagens de chamados reais

## 3.5 Saídas
- Tabela de triagem humana  
- Tabela de triagem IA  
- Comparação de tempo, custo e acurácia

## 3.6 Ferramentas
- Google Sheets  
- Cronômetro  
- ChatGPT  

## 3.7 Participantes
- 1 operador humano  
- Modelo de IA

## 3.8 Variáveis
### Dependentes  
- Tempo por triagem  
- Acurácia  
- Custo  
- Carga de trabalho

## 3.9 Tabela de Variáveis

| Tipo | Variável | Descrição | Unidade/Tipo |
|------|----------|------------|--------------|
| Dependente | Tempo por triagem | Tempo para analisar um chamado | segundos |
| Dependente | Acurácia | Porcentagem de classificações corretas | % |
| Dependente | Custo | Custo operacional por triagem | R$ |
| Dependente | Carga de trabalho | Percentual de esforço humano | % |
| Independente | Tipo de solicitação | Categoria do chamado (acesso, erro, dúvida) | Qualitativa |
| Independente | Volume de solicitações | Quantidade de chamados processados | Quantitativa |
| Independente | Ferramenta de IA | Modelo utilizado | Qualitativa |


### Independentes  
- Tipo da solicitação  
- Volume  
- Ferramenta de IA utilizada  

---

# 4. Passo a Passo do Experimento

## Rodada 1 – Humana
1. Ler cada mensagem  
2. Classificar  
3. Definir responsável  
4. Responder  
5. Registrar  
6. Cronometrar  

## Rodada 2 – IA
1. Inserir mensagem no chatbot  
2. IA classifica  
3. IA responde  
4. Registrar automaticamente

# 4.3 Fatores e Tratamentos

| Fator | Tratamentos |
|-------|-------------|
| Tipo de atendente | Humano / IA |
| Tipo de solicitação | Acesso / Erro / Dúvida / Outro |
| Volume de chamados | 10 / 30 / 100 |
| Tipo de resposta | Manual / Automática |

## 4.4 Combinações Experimentais

| Combinação | Tipo de atendente | Volume | Tipo de solicitação | Tipo de resposta |
|------------|------------------|--------|---------------------|------------------|
| C1 | Humano | 30 | Variado | Manual |
| C2 | IA | 30 | Variado | Automática |
| C3 | IA | 100 | Variado | Automática |
| C4 | Humano | 10 | Variado | Manual |
| C5 | IA | 10 | Variado | Automática |


## 4.5 Fluxograma Operacional do Experimento

INÍCIO  
  |  
  v  
Coleta das 30 mensagens de chamados reais  
  |  
  v  
Classificação em duas abordagens:  
---------------------------------------  
|                                     |  
v                                     v  
TRIAGEM HUMANA                        TRIAGEM IA  
Stakeholder: atendente humano         Stakeholder: modelo de IA  
Instrumentos: Google Sheets,          Instrumentos: ChatGPT, prompts  
Cronômetro                           Scripts de automação  
Variáveis resultantes:                Variáveis resultantes:  
 - Tempo humano por solicitação        - Tempo IA por solicitação  
 - Custo horário humano                - Custo IA por operação  
 - Decisão humana                      - Decisão automatizada  
---------------------------------------  
  |  
  v  
Registro dos resultados em planilha  
Métricas avaliadas: M1–M18  
(tempo, custo, acurácia, esforço, volume)  
  |  
  v  
Comparação dos resultados  
Entre:  
- variáveis dependentes (resultado)  
- variáveis independentes (fatores)  
  |  
  v  
Avaliação estatística e conclusões  
  |  
  v  
FIM


---

# 5. Modelo GQM (com 4 objetivos, 3 perguntas cada, mínimo 2 métricas cada)

| **Objetivo** | **Perguntas** | **Métricas Associadas** |
|--------------|---------------|--------------------------|
| **O1 – Reduzir o tempo de triagem** | P1.1 Qual é o tempo médio humano por solicitação? | M1, M2 |
| | P1.2 Qual é o tempo médio da IA por solicitação? | M3, M4 |
| | P1.3 Qual a redução percentual de tempo? | M5, M6 |
| **O2 – Aumentar a acurácia da classificação** | P2.1 Quantas classificações da IA estão corretas? | M7, M8 |
| | P2.2 Quantas classificações da IA estão incorretas? | M8, M9 |
| | P2.3 A IA é consistente nas classificações? | M10, M7 |
| **O3 – Reduzir custos operacionais** | P3.1 Qual é o custo atual da triagem humana? | M11, M12 |
| | P3.2 Qual é o custo para operar a IA? | M13, M14 |
| | P3.3 Qual é a economia total gerada? | M12, M14 |
| **O4 – Reduzir necessidade de mão de obra** | P4.1 Quantos atendentes são necessários hoje? | M15, M18 |
| | P4.2 Quantos atendentes serão necessários após IA? | M16, M18 |
| | P4.3 Qual a redução percentual da carga de trabalho? | M17, M18 |

---

# 6. Tabela Completa de Métricas (18 métricas)

| **Métrica** | **Descrição** | **Unidade** |
|-------------|----------------|-------------|
| **M1** | Tempo por solicitação humana | segundos |
| **M2** | Tempo total humano | minutos |
| **M3** | Tempo por solicitação IA | segundos |
| **M4** | Tempo total IA | minutos |
| **M5** | Diferença percentual de tempo | % |
| **M6** | Economia absoluta de tempo | minutos |
| **M7** | Taxa de acerto IA | % |
| **M8** | Número de acertos ou erros | contagem |
| **M9** | Taxa de erro IA | % |
| **M10** | Variabilidade da classificação IA | índice |
| **M11** | Custo/hora do atendente humano | R$ |
| **M12** | Custo total da triagem humana | R$ |
| **M13** | Custo IA por solicitação | R$ |
| **M14** | Custo mensal da IA | R$ |
| **M15** | Número de atendentes atuais | pessoas |
| **M16** | Número necessário após IA | pessoas |
| **M17** | Redução da carga de trabalho | % |
| **M18** | Volume de solicitações automatizadas | % |

---

# 7. Conclusão Esperada
A IA deve reduzir o tempo de triagem em **90–98%**, diminuir custos, reduzir necessidade de atendentes humanos, aumentar velocidade de resposta e manter ou melhorar a acurácia.

---

