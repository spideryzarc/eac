# Resultado do OCR

Exercício 3. Faça a tabela-verdade da disjunção exclusiva.
Em Lógica, como se observou, uma disjunção é verdadeira quando uma das proposições constituintes é verdadeira ou, também, quando ambas são verdadeiras simultaneamente.

Exercício 4. Faça o que se pede.

1. Sejam as proposições $A \equiv$ "O livro é interessante" e $B \equiv$ "O livro é caro". Fornecer uma sentença na linguagem natural que descreva cada uma das simbolizações abaixo:
a) $(\neg A)$
b) $(A \wedge B)$
c) $(A \vee B)$
d) $(B \vee(\neg A))$
e) $((\neg A) \wedge(\neg B))$
2. Sejam as sentenças: $A \equiv$ "A neve é branca" e $B \equiv$ "O sol é um astro". Determinar o valor-verdade das sentenças abaixo:
a) $[A \wedge(\neg B)]$
b) $[\neg(A \vee B)]$
c) $[(\neg A) \vee B]$
d) $[(\neg A) \wedge(\neg B)]$
e) $[A \leftrightarrow(\neg B)]$
3. Em que casos as sentenças abaixo são falsas? (Em cada item estude todas as possibilidades)
a) Ela é mineira e ele é paraense.
b) Ela é mineira ou ele é paraense.
c) É falso que ela é mineira e ele é paraense.
d) É falso que ela é mineira e é falso que ele é paraense.
4. Sejam as expressões $A \equiv$ "O céu é azul", $B \equiv$ "Deus existe" e $C \equiv$ "O Sol gira em torno da Terra". Fornecer uma sentença na linguagem natural que descreva cada uma das afirmações abaixo:
a) $(\neg A)$
b) $(A \wedge B)$
c) $((A \vee B) \wedge C)$
d) $(B \vee(\neg C))$
e) $[(\neg A) \wedge(\neg B)]$
f) $[\neg((\neg A) \vee C)]$
g) $[\neg(A \vee(\neg \neg B))]$
h) $(C \wedge(\neg B))$
5. Escreva as sentenças em linguagem simbólica abaixo utilizando os conectivos $\neg, \wedge \mathrm{e} \vee$.
a) Não é verdade que Galileu esteja certo.
b) A água não pode ser simultaneamente líquida e sólida.
c) O seguro da casa inclui incêndio ou roubo.
d) Compro ou não compro.
e) Não estudarei hoje, mas estudarei amanhã e quarta-feira.
6. Determinar a tabela verdade das sentenças abaixo, sendo $A \equiv \varnothing=\{\varnothing\}, B \equiv \varnothing=\varnothing, C \equiv\{\varnothing\}=\{\{\varnothing\}\}:$
a) $[A \wedge(\neg C)]$
b) $[\neg(B \vee C)]$
c) $[(\neg B) \wedge(\neg C)]$
d) $[\neg(A \wedge(\neg B))]$
f) $[\neg[(\neg A) \wedge(\neg B)]]$
g) $[\mathrm{A} \vee(\neg(A \wedge C))]$

7. Em que casos as sentenças abaixo não são falsas? (Estude todas as possibilidades)
a) A Terra gira e Maria gosta de José.
b) Passarei em lógica ou $2+2=4$.
c) É falso que ela gosta dele e é falso que ele gosta dela.
d) É falso que ela gosta dele e ele gosta dela.
8. Entendemos por disjunção exclusiva ao tipo de disjunção em que as sentenças não podem ocorrer simultaneamente, como no exemplo "Ela está alegre ou não está alegre". Definir, nos casos abaixo se o ou corresponde à disjunção inclusiva ou exclusiva.
a) Eu menti ontem ou mentirei amanhã.
b) Meu time é o campeão deste ano ou não é o campeão deste ano.
c) Ela se formou em 1993 ou em 1998.
d) Com sol ou com chuva, você trabalhava.
e) O terno é de Bentinho ou de Escobar.

# 4) Implicação 

