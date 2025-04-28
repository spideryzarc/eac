# Resultado do OCR

Universidade Estadual de Maringá
Centro de Ciências Exatas
Departamento de Matemática
Exercícios
de
Lógica
![img-0.jpeg](img-0.jpeg)

Organizador: João Roberto Gerônimo
abril de 2007
Maringá - PR

# Introdução 

O objetivo deste material é servir de reforço aos conceitos de lógica desenvolvidos na sala da aula. Os exercícios aqui propostos são de dificuldade baixa, média e alta e devem ser tomados como um complemento aos exercícios do livro. A intenção é proporcionar ao estudante o conhecimento de suas principais lacunas de modo a melhor orientar seu estudo.

Esta lista está dividida em assuntos e seus tópicos e contém exercícios "prováveis", ou seja, é provável que exercícios desse tipo caiam em prova.

Dividimos em temas conforme segue:

- Conceitos
- Tabelas-Verdade
- Método Dedutivo
- Quantificadores
- Problemas Lógicos
- Circuitos Lógicos e Interruptores


## Conceitos

1. O que é Lógica? Para que serve?
2. Para que estudar lógica se eu faço o curso de Matemática?
3. Quais os três princípios que regem a Lógica Clássica?
4. a) O que é o Princípio da Identidade. Exemplifique.
b) O que é o Princípio do Terceiro Excluído. Exemplifique.
c) O que é o Princípio da Não-Contradição. Exemplifique.
5. O que é uma proposição?
6. O que são proposições compostas?
7. Quais as principais maneiras de construir proposições compostas?
8. Sejam as proposições P: "Está chovendo" ,Q: "O sol está brilhando" e R: "Há nuvens no céu". Traduza as seguintes sentenças abaixo em notação lógica:
a) "choverá se o sol brilhar ou se o céu estiver com nuvens".
b) "se está chovendo, então há nuvens no céu."
c) "o sol brilha quando e apenas quando o céu fica com nuvens."
9. Utilizando o exercício anterior, determine significados para as para as proposições:
a) $(\mathrm{P} \wedge \mathrm{Q}) \rightarrow \mathrm{R}$
b) $-\mathrm{P} \leftrightarrow(\mathrm{Q} \vee \mathrm{R})$
c) $-(\mathrm{P} \vee \mathrm{Q}) \wedge \mathrm{R}$
10. Determine os valores lógicos de cada uma das proposições:
a) se $2+2=4$ então $2+4=8$.
b) se $2+2=5$ então $2+4=8$.
c) se $2+2=4$ então $2+4=6$.
d) se $2+2=5$ então $2+4=6$.
11. Suponha que $\mathrm{P} \rightarrow \mathrm{Q}$ seja falso. É possível determinar os valores lógicos de
a) $\mathrm{P} \wedge \mathrm{Q}$.

b) $\mathrm{P} \vee \mathrm{Q}$.
c) $\mathrm{Q} \rightarrow \mathrm{P}$.
12. (FM-2005) Observe as seguintes demonstrações:
I)

Temos $16-36=25-45$.
Somamos $(81 / 4)$ nos dois lados, o que não altera a igualdade.
Assim, $16-36+(81 / 4)=25-45+(81 / 4)$.
Isso pode ser escrito da seguinte forma: $\left(4-(9 / 2)\right)^{2}=(5-$ $(9 / 2))^{2}$.
Tirando a raiz quadrada em ambos os lados temos:4-(9/2) $=5-(9 / 2)$.
Somando (9/2) nos dois lados da igualdade temos:4 $=5$.

II)
Primo notou que o papel de Tornasol ficou vermelho ao ser posto em ácido.
Verificou ainda, que ficou azul ao ser posto em solução alcalina.
Agora, Primo está colocando o papel de Tornasol em uma solução ácida ou alcalina.
Primo observa que o papel não ficou azul.
É claro que o papel ficou vermelho.

Em (I) concluímos que:
A) Desde crianças fomos enganados e de fato $4=5$.
B) Existe algo errado nessa demonstração.

Caso a sua resposta seja a A), ou seja, você foi enganado, o que resta é o chorar.
Se sua resposta foi a B), ou seja, deve haver algum erro nisto, mostre onde ele está e porque.
Em (II), a conclusão está correta? Justifique sua resposta utilizando os operadores lógicos conhecidos por você.

# Tabela Verdade 

13. a) O que é uma tabela verdade?
b) Como se constrói uma tabela verdade?
c) Quantas linhas são utilizadas na construção da tabela verdade?
14. A conjunção de duas proposições $\mathbf{P}$ e $\mathbf{Q}$, denotada por $\mathrm{P} \wedge \mathrm{Q}$, é uma proposição composta que é verdadeira somente quando ambas o são. Construa sua tabela-verdade.
15. A disjunção de duas proposições $\mathbf{P}$ e $\mathbf{Q}$, denotada por $\mathrm{P} \vee \mathrm{Q}$, é uma proposição composta que é verdadeira somente quando uma delas o é. Construa sua tabela-verdade.
16. A negação de uma proposição $\mathbf{P}$, denotada por $\sim \mathrm{P}$, é uma proposição que troca o valor lógicao da proposição original. Construa sua tabela-verdade.
17. A condicional de duas proposições $\mathbf{P}$ e $\mathbf{Q}$, denotada por $\mathrm{P} \rightarrow \mathrm{Q}$, é uma proposição composta que é falsa somente quando a primeira é verdadeira e a segunda é falsa.
18. A bicondicional de duas proposições $\mathbf{P}$ e $\mathbf{Q}$, denotada por $\mathrm{P} \leftrightarrow \mathrm{Q}$, é uma proposição composta que é verdadeira somente quando ambas possuem o mesmo valor lógico
19. a) O que é uma tautologia?
b) O que é uma contradição?
c) O que é uma implicação ou inferência?
d) O que é uma bicondicional ou equivalência lógica?
20. Verifique que $\mathrm{p} \wedge \sim \mathrm{p}$ é uma contradição.
21. As tabelas a seguir estabelecem as principais regras de inferência e equivalências lógicas. Demonstre, utilizando a tabela verdade, cada uma dessas regras.

|  | REGRAS DE INFERÊNCIA |  |  |
| :-- | :-- | :-- | :-- |
| $\mathbf{1}$ | Adição | $\mathrm{P} \Rightarrow \mathrm{P} \vee \mathrm{Q}$ | $\mathrm{Q} \Rightarrow \mathrm{P} \vee \mathrm{Q}$ |
|  | Simplificação | $\mathrm{P} \wedge \mathrm{Q} \Rightarrow \mathrm{P}$ | $\mathrm{P} \wedge \mathrm{Q} \Rightarrow \mathrm{Q}$ |
| $\mathbf{2}$ | Silogismo Disjuntivo | $(\mathrm{P} \vee \mathrm{Q}) \wedge \sim \mathrm{P} \Rightarrow \mathrm{Q}$ |  |
|  | Modus Ponens | $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge \mathrm{P} \Rightarrow \mathrm{Q}$ |  |

|  | ModusTollens | $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge \sim \mathrm{Q} \Rightarrow \sim \mathrm{P}$ |
| :--: | :--: | :--: |
| 3 | Dilemas Construtivos | $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge(\mathrm{R} \rightarrow \mathrm{S}) \Rightarrow(\mathrm{P} \vee \mathrm{R}) \rightarrow(\mathrm{Q} \vee \mathrm{S})$ |
|  |  | $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge(\mathrm{R} \rightarrow \mathrm{S}) \Rightarrow(\mathrm{P} \wedge \mathrm{R}) \rightarrow(\mathrm{Q} \wedge \mathrm{S})$ |
| 4 | Dilemas Destrutivos | $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge(\mathrm{R} \rightarrow \mathrm{S}) \Rightarrow[(\sim \mathrm{Q} \vee \sim \mathrm{S}) \rightarrow(\sim \mathrm{P} \vee \sim \mathrm{R})]$ |
|  |  | $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge(\mathrm{R} \rightarrow \mathrm{S}) \Rightarrow[(\sim \mathrm{Q} \wedge \sim \mathrm{S}) \rightarrow(\sim \mathrm{P} \wedge \sim \mathrm{R})]$ |
| 5 | Lei Tramitiva | $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge(\mathrm{Q} \rightarrow \mathrm{R}) \Rightarrow(\mathrm{P} \rightarrow \mathrm{R})$ |
| 6 | Contradição/Tautologia | $\mathrm{c} \Rightarrow \mathrm{P}$ |
| 7 | Inferência por casos <br> Inferência eliminação | $(\mathrm{Q} \rightarrow \mathrm{P}) \wedge(\mathrm{R} \rightarrow \mathrm{P}) \Rightarrow[(\mathrm{Q} \vee \mathrm{R}) \rightarrow \mathrm{P}]$ |
| 8 | União | $\mathrm{P} \wedge \mathrm{Q} \Rightarrow \mathrm{P} \vee \mathrm{Q}$ |
| 9 | Transitividade | $[\mathrm{P} \Rightarrow \mathrm{Q} \wedge \mathrm{Q} \Rightarrow \mathrm{R}] \Rightarrow(\mathrm{P} \Rightarrow \mathrm{R})$ |
| EQUIVALÊNCIAS LÓGICAS |  |  |
| 1 | Condicional | $\mathrm{P} \rightarrow \mathrm{Q} \Leftrightarrow \sim[\mathrm{P} \wedge(\sim \mathrm{Q})]$ |
| 2 | Bicondicional | $(\mathrm{P} \leftrightarrow \mathrm{Q}) \Leftrightarrow[(\mathrm{P} \rightarrow \mathrm{Q}) \wedge(\mathrm{Q} \rightarrow \mathrm{P})]$ |
| 3 | Lei da dupla negação | $\sim(\sim \mathrm{P}) \Leftrightarrow \mathrm{P}$ |
| 4 | Leis comutativas | $\mathrm{P} \wedge \mathrm{Q} \Leftrightarrow \mathrm{Q} \wedge \mathrm{P}$ |
| 5 | Leis de idempotência | $\mathrm{P} \vee \mathrm{P} \Leftrightarrow \mathrm{P}$ |
| 6 | Lei contrapositiva | $(\mathrm{P} \rightarrow \mathrm{Q}) \Leftrightarrow[(\sim \mathrm{Q}) \rightarrow(\sim \mathrm{P})]$ |
| 7 | Reduci <br> Aba <br> Abaurulum | $(\mathrm{P} \rightarrow \mathrm{Q}) \Leftrightarrow(\mathrm{P} \wedge \sim \mathrm{Q}) \rightarrow \mathrm{c}$ |
| 8 | Leis de De Morgan | $\sim(\mathrm{P} \wedge \mathrm{Q}) \Leftrightarrow[(\sim \mathrm{P}) \vee(\sim \mathrm{Q})]$ |
| 9 | Leis associativas | $(\mathrm{P} \wedge \mathrm{Q}) \wedge \mathrm{R} \Leftrightarrow \mathrm{P} \wedge(\mathrm{Q} \wedge \mathrm{R})$ |
| 10 | Leis distributivas | $\mathrm{P} \wedge(\mathrm{Q} \vee \mathrm{R}) \Leftrightarrow(\mathrm{P} \wedge \mathrm{Q}) \vee(\mathrm{P} \wedge \mathrm{R})$ |
| 11 | Contradição- <br> Tautologia | $\mathrm{P} \wedge \mathrm{t} \Leftrightarrow \mathrm{P}$ |
|  |  | $\mathrm{P} \vee \mathrm{t} \Leftrightarrow \mathrm{t}$ |
| 12 | Substituição | $\left(\mathrm{P} \Leftrightarrow \mathrm{P}^{\prime}\right) \Rightarrow\left[\mathrm{P}\left(\mathrm{p}, \mathrm{q}, \mathrm{r}, \ldots\right) \Leftrightarrow \mathrm{P}\left(\mathrm{p}^{\prime}, \mathrm{q}, \mathrm{r}, \ldots\right)\right]$ |
| 13 | Absorção | $[\mathrm{P} \vee(\mathrm{P} \wedge \mathrm{Q})] \Leftrightarrow \mathrm{P}$ |

22. Diga em cada caso, qual a lei de equivalência está sendo usada.
a) $\sim(\sim(\mathrm{P} \vee \mathrm{Q})) \Leftrightarrow \mathrm{P} \vee \mathrm{Q}$.
b) $(\mathrm{P} \vee \mathrm{Q}) \wedge \sim \mathrm{R} \Leftrightarrow \sim \mathrm{R} \wedge(\mathrm{P} \vee \mathrm{Q})$.
c) $[\mathrm{P} \rightarrow(\mathrm{Q} \leftrightarrow \mathrm{R})] \vee[\mathrm{P} \rightarrow(\mathrm{Q} \leftrightarrow \mathrm{R})] \Leftrightarrow[\mathrm{P} \rightarrow(\mathrm{Q} \leftrightarrow \mathrm{R})]$.
d) $\sim(\sim(\sim \mathrm{P})) \Leftrightarrow \sim \mathrm{P}$.
e) $\mathrm{P} \wedge(\mathrm{Q} \rightarrow \mathrm{R}) \Leftrightarrow(\mathrm{Q} \rightarrow \mathrm{R}) \wedge \mathrm{P}$.
f) $\sim \mathrm{P} \rightarrow(\mathrm{Q} \wedge \mathrm{S}) \Leftrightarrow \sim(\mathrm{Q} \wedge \mathrm{S}) \rightarrow \mathrm{P}$.
g) $(\mathrm{P} \rightarrow \sim \mathrm{Q}) \wedge(\sim \mathrm{R} \wedge \mathrm{S}) \Leftrightarrow[(\mathrm{P} \rightarrow \sim \mathrm{Q}) \wedge \sim \mathrm{R}] \wedge \mathrm{S}$.
h) $\sim \mathrm{P} \wedge \mathrm{Q} \Leftrightarrow \sim(\mathrm{P} \vee \sim \mathrm{Q})$.
i) $[\mathrm{P} \rightarrow(\mathrm{Q} \wedge \mathrm{R}) \wedge(\mathrm{P} \vee \sim \mathrm{P})] \Leftrightarrow \mathrm{P} \rightarrow(\mathrm{Q} \wedge \mathrm{R})$.
j) $(\mathrm{P} \vee \mathrm{R}) \wedge(\mathrm{R} \vee \mathrm{Q}) \Leftrightarrow \mathrm{R} \vee(\mathrm{P} \wedge \mathrm{Q})$.
k) $(\mathrm{P} \wedge \mathrm{Q}) \rightarrow \sim \mathrm{R} \Leftrightarrow \sim(\mathrm{P} \wedge \mathrm{Q} \wedge \mathrm{R})$.
l) $\mathrm{P} \vee \mathrm{Q} \Leftrightarrow \sim(\sim \mathrm{P} \wedge \sim \mathrm{Q})$.
m) $[(P \wedge R) \rightarrow S] \rightarrow \sim Q \Leftrightarrow Q \rightarrow \sim(P \wedge R) \rightarrow S$.
n) $(\mathrm{P} \rightarrow \sim \mathrm{Q}) \Leftrightarrow(\mathrm{P} \wedge \mathrm{Q}) \rightarrow(\mathrm{P} \wedge \sim \mathrm{P})$.
o) $(\sim \mathrm{P} \rightarrow \sim \mathrm{Q}) \vee(\mathrm{Q} \vee \sim \mathrm{Q}) \Leftrightarrow \mathrm{P} \rightarrow \mathrm{P}$.
p) $\sim(\sim \mathrm{P} \wedge(\mathrm{Q} \vee \mathrm{R})) \Leftrightarrow \sim((\sim \mathrm{P} \wedge \mathrm{Q}) \vee(\sim \mathrm{P} \wedge \mathrm{R}))$.
q) $\sim(\mathrm{P} \rightarrow \mathrm{Q}) \wedge \mathrm{R} \Leftrightarrow \sim(\sim \mathrm{R} \vee(\mathrm{P} \rightarrow \mathrm{Q}))$.
r) $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge(\sim \mathrm{Q} \wedge \sim \mathrm{P}) \Leftrightarrow((\mathrm{P} \rightarrow \mathrm{Q}) \wedge \sim \mathrm{Q}) \wedge \sim \mathrm{P}$.
s) $(\mathrm{Q} \wedge \sim \mathrm{R}) \vee(\mathrm{R} \wedge \sim \mathrm{R}) \Leftrightarrow \mathrm{Q} \wedge \sim \mathrm{R}$.
t) $\sim \mathrm{P} \rightarrow(\mathrm{Q} \rightarrow \mathrm{R}) \Leftrightarrow \mathrm{P} \vee(\mathrm{Q} \rightarrow \mathrm{R})$.
23. Diga em cada caso qual a regra de inferência que está sendo usada.
a) $\sim \mathrm{P} \Rightarrow \mathrm{Q} \vee \sim \mathrm{P}$.
b) $(\mathrm{P} \vee \sim \mathrm{Q}) \wedge \mathrm{Q} \Rightarrow \mathrm{P}$.
c) $(\mathrm{P} \rightarrow \sim \mathrm{Q}) \wedge \mathrm{P} \Rightarrow \sim \mathrm{Q}$.
d) $(\sim \mathrm{P} \rightarrow \mathrm{Q}) \wedge(\mathrm{Q} \rightarrow \sim \mathrm{R}) \Rightarrow(\sim \mathrm{P} \rightarrow \sim \mathrm{R})$.
e) $\sim \mathrm{P} \wedge \mathrm{Q} \Rightarrow \sim \mathrm{P}$.
f) $(\mathrm{P} \rightarrow(\mathrm{P} \rightarrow \mathrm{Q})) \wedge \mathrm{P} \Rightarrow(\mathrm{P} \rightarrow \mathrm{Q})$.
g) $(\mathrm{P} \rightarrow \sim \mathrm{Q}) \wedge(\mathrm{Q} \rightarrow \sim \mathrm{R}) \Rightarrow(\mathrm{P} \vee \mathrm{Q}) \rightarrow(\sim \mathrm{Q} \vee \sim \mathrm{R})$.

h) $(-\mathrm{P} \rightarrow \mathrm{Q}) \wedge \sim \mathrm{Q} \Rightarrow \mathrm{P}$.
i) $(-\mathrm{P} \vee \mathrm{Q}) \wedge \sim \mathrm{Q} \Rightarrow \sim \mathrm{Q}$.
j) $(-\mathrm{P} \rightarrow \mathrm{Q}) \wedge \sim \mathrm{P} \Rightarrow \mathrm{Q}$.
k) $((\mathrm{P} \rightarrow \mathrm{Q}) \vee \mathrm{R}) \wedge \sim \mathrm{R} \Rightarrow(\mathrm{P} \rightarrow \mathrm{Q})$.
l) $\mathrm{P} \wedge \sim \mathrm{P} \Rightarrow \mathrm{R} \wedge \mathrm{S} \wedge \sim \mathrm{Q}$.
m) $((\mathrm{P} \rightarrow \mathrm{Q}) \rightarrow(\mathrm{P} \rightarrow \mathrm{R})) \vee(\mathrm{S} \rightarrow \mathrm{R}) \Rightarrow(\sim \mathrm{R} \vee \sim(\mathrm{P} \rightarrow \mathrm{R})) \rightarrow(\sim \mathrm{S} \vee \sim(\mathrm{P} \rightarrow \mathrm{Q}))$.
n) $((\mathrm{P} \wedge \mathrm{Q}) \rightarrow(\mathrm{R} \wedge \mathrm{S})) \wedge((\mathrm{R} \wedge \mathrm{S}) \rightarrow \sim \mathrm{P}) \Rightarrow(\mathrm{P} \wedge \mathrm{Q}) \rightarrow \sim \mathrm{P}$.
o) $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge(\mathrm{Q} \rightarrow \mathrm{R}) \Rightarrow(\mathrm{Q} \rightarrow \mathrm{R})$.
p) $\mathrm{P} \Rightarrow \mathrm{P} \vee \sim \mathrm{P}$.
q) $((\mathrm{R} \rightarrow \mathrm{S}) \rightarrow \mathrm{R}) \wedge(\mathrm{R} \rightarrow \mathrm{S}) \Rightarrow \mathrm{R}$.
r) $(\mathrm{P} \rightarrow(\mathrm{P} \vee \mathrm{Q})) \wedge \sim(\mathrm{P} \vee \mathrm{Q}) \Rightarrow \sim \mathrm{P}$.
s) $(\mathrm{P} \vee \mathrm{Q}) \wedge(\mathrm{R} \vee \mathrm{S}) \Rightarrow \mathrm{P} \vee \mathrm{Q} \vee \mathrm{R} \vee \mathrm{S}$.
t) $((\mathrm{P} \rightarrow \mathrm{Q}) \vee \mathrm{R}) \wedge \sim \mathrm{S} \Rightarrow \mathrm{R} \vee \sim \mathrm{R}$.
u) $((\mathrm{P} \rightarrow \mathrm{Q}) \rightarrow \mathrm{R}) \wedge(\mathrm{R} \rightarrow(\mathrm{Q} \rightarrow \mathrm{P})) \Rightarrow(\mathrm{P} \rightarrow \mathrm{Q}) \rightarrow(\mathrm{Q} \rightarrow \mathrm{P})$.
v) $(\sim(\mathrm{P} \rightarrow \mathrm{Q}) \rightarrow(\mathrm{Q} \rightarrow \mathrm{R}) \vee \sim(\mathrm{Q} \rightarrow \mathrm{P})) \Rightarrow(\mathrm{P} \rightarrow \mathrm{Q})$.
x) $((\mathrm{P} \wedge \mathrm{Q}) \vee \mathrm{R}) \wedge \sim(\mathrm{P} \wedge \mathrm{Q}) \Rightarrow \mathrm{R}$.
w) $(\sim \mathrm{P} \rightarrow \sim \mathrm{Q}) \wedge \sim \mathrm{P} \Rightarrow \sim \mathrm{Q}$.
y) $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge \mathrm{R} \Rightarrow(\mathrm{P} \rightarrow \mathrm{Q})$.
24. Uma contingência é uma proposição que assume pelo menos um valor lógico falso e um valor lógico verdadeiro. Portanto, qualquer proposição deve ser uma tautologia ou uma contradição ou uma contingência. Nas proposições abaixo, verifique através da tabela-verdade se é uma tautologia ou uma contradição ou uma contingência. (Utilizaremos a letra t para representar tautologia e a letra c para representar contradição):
a) $(\mathrm{FM}-2002)[\mathrm{p} \wedge(\mathrm{q} \rightarrow \mathrm{r})] \rightarrow[\mathrm{q} \rightarrow(\mathrm{p} \wedge \mathrm{r})]$.

Solução: Faremos a tabela verdade de $[\mathrm{p} \wedge(\mathrm{q} \rightarrow \mathrm{r})] \rightarrow[\mathrm{q} \rightarrow(\mathrm{p} \wedge \mathrm{r})]$.

| $p$ | $q$ | $r$ | $/ p$ | $\wedge$ | $/ q$ | $\rightarrow$ | $r / J$ | $\rightarrow$ | $/ q$ | $\rightarrow$ | $/ p$ | $\wedge$ | $r / J$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ | $F$ | $F$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ | $F$ |
| $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ |
| $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ |
| $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ |
| $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ |
| Etapa |  |  | 1 | 3 | 1 | 2 | 1 | 4 | 1 | 3 | 1 | 2 | 1 |

Como todas as possibilidades lógicas da etapa 4 são verdadeiras temos que a proposição é uma tautologia
b) $(\mathrm{FM}-2002)[(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r}] \rightarrow[(\mathrm{p} \rightarrow \mathrm{r}) \vee(\mathrm{q} \rightarrow \mathrm{r})]$.
c) $(\mathrm{FM}-2001)[(\mathrm{p} \wedge \mathrm{q}) \wedge(\mathrm{r} \wedge \mathrm{c})] \leftrightarrow(\mathrm{p} \vee \sim \mathrm{r})$.
d) $(\mathrm{FM}-2000)(\mathrm{p} \vee \sim \mathrm{q}) \leftrightarrow(\sim \mathrm{p} \wedge \mathrm{q})$.
e) $(\mathrm{FM}-2000)(\mathrm{p} \wedge \sim \mathrm{p}) \rightarrow(\mathrm{q} \vee \mathrm{p})$.
f) $(\mathrm{FM}-2000)(\mathrm{p} \rightarrow \mathrm{r}) \vee(\mathrm{q} \rightarrow \mathrm{r}) \leftrightarrow(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{r}$.
g) $(\mathrm{FM}-2000)(\mathrm{p} \wedge \mathrm{q}) \vee(\sim \mathrm{r})$.
h) $(\mathrm{FM}-2000)(\mathrm{p} \vee \mathrm{q}) \rightarrow(\mathrm{r} \wedge \mathrm{p})$.
i) $(\mathrm{FM}-2000)[(\mathrm{p} \rightarrow \mathrm{r}) \rightarrow(\mathrm{q} \rightarrow \mathrm{r})] \leftrightarrow[(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{r}]$.
j) $(\mathrm{FM}-1999)(\mathrm{MD}-2003)[\mathrm{p} \vee(\mathrm{p} \rightarrow \mathrm{r})] \rightarrow \mathrm{p}$.
k) $(\mathrm{FM}-1999) \sim(\mathrm{p} \wedge \mathrm{q}) \vee \sim(\mathrm{q} \leftrightarrow \mathrm{p})$.
l) $(\mathrm{FM}-1999)(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{q} \vee \mathrm{p}$.
m) (FM-1999) (MD-2003) $(\mathrm{p} \rightarrow \mathrm{q}) \leftrightarrow \sim \mathrm{p} \vee \mathrm{q}$.
n) $(\mathrm{FM}-1999)[\mathrm{p} \wedge(\sim \mathrm{q})] \rightarrow[(\sim \mathrm{p}) \vee \mathrm{q}]$.
o) $(\mathrm{FM}-1999)(\mathrm{p} \wedge \mathrm{q} \wedge \mathrm{r}) \leftrightarrow[(\sim \mathrm{p}) \vee(\sim \mathrm{q}) \vee(\sim \mathrm{r})$.
p) $(\mathrm{FM}-1999) \mathrm{p} \wedge(\mathrm{p} \rightarrow \mathrm{q}) \wedge[\mathrm{p} \rightarrow(\sim \mathrm{q})]$.
q) $(\mathrm{FM}-1999)(\sim \mathrm{p}) \rightarrow(\mathrm{p} \rightarrow \mathrm{q})$.
r) $\sim(\mathrm{P} \wedge \mathrm{Q})$.
s) $R \Rightarrow \sim(P \wedge Q)$.
t) $\sim(\mathrm{P} \wedge \mathrm{Q})$.
u) $(\mathrm{P} \Rightarrow \mathrm{Q}) \Rightarrow(\mathrm{P} \vee \sim \mathrm{Q})$.
v) $\sim(\mathrm{p} \vee \sim \mathrm{q})$.
x) $\sim(\mathrm{p} \rightarrow \mathrm{q})$.
w) $\sim(\mathrm{p} \wedge \mathrm{q}) \vee \sim(\mathrm{q} \leftrightarrow \mathrm{p})$

