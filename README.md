# 🏨 Gestão de Caixa e Sazonalidade Hoteleira com NotebookLM & AI Skills 📊

![NotebookLM](https://img.shields.io/badge/AI-NotebookLM-blue?style=for-the-badge&logo=google)
![Skywork](https://img.shields.io/badge/Agent-Skywork--MCP-purple?style=for-the-badge)
![DIO](https://img.shields.io/badge/Curso-DIO-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)

Este repositório contém o projeto prático desenvolvido para o desafio de projeto **"Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM"** da plataforma DIO (Digital Innovation One). O objetivo é construir um "segundo cérebro" e um agente autônomo focados em subsidiar micro e pequenos empreendedores do turismo a enfrentar a gestão financeira diante da sazonalidade hoteleira.

---

## 📌 Contexto e Objetivos

### Contexto
O mercado de hospitalidade independente (pousadas, hostels e hotéis de pequeno porte) lida com uma realidade complexa: faturamentos exponenciais na alta temporada que, se não provisionados corretamente, geram crises severas de liquidez na baixa temporada. 

O diferencial deste projeto é utilizar **Engenharia de Prompts** e **Protocolos de Contexto (MCP)** para transformar cartilhas gerais de finanças empresariais em um **Consultor Hoteleiro Especializado e Automatizado**, capaz de cruzar regras rígidas de fluxo de caixa com a dinâmica de ocupação e meios de pagamento (taxas de maquininha, Pix e antecipações).

### Objetivos de Estudo
1. **Domínio de Fluxo de Caixa Real:** Compreender como separar contabilmente o regime de caixa (entradas e saídas imediatas) do regime de competência (reservas pagas antecipadamente para meses futuros).
2. **Mitigação Hoteleira da Sazonalidade:** Aprender a calcular o provisionamento necessário de capital de giro para meses com baixa taxa de ocupação.
3. **Otimização de Liquidez:** Avaliar o impacto real das taxas de adquirência e antecipações na margem de lucro de pequenos meios de hospedagem.

---

## 📚 Curadoria de Fontes (Verdade Única)

O ecossistema foi alimentado estritamente com fontes oficiais e abertas do SEBRAE para garantir a precisão analítica e mitigar alucinações. As fontes utilizadas foram:

1. **E-book - Dicas Básicas de Finanças (SEBRAE):** Fundamentos sobre controle de entradas, saídas e saúde financeira empresarial.
2. **E-book - Meios de Pagamentos para o seu Negócio (SEBRAE):** Manual técnico sobre o funcionamento de taxas de cartão, arranjos de pagamento (Pix) e prazos de recebimento.
3. **E-book - Gestão Financeira SP (SEBRAE):** Diretrizes para planejamento financeiro de curto e médio prazo.
4. **Cartilha MEI (SEBRAE):** Regras de conformidade e obrigações básicas para microempreendedores individuais.
5. **Portal de Bibliotecas SEBRAE:** Base complementar para consultas e validações de dados de microempresas.

---

## 🧠 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

O núcleo do desafio consistiu em testar como a estrutura das instruções altera a precisão da IA. Abaixo estão documentadas as descobertas e melhorias executadas:

### ❌ Teste 1: Prompt Aberto e Superficial (Resultado Ineficaz)
* **Prompt enviado:** *"Como uma pousada de praia deve se preparar para a baixa temporada?"*
* **Resultado da IA:** Conselhos óbvios de marketing digital (ex: "faça postagens no Instagram", "dê descontos"). A IA ignorou completamente os dados financeiros das fontes anexadas.
* **Cicatriz (Diagnóstico):** Perguntas sem a atribuição de um papel técnico (*role*) e sem contexto financeiro delimitado fazem a IA buscar respostas genéricas no seu conhecimento geral, falhando na aplicação da "verdade única".

### 🟢 Teste 2: Prompt Avançado e Contextualizado (Resultado Excelente)
* **Prompt enviado:**
  > "Aja como um Controller Financeiro Hoteleiro Sênior. Com base estritamente nos e-books de Gestão Financeira e Meios de Pagamento do SEBRAE anexados, responda: Uma pousada pequena projeta uma queda de 50% na ocupação nos próximos 3 meses. 1) Como ela deve estruturar seu Fluxo de Caixa para garantir o pagamento dos custos fixos? 2) Qual o risco de ela utilizar a antecipação de recebíveis de cartão de crédito para fechar a conta do mês? Use os termos técnicos das fontes."
* **Resultado da IA:** O modelo aplicou as regras do SEBRAE perfeitamente ao nicho. Explicou que valores de reservas antecipadas (vendas para o futuro) entram como obrigações e não receita realizada. Alertou que a antecipação de recebíveis deteriora a margem de contribuição devido às taxas de desconto cobradas pelas adquirentes, sugerindo o uso do Pix para liquidez imediata sem custos punitivos.

---

## 🤖 A Evolução: O Agente Autônomo (AI Skill)

Indo além da Engenharia de Prompt convencional, os conceitos validados foram consolidados e publicados na forma de um **Agente de IA customizado (Skill: Consultor de Finanças Hoteleiras)** via ferramentas de automação. 

A Skill foi compilada com sucesso e estruturada nos seguintes blocos operacionais:
* **🎭 Persona:** Controller Financeiro Hoteleiro Sênior — foco em respostas diretas, técnicas e sem clichês comerciais.
* **📋 Normas SEBRAE de Fluxo de Caixa:** Aplicação automatizada do regime de caixa vs. competência e blindagem de capital de giro sazonal.
* **💳 Meios de Pagamento:** Hierarquia de tomada de decisão financeira para priorização de recebimentos (Pix → Débito → Crédito → Antecipação).
* **✅ Checklist Padrão:** Geração automática de planos de contingência em 5 áreas críticas hoteleiras para a entrada na baixa temporada.

---

## 📖 Miniguia de Estudo

### 📌 Resumos Estruturados do Assunto

#### 1. A Armadilha da Falsa Liquidez na Hospitalidade
Pousadas independentes frequentemente quebram porque gastam o dinheiro de reservas futuras na alta temporada. O controle eficiente exige rastreamento rígido do **Regime de Caixa**. O faturamento de pacotes futuros deve ser alocado em contas de provisionamento, uma vez que o custo operacional para atender o hóspede (limpeza, lavanderia, café da manhã, energia) só acontecerá meses depois.

#### 2. Meios de Pagamento e Dinâmica de Caixa
A escolha da tecnologia de cobrança define a velocidade do caixa. Vendas via **Pix** geram liquidez imediata com taxa zero ou reduzida. Já as vendas parceladas no cartão de crédito exigem planejamento: recorrer à antecipação de recebíveis de forma recorrente para pagar despesas fixas da baixa temporada consome o lucro real do negócio, mascarando problemas estruturais de Capital de Giro.

---

### 🗂️ Glossário de Conceitos Chave

* **Fluxo de Caixa:** Registro diário e cronológico das entradas e saídas reais de dinheiro da empresa.
* **Capital de Giro:** Recursos financeiros guardados e disponíveis para sustentar a operação do hotel (folha, fornecedores, impostos) enquanto as novas receitas não entram.
* **Taxa de Desconto / Adquirência:** Percentual cobrado pelas empresas de maquininhas e meios de pagamento sobre o valor bruto de cada venda realizada no crédito ou débito.
* **Antecipação de Recebíveis:** Operação financeira onde a empresa solicita o adiantamento de parcelas de vendas a prazo, recebendo o dinheiro na hora em troca do pagamento de taxas de juros (desconto).

---

### 📋 Prompts Reutilizáveis para Revisão Futura

> **[PROMPT 1: AUDITORIA DE SAZONALIDADE]**
> Contexto: Minha pousada passará por 4 meses de baixa ocupação. Com base nos e-books de gestão financeira do SEBRAE, monte um checklist de 5 passos focados em redução de custos variados e blindagem do capital de giro para garantir a sobrevivência do caixa até o fim da temporada.

> **[PROMPT 2: ANÁLISE DE CUSTO-BENEFÍCIO EM MEIOS DE PAGAMENTO]**
> Aja como um analista de operações financeiras. Com base no guia de meios de pagamentos, me explique matematicamente por que priorizar o recebimento por Pix ou transferências diretas protege o fluxo de caixa de um pequeno hostel em comparação ao parcelamento longo no cartão de crédito tradicional.

---

## 🚀 Próximos Passos e Implementações Futuras

Para escalar o impacto deste "segundo cérebro", as seguintes melhorias estão mapeadas para o ecossistema da IA:

1. **Simulador de Fluxo de Caixa Automático:** Desenvolver um prompt avançado que receba dados reais da pousada e gere uma simulação matemática detalhada de fluxo de caixa para 4 meses de baixa temporada, calculando as taxas de desconto de cartão e provisionamento de reservas.
2. **Integração com Yield Management:** Ampliar a base de conhecimento do agente para incluir estratégias de *Precificação Dinâmica* (Revenue Management), atrelando o planejamento financeiro às variações de demanda de mercado.
3. **Deploy em Web App Mobile:** Transformar a Skill gerada e os checklists em uma interface web leve (Progressive Web App), permitindo que pequenos pousadeiros acessem o diagnóstico na palma da mão, agilizando a tomada de decisão.

---
## 👤 Sobre o Autor

**Breno dos Santos-Rodrigues**
* 🎓 **Mestre em Turismo** – Universidade Federal do Paraná (UFPR), com ênfase em Marketing de relacionamento e Análise de BigData
* 🏨 **Pós-graduado Gestão Hoteleira Hospitalar** (MBA) - Faculdade Iguaçú
* 💼 **Bacharel em Turismo** – Universidade Federal do Delta do Parnaíba
* 💻 **Técnico em Informática** - com enfase em desenvolvimento de software - Instituto Federal do Piauí

---
_Projeto desenvolvido como estudo prático para o desafio de Engenharia de Prompts da plataforma DIO._
