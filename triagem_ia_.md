# Plano de Experimento – Automação da Triagem de Chamados de TI com IA

## 1. Identificação básica

### 1.1 Título do experimento
Avaliação Comparativa da Triagem de Chamados de TI Realizada por Atendente Humano versus Modelo de IA

### 1.2 ID / código
EXP-TI-TRIAGEM-IA-2024-01

### 1.3 Versão do documento e histórico de revisão
- Versão: v1.0  
- Histórico:
  - v1.0 – Criação do documento (24/11)

### 1.4 Datas
- Data de criação: 24/11  
- Última atualização: 24/11  

### 1.5 Autores
- Miguel Vieira – Discente  

### 1.6 Responsável principal
Miguel Vieira

### 1.7 Projeto relacionado
Projeto acadêmico da disciplina Medição e Experimentação de Software.

---

## 2. Contexto e problema

O processo atual de triagem dos chamados internos de TI ocorre manualmente. Esse fluxo é demorado, suscetível a erros e consome tempo de profissionais da área. Surge a oportunidade de analisar se um modelo de IA pode reduzir tempo, custo e esforço humano mantendo precisão adequada.

O contexto técnico envolve um conjunto de 30 chamados reais (texto curto), um atendente humano treinado e o uso do ChatGPT para simular triagem automática.

Pesquisas anteriores indicam que modelos de NLP podem classificar textos com alta precisão e melhorar a eficiência de processos repetitivos, especialmente em service desk.

---

## 3. Objetivos e questões (GQM)

### 3.1 Objetivo geral
Analisar o processo de triagem de chamados de TI com o propósito de avaliar desempenho, acurácia e custo, sob a perspectiva de gestores de TI, no contexto de uma simulação comparativa entre humano e IA.

### 3.2 Objetivos específicos
- O1: Comparar tempo médio entre triagem humana e triagem por IA.  
- O2: Avaliar acurácia de classificação da IA.  
- O3: Estimar redução de custo operacional.  
- O4: Avaliar redução da carga de trabalho do atendente.

### 3.3 Questões de pesquisa
- Q1: A IA reduz o tempo médio de triagem?  
- Q2: A IA mantém ou melhora a acurácia?  
- Q3: O custo total do processo é reduzido com IA?  
- Q4: A carga de trabalho humano é reduzida?

### 3.4 Métricas
- M1: Tempo por solicitação humana (s)  
- M2: Tempo total humano (min)  
- M3: Tempo por solicitação IA (s)  
- M4: Tempo total IA (min)  
- M5: Acurácia da IA (%)  
- M6: Taxa de erro (%)  
- M7: Custo hora humano (R$)  
- M8: Custo total humano (R$)  
- M9: Custo por solicitação IA (R$)  
- M10: Custo mensal IA (R$)  
- M11: Carga de trabalho humano (%)  
- M12: Redução de carga (%)  

---

## 4. Escopo e contexto do experimento

### 4.1 Escopo incluído
- Leitura da descrição do chamado  
- Classificação da natureza do problema  
- Identificação da equipe/responsável  
- Geração de resposta padrão  
- Registro em planilha  
- Comparação entre humano e IA  

### 4.2 Escopo excluído
- Solução técnica do chamado  
- Análise de tickets complexos  
- Interações com usuários finais  
- Suporte avançado  

### 4.3 Premissas
- Conjunto de mensagens representa a realidade de TI interna.  
- O modelo de IA permanece estável.  
- O operador humano está disponível durante todo o experimento.

### 4.4 Restrições
- Apenas um operador humano.  
- Execução dentro do período da disciplina.  
- Amostra limitada a 30 mensagens.

### 4.5 Limitações previstas
- Baixa generalização devido à amostra pequena.  
- Somente um atendente testado.  
- Ambiente simulado e não produtivo.

---

## 5. Stakeholders e impacto esperado

### 5.1 Stakeholders
- Atendentes de TI  
- Gestores de TI  
- Usuários internos  
- Professor/orientador

### 5.2 Interesses
- Gestores: redução de custo e tempo  
- Atendentes: diminuição de carga repetitiva  
- Usuários: maior rapidez de resposta  
- Equipe acadêmica: validade do experimento

### 5.3 Impactos
- Possível adoção futura da automação  
- Redução de retrabalho  
- Melhoria no SLA  
- Dependência tecnológica crescente

---

## 6. Riscos, premissas e critérios de sucesso

### 6.1 Riscos
- Falha de acesso ao ChatGPT  
- Interpretação ambígua das mensagens  
- Fadiga do operador humano  
- Limites de tempo da disciplina

### 6.2 Critérios de sucesso
- IA reduz tempo ≥ 80% em relação ao humano  
- Acurácia ≥ 85%  
- Redução perceptível de esforço humano  
- Dados coletados sem inconsistências  