y) $(\mathrm{p} \wedge \mathrm{q}) \rightarrow(\mathrm{q} \vee \mathrm{p})$
z) $\sim(\mathrm{p} \rightarrow \mathrm{q}) \leftrightarrow \sim(\mathrm{p} \vee \mathrm{q})$
aa) $\mathrm{p} \wedge \mathrm{q} \rightarrow \mathrm{p} \vee \mathrm{q}$.
ab) $\sim \mathrm{p} \rightarrow(\mathrm{q} \rightarrow \mathrm{p})$.
ac) $(\mathrm{p} \rightarrow \mathrm{q}) \rightarrow(\mathrm{p} \wedge \mathrm{q})$.
ad) $\mathrm{q} \leftrightarrow(\sim \mathrm{p} \wedge \mathrm{q})$.
ae) $(\mathrm{p} \leftrightarrow \sim \mathrm{q}) \leftrightarrow(\mathrm{p} \rightarrow \mathrm{p})$.
af) $(\mathrm{p} \leftrightarrow \sim \mathrm{q}) \rightarrow(\sim \mathrm{p} \wedge \mathrm{q})$.
ag) $(\sim \mathrm{p} \wedge \mathrm{r}) \rightarrow(\mathrm{q} \vee \mathrm{r})$.
ah) $(\mathrm{p} \rightarrow \mathrm{r}) \leftrightarrow(\mathrm{q} \vee \sim \mathrm{r})$.
ai) $(\mathrm{p} \rightarrow(\mathrm{p} \rightarrow \sim \mathrm{r})) \leftrightarrow(\mathrm{q} \vee \mathrm{r}) \mathrm{l})(\mathrm{p} \wedge \mathrm{q}) \vee[\sim \mathrm{p} \leftrightarrow(\mathrm{q} \vee \sim \mathrm{r})]$.
aj) $[\mathrm{p} \wedge(\sim \mathrm{q})] \rightarrow[(\sim \mathrm{p}) \vee \mathrm{q}]$.
ak) $[(p \wedge q) \wedge r] \leftrightarrow[(\sim p) \vee(\sim q) \vee(\sim r)]$.
al) $[\mathrm{p} \wedge(\mathrm{p} \rightarrow \mathrm{q})] \wedge[\mathrm{p} \rightarrow(\sim \mathrm{q})]$.
$\mathrm{am})(\sim \mathrm{p}) \rightarrow(\mathrm{p} \rightarrow \mathrm{q})$.
an) $\mathrm{p} \vee \sim \mathrm{q}) \leftrightarrow(\sim \mathrm{p} \wedge \mathrm{q})$.
ao) $(\mathrm{p} \wedge \sim \mathrm{p}) \rightarrow(\mathrm{q} \vee \mathrm{p})$.
ap) $\mathrm{p} \wedge(\mathrm{p} \vee \mathrm{q}) \leftrightarrow \mathrm{p}$.
aq) $[(p \rightarrow r) \rightarrow(q \rightarrow r)] \rightarrow[(p \wedge q) \rightarrow r]$.
ar) $[\mathrm{p} \leftrightarrow \mathrm{p} \wedge \mathrm{q})] \leftrightarrow[\mathrm{p} \rightarrow \mathrm{q}]$.
as) $\mathrm{p} \vee(\mathrm{p} \wedge \mathrm{q}) \leftrightarrow \mathrm{q}$.
at) $[\mathrm{q} \leftrightarrow(\mathrm{p} \vee \mathrm{q})] \leftrightarrow[\mathrm{p} \rightarrow \mathrm{q}]$.
au) $(\mathrm{p} \rightarrow \mathrm{q}) \wedge(\mathrm{p} \rightarrow \mathrm{r}) \leftrightarrow[\mathrm{p} \rightarrow(\mathrm{q} \wedge \mathrm{r})]$.
av) $(\mathrm{p} \rightarrow \mathrm{q}) \vee(\mathrm{p} \rightarrow \mathrm{r}) \leftrightarrow[\mathrm{p} \rightarrow(\mathrm{q} \vee \mathrm{r})]$.
ax) $[(p \rightarrow q) \rightarrow r] \leftrightarrow[(q \wedge \sim r) \rightarrow \sim p]$.
aw) $(\mathrm{p} \wedge \mathrm{q}) \vee(\sim \mathrm{p}) \vee(\sim \mathrm{q})$.
ay) $\mathrm{p} \wedge(\mathrm{q} \vee \mathrm{r})$.
az) $\mathrm{q} \rightarrow(\mathrm{p} \vee \mathrm{q})$.
ba) $(\mathrm{p} \vee \mathrm{q}) \wedge(\mathrm{q} \vee \mathrm{r}) \wedge(\mathrm{r} \vee \mathrm{p})$.
bb) $(\sim \mathrm{p} \rightarrow \mathrm{p}) \leftrightarrow \mathrm{p}$.
bc) $(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{p}$.
bd) $(\mathrm{p} \wedge \mathrm{q} \wedge \mathrm{r}) \vee \mathrm{p} \vee \mathrm{q} \vee \mathrm{r}$.
be) $(\mathrm{p} \vee \mathrm{q}) \wedge \mathrm{r}$.
bf) $(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{q}$.
bg) $(\mathrm{p} \wedge \mathrm{q}) \leftrightarrow(\mathrm{q} \wedge \mathrm{p})$.
bh) $(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r}$.
bi) $(\mathrm{p} \rightarrow \mathrm{p}) \leftrightarrow \mathrm{p}$.
bj) $(\sim \mathrm{p}) \leftrightarrow[\mathrm{p} \vee(\sim \mathrm{q})]$.
bk) $(\mathrm{p} \rightarrow \sim \mathrm{p}) \leftrightarrow \mathrm{p}$
bl) $(\sim \mathrm{p}) \rightarrow \mathrm{q}$.
bm) $(\sim q) \rightarrow(\sim p)$
bn) $\mathrm{p} \vee \sim \mathrm{p}$
bo) $\mathrm{p} \vee(\mathrm{q} \wedge \mathrm{r})$.
bp) $(\mathrm{p} \vee \mathrm{q}) \vee \mathrm{r}$
bq) $(\mathrm{p} \rightarrow \mathrm{q}) \rightarrow[\mathrm{p} \vee(\mathrm{q} \wedge \mathrm{r}) \rightarrow \mathrm{p} \wedge(\mathrm{p} \vee \mathrm{r})]$.
br) $(\mathrm{p} \wedge \mathrm{q}) \vee(\mathrm{p} \wedge \mathrm{r})$.
bs) $(\mathrm{p} \rightarrow \mathrm{q}) \leftrightarrow[(\mathrm{p} \wedge \mathrm{q}) \rightarrow(\mathrm{q} \wedge \mathrm{r})]$.
bt) $(\mathrm{p} \vee \mathrm{q}) \wedge(\mathrm{p} \vee \mathrm{r})$
bu) $\mathrm{p} \vee(\mathrm{q} \vee \mathrm{r})$.
bv) $(\mathrm{p} \wedge \mathrm{q} \wedge \mathrm{r}) \vee(\sim \mathrm{p} \wedge \mathrm{q} \wedge \sim \mathrm{r}) \vee(\sim \mathrm{p} \wedge \sim \mathrm{q} \wedge \sim \mathrm{r})$.
bw) $(\mathrm{p} \rightarrow \mathrm{q}) \rightarrow[\mathrm{p} \vee(\mathrm{q} \vee \mathrm{r}) \rightarrow \mathrm{p} \wedge(\mathrm{p} \vee \mathrm{r})]$.
by) $\mathrm{p} \rightarrow \mathrm{p}$
bz) $\mathrm{p} \wedge \mathrm{q} \rightarrow \mathrm{q} \wedge \mathrm{p}$
ca) $\mathrm{p} \rightarrow \mathrm{p} \wedge \mathrm{p}$
cb) $\mathrm{p} \wedge \mathrm{q} \rightarrow \mathrm{q}$
cc) $[\mathrm{p} \vee(\mathrm{q} \rightarrow \mathrm{r})] \rightarrow \mathrm{p}$
25. Mostre que
a) $(\mathrm{p} \leftrightarrow \mathrm{q}) \Leftrightarrow(\sim \mathrm{p} \leftrightarrow \sim \mathrm{q})$.
b) $(\mathrm{p} \rightarrow \mathrm{q}) \rightarrow(\sim \mathrm{p} \leftrightarrow \sim \mathrm{q})$ não é uma tautologia.
c) $[(p \rightarrow q) \wedge \sim p] \rightarrow \sim q$ é equivalente a $(p \rightarrow q) \rightarrow(\sim p \leftrightarrow \sim q)$.

26. O sinal $\underset{\sim}{\mathrm{e}}$ é denominado disjunção exclusiva, $\mathrm{p} \underset{\sim}{\mathrm{e}}$ q é verdadeira quando $\mathrm{p} \vee \mathrm{q}$ é verdadeira, mas não ambos o são.
a) Construa a tabela verdade de $\mathrm{p} \underset{\sim}{\mathrm{q}}$.
b) Construa a tabela verdade da proposição $(\mathrm{p} \vee \mathrm{q}) \wedge \sim(\mathrm{p} \wedge \mathrm{q})$.
c) Comparando as tabelas verdade dos itens a) e b) que conclusão podemos chegar?
d) Mostre que: $\mathrm{p} \underset{\sim}{\mathrm{q}} \Leftrightarrow \mathrm{q} \underset{\sim}{\mathrm{p}}$.
e) Mostre que: $\mathrm{p} \underset{\sim}{\mathrm{q}}(\mathrm{q} \underset{\sim}{\mathrm{r}}) \Leftrightarrow(\mathrm{p} \underset{\sim}{\mathrm{q}}) \underset{\sim}{\mathrm{r}}$.
f) Mostre que: $\mathrm{p} \underset{\sim}{\mathrm{t}} \Leftrightarrow \sim \mathrm{p}$.
g) Mostre que: $\mathrm{p} \underset{\sim}{\mathrm{c}} \Leftrightarrow \mathrm{p}$.
h) Mostre que: $\mathrm{p} \underset{\sim}{\mathrm{p}} \Leftrightarrow \mathrm{c}$.
i) Mostre que: $\sim(\mathrm{p} \underset{\sim}{\mathrm{q}}) \Leftrightarrow(\mathrm{p} \leftrightarrow \mathrm{q})$.
27. Dadas duas proposições p e q e a condicional $\mathrm{p} \rightarrow \mathrm{q}$, definimos:

# Recíproca ou converso: $\mathrm{q} \rightarrow \mathrm{p}$. 

## Inversa: $\sim \mathrm{p} \rightarrow \sim \mathrm{q}$.

Contrapositiva ou Contra recíproca: $\sim \mathrm{q} \rightarrow \sim \mathrm{p}$.
Com essas definições determinar e simplificar:
a) A contrapositiva da contrapositiva.
b) A contrapositiva da recíproca.
c) A contrapositiva da inversa.
d) A contrapositiva de $\mathrm{p} \rightarrow \sim \mathrm{q}$.
e) A contrapositiva de $\sim \mathrm{p} \rightarrow \mathrm{q}$.
f) A contrapositiva da recíproca de $\mathrm{p} \rightarrow \sim \mathrm{q}$.
g) A recíproca de $\sim \mathrm{p} \rightarrow \sim \mathrm{q}$.
28. O sinal $\downarrow$ é denominado negação conjunta, $\mathrm{p} \downarrow \mathrm{q}$ é verdadeira quando nem p e nem q o são.
a) (FM-2002) Construa a sua tabela verdade.
b) Mostre as seguintes equivalências:
i) $\sim \mathrm{p} \Leftrightarrow \mathrm{p} \downarrow \mathrm{p}$.
ii) $\mathrm{p} \wedge \mathrm{q} \Leftrightarrow(\mathrm{p} \downarrow \mathrm{p}) \downarrow(\mathrm{q} \downarrow \mathrm{q})$.
iii) $\mathrm{p} \vee \mathrm{q} \Leftrightarrow(\mathrm{p} \downarrow \mathrm{q}) \downarrow(\mathrm{p} \downarrow \mathrm{q})$.
iv) $\mathrm{p} \downarrow \mathrm{q} \Leftrightarrow \sim \mathrm{p} \wedge \sim \mathrm{q}$.
c) (FM-2002) Construa a tabela verdade da proposição $[(p \downarrow q) \rightarrow p] \wedge[q \downarrow(p \vee q)]$.
29. (FM-2002) Considere o conectivo lógico $\otimes$ definido por

| p | q | $\mathrm{p} \otimes \mathrm{q}$ |
| :-- | :-- | :-- |
| V | V | F |
| V | F | F |
| F | V | V |
| F | F | F |

Construa a tabela verdade da proposição $(\mathrm{p} \wedge \mathrm{q}) \otimes(\mathrm{p} \leftrightarrow \mathrm{q}) \rightarrow(\mathrm{p} \otimes \mathrm{q}) \vee \sim \mathrm{p}$.
Solução: A tabela verdade é obtida por

| $P$ | $q$ | $/ p$ | $\wedge$ | $q j$ | $\otimes$ | $/ p$ | $\leftrightarrow$ | $q j$ | $\rightarrow$ | $/ p$ | $\otimes$ | $q j$ | $\vee$ | $\sim$ | $p$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ |
| $V$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $F$ |
| $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ |
| Etapas |  | 1 | 2 | 1 | 3 | 1 | 2 | 1 | 4 | 1 | 2 | 2 | 3 | 2 | 1 |

30. (FM-2001) O sinal " $\leftarrow$ " é denominado recíproca da condicional. Temos que $\mathrm{p} \leftarrow \mathrm{q}$ só é falsa quando a condicional é verdadeira, se p e q tem valores verdades distintos.
a) Construa a tabela da verdade de $\mathrm{p} \leftarrow \mathrm{q}$.
b) Construa a tabela da verdade da proposição $[(\mathrm{p} \vee \mathrm{q}) \wedge \mathrm{q}] \rightarrow(\mathrm{p} \leftrightarrow \mathrm{q})$.
c) Comparando a tabelas da verdade dos itens a) e b) que conclusões podemos chegar?
31. (MD-2001) Dada a seguinte proposição:

$$
[\mathrm{a} \rightarrow(\mathrm{~b} \wedge \sim \mathrm{c})] \leftrightarrow[\mathrm{b} \rightarrow(\sim \mathrm{a} \vee \mathrm{c})]
$$

a) Determine, usando uma tabela-verdade, seus valores-verdade;
b) Diga se é uma tautologia (justifique);
c) Diga se é equivalente à proposição $\sim$ a (justifique).
32. Sabendo que a proposição p é verdadeira, encontre a tabela verdade das proposições:
a) (MD-2001) $[\mathrm{p} \rightarrow(\sim \mathrm{q})] \leftrightarrow[(\mathrm{p} \vee \mathrm{r}) \wedge \mathrm{q}]$.

Solução: Como p é sempre verdadeira, temos a seguinte tabela verdade detalhada.

| p | q | r | $[\mathrm{p}$ | $\rightarrow$ | $(\sim$ | q $)]$ | $\leftrightarrow$ | $[$ (p | $\vee$ | r$)$ | $\wedge$ | q $]$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| V | V | V | V | F | F | V | F | V | V | V | V | V |
| V | V | F | V | F | F | V | F | V | V | F | V | V |
| V | F | V | V | V | V | F | F | V | V | V | F | F |
| V | F | F | V | V | V | F | F | V | V | F | F | F |
| Etapa |  |  | 1 | 3 | 2 | 1 | 4 | 1 | 2 | 1 | 3 | 1 |

b) $(\mathbf{M D}-2001)[(\mathrm{p} \rightarrow \mathrm{r}) \vee(\mathrm{q} \rightarrow \mathrm{r})] \leftrightarrow[(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{r}]$.

Solução:

| p | q | r | $[$ (p | $\rightarrow$ | r) | $\vee$ | (q | $\rightarrow$ | r) | $\leftrightarrow$ | $[$ (p | $\wedge$ | q | $\rightarrow$ | r] |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| V | V | V | V | V | V | V | V | V | V | V | V | V | V | V | V |
| V | V | F | V | F | F | F | V | F | F | V | V | V | V | F | F |
| V | F | V | V | V | V | V | F | V | V | V | V | F | F | V | V |
| V | F | F | V | F | F | V | F | V | F | V | V | F | F | V | F |
| Etapa |  |  | 1 | 2 | 1 | 3 | 1 | 2 | 1 | 4 | 1 | 2 | 1 | 3 | 1 |

33. Prove ou disprove as proposições abaixo: (Note que basta uma linha ser F para falhar uma tautologia.)
a) $(\mathrm{Q} \rightarrow \mathrm{P}) \Leftrightarrow(\mathrm{P} \wedge \mathrm{Q})$
b) $(\mathrm{P} \wedge \sim \mathrm{Q}) \Rightarrow(\mathrm{P} \rightarrow \mathrm{Q})$
34. Vários livros apresentam as notações: $\mathrm{w}(\mathrm{P})=1$ se P vale, e $\mathrm{w}(\mathrm{p})=0$ quando ela é falsa. Tais notações facilitam a simulação de tabelas verdade no computador, por exemplo: se $\mathrm{w}(\mathrm{P})=\mathrm{x}$ e $\mathrm{w}(\mathrm{Q})=\mathrm{y}$, a tabela verdade da conjunção pode ser simulada pela função
$\mathrm{f}_{\wedge}:\{0,1\} \times\{0,1\} \rightarrow\{0,1\}$ onde $\mathrm{f}_{\wedge}(\mathrm{x}, \mathrm{y})=\mathrm{x} . \mathrm{y}$, ou ainda , $\mathrm{w}(\mathrm{P} \wedge \mathrm{Q})=\mathrm{w}(\mathrm{P}) \cdot \mathrm{w}(\mathrm{Q})$.
a) Verifique tal afirmação:
b) Analogamente, crie funções: f, ,f,, f., ,f,,, que representem os outros conectivos.
c) Através destas funções, crie funções representativas de:
$-(P \vee Q),(P \wedge Q) \vee \sim Q,(P \wedge Q) \vee R$.
(Este exercício ilustra o fato de que a construção de tabelas-verdade é um problema compatível)
35. (FM-2002) Verifique se é tautologia, contradição ou contingência.

$$
[(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r}] \rightarrow[(\mathrm{p} \rightarrow \mathrm{r}) \vee(\mathrm{q} \rightarrow \mathrm{r})]
$$

Faremos a tabela verdade de $[(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r}] \rightarrow[(\mathrm{p} \rightarrow \mathrm{r}) \vee(\mathrm{q} \rightarrow \mathrm{r})]$.

| $p$ | $q$ | $r$ | $[$ (p | $\vee$ | $q$ ) | $\rightarrow$ | $r]$ | $\rightarrow$ | $[$ (p | $\rightarrow$ | $r]$ | $\vee$ | $[q$ | $\rightarrow$ | $r]$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| V | V | V | V | V | V | V | V | V | V | V | V | V | V | V | V |
| V | V | F | V | V | V | F | F | V | V | F | F | F | V | F | F |
| V | F | V | V | V | F | V | V | V | V | V | V | V | F | V | V |
| V | F | F | V | V | F | F | F | V | V | F | F | V | F | V | F |
| F | V | V | F | V | V | V | V | V | F | V | V | V | V | V | V |
| F | V | F | F | V | V | F | F | V | F | V | F | V | V | F | F |
| F | F | V | F | F | F | V | V | V | F | V | V | V | F | V | V |
| F | F | F | F | F | F | V | F | V | F | V | F | V | F | V | F |
| Etapa |  |  | 1 | 2 | 1 | 3 | 1 | 4 | 1 | 2 | 1 | 3 | 1 | 2 | 1 |

Como na última etapa (etapa 4) todas as possibilidades lógicas são verdadeiras, temos que a proposição é uma tautologia.
36. (FM-2002) Considere o conectivo lógico $\otimes$ definido por

| p | q | $\mathrm{p} \otimes \mathrm{q}$ |
| :--: | :--: | :--: |
| V | V | F |
| V | V | F |
| F | F | F |
| F | F | V |

Construa a tabela verdade da proposição

$$
[(\mathrm{p} \otimes \mathrm{q}) \rightarrow \mathrm{p}] \wedge[\mathrm{q} \otimes(\mathrm{p} \vee \mathrm{q})]
$$

A tabela verdade da proposição dada é:

| $p$ | $q$ | $[$ (p | $\otimes$ | $q$ ) | $\rightarrow$ | $p J$ | $\wedge$ | $/ q$ | $\otimes$ | $(p$ | $\vee$ | $q J$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| V | V | V | F | V | V | F | F | V | F | V | V | V |

| $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ |
| $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ |
| Etapas | 1 | 2 | 1 | 3 | 1 | 4 | 1 | 3 | 1 | 2 | 1 |  |

Como na etapa 4 temos apenas valores lógicos falsos dizemos que o resultado é uma contradição.
37. (FM-2001) O sinal " $\leftarrow$ é denominado recíproca da condicional. Temos que $\mathrm{p} \leftarrow \mathrm{q}$ só é falsa quando a condicional é verdadeira, se p e q tem valores verdades distintos.
a) Construa a tabela da verdade de $\mathrm{p} \leftarrow \mathrm{q}$.
b) Construa a tabela da verdade da proposição $[(\mathrm{p} \vee \mathrm{q}) \wedge \mathrm{q}] \rightarrow(\mathrm{p} \leftrightarrow \mathrm{q})$.
c) Comparando a tabelas da verdade dos itens a) e b) que conclusões podemos chegar?

Solução:
a)

| $p$ | $q$ | $\rightarrow$ | $\leftarrow$ |
| :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $F$ | $V$ |
| $F$ | $V$ | $V$ | $F$ |
| $F$ | $F$ | $V$ | $V$ |

b)

| $p$ | $q$ | $\vee$ | $\wedge$ | $\rightarrow$ | $\leftrightarrow$ |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $V$ | $F$ | $V$ | $F$ |
| $F$ | $V$ | $V$ | $V$ | $F$ | $F$ |
| $F$ | $F$ | $F$ | $F$ | $V$ | $V$ |
| Etapas | $1^{a}$ | $2^{a}$ | $4^{a}$ | $3^{a}$ |  |

c) Como as tabela-verdade das duas proposições são iguais, temos que $p \leftarrow q e \quad[(p \vee q) \wedge q] \rightarrow p \leftrightarrow q$ ) são logicamente equivalentes, ou seja, $p \leftarrow q=[(p \vee q) \wedge q] \rightarrow(p \leftarrow \leftrightarrow q)$.
38. (FM-2001) a) Faça a Tabela Verdade Detalhada da proposição
$[p \wedge(\sim q \rightarrow p)] \wedge \sim[(p \leftrightarrow(\sim q)) \rightarrow(q \vee(\sim p))]$
b) Sabendo que os valores lógicos de p, q e r são, respectivamente, V, F e V, determine o valor lógico (V ou F) de $(\mathrm{p} \rightarrow \mathrm{r}) \leftrightarrow[\mathrm{q} \vee(\sim \mathrm{r})]$.

# Solução: 

a) A tabela verdade detalhada da proposição é:

| $p$ | $q$ | $/ p$ | $\wedge$ | $(\sim$ | $q$ | $\rightarrow$ | $p)]$ | $\wedge$ | $\sim$ | $[(p$ | $\leftrightarrow$ | $(\sim$ | $q)]$ | $\rightarrow$ | $f q$ | $\vee$ | $(\sim$ | $p)]$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ |
| $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ |
| Etapa | 1 | 4 | 2 | 1 | 3 | 1 | 6 | 5 | 1 | 3 | 2 | 1 | 4 | 1 | 3 | 2 | 1 |  |

b) O valor lógico da proposição é dado pela terceira linha e etapa 4 da tabela detalhada a seguir:

| $p$ | $q$ | $r$ | $/ p$ | $\rightarrow$ | $r)$ | $\leftrightarrow$ | $f q$ | $\vee$ | $(\sim$ | $r)]$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ |
| $V$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ |
| $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ |
| $F$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $F$ |

| $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ |
| Etapas |  | 1 | 2 | 1 | 4 | 1 | 3 | 2 | 1 |  |

39. (FM-2001) Sabendo que c representa uma contradição, faça a Tabela Verdade Detalhada da proposição

$$
[(\mathrm{p} \wedge \mathrm{q}) \wedge(\mathrm{r} \wedge \mathrm{c})] \leftrightarrow(\mathrm{p} \vee \sim \mathrm{c})
$$

Solução:

| $p$ | $q$ | $r$ | $f(p$ | $\wedge$ | $q$ | $\wedge$ | $r$ | $\wedge$ | $c)]$ | $\leftrightarrow$ | $p$ | $\vee$ | $\sim$ | $r)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ |
| $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ |
| $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ |
| $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ |
| $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ |
| $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ |
| $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ |
|  | Etapa |  | 1 | 2 | 1 | 3 | 1 | 2 | 1 | 4 | 1 | 3 | 2 | 1 |

40. (FM-2000) Encontre a tabela verdade das seguintes proposições.
a) $(\mathrm{p} \vee \sim \mathrm{q}) \leftrightarrow(\sim \mathrm{p} \wedge \mathrm{q})$
b) $(\mathrm{p} \wedge \sim \mathrm{p}) \rightarrow(\mathrm{q} \vee \mathrm{p})$
c) $(\mathrm{p} \rightarrow \mathrm{r}) \vee(\mathrm{q} \rightarrow \mathrm{r}) \leftrightarrow(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{r}$.

Solução:
a) $(p \vee \sim q) \leftrightarrow(\sim p \wedge q)$

| $p$ | $q$ | $p$ | $\vee$ | $\sim$ | $q$ | $\leftrightarrow$ | $l \sim$ | $p$ | $\wedge$ | $q)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ |
| $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ |
| $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ |
|  | Etapas |  | 1 | 3 | 2 | 1 | 4 | 2 | 1 | 3 | 1 |

Temos que o resultado da tabela- verdade acima é uma contradição.
b) $(p \wedge \sim p) \rightarrow(q \vee p)$

| $p$ | $q$ | $p$ | $\wedge$ | $\sim$ | $p$ | $\rightarrow$ | $q$ | $\vee$ | $p)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ |
| $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ |
|  | Etapas |  | 1 | 3 | 2 | 1 | 4 | 1 | 2 | 1 |

Temos que o resultado da tabela - verdade é uma tautologia.
c) $f(p \rightarrow r) \rightarrow(q \rightarrow r) J \rightarrow f(p \wedge q) \rightarrow r J$

| $p$ | $q$ | $r$ | $f(p$ | $\rightarrow$ | $r)$ | $\rightarrow$ | $q$ | $\rightarrow$ | $r j$ | $\rightarrow$ | $f(p$ | $\wedge$ | $q)$ | $\rightarrow$ | $r)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |  |
| $V$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ |  |
| $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ |  |
| $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ |  |
| $F$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ |  |
| $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ |  |
| $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ |  |

| $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| Etapas | 1 | 2 | 1 | 3 | 1 | 2 | 1 | 4 | 1 | 2 | 1 | 3 | 1 |

Temos que o resultado da tabela- verdade acima é uma contingência.
41. (FM-2000) Encontre a tabela verdade das seguintes proposições.
a) $(\mathrm{p} \wedge \mathrm{q}) \vee(-\mathrm{r})$
b) $(\mathrm{p} \vee \mathrm{q}) \rightarrow(\mathrm{r} \wedge \mathrm{p})$
c) $[(\mathrm{p} \rightarrow \mathrm{r}) \rightarrow(\mathrm{q} \rightarrow \mathrm{r})] \leftrightarrow[(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{r}]$.

Solução:
a) $(p \wedge q) \vee(-r)$

| $p$ | $q$ | $r$ | $(p$ | $\wedge$ | $q)$ | $v$ | $(-)$ | $r)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ |
| $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ |
| $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ |
| $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ |
| $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ |
| $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ |
| $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ |
| Etapa |  |  | 1 | 2 | 1 | 3 | 2 | 1 |

b) $(p \vee q) \rightarrow(r \wedge p)$

| $p$ | $Q$ | $r$ | $(p$ | $v$ | $q)$ | $\rightarrow$ | $(r$ | $\wedge$ | $p)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $V$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ |
| $F$ | $V$ | $V$ | $F$ | $V$ | $V$ | $F$ | $V$ | $F$ | $F$ |
| $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ |
| $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ |
| $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ |
| Etapa |  |  | 1 | 2 | 1 | 3 | 1 | 2 | 1 |

c) $[(p \rightarrow r) \rightarrow(q \rightarrow r)] \leftrightarrow[(p \wedge q) \rightarrow r]$

| $p$ | $q$ | $r$ | $[(p$ | $\rightarrow$ | $r)$ | $\rightarrow$ | $(q$ | $\rightarrow$ | $r)$ | $\leftrightarrow$ | $[(p$ | $\wedge$ | $q)$ | $\rightarrow$ | $r]$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ |
| $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ |
| $F$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ |
| $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ |
| $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ |
| Etapa |  | 1 | 2 | 1 | 3 | 1 | 2 | 1 | 4 | 1 | 2 | 1 | 3 | 1 |  |

42. (FM-2000) Encontre a tabela verdade das seguintes proposições.
a) $(\mathrm{p} \vee \sim \mathrm{q}) \leftrightarrow(-\mathrm{p} \wedge \mathrm{q})$
b) $(\mathrm{p} \wedge \sim \mathrm{p}) \rightarrow(\mathrm{q} \vee \mathrm{p})$
c) $(\mathrm{p} \rightarrow \mathrm{r}) \vee(\mathrm{q} \rightarrow \mathrm{r}) \leftrightarrow(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{r}$.

Solução:

a) $(p \vee \neg q) \leftrightarrow(\neg p \wedge q)$

| $p$ | $q$ | $(p$ | $\vee$ | $\neg$ | $q)$ | $\leftrightarrow$ | $(\neg$ | $p$ | $\wedge$ | $q)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ |
| $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ |
| $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ |
| Etapa | 1 | 3 | 2 | 1 | 4 | 2 | 1 | 3 | 1 |  |

b) $(p \wedge \neg p) \rightarrow(q \vee p)$

| $p$ | $q$ | $(p$ | $\wedge$ | $\neg$ | $p)$ | $\rightarrow$ | $l q$ | $\vee$ | $p)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ |
| $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ |
| Etapa | 1 | 3 | 2 | 1 | 4 | 1 | 2 | 1 |  |

c) $(p \rightarrow r) \vee(q \rightarrow r) \leftrightarrow(p \wedge q) \rightarrow r$