Dadas as proposições $A$ e $B$ podemos considerar a nova proposição $(A \rightarrow B)$, a implicação de $B$ por $A$.

A proposição $A$ chama-se antecedente da implicação $(A \rightarrow B)$ e $B$ chama-se o conseqüente da implicação $(A \rightarrow B)$.

Postulamos que a proposição $(A \rightarrow B)$ é falsa se e somente se o antecedente $A$ é verdadeiro e o conseqüente $B$ é falso. Nos demais casos, a proposição $(A \rightarrow B)$ é verdadeira.

As considerações acima podem ser esquematizadas como se segue:

## Tabela-verdade da implicação:

| $A$ | $B$ | $(A \rightarrow B)$ |
| :--: | :--: | :--: |
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 1 |
| 0 | 0 | 1 |

Exemplo 7. Consideremos as seguintes proposições:

1) $\frac{[(2+4=4) \wedge(1 \leq 2)]}{\text { verdadeira }} \underset{\text { verdadeira }}{\text { : }}$
2) $\frac{[(2+4=4) \wedge(1 \geq 2)]}{\text { verdadeira }}$
3) $\frac{[(2+4 \neq 4) \wedge(1 \leq 2)]}{\text { falsa }}$
4) $\frac{[(2+4 \neq 4) \wedge(2+4 \neq 4)}{\text { falsa }} \underset{\text { falsa }}{\text { verdadeira }}$

Esta proposição é verdadeira
Esta proposição é verdadeira

Exercício 6. Dizer se são verdadeiras ou falsas (adote o "bom senso" nos juízos):

1. Se a neve é branca, então Paris é a capital da França.
2. Se Penha é um bairro de São Paulo, então o céu não contém estrelas.
3. Se os planetas giram em torno da terra, então inexistem extra-terráqueos.
4. Se o sol é um planeta inerte, então a terra é uma estrela.

# 5) Bi-implicação 

Dadas as proposições $A$ e $B$ podemos considerar a nova proposição $(A \leftrightarrow B)$, a bi-implicação de $A$ e $B$.

Postulamos que a proposição $(A \leftrightarrow B)$ é verdadeira se e somente se as proposições $A$ e $B$ possuem o mesmo valor-verdade. A proposição $(A \leftrightarrow$ $B$ ) é falsa se e somente se as proposições $A$ e $B$ tiverem valores-verdade trocados.

As considerações acima podem ser esquematizadas como se segue:

## Tabela-verdade da bi-implicação:

| $A$ | $B$ | $(A \leftrightarrow B)$ |
| :--: | :--: | :--: |
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 0 |
| 0 | 0 | 1 |

Exemplo 9. Consideremos as seguintes proposições:

1) $\underbrace{[(2+4=4)}_{\text {verdadeira }} \wedge \underbrace{(1 \leq 2)]}_{\text {verdadeira }}$ Esta proposição é verdadeira
2) $\underbrace{[(2+4=4)}_{\text {verdadeira }} \wedge \underbrace{(1 \geq 2)]}_{\text {falsa }}$ Esta proposição é falsa
3) $\underbrace{[(2+4 \neq 4)}_{\text {falsa }} \wedge \underbrace{(1 \leq 2)]}_{\text {verdadeira }}$ Esta proposição é falsa
4) $\underbrace{[(2+4 \neq 4)}_{\text {falsa }} \wedge \underbrace{(1 \geq 2)]}_{\text {falsa }}$ Esta proposição é verdadeira

Exercício 7. Faça o que se pede.

1. Indiquemos por $A \equiv$ "Está calor" e por $B \equiv$ "É verão". Escrever em forma simbólica as seguintes afirmações:
a) É verão somente se está calor.
b) Uma condição necessária para estar calor é que seja verão.
c) Uma condição suficiente para estar calor é que seja verão.
d) Sempre que é verão, faz calor.
e) Nunca é verão, quando está calor.