---

## 7. Planejamento da execução

### 7.1 Materiais necessários
- Conjunto de 30 mensagens reais  
- Cronômetro digital  
- Planilha de registro  
- Acesso ao ChatGPT  
- Procedimento padronizado de classificação

### 7.2 Procedimento experimental
1. Apresentar o conjunto de mensagens ao operador humano.  
2. Registrar tempo total e individual de cada triagem.  
3. Repetir processo utilizando o modelo de IA.  
4. Registrar classificações em planilha.  
5. Comparar resultados com gabarito previamente definido.  
6. Calcular métricas de tempo, acurácia, custo e carga.

### 7.3 Tamanho da amostra
30 mensagens representando categorias recorrentes na TI interna.

---

## 8. Instrumentação

- Planilha Google Sheets para registrar tempos e classificações.  
- Cronômetro embutido (Sheets script ou manual).  
- Prompt fixo para interação com IA.  
- Especificação clara das categorias de classificação.  

---

## 9. Coleta de dados

Os dados serão coletados manualmente e automaticamente (no caso do tempo medido pela IA). Todos os tempos serão registrados em formato de segundos e posteriormente agregados.

---

## 10. Análise de dados

- Análise descritiva (médias, desvios, proporções).  
- Comparações diretas entre métodos.  
- Cálculo de diferença percentual entre tempos e custos.  
- Verificação de concordância com gabarito (acurácia).  

---

## 11. Considerações éticas

Os dados utilizados são internos, não contêm informações sensíveis e não expõem usuários. O operador humano participa voluntariamente.

---

## 12. Cronograma

| Etapa | Data | Status |
|------|------|--------|
| Preparação das mensagens | 24/11 | Concluído |
| Execução com humano | 25/11 | Pendente |
| Execução com IA | 25/11 | Pendente |
| Análise dos resultados | 26/11 | Pendente |
| Relatório final | 27/11 | Pendente |

---

## 13. Ameaças à validade

### 13.1 Introdução
A validade do experimento depende de reduzir vieses que possam comprometer causalidade, precisão das medidas e generalização dos resultados.

---

### 13.2 Validade interna

A validade interna pode ser afetada por causas alternativas para os efeitos observados.

- **History:** eventos externos podem alterar o desempenho do humano ou da IA.  
  **Mitigação:** executar o experimento em sessão única e ambiente controlado.

- **Maturation:** o operador pode cansar ao longo da tarefa.  
  **Mitigação:** permitir pausas, manter número reduzido de mensagens.

- **Selection:** usar operadores distintos poderia criar diferenças indevidas.  
  **Mitigação:** utilizar apenas um operador humano e o mesmo modelo de IA em todas as rodadas.

- **Instrumentation:** variações na ferramenta ou instruções podem distorcer resultados.  
  **Mitigação:** planilha padronizada, prompt fixo e procedimento repetível.

---

### 13.3 Validade de constructo

Avalia se as métricas representam corretamente os conceitos.

O tempo representa diretamente esforço operacional.  
A acurácia é comparada contra um gabarito, reduzindo ambiguidades sobre o que é “classificação correta”.  
Para evitar múltiplas interpretações, todas as categorias de solicitação serão definidas de forma objetiva antes da coleta.  
A carga de trabalho será inferida pelo tempo relativo e esforço manual, alinhado a métricas comuns em service desk.  
A coleta será padronizada para garantir consistência.

---

### 13.4 Validade externa

Refere-se à capacidade de generalização dos resultados.

O experimento pode ser generalizado para contextos semelhantes, como equipes internas de TI com chamados rotineiros.  
A generalização é limitada para ambientes com grande volume, suporte externo, SLAs rígidos ou alta complexidade técnica.  
Diferenças em ferramentas, perfis dos usuários ou maturidade de processos podem afetar a replicação dos resultados.

---

### 13.5 Resumo das ameaças e estratégias (tabela)

| Ameaça | Tipo | Impacto | Mitigação |
|--------|------|---------|-----------|
| History | Interna | Alterar desempenho por fatores externos | Sessão única em ambiente controlado |
| Maturation | Interna | Cansaço do operador humano | Pausas e amostra pequena |
| Selection | Interna | Diferenças entre operadores | Usar um operador e uma IA fixa |
| Instrumentation | Interna | Variação não planejada na coleta | Procedimentos, prompts e planilhas padronizadas |
| Constructo inadequado | Constructo | Medidas não representarem conceitos | Definição clara de categorias e métricas |
| Baixa generalização | Externa | Resultados não se aplicarem a outros cenários | Limitar generalização a contextos similares |

---