| $p$ | $q$ | $r$ | $(p$ | $\rightarrow$ | $r)$ | $\vee$ | $l q$ | $\rightarrow$ | $r)$ | $\leftrightarrow$ | $(p$ | $\wedge$ | $q)$ | $\rightarrow$ | $r$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ |
| $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ |
| $F$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ |
| $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ |
| $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ |
| Etapa | 1 | 2 | 1 | 3 | 1 | 2 | 1 | 4 | 1 | 2 | 1 | 3 | 1 |  |  |

43. (FM-1999) Uma contingência é uma proposição que assume pelo menos um valor lógico falso e um valor lógico verdadeiro. Portanto, qualquer proposição deve ser uma tautologia ou uma contradição ou uma contingência. Nas proposições abaixo, verifique através da tabela-verdade se é uma tautologia ou uma contradição ou uma contingência:
a) $[p \wedge(\neg q)] \rightarrow[(\neg p) \vee q]$
b) $(p \wedge q \wedge r)] \leftrightarrow[(\neg p) \vee(\neg q) \vee(\neg r)$
c) $p \wedge(p \rightarrow q) \wedge[p \rightarrow(\neg q)]$
d) $(\neg p) \rightarrow(p \rightarrow q)$.

# Solução: 

a) $[p \wedge(\neg q)] \rightarrow[(\neg p) \vee q]$

| $p$ | $q$ | $f p$ | $\wedge$ | $(\neg$ | $q)$ | $\rightarrow$ | $f(\neg$ | $p)$ | $\vee$ | $q]$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ |
| $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $V$ |
| $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ | $V$ | $F$ |
| Etapos | 1 | 2 | 2 | 1 | 4 | 2 | 1 | 3 | 1 |  |

Como na etapa 4 a proposição assume valores lógicos verdadeiros e falsos temos que o resultado da tabela- verdade é uma contingência.
b) $f(p \wedge q) \wedge r] \leftrightarrow[(\neg p) \vee(\neg q) \vee(\neg r)]$

| $p$ | $q$ | $r$ | $f(p$ | $\wedge$ | $q)$ | $\wedge$ | $r$ | $\leftrightarrow$ | $f(\neg$ | $p)$ | $\vee$ | $(\neg$ | $q)$ | $\vee(\neg$ | $r)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ |
| $V$ | $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ |
| $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ | $F$ | $V$ |
| $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ | $F$ | $F$ |
| $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ | $F$ |

| $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ |
| Etapos | 1 | 2 | 1 | 3 | 1 | 5 | 2 | 1 | 3 | 2 | 1 | 4 | 2 | 1 |

Como os valores lógicos da etapa 5 são falsos temos que o resultado da tabela - verdade é uma contradição.
c) $[p \wedge(p \rightarrow q)] \wedge[p \rightarrow(-q)]$

| $p$ | $q$ | $p$ | $\wedge$ | $(p$ | $\rightarrow$ | $q)]$ | $\wedge$ | $p$ | $\rightarrow$ | $(-q)]$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $F$ | $V$ | $F$ | $F$ | $V$ |
| $V$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ |
| $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ |
| $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ |
| Etapos | 1 | 3 | 1 | 2 | 1 | 4 | 1 | 3 | 2 | 1 |

Temos que o resultado da tabela- verdade é uma contradição.
d) $(-p) \rightarrow(p \rightarrow q)$

| $p$ | $q$ | $(-q)$ | $p$ | $\rightarrow$ | $(p$ | $\rightarrow$ | $q)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $V$ |
| $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ |
| $F$ | $V$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ |
| $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $F$ |
| Etapos | 2 | 1 | 3 | 1 | 2 | 1 |  |

Como os valores lógicos da etapa 3 são verdadeiros temos que o resultado da tabela - verdade é uma tautologia.
44. (FM-1999) Uma contingência é uma proposição que assume pelo menos um valor lógico falso e um valor lógico verdadeiro. Portanto, qualquer proposição deve ser uma tautologia ou uma contradição ou uma contingência. Nas proposições abaixo, verifique através da tabela-verdade se é uma tautologia ou uma contradição ou uma contingência:
a) $[p \vee(p \rightarrow r)] \rightarrow p$.
b) $\neg(p \wedge q) \vee \neg(q \leftrightarrow p)$
c) $(p \wedge q) \rightarrow q \vee p$.
d) $\neg(p \rightarrow q) \leftrightarrow-p \vee q$.

Solução:
a)

| $p$ | $r$ | $[p$ | $\vee$ | $(p$ | $\rightarrow$ | $r)]$ | $\rightarrow$ | $p$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ |
| $F$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ | $F$ | $F$ |
| $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ | $F$ | $F$ |
| Etapo | 1 | 3 | 1 | 2 | 1 | 4 | 1 | 2 |

b)

| $p$ | $q$ | $\neg$ | $(p$ | $\wedge$ | $q)$ | $\vee$ | $(q$ | $\leftrightarrow$ | $p)$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ |
| $F$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ |
| $F$ | $F$ | $V$ | $F$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ |
| Etapo | 3 | 1 | 2 | 1 | 4 | 1 | 2 | 1 |  |

c)

| $p$ | $q$ | $(p$ | $\wedge$ | $q)$ | $\rightarrow$ | $q$ | $\vee$ | $p$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $V$ |
| $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ | $V$ | $F$ |
| $F$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $F$ |

| Etapa |  | 1 | 2 | 1 | 3 | 1 | 2 | 1 |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |

d)

| $p$ | $q$ | $\sim$ | $(p$ | $\rightarrow$ | $q)$ | $\leftrightarrow$ | $\sim$ | $p$ | $\vee$ | $q$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V$ | $V$ | $F$ | $V$ | $V$ | $V$ | $F$ | $F$ | $V$ | $V$ | $V$ |
| $V$ | $F$ | $V$ | $V$ | $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ |
| $F$ | $V$ | $F$ | $F$ | $V$ | $V$ | $F$ | $V$ | $F$ | $V$ | $V$ |
| $F$ | $F$ | $F$ | $F$ | $V$ | $F$ | $F$ | $V$ | $F$ | $V$ | $F$ |
| Etapa |  | 3 | 1 | 2 | 1 | 4 | 2 | 1 | 3 | 1 |

# Método Dedutivo 

45. O que é um argumento?
46. Quando um argumento é válido?
47. (FM-2005) Observe as demonstrações I e II a seguir:
I) Um aluno deu a solução seguinte para a inequação (1) abaixo:

| $(\mathrm{x}+3)(\mathrm{x}-2)$ <br> $(\mathrm{x}-1)>\mathrm{x}$ | $(1)$ |
| :--: | :--: |
| $(\mathrm{x}+3)(\mathrm{x}-2)>\mathrm{x}^{2}-\mathrm{x}$ | $(2)$ |
| $\mathrm{x}^{2}+\mathrm{x}-6>\mathrm{x}^{2}-\mathrm{x}$ | $(3)$ |
| $\mathrm{x}-6>-\mathrm{x}$ | $(4)$ |
| $2 \mathrm{x}>6$ | $(5)$ |
| $\mathrm{x}>3$ | $(6)$. |

II) Maria assustou-se esta noite com um gato branco. Como sabe que foi um gato? Bem, ela só poderia assustar-se com um animal e em sua casa só há cães e gatos. Se fosse um cão, o susto teria sido maior. E como sabe que o gato era branco? Na casa da Maria só tem gatos brancos e gatos pretos e os gatos pretos não seriam visíveis naquela escuridão...

Com isso concluímos que:
Todos os passos de (2) a (6) da solução estão corretos.
A conclusão está correta? Justifique sua resposta utilizando os operadores lógicos conhecidos por você.
48. Utilizando as regras de inferência e equivalência lógicas, mostre as seguintes tautologias:
a) (FM-2002) $(\mathrm{q} \wedge \mathrm{r}) \rightarrow \mathrm{p} \Leftrightarrow[\mathrm{q} \rightarrow(\mathrm{r} \rightarrow \mathrm{p})]$.
b) (FM-2002) $(\mathrm{p} \rightarrow \mathrm{q}) \rightarrow \mathrm{r} \Leftrightarrow \mathrm{r} \vee(\mathrm{p} \wedge \sim \mathrm{q})$
c) (FM-2002) $\mathrm{p} \vee(\mathrm{p} \wedge \mathrm{q}) \Leftrightarrow \mathrm{p}$.
d) (FM-2002) $[(\mathrm{p} \rightarrow \mathrm{q}) \vee(\mathrm{p} \rightarrow \mathrm{r})] \Leftrightarrow[\mathrm{p} \rightarrow(\mathrm{q} \vee \mathrm{r})]$.
e) (FM-2002) (MD-2003) $(\mathrm{p} \wedge \mathrm{q}) \vee \sim \mathrm{p} \Leftrightarrow(\sim \mathrm{q} \rightarrow \sim \mathrm{p})$.
f) (FM-2002) $(\mathrm{r} \vee \mathrm{s}) \vee \sim \mathrm{s} \Leftrightarrow \mathrm{t}$.
g) (FM-2002) $(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{r} \Leftrightarrow[(\mathrm{p} \rightarrow \mathrm{r}) \wedge(\mathrm{q} \rightarrow \mathrm{r})]$.
h) (FM-2001) $\mathrm{p} \Rightarrow(\mathrm{p} \wedge \mathrm{q}) \vee \sim \mathrm{p}$.
i) (FM-2001) $(\mathrm{p} \rightarrow \mathrm{q}) \wedge \mathrm{p} \Leftrightarrow \mathrm{p} \wedge \mathrm{q}$.
j) (FM-2001) $[\mathrm{p} \rightarrow(\mathrm{p} \wedge \mathrm{q})] \Leftrightarrow(\mathrm{p} \rightarrow \mathrm{q})$;
k) (FM-2001) $[(\mathrm{p} \rightarrow \mathrm{q}) \rightarrow \mathrm{q})] \Leftrightarrow(\mathrm{p} \vee \mathrm{q})$.
l) (FM-2001) $[(\mathrm{p} \rightarrow \mathrm{q}) \wedge(\mathrm{p} \rightarrow \mathrm{r})] \Leftrightarrow[\mathrm{p} \rightarrow(\mathrm{q} \wedge \mathrm{r})]$;
m) (FM-2001) $[\sim(\mathrm{p} \vee \mathrm{q}) \vee(\sim \mathrm{p} \wedge \mathrm{q})] \Leftrightarrow \sim \mathrm{p}$.
n) (FM-2001) $\mathrm{p} \Rightarrow(\mathrm{p} \wedge \mathrm{q}) \vee \sim \mathrm{q}$.
o) (FM-2001) $(\mathrm{p} \rightarrow \mathrm{q}) \wedge \mathrm{p} \Leftrightarrow \mathrm{p} \wedge \mathrm{q}$.

p) $(\mathrm{FM}-1999)(\mathrm{p} \wedge \mathrm{q}) \vee \sim \mathrm{p} \Leftrightarrow(\sim \mathrm{q} \rightarrow \sim \mathrm{p})$.
q) $(\mathrm{FM}-1999)(\mathrm{r} \vee \mathrm{s}) \vee \sim \mathrm{s} \Leftrightarrow \mathrm{s}$.
r) $(\mathrm{FM}-1999) \mathrm{p} \vee(\mathrm{p} \wedge \mathrm{q}) \Leftrightarrow \mathrm{p}$.
s) $(\mathrm{FM}-1999)[(\mathrm{p} \rightarrow \mathrm{q}) \vee(\mathrm{p} \rightarrow \mathrm{r}) \Leftrightarrow[\mathrm{p} \rightarrow(\mathrm{q} \vee \mathrm{r})]$.
t) (MD-2001) $[(\mathrm{p} \vee \mathrm{q}) \leftrightarrow(\mathrm{p} \wedge \mathrm{q}) \Leftrightarrow(\mathrm{p} \leftrightarrow \mathrm{q})$.
u) (MD-2001) $(\mathrm{p} \wedge \mathrm{q}) \vee \sim \mathrm{p} \Leftrightarrow(\sim \mathrm{q} \rightarrow \sim \mathrm{p})$.
v) $\mathrm{P} \wedge(\mathrm{Q} \rightarrow \mathrm{P}) \Leftrightarrow \mathrm{P} \vee(\mathrm{P} \wedge \sim \mathrm{Q})$.
x) $\mathrm{P} \Leftrightarrow \sim \mathrm{P}$ P.
w) $(\mathrm{P} \wedge \mathrm{Q}) \vee(\mathrm{P} \wedge \sim \mathrm{Q}) \Leftrightarrow \mathrm{P}$.
y) $(\mathrm{P} \rightarrow \mathrm{Q}) \wedge(\mathrm{P} \rightarrow \sim \mathrm{Q}) \Leftrightarrow \sim \mathrm{P}$.
z) $\mathrm{P} \rightarrow(\mathrm{P} \vee \mathrm{Q}) \Leftrightarrow \mathrm{P} \vee \sim \mathrm{P}$.
aa) $[((\mathrm{P} \rightarrow \mathrm{Q}) \wedge \mathrm{P}) \rightarrow \mathrm{Q}] \wedge(\mathrm{P} \rightarrow \mathrm{Q}) \Leftrightarrow(\mathrm{P} \rightarrow \mathrm{Q})$.
ab) $((\mathrm{P} \rightarrow(\mathrm{Q} \vee \mathrm{R})) \wedge \sim \mathrm{R}) \rightarrow(\mathrm{P} \rightarrow \mathrm{Q}) \Leftrightarrow(\mathrm{P} \wedge \sim \mathrm{Q}) \rightarrow \mathrm{P}$.
ac) $\mathrm{P} \Rightarrow \mathrm{P} \wedge(\mathrm{P} \vee \mathrm{Q})$
ad) $\mathrm{P} \vee(\mathrm{P} \wedge \mathrm{Q}) \Rightarrow \mathrm{P}$
ae) $(\sim \mathrm{P} \vee \mathrm{Q} \vee \mathrm{R}) \wedge \mathrm{P} \wedge \sim \mathrm{Q} \Rightarrow \mathrm{R}$
af) $(\mathrm{P} \wedge \mathrm{Q}) \vee(\mathrm{P} \wedge \mathrm{R}) \Rightarrow(\mathrm{Q} \vee \mathrm{R})$
ag) $\mathrm{P} \wedge(\mathrm{Q} \rightarrow \mathrm{R}) \wedge[(\mathrm{P} \rightarrow \mathrm{Q}) \vee(\mathrm{R} \rightarrow \mathrm{S})] \wedge \sim \mathrm{R} \Rightarrow(\mathrm{Q} \rightarrow \mathrm{S})$
ab) Absorção I: $\mathrm{p} \wedge(\mathrm{p} \vee \mathrm{q}) \Leftrightarrow \mathrm{p}$.
ai) Absorção II: $\mathrm{p} \vee(\mathrm{p} \wedge \mathrm{q}) \Leftrightarrow \mathrm{p}$.
aj) $(\mathrm{p} \rightarrow \mathrm{q}) \Leftrightarrow(\mathrm{p} \vee \mathrm{q} \rightarrow \mathrm{q})$.
ak) $(\mathrm{p} \rightarrow \mathrm{q}) \Leftrightarrow \sim \mathrm{p} \vee \mathrm{q}$.
al) $(\mathrm{p} \rightarrow \mathrm{q}) \wedge(\mathrm{p} \rightarrow \sim \mathrm{q}) \Leftrightarrow \sim \mathrm{p}$.
am) $(\mathrm{p} \rightarrow \mathrm{q}) \Leftrightarrow[\mathrm{p} \rightarrow(\mathrm{p} \wedge \mathrm{q})$.
an) $(\mathrm{p} \rightarrow \mathrm{q}) \Rightarrow[(\mathrm{p} \wedge \mathrm{r}) \rightarrow(\mathrm{q} \wedge \mathrm{r})]$.
49. Para cada um dos seguintes argumentos dados abaixo, dê uma prova direta ou uma prova indireta da validade.

| a) $\mathrm{H} 1: \mathrm{q} \vee(\mathrm{r} \rightarrow \mathrm{u})$ | b) $\mathrm{H} 1: \mathrm{p} \vee(\mathrm{q} \wedge \mathrm{r})$ |
| :--: | :--: |
| $\mathrm{H} 2: \mathrm{q} \rightarrow \mathrm{s}$ | $\mathrm{H} 2: \mathrm{q} \rightarrow \mathrm{s}$ |
| $\mathrm{H} 3: \sim \mathrm{s} \rightarrow(\mathrm{u} \rightarrow \mathrm{p})$ | $\mathrm{H} 3: \mathrm{r} \rightarrow \mathrm{u}$ |
| $\mathrm{H} 4: \sim \mathrm{s}$ | $\mathrm{H} 4: \mathrm{s} \wedge \mathrm{u} \rightarrow \mathrm{p} \vee \mathrm{r}$ |
| $\mathrm{T}: \mathrm{r} \rightarrow \mathrm{p}$ | $\mathrm{H} 5: \sim \mathrm{p}$ |
|  | $\mathrm{T}: \mathrm{r}$ |
| c) $\mathrm{H} 1: \mathrm{p} \vee \mathrm{q}$ | d) $\mathrm{H} 1: \mathrm{p} \rightarrow \mathrm{q}$ |
| $\mathrm{H} 2: \sim \mathrm{q} \vee \mathrm{r}$ | $\mathrm{H} 2: \sim \mathrm{q}$ |
| $\mathrm{T}: \mathrm{p} \vee \mathrm{r}$ | $\mathrm{T}: \sim \mathrm{p}$ |
| e) $\mathrm{H} 1: \mathrm{p} \leftrightarrow \mathrm{q}$ | f) $\mathrm{H} 1: \mathrm{p} \rightarrow \sim \mathrm{q}$ |
| $\mathrm{H} 2: \mathrm{q}$ | $\mathrm{H} 2: \mathrm{r} \rightarrow \mathrm{q}$ |
| $\mathrm{T}: \mathrm{p}$ | $\mathrm{H} 3: \mathrm{r}$ |
|  | $\mathrm{T}: \sim \mathrm{p}$ |
| g) $\mathrm{H} 1: \mathrm{p} \rightarrow \mathrm{q}$ | h) (FM-2002) $\mathrm{H}_{1}, \mathrm{H}_{2}, \mathrm{H}_{3}, \mathrm{H}_{4} \rightarrow \mathrm{~T}$, onde |
| $\mathrm{H} 2: \mathrm{r} \rightarrow \sim \mathrm{q}$ | $\mathrm{H} 1:(\mathrm{p} \rightarrow \mathrm{q})$ |
| $\mathrm{T}: \mathrm{r} \rightarrow \sim \mathrm{p}$ | $\mathrm{H}_{2}:(\mathrm{r} \rightarrow \mathrm{s})$ |
|  | $\mathrm{H}_{3}(\mathrm{q} \vee \mathrm{s}) \rightarrow \sim \mathrm{m} \mathrm{H}_{4}: \mathrm{m}$ |
|  | $\mathrm{T}:(\sim \mathrm{p} \wedge \sim \mathrm{r})$ |
| i) (FM-2002) $\mathrm{H}_{1}, \mathrm{H}_{2}, \mathrm{H}_{3}, \mathrm{~T}$, onde | j) (FM-2002) |
| $\mathrm{H}_{1}: \mathrm{p} \rightarrow \mathrm{q}$, | $\mathrm{H}_{1}: \mathrm{p} \rightarrow \mathrm{q}$ |
| $\mathrm{H}_{2}: \mathrm{p} \vee \mathrm{q}$, | $\mathrm{H}_{2}: \mathrm{p} \vee \mathrm{r}$ |
| $\mathrm{H}_{3} \sim \mathrm{p}$ | $\mathrm{H}_{3}: \sim \mathrm{q}$ |
| $\mathrm{T}: \mathrm{c}$. | $\mathrm{H}_{4}: \mathrm{r} \rightarrow(\mathrm{s} \wedge \mathrm{t})$ |
|  | $\mathrm{T}: \mathrm{s}$ |
| k) (FM-2002) | l) (FM-2002) |
| $\mathrm{H}_{1}: \mathrm{p} \rightarrow \mathrm{q}$ | $\mathrm{H}_{1}: \mathrm{p} \wedge \sim \mathrm{q} \rightarrow \mathrm{s}$ |
| $\mathrm{H}_{2}: \mathrm{q} \rightarrow \mathrm{r}$ | $\mathrm{H}_{2}: \sim(\mathrm{s} \vee \mathrm{u})$ |
| $\mathrm{H}_{3}: \sim \mathrm{r}$ | $\mathrm{H}_{3}: \mathrm{q} \rightarrow \mathrm{r}$ |
| $\mathrm{T}: \sim \mathrm{p}$ | $\mathrm{T}: \mathrm{p} \rightarrow \mathrm{q} \wedge \mathrm{r}$ |
|  | n) (FM-2002) |
| $\mathrm{H}_{1}: \mathrm{p} \rightarrow \mathrm{q}$ | H1: $\mathrm{p} \rightarrow \mathrm{q}$ |
| $\mathrm{H}_{2}: \mathrm{p} \vee \mathrm{r}$ | $\mathrm{H} 2: \mathrm{q} \rightarrow \mathrm{r}$ |
| $\mathrm{H}_{3}: \sim \mathrm{q}$ | $\mathrm{H} 3: \sim \mathrm{r}$ |

| $\mathrm{H}_{4}: \mathrm{r} \rightarrow(\mathrm{s} \wedge \mathrm{t})$ | $\mathrm{T}: \sim \mathrm{p}$ |
| :--: | :--: |
| T: s |  |
| o) (FM-2002) | p) (FM-2001) $\mathrm{H}_{1}, \mathrm{H}_{2}, \mathrm{H}_{3}, \mathrm{H}_{4} \rightarrow \mathrm{~T}$, onde |
| $\mathrm{H}_{1}: \mathrm{p} \wedge \sim \mathrm{q} \rightarrow \mathrm{s}$ | $\mathrm{H}_{1}: \mathrm{p} \rightarrow \mathrm{q}$ |
| $\mathrm{H}_{2}: \sim(\mathrm{s} \vee \mathrm{u})$ | $\mathrm{H}_{2}: \mathrm{r} \rightarrow \mathrm{s}$ |
| $\mathrm{H}_{3}: \mathrm{q} \rightarrow \mathrm{r}$ | $\mathrm{H}_{3}: \sim \mathrm{q} \wedge \mathrm{r}$ |
| T: $\mathrm{p} \rightarrow \mathrm{q} \wedge \mathrm{r}$ | $\mathrm{H}_{4}: \sim \mathrm{p} \wedge \mathrm{s} \rightarrow \mathrm{x}$ |
|  | T: x |
| q) (FM-2001) | r) (FM-2001) |
| H1: p $\rightarrow$ q | H1: $\sim(\mathrm{p} \wedge \mathrm{q})$ |
| H2: q $\leftrightarrow$ s | H2: $(\sim \mathrm{r}) \rightarrow \mathrm{q}$ |
| H3: u $\vee[\mathrm{r} \wedge(\sim \mathrm{s})]$ | H3: $\sim \mathrm{p} \rightarrow \mathrm{r}$ |
| H4: p | T: r |
| T: u |  |
| s) (FM-2001) | u) (FM-2001) |
| H1: p $\rightarrow$ q | H1: $(\sim \mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r}$ |
| H2: $\mathrm{r} \rightarrow \mathrm{s}$ | H2: $(\mathrm{r} \vee \mathrm{s}) \rightarrow \sim \mathrm{u}$ |
| H3: $(\mathrm{q} \vee \mathrm{s}) \rightarrow \sim \mathrm{u}$ | H3: u |
| H4: u | T: $\sim q$ |
| T: $\sim \mathrm{p} \wedge \sim \mathrm{r}$ |  |
| v) (FM-2000) | x) (FM-2000) |
| H1: $\mathrm{p} \vee(\mathrm{q} \wedge \mathrm{r})$ | H1: $(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r} \wedge \mathrm{s}$ |
| H2: $\mathrm{p} \vee \mathrm{q} \rightarrow \mathrm{s}$ | H2: $\mathrm{r} \wedge \mathrm{s} \rightarrow \mathrm{s}$ |
| T: pvs | H3: 〜s |
|  | T: 〜q |
| w) (FM-2000) | y) (FM-2000) |
| H1: $\mathrm{p} \vee(\mathrm{q} \wedge \mathrm{r})$ | H1: $(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r} \wedge \mathrm{s}$ |
| H2: $\mathrm{p} \vee \mathrm{q} \rightarrow \mathrm{s}$ | H2: $\mathrm{r} \wedge \mathrm{s} \rightarrow \mathrm{s}$ |
| T: pvs | H3: 〜s |
|  | T: $\sim \mathrm{q}$ |
| z) (FM-2000) | aa) (FM-2000) (MD-2003) |
| H1: pvq $\rightarrow \mathrm{r}$ | H1: $\mathrm{s} \rightarrow \mathrm{p} \wedge \mathrm{q}$ |
| H2: s $\rightarrow \mathrm{p} \wedge \mathrm{u}$ | H2: $\sim \mathrm{s} \rightarrow \mathrm{p}$ |
| H3: q $\vee \mathrm{s}$ | H3: $\sim \mathrm{p}$ |
| T: r | T: q |
| ab) (MD-2001) | ac) (MD-2001) |
| a | $\mathrm{p} \vee \mathrm{q}$ |
| $\mathrm{b} \vee \sim \mathrm{c}$ | $\mathrm{p} \rightarrow \mathrm{q}$ |
| $\mathrm{d} \rightarrow \mathrm{c}$ |  |
| $\mathrm{a} \rightarrow \sim \mathrm{b} \wedge \mathrm{e}$ | q |
| $\sim \mathrm{d}$ |  |
| ad) (MD-2001) | ae) (MD-2001) |
| $\mathrm{p} \vee \mathrm{q}$ | b |
| $\mathrm{p} \rightarrow \mathrm{q}$ | $\mathrm{c} \vee \sim \mathrm{d}$ |
| $\sim$ | $\mathrm{e} \rightarrow \mathrm{d}$ |
| p | $\mathrm{b} \rightarrow \sim \mathrm{c} \wedge \mathrm{a}$ |
|  | $\sim \mathrm{e}$ |
| af) (MD-2001) | ag) (MD-2001) |
| H1: $(\mathrm{p} \vee \mathrm{q}) \rightarrow(\mathrm{r} \wedge \mathrm{s})$ | c |
| H2: $(\mathrm{r} \wedge \mathrm{s}) \rightarrow \mathrm{s}$ | $\mathrm{d} \vee \sim \mathrm{e}$ |
| H3: $\sim \mathrm{s}$ | $\mathrm{a} \rightarrow \mathrm{e}$ |
| T: $\sim \mathrm{q}$ | $\mathrm{c} \rightarrow \sim \mathrm{d} \wedge \mathrm{b}$ |
|  | $\sim \mathrm{a}$ |
| ah) $\mathrm{H}_{1} \mathrm{P} \rightarrow \mathrm{Q}$ | ai) $\mathrm{H}_{1} \mathrm{P} \vee \mathrm{Q}$ |
| $\mathrm{H}_{2} \mathrm{P} \rightarrow \mathrm{R}$ | $\mathrm{H}_{2}(\mathrm{R} \rightarrow \mathrm{P}) \rightarrow \mathrm{S}$ |
| T: $\mathrm{P} \rightarrow(\mathrm{Q} \wedge \mathrm{R})$ | $\mathrm{H}_{3} \sim \mathrm{~S}$ |
|  | T:Q |
| aj) $\mathrm{H}_{1} \mathrm{P} \vee(\mathrm{Q} \wedge \mathrm{R})$ | ak) $\mathrm{H}_{1} \mathrm{~A} \vee(\mathrm{~B} \rightarrow \mathrm{C})$ |
| $\mathrm{H}_{2} \mathrm{Q} \rightarrow \mathrm{S}$ | $\mathrm{H}_{2} \mathrm{C} \rightarrow(\mathrm{D} \wedge \mathrm{E})$ |
| $\mathrm{H}_{3} \mathrm{P} \rightarrow \mathrm{U}$ | $\mathrm{H}_{3}(\sim \mathrm{~B} \vee \mathrm{D}) \rightarrow \mathrm{F}$ |

