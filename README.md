# 🚀 Caderno Temático Inteligente: Engenharia Reversa do Edital Banco do Brasil (Agente de Tecnologia)
### Projeto Prático - Desafio DIO (Aprendizagem Ativa com IA)

---

## 📝 Contexto e Objetivos

Este repositório foi criado para documentar o desenvolvimento de um Caderno Temático Inteligente utilizando o **NotebookLM** da Google como ferramenta de aprendizagem ativa. 

O foco deste estudo é a análise estratégica do material oficial da **Seleção Externa do Banco do Brasil de 2022 para o cargo de Agente de Tecnologia**. O objetivo é utilizar a Inteligência Artificial para destrinchar as regras do exame, analisar o peso das disciplinas e consolidar o conteúdo programático avaliado.

### 🎯 Objetivos de Estudo:
* **Mapeamento Estratégico:** Compreender a divisão de pontos e critérios de avaliação das provas objetivas e discursivas.
* **Priorização Baseada em Dados:** Identificar quais disciplinas e assuntos oferecem o melhor custo-benefício (maior peso e volume de questões) para otimizar o cronograma de estudos.
* **Consolidação de Conceitos:** Estruturar um glossário e resumos focados nos pilares do edital, como Mercado Financeiro e Tecnologia da Informação.

---

## 📚 Curadoria de Fontes

Para alimentar a base de conhecimento do NotebookLM, foi utilizado o seguinte documento oficial:

* 📄 **Material Oficial de Seleção Externa BB (2022) - Agente de Tecnologia:** Arquivo completo detalhando as regras do exame, distribuição de questões de conhecimentos básicos (Língua Portuguesa, Língua Inglesa, Matemática) e específicos (Tecnologia da Informação), além de textos de apoio da redação e questões objetivas aplicadas (Mercado Financeiro, Empreendedorismo Social e Evolução do Dinheiro). Também foram utilizados vídeo-aulas para maior riqueza dos maiteriais.

[Edital 2022](https://www.bb.com.br/docs/portal/dipes/Edital-de-Abertura-de-Selecao-Externa-2022-01.pdf)
[Provas 2022](https://www.cesgranrio.org.br/concurso/banco-do-brasil-bb-01-2022/)
[Vídeos Português](https://www.youtube.com/channel/UCBRXmX3weo-Ffsd1qAaeEuw)
[Vídeos Inglês](https://www.youtube.com/channel/UCT-sOsVY16pr5P_kLaRxjKw)
[Vídeos Matemática](https://www.youtube.com/channel/UCaKcls8S67BP8E-XKBSKZQg)
[Vídeos Atualidades no Mercado Financeiro](https://www.youtube.com/channel/UCoYnTN6fiIBzS4w7zG_ernw)
[Vídeos Probabilidade e Estatística](https://www.youtube.com/channel/UChJ6mxNyukoIeWR9IWV7xVQ)
[Vídeos Conhecimentos Bancários](https://www.youtube.com/channel/UCoYnTN6fiIBzS4w7zG_ernw)
[Vídeos Tecnologia da Informação](https://www.youtube.com/channel/UCps7BWEsYAZfdiMbnchTXfQ)
[Vídeos Redação](https://www.youtube.com/channel/UCwSxSJqGpSRpEsq5-YUbM8g)


---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

A engenharia de prompts foi aplicada para realizar uma verdadeira "engenharia reversa" do processo seletivo, extraindo dados frios e transformando-os em direcionamento estratégico.

### 🛠️ Prompts de Análise e Direcionamento Utilizados

* **Prompt de Extração de Métricas:**
  > *"Como é dividida a pontuação das provas objetivas do Banco do Brasil?"*
  * **Intenção:** Forçar a IA a ler as tabelas de pontuação do edital para separar o peso dos Conhecimentos Básicos em relação aos Conhecimentos Específicos (TI), mapeando onde a aprovação é decidida.

* **Prompt de Planejamento Estratégico (Custo-Benefício):**
  > *"Quais matérias e assuntos eu deveria priorizar com base na quantidade de questões e nas pontuações de cada disciplina?"*
  * **Intenção:** Fazer o NotebookLM atuar como um consultor de estudos, cruzando o número de questões com o peso de cada matéria para ditar quais disciplinas devem ocupar a maior parte do cronograma.

### 🩹 Cicatrizes e Lições Aprendidas (Troubleshooting)
* **O Desafio:** Documentos de concursos são extensos e misturam regras jurídicas, cronogramas e conteúdos. Perguntas abertas como *"O que eu preciso estudar?"* faziam a IA listar tudo com o mesmo nível de importância, gerando sobrecarga de informação.
* **A Solução:** O uso de prompts ultraespecíficos e delimitados por métricas (como quantidade de questões e pontuação) obrigou a IA a ignorar a burocracia do texto e focar puramente na matriz de pontos, entregando uma ordem de prioridade técnica para os estudos.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 📝 Resumo Estruturado do Exame

#### 1. Estrutura das Provas Objetivas e Redação
* **Divisão de Blocos:** Análise da distribuição de questões entre a base de conhecimentos gerais (Português, Inglês e Matemática) e o bloco focado em Tecnologia da Informação.
* **Prova Discursiva (Redação):** Foco em critérios de qualidade no atendimento dentro de instituições financeiras, utilizando os textos de apoio para entender a linha de argumentação exigida pela banca.

#### 2. Tópicos Interdisciplinares Avaliados
* **Conhecimentos Bancários e Sociais:** Estudo focado nos conceitos de mercado financeiro, evolução histórica do dinheiro e tópicos contemporâneos como empreendedorismo social.

### 📒 Glossário de Conceitos Chave

| Termo / Conceito | Contexto no Exame de Agente de TI (2022) |
| :--- | :--- |
| **Tecnologia da Informação** | Bloco de conhecimentos específicos com maior peso na pontuação final do candidato. |
| **Qualidade no Atendimento** | Tema central da prova de redação voltada ao cenário de instituições financeiras. |
| **Mercado Financeiro** | Conjunto de questões teóricas abordando a evolução do dinheiro e produtos bancários. |
| **Empreendedorismo Social** | Conceito explorado nas questões objetivas para avaliar a compreensão de impacto socioambiental no setor financeiro. |

### 🔄 Prompts Reutilizáveis para Revisão

1. 📥 *"Gere um simulado com 5 questões inéditas no formato de múltipla escolha sobre o tópico de Mercado Financeiro, simulando o nível de dificuldade do documento base."*
2. 📥 *"Com base nos critérios da redação contidos na fonte, liste 3 argumentos técnicos que sustentam a importância da qualidade no atendimento bancário digital."*
