---
marp: true
theme: default
paginate: true
math: true
---

# Lógica Proposicional

Proposições, conectivos lógicos e tabelas-verdade.

---

## Introdução

### O que é lógica proposicional?

A lógica proposicional trata de proposições e suas relações por meio de conectivos lógicos.

É base para áreas como:
- Matemática
- Filosofia
- Ciência da computação

---

## O que é uma proposição?

> 💬 Sentença declarativa que pode ser **verdadeira (V)** ou **falsa (F)**, mas nunca ambas.

---

## Exemplos

- "Feche a porta!" ❌ (ordem — não é proposição)
- "$x + 1 = 3$" ❌ (não é proposição **sem** valor definido para $x$)
- "2 é um número par." ✅
- "3 é um número par." ✅
- "A chuva está forte." ✅

⚠️ $x+1=3$ não é uma proposição, mas um predicado — veremos mais adiante.

---

## Proposições Simples e Compostas

- **Simples**: não pode ser decomposta em outras proposições.
- **Composta**: formada por proposições simples ligadas por conectivos lógicos.

---

## Exemplos

- **Simples**: 
    - "Está chovendo."
    - "Está frio."
    - "2 é um número par."
- **Compostas**: 
    - "Está chovendo **e** está frio."
    - "2 é um número par **ou** 3 é um número ímpar."
    - "Se chover, então está frio."

---

## Conectivos Lógicos

| Conectivo       | Nome               | Símbolo                   | Leitura                      |
|------------------|--------------------|----------------------------|------------------------------|
| Negação         | não                | $\neg p$                   | "não p"                      |
| Conjunção       | e                  | $p \land q$                | "p e q"                      |
| Disjunção       | ou                 | $p \lor q$                 | "p ou q"                     |
| Implicação      | se...então         | $p \rightarrow q$          | "se p, então q"              |
| Bicondicional   | se e somente se    | $p \leftrightarrow q$      | "p se e somente se q"        |

---

## Uso informal vs. formal

⚠️ Conectivos lógicos são aproximações formais da linguagem cotidiana.  
Nem sempre seu uso na lógica corresponde ao uso informal.

---

## "Ou" – Disjunção

- No uso comum, “ou” pode significar exclusão: **um ou outro, mas não ambos**.
- Na lógica, $p \lor q$ é **inclusivo**: verdadeiro mesmo se ambos forem verdadeiros.

**Exemplo**:  
> "Você pode escolher fígado ou peixe."  
Na prática: escolha só um.  
Na lógica: ambos são permitidos.

---

## "Se... então" – Implicação

- Cotidianamente, "se... então" sugere causa e consequência.
- Na lógica, $p \rightarrow q$ só é **falsa** se $p$ for verdadeira **e** $q$ for falsa.

**Exemplo**:  
> "Se você estudar, então pode sair."  
Se não estudar e sair, a lógica ainda considera a proposição **verdadeira**.

💡 Mais precisa seria a forma:  
> "Você só pode sair **se e somente se** estudar."  
Representado por $p \leftrightarrow q$.

---

## "E" – Conjunção

- No uso comum, “e” pode implicar ordem temporal.
- Na lógica, $p \land q$ é **comutativo**: a ordem não importa.

**Exemplo**:  
> "Ele acordou e tomou banho."  
> "Ele tomou banho e acordou."

Na prática, essas frases têm significados diferentes.  
Na lógica, são **equivalentes**.

---

## Tabelas-Verdade

A tabela-verdade mostra todos os valores lógicos possíveis de uma proposição composta.

### Exemplo: Conjunção $p \land q$

| $p$ | $q$ | $p \land q$ |
|-----|-----|--------------|
|  V  |  V  |      V       |
|  V  |  F  |      F       |
|  F  |  V  |      F       |
|  F  |  F  |      F       |

---

## Exercício 🧩

Considere as proposições:

- $p$: "O número 3 é primo"
- $q$: "4 é um número ímpar"

Construa a tabela-verdade para:

1. $\neg p$
2. $p \land q$
3. $p \lor q$
4. $p \rightarrow q$

Verifique quais proposições compostas são **sempre verdadeiras**.

---

## Próximos Tópicos 📌

- Tabelas-verdade dos demais conectivos
- Equivalências lógicas fundamentais
- Validade de argumentos
- Exercícios resolvidos