| $\mathrm{H}_{4} \sim(\mathrm{R} \wedge \mathrm{X})$ | $\mathrm{H}_{4} \sim \mathrm{~F}$ |
| :--: | :--: |
| $\mathrm{H}_{5} \mathrm{~S} \rightarrow(\mathrm{X} \vee \mathrm{Y})$ | T: A |
| $\mathrm{H}_{6} \sim \mathrm{U}$ |  |
| T: Y |  |
| al) $\mathrm{H}_{1} \mathrm{P} \vee \mathrm{Q}$ | af) $\mathrm{H}_{1} \mathrm{~A} \leftrightarrow \mathrm{~B}$ |
| $\mathrm{H}_{2} \mathrm{P} \rightarrow \mathrm{Q}$ | $\mathrm{H}_{2} \mathrm{C} \leftrightarrow \mathrm{D}$ |
| T: Q | $\mathrm{T}:(\mathrm{A} \rightarrow \mathrm{D}) \leftrightarrow(\mathrm{B} \rightarrow \mathrm{C})$ |
| ag) $\mathrm{H}_{1}-\mathrm{p} \vee(\mathrm{q} \wedge \mathrm{r})$ | ah) $\mathrm{H}_{1}-(\mathrm{p} \vee \mathrm{q}) \rightarrow(\mathrm{r} \vee \mathrm{s})$ |
| $\mathrm{H}_{2}-(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{s}$ | $\mathrm{H}_{2} \sim(\mathrm{r} \wedge \mathrm{s}) \rightarrow \mathrm{s}$ |
| T: pvs | $\mathrm{H}_{3} \sim \sim \mathrm{~s}$ |
|  | $\mathrm{T}: \sim \mathrm{q}$ |
| ai) $\mathrm{H}_{1}-(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r}$ | aj) $\mathrm{H}_{1}-\mathrm{s} \rightarrow(\mathrm{p} \wedge \mathrm{q})$ |
| $\mathrm{H}_{2}-\mathrm{s} \rightarrow(\mathrm{p} \wedge \mathrm{u})$ | $\mathrm{H}_{2}-\mathrm{s} \rightarrow \mathrm{p}$ |
| $\mathrm{H}_{3}-\mathrm{q} \vee \mathrm{s}$ | $\mathrm{H}_{3}-\mathrm{p}$ |
| T: r | T: q |
| ak) b, c $\vee \sim \mathrm{d}, \mathrm{e} \rightarrow \mathrm{d}, \mathrm{b} \rightarrow \sim \mathrm{c} \wedge \mathrm{a} \vdash \sim \mathrm{e}$ | al) (FM-2005) |
|  | $\mathrm{H}_{1}:(\mathrm{F} \wedge \mathrm{A}) \wedge(\mathrm{C} \wedge \mathrm{B})$ |
|  | $\mathrm{T}: \mathrm{C} \wedge \mathrm{P}$ |
| am) (FM-2005) | an) (FM-2005) |
| $\mathrm{H}_{1}: \mathrm{P} \rightarrow(\mathrm{Q} \rightarrow \mathrm{R})$ | $\mathrm{H}_{1}:(\mathrm{X} \rightarrow \mathrm{R}) \wedge(\mathrm{R} \rightarrow \mathrm{V})$ |
| $\mathrm{H}_{2}: \mathrm{P} \vee \mathrm{S}$ | $\mathrm{H} 2:(\mathrm{V} \rightarrow \mathrm{P}) \wedge(\mathrm{P} \rightarrow \mathrm{A})$ |
| $\mathrm{H}_{3}:(\mathrm{S} \rightarrow \mathrm{X}) \wedge(\mathrm{X} \rightarrow \mathrm{U})$ | $\mathrm{T}: \mathrm{X} \rightarrow \mathrm{P}$ |
| $\mathrm{H}_{4}: \mathrm{V} \rightarrow(\sim \mathrm{U} \wedge \sim \mathrm{R})$ |  |
| $\mathrm{H}_{5}: \mathrm{V}$ |  |
| $\mathrm{T}: \sim \mathrm{Q}$ |  |

50. (FM-2002) Demonstre pelo método dedutivo as seguintes tautologias:
a) $\mathrm{p} \vee(\mathrm{p} \wedge \mathrm{q}) \Leftrightarrow \mathrm{p}$.
b) $[(\mathrm{p} \rightarrow \mathrm{q}) \vee(\mathrm{p} \rightarrow \mathrm{r})] \Leftrightarrow[\mathrm{p} \rightarrow(\mathrm{q} \vee \mathrm{r})]$.
a) $p \vee(p \wedge q) \Leftrightarrow p$

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $p \vee(p \wedge q) \Leftrightarrow$ | $H_{1}$ |
| 2 | $(p \vee p) \wedge(p \vee q)$ | 1, Teorema 2.11 d - Distributiva |
| 3 | $p \wedge(p \vee q)$ | 2, Teorema 2.11 b - Idempotécia <br> Teorema 2.13 - Substituição |
| 4 | $(p \vee c) \wedge(p \vee q)$ | 3, Teorema 2.12 d - Contradição <br> Teorema 2.13 - Substituição |
| 5 | $p \vee(c \wedge q)$ | 4, Teorema 2.11 d - Distributiva |
| 6 | $p \vee(q \wedge c)$ | 5, Teorema 2.11 a - Comutativa <br> Teorema 2.13 - Substituição |
| 7 | $p \vee c$ | 6, Teorema 2.12 f - Contadição |
| 8 | $p$ | 7, Teorema 2.12 g - Contadição |

b) $[(p \rightarrow q) \vee(p \rightarrow r)] \Leftrightarrow[p \rightarrow(q \vee r)]$

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $(p \rightarrow q) \vee(p \rightarrow r) \Leftrightarrow$ | $H_{1}$ |
| 2 | $(-p \vee q) \vee(-p \vee r)$ | 1, Teorema 2.9 b - Condicional <br> Teorema 2.13 - Substituição |
| 3 | $(q \vee-p) \vee(r \vee-p)$ | 2, Teorema 2.11 a - Comutativa <br> Teorema 2.13 - Substituição |
| 4 | $q \vee(-p \vee r) \vee-p$ | 3, Teorema 2.11 c - Associativa |
| 5 | $q \vee(r \vee-p) \vee-p$ | 4, Teorema 2.11 a - Comutativa <br> Teorema 2.13 Substituição |
| 6 | $(q \vee r) \vee(-p \vee-p)$ | 5, Teorema 2.11 c - Associativa |
| 7 | $(q \vee r) \vee-p$ | 6, Teorema 2.11 b - Idempotência <br> Teorema 2.13 Substituição |
| 8 | $-p \vee(q \vee r)$ | 7, Teorema 2.11 a - Comutativa |
| 9 | $p \rightarrow(q \vee r)$ | 8, Teorema 2.9 b - Condicional |

51. (FM-2002) Demonstre:
![img-1.jpeg](img-1.jpeg)
a) Demonstração Direta:

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $p \rightarrow q$ | $H_{1}$ |
| 2 | $p \vee r$ | $H_{2}$ |
| 3 | $\sim q$ | $H_{3}$ |
| 4 | $r \rightarrow(s \wedge u)$ | $H_{4}$ |
| 5 | $\sim p$ | 1, 3, Teorema 2.8 f - Modus Tolles |
| 6 | $r$ | 2, 5, Teorema 2.8 d - Silogismo Disjuntivo |
| 7 | $s \wedge u$ | 46 Teorema 2.8 e - Modus Ponens |
| 8 | $s$ | 7, Teorema 2.8 c Simplificação |

b) Demonstração Indireta

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $p \rightarrow q$ | $H_{1}$ |
| 2 | $q \vee r$ | $H_{2}$ |
| 3 | $\sim r$ | $H_{3}$ |
| 4 | $p$ | $H_{4}$ Negação da Tese |
| 5 | $q$ | 1, 4, Teorema 2.8 e - Modus Ponens |
| 6 | $r$ | 2, 5, Teorema 2.8 e - Modus Ponens |
| 7 | $\sim r \wedge r$ | 3, 6, Conjunção |

c) Demonstração Condicional

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $(p \wedge \sim q) \rightarrow s$ | $H_{1}$ |
| 2 | $\sim(s \vee t)$ | $H_{2}$ |
| 3 | $q \rightarrow r$ | $H_{3}$ |
| 4 | $p$ | $H_{4}$ |
| 5 | $\sim s \wedge \sim t$ | 2, Teorema 2.10 b - De Morgan |
| 6 | $\sim s$ | 5, Teorema 2.8 c - Simplificação |
| 7 | $\sim(p \wedge \sim q)$ | 16 Teorema 2.8 f - Modus Tolles |
| 8 | $p \rightarrow q$ | 7 Teorema 2.9 a - Condicional |
| 9 | $p \rightarrow r$ | 3, 8, Exemplo 2.18 - Transitiva |
| 10 | $r$ | 4, 9,Teorema 2.8 e - Modus Ponens |
| 11 | $q$ | 7,Teorema 2.8 c- Simplificação <br> Teorema 2.8 a - Dupla negação |
| 12 | $q \wedge r$ | 10, 11, Conjunção |

52. (FM-2002) Demonstre pelo método dedutivo as seguintes tautologias:
a) $(\mathrm{p} \wedge \mathrm{q}) \vee \sim \mathrm{p} \Leftrightarrow(\sim \mathrm{q} \rightarrow \sim \mathrm{p})$.
b) $(\mathrm{r} \vee \mathrm{s}) \vee \sim \mathrm{s} \Leftrightarrow \mathrm{t}$.
a) Vamos demonstrar que $(p \wedge q) \vee \sim p \leftrightarrow(\sim q \rightarrow \sim p)$. (cé uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $H_{1}(p \wedge q) \vee \sim p \rightarrow(\sim q \rightarrow \sim p) ; e H_{2}:(q \rightarrow \sim p) \rightarrow(p \wedge q) \vee \sim p$.Vejamos o primeiro argumen

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $(p \wedge q) \vee \sim p$ | $H_{1}$ |

| 2 | $-p \vee(p \wedge q)$ | 1, Teorema 2.11 a - Comutativa |
| :-- | :-- | :-- |
| 3 | $(-p \vee p) \wedge(-p \vee q)$ | 2, Teorema 2.11 d - Distributiva |
| 4 | $t \wedge(-p \vee q)$ | 3, Teorema 2.12 j - Tautologia <br> Teorema 2.13 Substituição |
| 5 | $-p \vee q$ | 4, Teorema 2.11 a - Comutativa <br> Teorema 2.12 c- Tautologia |
| 6 | $q \vee \neg p$ | 5 Teorema 2.11 a - Comutativa |
| 7 | $-[(-q) \wedge p]$ | 6, Teorema 2.10 b - De Morgan |
| 8 | $(-q \rightarrow \neg p)$ | 7, Teorema 2.9 a - Condicional |

Para demostrar o segundo argumento utilizamos o mesmo processo de baixo para cima pois foram utilizadas somentes equivalências lógicas.
b) Vamos demonstrar que $r \vee s) \vee \neg s \leftrightarrow t$, é uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $H, r \vee s) \vee \neg s \rightarrow t$; e $H_{4}: t \rightarrow(r \vee s) \vee \neg s$.Vejamos o primeiro argumen

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $(r \vee s) \vee \neg s$ | $H_{1}$ |
| 2 | $r \vee(s \vee \neg s)$ | 1 Teorema 2.11 c - Associatiava |
| 3 | $r \vee t$ | 2, Teorema 2.12 j - Tautologia <br> Teorema 2.13 - Substituição |
| 4 | $t$ | 3, Teorema 2.12 - Tautologia |

Para demostrar o segundo argumento utilizamos o mesmo processo de baixo para cima pois foram utilizadas somentes equivalências lógicas.
53. (FM-2002) Demonstre:

| a) Direta | b) Indireta | c) condicional |
| :-- | :-- | :-- |
| $\mathrm{H}_{1}: \mathrm{p} \rightarrow \mathrm{q}$ | $\mathrm{H}_{1}: \mathrm{p} \rightarrow \mathrm{q}$ | $\mathrm{H}_{2}: \mathrm{p} \wedge \neg \mathrm{q} \rightarrow \mathrm{s}$ |
| $\mathrm{H}_{3}: \mathrm{p} \vee \mathrm{r}$ | $\mathrm{H}_{3}: \mathrm{q} \rightarrow \mathrm{r}$ | $\mathrm{H}_{3}: \neg(\mathrm{s} \vee \mathrm{u})$ |
| $\mathrm{H}_{3}:: \neg \mathrm{q}$ | $\mathrm{H}_{3}:: \neg \mathrm{r}$ | $\mathrm{H}_{3}: \mathrm{q} \rightarrow \mathrm{r}$ |
| $\mathrm{H}_{4}: \mathrm{r} \rightarrow(\mathrm{s} \wedge \mathrm{t})$ | $\mathrm{T}: \neg \mathrm{p}$ | $\mathrm{T}: \mathrm{p} \rightarrow \mathrm{q} \wedge \mathrm{r}$ |
| $\mathrm{T}: \mathrm{s}$ |  |  |

a) Demonstração Direta:

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $p \rightarrow q$ | $H_{1}$ |
| 2 | $p \vee r$ | $H_{2}$ |
| 3 | $\neg q$ | $H_{3}$ |
| 4 | $r \rightarrow(s \wedge u)$ | $H_{4}$ |
| 5 | $\neg p$ | 1, 3,Teorema 2.8 f - Modus Tolles |
| 6 | $r$ | 2, 5, Teorema 2.8 d - Silogismo Disjuntivo |
| 7 | $s \wedge u$ | 4, 6, Teorema 2.8 e - Modus Ponens |
| 8 | $s$ | 7, Teorema 2.8 c - Simplificação |

b) Demonstração Indireta

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $p \rightarrow q$ | $H_{1}$ |
| 2 | $q \vee r$ | $H_{2}$ |
| 3 | $\neg r$ | $H_{3}$ |
| 4 | $p$ | Negação da Tese |
| 5 | $q$ | 1, 4, Teorema 2.8 e - Modus Ponens |
| 6 | $r$ | 2, 5, Teorema 2.8 e - Modus Ponens |
| 7 | $\neg r \wedge r$ | 3, 6,Cconjunção |

c) Demonstração Condicional

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $(p \wedge \neg q) \rightarrow s$ | $H_{1}$ |
| 2 | $\neg(s \vee t)$ | $H_{2}$ |
| 3 | $q \rightarrow r$ | $H_{3}$ |
| 4 | $p$ | $H_{4}$ |

| 5 | $-s \wedge-t$ | 2, Teorema 2.10 b-De Morgan |
| :-- | :-- | :-- |
| 6 | $-s$ | 5, Teorema 2.8 c - Simplificação |
| 7 | $-(p \wedge-q)$ | 1, 6, Teorema 2.8 f - Modus Tolles |
| 8 | $p \rightarrow q$ | 7, Teorema 2.9 a - Condicional |
| 9 | $p \rightarrow r$ | 3, 8, Teorema 2.9 e - Reductio Absurdum |
| 10 | $r$ | 4, 9, Teorema 2.8 e - Modus Ponens |
| 11 | $q$ | 7, Teorema 2.8 c - Simplificação <br> Teorema 2.8 a - Dupla Negação |
| 12 | $q \wedge r$ | 10,11, Conjunção |

54. (FM-2002) Usando as regras de equivalência, mostre a seguinte tautologia:

$$
(\mathrm{p} \rightarrow \mathrm{q}) \rightarrow \mathrm{r} \Leftrightarrow \mathrm{r} \vee(\mathrm{p} \wedge \sim \mathrm{q})
$$

Mostraremos que $(p \rightarrow q) \rightarrow r \Leftrightarrow r \vee(p \wedge \sim q)$ é uma tautologia, de fato:

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $(p \rightarrow q) \rightarrow r \Leftrightarrow$ | $H_{1}$ |
| 2 | $\Leftrightarrow(-p \vee q) \rightarrow r \Leftrightarrow$ | 1, Teorema 2.9 b- Condicional <br> Teorema 2. 13 - Substituição |
| 3 | $\Leftrightarrow \sim(-p \vee q) \vee r \Leftrightarrow$ | 2,Teorema 2. 9 b - Condicional |
| 4 | $\Leftrightarrow r \vee \sim(-p \vee q)$ | 3, Teorema 2.11 c- - Distributiva |
| 5 | $r \vee(p \wedge \sim q)$ | 4, Teorema 2. 10b - De Morgan <br> Teorema 2. 13 - Substituição |

55. (FM-2002) Usando o método direto ou indireto e que c represente uma contradição demonstre o teorema $\mathrm{H}_{1}, \mathrm{H}_{2}, \mathrm{H}_{3} \mathrm{~T}$, onde
$\mathrm{H}_{1}: \mathrm{p} \rightarrow \mathrm{q}$
$\mathrm{H}_{2}: \mathrm{p} \vee \mathrm{q}$
$\mathrm{H}_{3} \sim \mathrm{p}$
T: c
Usaremoa o método direto papa mostrar o desjado.

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $p \rightarrow q$ | $H_{1}$ |
| 2 | $p \vee q$ | $H_{2}$ |
| 3 | $\sim q$ | $H_{3}$ |
| 4 | $\sim p$ | 1, 3, Teorema 2.8 f- Modus Tolles |
| 5 | $Q$ | 2, 4, Teorema 2. 8 d - Silogismo Disjuntivo |
| 6 | $q \wedge \sim p$ | 5, 3, Conjunção |
| 7 | $c$ | 6, Teorema 2.12 e - Contradição |

56. (FM-2002) Usando as regras de equivalência, mostre a seguinte tautologia: $(\mathrm{q} \wedge \mathrm{r}) \rightarrow \mathrm{p} \Leftrightarrow[\mathrm{q} \rightarrow(\mathrm{r} \rightarrow \mathrm{p})]$.

Mostraremos que $(q \wedge r) \rightarrow p \Leftrightarrow(q \rightarrow(r \rightarrow p)$ )é uma tautologia, de fato:

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $(q \wedge r) \rightarrow p$ | $H_{1}$ |
| 2 | $\sim(q \wedge r) \vee p$ | 1, Teorema 2.9 b - Condicional |
| 3 | $(\sim q \vee \sim r) \vee p$ | 2, Torema 2.10 b-De Morgan <br> Teorema 2.13 - Substituição |
| 4 | $\sim q \vee(\sim r \vee p)$ | 3, Teorema 2.11 c - Associativa <br> Teorema 2.13 - Substituição |
| 5 | $\sim q \vee(r \rightarrow p)$ | 4, Teorema 2.9 b -Condicional <br> Teorema 2.13 - Substituição |

| 6 | $q \rightarrow(r \rightarrow p)$ | 5, Teorema 2.9 b - Condicional <br> Teorema 2.13 - Substituição |
| :-- | :-- | :-- |

57. (FM-2002) Usando o método direto ou indireto, demonstre o teorema $\mathrm{H}_{1}, \mathrm{H}_{2}, \mathrm{H}_{3}, \mathrm{H}_{4} \rightarrow \mathrm{~T}$, onde $\mathrm{H} 1:(\mathrm{p} \rightarrow \mathrm{q}) \quad \mathrm{H}_{2}:(\mathrm{r} \rightarrow \mathrm{s}) \quad \mathrm{H}_{3}(\mathrm{q} \vee \mathrm{s}) \rightarrow \sim \mathrm{m} \quad \mathrm{H}_{4}: \mathrm{m} \quad \mathrm{T}:(\sim \mathrm{p} \wedge \sim \mathrm{r})$

Usaremos o método direto para mostrar o desejado.

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $p \rightarrow q$ | $H_{1}$ |
| 2 | $r \rightarrow s$ | $H_{2}$ |
| 3 | $(q \vee s) \rightarrow \sim m$ | $H_{3}$ |
| 4 | $m$ | $H_{4}$ |
| 5 | $\sim(q \vee s)$ | 3,4 , Teorema 2.8 f - Modus Tolles |
| 6 | $\sim q \wedge \sim s$ | 5, Teorema 2.10 b - De Morgan |
| 7 | $\sim q$ | 6, Teorema 2.8 c - Simplificação |
| 8 | $\sim s$ | 6, Teorema 2.8 c - Simplificação |
| 9 | $\sim p$ | 1, 7, Teorema 2.8 f - Modus Tolles |
| 10 | $\sim r$ | 2, 8, Teorema 2.8 f - Modus Tolles |
| 11 | $\sim p \wedge \sim r$ | 9, 10, Conjunção |

58. (FM-2002) Mostre que $2^{n}<n$ ! para todo $n \in I N$ e $n \geq 4$.

Primeiramente mostraremos que $P(4)$ é verdadeiro. De fato, $2^{4}=16<2=4$ !. Suponhamos agora que $p(k)$ seja verdadeiro, logo, $2^{k}<k$ !. Queremos mostrar que $P(k+1)$ é verdadeiro. De fato, $2.2^{k}<2 k$ ! implica $2^{k+1}<2 k$ !. Como $2 k$ ! $<(k+1)$ ! Temos então $2^{k+1}<(k+1)!$
59. (FM-2002) Mostre que $(\mathrm{p} \wedge \mathrm{q}) \rightarrow \mathrm{r} \Leftrightarrow[(\mathrm{p} \rightarrow \mathrm{r}) \wedge(\mathrm{q} \rightarrow \mathrm{r})]$, utilizando o método dedutivo.

Solução:

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $(p \wedge q) \rightarrow r$ | $H$ |
| 2 | $\sim(p \wedge q) \vee r$ | 1, Teorema 2.9 b - Condicional |
| 3 | $(\sim p \vee \sim q) \vee r$ | 2, Teorema 2.10 a - De Morgan |
| 4 | $\sim p \vee(\sim q \vee r)$ | 3, Teorema 2.11 c - Associativa |
| 5 | $\sim p \vee[\sim q \vee(r \vee r)$ | 4, Teorema 2.12 j - Tautologia |
| 6 | $\sim p \vee[r \vee(\sim q \vee r)$ | 5, Teorema 2.11 c - Associativa <br> Teorema 2.11 a - Comutativa |
| 7 | $(\sim p \vee r) \vee(\sim q \vee r)$ | 6, Teorema 2.11 c - Associativa |
| 8 | $(p \rightarrow r) \wedge(q \rightarrow r)$ | 7, Teorema 2.9 b - Condicional |

60. (FM-2001) Utilizando o método dedutivo, demonstre as seguintes tautologias:
a) $\mathrm{p} \Rightarrow(\mathrm{p} \wedge \mathrm{q}) \vee \sim \mathrm{p}$.
b) $(\mathrm{p} \rightarrow \mathrm{q}) \wedge \mathrm{p} \Leftrightarrow \mathrm{p} \wedge \mathrm{q}$.

Solução: a) Vamos demonstrar que $p \rightarrow(p \wedge q) \vee \sim p$.é uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade do argumento $H_{1}: p \rightarrow(p \wedge q) \vee \sim p$. Vejamos:

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $p$ | $H_{1}$ |
| 2 | $(p \vee \sim q)$ | 1, Teorema 2.8 b - Adição |
| 3 | $(p \vee \sim q) \wedge t$ | 2, Teorema 2.12 c - Identidade |
| 4 | $(p \vee \sim q) \wedge(q \vee \sim q)$ | 3, Teorema 2.12 j - Tautologia |
| 5 | $(p \wedge q) \vee \sim q$ | 4, Teorema 2.11 d - Distributiva |

b) Vamos demonstrar que $(p \sim q) \wedge p \leftrightarrow p \wedge q$ é uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $H_{1}:(p \rightarrow q) \wedge p \rightarrow p \wedge q$ e $H_{2}: p \wedge q \rightarrow(p \sim q)$ Vejamos o primeiro argumento

| Ordem | Proposição | Justificativa |
| :--: | :--: | :--: |

| 1 | $(p \rightarrow q) \wedge p$ | $H_{1}$ |
| :--: | :-- | :-- |
| 2 | $-(p \wedge \neg q) \wedge p$ | 1, Teorema 2.9 a - condicional |
| 3 | $(\neg p \vee q) \wedge p$ | 2, Teorema 2.10 a - De Morgan |
|  |  | Teorema 2.13 - Substituição |
| 4 | $(\neg p \wedge p) \vee(q \wedge p)$ | 3, Teorma 2.11 d - distributiva |
| 5 | $c \vee(q \wedge p)$ | 4, Teorema 2.12 e - contradição |
| 6 | $q \wedge p$ | 5, Teorema 2.12 c - identidade |
| 7 | $p \wedge q$ | 6, Teorema2.11 a - comutativa |

Para demostrar o segundo argumento utilizamos o mesmo processo de baixo para cima pois foram utilizadas somente equivalências lógicas.
61. (FM-2001) Considerando as hipóteses $\mathrm{H}_{1}, \mathrm{H}_{2}, \mathrm{H}_{3}$ e $\mathrm{H}_{4}$, demonstre a tese T , utilizando-se de um método direto ou indireto.
$\mathrm{H}_{1}: \mathrm{p} \rightarrow \mathrm{q} \quad \mathrm{H}_{2}: \mathrm{r} \rightarrow \mathrm{s} \quad \mathrm{H}_{3}: \neg \mathrm{q} \wedge \mathrm{r} \quad \mathrm{H}_{4}: \neg \mathrm{p} \wedge \mathrm{s} \rightarrow \mathrm{x} \quad \mathrm{T}: \mathrm{x}$
Solução:

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $p \rightarrow q$ | $H_{1}$ |
| 2 | $r \rightarrow s$ | $H_{2}$ |
| 3 | $\neg q \wedge r$ | $H_{3}$ |
| 4 | $\neg p \wedge s \rightarrow x$ | $H_{4}$ |
| 5 | $\neg q$ | 3,Teorema 2.8 c - Simplificação |
| 6 | $\neg p$ | 1,5,Teorema 2.9 d - Contra-positiva |
| 7 | $r$ | 3,Teorema 2.8 c - Simplificação |
| 8 | $s$ | 2,7, Teorema 2.8 e - Modus Ponens |
| 9 | $\neg p \wedge s$ | 6,8, Conjunção |
| 10 | $x$ | 4, 9,Teorema 2.8 - Modus Ponens |

62. (FM-2001) Demonstre, pelo Método Dedutivo, as seguintes proposições:
a) $[p \rightarrow(p \wedge q)] \Leftrightarrow(p \rightarrow q)$;
b) $[(p \rightarrow q) \rightarrow q)] \Leftrightarrow(p \vee q)$.

# Solução: 

a) Vamos demonstrar que $[p \rightarrow(p \wedge q)] \leftrightarrow(p \rightarrow q)$ :é uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $H_{1}[p \rightarrow(p \wedge q)] \rightarrow(p \rightarrow q) ; e H_{2} ;(p \rightarrow q) \rightarrow p \rightarrow(p \wedge q)]$. Vejamos o primeiro argumento

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $p \rightarrow(q \wedge q) \Leftrightarrow$ | $H_{1}$ |
| 2 | $-[p \wedge \neg(p \wedge q)]$ | 1, Teorema 2.9 a - Condicional |
| 3 | $-[p \wedge \neg p \vee \neg q)]$ | 2, Teorema 2.10 a - De Morgan |
|  |  | Teorema 2.13 - Substituição |
| 4 | $-[(p \wedge \neg p) \vee(p \wedge \neg q)]$ | 3, Teorema 2.11 d - Distributiva |
|  |  | Teorema 2.13 - Substituição |
| 5 | $-[c \vee(p \wedge \neg q)]$ | 4, Teorema 2.12 e - Contadição |
|  |  | Teorema 2.13 - Substituição |
| 6 | $-[(p \wedge \neg q) \vee c]$ | 5, Teorema 2.11 a - Comutativa |
|  |  | Teorema 2.13 - Substituição |
| 7 | $-(p \wedge \neg q)$ | 6, Teorema 2.12 g - Contradição |
|  |  | Teorema 2.13 - Substituição |
| 8 | $p \rightarrow q$ | 7, Teorema 2.9 a - Condicional |

Para demostrar o segundo argumento utilizamos o mesmo processo de baixo para cima pois foram utilizadas somente equivalências lógicas.

b) Vamos demonstrar que $[(p \rightarrow q) \rightarrow q)] \leftrightarrow(p \vee q) . . \mathrm{e}$ uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $H_{1}[(p \rightarrow q) \rightarrow q)] \rightarrow(p \vee q) . e H_{2}:(p \vee q) . \rightarrow[(p \rightarrow q) \rightarrow q)]$. Vejamos o primeiro argumento

| Ordem | Proposição | Justificativa |
| :--: | :--: | :-- |
| 1 | $(p \rightarrow q) \rightarrow q \Leftrightarrow$ | $H_{1}$ |
| 2 | $\sim[(p \rightarrow q) \wedge(\sim q)]$ | 1, Teorema 2.9 a - Condicional |
| 3 | $\sim(p \rightarrow q) \vee(\sim(\sim q))$ | 2, Teorema 2.10 a - De Morgan |
| 4 | $\sim(p \rightarrow q) \vee q$ | 4, Teorema 2.8 a - Dupla negação <br> Teorema 2.13 - Substituição |
| 5 | $\sim[\sim(p \wedge(\sim q))] \vee q$ | 4, Teorema 2.9 a - Condicional <br> Teorema 2.13 - Substituição |
| 6 | $[p \wedge(\sim q)] \vee q$ | 5, Teorema 2.8 a - Dupla negação <br> Teorema 2.13 - Substituição |
| 7 | $q \vee[p \wedge(\sim q)]$ | 6, Teorema 2.11 a - Comutativa |
| 8 | $(q \vee p) \wedge[q \vee(\sim q)]$ | 7, Teorema 2.11 d - Distibutiva |
| 9 | $(q \vee p) \wedge t$ | 8, Teorema 2.12 j - Tautologia <br> Teorema 2.13 - Substituição |
| 10 | $q \vee p$ | 9, Teorema 2.12 c - Identidade |
| 11 | $p \vee q$ | 10, Teorema 2.11 a - Comutativa |