2. Dentro do contexto da lógica proposicional, identifique as sentenças abaixo quanto a sua veracidade ou falsidade justificando devidamente cada resposta dada.
a) $(5+4=9 \wedge 2 \leq 4)$,
b) $(3+2=6 \wedge 2+2=4)$,
c) $(5+3=7 \vee 4+4=7)$,
d) $(4+3=7 \vee 2+3=4)$
e) $(2+3=5 \rightarrow 2+2=4)$,
f) $(3+3=5 \rightarrow 32 \leq 33)$
g) $(2+4=7 \rightarrow 2+2=5)$,
h) $(3+2=5 \rightarrow 2+2=5)$
i) $(6+2=8 \leftrightarrow 6 \leq 8)$,
j) $(3+3=5 \leftrightarrow 2+2=3)$,
k) $(2+2=3 \leftrightarrow 2+2=4)$,
l) $(3+4=6 \leftrightarrow 3+3=7)$,
m) $(32 \leq 2 \rightarrow 4 \leq 3)$,
n) $(32 \leq 33 \rightarrow 4+5=8)$,
o) $(2 \leq 3 \rightarrow(2+2=4 \wedge 7+2=9))$
1) $((3 \leq 4 \wedge 4 \leq 3) \rightarrow 3+3=7)$.

A seguir apresentamos algumas leituras que a negação, conjunção, disjunção, implicação e bi-implicação podem ter na linguagem natural.

| $(A)$ | Não $A$; <br> Não se dá que $A$; <br> Não é fato que $A$; <br> Não é verdade que $A$; <br> Não é que $A$; <br> Não se tem $A$. |
| :--: | :--: |
| $(A \wedge B)$ | $A$ e $B$; <br> $A$, mas $B$; <br> $A$, embora $B$; <br> $A$, assim como $B$; <br> $A$ e, além disso, $B$; <br> Tanto $A$ como $B$; <br> $A$ e também $B$; <br> Não só $A$, mas também $B$; <br> $A$, apesar de $B$. |
| $(A \vee B)$ | $A$ ou $B$ ou ambos. |
| $(A \rightarrow B)$ | se $A$, então $B$; <br> se $A$, isto significa que $B$; <br> tendo-se $A$, então $B$; <br> quando $A$, então $B$; <br> sempre que $A, B$; <br> $B$, sempre que se tenha $A$; <br> $B$, contanto que $A$; <br> $A$ é condição suficiente para $B$; <br> $B$ é condição necessária para $A$; <br> Uma condição suficiente para $B$ é $A$; <br> Uma condição necessária para $A$ é $B$; <br> $B$, se $A$; |

|  | $B$, quando $A$; <br> $B$, no caso de $A$; <br> $A$, só se $B$; <br> $A$, somente quando $B$; <br> $A$, só no caso de $B$; <br> $A$ implica $B$, <br> $A$ acarreta $B$, <br> $B$ é implicada por $A$. |
| :-- | :-- |
| $(A \leftrightarrow B)$ | $A$ se e só se $B$; <br> $A$ se e somente se $B$; <br> $A$ quando e somente quando $B$; <br> $A$ eqüivale a $B$; <br> Uma condição necessária e suficiente <br> para $A$ é $B$; <br> $A$ é condição necessária e suficiente <br> para $B$ |

3. Escreva as sentenças a seguir em linguagem simbólica, usando sentenças básicas (ou atômicas), isto é, as sentenças que não podem ser construídas a partir de outras sentenças.
a) Se Antônio está feliz, a esposa do Antônio não está feliz, e se o Antônio não está feliz, a esposa do Antônio não está feliz.
b) Ou Antônio virá à festa e Pedro não, ou Antônio não virá à festa e Pedro se divertirá.
c) Uma condição necessária e suficiente para o rei ser feliz é ele ter vinho, mulheres e música.
d) Teresa vai ao cinema só se o filme for uma comédia.
4. Traduza as sentenças abaixo, dado o seguinte esquema:
$A \equiv$ Clarissa sorri
$B \equiv$ Clarissa desperta
$C \equiv$ Clarissa vai á praia
$D \equiv$ Clarissa fica indecisa
$E \equiv$ Clarissa sente o sol
a) $(B \rightarrow A)$
b) $(A \rightarrow C)$
c) $((D \vee C) \rightarrow(A \leftrightarrow(B \wedge(\neg E))))$
5. Simbolize as sentenças abaixo, dado o seguinte esquema:
$A \equiv$ o estudante comete erros,
$B \equiv$ há motivação para o estudo,
$C \equiv$ o estudante aprende a matéria.
a) Se o estudante não comete erros, então ele aprende a matéria.
b) Se não há motivação para o estudo, então o estudante não aprende a matéria.
c) Se há motivação para o estudo, o estudante não comete erros.
d) O estudante aprende a matéria se, e somente se, há motivação para o estudo.

