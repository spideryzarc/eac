---
marp: true
theme: default
paginate: true
math: true
---

# Lógica Proposicional

---

## Introdução à Lógica Proposicional

### Por que estudar lógica proposicional?

- **Treinamento simbólico**: desenvolve a capacidade de representar ideias complexas com clareza e precisão por meio de símbolos e regras formais.
- **Domínio das regras do pensamento**: promove o raciocínio estruturado, coerente e rigoroso, essencial para argumentação e demonstração matemática.
- **Facilidade no entendimento de linguagens formais**: prepara o estudante para compreender e utilizar linguagens matemáticas e computacionais, como linguagens de programação, expressões regulares e notações científicas formais.

A lógica proposicional é um ramo da lógica que trata de proposições declarativas e de suas relações por meio de conectivos lógicos. É fundamental para a matemática, a filosofia, a ciência da computação e áreas que dependem de raciocínio formal.

> **Proposição** é uma sentença declarativa que pode ser classificada como **verdadeira (V)** ou **falsa (F)**, mas não ambas simultaneamente.

---

## Exemplos de Proposições

- "2 é um número par." ✅ (V)
- "O Sol gira em torno da Terra." ❌ (F)
- "Feche a porta!" ❌ (não é proposição - é uma ordem)
- "\(x + 1 = 3\)" ❌ (não é proposição enquanto \(x\) não estiver definido)

---

## Proposições Simples e Compostas

- **Proposição simples**: não contém conectivos lógicos.  
  Ex: "A terra é redonda."
- **Proposição composta**: formada por proposições simples ligadas por conectivos.  
  Ex: "A terra é redonda E gira em torno do Sol."

---

## Conectivos Lógicos

| Conectivo | Nome               | Símbolo       | Leitura                      |
|-----------|--------------------|----------------|-------------------------------|
| Negação   | não                | \(\neg p\)     | "não p"                      |
| Conjunção | e                  | \(p \land q\)  | "p e q"                      |
| Disjunção | ou                 | \(p \lor q\)   | "p ou q"                     |
| Implicação| se...então         | \(p \rightarrow q\) | "se p, então q"        |
| Bicondicional | se e somente se | \(p \leftrightarrow q\) | "p se e somente se q" |

---

## Tabelas-Verdade

A tabela-verdade mostra todos os valores lógicos possíveis de uma proposição composta.

### Exemplo: Conjunção \(p \land q\)

| \(p\) | \(q\) | \(p \land q\) |
|------|------|----------------|
|  V   |  V   |       V        |
|  V   |  F   |       F        |
|  F   |  V   |       F        |
|  F   |  F   |       F        |

---

## Exercício

Considere as proposições abaixo:

- \(p\): "O número 3 é primo"
- \(q\): "4 é um número ímpar"

Construa a tabela-verdade para as seguintes expressões:

1. \(\neg p\)
2. \(p \land q\)
3. \(p \lor q\)
4. \(p \rightarrow q\)

Verifique quais proposições compostas são verdadeiras em todos os casos.

---

## Próximos Tópicos

- Tabelas-verdade dos demais conectivos
- Equivalências lógicas fundamentais
- Validade de argumentos
- Exercícios resolvidos
