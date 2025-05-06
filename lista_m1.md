# Lista de exercícios 1 

**Conteúdo:** 
- Lógica Proposicional: proposições, conectivos lógicos, tabelas-verdade, equivalências lógicas
- Quantificadores: quantificadores existencial e universal, negação de quantificadores
- Notações somatório e produtório: definições, propriedades, exemplos
- Indução Matemática: princípios de indução, provas por indução
- Teoria dos Conjuntos: subconjuntos, cardinalidade, operações, diagramas de Venn


# Lógica Proposicional e Quantificadores

## Parte 1 – Regras de Inferência

Identifique a regra de inferência ilustrada em cada argumento abaixo:

1. Se Martins é o autor, então o livro é de ficção. Mas o livro não é de ficção. Portanto, Martins não é o autor.
2. Se a firma falir, todos os seus ativos têm que ser confiscados. A firma faliu. Logo, todos os ativos foram confiscados.
3. O cachorro tem pelo sedoso e adora latir. Portanto, o cachorro adora latir.
4. Se Paulo é um bom nadador, então ele é um bom corredor. Se Paulo é um bom corredor, então ele é um bom ciclista. Portanto, se Paulo é um bom nadador, então ele é um bom ciclista.

## Parte 2 – Justificação e Demonstração

Justifique cada passo na sequência de demonstração abaixo:

$$
\begin{align*}
H_1 & & \neg A\\
H_2 & & B\\
H_3 & & B \rightarrow (A\lor C)\\
\therefore & & C\\
\hline
1. && A \lor C & \underline{\hspace{2cm}}\\
2. && C & \underline{\hspace{2cm}}\\
\end{align*}
$$

## Parte 3 – Avaliação Lógica de Proposições

Determine o valor lógico das proposições abaixo, considerando o conjunto universo como todos os inteiros:

1. $(\exists x)(I(x))$
2. $(\forall x)[L(x) \rightarrow I(x)]$
3. $(\exists x)[L(x) \land G(x)]$
4. $(\forall x)[L(x) \lor G(x)]$

Considere:
- $I(x)$: x é ímpar
- $L(x)$: x < 0
- $G(x)$: x > 9

## Parte 4 – Tradução para linguagem natural

Sejam as proposições:
- A: "O livro é interessante"
- B: "O livro é caro"

Traduza para a linguagem natural:

1. $\neg A$
2. $A \land B$
3. $A\lor B$
4. $B\lor (\neg A)$
5. $(\neg A) \land (\neg B)$

## Parte 5 – Determinação da Negação

Determine a negação correta para as sentenças abaixo:

1. Estou feliz.
2. Todos os elefantes são cor-de-rosa.
3. Alguns cavalos são brancos.
4. Todos os cavalos são pretos.
5. O sol está brilhando.

## Parte 6 – Tabela-verdade

Faça a tabela-verdade para as sentenças a seguir:

1. $(A \rightarrow B)$
2. $(A \leftrightarrow B)$

## Parte 7 – Tradução de frases em linguagem simbólica

Traduza as frases abaixo para a linguagem simbólica:

1. É verão somente se está calor.
2. Uma condição necessária para estar calor é que seja verão.
3. Nunca é verão quando está calor.

Considere:
- A: "Está calor"
- B: "É verão"

## Parte 8 – Exercícios de interpretação lógica

Analise logicamente as proposições e indique sua veracidade:

1. $(5+4=9 \land 2 \leq 4)$
2. $(3+2=6 \land 2+2=4)$
3. $(5+3=7\lor 4+4=7)$
4. $(4+3=7\lor 2+3=4)$

## Parte 9 – Uso dos quantificadores

Escreva cada afirmação em forma simbólica, usando quantificadores:

1. Todos os dias são ensolarados.
2. Alguns dias são chuvosos.
3. Nenhum dia é ensolarado e chuvoso ao mesmo tempo.

Considere:
- $D(x)$: x é um dia.
- $S(x)$: x é ensolarado.
- $C(x)$: x é chuvoso.

## Parte 10 – Provas e validação

Use lógica proposicional para provar que cada argumento é válido:

### Argumento 1
$$
\begin{align*}
H_1 & & \neg A\\
H_2 & & B \rightarrow A\\
\therefore & & \neg B\\
\hline
\end{align*}
$$

### Argumento 2
$$
\begin{align*}
H_1 & & A \rightarrow (B \rightarrow C)\\
H_2 & & A\lor \neg D\\
H_3 & & B\\
\therefore & & D \rightarrow C\\
\hline
\end{align*}
$$

### Argumento 3
$$
\begin{align*}
H_1 & & \neg A \rightarrow \neg B\\
H_2 & & B\\
H_3 & & A \rightarrow C\\
\therefore & & C\\
\hline
\end{align*}
$$

### Argumento 4
$$
\begin{align*}
H_1 & & P\lor \neg Q\\
H_2 & & Q\\
\therefore & & P\\
\hline
\end{align*}
$$

