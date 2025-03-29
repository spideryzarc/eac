---
marp: true
title: "Lógica Proposicional"
theme: default
class: lead
footer: "F.P. - Albert E. F. Muritiba"
paginate: true
backgroundColor: #d6e0e1
#backgroundImage: url('https://marp.app/assets/hero-background.svg')
# backgroundImage: url('https://spideryzarc.github.io/backgrounds/tt/light_desk.jpg')
style: |
  .small{
    font-size: 0.75rem;
  }
  .big{
    font-size: 1.5rem;
  }
# Deus é bom o tempo todo
---

<!-- _backgroundImage: url('https://spideryzarc.github.io/backgrounds/tt/light_desk.jpg') -->

![bg right](empty.svg)

# Lógica Proposicional

Proposições, conectivos lógicos e tabelas-verdade.

---

## Introdução

### O que é lógica proposicional?

A lógica proposicional trata de **proposições** e suas relações por meio de **conectivos lógicos**.

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

⚠️ $x+1=3$ não é uma proposição, mas um **predicado lógico** — veremos mais adiante.

---

## Representação

- Proposições são representadas por letras: $p$, $q$, $r$, etc.
- Exemplos:
    - $p$: "Está chovendo."
    - $q$: "Está frio."
    - $r$: "2 é um número par."
<br>

> 💡**Convenção**: damos preferência a letras minúsculas começando do $p$. Mas podemos usar qualquer outra letra se for conveniente.

---

## Proposições Simples e Compostas

- **Simples**: não pode ser decomposta em outras proposições.
- **Composta**: formada por proposições simples ligadas por conectivos lógicos.

<br>

> 💡**Convenção**: Usa-se letras minúsculas para proposições simples e letras maiúsculas para proposições compostas.

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
| Negação         | não - *not*               | $\neg p$                   | "não p"                      |
| Conjunção       | e - *and*                 | $p \land q$                | "p e q"                      |
| Disjunção       | ou - *or*                 | $p \lor q$                 | "p ou q"                     |
| Implicação      | se...então - *if*        | $p \rightarrow q$          | "se p, então q"              |
| Bicondicional   | se e somente se - *if only if (iff)*  | $p \leftrightarrow q$      | "p se e somente se q"        |

---

## Negação
A negação de uma proposição $p$ é representada por $\neg p$ e inverte seu valor lógico.

Tabela-verdade:
| $p$ | $\neg p$ |
|-----|----------|
|  V  |    F     |
|  F  |    V     |

> Exemplo:
> "$p$: Está chovendo."
>  $\neg p$: "Não está chovendo."

![bg right:30% drop-shadow 90%](images/not.drawio.svg)

---

## Conjunção (E)
A conjunção de duas proposições $p$ e $q$ é representada por $p \land q$ e é verdadeira apenas se ambas forem verdadeiras.
Tabela-verdade:
| $p$ | $q$ | $p \land q$ |
|-----|-----|--------------|
|  V  |  V  |      V       |
|  V  |  F  |      F       |
|  F  |  V  |      F       |
|  F  |  F  |      F       |

![bg right:30% drop-shadow 90%](images/and.drawio.svg)

---

> Exemplo:
> "$p$: Está chovendo."
> "$q$: Está frio."
> $p \land q$: "Está chovendo **e** está frio."

---

## Disjunção (OU)

A disjunção de duas proposições $p$ e $q$ é representada por $p \lor q$ e é verdadeira se pelo menos uma das proposições for verdadeira.
Tabela-verdade:
| $p$ | $q$ | $p \lor q$ |
|-----|-----|--------------|
|  V  |  V  |      V       |
|  V  |  F  |      V       |
|  F  |  V  |      V       |
|  F  |  F  |      F       |
![bg right:30% drop-shadow 90%](images/or.drawio.svg)
---
> Exemplo:
> "$p$: Está chovendo."
> "$q$: Está frio."
> $p \lor q$: "Está chovendo **ou** está frio."
>
---

**E, OU e NÃO** são conectivos lógicos fundamentais. Contudo, devido à sua importância, é interessante conhecer outros conectivos lógicos. 

---
## Condicional (SE... ENTÃO)
A condicional de duas proposições $p$ e $q$ é representada por $p \rightarrow q$ e é verdadeira, exceto quando $p$ é verdadeira e $q$ é falsa.

Tabela-verdade:
| $p$ | $q$ | $p \rightarrow q$ |
|-----|-----|--------------------|
|  V  |  V  |         V          |
|  V  |  F  |         F          |
|  F  |  V  |         V          |
|  F  |  F  |         V          |
![bg right:30% drop-shadow 90%](images/if.drawio.svg)

---

> Exemplo:
> "$p$: Está chovendo."
> "$q$: Está frio."
> $p \rightarrow q$: "Se está chovendo, então está frio."
>

<br>

Este conectivo é muito importante, por isso vamos analisá-lo com mais cuidado.

---

### Condição Necessária e Suficiente

Suponha que a proposição abaixo seja verdadeira:
> $p \rightarrow q$: "Se está chovendo, então está frio."

- O que você pode concluir, se eu afirmar:
  * "Está chovendo."?
    * Você pode concluir que "Está frio." ✅
  * "Não está frio."?
    * Você pode concluir que "Não está chovendo." ✅ 







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