6. Simbolize as sentenças abaixo:
a) Ou Capitu é ou não é a criação mais notável de Machado de Assis.
b) Não é verdade que Machado de Assis escreveu ou não escreveu poesias.
c) Se é fácil ler o que José da Silva escreveu, não é fácil ler o que escreveu Guimarães Rosa.
7. Escreva as sentenças a seguir em linguagem simbólica, usando formas simples, isto é, as sentenças que não podem ser construídas a partir de outras sentenças.
a) Uma condição suficiente para x ser ímpar é x ser primo
b) Uma condição necessária para uma seqüência $s$ convergir é que $s$ seja limitada.
c) O suborno será pago se, e somente se, a mercadoria for entregue.
d) Judite vencerá o torneio de xadrez, a menos que Tânia vença hoje.
e) Se $x$ é positivo, então $x^{2}$ é positivo.
8. Traduza as sentenças abaixo, dado o seguinte esquema:
$A \equiv$ ganho um livro
$B \equiv$ ganho uma revista
$C \equiv$ posso ler
$D \equiv$ estou motivado
$E \equiv$ sou aprovado no exame.
a) $(C \rightarrow(A \vee B))$
b) $(D \rightarrow(\neg C))$
c) $(D \rightarrow((\neg C) \wedge(A \vee B)))$
d) $((\neg D) \rightarrow(E \rightarrow(A \vee B)))$
e) $((\neg D) \rightarrow(C \rightarrow(A \vee B))$
f) $(((\neg C) \wedge A) \rightarrow(E \rightarrow(\neg D)))$
9. Traduza as sentenças abaixo, dado o seguinte esquema:
$A \equiv$ há nuvens,
$B \equiv$ choverá,
$C \equiv$ ventará.
$D \equiv$ fará bom tempo amanhã.
a) $(A \rightarrow B)$
b) $(A \rightarrow(\neg D))$
c) $((\neg D) \wedge(B \wedge C))$
d) $((\neg A) \rightarrow D)$
e) $(A \wedge(B \vee C))$
f) $((A \wedge B) \vee C)$
g) $(A \rightarrow(B \vee C))$
h) $((A \rightarrow B) \vee C)$
i) $((A \leftrightarrow B) \wedge((\neg C) \wedge D))$
j) $(A \leftrightarrow((B \wedge C) \vee D))$
10. Simbolize as sentenças abaixo, dado o seguinte esquema:
$A \equiv$ o estudante comete erros;

