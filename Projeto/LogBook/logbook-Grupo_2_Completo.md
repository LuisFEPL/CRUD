# 📓 LOGBOOK AFP — Algoritmos e Programação (2026.2)

> **Como usar este arquivo:** copie-o para a raiz do **seu** repositório (ou para `logbook/LOGBOOK.md`) e preencha **direto no GitHub** (botão ✏️ *Edit this file*) ou no VS Code. Ele reúne todos os instrumentos do Protocolo AFP 2026.2 (Logbook Individual — Campos 01 a 04, 06 e 07; Registro de Revisão por Pares — Campo 05; Checkpoint Conceitual; Rubrica de Defesa Técnica).
>
> **Organização:** o Logbook está dividido em **3 grupos de entrega**, cada um com seu prazo. Dentro de cada grupo, os **ciclos de entrega (01 a 12)** continuam os mesmos, com as orientações de preenchimento. Siga a ordem: **Grupo 1 → Grupo 2 → Grupo 3 → Defesa Técnica**.
>
> O `Diario.md` do checklist passa a ser **este arquivo**: o registro de cada ciclo está na seção do ciclo correspondente.

## 📍 Navegação rápida

| Seção | Prazo |
|---|---|
| [👨‍🎓 Identificação](#-identificação) | Hoje |
| [🟢 Grupo 1](#-grupo-1--prazo-segunda-1611-às-23h59) · Registros 01–04, Campos 01 e 02 | **Segunda 16/11, 23h59** |
| [🟠 Grupo 2](#-grupo-2--prazo-sábado-2111-às-23h59) · Registros 05–08, Checkpoint, Campos 03 e 04 | **Sábado 21/11, 23h59** |
| [🔵 Grupo 3](#-grupo-3--prazo-quinta-2611-às-23h59) · Registros 09–12, Campos 05, 06 e 07 | **Quinta 26/11, 23h59** |
| [🏁 Defesa Técnica](#-defesa-técnica--quarta-1811) | **Quarta 18/11** |
| [🆘 Estou atrasado](#-estou-atrasado-no-logbook-e-agora) | — |

---

## 👨‍🎓 Identificação

| Campo                           | Preencha                                           |
| ------------------------------- | -------------------------------------------------- |
| **Nome do estudante**           | Luis Felipe Everton Pinheiro Lopes                 |
| **Curso / Módulo**              | Engenharia de Software - 2º Período                |
| **Unidade curricular**          | Algoritmos e Programação — UnDB 2026.2             |
| **Professor**                   | Rondineli Seba Salomão                             |
| **App-base do meu CRUD**        | Agenda de Contatos                                 |
| **Link do meu repositório**     | https://github.com/LuisFEPL/CRUD/tree/main/Projeto |
| **Dupla de revisão (Campo 05)** | José Guilherme/ José Guilherme                     |
| **Função neste ciclo**          | _Autor do meu CRUD · Revisor do CRUD de um colega_ |

---

## 🧭 Regras de ouro (leia antes de preencher)

1. **Processo, não resultado.** O Logbook mostra *como você pensou*, não só o que funcionou. Registre erros, desvios e dúvidas reais.
2. **Vocabulário técnico.** Use os termos da área (ex.: "laço de repetição", "validação de entrada", "estrutura de dados"). Respostas genéricas ("aprendi Python") não são aceitas.
3. **Todo registro relevante tem 3 âncoras:** o **objeto de conhecimento** mobilizado + a **justificativa técnica** + a **referência/fonte**. *Decisão sem objeto de conhecimento e sem referência é considerada não rastreável e não conta para a avaliação formativa.*
4. **Coerência entre campos.** O Campo 02 deve ser coerente com o Campo 01. *Incoerência é evidência de autoria externa.* O Campo 07 retoma o Campo 01.
5. **IA é permitida e avaliada (Campo 04).** *Print sem análise crítica = devolução imediata. Reproduzir a IA sem questionamento = reprovado.* Você precisa mostrar o que aceitou **e** o que questionou/descartou, com argumento técnico.
6. **O histórico do Git é a sua evidência.** Faça commits pequenos e frequentes. Nunca reescreva o histórico (`force push`) do arquivo do Logbook.
7. **Campo 01 e Checkpoint são "sem consulta".** Preencha em um bloco contínuo, sem internet, sem material e sem colegas, no tempo indicado (Campo 01: durante o laboratório; Checkpoint: 20 min). Depois **não edite** esses campos — se perceber um erro, corrija em um campo posterior (Campo 03 ou 07), explicando.
8. **Os prazos dos grupos (16/11, 21/11 e 26/11, às 23h59)** valem para o commit no GitHub. O horário do commit é o registro oficial.

### ✅ Padrão de commit do Logbook

```text
docs(logbook): campo 01 — ciclo 02
docs(logbook): registro do ciclo 05
docs(logbook): campo 05 — revisão do CRUD de <colega>
```

---

## 🗓️ Calendário de entregas e Defesa

Os grupos têm **5 dias entre um prazo e outro**. O horário do commit no GitHub é o registro oficial.

| Grupo | Janela de preenchimento | **Prazo** | O que entregar |
|:--:|---|---|---|
| **1** | Qua 11/11 → seg 16/11 | **Segunda 16/11, 23h59** | Identificação · Registros dos Ciclos 01 a 04 · Campo 01 · Campo 02 |
| **2** | Seg 16/11 → sáb 21/11 | **Sábado 21/11, 23h59** | Registros dos Ciclos 05 a 08 · Checkpoint Conceitual · Campo 03 · Campo 04 |
| **3** | Sáb 21/11 → qui 26/11 | **Quinta 26/11, 23h59** | Registros dos Ciclos 09 a 12 · Campo 05 (2 revisões) · Campo 06 · Campo 07 |
| 🏁 | — | **Quarta 18/11** | **Defesa Técnica individual** (Rubrica) |

### Linha do tempo

| Data | Evento |
|---|---|
| Qua 11/11 | **Hoje:** começa o Grupo 1 |
| Seg 16/11 | ✅ Prazo do **Grupo 1** |
| **Qua 18/11** | 🏁 **Defesa Técnica** |
| Sáb 21/11 | ✅ Prazo do **Grupo 2** |
| Qua 25/11 | Avaliação P2 |
| Qui 26/11 | ✅ Prazo do **Grupo 3** |
| Qua 02/12 | Avaliação Substitutiva |
| Qua 09/12 | Avaliação Final |

> ⚠️ **Atenção:** a Defesa Técnica (18/11) acontece **antes** dos prazos dos Grupos 2 e 3. Na defesa você será arguido sobre **o que já estiver registrado e commitado**. Veja a seção [Defesa Técnica](#-defesa-técnica--quarta-1811) para saber o que priorizar até 18/11.

### Ciclos de entrega por grupo

| Ciclo | Data da aula | Tema do ciclo | Grupo | O que preencher |
|:--:|:--:|---|:--:|---|
| 01 | 12/08 | Preparação do laboratório e escolha do projeto | **1** | Registro do Ciclo |
| 02 | 19/08 | Variáveis, tipos de dados, entrada/saída | **1** | Registro + **Campo 01** + **Campo 02** |
| 03 | 26/08 | Operadores, fluxogramas, paradigmas | **1** (registro) · **2** (campos) | Registro (G1) · **Checkpoint**, **Campo 03**, **Campo 04** (G2) |
| 04 | 02/09 | Condicionais: `if`, `elif`, `else` | **1** | Registro do Ciclo |
| 05 | 09/09 | Condicionais aninhadas e operadores lógicos | **2** | Registro do Ciclo |
| 06 | 30/09 | Repetição: `for`, `while`, `break`, `continue` | **2** | Registro do Ciclo (inclui devolutiva da P1) |
| 07 | 07/10 | Listas: armazenamento e iteração | **2** | Registro do Ciclo |
| 08 | 14/10 | Busca e introdução a dicionários/matrizes | **2** | Registro do Ciclo |
| 09 | 21/10 | Atualização e exclusão: CRUD completo | **3** | Registro + **Campo 05** (revisão nº 1) |
| 10 | 28/10 | Modularização: funções | **3** | Registro do Ciclo |
| 11 | 04/11 | Recursividade | **3** | Registro + **Campo 06** |
| 12 | 11/11 | Refatoração e qualidade de código | **3** | Registro + **Campo 05** (revisão nº 2) + **Campo 07** |

---

## 📊 Painel de acompanhamento

Atualize a cada commit (troque ⬜ por ✅).

| Grupo | Item                                     | Prazo | Preenchido | Commit |
| :---: | ---------------------------------------- | ----- | :--------: | :----: |
|   1   | Identificação                            | 16/11 |     ✅      |   ✅    |
|   1   | Registros dos Ciclos 01, 02, 03 e 04     | 16/11 |     ✅      |   ✅    |
|   1   | Campo 01 — Instrumento de entrada        | 16/11 |     ✅      |   ✅    |
|   1   | Campo 02 — Aprofundamento                | 16/11 |     ✅      |   ✅    |
|   2   | Registros dos Ciclos 05, 06, 07 e 08     | 21/11 |     ✅      |   ✅    |
|   2   | Checkpoint Conceitual                    | 21/11 |     ⬜      |   ⬜    |
|   2   | Campo 03 — Execução e desvios            | 21/11 |     ✅      |   ✅    |
|   2   | Campo 04 — Interação com IA              | 21/11 |     ✅      |   ✅    |
|   3   | Registros dos Ciclos 09, 10, 11 e 12     | 26/11 |     ⬜      |   ⬜    |
|   3   | Campo 05 — Revisão por pares nº 1 e nº 2 | 26/11 |     ⬜      |   ⬜    |
|   3   | Campo 06 — Próximos passos               | 26/11 |     ⬜      |   ⬜    |
|   3   | Campo 07 — Evolução conceitual           | 26/11 |     ⬜      |   ⬜    |
|  🏁   | Defesa Técnica                           | 18/11 |     ⬜      |   —    |

---

## ❓ A questão-problema da AFP

**Título:** *O sistema em produção: diagnosticando as falhas do CRUD que você mesmo construiu.*

> **Enunciado completo (Apêndice A):** _professor(a): cole aqui o enunciado e os anexos liberados conforme o cronograma._

A questão-problema é **a mesma durante todo o semestre**: ela se aplica ao **seu** CRUD, que cresce a cada ciclo. Os **dados com defeito** do seu app chegam em um **lote cumulativo único** e vão expondo problemas diferentes conforme sua estrutura evolui. Seu trabalho é diagnosticar, ajustar o CRUD para tratar cada falha e **registrar o raciocínio** neste Logbook.

---

# 🔁 REGISTRO DO CICLO — modelo (copie em cada ciclo)

Cada ciclo tem sua própria seção abaixo, já com o modelo. Se precisar de espaço extra, acrescente linhas.

```markdown
### Registro do Ciclo NN — DD/MM
1. **Desafio do ciclo (em 1 frase):**
2. **O que implementei (commits / arquivos / links):**
3. **Objeto(s) de conhecimento mobilizado(s) (vocabulário técnico):**
4. **Desvio ou erro encontrado + causa técnica:**
5. **Decisão de ajuste + fonte (livro, doc, vídeo, colega, IA):**
6. **Feedback recebido (professor/colega) e o que mudei por causa dele:**
7. **Próximo passo:**
```

**Como preencher bem:** escreva como se explicasse a um colega que não esteve na aula. O item 3 e o item 5 são os mais importantes: eles ligam o que você fez ao **conteúdo** e à **fonte**.

| ❌ Fraco | ✅ Forte |
|---|---|
| "Aprendi a usar `if`." | "Usei estrutura condicional aninhada para validar a idade antes de cadastrar. Meu erro foi comparar `str` com `int` (resultado de `input()`); corrigi com `int()` (Pense em Python, cap. 2)." |
| "Deu erro e consertei." | "O programa quebrou com `ZeroDivisionError` ao calcular a média de um item sem avaliações. Causa: divisão por `len(lista)` com lista vazia. Ajuste: testar `if len(lista) > 0`." |

---

# 🟢 GRUPO 1 — prazo segunda 16/11 às 23h59

> **Janela:** quarta 11/11 → segunda 16/11. **O que entregar:** Identificação · Registros dos Ciclos 01, 02, 03 e 04 · Campo 01 · Campo 02.
>
> **Sugestão de ordem:** (1) Identificação → (2) **Campo 01 primeiro, sem consulta** → (3) Registros dos Ciclos 01 a 04 → (4) Campo 02, com pesquisa.

**Checklist do Grupo 1**
- [x] Identificação preenchida (app-base, link do repositório, dupla de revisão)
- [x] Campo 01: 3 objetos de conhecimento, 3 lacunas, hipótese de até 5 linhas
- [x] Registros dos Ciclos 01, 02, 03 e 04 com os 7 itens
- [x] Campo 02: 2 referências com contribuição, hipótese revisada, 3 recursos
- [x] Commits no GitHub e painel atualizado

## 🟢 CICLO 01 — 12/08 — Preparação do laboratório e escolha do projeto

<details>
<summary>📘 Orientações do Ciclo 01</summary>

- **Hoje não há Campo do Protocolo.** O foco é preparar o ambiente: criar o repositório, configurar o VS Code e escolher o **app-base** do seu CRUD (e, portanto, o *schema* dos seus dados).
- Preencha a **Identificação** (no início deste arquivo) e o **Registro do Ciclo 01**.
- No item 3, registre **o que você já sabia** e o que era novo (Git, GitHub, VS Code). Isso será útil para o Campo 07.
- No item 4, registre qualquer problema de instalação ou configuração e como o resolveu — isso conta como desvio.
- Faça o primeiro commit: `docs(logbook): registro do ciclo 01`.
</details>

#### Registro do Ciclo 01 — 12/08
1. **Desafio do ciclo (em 1 frase):** Compreender como Linkar o GitHub ao Vscode para fazer commits mais facilmente
2. **O que implementei (commits / arquivos / links):**  Criei um novo repositório no GitHub para armazenar os arquivos e acompanhar o desenvolvimento do meu CRUD, que consiste em um gerenciador de contatos. Link do repositório: https://github.com/LuisFEPL/CRUD/
3. **Objeto(s) de conhecimento mobilizado(s):**  Git, GitHub e VsCode
4. **Desvio ou erro encontrado + causa técnica:** Não encontrei desvios ou erros técnicos relevantes durante a criação do repositório e a configuração do ambiente de desenvolvimento. A integração entre o GitHub e o VS Code ocorreu conforme esperado, sem necessidade de correções
5. **Decisão de ajuste + fonte:**  Como não foram identificados problemas técnicos durante a configuração, não foi necessário realizar ajustes no ambiente.
6. **Feedback recebido e o que mudei:**  Não recebi feedback específico do professor ou de colegas durante este ciclo. Portanto, não foram realizadas alterações decorrentes de avaliações externas.
7. **Próximo passo:** Aprender mais comandos do git, como git clone e a fazer pull requests.


## 🟢 CICLO 02 — 19/08 — Variáveis, tipos de dados e entrada/saída

<details>
<summary>📘 Orientações do Ciclo 02 — Campo 01 (sem consulta) e Campo 02 (pesquisa)</summary>

**Campo 01 — Instrumento de entrada** · *sem consulta · faça primeiro*
- Preencha **antes de tudo**, em um bloco contínuo de cerca de 15 minutos, sem internet, sem material, sem IA e sem colegas, depois de conhecer a questão-problema e a primeira amostra de dados do seu app. Depois do Campo 01 você pode consultar o que quiser.
- **1a.** Liste pelo menos **3 objetos de conhecimento** que você acha que precisa dominar para resolver o problema. Use o vocabulário técnico da área. *Não precisa acertar tudo — o Campo 07 vai mostrar o quanto você evoluiu.*
- **1b.** Liste pelo menos **3 lacunas**: o que você **não sabe** e precisa descobrir, com precisão (ruim: "não sei programar"; bom: "não sei como validar a entrada para impedir que o usuário digite texto onde espero número").
- **1c.** Escreva sua **hipótese inicial** em até 5 linhas: o que você acha que está causando as falhas do CRUD e por quê.
- Faça o commit **logo ao terminar**. Depois, **não edite** o Campo 01.

**Campo 02 — Aprofundamento** · *AV Qualis · segunda 16/11, 23h59*
- Preencha **depois do Campo 01, com pesquisa real**, e seja coerente com ele.
- **2a.** Pelo menos **2 referências** (livro, documentação, vídeo, artigo), cada uma com a **contribuição** concreta para a sua solução. Não basta listar o título.
- **2b.** **Hipótese revisada:** o que mudou em relação ao Campo 01 e **por quê**. Se não mudou nada, explique por que a pesquisa confirmou a hipótese.
- **2c.** **Dimensionamento inicial de recursos** (mínimo 3 itens), com quantidade estimada e justificativa técnica. Exemplos de recursos no seu contexto: horas de estudo, número de casos de teste, módulos/arquivos do projeto, dados de teste, bibliotecas.
</details>

### 🧩 CAMPO 01 — Instrumento de entrada
*Grupo 1 | Prazo segunda 16/11, 23h59 | SEM CONSULTA*

**1a. Objetos de conhecimento identificados (mínimo 3, com vocabulário técnico):**
1. Variáveis
2. Tipos de Dados
3. Input e Output
4. Type casting

**1b. Lacunas — o que não sei e preciso descobrir (mínimo 3, com precisão técnica):**
1.  Não encontrei nenhuma lacuna significativa que pudesse reparar.
2.  Não encontrei nenhuma lacuna significativa que pudesse reparar.
3.  Não encontrei nenhuma lacuna significativa que pudesse reparar.

**1c. Hipótese inicial em até 5 linhas — com lógica da área de formação:**

> Como dito, não encontrei nenhuma lacuna significativa que pudesse reparar.

### 🧩 CAMPO 02 — Aprofundamento pós-aula
*AV Qualis — Grupo 1 | Segunda 16/11, 23h59*

> **Preenchido depois do Campo 01, com pesquisa real. Deve ser coerente com o Campo 01. Incoerência = evidência de autoria externa.**

**2a. Aprofundamento dos objetos de conhecimento (mínimo 2 referências com síntese da contribuição para a solução):**

- **Referência 1:** Documentação oficial do Python — **Contribuição:** Input and Output.
- **Referência 2:** Livro Pense Python — **Contribuição:**  f string(f'') dentro do print, permitindo fazer operações ainda dentro da string.


**2b. Hipótese revisada — o que mudou em relação ao Campo 01 e por quê:**

> Não houve hipótese pois Não encontrei nenhuma lacuna significativa que pudesse reparar nesse ciclo.

**2c. Dimensionamento inicial de recursos (recurso, quantidade estimada, justificativa técnica — mínimo 3 itens):**

| RECURSO / MATERIAL / INSUMO     | QUANTIDADE ESTIMADA | JUSTIFICATIVA TÉCNICA                                                                                   |
| ------------------------------- | ------------------- | ------------------------------------------------------------------------------------------------------- |
| Computador com VS Code e Python | 1 unidade           | Necessário para desenvolver, executar e depurar a aplicação.                                            |
| Documentação oficial do Python  | 2 Referências       | Auxilia na compreensão de entrada/saída, tipos de dados e estruturas utilizadas no CRUD.                |
| Horas de estudo e testes        | 4 Horas             | Tempo estimado para revisar os conceitos, analisar possíveis falhas e testar as operações da aplicação. |
|                                 |                     |                                                                                                         |
|                                 |                     |                                                                                                         |

#### Registro do Ciclo 02 — 19/08
1. **Desafio do ciclo (em 1 frase):** Compreender como as variáveis e os diferentes tipos de dados são utilizados para armazenar informações e como ocorre a entrada e saída de dados em Python.
2. **O que implementei (commits / arquivos / links):** Implementei variáveis na primeira etapa do CRUD, que são o coração do código: `https://github.com/LuisFEPL/CRUD/blob/main/Projeto/CRUD/CRUD_1`
3. **Objeto(s) de conhecimento mobilizado(s):** Variáveis, atribuição de valores, tipos primitivos (int, float, str e bool), conversão de tipos (type casting) e operações de entrada e saída utilizando input() e print().
4. **Desvio ou erro encontrado + causa técnica:** Tentei realizar operações com um valor tipo str, resultado de input()
5. **Decisão de ajuste + fonte:**  Decidi verificar o tipo de dado gerado por input() com type(), resultado: str, para resolver fiz type casting, como int(), não usei essa conversão na primeira etapa do CRUD, mas foi um aprendizado
6. **Feedback recebido e o que mudei:** Não houve feedback específico nem alterações decorrentes de avaliação externa. 
7. **Próximo passo:**  Aprofundar o conhecimento sobre conversão de tipos e validação de entradas, evitando incompatibilidades entre os dados fornecidos pelo usuário e as operações realizadas pelo programa.

## 🟢 CICLO 03 — 26/08 — Operadores, fluxogramas e paradigmas

<details>
<summary>📘 Orientações do Ciclo 03 — Registro (Grupo 1)</summary>

- Neste grupo você preenche **apenas o Registro do Ciclo 03**. O **Checkpoint Conceitual** e os **Campos 03 e 04** deste ciclo estão no **Grupo 2**.
- Item 3: nomeie os **operadores** (aritméticos, relacionais, lógicos) e os **tipos** que usou. Se montou fluxogramas, cite o que o fluxograma ajudou a perceber.
- Item 4: registre erros de precedência de operadores, divisão por zero ou confusão entre `=` e `==`, com a causa técnica.
</details>

#### Registro do Ciclo 03 — 26/08
1. **Desafio do ciclo (em 1 frase):**  Compreender como os operadores e as representações de algoritmos por meio de fluxogramas auxiliam na construção da lógica de um programa.
2. **O que implementei (commits / arquivos / links):**  Apenas atividades realizadas em aula
3. **Objeto(s) de conhecimento mobilizado(s):**  Operadores aritméticos (+, -, *, /), relacionais (==, !=, >, <, >=, <=) e lógicos (and, or, not). Também foram trabalhadas expressões booleanas, precedência de operadores, algoritmos e representação de fluxos de decisão.
4. **Desvio ou erro encontrado + causa técnica:**  Não tive nenhum erro significativo nesse ciclo
5. **Decisão de ajuste + fonte:** Não tive nenhum erro significativo nesse ciclo, então não precisei ajustar.
6. **Feedback recebido e o que mudei:** Não recebi feedbacks específicos.  
7. **Próximo passo:**  Aplicar operadores relacionais e lógicos na construção de expressões condicionais, entendendo como eles permitem controlar o fluxo de execução de um algoritmo.

## 🟢 CICLO 04 — 02/09 — Estruturas condicionais: `if`, `elif`, `else`

<details>
<summary>📘 Orientações do Ciclo 04</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 04.
- Conecte **cada condicional** do seu CRUD a uma **regra de negócio** (ex.: "preço não pode ser negativo").
- Se já recebeu o lote de dados com defeito, procure **qual registro quebra qual condição** e registre o item 4 com a **causa técnica** (ex.: valor `None`, texto vazio, número negativo, divisão por zero).
- No item 5, cite a fonte da decisão: livro (*Pense em Python*), documentação ou exercício que você resolveu.
- Compare com o **Campo 02**: o desvio de hoje já estava previsto no seu dimensionamento?
</details>

#### Registro do Ciclo 04 — 02/09
1. **Desafio do ciclo (em 1 frase):**  Entender como utilizar estruturas condicionais para controlar o fluxo de execução de um programa de acordo com determinadas condições.
2. **O que implementei (commits / arquivos / links):**   Adicionei mecanismos para verificar se o valor de uma variável é vazia ou se o valor de entrada é um valor específico, link do código: `https://github.com/LuisFEPL/CRUD/blob/main/Projeto/CRUD/CRUD_1`
3. **Objeto(s) de conhecimento mobilizado(s):**  Estruturas condicionais (if, elif e else), expressões booleanas, operadores relacionais e lógicos, indentação e controle de fluxo. Esses conceitos permitem estabelecer regras de negócio, como impedir o cadastro de contatos sem nome ou verificar se um contato existe antes de atualizá-lo.
4. **Desvio ou erro encontrado + causa técnica:** "Identation Error", coloquei uma condição if fora do alcance em um lugar do programa, deixando-o desalinhado.
5. **Decisão de ajuste + fonte:**  Usei condições aninhadas e alinhadas, deixando o código mais legível e funcional.
6. **Feedback recebido e o que mudei:**  Não Houve feedbacks recebidos.
7. **Próximo passo:** Aprofundar o uso de estruturas condicionais combinadas com operadores lógicos, aplicando validações para garantir que as operações do CRUD sejam executadas somente quando os dados e as condições forem adequados.

---

# 🟠 GRUPO 2 — prazo sábado 21/11 às 23h59

> **Janela:** segunda 16/11 → sábado 21/11. **O que entregar:** Registros dos Ciclos 05, 06, 07 e 08 · Checkpoint Conceitual · Campo 03 · Campo 04.
>
> ⚠️ O prazo cai num **sábado**: planeje terminar na sexta. Os campos do Ciclo 03 (Checkpoint, 03 e 04) aparecem **primeiro**, porque são a base da investigação.

**Checklist do Grupo 2**
- [ X ] Checkpoint Conceitual feito conforme orientação do professor (20 min, sem consulta)
- [ X ] Campo 03: 2 achados com objeto, 1 desvio com causa técnica, 1 decisão com fonte
- [ X ] Campo 04: ferramenta, pergunta íntegra, resumo, o que aceitei e o que questionei
- [ X ] Registros dos Ciclos 05, 06, 07 e 08 com os 7 itens (devolutiva da P1 no ciclo 06)
- [ X ] Commits no GitHub e painel atualizado

## 🟠 CICLO 03 (campos) — 26/08 — Checkpoint, Campo 03 e Campo 04

<details>
<summary>📘 Orientações — Checkpoint, Campo 03 e Campo 04 (referentes ao Ciclo 03)</summary>

**Checkpoint Conceitual** · *20 min · sem consulta · conforme orientação do professor*
- Verifica o **seu domínio individual** do conteúdo — não avalia a sua solução. São **3 questões dissertativas**. Quem investiu por conta própria responde com segurança.
- Respostas **genéricas, sem ancoragem técnica, não são aceitas**. Defina o objeto **e** relacione-o ao problema do seu CRUD, explicitando as implicações.
- Critérios: *precisão conceitual*, *relação conteúdo-problema*, *qualidade do raciocínio*.
- Se for insatisfatório, você recebe **feedback escrito em até 48h** e deve ajustar a investigação antes da avaliação somativa.
- Se o professor aplicar o Checkpoint via GitHub, use o arquivo abaixo **só durante os 20 minutos**, com um único commit ao final.

**Campo 03 — Execução e desvios** · *sábado 21/11, 23h59*
- **3a.** Pelo menos **2 achados** que mudaram sua compreensão do problema, cada um com o **objeto de conhecimento** associado.
- **3b.** Pelo menos **1 desvio** em relação ao Campo 02 (o que você planejou e não aconteceu) e a **causa técnica** — não vale "falta de tempo".
- **3c.** Pelo menos **1 decisão de ajuste**, com justificativa e **fonte**, e o objeto de conhecimento mobilizado.

**Campo 04 — Interação com IA** · *sábado 21/11, 23h59 · obrigatório e avaliado*
- Registre **pelo menos uma** interação real com uma IA sobre o seu CRUD.
- **4b.** Transcreva a pergunta **na íntegra** (copie e cole).
- **4c.** Resuma a resposta em **um parágrafo** com as suas palavras.
- **4d.** O que você **aceitou**, ligando ao objeto de conhecimento.
- **4e.** O que você **questionou ou descartou**, com **argumento técnico ou fonte** (teste, documentação, livro). Dica: **rode o código** que a IA sugeriu antes de decidir.
- **Print sem análise crítica = devolução imediata.** Se você aceitou tudo, volte e procure o que verificar.
</details>

### 🧩 CHECKPOINT CONCEITUAL INDIVIDUAL
*20 minutos · sem consulta a qualquer fonte, material ou colega · conforme orientação do professor.*

|                        |                                    |
| ---------------------- | ---------------------------------- |
| **Nome do estudante**  | Luis Felipe Everton Pinheiro Lopes |
| **Data de realização** | 20/11/2026                         |
| **Unidade curricular** | Algoritmos e Programação           |
| **Professor(a)**       | Rondineli Seba Salomão             |

> **INSTRUÇÕES:** Responda individualmente, sem consulta. Você tem 20 minutos. As questões avaliam seu domínio dos objetos de conhecimento do componente — não sua solução para o problema. Respostas genéricas sem ancoragem técnica não são aceitas.

**QUESTÃO 1** — Objeto de conhecimento: _…_
> Não houve identificação das perguntas

**RESPOSTA:**

> Não houve identificação das perguntas

**QUESTÃO 2** — Objeto de conhecimento: _…_
> Não houve identificação das perguntas

**RESPOSTA:**

> Não houve identificação das perguntas

**QUESTÃO 3** — Objeto de conhecimento: _…_
>  Não houve identificação das perguntas

**RESPOSTA:**

> Não houve identificação das perguntas

<details>
<summary>🔒 Uso do professor — critérios de avaliação do Checkpoint</summary>

| CRITÉRIO | SATISFATÓRIO | INSATISFATÓRIO |
|---|---|---|
| **Precisão conceitual** | Domínio do objeto de conhecimento, com vocabulário técnico adequado e sem erros conceituais relevantes. | Resposta vaga, com erros conceituais ou sem ancoragem nos objetos de conhecimento do componente. |
| **Relação conteúdo-problema** | Conecta o objeto de conhecimento ao problema trabalhado na AFP. | Responde o objeto de forma isolada, sem relação com o problema do ciclo. |
| **Qualidade do raciocínio** | Raciocínio técnico articulado: relaciona o objeto ao problema e explicita implicações para a investigação. | Apenas define o objeto, sem articular raciocínio ou relação com o problema investigado. |

**RESULTADO:** ☐ Satisfatório ☐ Insatisfatório
**AÇÃO DO PROFESSOR:** Checkpoint insatisfatório gera feedback escrito individualizado até 48h — o aluno ajusta a investigação antes da avaliação somativa.
</details>

### 🧩 CAMPO 03 — Execução e desvios
*AV Qualis — Grupo 2 | Sábado 21/11, 23h59*

**3a. O que descobri que mudou minha compreensão do problema (mínimo 2 achados, com objeto de conhecimento associado):**
1. Durante o desenvolvimento, aprendi que as entradas recebidas por input() são armazenadas como strings (str), independentemente do conteúdo digitado. Isso significa que, quando uma operação exige outro tipo de dado, é necessário realizar a conversão adequada e considerar possíveis erros caso a entrada seja incompatível. Esse entendimento ampliou minha percepção sobre a importância da validação de dados na aplicação. — *Objeto de conhecimento:* Tipos de dados, conversão de tipos e validação de entradas.
2. Entendi que a organização dos dados influencia diretamente a implementação das operações de um CRUD. A utilização de estruturas como listas e dicionários permite armazenar, acessar, modificar e localizar informações de maneira mais organizada, mas exige atenção à forma como os elementos são manipulados, principalmente durante buscas, alterações e remoções. — *Objeto de conhecimento:*  Estruturas de dados, listas, dicionários, indexação e manipulação de informações.
3. _…_ *(opcional)*

**3b. Desvio em relação ao Campo 02 (ao menos 1 — causa técnica):**
- **Desvio:** Não houve, pois no campo 2 eu relatei que não havia encontrado nenhuma falha significativa, o grupo 2 é um CRUD simplesmente mais completo que o grupo 1. A única limitação foi poder apenas criar um único contato, e, se precisasse criar outro, precisaria apagar o anterior.
- **Causa técnica:** Ausência de uma estrutura de dados dinâmica que permitisse criar contatos sem perder o contato anterior.

**3c. Decisão de ajuste (ao menos 1) com justificativa e fonte:**
- **Decisão:**  A solução, que só pôde ser possível no Grupo 2, veio com a ideia de implementar listas e dicionários para guardar os contatos em uma estrutura.
- **Fonte:**  Aulas do professor Rondineli - Listas, matrizes e dicionários.

**Objeto de conhecimento mobilizado nesta decisão:** Listas, matrizes e dicionários e suas operações.

### 🧩 CAMPO 04 — Interação com IA
*AV Qualis — Grupo 2 | Sábado 21/11, 23h59 | OBRIGATÓRIO*

> **Obrigatório e avaliado. Print sem análise crítica = devolução imediata. Reproduzir a IA sem questionamento = reprovado.**

**4a. Ferramenta:** CHAT-GPT  **Data:** 20/11/2026

**4b. Pergunta formulada (transcrita integralmente):**

> "tem algum erro de python que acontece se vc digitar algo inesperado no input()? como um tipo de dado diferente do esperado"

**4c. Resposta da IA (resumida em parágrafo):**

> A resposta explicou que a função input() retorna uma string (str) e que, quando essa entrada é convertida para outro tipo de dado, podem ocorrer erros caso o valor fornecido seja incompatível. Foi apresentado o ValueError, que pode acontecer ao tentar converter um texto não numérico utilizando int(), e o TypeError, que ocorre em operações incompatíveis entre tipos. Também foi explicado que o uso de try e except permite tratar determinadas exceções sem encerrar abruptamente o programa.

**4d. O que aceitei — com referência ao objeto de conhecimento do componente:**

> Aceitei a explicação de que os dados recebidos por input() são strings e que conversões como int() podem provocar ValueError quando o conteúdo não representa um número inteiro válido. Esse conhecimento é relevante para a Agenda de Contatos porque permite compreender a necessidade de validar entradas e evitar que dados inesperados comprometam o processamento. Objeto de conhecimento: Tipos de dados, conversão de tipos, validação de entradas e tratamento de exceções.

**4e. O que questionei ou descartei — com argumento técnico ou fonte:**

> Não considerei que o uso de try/except fosse suficiente para validar todas as entradas da aplicação. O tratamento de exceções evita que determinados erros interrompam o programa inesperadamente, mas não garante que o valor recebido seja válido para a regra de negócio. Por exemplo, converter um valor para inteiro não garante que ele seja uma idade válida ou que esteja dentro de um intervalo permitido. Devido a isso, tratei todos os erros com if e else.

## 🟠 CICLO 05 — 09/09 — Condicionais aninhadas e operadores lógicos

<details>
<summary>📘 Orientações do Ciclo 05</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 05.
- Registre **qual combinação de condições** (`and`, `or`, `not`) você precisou e **por que** uma condicional aninhada ou um operador lógico foi a melhor escolha.
- Descreva **pelo menos um caso de teste** que você usou para provar a lógica (entrada → resultado esperado → resultado obtido).
- **Atenção à P1 (23/09):** reveja o Logbook até aqui. Complete itens em branco e confirme se os commits estão em dia.
- Na semana de 16/09 (Nivelamento / Peer Instruction), reserve 10 minutos para atualizar este arquivo.
</details>

#### Registro do Ciclo 05 — 09/09
1. **Desafio do ciclo (em 1 frase):** Entender como combinar operadores lógicos e estruturas condicionais aninhadas para avaliar múltiplas condições dentro de um algoritmo.
2. **O que implementei (commits / arquivos / links):**  Implemente um sistema de análise de escolhas do menu de escolhas usando and e or, usei também condições aninhadas para analisar essas escolhas; link do código: https://github.com/LuisFEPL/CRUD/blob/main/Projeto/CRUD/CRUD_2
3. **Objeto(s) de conhecimento mobilizado(s):**  Operadores lógicos and, or e not, expressões booleanas, condicionais aninhadas, precedência lógica e fluxo de execução. Esses conceitos permitem avaliar múltiplas condições simultaneamente e controlar a execução de diferentes blocos de código.
4. **Desvio ou erro encontrado + causa técnica:** Não tive nenhum problema nesse ciclo.
5. **Decisão de ajuste + fonte:** Não tive nenhum problema nesse ciclo
6. **Feedback recebido e o que mudei:**  O feedback mostrou a necessidade de analisar melhor a combinação de condições lógicas, principalmente a diferença entre os operadores and e or, para evitar que uma condição seja considerada verdadeira quando nem todos os requisitos necessários foram atendidos. Desde então passei a observar com mais atenção a lógica das expressões condicionais e o resultado esperado de cada combinação de condições.
7. **Próximo passo:** Aplicar operadores lógicos em validações mais complexas e desenvolver maior clareza na construção de expressões condicionais.

## 🟠 CICLO 06 — 30/09 — Devolutiva da P1 + repetição: `for`, `while`, `break`, `continue`

<details>
<summary>📘 Orientações do Ciclo 06</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 06.
- Use o item 6 para registrar a **devolutiva da P1**: o que errou e **qual conceito** estava faltando. Esses erros alimentam o **Campo 07c** (conceitos corrigidos). *Anote já, para não esquecer.*
- Registre **por que escolheu `for` ou `while`** em cada laço do seu CRUD (cadastro em lote, listagem, menu).
- Item 4: se um laço ficou infinito ou pulou itens, descreva a **causa técnica** (condição de parada, incremento, `break` fora de lugar).
</details>

#### Registro do Ciclo 06 — 30/09
1. **Desafio do ciclo (em 1 frase):** Aprender como utilizar estruturas de repetição para executar instruções múltiplas vezes, controlando as condições de continuidade e encerramento de um laço.
2. **O que implementei (commits / arquivos / links):**  loop while True para manter a execução do programa até o usuário parar, também houve uso de loop for para percorrer a estrutura de dados; link do código: https://github.com/LuisFEPL/CRUD/blob/main/Projeto/CRUD/CRUD_2
3. **Objeto(s) de conhecimento mobilizado(s):** Estruturas de repetição for e while, iteração, condição de parada, incremento, controle de fluxo, break e continue. O for permite percorrer sequências e coleções, enquanto o while executa um bloco enquanto sua condição for verdadeira.
4. **Desvio ou erro encontrado + causa técnica:** Não houve erros ou desvios nesse ciclo.
5. **Decisão de ajuste + fonte:** Não houve erros ou desvios nesse ciclo.
6. **Feedback recebido (inclui devolutiva da P1) e o que mudei:**  Não Houve devolutiva da P1
7. **Próximo passo:** Aprofundar o uso de laços para percorrer listar, realizar buscas e controlar a repetição de operações no CRUD, evitando loops infinitos e execuções desnecessárias.

## 🟠 CICLO 07 — 07/10 — Listas: armazenamento e iteração

<details>
<summary>📘 Orientações do Ciclo 07</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 07.
- Justifique **por que seus dados cabem em uma lista** e como você os percorre (iteração).
- Item 4: erros típicos — índice fora do intervalo, alterar a lista enquanto percorre, confundir cópia com referência. Registre qual deles aconteceu e a causa técnica.
- Item 3: nomeie as **operações de lista** que usou (adicionar, remover, ordenar, fatiar…).
</details>

#### Registro do Ciclo 07 — 07/10
1. **Desafio do ciclo (em 1 frase):** Entender que listas permitem armazenar múltiplos elementos em uma única estrutura e como realizar operações de manipulação e iteração sobre esses dados.
2. **O que implementei (commits / arquivos / links):**  Implementei uma lista de dicionários para alocar os contatos de forma dinâmica, que no caso é provavelmente a parte mais importante do CRUD etapa 2, todas as operações giram em torno desse mini banco de dados que implementei, link do código: https://github.com/LuisFEPL/CRUD/blob/main/Projeto/CRUD/CRUD_2
3. **Objeto(s) de conhecimento mobilizado(s):** Listas, índices, elementos, mutabilidade, métodos append(), remove(), pop(), len() e iteração por meio de for. Esses recursos possibilitam organizar conjuntos de contatos e percorrer seus registros para realizar consultas e operações.
4. **Desvio ou erro encontrado + causa técnica:** "List Index out of range" usei um loop for com intervalo do tipo 0 até len(lista + 1), porém o índice lista -1 não existe.
5. **Decisão de ajuste + fonte:** Troquei o intervalo para for i in range(len(lista)):, dessa forma o contador vai de 0 até lista -1, índice que existe, pois o último não é incluído(porque o 0 conta), não precisei usar nenhuma fonte.
6. **Feedback recebido e o que mudei:**  O feedback que recebi mostrou a importância de entender a indexação das listas e a diferença entre acessar, adicionar e remover elementos. Após o feedback passei a tomar mais cuidado com a posição dos elementos e os limites dos índices, evitando acessos incompatíveis com o tamanho da lista e entendendo melhor como as alterações afetam no CRUD.
7. **Próximo passo:**  Melhorar a manipulação de coleções e estudar formas de organizar cada contato em estruturas de dados que facilitem o acesso e a atualização de informações.

## 🟠 CICLO 08 — 14/10 — Busca/consulta e introdução a dicionários e matrizes

<details>
<summary>📘 Orientações do Ciclo 08</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 08.
- Explique **por que cada item do seu catálogo virou um dicionário** (chave → valor) em vez de uma lista de valores soltos.
- Item 4: registre **qual busca falhou** (item inexistente, tipo diferente — `"2"` ≠ `2`, chave com maiúscula errada) e a causa técnica.
- Se usou o lote de dados defeituoso, registre **qual registro** quebrou a busca.
- Item 5: cite a fonte (*Pense em Python*, cap. 11, ou outra).
</details>

#### Registro do Ciclo 08 — 14/10
1. **Desafio do ciclo (em 1 frase):** Entender como realizar buscas em estruturas de dados e utilizar dicionários para organizar informações por meio de pares de chave e valor.
2. **O que implementei (commits / arquivos / links):** Implementei um dicionário que possui uma chave "contatos", que é uma lista de dicionários
3. **Objeto(s) de conhecimento mobilizado(s):**  Busca linear, comparação de valores, estruturas de dados, dicionários, pares chave-valor, chaves, valores, acesso por índice e acesso por chave. Os dicionários permitem associar atributos identificadores a informações específicas, como nome, número, endereço e email de um contato.
4. **Desvio ou erro encontrado + causa técnica:**  Não houve erros ou desvios nessa etapa.
5. **Decisão de ajuste + fonte:**  Não houve erros ou desvios nessa etapa.
6. **Feedback recebido e o que mudei:**  Recebi um feedback positivo quanto a organização da estrutura de dados e a forma de busca usada para encontrar um contato e mostrá-los, devido a isso não julguei ser necessário qualquer mudança.
7. **Próximo passo:** Terminar de revisar  a estrutura de armazenamento dos contatos.
---

# 🔵 GRUPO 3 — prazo quinta 26/11 às 23h59

> **Janela:** sábado 21/11 → quinta 26/11. **O que entregar:** Registros dos Ciclos 09, 10, 11 e 12 · Campo 05 (duas revisões por pares) · Campo 06 · Campo 07.
>
> ⚠️ O prazo vem **um dia depois da P2 (25/11)**. Os Campos 06 e 07 dependem de todo o Logbook: deixe-os para o final, mas **adiante o rascunho do 6c e do 7a/7b antes da Defesa (18/11)**.

**Checklist do Grupo 3**
- [ ] Registros dos Ciclos 09, 10, 11 e 12 com os 7 itens
- [ ] Campo 05: duas revisões (Ciclos 09 e 12), blocos 5a a 5e
- [ ] Campo 06: decisão autônoma, lacuna com plano, pergunta da banca com 5 linhas ou mais
- [ ] Campo 07: 7a a 7e, com 3 objetos, 2 equívocos corrigidos e transferência
- [ ] Coerência entre Campo 01 e Campo 07
- [ ] Painel de acompanhamento completo

## 🔵 CICLO 09 — 21/10 — Atualização e exclusão: CRUD completo

<details>
<summary>📘 Orientações do Ciclo 09 — Registro + Campo 05 (revisão por pares nº 1)</summary>

- Neste ciclo seu CRUD ficou **completo** (Create, Read, Update, Delete). Preencha o Registro do Ciclo 09.
- **Item 4:** *atualizar* ou *excluir* item inexistente, e excluir durante um laço (a lista muda de tamanho e itens são pulados) são erros comuns.
- **Campo 05 — Registro de Revisão por Pares.** Você passa a ser **revisor** do CRUD de um colega.
  - Cada revisão tem **um registro** (copie a seção do Campo 05) com o nome e o link do repositório revisado.
  - **Revise o processo, não só o código:** o que foi decidido, em que objeto de conhecimento se apoia, com que fonte.
  - **5a:** liste as etapas da revisão (ex.: rodar o CRUD, testar com o lote de dados com defeito, ler o código, registrar achados, devolver feedback).
  - **5b:** liste os insumos que usou (lote de dados, casos de teste, `requisitos.md`) com quantidade planejada, utilizada e variação.
  - **5c:** diga se a solução do colega atende ao critério (Sim/Parcialmente/Não) e **qual critério** usou (ex.: requisito do `requisitos.md`).
  - **5d:** riscos da revisão (ex.: não conseguir rodar o código do colega) e como mitigou.
  - **5e:** registre **cada decisão técnica** da revisão com **data, responsável, objeto de conhecimento e fundamentação/referência**. *Sem objeto e sem referência, não é rastreável.*
  - Feedback ao colega: **específico e respeitoso** (o que está bom, o que quebrou, como reproduzir, sugestão).
</details>

#### Registro do Ciclo 09 — 21/10
1. **Desafio do ciclo (em 1 frase):** _…_
2. **O que implementei (commits / arquivos / links):** _…_
3. **Objeto(s) de conhecimento mobilizado(s):** _…_
4. **Desvio ou erro encontrado + causa técnica:** _…_
5. **Decisão de ajuste + fonte:** _…_
6. **Feedback recebido e o que mudei:** _…_
7. **Próximo passo:** _…_

### 🧩 CAMPO 05 — Registro de Revisão por Pares
*Adaptação do **Logbook do Time** (Apêndice C) para o CRUD individual. Documento atualizado pelo **revisor**. Cada decisão técnica relevante deve ter associado o objeto de conhecimento correspondente.*

> ⚠️ **Nota de adaptação:** o Apêndice C original prevê Gestor, Responsável Técnico, Analista de Qualidade e Comunicador. Como o CRUD é **individual** e os alunos atuam como **revisores**, mantive os blocos 5a a 5e e troquei os papéis por **Autor** (dono do CRUD) e **Revisor** (você). *Pendente de validação do professor/NDE.*

> **O Logbook de revisão é um registro de conhecimento em ação.** Cada decisão técnica relevante deve estar associada ao objeto de conhecimento que a fundamenta, à justificativa técnica e à referência utilizada. Registros sem esse vínculo não são aceitos.

#### Revisão nº 1

| | |
|---|---|
| **Autor do CRUD revisado** | _nome_ |
| **Repositório revisado** | _link_ |
| **Revisor** | _seu nome_ |
| **Unidade curricular / Semestre** | Algoritmos e Programação · 2026.2 |
| **Ciclo / data** | _Ciclo 09 · 21/10_ |

**5a. AVANÇO DO PROCESSO DE REVISÃO — análise técnica de cada etapa:**

| ETAPA DO PROCESSO | RESPONSÁVEL | PRAZO | STATUS | DESVIO / JUSTIFICATIVA |
|---|---|---|---|---|
| 1. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |
| 2. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |
| 3. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |
| 4. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |
| 5. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |

**5b. ANÁLISE DE INSUMOS E CRITÉRIOS DE QUALIDADE:**

| RECURSO | QTDE PLANEJADA | QTDE UTILIZADA | VARIAÇÃO | JUSTIFICATIVA TÉCNICA |
|---|---|---|---|---|
| _…_ | _…_ | _…_ | _…_ | _…_ |
| _…_ | _…_ | _…_ | _…_ | _…_ |
| _…_ | _…_ | _…_ | _…_ | _…_ |

**5c. CONTROLE DE QUALIDADE:**
- **Critério ou norma técnica:** _…_
- **A solução atende?** ☐ Sim ☐ Parcialmente ☐ Não

**5d. GESTÃO DE RISCOS:**
- **Risco:** _…_
- **Estratégia de mitigação:** _…_

**5e. RASTREABILIDADE DAS DECISÕES TÉCNICAS — COM VÍNCULO AO CONTEÚDO:**

| DATA | DECISÃO TÉCNICA | RESP. | OBJETO DE CONHECIMENTO MOBILIZADO | FUNDAMENTAÇÃO / REFERÊNCIA |
|---|---|---|---|---|
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |

> **IMPORTANTE:** Decisão registrada sem objeto de conhecimento associado e sem referência é considerada **não rastreável** e não conta para a avaliação formativa. O vínculo entre processo e conteúdo é obrigatório em todas as decisões relevantes.

## 🔵 CICLO 10 — 28/10 — Modularização: funções

<details>
<summary>📘 Orientações do Ciclo 10</summary>

- **Sem Campo do Protocolo hoje.** Preencha o Registro do Ciclo 10.
- Explique **como dividiu** o CRUD em funções (`cadastrar()`, `buscar()`, `alterar()`, `excluir()`, `listar()`, `menu()`) e **por que** cada função tem aquela responsabilidade.
- Item 4: erros típicos — variável fora de escopo, função sem `return`, parâmetro na ordem errada.
- Compare o código **antes e depois** da refatoração: o que ficou mais claro? Registre no item 6 o feedback do colega que fez a *peer review*.
</details>

#### Registro do Ciclo 10 — 28/10
1. **Desafio do ciclo (em 1 frase):** _…_
2. **O que implementei (commits / arquivos / links):** _…_
3. **Objeto(s) de conhecimento mobilizado(s):** _…_
4. **Desvio ou erro encontrado + causa técnica:** _…_
5. **Decisão de ajuste + fonte:** _…_
6. **Feedback recebido e o que mudei:** _…_
7. **Próximo passo:** _…_

## 🔵 CICLO 11 — 04/11 — Recursividade

<details>
<summary>📘 Orientações do Ciclo 11 — Registro + Campo 06 (Grupo 3)</summary>

- Preencha o Registro do Ciclo 11 (caso base, chamada recursiva, pilha de execução).
- **Campo 06 — Próximos passos para a defesa** · *individual · quinta 26/11, 23h59*. Prepare-se para a **Defesa Técnica de quarta 18/11**: como o prazo é posterior à defesa, **adiante pelo menos o 6c** (pergunta da banca e resposta) e leve-o para a arguição.
  - **6a.** Uma **decisão técnica que você defende com plena autonomia**: algo que aprendeu e **é exclusivamente seu**, que nenhum colega consegue explicar por você.
  - **6b.** Uma **lacuna técnica real** e um **plano de ação** com passos e datas para saná-la antes da defesa.
  - **6c.** Uma **pergunta que a banca pode fazer** (nível de Avaliação ou Criação) e a sua **resposta fundamentada em, no mínimo, 5 linhas**, com o objeto de conhecimento e a fonte.
  - Dica: leia a **Rubrica de Defesa Técnica** (no Encerramento) e escolha uma pergunta que teste *aplicação*, *evolução* ou *transferência*.
</details>

#### Registro do Ciclo 11 — 04/11
1. **Desafio do ciclo (em 1 frase):** _…_
2. **O que implementei (commits / arquivos / links):** _…_
3. **Objeto(s) de conhecimento mobilizado(s):** _…_
4. **Desvio ou erro encontrado + causa técnica:** _…_
5. **Decisão de ajuste + fonte:** _…_
6. **Feedback recebido e o que mudei:** _…_
7. **Próximo passo:** _…_

### 🧩 CAMPO 06 — Próximos passos para a defesa
*AV Qualis — Grupo 3 | Individual | Quinta 26/11, 23h59*

**6a. Decisão técnica que defendo com plena autonomia — o que aprendi que é exclusivamente meu e não consigo transferir para nenhum colega:**

> _…_

**6b. Lacuna técnica e plano de ação para saná-la:**

- **Lacuna:** _…_
- **Plano de ação (passos e datas):** _…_

**6c. Pergunta que a banca pode fazer — com resposta fundamentada (mínimo 5 linhas):**

- **Pergunta:** _…_
- **Resposta:**

> _…_

**Objeto de conhecimento mobilizado:** _…_
**Fonte:** _…_

## 🔵 CICLO 12 — 11/11 — Refatoração e qualidade de código

<details>
<summary>📘 Orientações do Ciclo 12 — Registro + Campo 05 (revisão nº 2) + início do Campo 07</summary>

- Preencha o Registro do Ciclo 12. Registre o que revisou: código duplicado, nomes ruins, funções grandes, comentários desnecessários, lógica confusa.
- **Campo 05 — Revisão por pares nº 2.** Foque em **qualidade**: o CRUD do colega resiste aos casos de teste (mínimos, máximos, inválidos, entradas vazias) e ao **lote de dados com defeito**? Use a seção abaixo (copie o bloco *Revisão nº 1* do Ciclo 09 e preencha novamente).
- **Campo 07 — Evolução conceitual** · *individual · quinta 26/11, 23h59.* Comece agora, enquanto a memória do semestre está fresca; leve o rascunho de 7a e 7b para a Defesa de 18/11. Dicas por item:
  - **7a.** Releia o **Campo 01** e resuma o que você *pensava* e *achava que sabia*. Seja honesto, mesmo se o Campo 01 estiver "errado".
  - **7b.** Pelo menos **3 objetos de conhecimento** na tabela: o que você *não dominava*, o que *aprendeu e consegue demonstrar* e a **evidência** (em qual Campo ou ciclo do Logbook aparece).
  - **7c.** Pelo menos **2 equívocos corrigidos**, dizendo **o que os corrigiu** (Fechamento Teórico, pesquisa, *Peer Review*, arguição, devolutiva da P1).
  - **7d.** **Transferência:** um exemplo concreto de aplicar o que aprendeu em um **contexto diferente** do CRUD (outra área do seu curso ou outro tipo de sistema).
  - **7e.** Avaliação honesta do que **ainda não domina** e vai aprofundar.
</details>

#### Registro do Ciclo 12 — 11/11
1. **Desafio do ciclo (em 1 frase):** _…_
2. **O que implementei (commits / arquivos / links):** _…_
3. **Objeto(s) de conhecimento mobilizado(s):** _…_
4. **Desvio ou erro encontrado + causa técnica:** _…_
5. **Decisão de ajuste + fonte:** _…_
6. **Feedback recebido e o que mudei:** _…_
7. **Próximo passo:** _…_

### 🧩 CAMPO 05 — Registro de Revisão por Pares (revisão nº 2)

| | |
|---|---|
| **Autor do CRUD revisado** | _nome_ |
| **Repositório revisado** | _link_ |
| **Revisor** | _seu nome_ |
| **Ciclo / data** | _Ciclo 12 · 11/11_ |

**5a. AVANÇO DO PROCESSO DE REVISÃO:**

| ETAPA DO PROCESSO | RESPONSÁVEL | PRAZO | STATUS | DESVIO / JUSTIFICATIVA |
|---|---|---|---|---|
| 1. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |
| 2. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |
| 3. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |
| 4. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |
| 5. _…_ | Revisor / Autor | _DD/MM_ | ☐ Concluída ☐ Em andamento ☐ Com desvio | _…_ |

**5b. ANÁLISE DE INSUMOS E CRITÉRIOS DE QUALIDADE:**

| RECURSO | QTDE PLANEJADA | QTDE UTILIZADA | VARIAÇÃO | JUSTIFICATIVA TÉCNICA |
|---|---|---|---|---|
| _…_ | _…_ | _…_ | _…_ | _…_ |
| _…_ | _…_ | _…_ | _…_ | _…_ |
| _…_ | _…_ | _…_ | _…_ | _…_ |

**5c. CONTROLE DE QUALIDADE:**
- **Critério ou norma técnica:** _…_
- **A solução atende?** ☐ Sim ☐ Parcialmente ☐ Não

**5d. GESTÃO DE RISCOS:**
- **Risco:** _…_
- **Estratégia de mitigação:** _…_

**5e. RASTREABILIDADE DAS DECISÕES TÉCNICAS — COM VÍNCULO AO CONTEÚDO:**

| DATA | DECISÃO TÉCNICA | RESP. | OBJETO DE CONHECIMENTO MOBILIZADO | FUNDAMENTAÇÃO / REFERÊNCIA |
|---|---|---|---|---|
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |
| _DD/MM/AA_ | _…_ | _…_ | _…_ | _…_ |

### 🧩 CAMPO 07 — Evolução conceitual
*AV Qualis — Grupo 3 | Individual | Quinta 26/11, 23h59*

*Evidência rastreável de aprendizagem entre o início e o encerramento do ciclo AFP.*

**7a. O que eu pensava no início do ciclo (com base no Campo 01 — registrar a hipótese inicial e os objetos de conhecimento que achava conhecer):**

> _…_

**7b. O que aprendi — conceitos, princípios ou relações técnicas que não dominava no início e que agora consigo explicar com precisão (mínimo 3 objetos de conhecimento):**

| OBJETO DE CONHECIMENTO | O QUE EU NÃO DOMINAVA | O QUE APRENDI E CONSIGO DEMONSTRAR | EVIDÊNCIA (campo do Logbook onde aparece) |
|---|---|---|---|
| _…_ | _…_ | _…_ | _…_ |
| _…_ | _…_ | _…_ | _…_ |
| _…_ | _…_ | _…_ | _…_ |

**7c. Conceitos que precisei corrigir ao longo do ciclo — onde eu estava equivocado e o que o corrigiu (Fechamento Teórico, pesquisa, Peer Review, arguição):**

1. **Equívoco:** _…_ — **Correção:** _…_
   **O que corrigiu:** _…_
2. **Equívoco:** _…_ — **Correção:** _…_
   **O que corrigiu:** _…_

**7d. Transferência — como este aprendizado se aplica a um contexto diferente do problema trabalhado (ao menos 1 exemplo concreto da área de formação):**

> _…_

**7e. Avaliação honesta do próprio percurso — o que ainda não domino e preciso aprofundar após este ciclo:**

> _…_

---

# 🏁 DEFESA TÉCNICA — quarta 18/11

<details>
<summary>📘 Orientações para a Defesa Técnica e preparação</summary>

**A Defesa é antes dos prazos dos Grupos 2 e 3.** Você será arguido sobre o que já estiver registrado e commitado. Priorize, até **terça 17/11**:
- [ ] **Grupo 1 entregue** (prazo 16/11): Identificação, Registros 01 a 04, Campos 01 e 02.
- [ ] **Campo 04 (IA)** e **Campo 03** ao menos em rascunho, para sustentar as perguntas sobre decisões (critérios 2 e 5).
- [ ] **Campo 06c** (pergunta da banca e resposta) e **rascunho de 7a e 7b**, para sustentar a evolução conceitual (critério 3).
- [ ] Registros dos Ciclos já feitos, mesmo que ainda não "entregues" no prazo do grupo.
- [ ] `README.md`, `docs/` e CRUD rodando.
- [ ] Você consegue explicar **cada linha** do seu código e **cada decisão** registrada.
- Os demais itens seguem com os prazos dos grupos (21/11 e 26/11). A banca pode consultar o histórico do Git.

**A Defesa Técnica é individual.** Você será arguido sobre o que registrou. Cada aluno recebe pelo menos **1 questão** nos níveis de **Avaliação** ou **Criação** (taxonomia de Bloom).

**Como a Rubrica se liga ao seu Logbook:**

| Critério da Rubrica | Onde você prepara a evidência |
|---|---|
| 1. Domínio dos objetos de conhecimento | Campos 01, 02 e 07b |
| 2. Aplicação do conteúdo à solução ⚠️ *inegociável* | Registros dos ciclos (itens 3 e 5), Campo 03c e Campo 05e |
| 3. Evolução conceitual ⚠️ *inegociável* | Campo 01 → Campo 07 (7a, 7b e 7c; leve o rascunho) |
| 4. Capacidade de transferência | Campo 07d |
| 5. Argumentação sob pressão | Campo 06c e Campo 04e |
| 6. Autonomia intelectual e coerência com o Logbook | Todo o Logbook (principalmente Campos 04 e 06a) |

**Treino:** peça a um colega que faça 3 perguntas "imprevistas" sobre o seu CRUD e responda **sem consultar** o Logbook. Se não conseguir, volte ao Campo 06b.
</details>

## 🧩 RUBRICA DE DEFESA TÉCNICA (revisada)
*Avaliação individual de cada membro na Semana 16. Cada membro recebe ao menos 1 questão nos níveis de Avaliação ou Criação da Taxonomia de Bloom. Critérios revisados para medir aprendizagem, aplicação, evolução e transferência do conteúdo.*

| | |
|---|---|
| **Nome** | _…_ |
| **Curso / Time / Função** | _…_ |

<details>
<summary>🔒 Uso do professor — rubrica completa</summary>

| CRITÉRIO | EXCELENTE (4,0) | SATISFATÓRIO (3,0) | INSATISFATÓRIO (2,0) | AUSENTE (0) |
|---|---|---|---|---|
| **1. DOMÍNIO DOS OBJETOS DE CONHECIMENTO** — Responde com precisão técnica, sem apoio dos colegas, demonstrando aprendizagem do conteúdo. | Responde com precisão e profundidade, nomeando os objetos de conhecimento mobilizados sem hesitação. | Responde com precisão, com imprecisões pontuais que não comprometem o raciocínio. | Responde de forma vaga, com erros conceituais relevantes ou dependendo dos colegas. | Não responde ou demonstra desconhecimento total. |
| **2. APLICAÇÃO DO CONTEÚDO À SOLUÇÃO** — Demonstra como os objetos de conhecimento fundamentaram as decisões do processo. | Explicita com precisão qual objeto de conhecimento fundamentou cada decisão relevante do processo investigativo, citando referência e demonstrando por que aquele conhecimento era o mais adequado. | Estabelece a relação conteúdo-decisão na maioria das perguntas, com alguma imprecisão pontual. | Não consegue explicitar a relação entre o conteúdo e as decisões do processo investigativo com clareza. | Não demonstra nenhuma relação entre os objetos de conhecimento e as decisões tomadas. |
| **3. EVOLUÇÃO CONCEITUAL** — Demonstra aprendizagem em relação ao que sabia no início do ciclo. | Identifica com precisão o que aprendeu, o que corrigiu e como o conhecimento evoluiu ao longo do ciclo. | Demonstra evolução em parte dos conceitos trabalhados, com alguma dificuldade de articular a trajetória. | Dificuldade em identificar diferenças entre o que sabia no início e o que domina agora. | Não demonstra nenhuma percepção de evolução conceitual ao longo do ciclo. |
| **4. CAPACIDADE DE TRANSFERÊNCIA** — Aplica o conhecimento a um contexto diferente do problema trabalhado. | Consegue transferir o aprendizado para um contexto novo com fundamentação técnica precisa. | Realiza a transferência com imprecisões que não comprometem a lógica do raciocínio. | Demonstra dificuldade em aplicar o conhecimento a contextos diferentes do problema original. | Não consegue realizar nenhuma transferência do conhecimento para contexto diferente. |
| **5. ARGUMENTAÇÃO SOB PRESSÃO** — Mantém coerência técnica diante de questionamentos imprevistos. | Mantém raciocínio coerente, reconhece limites com honestidade e reformula com fundamentação. | Mantém coerência na maior parte, com hesitações pontuais sem perda do fio técnico. | Fragilidade técnica diante de questionamentos imprevistos. | Não sustenta argumentação técnica diante de nenhum questionamento. |
| **6. AUTONOMIA INTELECTUAL E COERÊNCIA COM O LOGBOOK** — Defende o que registrou com consciência e sem depender do grupo. | Defende com precisão as decisões do Logbook, demonstrando autoria plena e independência intelectual. | Defende a maioria das decisões com coerência, com alguma imprecisão ou apoio pontual. | Depende dos colegas ou demonstra desconhecimento de parte do que registrou no próprio Logbook. | Não reconhece o que registrou ou não demonstra autonomia intelectual durante a arguição. |

**PONTUAÇÃO:** _____ / 24,0 **CONCEITO:** _____________

**Conversão:** 20–24 = Excelente (4,0) | 14–19 = Satisfatório (3,0) | 8–13 = Insatisfatório (2,0) | < 8 = Ausente (0)

> ⚠️ **Critérios 2 (Aplicação) e 3 (Evolução Conceitual) são inegociáveis — AUSENTE em qualquer um deles implica nota máxima de 2,0 na Defesa, independentemente do desempenho nos demais.**

**OBSERVAÇÕES:** _…_

**Professor(a):** _________________  **Data:** ___________
</details>

### Registro do Encerramento — 18/11
1. **O que apresentei/defendi (em 1 frase):** _…_
2. **Objeto(s) de conhecimento que a banca mais explorou:** _…_
3. **Pergunta que mais me desafiou e como respondi:** _…_
4. **O que levo deste semestre para o próximo módulo:** _…_

---

# 🆘 Estou atrasado no Logbook. E agora?

1. **Não apague nem "retroescreva" o passado.** Preencha agora e **escreva a data real** do preenchimento (ex.: *"preenchido com atraso em 12/11"*).
2. **Campo 01 e Checkpoint (sem consulta):** se perdeu a janela, registre **o que sabe hoje, sem consultar nada**, marcando-o como *preenchimento tardio*. Combine o tratamento com o professor.
3. **Priorize a ordem dos grupos:** Grupo 1 (16/11) → Defesa (18/11) → Grupo 2 (21/11) → Grupo 3 (26/11). Dentro de cada grupo, os Campos vêm antes dos Registros.
4. **Use o histórico do Git** (`git log --oneline`) para reconstruir o que fez em cada ciclo — ele é uma evidência melhor que a memória.
5. **Fale com o professor** antes do prazo, não depois.