Para demostrar o segundo argumento utilizamos o mesmo processo de baixo para cima pois foram utilizadas somente equivalências lógicas
63. (FM-2001) Mostre pelo método direto ou indireto as seguintes tautologias:

| a) H1: p $\rightarrow$ q | b) H1: $\sim(\mathrm{p} \wedge \mathrm{q})$ |
| :--: | :--: |
| H2: $\mathrm{q} \leftrightarrow \mathrm{s}$ | H2: $(\sim \mathrm{r}) \rightarrow \mathrm{q}$ |
| H3: $\mathrm{u} \vee[\mathrm{r} \wedge(\sim \mathrm{s})]$ | H3: $\sim \mathrm{p} \rightarrow \mathrm{r}$ |
| H4: p | T: r |
| T: u |  |

a) Faremos pelo Método Direto

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $p \rightarrow q$ | $H_{1}$ |
| 2 | $q \rightarrow s$ | $H_{2}$ |
| 3 | $u \vee[r \wedge(\sim s)]$ | $H_{3}$ |
| 4 | $p$ | $H_{4}$ |
| 5 | $(u \vee r) \wedge(u \vee(\sim s))$ | 3, Teorema 2.11 d - Distributiva |
| 6 | $(u \vee \sim s)$ | 5, Teorema 2.8 c - Simplificação |
| 7 | $Q$ | 1, 4, Teorema 2.8 e - Modus Ponens |
| 8 | $S$ | 2,7, Teorema 2.8 e - Modus Ponens |
| 9 | $(\sim s) \vee u$ | 6, Teorema 2.11 a - Comutativa |
| 10 | $U$ | 9, 8,Teorema 2.8 d Silogismo <br> disjuntivo |

b) Faremos pelo Método Indireto:

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $\sim(p \wedge q)$ | $H_{1}$ |
| 2 | $(\sim r) \rightarrow q$ | $H_{2}$ |
| 3 | $(\sim p) \rightarrow r$ | $H_{3}$ |
| 4 | $\sim r$ | Negação da Tese |
| 5 | $\sim(\sim p)$ | 3, 4, Teorema 2.8 f - Modus Tolles |

| 6 | $p$ | 5, Teorema 2.8 a - Dupla Negação |
| :--: | :-- | :-- |
| 7 | $(-p) \vee(-q)$ | 1, Teorema 2.10 a - De Morgan |
| 8 | $\sim q$ | 7, 6, Teorema 2.8 d - Silogismo Disjuntivo |
| 9 | $q$ | 2, 4, Teorema 2.8 e - Modus Ponens |
| 10 | $q \wedge(-q)$ | 8, 9, Conjunção |
| 11 | $c$ | 10, Teorema 2.12 e - Contradição |

Como negamos a tese e chegamos em uma contradição temos o desejado
64. (FM-2001) Demonstre, pelo Método Dedutivo, as seguintes proposições:
a) $[(p \rightarrow q) \wedge(p \rightarrow r)] \Leftrightarrow[p \rightarrow(q \wedge r)]$
b) $[\sim(p \vee q) \vee(\sim p \wedge q)] \Leftrightarrow \sim p$.

Solução:
a) Vamos demostrar que $[(p \rightarrow q) \wedge(p \rightarrow r)] \leftrightarrow[p \rightarrow(q \wedge r)]$ e uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $H_{1}[(p \rightarrow q) \wedge(p \rightarrow r)] \rightarrow[p \rightarrow(q \wedge r)]$ e $H_{2}[p \rightarrow(q \wedge r)] \rightarrow[(p \rightarrow q) \wedge(p \rightarrow r)]$. Vejamos o primeiro argumento

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $(p \rightarrow q) \wedge(p \rightarrow r)$ | $H_{1}$ |
| 2 | $(-p \vee q) \wedge(-p \vee r)$ | 1, Teorema 2.9 b - Condicional <br> Teorema 2.13 - Substituição |
| 3 | $\sim p \vee(q \wedge r)$ | 2, Teorema 2.10 d - Distributiva |
| 4 | $p \rightarrow(q \wedge r)$ | 3, Teorema 2.9 b - Condicional |

Para demonstrar o segundo aergumento utlizaremos o mesm processo de baixo para cima pois foram utilizadas somente equivalências lógicas.
b) Vamos demostrar que $[-(p \vee q) \vee(-p \wedge q)] \leftrightarrow \sim p$ é uma tautologia utilizando método dedutivo.Para isto demos mostrar a validade dos argumentos $H_{1}[-(p \vee q) \vee(-p \wedge q)] \rightarrow-p$ e $H_{2} p \rightarrow[-(p \vee q) \vee(-p \wedge q)]$. Vejamos o primeiro argumento

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $\sim(p \vee q) \vee(-p \wedge q)$ | $H_{1}$ |
| 2 | $(-p \wedge \sim q) \vee(-p \wedge q)$ | 1, Teorema 2.10 b - De Morgan <br> Teorema 2.13 - Substituição |
| 3 | $\sim p \wedge(-q \vee q)$ | 2, Teorema 2.11 d - Distributiva |
| 4 | $\sim p \wedge t$ | 3, Teorema 2.12 j - Tautologia <br> Teorema 2.13 Substituição |
| 5 | $\sim p$ | 4, Teorema 2.12 c - Tautologia |

Para demonstrar o segundo aergumento utlizaremos o mesm processo de baixo para cima pois foram utilizadas somente equivalências lógicas.
65. (FM-2001) Mostre pelo método direto ou indireto as seguintes tautologias:
a) H1: $p \rightarrow q$
b) H1: $(-p \vee q) \rightarrow r$
H2: $(\mathrm{r} \vee \mathrm{s}) \rightarrow \sim \mathrm{u}$
H3: $(\mathrm{q} \vee \mathrm{s}) \rightarrow \sim \mathrm{u}$
H3: u
H4: u
T: $\sim \mathrm{p} \wedge \sim \mathrm{r}$
T: $\sim \mathrm{p} \wedge \sim \mathrm{r}$

Solução:
a)

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $a \rightarrow a$ | $H_{1}$ |
| 2 | $r \rightarrow s$ | $H_{2}$ |
| 3 | $(a \vee s) \rightarrow \sim u$ | $H_{3}$ |
| 4 | $u$ | $H_{4}$ |
| 5 | $\sim(\sim u)$ | 4, Teorema 2.8 a - Duplo Negação |
| 6 | $\sim(a \vee s)$ | 3, 5, Teorema 2.8 f - Modus Tolles |

| 7 | $(-a) \wedge(-s)$ | 6, Teorema 2.10 b-De Morzan |
| :--: | :-- | :-- |
| 8 | $\sim s$ | 7, Teorema 2.8 c-Simplificação |
| 9 | $\sim r$ | 2,8 Teorema 2.8 f-Modus Tolles |
| 10 | $\sim q$ | 7, Teorema 2.8 c-Simplificação |
| 11 | $\sim p$ | 1,7 Teorema 2.8 f-Modus Tolles |
| 12 | $\sim p \wedge \sim r$ | 9,11, Conjuncão |

b)

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | , $(\sim p \vee q) \rightarrow r$ | $H_{1}$ |
| 2 | $(r \vee s) \rightarrow \sim u$ | $H_{2}$ |
| 3 | $u$ | $H_{3}$ |
| 4 | $\sim(\sim u)$ | 3, Teorema 2.8 a-Dupla Negação |
| 5 | $\sim(r \vee s)$ | 2, 4, Teorema 2.8 fModus Tolles |
| 6 | $(\sim r) \wedge(\sim s)$ | 5, Teorema 2.10 b De Morgan |
| 7 | $\sim r$ | 6, Teorema 2.8 c-Simplificação |
| 8 | $\sim(\sim p \vee q)$ | 1, 7, Teorema 2.8 f-Modus Tolles |
| 9 | $\sim(\sim p) \wedge \sim q$ | 8, Teorema 2.10 b-De Morgan |
| 10 | $\sim q$ | 9, Teorema 2.8 c-Simplificação |

66. (MD-2001) Para cada inferência abaixo, demonstre sua validade (justificando cada passo) ou dê um contraexemplo:

| q $\vee$ p | q $\vee$ p |
| :-- | :-- |
| q $\rightarrow$ p | q $\rightarrow$ p |
| $\ldots \ldots \ldots$ | $\ldots \ldots \ldots$ |
| p | q |

67. (MD-2001) Dada a seguinte proposição:
$[\mathrm{r} \rightarrow(\mathrm{p} \wedge \sim \mathrm{q})] \leftrightarrow[\mathrm{p} \rightarrow(\sim \mathrm{r} \vee \mathrm{q})]$
a) determine, usando uma tabela-verdade, seus valores-verdade;
b) diga se é uma tautologia (justifique);
c) diga se é equivalente à proposição $\sim$ r (justifique).
68. (MD-2001) Demonstre, justificando cada passo, a seguinte inferência:
p
$\mathrm{q} \vee \sim \mathrm{r}$
$\mathrm{s} \rightarrow \mathrm{r}$
$\mathrm{p} \rightarrow \sim \mathrm{q} \wedge \mathrm{u}$
$\sim \mathrm{s}$
69. (MD-2001) Demonstre, utilizando o método dedutivo, a tautologia $[(\mathrm{p} \vee \mathrm{q}) \leftrightarrow(\mathrm{p} \wedge \mathrm{q}) \equiv(\mathrm{p} \leftrightarrow \mathrm{q})$. Solução:

| 1. $(\mathrm{p} \vee \mathrm{q}) \leftrightarrow(\mathrm{p} \wedge \mathrm{q})$ |  |
| :-- | :-- |
| 2. $[(\mathrm{p} \vee \mathrm{q}) \rightarrow(\mathrm{p} \wedge \mathrm{q})] \wedge[(\mathrm{p} \wedge \mathrm{q}) \rightarrow(\mathrm{p} \vee \mathrm{q})]$ | $(\mathrm{EL}-2)$ |
| 3. $[-(\mathrm{p} \vee \mathrm{q}) \vee(\mathrm{p} \wedge \mathrm{q})] \wedge[-(\mathrm{p} \wedge \mathrm{q}) \vee(\mathrm{p} \vee \mathrm{q})]$ | $(\mathrm{EL}-1 \mathrm{~b})$ |
| 4. $[(-p \wedge \sim q) \vee(p \wedge q)] \wedge[(-p \vee \sim q) \vee(p \vee q)]$ | $(\mathrm{EL}-8 \mathrm{a}, \mathrm{EL}-8 \mathrm{~b})$ |
| 5. $[(-p \wedge \sim q) \vee(p \wedge q)] \wedge[(-p \vee p) \vee(\sim q \vee q)]$ | $(\mathrm{EL}-5, \mathrm{EL}-9)$ |
| 6. $[(-p \wedge \sim q) \vee(p \wedge q)] \wedge t$ | $(\mathrm{EL}-11 \mathrm{~h}, \mathrm{EL}-6 \mathrm{a})$ |
| 7. $[(-p \wedge \sim q) \vee(p \wedge q)]$ | $(\mathrm{EL}-11 \mathrm{a})$ |
| 8. $[(-p \wedge \sim q) \vee p] \wedge[(-p \wedge \sim q) \vee q]$ | $(\mathrm{EL}-10 \mathrm{~b})$ |
| 9. $[(\mathrm{p} \vee \sim \mathrm{p}) \wedge(\mathrm{p} \vee \sim \mathrm{q})] \wedge[(\mathrm{q} \vee \sim \mathrm{p}) \wedge(\mathrm{q} \vee \sim \mathrm{q})]$ | $(\mathrm{EL}-5, \mathrm{EL}-10 \mathrm{~b}))$ |
| 10. $(\mathrm{p} \vee \sim \mathrm{q}) \wedge(\mathrm{q} \vee \sim \mathrm{p})$ | $(\mathrm{EL}-11 \mathrm{~h}, \mathrm{EL}-11 \mathrm{a})$ |
| 11. $\mathrm{p} \rightarrow \mathrm{q} \wedge \mathrm{q} \rightarrow \mathrm{p}$ | $(\mathrm{EL}-1 \mathrm{~b})$ |
| 12. $\mathrm{p} \leftrightarrow \mathrm{q}$ | $(\mathrm{EL}-2)$ |

70. (MD-2001) Demonstre, utilizando o método direto ou indireto

$$
\left\{\begin{array}{l}
\mathrm{H} 1:(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r} \\
\mathrm{H} 2:(\mathrm{r} \vee \mathrm{q}) \rightarrow(\mathrm{p} \rightarrow \mathrm{~s}) \\
\mathrm{H} 3: \mathrm{p} \wedge \mathrm{t} \\
\mathrm{~T}: \mathrm{s}
\end{array}\right.
$$

Solução:

| $1 .(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r}$ | (Hipótese 1) |
| :-- | :-- |
| $2 .(\mathrm{r} \vee \mathrm{q}) \rightarrow(\mathrm{p} \rightarrow \mathrm{s})$ | (Hipótese 2) |
| $3 . \mathrm{p} \wedge \mathrm{t}$ | (Hipótese 3) |
| $4 . \mathrm{p}$ | $(3,1-2 \mathrm{a})$ |
| $5 . \mathrm{p} \vee \mathrm{q}$ | $(4,11 \mathrm{a})$ |
| $6 . \mathrm{r}$ | $(1,5,14)$ |
| $7 . \mathrm{r} \vee \mathrm{q}$ | $(6,11 \mathrm{a})$ |
| $8 . \mathrm{p} \rightarrow \mathrm{s}$ | $(2,7,14)$ |
| $9 . \mathrm{s}$ | $(8,4,14)$ |

71. (MD-2001) Demonstre, utilizando o método dedutivo, a tautologia $(\mathrm{p} \wedge \mathrm{q}) \vee \neg \mathrm{p} \Leftrightarrow(\neg \mathrm{q} \rightarrow \neg \mathrm{p})$. Solução:
$(\mathrm{p} \wedge \mathrm{q}) \vee \neg \mathrm{p} \Leftrightarrow(\neg \mathrm{q} \rightarrow \neg \mathrm{p})$

| $1 .(\mathrm{p} \wedge \mathrm{q}) \vee \neg \mathrm{p}$ |  |
| :-- | :-- |
| $2 . \neg \mathrm{p} \vee(\mathrm{p} \wedge \mathrm{q})$ | $\mathrm{EL}-5(\mathrm{~b})$ |
| $3 .(\neg \mathrm{p} \vee \mathrm{p}) \wedge(\neg \mathrm{p} \vee \mathrm{q})$ | $\mathrm{EL}-10(\mathrm{~b})$ |
| $4 . \mathrm{t} \wedge(\neg \mathrm{p} \vee \mathrm{q})$ | $\mathrm{EL}-11(\mathrm{~g})$ |
| $5 .(\neg \mathrm{p} \vee \mathrm{q})$ | $\mathrm{EL}-11(\mathrm{a})$ |
| $6 . \mathrm{p} \rightarrow \mathrm{q}$ | $\mathrm{EL}-1(\mathrm{~b})$ |
| $7 . \neg \mathrm{q} \rightarrow \neg \mathrm{p}$ | $\mathrm{EL}-7$ |

72. (MD-2001) Demonstre, utilizando o método direto ou indireto

$$
\begin{aligned}
& \mathrm{H} 1:(\mathrm{p} \vee \mathrm{q}) \rightarrow(\mathrm{r} \wedge \mathrm{~s}) \\
& \mathrm{H} 2:(\mathrm{r} \wedge \mathrm{~s}) \rightarrow \mathrm{s} \\
& \mathrm{H} 3: \neg \mathrm{s} \\
& \mathrm{~T}: \neg \mathrm{q}
\end{aligned}
$$

Solução:

| $1 .(\mathrm{p} \vee \mathrm{q}) \rightarrow(\mathrm{r} \wedge \mathrm{s})$ | (Hipótese 1) |
| :-- | :-- |
| $2 .(\mathrm{r} \wedge \mathrm{s}) \rightarrow \mathrm{s}$ | (Hipótese 2) |
| $3 . \neg \mathrm{s}$ | (Hipótese 3) |
| $4 . \neg(\mathrm{r} \wedge \mathrm{s})$ | $(2,3,1-6)$ |
| $5 . \neg(\mathrm{p} \vee \mathrm{q})$ | $(1,4,1-6)$ |
| $6 . \neg \mathrm{p} \wedge \neg \mathrm{q}$ | $(5, \mathrm{EL}-8(\mathrm{~b}))$ |
| $5 . \neg \mathrm{q}$ | $(6,1-2(\mathrm{~b}))$ |

# 73. (FM-2001) 

i) Utilizando o método dedutivo, demonstre as seguintes tautologias:
a) $\mathrm{p} \Rightarrow(\mathrm{p} \wedge \mathrm{q}) \vee \neg \mathrm{q}$.
b) $(\mathrm{p} \rightarrow \mathrm{q}) \wedge \mathrm{p} \Leftrightarrow \mathrm{p} \wedge \mathrm{q}$.

## Solução:

a)

| $P \Rightarrow$ | $H$ |
| :-- | :-- |
| $\Rightarrow P \vee(\neg Q) \equiv$ | RI 1a (adição) |
| $\equiv(P \vee \neg Q) \wedge t$ | EL 11a (tautologia- contradição) |
| $\equiv(P \vee \neg Q) \wedge(Q \vee \neg Q)$ | EL 11b (tautologia- contradição) EL 4b(comutativa) |
| $\equiv \neg Q \vee(P \wedge Q)$ | EL 10b (distributiva) |
| $\equiv(P \wedge Q) \vee \neg Q$ | EL 4 b (comutativa) |

| $(P \rightarrow Q) \wedge P \equiv$ |  |
| :-- | :-- |
| $\equiv(\sim P \vee Q) \wedge P$ | EL 1a (condicional) |
| $\equiv P \wedge(\sim P \vee Q)$ | EL 4a (comutativa) |
| $\equiv(P \wedge \sim P) \vee(P \mathrm{Q})$ | EL 10a (distributiva) |
| $\equiv c \vee P \wedge Q$ | EL 11c (tautologia - contradição) |
| $\equiv P \wedge Q$ | EL4b (comutativa)EL 11e (tautologia -contradição) |

74. (FM-2000) Mostre pelo método direto ou indireto as seguintes tautologias.
a) H1: $\mathrm{p} \vee(\mathrm{q} \wedge \mathrm{r})$
b) H1: $(\mathrm{p} \vee \mathrm{q}) \rightarrow \mathrm{r} \wedge \mathrm{s}$
H2: $\mathrm{r} \wedge \mathrm{s} \rightarrow \mathrm{s}$
T: $\mathrm{p} \vee \mathrm{s}$
H3: $\sim \mathrm{s}$
$\mathrm{T}: \sim \mathrm{q}$

# Solução: 

a)

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $p \vee(q \wedge r)$ | $H_{1}$ |
| 2 | $p \vee q \rightarrow s$ | $H_{2}$ |
| 3 | $(p \vee q) \wedge(p \vee r)$ | 1, Teorema 2.11 d - Distributiva |
| 4 | $(p \vee q)$ | 3, Teorema 2.8 c - Simplificação |
| 5 | $S$ | 2, 4,Teorema 2.8 e - Modus Ponens |
| 6 | $p \vee s$ | 5, Teorema 2.8 b - Adição <br> Teorema2.11 a Comutativa |

b)

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $(p \vee q) \rightarrow(r \wedge s)$ | $H_{1}$ |
| 2 | $r \wedge s \rightarrow s$ | $H_{2}$ |
| 3 | $\sim s$ | $H_{3}$ |
| 4 | $p \vee q \rightarrow s$ | 1,2, Exemplo 2.18 - Transitiva |
| 5 | $\sim(p \vee q)$ | 3,4, Teorema 2.8 f - Modus Tolles |
| 6 | $\sim p \wedge \sim q$ | 5, Teorema 2.10 b - De Morgan |
| 7 | $\sim q$ | 6, Teorema 2.8 c - Simplificação |

Outra solução:

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $(p \vee q) \rightarrow r \wedge s$ | $H_{1}$ |
| 2 | $r \wedge s \rightarrow s$ | $H_{2}$ |
| 3 | $\sim s$ | $H_{3}$ |
| 4 | $\sim(r \wedge s)$ | 2,3, Teorema 2.8 f - Modus Tolles |
| 5 | $\sim(p \vee q)$ | 1,4, Teorema 2.8 f - Modus Tolles |
| 6 | $\sim p \wedge \sim q$ | 5, Teorema 2.10 b - De Morgan |
| 7 | $\sim q$ | 6, Teorema 2.8 c - Simplificação |

Método Indireto

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $p \vee q \rightarrow r \wedge s$ | $H_{1}$ |
| 2 | $r \wedge s \rightarrow s$ | $H_{2}$ |
| 3 | $\sim s$ | $H_{3}$ |
| 4 | $q$ | $H_{4}$ negação da tese |
| 5 | $p \vee q$ | 4, Teorema 2.8 b - Adição |
| 6 | $r \wedge s$ | 1,5, Teorema 2.8 e - Modus Ponens |
| 7 | $s$ | 4, Teorema 2.8 c - Simplificação |

75. (FM-2000) Mostre pelo método direto ou indireto as seguintes tautologias.

| a) H1: pv(q $\wedge$ r) | b) H1: (p $\vee q) \rightarrow r \wedge s$ |
| :--: | :--: |
| H2: $\mathrm{p} \vee \mathrm{q} \rightarrow \mathrm{s}$ | H2: $\mathrm{r} \wedge \mathrm{s} \rightarrow \mathrm{s}$ |
| T: $\mathrm{p} \vee \mathrm{s}$ | H3: $\sim \mathrm{s}$ |
|  | T: $\sim \mathrm{q}$ |

# Solução: 

a)

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $p \vee(q \wedge r)$ | $H_{1}$ |
| 2 | $p \vee q \rightarrow s$ | $H_{2}$ |
| 3 | $(p \vee q) \wedge(p \vee r)$ | 1, Teorema 2.11 d - Distributiva |
| 4 | $(p \vee q)$ | 3, Teorema 2.8 c - Simplificação |
| 5 | $s$ | 2, 4, Teorema 2.8 e - Modus Ponens |
| 6 | $p \vee s$ | 5, Teorema 2.8 b - Adição |

b)

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $(p \vee q) \rightarrow(r \wedge s)$ | $H_{1}$ |
| 2 | $r \wedge s \rightarrow s$ | $H_{2}$ |
| 3 | $\sim s$ | $H_{3}$ |
| 4 | $p \vee q \rightarrow s$ | 1,2 Exemplo 2.18 - Transitiva |
| 5 | $\sim(p \vee q)$ | 3,4, Teorema 2.8 f - Modus Tolles |
| 6 | $\sim p \wedge \sim q$ | 5, Teorema 2.10 b - De Morgan |
| 7 | $\sim q$ | 6, Teorema 2.8 c - Simplificação |

Outra solução:

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $(p \vee q) \rightarrow r \wedge s$ | $H_{1}$ |
| 2 | $r \wedge s \rightarrow s$ | $H_{2}$ |
| 3 | $\sim s$ | $H_{3}$ |
| 4 | $\sim(r \wedge s)$ | 2,3, Teorema 2.8 f - Modus Tolles |
| 5 | $\sim(p \vee q)$ | 1,4,Teorema 2.8 f - Modus Tolles |
| 6 | $\sim p \wedge \sim q$ | 5, Teorema 2.10 b - De Morgan |
| 7 | $\sim q$ | 6, Teorema 2.8 c - Simplificação |

Método Indireto

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $p \vee q \rightarrow r \wedge s$ | $H_{1}$ |
| 2 | $r \wedge s \rightarrow s$ | $H_{2}$ |
| 3 | $\sim s$ | $H_{3}$ |
| 4 | $q$ | $H_{4}$ negação da tese |
| 5 | $p \vee q$ | 4, Teorema 2.8 b - Adição |
| 6 | $r \wedge s$ | 1,5, Teorema 2.8 e - Modus Ponens |
| 7 | $s$ | 4, Teorema 2.8 c - Simplificação |
| 8 | $s \wedge \sim s$ | 3,7 conjunção |

76. (FM-2000) Mostre pelo método direto ou indireto as seguintes tautologias.

| a) H1: $\mathrm{p} \vee \mathrm{q} \rightarrow \mathrm{r}$ | b) H1: $\mathrm{s} \rightarrow \mathrm{p} \wedge \mathrm{q}$ |
| :-- | :-- |
| H2: $\mathrm{s} \rightarrow \mathrm{p} \wedge \mathrm{u}$ | H2: $\sim \mathrm{s} \rightarrow \mathrm{p}$ |
| H3: $\mathrm{q} \vee \mathrm{s}$ | H3: $\sim \mathrm{p}$ |

# Solução: 

a) Método Indireto

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $(p \vee q) \rightarrow r$ | $H_{1}$ |
| 2 | $s \rightarrow(p \wedge u)$ | $H_{2}$ |
| 3 | $q \vee s$ | $H_{3}$ |
| 4 | $\neg r$ | $H_{4}$ negação da tese |
| 5 | $\neg(p \vee q)$ | 1,4, Teorema 2.8 f-Modus Tolles |
| 6 | $\neg p \wedge \neg q$ | 5, Teorema 2.10 b-De Morgan |
| 7 | $\neg q$ | 6, Teorema 2.8 c - Simplificação |
| 8 | $s$ | 7,2, Teorema 2.8 d - Silogismo disjuntivo |
| 9 | $p \wedge u$ | 2, Teorema 2.8 e - Modus Ponens |
| 10 | $p$ | 9, Teorema 2.8 c - Simplificação |
| 11 | $\neg p$ | 6, Teorema 2.11 b - Idempotência |
| 12 | $p \wedge \neg p$ | 1011 conjunção |

b)Método Direto

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $s \rightarrow(p \wedge q)$ | $H_{1}$ |
| 2 | $\neg s \rightarrow p$ | $H_{2}$ |
| 3 | $\neg p$ | $H_{3}$ |
| 4 | $s$ | 2,3, Teorema 2.8 f - Modus Tolles |
| 5 | $p \wedge q$ | 1,4, Teorema 2.8 e - Modus Ponens |
| 6 | $q$ | 5, Teorema 2.8 c - Simplificação |

77. (FM-1999) Demonstre pelo método dedutivo as seguintes tautologias:
a) $(\mathrm{p} \wedge \mathrm{q}) \vee \neg \mathrm{p} \Leftrightarrow(\neg \mathrm{q} \rightarrow \neg \mathrm{p})$.
b) $(\mathrm{r} \vee \mathrm{s}) \vee \neg \mathrm{s} \Leftrightarrow \mathrm{s}$.

## Solução:

a) Vamos demonstrar que $(p \wedge q) \vee \neg p \leftrightarrow(\neg q \rightarrow \neg p)$.é uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $(p \wedge q) \vee \neg p /-(\neg q \rightarrow \neg p)$ e $(\neg q \rightarrow \neg p) /-(p \wedge q) . \vee \neg p$ Vejamos o primeiro argumento:

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $(p \wedge q) \vee \neg p$ | $H_{1}$ |
| 2 | $\neg p \vee(p \wedge q)$ | 1, Teorema 2.11 a - Comutativa |
| 3 | $(\neg p \vee p) \wedge(\neg p \vee q)$ | 2, Teorema 2.11 d - Distributiva |
| 4 | $t \wedge(\neg p \vee q)$ | 3, Teorema 2.12 j - Tautologia <br> Teorema 2.13 - Substituição |
| 5 | $\neg p \vee q$ | 4, Teorema 2.11a - Comutativa <br> Teorema 2.12 c - Tautologia |
| 6 | $q \vee \neg p$ | 5, Teorema 2.11 a - Comutativa |
| 7 | $\neg q \rightarrow \neg p$ | 6, Teorema 2.9 b - Condicional |

Para mostrar o segundo argumento utilizamos o mesmo processo de baixo para cima pois foram utilizadas somente equivalências lógicas.

b) Vamos demonstrar que. $(r \vee s) \vee \sim s \leftrightarrow s$ é uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $(r \vee s) \vee \sim s \rightarrow s e$ $s \rightarrow(r \vee s) \vee \sim s$ Vejamos o primeiro argumento

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $(r \vee s) \vee \sim s$ | $H_{1}$ |
| 2 | $r \vee(s \vee \sim s)$ | 1, Teorema 2.11 a - Comutativa |
| 3 | $r \vee t$ | 2, Teorema 2.12 j - Tautologia <br> Teorema 2.13 - Substituição |
| 4 | $t$ | 3, Teorema 2.12 d - Tautologia |
| 5 | $s \wedge s \vee t$ | 4, Teorema 2.12 d - Tautologia |
| 6 | $s \wedge t$ | 5, Teorema 2.12 d - Tautologia <br> Teorema 2.13 - Substituição |
| 7 | $s$ | 6, Teorema 2.12 c - Tautologia |