$B \equiv$ há motivação para o estudo,
$C \equiv$ o estudante aprende a matéria.
a) Se não há motivação para o estudo, então o estudante comete erros ou não aprende a matéria.
b) Se o estudante comete erros, então, se não há motivação para o estudo, o estudante não aprende a matéria.
c) O estudante comete erros; além disso, há motivação para o estudo e o estudante aprende a matéria.
d) Não há motivação para o estudo se e somente se o estudante comete erros e não aprende a matéria.
e) Se há motivação para o estudo e o estudante não comete erros, então o estudante aprende a matéria se há motivação.
11. Simbolize as sentenças abaixo, dado o seguinte esquema:
$A \equiv$ Paulo diminui os erros cometidos,
$B \equiv$ há motivação para o estudo,
$C \equiv$ Paulo aprendeu a matéria,
$D \equiv$ O professor é bom.
a) Se o professor é bom, Paulo aprende a matéria.
b) Se o professor não é bom, não há motivação para estudar.
c) O professor é bom, há motivação para estudar e, além disso, Paulo aprende a matéria.
d) Paulo não aprendeu a matéria; ele não diminuiu os erros cometidos.
e) Se Paulo não diminuiu os erros cometidos, o professor não era bom ou não havia motivação para estudar.
f) Paulo aprende a matéria ou diminui os erros cometidos.
g) Paulo diminui os erros cometidos se, e somente se, há motivação para estudar.
h) Se o professor é bom, então, caso haja motivação para estudar, Paulo aprenderá a matéria.
i) Paulo diminuirá o número de erros cometidos se, e somente se, não ocorrer o seguinte: não deixa de haver motivação para o estudo e Paulo não deixa de aprender a matéria.
12. Simbolize as sentenças abaixo:
a) É fácil compreender as obras de José da Silva, mas não os de Guimarães Rosa.
b) Se Diana foi ao baile, não é fato que não tenha ido ao baile.
c) Não é fato que Paulo que vá à festa e fique satisfeito.
d) Se o computador auxilia o cientista se, e somente se, altera a sua programação, então, se altera a programação, é útil.
e) Não se dá o seguinte: não viajamos e não levamos as barracas.
f) Irei á praia salvo se chover.
g) Vou estudar exceto se tiver vontade.
13. Dadas as sentenças atômicas abaixo, escrever por meio de símbolos:
$A \equiv$ "Ela é bonita"
$B \equiv$ "Ela é inteligente"
$C \equiv$ "Ela é rica"

$D \equiv$ "Ela é jovem"
$E \equiv$ "Ela gosta de mim"
$F \equiv$ "Quero casar com ela"
a) "Ela é pobre"
b) "Ela é rica ou jovem"
c) "Ela é inteligente e anciã"
d) "Não é que ela é burra"
e) "Se ela é rica, então quero casar com ela"
f) "Ela é inteligente, bonita, rica, jovem e ela gosta de mim"
g) "Quero casar com ela, mas ela não gosta de mim"
h) "Uma condição necessária para casar com ela é que ela seja bonita"
i) "Uma condição suficiente para casar com ela é que ela seja rica"
j) "Ela é feia, burra, pobre, anciã, mas quero casar com ela"
k) "Quero casar com ela só se ela gosta de mim"
l) "Se ela é jovem então ela é bonita"
m) "Uma condição necessária e suficiente para casar com ela é que ela goste de mim"
n) "Quero casar com ela, exceto se ela é burra"

# 2.6 - Fórmulas atômicas e fórmulas 

Como observamos no início deste capítulo, através dos conectivos lógicos $\neg, \wedge, \vee, \rightarrow \mathrm{e} \leftrightarrow$, podemos construir sentenças mais "complexas" a partir de outras sentenças mais "simples". Este procedimento é clarificado pela seguinte regra de formação de sentenças:

Partimos de certas sentenças denominadas fórmulas atômicas ${ }^{1}: p$, $q, r, \ldots$ Elas desempenham, intuitivamente, o papel de sentenças básicas ou atômicas da linguagem proposicional.

As sentenças (que daqui em diante receberão o nome de 'fórmulas') em geral são obtidas pela seguinte definição indutiva generalizada:

1. Todas as fórmulas atômicas são fórmulas.
2. Se $A$ e $B$ são fórmulas, então
$(\neg A)$,
$(A \wedge B)$,
$(A \vee B)$,
$(A \rightarrow B)$ e
$(A \leftrightarrow B)$
são também fórmulas.
3. Uma dada expressão constitui uma fórmula se e somente se foi obtida pela aplicação de uma das regras (1 ou 2 ) acima.

Observe-se que os símbolos $A$ e $B$ introduzidos na definição anterior (item 2) se tratam de variáveis que denotam sentenças quaisquer da linguagem proposicional. O leitor deve estar atento para o fato de que tais símbolos não são propriamente símbolos da linguagem em apreço, mas sim símbolos que estão "fora" da linguagem proposicional. Tais variáveis denominam-se, costumeiramente, meta-variáveis.

