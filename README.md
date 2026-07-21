# 📈 Caderno de Investimentos para Iniciantes (via NotebookLM)

---

## 🎯 1. Contexto e Objetivos

### Assunto de Interesse
O tema escolhido para este caderno temático é a **Educação Financeira e Investimentos para Iniciantes**. O objetivo é desmistificar o mercado financeiro para quem deseja dar os primeiros passos com segurança.

### Objetivos de Estudo
- Compreender a diferença teórica e prática entre **Renda Fixa** e **Renda Variável**.
- Entender como construir uma **Reserva de Emergência** adequada e quais ativos utilizar.
- Mapear os conceitos-chave do mercado (Selic, CDI, IPCA, Liquidez, Rendimento Líquido vs. Bruto).
- Utilizar a IA (NotebookLM) como assistente de estudo e síntese para estruturar um material didático reusável.

---

## 📚 2. Curadoria de Fontes

Para garantir a acurácia do conteúdo sintetizado pelo NotebookLM, foram selecionadas e carregadas as seguintes **7 fontes abertas** em PDF e texto:

1. *[YouTube - Curso de Investimento (Playlist)](https://www.youtube.com/playlist?list=PL-QAz5R5Rlm48QwcnzG-IUqzUT3bpyZik)*
2. *[Análise de Investimento (PDF)](https://egov.df.gov.br/wp-content/uploads/2020/11/Analise-de-Investimentos-Material-Teorico.pdf)*
3. *[Universidade do Sul de Santa Catarina - Análise de Investimento (PDF)](https://repositorio-api.animaeducacao.com.br/server/api/core/bitstreams/4136b636-38c9-46b7-999f-c391c78c39e1/content)*
4. *[Introdução ao Mercado e Capitais (PDF)](https://unisalesiano.com.br/aracatuba/wp-content/uploads/2022/01/Artigo-Mercado-de-Capitais-Pronto.pdf)*
5. *[Material de Estudo (ANBIMA) - Princípios de Investimento (PDF)](https://www.anbima.com.br/data/files/74/40/1D/33/466A4810EA926748882BA2A8/CPA-10-Cap4.pdf)*
6. *[Programa bem-estar financeiro (CVM) - Introdução aos Investimentos](https://www.gov.br/investidor/pt-br/educacional/programa-bem-estar-financeiro/programa-bem-estar-financeiro-arquivos/apostila-06.pdf/@@display-file/file)*
7. *[Apostila - Investimento (PDF)](https://www.harioncamargo.com/pdf/apostila_investimentos_porHarionCamargo.pdf)*

---

## 🧠 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção está registrado o processo interativo de construção do conhecimento, as variações de prompts testadas e como os desafios foram superados.

### A. Perguntas Estratégicas e Variações de Prompts
- **Prompt V1 (Inicial):** *"Me explique o que é Renda Fixa."*
  - *Resultado:* Resposta muito genérica e longa.
- **Prompt V2 (Refinado):** *"Com base nos PDFs carregados, elabore uma comparação em tabela entre Tesouro Selic, CDB e LCI, destacando: liquidez, tributação e risco."*
  - *Resultado:* Resposta precisa e orientada às fontes.

### B. Cicatrizes e Troubleshooting (Dificuldades e Soluções)
* **Desafio 1 - Alucinação ou Mistura de Termos:** A IA confundiu a tributação de LCIs/LCAs com a de CDBs nas primeiras tentativas.
  * **Solução:** Adicionei ao prompt o comando explícito: *"Cite apenas as regras tributárias expressas nas Fontes  e destaque a isenção de IR para pessoa física nas LCIs/LCAs."*
* **Desafio 2 - Respostas Genéricas sem Citação:**
  * **Solução:** Passei a solicitar: *"Aponte em qual trecho ou documento das fontes você baseou cada afirmação sobre a Reserva de Emergência."*

---

## 📖 4. Miniguia de Estudo (Entrega Final)

### A. Resumos Estruturados do Assunto
* **Reserva de Emergência:** Deve corresponder a 3 a 6 meses do custo de vida, alocada em ativos de altíssima liquidez (resgate diário) e baixo risco (ex: Tesouro Selic ou CDB 100% CDI).
* **Renda Fixa:** Empréstimo de dinheiro a emissores (Governo ou Bancos) em troca de uma taxa combinada (prefixada, pós-fixada ou híbrida).
* **Renda Variável:** Compra de frações de empresas (Ações) ou ativos imobiliários (FIIs), onde o retorno não é garantido e depende da oscilação do mercado.

### B. Glossário de Conceptos Aprendidos
| Termo | Definição Rápida |
| :--- | :--- |
| **Selic** | A taxa básica de juros da economia brasileira. |
| **CDI** | Taxa que baliza os rendimentos de diversos títulos de Renda Fixa privada. |
| **Liquidez** | A facilidade e rapidez com que um investimento pode ser convertido em dinheiro. |
| **IPCA** | O índice oficial de inflação do Brasil. |
| **FGC** | Fundo Garantidor de Créditos, que protege depósitos em bancos até determinados limites. |

### C. Prompts Reutilizáveis (para revisões futuras)
Você pode usar estes prompts no NotebookLM para revisões rápidas deste tema:

```text
Prompt 1 (Revisão Prática): "Elabore um quiz com 5 perguntas e respostas com justificativa técnica para testar se um iniciante entendeu a diferença entre IPCA e Selic."

Prompt 2 (Análise de Perfil): "Crie um roteiro de decisão para escolher entre investir em Tesouro Direto ou CDB, baseado apenas nos documentos do repositório."

Prompt 3 (Resumo Executivo): "Resuma os 3 erros mais graves que um investidor iniciante deve evitar ao construir a reserva de emergência, em formato de bullet points diretos."