Para mostrar o segundo argumento utilizamos o mesmo processo de baixo para cima pois foram utilizadas somente equivalências lógicas.
78. (FM-1999) Demonstre pelo método dedutivo as seguintes tautologias:
a) $\mathrm{p} \vee(\mathrm{p} \wedge \mathrm{q}) \Leftrightarrow \mathrm{p}$.
b) $[(\mathrm{p} \rightarrow \mathrm{q}) \vee(\mathrm{p} \rightarrow \mathrm{r}) \Leftrightarrow[\mathrm{p} \rightarrow(\mathrm{q} \vee \mathrm{r})]$.

# Solução: 

a) Vamos demonstrar que. $p \vee(p \wedge q) \leftrightarrow p$ é uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $p \vee(p \wedge q) \rightarrow p$ e $p \rightarrow[p \vee(p \wedge q)$. Vejamos o primeiro argumento

| Ordem | Proposição | Justificativa |
| :--: | :-- | :-- |
| 1 | $p \vee(p \wedge q)$ | $H_{1}$ |
| 2 | $(p \vee p) \wedge(p \vee q)$ | 1, Teorema 2.11 d - Distributiva |
| 3 | $p \wedge q \vee p$ | 2, Teorema 2.11 b - Idempotência |
| 4 | $P$ | 3, Teorema 2.8 c - Simplificação |

ii) Para mostrar o segundo argumento utilizamos a tabela abaixo.

| Ordem | Proposição | Justificativa |
| :-- | :-- | :-- |
| 1 | $P$ | $H_{1}$ |
| 2 | $p \vee(p \wedge q)$ | 1, Teorema 2.8 b - Adição |

b) Vamos demonstrar que. $[(p \rightarrow q) \vee(p \rightarrow r) \leftrightarrow[p \rightarrow(q \vee r)]$. é uma tautologia utilizando o método dedutivo. Para isto devemos mostrar a validade dos argumentos $[(p \rightarrow q) \vee(p \rightarrow r)[p \rightarrow(q \vee r)] . e[p \rightarrow(q \vee r)] \rightarrow[(p \rightarrow q) \vee(p \rightarrow r)$. Vejamos o primeiro argumento

| Ordem | Proposição | Justificativa |
| :--: | :--: | :-- |
| 1 | $[(p \rightarrow q) \vee(p \rightarrow r)$ | $H_{1}$ |
| 2 | $(\sim p \vee q) \vee(\sim p \vee r)$ | 1,Teorema 2.9 a - Condicional <br> Teorema 2.13 - Substituição |
| 3 | $(\sim p \vee \sim p) \vee(q \vee r)$ | 2, Teorma 2.11 a - Comutativa <br> Teorema 2.13 - Substituição |
| 4 | $\sim p \vee(q \vee r)$ | 3, Teorema 2.11 b - Idempotência <br> Teorema 2.13 - Substituição |
| 5 | $p \rightarrow(q \vee r)$ | 4, Teorema 2.9 a - Condicional |

Para mostrar o segundo argumento utilizamos o mesmo processo de baixo para cima pois foram utilizadas somente equivalências lógicas.
79. Considere as seguintes inferências:

$$
\begin{array}{ll}
\mathrm{H}_{1}(\mathrm{P} \vee \mathrm{Q}) \wedge \mathrm{R} & \mathrm{~B}: \mathrm{H}_{1} \mathrm{P} \rightarrow \mathrm{R} \\
\mathrm{H}_{2}-\mathrm{P} & \mathrm{H}_{2} \mathrm{Q} \rightarrow-\mathrm{r} \\
\mathrm{~T}: \mathrm{Q} & \mathrm{H}_{3} \mathrm{Q} \\
& \mathrm{~T}:-\mathrm{P}
\end{array}
$$

Nos itens abaixo, são apresentados algumas apresentações de A e B . Em cada uma delas, descreva passo a passo, quais equivalências lógicas e /ou regras de inferência foram usadas, especificando também a quais linhas as regras fazem referência (Veja o exemplo dado)
a) Demonstração direta de A

| 1 | $(\mathrm{P} \vee \mathrm{Q}) \wedge \mathrm{R}$ |  |
| :-- | :-- | :-- |
| 2 | $-\mathrm{P}$ |  |
| 3 | $\mathrm{P} \vee \mathrm{Q}$ |  |
| 4 | Q |  |

b) Demonstração direta de A

| 1 | $(\mathrm{P} \vee \mathrm{Q}) \wedge \mathrm{R}$ |  |
| :-- | :-- | :-- |
| 2 | $-\mathrm{P}$ |  |
| 3 | $(\mathrm{P} \wedge \mathrm{R}) \vee(\mathrm{Q} \wedge \mathrm{R})$ |  |
| 4 | $-\mathrm{P} \vee-\mathrm{R}$ |  |
| 5 | $-(\mathrm{P} \wedge \mathrm{R})$ |  |
| 6 | $\mathrm{Q} \wedge \mathrm{R}$ |  |
| 7 | Q |  |

c) Demonstração indireta de A

| 1 | $(\mathrm{P} \vee \mathrm{Q}) \wedge \mathrm{R}$ |  |
| :-- | :-- | :-- |
| 2 | $-\mathrm{P}$ |  |
| 3 | $-\mathrm{Q}$ |  |
| 4 | $\mathrm{P} \vee \mathrm{Q}$ |  |
| 5 | P |  |
| 6 | $\mathrm{P} \wedge-\mathrm{P}$ |  |

d) Demonstração direta de B

| 1 | $\mathrm{P} \rightarrow \mathrm{R}$ |  |
| :-- | :-- | :-- |
| 2 | $\mathrm{Q} \rightarrow-\mathrm{R}$ |  |
| 3 | Q |  |
| 4 | $\mathrm{R} \rightarrow-\mathrm{Q}$ |  |
| 5 | $\mathrm{P} \rightarrow-\mathrm{Q}$ |  |
| 6 | $-\mathrm{P}$ |  |

e) Demonstração direta de B

| 1 | $\mathrm{P} \rightarrow \mathrm{R}$ |  |
| :-- | :-- | :-- |
| 2 | $\mathrm{Q} \rightarrow-\mathrm{R}$ |  |
| 3 | Q |  |
| 4 | $-\mathrm{P} \vee \mathrm{R}$ |  |
| 5 | $-\mathrm{Q} \vee-\mathrm{R}$ |  |
| 6 | $-\mathrm{R}$ |  |
| 7 | $-\mathrm{P}$ |  |

f) Demonstração indireta de B

| 1 | $\mathrm{P} \rightarrow \mathrm{R}$ |  |
| :-- | :-- | :-- |
| 2 | $\mathrm{Q} \rightarrow-\mathrm{R}$ |  |
| 3 | Q |  |
| 4 | P |  |
| 5 | R |  |
| 6 | $-\mathrm{Q}$ |  |
| 7 | $\mathrm{Q} \wedge-\mathrm{Q}$ |  |

80. Mostre que as inferências abaixo não são válidas, ou seja, a conjunção das hipóteses não implica a tese. Para mostrar isso é necessário achar um contra exemplo ,ou seja, achar exemplos de proposições que tornam as hipóteses verdadeiras e a tese falsa -veja o exemplo dado):

| a) $\mathrm{H}_{1} \mathrm{P} \vee \mathrm{R}$ | b) $\mathrm{H}_{1} \mathrm{P} \rightarrow \mathrm{Q}$ |
| :-- | :-- |
| $\mathrm{H}_{2} \mathrm{Q} \vee \mathrm{R}$ | $\mathrm{H}_{2} \mathrm{Q} \rightarrow \mathrm{R}$ |
| $\mathrm{T}: \mathrm{P} \vee \mathrm{Q}$ | $\mathrm{T}: \mathrm{P} \rightarrow \mathrm{Q}$ |
| c) $\mathrm{H}_{1} \mathrm{P} \rightarrow \mathrm{Q}$ | d) $\mathrm{H}_{1} \mathrm{P} \wedge \mathrm{Q}$ |
| $\mathrm{H}_{2} \sim \mathrm{P} \rightarrow \mathrm{R}$ | $\mathrm{H}_{2} \mathrm{R} \vee(\mathrm{~S} \rightarrow \mathrm{P})$ |
| $\mathrm{H}_{3} \sim \mathrm{Q}$ | $\mathrm{H}_{3} \sim \mathrm{R}$ |
| $\mathrm{T}: \mathrm{R} \rightarrow \mathrm{Q}$ | $\mathrm{T}: \mathrm{S}$ |

81. Leia o trecho abaixo e responda as questões apresentadas.
"Certa vez um homem caminhava em uma praia com um único pensamento: entender o que era lógica! Depois de muito caminhar, encontrou um amigo que se mostrou interessado em fazer com que o outro entendesse tal dádiva do pensamento humano. Colocou-se então a explicar...

- Você tem aquário em casa?
- Sim.
- Então você gosta de peixe!
- Claro.
- Se você gosta de peixe, deve gostar de sereia, que é metade peixe!
- É gosto.
- Mas gostando de sereia você gosta de mulher, pois sereia tem metade peixe e a outra metade mulher!
- Tem razão!
- Pois então, como você gosta de mulher, você é homem.
- É verdade, eu sou homem.
- Viu que legal, isto é lógica.

O homem saiu satisfeito com a explicação do amigo e louco para mostrar a alguém o que havia aprendido. Até que encontrou um outro homem também caminhando pela praia e perguntou:

- Você tem aquário em casa?

O homem respondeu:

- Não, não tenho.
- Então você não é homem!

E os dois se atacaram..."
Responda: No trecho em que o homem tenta explicar o que é lógica, faz-se uso de uma técnica dedutiva. Qual é? Por quê?
Porque a conclusão de que não ter aquário em casa implica não ser homem é falsa? (Explique usando artifícios do cálculo proposicional e das técnicas dedutivas).
82. Considere a afirmação:

Em um triângulo cujos lados medem a, b, c com a $\geq b \geq, c$, sempre temos $c+b>a$ " (Desigualdade triangular)
Desta forma analise a proposição abaixo, bem como a prova dada:
Proposição: "Dados dois pontos x e y distintos e não colineares com o centro em uma circunferência de raio r e centro $O$, temos que a distância entre $x$ e $y(d(x, y))$ é sempre menor que $2 r$."
Prova: De fato, se a distância entre $x$ e y fosse maior que $2 r$ (já que igual não pode ser, uma vez que os pontos não são colineares), teríamos:
$d(x, O)+d(y, O)>d(x, y)$
$r+r>d(x, y)>2 r$
$2 r>2 r$
Desta forma segue que a distância entre dois pontos distintos não colineares com o centro em uma circunferência é sempre menor do que o diâmetro da mesma.
Qual a técnica dedutiva usada neste caso? Por que?
83. Numa acareação da CPI do "pão de queijo", as seguintes informações ocorrem:
a) A diz que $B$ mente.
b) B diz que C mente.
c) C diz que A e B mentem. Se o conjunto de sentenças não é contraditório, quem está falando a verdade?
84. Legitime o argumento: "Se eu não especifico as condições iniciais, meu programa não roda. Se eu cometo 'loop infinito', meu programa não termina. Se o programa não roda ou se ele não termina, então o programa falha. Log se o programa não falha, então eu especifiquei as condições iniciais e não cometi 'loop'.
85. Assuma que "Zé é uma menina" e que "Zé tem dez anos" são sentenças falsas. Quais das seguintes são válidas?
a) Se Zé tem dez anos então Zé é menina.

b) Zé tem dez anos se e somente se é menina.
c) Zé não é menina com dez anos.
86. Suponha que "Zé não é baixo" seja falso e que assuma válidas as seguintes sentenças: "Zé ou Maria têm dez anos" e "se Maria tem dez anos então Zé não é baixo." Quais das sentenças abaixo são verdadeiras?
a) Zé não é baixo.
b) Maria tem dez anos.
c) Zé tem dez anos.
d) Ou Zé ou Maria não tem dez anos.
87. Denote por I: "uma dada matriz é invertível" e por D: "seu determinante é diferente de zero". Considerando válida a proposição $\mathrm{I} \Rightarrow \mathrm{D}$, quais da sentenças abaixo são conseqüências da asserção feita? (Não é necessário conhecimento de Álgebra Linear e observe a posição do para)
a) "para uma matriz Ter inversa basta que seu determinante seja nulo."
b) "para s3eu determinante ser não nulo 'é suficiente que a matriz seja invertível."
c) "para seu determinante ser nulo é necessário que a matriz seja invertível."
d) "uma matriz tem inversa se e apenas se seu determinante é não nulo."
e) "uma matriz tem determinante zero se ela não é invertível."
88. Em cálculo, a seguinte asserção vale: "uma função diferenciável é contínua" .Análogo ao exercício anterior, quais das sentenças seguem da asserção feita? (não é necessário conhecimento de cálculo)
a) "uma função é diferenciável apenas se ela é contínua"
b) "uma função é contínua apenas se ela é diferenciável"
c) "ser diferenciável é condição necessária para que seja contínua"
d) "ser diferenciável é condição suficiente para que seja contínua"
e) "a função é diferenciável se, e somente se é contínua"

# Quantificadores 

89. a) O que é uma sentença aberta?
b) Como transformar uma sentença aberta em proposição?
c) Quais os quantificadores existentes?
d) Qual a negação do quantificador existencial?
e) Qual a negação do quantificador universal?
90. Apresente a definição de limite utilizando quantificadores e encontre a negação.
91. Analise o significado lógico das seguintes frases do cotidiano:
a) Eu não fiz nada.
b) Eu não entendi nada.
c) Eu não vi ninguém.
92. Apresente a negação de $(\exists!x)(\mathrm{p}(\mathrm{x}))$.
93. Demonstre as seguintes propriedades de quantificadores
a) $(\forall \mathrm{x})(\mathrm{p}(\mathrm{x})) \Rightarrow \mathrm{p}(\mathrm{b})$
b) $[(\forall \mathrm{x})(\mathrm{p}(\mathrm{x})) \vee(\forall \mathrm{x})(\mathrm{q}(\mathrm{x}))] \Rightarrow(\forall \mathrm{x})(\mathrm{p}(\mathrm{x}) \vee \mathrm{q}(\mathrm{x}))$.
c) $(\forall \mathrm{x})(\mathrm{p}(\mathrm{x})) \Rightarrow(\exists \mathrm{x})(\mathrm{p}(\mathrm{x}))$
d) $(\exists \mathrm{x})(\mathrm{p}(\mathrm{x}) \wedge \mathrm{q}(\mathrm{x})) \Rightarrow[(\exists \mathrm{x})(\mathrm{p}(\mathrm{x})) \wedge(\exists \mathrm{x})(\mathrm{q}(\mathrm{x}))]$
e) $(\exists \mathrm{x})(\forall \mathrm{y})(\mathrm{p}(\mathrm{x}, \mathrm{y})) \Rightarrow(\forall \mathrm{y})(\exists \mathrm{x})(\mathrm{p}(\mathrm{x}, \mathrm{y}))$
f) $(\forall \mathrm{x})(\mathrm{p}(\mathrm{x}) \sim \mathrm{q}(\mathrm{x})) \Leftrightarrow[(\forall \mathrm{x})(\mathrm{p}(\mathrm{x})) \wedge(\forall \mathrm{x})(\mathrm{q}(\mathrm{x}))]$
g) $[(\exists \mathrm{x})(\mathrm{p}(\mathrm{x})) \vee(\exists \mathrm{x})(\mathrm{q}(\mathrm{x}))] \Leftrightarrow(\exists \mathrm{x})(\mathrm{p}(\mathrm{x}) \sim \mathrm{q}(\mathrm{x}))$
h) $(\exists \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{x}, \mathrm{y})) \Leftrightarrow(\exists \mathrm{y})(\exists \mathrm{x})(\mathrm{p}(\mathrm{x}, \mathrm{y}))$
i) $\sim[(\exists \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{x}, \mathrm{y}))] \Leftrightarrow(\forall \mathrm{x})(\forall \mathrm{y})(\sim \mathrm{p}(\mathrm{x}, \mathrm{y}))$
j) $(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{p}(\mathrm{x}, \mathrm{y})) \Leftrightarrow(\forall \mathrm{y})(\forall \mathrm{x})(\mathrm{p}(\mathrm{x}, \mathrm{y}))$
k) $\sim[(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{x}, \mathrm{y}))] \Leftrightarrow(\exists \mathrm{x})(\forall \mathrm{y})(\sim \mathrm{p}(\mathrm{x}, \mathrm{y}))$
l) $\sim[(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{p}(\mathrm{x}, \mathrm{y}))] \Leftrightarrow(\exists \mathrm{x})(\exists \mathrm{y})(\sim \mathrm{p}(\mathrm{x}, \mathrm{y}))$
m) $\sim[(\exists \mathrm{x})(\forall \mathrm{y})(\mathrm{p}(\mathrm{x}, \mathrm{y}))] \Leftrightarrow(\forall \mathrm{x})(\exists \mathrm{y})(\sim \mathrm{p}(\mathrm{x}, \mathrm{y}))$
94. (FM-2005) Verifique a validade dos quantificadores no universo dos números reais.

a) $(\forall \mathrm{x})(\exists \mathrm{y})\left(\mathrm{x}^{2}-\mathrm{y}=3\right)$
b) $(\forall \mathrm{y})(\exists \mathrm{x})\left(\mathrm{x}^{2}-\mathrm{y}=3\right)$
c) $(\exists \mathrm{y})(\exists \mathrm{x})\left(\mathrm{x}^{2}-\mathrm{y}=3\right)$
95. (FM-2002) (MD-2003) (FM-1999) Verifique a validade dos quantificadores a seguir para a proposição no universo dos números reais: $\mathrm{x}^{2}+\mathrm{x}+1 \geq 0$.
a) $(\forall \mathrm{x})(\mathrm{p}(\mathrm{x}))$.
b) $(\forall \mathrm{x})(\sim \mathrm{p}(\mathrm{x}))$.
c) $(\exists \mathrm{x})(\mathrm{p}(\mathrm{x}))$.
d) $(\exists \mathrm{x})(\sim \mathrm{p}(\mathrm{x}))$.

# Solução: 

a) Falso, pois para $x=3,2 x^{2}-5 x+2 \neq 0$.
b) Falso, pois para $x=2,2 x^{2}-5 x+2=0$
c) Verdadeiro, pois quando $x=2,2 x^{2}-5 x+2=0$
d) Verdadeiro, pois se considerarmos $x=3$, temos $2 x^{2}-5 x+2=0$ então $(\exists x)(-p(x))$.
97. (FM-2002) Considere o universo de discurso como sendo os números inteiros e a proposição aberta $\mathrm{p}(\mathrm{x}, \mathrm{y}) \mathrm{xy}+\mathrm{x}=$ $3 x$. Determine o valor lógico das proposições abaixo justificando:
a) $(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{x}, \mathrm{y}))$.
b) $\sim[(\exists \mathrm{x})(\exists \mathrm{y})(\sim \mathrm{p}(\mathrm{x}, \mathrm{y}))]$.
98. (FM-2002) Considerando a proposição aberta $\mathrm{p}(\mathrm{a}, \mathrm{b}): \mathrm{a}^{4}=3+\mathrm{b}$, onde a assume valores em $\{0,1,-1,2,-2\}$ e b em $\{3,-2,13\}$. Determine o valor lógico das proposições abaixo, justificando:
a) $(\forall \mathrm{a})(\exists \mathrm{b})(\mathrm{p}(\mathrm{a}, \mathrm{b}))$
b) $\sim[(\forall \mathrm{b})(\exists \mathrm{a})(\sim \mathrm{p}(\mathrm{a}, \mathrm{b})]$
99. (FM-2001) Nas sentenças abertas $\mathrm{p}(\mathrm{x})$ abaixo, considere x como sendo um número real. Transforme $\mathrm{p}(\mathrm{x})$ em proposições verdadeiras, utilizando quantificadores. Justifique suas respostas.
a) $\mathrm{p}(\mathrm{x}):\left(\frac{\mathrm{x}^{4}-2 \mathrm{x}^{2}+1}{\mathrm{x}^{2}-1}=\mathrm{x}^{2}-1\right)$.
b) $\mathrm{p}(\mathrm{x}):\left(\sqrt{\mathrm{x}^{2}} \neq \mathrm{x} \vee \sqrt{\mathrm{x}^{2}} \neq-\mathrm{x}\right)$.
c) $\mathrm{p}(\mathrm{x}):\left(\mathrm{x}^{2}+1 \leq 0\right)$.
100. (FM-2001) a) Sendo $A=\{1,2,3\}$, determine o valor lógico de $(\exists x \in A)\left(x^{2}+x-6=0\right)$;
b) Sendo A um conjunto qualquer, determine a negação de $[(\forall x \in A)(p(x))] \wedge[(\exists x \in A)(q(x))]$.
101. (FM-2001) Sendo $A=\{3,5,7,9,11,13\}$, verifique o valor verdade das seguintes proposições, justificando a resposta:
a) $(\forall \mathrm{x} \in \mathrm{A})(\mathrm{x}$ é primo);
b) $(\forall \mathrm{x} \in \mathrm{A})(\mathrm{x}+3 \leq 9) \vee(\exists \mathrm{x} \in \mathrm{A})\left(\mathrm{x}^{2}+2=11\right)$.
102. (MD-2001) Considere, no universo dos números naturais, os seguintes predicados:

$$
\begin{array}{ll}
\mathrm{p}(\mathrm{x}): & \text { "x é par" } \\
\mathrm{s}(\mathrm{x}, \mathrm{y}): & \text { "y = x + 1" } \\
\mathrm{q}(\mathrm{x}, \mathrm{y}, \mathrm{z}): & \text { "x = } \mathrm{y}^{2}+\mathrm{z}^{2} \text { " }
\end{array}
$$

a) Dadas as proposições

$$
(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{s}(\mathrm{x}, \mathrm{y}) \rightarrow \mathrm{p}(\mathrm{x}) \vee \mathrm{p}(\mathrm{y}))
$$

$(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{y}) \wedge \mathrm{s}(\mathrm{x}, \mathrm{y}))$
determine seus valores-verdade e expresse as respectivas negações;
b) Escreva em linguagem lógica, usando quantificadores e os predicados acima, a sentença "Todo número natural ímpar é soma de dois quadrados" (sugestão: escreva, antes, o predicado "x é soma de dois quadrados").

103. (MD-2001) Sendo $\mathrm{A}=\{1,2,3,4\}$, determinar o valor lógico da proposição

$$
(\exists \mathrm{x} \in \mathrm{~A})\left(2 \mathrm{x}^{2}+\mathrm{x}=15\right)
$$

104. (FM-2000) Responda as questões a seguir justificando sua resposta.
a) A proposição $\left(\forall \mathrm{x} \in \mathrm{IR}\right)\left[\mathrm{x}^{2}+1=(\mathrm{x}+1)^{2}\right]$ é verdadeira?
b) A proposição $\left(\forall \mathrm{x} \in \mathrm{IR}\right)\left(\mathrm{x}^{2}>0\right)$ é verdadeira?
c) A proposição $\left(\exists \mathrm{x} \in \mathrm{IR}\right)\left(\mathrm{x}^{2}+2 \mathrm{x}+1<0\right)$ é verdadeira?
d) Quantifique a expressão $5 . \mathrm{a}+4 \geq 11$ de forma a obter uma sentença verdadeira no universo dos números reais..
105. (FM-1999) Considere o conjunto universo $U=\{1,2,3\}$. Verifique quais das frases abaixo são verdadeiras e quais são falsas, justifique sua resposta.
a) $(\forall \mathrm{x} \in \mathrm{U})(\exists \mathrm{y} \in \mathrm{U})$ tal que $\mathrm{x}^{2}<\mathrm{y}+1$.
b) $(\forall \mathrm{x} \in \mathrm{U}),(\exists \mathrm{x} \in \mathrm{U})$ tal que $\mathrm{x}^{2}+\mathrm{y}^{2}<12$.
c) $(\forall \mathrm{z} \in \mathrm{U}),(\exists \mathrm{x} \in \mathrm{U}),(\exists \mathrm{y} \in \mathrm{U})$, tal que $\mathrm{x}^{2}+\mathrm{y}^{2}<\mathrm{z}^{2}$.
106. Escreva cada frase abaixo em linguagem lógica, usando quantificadores:

Universo $=$ seres humanos
(exemplo) Quem com ferro fere com ferro será ferido
solução: sejam os predicados:
$p(x):$ " $x$ fere com ferro"
$q(x):$ " $x$ é ferido com ferro"
a frase fica $(\forall x)(p(x) \rightarrow q(x))$
a) Todo brasileiro é técnico da seleção.
b) Há brasileiros que já viram a neve, mas não há finlandeses que nunca a viram.
c) Todo ser humano ou é do hemisfério sul ou do hemisfério norte.
d) Existe um ser humano que mora na lua.
e) Quem não arrisca não petisca.

Universo $=$ números naturais (nesse item, descreva em linguagem lógica também os predicados, por exemplo um predicado do tipo "x é produto de dois números naturais" é descrito como $(\exists \mathrm{y})(\exists \mathrm{z})(\mathrm{x}=\mathrm{y} . \mathrm{z})$
f) Todo número natural é soma de dois quadrados.
g) Nenhum número ímpar é divisível por dois.
h) Se a soma de dois números é par, então um dos números também é par.
i) O quadrado de um número natural é um número natural.
j) A média de um número natural ainda é um número natural.
107. Considere, no universo dos números naturais, os seguintes predicados:
$\mathrm{P}(\mathrm{x}): \mathrm{x}$ é par
$\mathrm{Q}(\mathrm{x}, \mathrm{y}): \mathrm{x}=2 \mathrm{y}$
$\mathrm{R}(\mathrm{x}, \mathrm{y}, \mathrm{z}): \mathrm{z}=\mathrm{x}+\mathrm{y}$
$\mathrm{S}(\mathrm{x}, \mathrm{y}): \mathrm{y}=\mathrm{x}+1$
Escreva as proposição abaixo em linguagem usual (português).
a) $(\forall \mathrm{x}) \mathrm{P}(\mathrm{x})$
b) $(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{S}(\mathrm{x}, \mathrm{y}))$
c) $(\forall \mathrm{x})(\forall \mathrm{y})(\exists \mathrm{z})(\mathrm{R}(\mathrm{x}, \mathrm{y}, \mathrm{z})$
d) $(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{S}(\mathrm{x}, \mathrm{y}) \rightarrow(\mathrm{P}(\mathrm{x}) \vee \mathrm{P}(\mathrm{y}))$
e) $(\forall \mathrm{y})(\exists \mathrm{x})(\mathrm{Q}(\mathrm{x}, \mathrm{y}))$
f) $(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{Q}(\mathrm{x}, \mathrm{y}) \rightarrow \mathrm{P}(\mathrm{x}))$
108. Determine o valor verdade das proposições do exercício 106 (somente aquelas referentes ao universo dos naturais), do exercício 107 e das proposições abaixo (cujo universo é o dos números inteiros).
a) $(\forall \mathrm{x})(\forall \mathrm{y})(\forall \mathrm{z})(\exists \mathrm{t})(\mathrm{x} . \mathrm{t}=\mathrm{y} . \mathrm{z})$
b) $(\forall \mathrm{x})(\exists \mathrm{y})(\exists \mathrm{z})(\exists \mathrm{t})\left(\mathrm{x}=\mathrm{y}^{2}+\mathrm{z}^{2} \mathrm{t}^{2}\right)$
c) $(\exists \mathrm{x})(\forall \mathrm{y})(\exists \mathrm{z})(\mathrm{y} \mathrm{z}=\mathrm{x})$
d) $(\exists \mathrm{x})(\forall \mathrm{y})(\exists \mathrm{z})(\mathrm{y}-\mathrm{z}=\mathrm{x})$
e) $(\forall \mathrm{x})(\exists \mathrm{y})(\exists \mathrm{z})(\mathrm{x}=(\mathrm{y}+\mathrm{z}) / 2)$
f) $(\forall \mathrm{y})(\exists!x)\left(\mathrm{x}=\mathrm{y}^{2}\right)$
g) $(\forall \mathrm{x})(\exists!\mathrm{y})(\mathrm{y}+1=\mathrm{x})$
h) $(\forall \mathrm{x})[(\exists \mathrm{y})(\mathrm{x}=2 \mathrm{y}) \rightarrow(\mathrm{x}+1$ é ímpar $)]$
109. Expresse a negação de cada uma das proposições do exercício 108. Nos itens f e g tente negar antes uma proposição do tipo $(\exists!x)(\mathrm{P}(\mathrm{x}))$, lembrando que $(\exists!x)(\mathrm{P}(\mathrm{x}))=(\exists \mathrm{x})[(\mathrm{P}(\mathrm{x})) \wedge(\forall \mathrm{y})(\neg \mathrm{P}(\mathrm{x})) \vee(\mathrm{x}=\mathrm{y}))]$.