### Argumento 5
$$
\begin{align*}
H_1 & & P \rightarrow Q\\
H_2 & & Q \rightarrow R\\
\therefore & & P \rightarrow R\\
\hline
\end{align*}
$$

### Argumento 6
$$
\begin{align*}
H_1 & & P \rightarrow \neg Q\\
H_2 & & P\\
\therefore & & \neg Q\\
\hline
\end{align*}
$$

### Argumento 7
$$
\begin{align*}
H_1 & & \neg P \rightarrow Q\\
H_2 & & Q \rightarrow \neg R\\
\therefore & & \neg P \rightarrow \neg R\\
\hline
\end{align*}
$$

### Argumento 8
$$
\begin{align*}
H_1 & & P\lor Q\\
H_2 & & \neg P\\
\therefore & & Q\\
\hline
\end{align*}
$$

# Somatório e Indução Matemática

## Parte 1 – Propriedades do Somatório

Determine o valor de cada somatório abaixo:

1. $\sum_{i=1}^{10} i$
2. $\sum_{i=1}^{5} (2i + 3)$
3. $\sum_{i=2}^{2} (3i^2 + 2i + 1)$
4. $\sum_{i=1}^{100} 12$

Verifique se as equivalências abaixo são verdadeiras:

5. $\sum_{i=1}^{n} (a_i + b_i) = \sum_{i=1}^{n} a_i + \sum_{i=1}^{n} b_i$
6. $\sum_{i=1}^{n} (a_i \cdot b_i) = \sum_{i=1}^{n} a_i \cdot \sum_{i=1}^{n} b_i$
7. $\sum_{i=1}^{3} a_i + \sum_{i=4}^{n} a_i = \sum_{i=1}^{n} a_i$
8. $\sum_{i=1}^{n} a_i = \sum_{i=1}^{n-1} a_i +  a_n$
9. $\sum_{i=1}^{n} a_i = \sum_{i=0}^{n-1} a_{i+1}$
10. $(\sum_{i=1}^{n} a_i)^2 = \sum_{i=1}^{n} a_i^2$

## Parte 2 – Prova por Indução Matemática

Prove por indução matemática as seguintes afirmações:

### Somatório

11. A soma dos n primeiros números naturais é dada por $\frac{n(n+1)}{2}$.
12. A soma dos n primeiros números ímpares é dada por $n^2$.
13. A soma dos n primeiros números pares é dada por $n(n+1)$.
14. A soma dos n primeiros números quadrados é dada por $\frac{n(n+1)(2n+1)}{6}$.
15. $\sum_{i=1}^{n} i.2^{i-1} = (n-1)2^n + 1$

### Divisibilidade

16. $n^3+ 2n$ é divisível por 3 para todo n natural.
17. $4^n+6n-1$ é divisível por 9 para todo n natural.
18. $2^{2n} - 1$ é divisível por 3 para todo n natural.


# Conjuntos e Teoria dos Conjuntos

## Parte 1 – Elementos e Conjuntos

Seja: 
- $A = \{1, 2, 3\}$
- $B = \{\emptyset, 1, 2\}$
- $C = \{\{1, 2, 3\}, 1, 2, 3, 4\}$

Marque V (verdadeiro) ou F (falso) para cada uma das afirmações abaixo:
1. $A \subset B$  
2. $B \subset A$
3. $A \subset C$
4. $C \subset A$
5. $A \in B$
6. $B \in A$
7. $C \in A$
8. $A \in C$
9. $A \cap B = \emptyset$
10. $(A \cap C) \in C$
11. $A \cup B = \{1, 2, 3\}$
12. $B \subsetneq A$

## Parte 2 – Conjuntos e Lógica Proposicional


### Conjuntos e Lógica Proposicional

Qual lei lógica dá respaldo a cada uma das afirmações abaixo?

1. $(A \subset B) \land (x \in A) \implies (x \in B)$
2. $(A \cap B) \subset A$
3. $A \subset (A \cup B)$
4. $A' \subset B' \equiv A \supset B$
5. $A \cap (B \cup C) = (A \cap B) \cup (A \cap C)$
6. $A' \cup B' = (A \cap B)'$
7. $A \subset B \equiv x \notin A \lor x \in B$
8. $A \cap A' = \emptyset$
9. $A \cup A' = U$
10. $A \cap (B \cap C) = (A \cap B) \cap C$
11. $x \in (A \cup B) \land x \notin A \implies x \in B$


### Definições das operações de conjuntos

A quais definições correspondem as afirmações abaixo?

1. $(\forall x)(x \in A \rightarrow x \in B)$
2. $(\forall x)(x \in A \leftrightarrow x \in B)$
3. $\{x |x \in A \land x \in B\}$
4. $\{x |x \in A \lor x \in B\}$
5. $\{x |x \in A \land x \notin B\}$
6. $(\forall x)(x \in A \rightarrow x \in B)\land  (\exists x)(x \in B \land x \notin A)$