110. Verifique se valem as seguintes afirmações (prove as implicações que valem, e dê contra- exemplo para as implicações que não valem)
$(\exists x)(P(x) \rightarrow Q(x)) \Leftrightarrow(\exists x)(P(x)) \rightarrow(\exists x)(Q(x))$
$(\forall x)(P(x) \rightarrow Q(x)) \Leftrightarrow(\forall x)(P(x)) \rightarrow(\forall x)(Q(x))$
(dica: em cada afirmação há uma implicação que vale e outra que não vale)
111. Sejam os predicados no universo dos inteiros: $\mathrm{N}(\mathrm{x})$ : x é inteiro não negativo, $\mathrm{E}(\mathrm{x})$ : x é par, $\mathrm{I}(\mathrm{x})$ : x é impar, $\mathrm{P}(\mathrm{x})$ : x é primo.
a) Escreva as proposições abaixo simbolicamente :
b) Existe um inteiro impar.
c) Todo inteiro é par ou ímpar.
d) Todo inteiro primo não é negativo.
e) O único par primo é 2 .
f) Existe um e apenas um par primo.
g) Nem todos primos são impares.
h) Se um inteiro não é ímpar, então ele é par.
112. Determine os valores (universo: inteiros)
a) $(\forall \mathrm{m})(\exists \mathrm{n})[2 \mathrm{n}=\mathrm{m}]$
b) $(\forall \mathrm{m})(\exists \mathrm{n})[2 \mathrm{~m}=\mathrm{n}]$
c) $(\forall \mathrm{m})(\exists \mathrm{n}) \sim[2 \mathrm{n}=\mathrm{m}]$
d) $(\exists \mathrm{n})(\forall \mathrm{m})(2 \mathrm{~m}=\mathrm{n})$
e) $(\exists \mathrm{n})(\forall \mathrm{m})(\mathrm{m}<\mathrm{n}+\mathrm{m})$
f) $(\exists \mathrm{n})(\forall \mathrm{m})(\mathrm{n}<\mathrm{n}+\mathrm{m})$
113. Determine quais das seguintes proposições são verdadeiras (universo: inteiros). Depois considere os reais como universo.
a) $(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{x} \mathrm{y}=0)$
b) $(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{x} \mathrm{y}=1)$
c) $(\exists \mathrm{x})(\forall \mathrm{y})(\mathrm{x} \mathrm{y}=1)$
d) $((\exists \mathrm{x})(\forall \mathrm{y})(\mathrm{x} \mathrm{y}=\mathrm{x})$
114. Considere os predicados: $S(x, y, z)$ : " $x+y=z$ ", $P(x, y, z)$ : " $x . y=z$ " e $L(x, y, z)$ : " $x<y$ "; e o universo do discurso o conjunto dos naturais. Exprima a frase usando predicados dados e determine i valor verdade:
a) Para todo $x$ e $y$,existe $z$ tal que $x+y=z .0$
b) Nenhum $x$ é menor do que 0 .
c) Existe elemento neutro na adição.
d) Existe um único elemento neutro na adição.
e) Para todo $x, x . y=y$ para todo $y$.
f) Existe um x tal que $\mathrm{x} . \mathrm{y}=\mathrm{y}$ para todo y .
115. Simule computacionalmente o valor verdade dos predicados:
a) $(\forall \mathrm{x}) \mathrm{P}(\mathrm{x})(\mathrm{P}(\mathrm{x})$ um vetor com entradas booleanas de comprimento 20)
b) $(\forall \mathrm{x})(\exists \mathrm{y}) \mathrm{P}(\mathrm{x})$ um "array"- matriz $10 \times 30$ com entradas boolenas, diagramos, $1 \leq \mathrm{x} \leq 10$ e $1 \leq \mathrm{y} \leq 30$.
116. Outra forma de quantificar é "existe um apenas um" elemento do discurso que torna o predicado P verdadeiro, denotado por $\exists!x \mathrm{P}(\mathrm{x})$. Tente expressa- lo em função dos outros conectivos e quantificadores.
117. Quando $(\forall \mathrm{x}) \mathrm{P}(\mathrm{x})$ falha, significa que existe um sujeito $\mathrm{x}_{0}$ tal que $\mathrm{P}\left(\mathrm{x}_{0}\right)$ não vale. Neste caso dizemos que $\mathrm{x}_{0}$ é um contra- exemplo das sentenças abaixo:
a) Todos os primos são ímpares: $(\forall \mathrm{x})(\mathrm{x}$ é primo $\Rightarrow \mathrm{x}$ é ímpar)
b) Todos inteiro é soma de dois quadrados.
c) Todos inteiros é soma de três quadrado.
118. Utilizando os predicados: a | b: "a divide b", a = b: "a igual a b", exiba o predicado $\mathrm{P}(\mathrm{x})$ : "x é primo" em notação lógica. Como fica sua negação sem usar o conectivo $\sim$ ?
119. Expresse a sentença "não existe o maior primo" (use P do exercício acima e o predicado $>$ : "maior que").
120. Denote por $T(a, b, c)$ o predicado " $a, b$, $c$ são lados de um triângulo retângulo. Enuncie o Teorema de Pitágoras.
121. Universo: inteiros. Para cada uma das afirmações abaixo, encontre um predicado P que torna a implicação falsa.
a) $(\forall \mathrm{x})(\exists!y) \mathrm{P}(\mathrm{x}, \mathrm{y}) \Rightarrow(\exists!y)(\forall y) \mathrm{P}(\mathrm{x}, \mathrm{y})$

b) $(\exists!y)(\forall y) P(x, y) \Rightarrow(\forall x)(\exists!y) P(x, y)$
122. Mostre que as afirmações não são válidas:
a) $(\exists x)[P(x) \Rightarrow Q(x)] \Leftrightarrow[(\exists x) P(x) \Rightarrow \exists x Q(x)]$
b) $(\forall x)[P(x) \Rightarrow Q(x)] \Leftrightarrow[(\forall x) P(x) \Rightarrow \forall x Q(x)]$
123. Legitime o argumento: "Todos os poetas são ou niilistas ou sonhadores. Afrânio é poeta. Mais ele não é niilista. Logo há sonhadores".(P: poeta, N: niilista, S: sonhador e A: Afrânio ).
124. Inferir: "Todos os gaúchos gostam de estórias .Todos os contadores de história são interessantes. O escritor Veríssimo é gaúcho. Logo, alguém é gaúcho e interessante".(G: gaúcho, C: contar estórias, I: ser interessante, V: Veríssemo).
125. Inferir: Todos os peixes vivem no mar. Acontece que Pluto é um animal. Pluto não vive no mar. Portanto, há animais que não são peixes.
126. Verifique se as conclusões estão corretas. Caso afirmativo tente justificar o argumento.
a) Premissas: (1) Todos os comunistas são ateus. (2) Bakunin é ateu. Conclusão: Bakunin é comunista.
b) Premissas: (2) Todos os comunistas são ateus (2) Bakunin é comunista. Conclusão: Bakunin é ateu.
c) Premissas: (1) Nenhum estudante é maníaco. (2) Todos os jovens são estudantes. Conclusão: Não existe um jovem maníaco. (obs.: a premissa 1 é equivalente a: Todos os estudantes não são maníacos.)
127. (FM-2002) Considerando a proposição aberta $p(a, b): a^{4}=3+b$, onde a assume valores em $\{0,1,-$ $1,2,-2\}$ e b em $\{3,-2,13\}$. Determine o valor lógico das proposições abaixo, justificando:
a) $(\forall a)(\exists b)(p(a, b))$
b) $\sim[(\forall b)(\exists a)(\sim p(a, b)]$
a) Falsa, pois para $x=0$ não temos a proposição verdadeira independente do valor de $b$.
b) Verdadeira, pois $(\forall b)(\exists a)(\sim p(a, b)$ é verdadeira Logo sua negação é falsa.
128. (FM-2002) Considere o universo de discurso como sendo os números inteiros e a proposição aberta $\mathrm{p}(\mathrm{x}, \mathrm{y}): \mathrm{xy}+\mathrm{x}=3 \mathrm{x}$.Determine o valor lógico das proposições abaixo justificando:
a) $(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{x}, \mathrm{y}))$.
b) $\sim[(\exists x)(\exists y)(\sim p(x, y))]$.
a) Verdadeira pois para qualquer $x$ inteiro considere $y=2 \in Z$ tal que: $x .2+x=3 x$.
b) Falsa pois para $y=3$ e $x=1$ temos $x . y+x=1.3+1=4 \neq 3.1$
129. (FM-2002) Verifique a validade dos quantificadores a seguir para a proposição no universo dos números reais:

$$
x^{2}+x+1 \geq 0
$$

a) $(\forall x)(p(x))$.
b) $(\forall x)(\sim p(x))$.
c) $(\exists x)(p(x))$.
d) $(\exists x)(\sim p(x))$.
a) Verdadeiro, pois para todo $x$ existirá $p(x)$.Se este $x$ for pertencente aos números reais.
b) Falso, pois ele é a negação de $(\exists x)(p(x))$ que também é verdadeiro.
c) Verdadeiro, basta pegar $x=2$ e veremos que $x^{2}+x+1 \geq 0$.
d) Falso, pois ele é a negação de $(\forall x)(p(x))$ que também é verdade.
130. (MD-2001) Considere o conjunto universo $U=\{1,2,3\}$. Verifique se a proposição é verdadeira ou falsa, justificando sua resposta.

$$
\forall \mathrm{z} \in \mathrm{U}, \exists \mathrm{x} \in \mathrm{U}, \exists \mathrm{y} \in \mathrm{U}, \text { tal que, } \mathrm{x}^{2}+\mathrm{y}^{2}<2 \mathrm{z}^{2}
$$

Solução: A proposição é falsa pois para $\mathrm{z}=1$ temos

$$
\begin{aligned}
& \mathrm{x}=1 \wedge \mathrm{y}=1 \Rightarrow \mathrm{x}^{2}+\mathrm{y}^{2}=2 \cdot \mathrm{z}^{2} \\
& \mathrm{x}=1 \wedge \mathrm{y}=2,3 \Rightarrow \mathrm{x}^{2}+\mathrm{y}^{2}>2 \cdot \mathrm{z}^{2} \\
& \mathrm{x}=2 \wedge \mathrm{y}=1,2,3 \Rightarrow \mathrm{x}^{2}+\mathrm{y}^{2}>2 \cdot \mathrm{z}^{2} \\
& \mathrm{x}=3 \wedge \mathrm{y}=1,2,3 \Rightarrow \mathrm{x}^{2}+\mathrm{y}^{2}>2 \cdot \mathrm{z}^{2}
\end{aligned}
$$

131. (MD-2001) Sendo $A=\{1,2,3,4\}$, determinar o valor lógico da proposição

$$
(\exists \mathrm{x} \in \mathrm{~A})\left(2 \mathrm{x}^{2}+\mathrm{x}=15\right)
$$

Solução: É falsa, pois para

$$
\begin{aligned}
& \mathrm{x}=1, \text { temos } 2 \mathrm{x}^{2}+\mathrm{x}=3 \\
& \mathrm{x}=2, \text { temos } 2 \mathrm{x}^{2}+\mathrm{x}=10 \\
& \mathrm{x}=3, \text { temos } 2 \mathrm{x}^{2}+\mathrm{x}=21 \\
& \mathrm{x}=4, \text { temos } 2 \mathrm{x}^{2}+\mathrm{x}=36
\end{aligned}
$$

Logo, $(\forall \mathrm{x} \in \mathrm{A})\left(2 \mathrm{x}^{2}+\mathrm{x} \neq 15\right)$ é verdadeira.
Portanto, $(\exists \mathrm{x} \in \mathrm{A})\left(2 \mathrm{x}^{2}+\mathrm{x} \neq 15\right)=-(\forall \mathrm{x} \in \mathrm{A})\left(2 \mathrm{x}^{2}+\mathrm{x} \neq 15\right)$ é falsa.
132. (MD-2001) Considere, no universo dos números naturais, os seguintes predicados:
$\mathrm{p}(\mathrm{x}): \quad$ "x é par"
$\mathrm{s}(\mathrm{x}, \mathrm{y}): \quad " \mathrm{y}=\mathrm{x}+1 "$
$\mathrm{q}(\mathrm{x}, \mathrm{y}, \mathrm{z}): \quad " \mathrm{x}=\mathrm{y}^{2}-\mathrm{z}^{2} "$
a) Dadas as proposições
$(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{s}(\mathrm{x}, \mathrm{y}) \wedge \mathrm{p}(\mathrm{x}) \rightarrow \sim \mathrm{p}(\mathrm{y}))$
$(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{y}) \wedge \mathrm{s}(\mathrm{x}, \mathrm{y}))$
determine seus valores-verdade e expresse as respectivas negações;
b) Escreva em linguagem lógica, usando quantificadores e os predicados acima, a sentença "Todo número natural impar é diferença de dois quadrados"
[sugestão: escreva, antes, o predicado "x é diferença de dois quadrados"].
133. (MD-2001) Considere, no universo dos números naturais, os seguintes predicados:
$\mathrm{p}(\mathrm{x}): \quad$ "x é impar"
$\mathrm{s}(\mathrm{x}, \mathrm{y}): \quad " \mathrm{y}=\mathrm{x}+1 "$
$\mathrm{q}(\mathrm{x}, \mathrm{y}, \mathrm{z}): \quad " \mathrm{x}=\mathrm{y}^{2}+\mathrm{z}^{2} "$
c) Dadas as proposições
$(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{s}(\mathrm{x}, \mathrm{y}) \rightarrow \mathrm{p}(\mathrm{x}) \vee \mathrm{p}(\mathrm{y}))$
$(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{y}) \wedge \mathrm{s}(\mathrm{x}, \mathrm{y}))$
determine seus valores-verdade e expresse as respectivas negações;
d) Escreva em linguagem lógica, usando quantificadores e os predicados acima, a sentença "Todo número natural par é soma de dois quadrados"
[sugestão: escreva, antes, o predicado "x é soma de dois quadrados"].
134. (MD-2001) Considere, no universo dos números naturais, os seguintes predicados:
$\mathrm{p}(\mathrm{x}): \quad$ "x é par"
$\mathrm{s}(\mathrm{x}, \mathrm{y}): \quad " \mathrm{y}=\mathrm{x}+1 "$
$\mathrm{q}(\mathrm{x}, \mathrm{y}, \mathrm{z}): \quad " \mathrm{x}=\mathrm{y}^{2}+\mathrm{z}^{2} "$
e) Dadas as proposições
$(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{s}(\mathrm{x}, \mathrm{y}) \rightarrow \mathrm{p}(\mathrm{x}) \vee \mathrm{p}(\mathrm{y}))$
$(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{y}) \wedge \mathrm{s}(\mathrm{x}, \mathrm{y}))$
determine seus valores-verdade e expresse as respectivas negações;
f) Escreva em linguagem lógica, usando quantificadores e os predicados acima, a sentença "Todo número natural par é soma de dois quadrados"
[sugestão: escreva, antes, o predicado "x é soma de dois quadrados"].
135. (MD-2001) Considere, no universo dos números naturais, os seguintes predicados:
$\mathrm{p}(\mathrm{x}): \quad$ "x é impar"
$\mathrm{s}(\mathrm{x}, \mathrm{y}): \quad " \mathrm{y}=\mathrm{x}+1 "$
$\mathrm{q}(\mathrm{x}, \mathrm{y}, \mathrm{z}): \quad " \mathrm{x}=\mathrm{y}^{2}+\mathrm{z}^{2} "$
g) Dadas as proposições
$(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{s}(\mathrm{x}, \mathrm{y}) \rightarrow \mathrm{p}(\mathrm{x}) \vee \mathrm{p}(\mathrm{y}))$
$(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{y}) \wedge \mathrm{s}(\mathrm{x}, \mathrm{y}))$
determine seus valores-verdade e expresse as respectivas negações;
h) Escreva em linguagem lógica, usando quantificadores e os predicados acima, a sentença "Todo número natural impar é soma de dois quadrados"
[sugestão: escreva, antes, o predicado "x é soma de dois quadrados"].
136. (MD-2001) Considere, no universo dos números naturais, os seguintes predicados:
$\mathrm{p}(\mathrm{x}): \quad$ "x é par"
$\mathrm{s}(\mathrm{x}, \mathrm{y}): \quad " \mathrm{y}=\mathrm{x}+1 "$
$\mathrm{q}(\mathrm{x}, \mathrm{y}, \mathrm{z}): \quad " \mathrm{x}=\mathrm{y}^{2}+\mathrm{z}^{2} "$
i) Dadas as proposições
$(\forall \mathrm{x})(\forall \mathrm{y})(\mathrm{s}(\mathrm{x}, \mathrm{y}) \rightarrow \mathrm{p}(\mathrm{x}) \vee \mathrm{p}(\mathrm{y}))$

$$
(\forall \mathrm{x})(\exists \mathrm{y})(\mathrm{p}(\mathrm{y}) \wedge \mathrm{s}(\mathrm{x}, \mathrm{y}))
$$

determine seus valores-verdade e expresse as respectivas negações;
j) Escreva em linguagem lógica, usando quantificadores e os predicados acima, a sentença "Todo número natural impar é soma de dois quadrados"
[sugestão: escreva, antes, o predicado "x é soma de dois quadrados"].
137. (FM-2001) Sendo $A=\{3,5,7,9,11,13\}$, verifique o valor verdade das seguintes proposições, justificando a resposta:
a) $(\forall \mathrm{x} \in \mathrm{A})(\mathrm{x}$ é primo);
b) $(\forall \mathrm{x} \in \mathrm{A})(\mathrm{x}+3 \leq 9) \vee(\exists \mathrm{x} \in \mathrm{A})\left(\mathrm{x}^{2}+2=11\right)$.

# Solução: 

Seja $A=\{3,5,7,9,11,13\}$.
a) ( $\forall x$ e A) (x é primo) é uma proposição FALSA, basta considerar $x=9=3.3$ que, portanto, não é primo.
b) $(\forall x$ e A) $(x+3 \leq 9)$ é FALSA, pois para $x=7$, temos $x+3=10>9$. $(\exists x$ e A) $\left(x^{2}+2=11\right)$ é VERDADEIRA, pois para $x=3$, temos $x^{2}+2=11$. Portanto, a proposição dada pela disjunção destas duas é VERDADEIRA.
138. (FM-2001) a) Sendo $A=\{1,2,3\}$, determine o valor lógico de $(\exists \mathrm{x} \in \mathrm{A})\left(\mathrm{x}^{2}+\mathrm{x}-6=0\right)$;
b) Sendo A um conjunto qualquer, determine a negação de $[(\forall \mathrm{x} \in \mathrm{A})(\mathrm{p}(\mathrm{x}))] \wedge[(\exists \mathrm{x} \in \mathrm{A})(\mathrm{q}(\mathrm{x}))]$.

## Solução:

a) 0 valor lógico é verdadeiro, pois basta considerar $x=2$ e $A$ e $2^{2}+2-6=6-6=0$.
b) A negação é dada pela proposição

$$
-[((\forall \mathrm{x} \in \mathrm{~A})(\mathrm{p}(\mathrm{x}))] \wedge[(\exists \mathrm{x} \in \mathrm{~A})(\mathrm{q}(\mathrm{x}))]]
$$

Utilizando a regra de De Morgan (19 a) teremos:

$$
\left[-[(\forall \mathrm{x} \in \mathrm{~A})(\mathrm{p}(\mathrm{x}))]\right] \vee\left[-[(\exists \mathrm{x} \in \mathrm{~A})(\mathrm{q}(\mathrm{x})]\right]
$$

Por (27) teremos

$$
[(\exists \mathrm{x} \in \mathrm{~A})(\sim \mathrm{p}(\mathrm{x}))] \vee[(\forall \mathrm{x} \in \mathrm{~A})(\sim \mathrm{q}(\mathrm{x}))]
$$

139. (FM-2001) Nas sentenças abertas $\mathrm{p}(\mathrm{x})$ abaixo, considere x como sendo um número real. Transforme $\mathrm{p}(\mathrm{x})$ em proposições verdadeiras, utilizando quantificadores. Justifique suas respostas.
a) $\mathrm{p}(\mathrm{x}):\left(\frac{\mathrm{x}^{4}-2 \mathrm{x}^{2}+1}{\mathrm{x}^{2}-1}=\mathrm{x}^{2}-1\right)$,
b) $\mathrm{p}(\mathrm{x}):\left(\sqrt{\mathrm{x}^{2}} \neq \mathrm{x} \vee \sqrt{\mathrm{x}^{2}} \neq-\mathrm{x}\right)$,
c) $\mathrm{p}(\mathrm{x}):\left(\mathrm{x}^{2}+1 \leq 0\right)$.

## Solução:

a) $(\exists \mathrm{x})\left(\frac{\mathrm{x}^{4}-2 \mathrm{x}^{2}+1}{\mathrm{x}^{2}-1}=\mathrm{x}^{2}-1\right)$, pois se $x=0$, teremos a igualdade, mas se $x=1$ ou $x=-1$, o lado esquerdo não está definido.
b) $(\exists \mathrm{x})\left(\sqrt{\mathrm{x}^{2}} \neq \mathrm{x} \vee \sqrt{\mathrm{x}^{2}} \neq-\mathrm{x}\right)$, pois se $x=2$, temos $\sqrt{2^{2}}=2$, mas se $x=0 \sqrt{0^{2}}=0$ e $\sqrt{0}=-0$, portanto para 0 não vale.
c) $x^{2}+1>0$, pois para todo $x, x^{2}>0$ e assim $x^{2}+1>0$, logo $(\forall x)\left(x^{2}+1>0\right)$, ou seja, $(\forall x)(-p(x))$.
140. (FM-2000) Responda as questões a seguir justificando sua resposta.

Quantifique a expressão $5 . \mathrm{a}+4 \leq 11$ de forma a obter uma sentença verdadeira no universo dos números reais..
a) A proposição $(\forall \mathrm{x} \in \mathrm{IR})\left[\mathrm{x}^{2}+2 \mathrm{x}+1=(\mathrm{x}+1)^{2}\right]$ é verdadeira?
b) A proposição $(\forall \mathrm{x} \in \mathrm{IR})\left(\mathrm{x}^{2}+2 \mathrm{x}+1=0\right)$ é verdadeira?
c) A proposição $(\exists \mathrm{x} \in \mathrm{IR})\left(\mathrm{x}^{2}+2 \mathrm{x}+1>0\right)$ é verdadeira?

## Solução:

a) Verdadeira, pois $(x+1)^{2}=(x+1) \cdot(x+1)=x^{2}+2 x+1$.
b) Falsa, basta pegar $x=3$ então $x^{2}+2 x+1=16 \neq 0$.
c) Verdadeira, se fizermos $x=2$ temos $x^{2}+2 x+1=9>0$.

$$
(\exists x \in \mathrm{IR})(5 a+4 \leq 11) \text { pois a equação só se satisfaz com } a \leq \frac{6}{5}
$$

141. (FM-2000) Verifique o valor verdade das proposições a seguir, justificando sua resposta.
a) Dado $B=\left\{\frac{1}{n}\left[n \in Z^{*}\right\rangle(\forall x \in B)\left(x^{2}-1 \leq 0\right)\right.$
b) Dado $A=\{1,2,3\}(\exists x \in A)(\forall y \in A)(\forall z \in A)\left(x^{2}+y^{2}<2 z^{2}\right)$
$\sim\{\{\exists x\}[(\forall y)(p(x, y))]\} \equiv(\forall x)[(\exists y)(\sim p(x, y))]$
Solução:
a) Verdadeira pois $\left(\frac{1}{n}\right)^{2} n \in Z$, tal que $n \neq 0$ é menor que zero.
b) Falsa, pois para $y=1$ e $z=1$ não temos $x \in A$ tal que $x^{2}+y^{2}<2 z^{2}$.
142. (FM-2000) Responda as questões a seguir justificando sua resposta.

Quantifique a expressão $5 . \mathrm{a}+4 \geq 11$ de forma a obter uma sentença verdadeira no universo dos números reais..
a) A proposição $(\forall \mathrm{x} \in \mathrm{IR})\left[\mathrm{x}^{2}+1=(\mathrm{x}+1)^{2}\right]$ é verdadeira?
b) A proposição $\left(\forall \mathrm{x} \in \mathrm{IR}\right)\left(\mathrm{x}^{2}>0\right)$ é verdadeira?
c) A proposição $(\exists \mathrm{x} \in \mathrm{IR})\left(\mathrm{x}^{2}+2 \mathrm{x}+1<0\right)$ é verdadeira?

# Solução: 

a) Falsa, pois se pegarmos $x=1$ teremos $\left(x^{2}+1\right)=3 \neq 4=(x+1)^{2}$.
b) Falsa, pois para $x=0$ temos $x^{2}=0$ e não $x^{2}>0$.
c) Falsa, pois para qualquer $x \in I R$ temos $x^{2}+2 x+1>0$.

$$
(\exists a \in I R)(5 a+4 \geq 11) \text { pois a equação só se satisfaz com } a \geq \frac{6}{5}
$$

143. (FM-1999) Considere o conjunto universo $\mathrm{U}=\{1,2,3\}$. Verifique quais das frases abaixo são verdadeiras e quais são falsas, justificando sua resposta.
a) $\forall \mathrm{x} \in \mathrm{U}, \exists \mathrm{y} \in \mathrm{U}$, tal que $\mathrm{x}^{2}<\mathrm{y}+1$.
b) $\forall \mathrm{x} \in \mathrm{U}, \exists \mathrm{y} \in \mathrm{U}$, tal que $\mathrm{x}^{2}+\mathrm{y}^{2}<12$.
c) $\forall \mathrm{z} \in \mathrm{U}, \exists \mathrm{x} \in \mathrm{U}, \exists \mathrm{y} \in \mathrm{U}$, tal que $\mathrm{x}^{2}+\mathrm{y}^{2}<2 \mathrm{z}^{2}$.

Considere o conjunto universo $U=\{1,2,3\}$. Verifique quais das frases abaixo são verdadeiras e quais são falsas, justifique sua resposta.
a) $(\forall x \in U)(\exists y \in U)$ tal que $x^{2}<y+1$

Falsa pois se $x=3$ para qualquer $y \in U$ temos que $x^{2}>y+1$.
b) $(\forall x \in U),(\exists x \in U)$ tal que $x^{2}+y^{2}<12$.

Verdadeira pois para $x=1 \forall y \in U$ temos $x^{2}+y^{2}<12$.
Para $x=2$ e $y=1$ ou $y=2$ temos $x^{2}+y^{2}<12$
Para $x=3$ e $y=1$ temos $x^{2}+y^{2}<12$
c) $(\forall z \in U),(\exists x \in U),(\exists y \in U)$, tal que $x^{2}+y^{2}<z^{2}$.

Falsa pois para $z=1(\forall x \in U) e(\forall y \in U)$ temos $x^{2}+y^{2} \geq 2 z^{2}$
144. (FM-1999) Verifique a validade dos quantificadores a seguir para a proposição no universo dos números inteiros: $2 \mathrm{x}^{2}-5 \mathrm{x}+2=0$.
a) $(\forall \mathrm{x})(\mathrm{p}(\mathrm{x}))$
b) $(\forall \mathrm{x})(\sim \mathrm{p}(\mathrm{x}))$
c) $(\exists \mathrm{x})(\mathrm{p}(\mathrm{x}))$
d) $(\exists \mathrm{x})(\sim \mathrm{p}(\mathrm{x}))$

## Solução:

a) Falsa, pois se considerarmos $x=3$ veremos que a proposição não é satisfeita.
b) Falsa, basta considerar $x=-2$ que satisfaz a proposição.
c) Verdadeira pois é a negação de $(\forall x)(\sim p(x))$ que é falsa.
d) Verdadeira, pois é a negação de $(\forall x)(p(x))$ que é falsa.
145. (FM-1999) Verifique a validade dos quantificadores a seguir para a proposição no universo dos números reais: $\mathrm{x}^{2}+\mathrm{x}+1 \geq 0$.
a) $(\forall \mathrm{x})(\mathrm{p}(\mathrm{x}))$
b) $(\forall \mathrm{x})(\sim \mathrm{p}(\mathrm{x}))$
c) $(\exists \mathrm{x})(\mathrm{p}(\mathrm{x}))$

d) $(\exists x)(-p(x))$

# Solução: 

a) Verdadeiro, pois para todo $x$ real, $x^{2}+x+1=0$ não possui raiz real, e também nunca é negativo, $\log o x^{2}+x+1 \geq 0$.
b) Falso, pois é negação de $(\exists x)(p(x))$ que também é verdadeiro.
c) Verdadeiro, pois pelo item a) para todo $x$ real temos $x^{2}+x+1 \geq 0$, logo temos um em particular.
d) Falso, pois ele é a negação de $(1 / x)(p(x))$ que é verdade pelo item a).

## Princípio da Indução Finita

146. (FM-2005) Sabe-se que para somar dois vetores $\overrightarrow{\mathbf{u}}$ e $\overrightarrow{\mathbf{v}}$, toma-se um segmento orientado ( $\mathrm{A}, \mathrm{B}$ ) para representar $\overrightarrow{\mathbf{u}}$ e um segmento orientado (B,C) para representar $\overrightarrow{\mathbf{v}}$, e a soma de $\overrightarrow{\mathbf{u}}$ e $\overrightarrow{\mathbf{v}}$ é um novo vetor denotado por $\overrightarrow{\mathbf{u}}+\overrightarrow{\mathbf{v}}$ que tem como representante o segmento orientado (A,C). Mostre utilizando o Princípio da Indução finita que a soma de n vetores $\overrightarrow{\mathbf{v}}_{1}+\overrightarrow{\mathbf{v}}_{2}+\ldots+\overrightarrow{\mathbf{v}}_{\mathrm{n}}$ é dada pelo vetor que tem como representante o segmento orientado (X,Y), onde X é a origem de $\overrightarrow{\mathbf{v}}_{1}$ e Y é a extremidade de $\overrightarrow{\mathbf{v}}_{\mathrm{n}}$.
147. (FM-2002)(FM-2000) Utilizando o Princípio da Indução Finita mostre que a seguinte proposição é verdadeira

$$
\left(\forall \mathrm{n} \in \mathrm{IN}^{*}\right)[1.2+2.3+\ldots+\mathrm{n} .(\mathrm{n}+1)=\frac{1}{3} \mathrm{n} .(\mathrm{n}+1)(\mathrm{n}+2)]
$$

Solução: i) Temos $p\left(n_{n}\right)$ é verdadeiro pois

$$
0.1=0 . \frac{1}{3} \cdot(0+1)(0+2)
$$

ii) Suponhamos que $p(k)$ é verdadeiro, então temos
$(0.1+1.2+2.3+\ldots+k .(k+1)=\frac{1}{3} k(k+1)(k+2)$
Provaremos que $p(k+1)$ é verdadeiro. De fato, somando $(k+1)(k+2)$ em ambos os lados da igualdade temos

$$
\begin{gathered}
0.1+1.2+2.3+\ldots k .(k+1)+(k+1)(k+2)=\frac{1}{3} k(k+1)(k+2)+(k+1)(k+2)= \\
\frac{k(k+1)(k+2)+3(k+1)(k+2)}{3}=\frac{(k+1)(k+2)(k+3)}{3}=\frac{1}{3}(k+1)(k+2)(k+3)
\end{gathered}
$$

Portanto, $p(k+1)$ é verdadeiro.
148. (FM-2002) Mostre que :

$$
1^{2}+3^{2}+5^{2}+\ldots(2 n-1)^{2}=\frac{n\left(4 n^{2}-1\right)}{3}
$$

para todo $\mathrm{n} \in \mathrm{IN}$ e $\mathrm{n} \geq 1$.

$$
\text { Temos } P(1) \text { verdadeiro pois } 1^{2}=1=\frac{1\left(4.1^{2}-1\right)}{3} \text {. Suponhamos que } p(k) \text { é verdadeiro, então } 1^{2}+3^{2}+5^{2}+\ldots+
$$

$(2 k \cdot 1)^{2}=\frac{k\left(4 k^{2}-1\right)}{3}$
Somando $[2(k+1)-1]^{2}$ em ambos os lados obtemos:

$$
\begin{aligned}
1^{2}+3^{2}+5^{2}+\ldots+(2 k-1)^{2}+(2(k+1)-1)^{2} & =\frac{k\left(4 k^{2}-1\right)}{3}+(2(k+1)-1)^{2}= \\
& =\frac{k\left(4 k^{2}-1\right)}{3}+(2 k+1)^{2}=\frac{k\left(4 k^{2}-1\right)+3(2 k+1)^{2}}{3}= \\
& =\frac{4 k^{3}-k+12 k^{2}+12 k+3}{3}=\frac{4 k^{3}+11 k+12 k^{2}+3}{3}=
\end{aligned}
$$

$$
\begin{gathered}
=\frac{(k+1) \cdot\left(4 k^{2}+8 k+4-1\right)}{3}=\frac{(k+1)\left(4 k^{2}+8 k+3\right)}{3}= \\
=\frac{(k+1)\left(4(k+1)^{2}-2\right)}{3}
\end{gathered}
$$

Portanto temos $P(k+1)$ é verdadeiro.
149. (FM-2002) Utilize o princípio de indução finita para mostrar a validade da proposição encontrando o valor de $\mathrm{n}_{0}$ : $\left(\exists \mathrm{n}_{0} \in \mathrm{IN}, \mathrm{n} \geq \mathrm{n}_{0}\right)\left(2^{\mathrm{n}}>\mathrm{n}^{2}\right)$.
Solução:Primeiramente faremos alguns testes para encontrar o possível valor de $n_{0}$,

| $\boldsymbol{n}$ | $\mathbf{2}^{\mathbf{n}}$ | $\boldsymbol{n}^{\mathbf{2}}$ |
| :-- | :-- | :-- |
| $\mathbf{0}$ | $\mathbf{1}$ | $\mathbf{0}$ |
| $\mathbf{1}$ | $\mathbf{2}$ | $\mathbf{1}$ |
| $\mathbf{2}$ | 4 | 4 |
| $\mathbf{3}$ | 8 | 9 |
| $\mathbf{4}$ | 16 | 16 |
| $\mathbf{5}$ | 32 | 25 |
| $\mathbf{6}$ | 64 | 36 |
| $\mathbf{7}$ | 128 | 49 |
| $\mathbf{8}$ | 256 | 64 |
| $\mathbf{9}$ | 512 | 81 |
| $\mathbf{1 0}$ | 1024 | 100 |

Pela tabela vemos que $p(5)$ é verdadeiro pois: $2^{5}=32>25=5^{2}$
Suponhamos que $p(k)$ é verdadeiro então: $2^{k}>k^{2} \quad *$
Multiplicando ${ }^{\circ}$ por 2 temos $2^{k+1}>2 k^{2}$
Assim devemos mostrar que $2 k^{2} \geq(k+1)^{2}$
De fato:
$K \geq 5 \Rightarrow k \geq \frac{2+2 \sqrt{2}}{2} \Rightarrow k^{2}+2 k+1 \geq 0 \Rightarrow 2 k^{2} \geq k^{2}-2 k+1 \Rightarrow 2 k^{2} \geq(k+1)^{2}$
Portanto $p(k+1)$ é verdadeiro.
150. (FM-2002) Mostre por indução que:

$$
(\forall \mathrm{n} \in \mathrm{IN}) \cdot\left(\left[\begin{array}{ll}
1 & 1 \\
0 & 1
\end{array}\right]^{n}=\left[\begin{array}{ll}
1 & n \\
0 & 1
\end{array}\right]\right)
$$

Solução:Temos que $p(1)$ é verdadeiro pois:

$$
\left[\begin{array}{ll}
1 & 1 \\
0 & 1
\end{array}\right]^{1}=\left[\begin{array}{ll}
1 & 1 \\
0 & 1
\end{array}\right]
$$

Suponhamos agora que $p(k)$ seja verdadeiro, então temos

$$
\left[\begin{array}{ll}
1 & 1 \\
0 & 1
\end{array}\right]^{k}=\left[\begin{array}{ll}
1 & 1 \\
0 & k
\end{array}\right]
$$

Devemos mostrar que $p(k+1)$ é verdadeiro. De fato:

$$
\left[\begin{array}{ll}
1 & 1 \\
0 & 1
\end{array}\right]^{k+1}=\left[\begin{array}{ll}
1 & 1 \\
0 & 1
\end{array}\right]^{k} \cdot\left[\begin{array}{ll}
1 & 1 \\
0 & 1
\end{array}\right]=\left[\begin{array}{ll}
1 & k \\
0 & 1
\end{array}\right]\left[\begin{array}{ll}
1 & 1 \\
0 & 1
\end{array}\right]=\left[\begin{array}{ll}
1 & k+1 \\
0 & 1
\end{array}\right]
$$

Como queríamos demonstrar.
151. (MD-2001)(FM-1999) Utilize o Princípio da Indução Matemática para mostrar que o termo geral de uma progressão aritmética de razão r é $\mathrm{a}_{\mathrm{k}}=\mathrm{a}_{1}+(\mathrm{n}-1) \cdot \mathrm{r}$.
Solução: $a_{\mathrm{r}}=a_{1}+(n-1) \cdot r, \quad n \in \mathbb{N}^{n}$
(i) $\mathrm{P}(1)$ é verdadeiro pois $\mathrm{a}_{1}=\mathrm{a}_{1}+(1-1) \cdot \mathrm{r}$.
(ii) Suponhamos que $\mathrm{P}(\mathrm{k})$ seja verdadeiro, então

$$
\mathrm{a}_{\mathrm{k}}=\mathrm{a}_{1}+(\mathrm{k}-1) \cdot \mathrm{r}
$$

Como temos uma P.A de razão r , $\mathrm{a}_{\mathrm{k}+1}=\mathrm{a}_{\mathrm{k}}+\mathrm{r}=\mathrm{a}_{1}+(\mathrm{k}-1) \cdot \mathrm{r}+\mathrm{r}=\mathrm{a}_{1}+[(\mathrm{k}-1)+1] \cdot \mathrm{r}=\mathrm{a}_{1}+[(\mathrm{k}+1)-1] \cdot \mathrm{r}$
Logo, $\mathrm{P}(\mathrm{k}+1)$ é verdadeiro.
Portanto, obtemos o desejado.

152. (FM-2001) Mostre, utilizando o Princípio de Indução Finita, as seguintes proposições:
a) $(\forall \mathrm{n} \in \mathrm{IN}) \quad\left(1+\frac{1}{4}+\frac{1}{9}+\ldots+\frac{1}{\mathrm{n}^{2}}\right) \leq 2-\frac{1}{\mathrm{n}}$
b) $(\forall \mathrm{n} \in \mathrm{IN})\left(2^{3 n}-1\right.$ é divisível por 7$)$.

# Solução: (1 ${ }^{\text {a }}$. maneira) 

a) $P(1)$ é verdadeira pois $1 \leq 1$. Suponhamos que $P(k)$ é verdadeiro, então

$$
\left(1+\frac{1}{4}+\frac{1}{9}+\ldots+\frac{1}{\mathrm{k}^{2}}\right) \leq 2-\frac{1}{\mathrm{k}}
$$

Somando $\frac{1}{(\mathrm{k}+1)^{2}}$ em ambos os lados obtemos

$$
\begin{aligned}
& \left(1+\frac{1}{4}+\frac{1}{9}+\ldots+\frac{1}{\mathrm{k}^{2}}+\frac{1}{(\mathrm{k}+1)^{2}}\right) \leq 2-\frac{1}{\mathrm{k}}+\frac{1}{(\mathrm{k}+1)^{2}}= \\
& =2 \cdot\left(\frac{1}{(\mathrm{k}+1)^{2}}-\frac{1}{\mathrm{k}}\right)^{( }\left(2-\frac{1}{\mathrm{k}+1}\right.
\end{aligned}
$$

Portanto, $P(k+1)$ é verdadeiro.
( ${ }^{a}$ ) $\frac{1}{(\mathrm{k}+1)^{2}}=\frac{1}{\mathrm{k}^{2}+2 \mathrm{k}+1} \leq \frac{1}{\mathrm{k}^{2}+1} \leq \frac{\mathrm{k}}{\mathrm{k}^{2}+1}=\frac{1}{\mathrm{k}}-\frac{1}{\mathrm{k}+1} \Rightarrow \frac{1}{(\mathrm{k}+1)^{2}}-\frac{1}{\mathrm{k}} \leq \frac{-1}{\mathrm{k}+1}$.
(2 ${ }^{a}$. maneira)
$P(1)$ é verdadeiro, pois $2^{2}-1=7$. Suponhamos que $P(k)$ é verdadeiro, então

$$
2^{2 k}-1=7 \cdot \mathrm{~m}, \mathrm{~m} \in \mathrm{Z}
$$

Multiplicando por $2^{3}$ em ambos os lados obtemos

$$
\begin{gathered}
2^{2 k} \cdot 2^{3}-2^{3}=7 \cdot \mathrm{~m} \cdot 2^{3} \Rightarrow 2^{3(k+1)}-8=7 \cdot \mathrm{~m} \cdot 2^{3} \Rightarrow 2^{3(k+1)}-1=7 \cdot \mathrm{~m} \cdot 2^{3}+7 \Rightarrow \\
\Rightarrow 2^{3(k+1)}-1=7 \cdot\left(\mathrm{~m} \cdot 2^{3}+7\right) \Rightarrow 2^{3(k+1)}-1=7 \cdot(8 \cdot \mathrm{~m}+7)
\end{gathered}
$$

Como $8 m+7 \in Z$, temos que $2^{(8+1)}-1$ é divisível por 7. Portanto, $P(k+1)$ é verdadeiro.
153. (FM-2001) Mostre, utilizando o Princípio de Indução Finita, as seguintes proposições:
a) $\left(\forall \mathrm{n} \in \mathrm{IN}^{n}\right)\left(2^{\mathrm{n}}>\mathrm{n}\right)$;
b) $(\forall \mathrm{n} \in \mathrm{IN})\left(3^{3 n}+7\right.$ é divisível por 8$)$.

## Solução:(1 ${ }^{\text {a }}$. maneira)

a) $P(1)$ é verdadeiro, pois

$$
2^{1}=2>1
$$

Suponhamos que $P(k)$ seja verdadeiro, então

$$
2^{\mathrm{k}}>\mathrm{k}
$$

Multiplicando ambos lados por 2 teremos:

$$
2^{\mathrm{k}} \cdot 2>2 \cdot \mathrm{k} \Rightarrow 2^{\mathrm{k}+1}>2 \cdot \mathrm{k}
$$

Como $k>1$ temos $k+k>k+1$ e, logo, $2 . k>k+1$.
Portanto, $2^{k+1}>k+1$ e $P(k+1)$ é verdadeiro
b) $P(0)$ é verdadeiro pois

$$
3^{2 \cdot k}+7=3^{0}+7=1+7=8=8 \cdot 1
$$

Suponhamos que $P(k)$ seja verdadeiro, então $\frac{8}{3^{2 \cdot k}+7}$, ou seja, $3^{2 \cdot k}+7=8$.a para algum $a \in Z$.
Multiplicando ambos os lados por $3^{2}$ obtemos:
$3^{2 \cdot k} 3^{2}+7 \cdot 3^{2}=8 \cdot a \cdot 3^{2} \Rightarrow 3^{2 k+2}+63=8 \cdot(9 \cdot a) \Rightarrow 3^{2(k+1)}+7=8 \cdot(9 \cdot a)-56 \Rightarrow \Rightarrow 3^{2(k+1)}+7=8 \cdot(9 \cdot a-7)$
$\exists b=(9 . a-7) \in Z$ tal que $3^{2(k+1)}+7=8 . b$. Portanto, $\frac{8}{3^{2 \cdot k}+7} e P(k+1)$ é verdadeiro.

## (2 ${ }^{a}$. maneira)

(a) i) Para $n=1$, temos que $2^{n}=2^{1}=2>1=n$.

ii) Suponhamos que para $n=k$ o resultado seja verdadeiro, ou seja, $2^{k}>k$. Queremos mostrar que o resultado é verdadeiro para $n=k+1$, ou seja, queremos mostrar que $2^{k+1}>k+1$.
Temos que $2^{k+1}=2^{k} \cdot 2^{1}$, mas pela hipótese de indução $2^{k}>k$, logo $2^{k} \cdot 2^{1}>2 . k$. Assim $2^{k+1}>2 . k=k+k>k+1$, pois $k \geq 1$. Pelo PIF, temos o desejado.
(b) $P(0)$ é verdadeiro pois

$$
3^{2 \cdot 0}+7=3^{0}+7=1+7=8=8 \cdot 1
$$

Suponhamos que o resultado seja verdadeiro para $n=k$, isto é, $3^{2 \cdot k}+7$ é divisível por 8. Queremos mostrar que a proposição é verdadeira quando $n=k+1$, ou seja, $3^{2 \cdot(k+1)}+7$ é divisível por 8 . Temos

$$
3^{2 \cdot(k+1)}+7=3^{2 k+2}+7=3^{2 k} \cdot 3+7 \quad\left({ }^{n}\right)
$$

Pela hipótese de indução $3^{2 \cdot k}+7=8$.a para algum a inteiro. Assim $3^{2 \cdot k}=8 . a-7$, em $\left({ }^{n}\right)$, obtemos

$$
3^{2 \cdot(k+1)}+7=9 \cdot 3^{2 k}+7=9 \cdot(8 \cdot a-7)+7=9 \cdot 8 \cdot a-56=8 \cdot(9 \cdot a-7)
$$

e 9.a -7 é um número inteiro. Assim temos pelo PIF o desejado.
154. (FM-2001) Define-se $a^{n}$ assim $a^{0}=1$ e $a^{n}=a^{n-1} \cdot a, \forall n>0$. Utilize esta definição e o Princípio da Indução Finita (PIF) para mostrar que $\mathrm{a}>0 \Rightarrow \mathrm{a}^{\mathrm{n}}>0, \forall \mathrm{n} \in \mathrm{IN}$.

# Solução: 

i) Se $n=0$, teremos $a>0 \Rightarrow a^{n}=a^{0}=1>0$, portanto a proposição é verdadeira.
ii) Suponhamos que para $n=k$ tenhamos uma proposição verdadeira, ou seja, $a>0 \Rightarrow a^{k}>0$. Queremos mostrar que, se $a>0 \Rightarrow a^{k+1}>0$. Temos $a^{k+1}=a^{k}$.a (por definição). Mas por hipótese de indução $a^{k}>0$ e por hipótese $a>0$, logo $a^{k+1}$ é produto de dois números positivos e assim $a^{k+1}>0$.
155. (MD-2001) Demonstre, por indução finita, que

$$
1^{3}+2^{3}+3^{3}+\ldots+n^{3}=\frac{n^{2}}{4}(n+1)^{2}, \quad \forall n \in I N
$$

Solução: (i) $P(1)$ é verdadeiro, pois $1^{3}=(1 / 4)^{2}(1+1)^{2}$.
(ii) Suponhamos que $p(k)$ é verdadeiro então

$$
1^{3}+2^{3}+3^{3}+\ldots+k^{3}=k^{2} / 4 \cdot(k+1)^{2}
$$

Somando $(k+1)^{3}$ em ambos os lados de $\left(^{*}\right)$, teremos

$$
\begin{aligned}
1^{3}+ & 2^{3}+3^{3}+\ldots+k^{3}+(k+1)^{3}=k^{2} / 4 \cdot(k+1)^{2}+(k+1)^{3}= \\
= & k^{2} / 4+k+1)+(k+1)^{2}=\left(k^{2}+4 k+4\right) / 4 \cdot(k+1)^{2}= \\
& =(k+1)^{2} / 4 \cdot\left(k^{2}+4 k+4\right)=(k+1)^{2} / 4 \cdot(k+2)^{2}
\end{aligned}
$$

Logo, $p(k+1)$ é verdadeiro. Portanto, $P(n)$ é verdadeiro para todo $n \in I N$, pelo Princípio da Indução Finita.
156. (FM-2000) Utilizando o Princípio da Indução Finita mostre que as seguinte proposição é verdadeira

$$
\left(\forall \mathrm{n} \in \mathrm{IN}^{*}\right)\left[3^{0}+3^{1}+\ldots+3^{n-1}=\frac{1}{2}\left(3^{n}-1\right)\right]
$$

## Solução:

Primeiramente mostraremos que $p(1)$ é verdadeiro. De fato

$$
3^{0}=1=\frac{1}{2}\left(3^{1}-1\right)
$$

Agora, suponhamos $p(k)$ verdadeiro, então temos

$$
3^{0}+3^{1}+3^{2}+\ldots 3^{k-1}=\frac{1}{2}\left(3^{k}-1\right)
$$

Queremos mostrar que $p(k+1)$ é verdadeiro. De fato

$$
\begin{aligned}
& 3^{0}+3^{1}+3^{2}+\ldots+3^{k+1(-1}=\frac{1}{2}\left(3^{k}-1\right)+3^{k+1}= \\
= & \frac{3^{k}}{2}-\frac{1}{2}+3^{k}=\frac{3 \cdot 3^{k}}{2}-\frac{1}{2}=\frac{1}{2}\left(3^{k+1}-1\right)
\end{aligned}
$$

157. (FM-2000) Mostre que $n^{3}+2 n$ é divisível por 3 .

Solução: $P(n):(V n \in I N, n \geq 0)\left(n^{2}+2 n\right)$ é divisível por 3.
Primeiramente, mostremos que $P(0)$ é verdadeiro. De fato,
$0^{3}+2.0=0=3.0$
Agora, por hipótese de indução, suponhamos que $P(k)$ é verdadeiro, ou seja,

(3a, $a \in Z, a \geq 0$ ) tal que $(\forall k \in I N, k \geq-1)$
$k^{2}+2 k=3 . a$
Queremos mostrar que $P(k+1)$ também é verdadeiro. De fato,

$$
\begin{aligned}
(k+1)^{2}+2(k+1)=k^{2}+3 k^{2}+3 k+1 & +2 k+2= \\
& =\left(k^{2}+2 k\right)+3 k^{2}+3 k+3= \\
& =3 a+3 k^{2}+3 k+3= \\
& =3 .\left(a+k^{2}+k+1\right)
\end{aligned}
$$

Portanto $P(k+1)$ é verdadeiro.
158. (FM-2000)(FM-1999) Utilizando o Princípio da Indução Finita mostre que a seguinte proposição é verdadeira

$$
\left(\forall \mathrm{n} \in \mathrm{IN}^{*}\right)\left[1+4+7+\ldots+(3 \mathrm{n}-2)=\frac{3 \mathrm{n}^{2}-\mathrm{n}}{2}\right.
$$

Solução: Primeiramente, mostraremos que p(1) é verdadeiro, de fato:

$$
3.1-2=1=\frac{3.1^{2}-1}{2}
$$

Agora, suponhamos que p(k) seja verdadeiro, então temos :

$$
1+4+7+\ldots+(3 k-2)=\frac{3 k^{2}-k}{2}
$$

Devemos mostrar que $p(k+1)$ é verdadeiro, de fato :

$$
\begin{aligned}
& 1+3+7+\ldots+(3 k-2)+(3(k+1)-2)=\frac{3 k^{2}-k}{2}+(3(k+1)-2)= \\
& \frac{3 k^{2}-k+2(3(k+1))-4}{2}=\frac{3 k^{2}-k+6 k+6-4}{2}= \\
& =\frac{3 k^{2}+5 k+2}{2}= \\
& =\frac{3 k^{2}+5 k+2+(k+1)-(k+1)}{2} \\
& =\frac{3\left[k^{2}+2 k+1\right]-(k+1)}{2} \\
& =\frac{3(k+1)^{2}-(k+1)}{2}
\end{aligned}
$$

159. (FM-1999) Prove por indução finita a seguinte asserção: $2+4+6+8+10+\ldots+2 \mathrm{n}=\mathrm{n} .(\mathrm{n}+1)$.

Solução: Temos que $P(0)$ é verdadeiro pois

$$
2.0=0=0(0+1)
$$

Agora, suponhamos que $p(k)$ seja verdadeiro, então temos

$$
2+4+6+8+10+\ldots+2 k=k(k+1)
$$

Devemos mostrar que $p(k+1)$ é verdadeiro, de fato:

$$
\begin{aligned}
2+4+6+8+10+\ldots+2 k+2(k+1) & =k(k+1)+2 k+2= \\
& =(k+1)(k+2)
\end{aligned}
$$

# Problemas Lógicos 

160. Num problema considere os seguintes elementos:

Temos cinco casas.
O inglês vive na casa amarela.

O brasileiro é o dono do cachorro.
Na casa verde se bebe café.
O espanhol bebe chá.
A casa verde está situada ao lado e a direita (do leitor) da casa cinzenta.
O estudante de psicologia possui macacos.
Na casa amarela se estuda filosofia.
Na casa do meio se bebe leite.
O norueguês vive na primeira casa.
O senhor que estuda lógica vive na casa vizinha à do homem que tem uma raposa.
Na casa vizinha a que se guarda o cavalo, estuda-se filosofia.
O estudante que se dedica a estudos sociais bebe suco de laranja.
O japonês estuda metodologia.
O norueguês vive ao lado da casa azul.
Esclarecimento: Cada uma das cinco casas está pintada de diferente cor. Seus moradores são de diferentes nacionalidades. Tem diferentes animais. Bebem diferentes bebidas e estudam diferentes matérias. Apresente clara e nitidamente qual a ordem das casas, quem é o morador de cada uma, de que cor são pintadas, o que estuda cada morador, qual seu bicho de estimação e qual sua cor preferida.

Perguntas: Quem bebe água? E quem é dono da zebra?
161. Escritor famoso:Um teste de um concurso indaga:"qual a época do nascimento de um eminente escritor inglês, sabendo-se que apenas uma das alternativas é correta?(a)nasceu no século XIX; (b) nasceu no século XX; (c) nasceu depois de 1860; (d) nasceu antes de 1860; (e) não é possível resolver este problema".
162. O filho do pianista:Para complicar a vida de um lógico que queria saber a idade de seus três filhos, uma senhora manteve com ele seguinte diálogo:
_O produto de suas idades é 36
_Ainda não sei, respondeu o lógico
_A soma de suas idades é igual ao número da casa ao lado.
_Ainda não sei, respondeu o lógico.
_O mais velho toca piano.
_ Agora já sei as idades, respondeu o lógico.
Qual era o numero da casa e quais as idades dos filhos?
163. Diálogo de filósofos: Um paradoxo conhecido desde a época medieval, imagina o seguinte diálogo entre Socrátes e Platão: Quem esta mentindo?
_ Socrátes: "O que Platão vai dizer é falso."
_ Platão: "Socrátes acaba de dizer uma verdade."
164. Frente e verso: Numa folha de papel em branco escreva: "A sentença do outro lado é verdadeira". No outro lado escreva: "A sentença do outro lado é falsa". As sentenças são verdadeiras?
165. O Barbeiro: Um barbeiro foi condenado a barbear todos e somente todos aqueles homens que não se barbeiam a si próprios. Quem barbeia o barbeiro?
166. O crocodilo sádico: Um crocodilo raptou um beb6e de sua mãe e prometeu devolvê-lo se a mãe respondesse corretamente "sim' ou "não". Questão: "Vou comer o sei bebê?"
O que a mãe respondeu e o que fez o crocodilo?
167. Os condenados: Os prisioneiros de um certo reino são sempre decapitados ou enforcados. Um prisioneiro conseguiu o privilégio de fazer uma previsão. Se fosse falsa, ele seria enforcado, e se fosse correta, decapitado. O prisioneiro conseguiu se livrar da pena?
168. O problema de três filósofos: Três filósofos, depois de uma longa discussão, adormeceram debaixo de uma árvore. Um moleque, passando por aí, pintou o nariz dos três de vermelho. Quando os filósofos acordaram, começaram a rir da cara do outro, até que um deles parou bruscamente, porque se deu conta que seu nariz também estava pintado. Qual foi seu raciocínio?
169. Os revolucionários: Três revolucionários foram presos, mas o juiz tinha simpatia pela causa que eles defendiam e queria achar uma maneira sutil de liberta-los. Num dia o juiz chegou à cela com 5 etiquetas, duas pretas e três brancas, e anunciou: "Vou fixar uma etiqueta nas costas de cada um, de modo que cada um de vocês possa ver a de seus companheiros sem ver o própria. Não poderá haver nenhum tipo de comunicação. Quem acertar a cor de sua etiqueta e puder explicar, estará livre." Em seguida, fixou as etiquetas brancas nas costas dos prisioneiros e saiu, deixando-os com o guarda. Como cada um deles pode acertar a cor de sua etiqueta?

# Circuitos Lógicos e de Interruptores 

170. Simplifique ao máximo os seguintes circuitos de interruptores:
b)
a)
![img-2.jpeg](img-2.jpeg)
c)
![img-3.jpeg](img-3.jpeg)
e)
![img-4.jpeg](img-4.jpeg)

