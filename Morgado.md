# Resultado do OCR

.

# Análise Combinatória e Probabilidade 

Augusto César de Oliveira Morgado<br>João Bosco Pitombeira de Carvalho<br>Paulo Cesar Pinto Carvalho<br>Pedro Fernandez

AQUISICACOMPA
ADQUIRIDO DE COSOM

78 FEV. 2000

PREÇO 20
REGIDRO 0317-8FE-1
DAM DO REGIDRO 12-4-2000

# Conteúdo 

1. Introdução ..... 1
1.1 O que é Combinatória? ..... 1
1.2 Um Pouco de História ..... 2
1.3 Conjuntos ..... 10
2. Combinações e Permutações ..... 17
2.1 Introdução ..... 17
2.2 Permutações Simples ..... 27
2.3 Combinações Simples ..... 31
2.4 Permutações Circulares ..... 41
2.5 Permutações de Elementos nem Todos Distintos ..... 45
2.6 Combinações Completas ..... 48
3. Outros Métodos de Contagem ..... 56
3.1 O Princípio da Inclusão-Exclusão ..... 56
3.2 Permutações Caóticas ..... 68
3.3 Os Lemas de Kaplansky ..... 72
3.4 O Princípio da Reflexão ..... 77
3.5 O princípio de Dirichlet ..... 81
4. Números Binomiais ..... 88
4.1 O Triângulo de Pascal ..... 88
4.2 O Binômio de Newton ..... 104
4.3 Polinômio de Leibniz ..... 114
5. Probabilidade ..... 118
5.1 Introdução ..... 118
5.2 Espaço Amostral e Probabilidades de Laplace ..... 119
5.3 Espaços de Probabilidade ..... 125
5.4 Probabilidades Condicionais ..... 140
5.5 A Distribuição Binomial ..... 165

Apêndice 1 ..... 170
Apêndice 2 ..... 175
Apêndice 3 ..... 178
Respostas dos Exercícios ..... 180
Bibliografia ..... 186

# Prefácio 

Este texto foi escrito como parte de um projeto de treinamento de professores de Matemática do $2^{\circ}$ grau, financiado pela Fundação VITAE, e iniciado no Rio de Janeiro, em janeiro de 1991. Aproveitamos para agradecer à VITAE por esta iniciativa.

A Análise Combinatória tem sido frequentemente indicada por professores do $2^{\circ}$ grau como sendo a parte da Matemática mais dificil de ensinar.

Apesar de repleta de problemas capazes de motivar os alunos, é considerada uma disciplina complicada, em que os alunos têm dificuldade de encontrar a fórmula correta para cada problema. Neste texto procuramos resolver problemas de contagem através do uso de alguns princípios fundamentais, evitando, sempre que possível, recorrer ao uso de fórmulas.

O livro incorpora a experiência dos autores em ensinar Análise Combinatória a alunos de $2^{\circ}$ grau, especialmente por parte do primeiro autor.

Rio de Janeiro, março de 1991.

Augusto César de Oliveira Morgado
João Bosco Pitombeira de Carvalho
Paulo Cezar Pinto Carvalho
Pedro Fernandez

.

# 1. Introdução 

### 1.1 O que é Combinatória ?

O que é Análise Combinatória ou simplesmente Combinatória? A maior parte dos alunos do $2^{\circ}$ grau responderia que ela é o estudo das combinações, arranjos e permutações. Isso no entanto é uma resposta parcial pois, embora combinações, arranjos e permutações façam parte da Análise Combinatória, são conceitos que permitem resolver um tipo de problemas de Análise Combinatória: os de contagem de certos tipos de subconjuntos de um conjunto finito, sem que seja necessário enumerar seus elementos. No entanto, a Análise Combinatória trata de vários outros tipos de problemas e dispõe, além das combinações, arranjos e permutaçōes, de outras técnicas para atacá-los: o princípio da inclusão-exclusão, o princípio das gavetas de Dirichlet, as funções geradoras, a teoria de Ramsey são exemplos de técnicas poderosas de Análise Combinatória. Pelo menos uma delas, o princípio das gavetas de Dirichlet, é mais simples ou pelo menos tão simples quanto o estudo das combinações, arranjos e permutações.

De maneira mais geral, podemos dizer que a Análise Combinatória é a parte da Matemática que analisa estruturas e relações discretas.

Dois tipos de problemas que ocorrem frequentemente em

Análise Combinatória são:

1) Demonstrar a existência de subconjuntos de elementos de um conjunto finito dado e que satisfazem certas condiçōes
2) Contar ou classificar os subconjuntos de um conjunto finito e que satisfazem certas condiçōes dadas.

Embora a Análise Combinatória disponha de técnicas gerais que permitem atacar certos tipos de problemas, é verdade que a solução de um problema combinatório exige quase sempre engenhosidade e a compreensão plena da situação descrita pela problema. Esse é um dos encantos desta parte da matemática, em que problemas fáceis de enunciar revelam-se por vezes difíceis, exigindo uma alta dose de criatividade para sua solução.

Por que privilegiar o estudo das combinaçōes, arranjos e permutações em um primeiro curso de Análise Combinatória?

Em primeiro lugar, entre os vários tipos de "números para contagem" da Análise Combinatória, eles são certamente os mais simples e de uso mais amplo. Além disso, eles permitem resolver uma grande quantidade de problemas de Análise Combinatória. Outra razão para seu estudo é a aplicabilidade desses números a problemas de probabilidades finitas, um campo de aplicação importante da Análise Combinatória.

Por outro lado, se a aprendizagem destes conceitos se faz de maneira mecânica, limitando-se a empregá-los em situações padronizadas, sem procurar habituar o aluno com a análise cuidadosa de cada problema, cria-se a impressão de que a Análise Combinatória é somente um jogo de fórmulas complicadas.

# 1.2 Um pouco de História 

O desenvolvimento do binômio $(1+x)^{n}$ está entre os primeiros problemas estudados ligados à Análise Combinatória. O caso $n=2$ já pode ser encontrado nos Elementos de Euclides, em

torno de 300 a.C. O triângulo de Pascal era conhecido por Chu Shih-Chieh, na China, (em torno de 1300) e antes disso pelos hindus e árabes. O matemático hindu Báskhara (1114-1185?), conhecido geralmente pela "fórmula de Báskhara" para a solução de equações do $2^{\circ}$ grau, sabia calcular o número de permutações, de combinações e de arranjos de $n$ objetos. O mesmo aconteceu com o matemático e filósofo religoso francês Levi ben Gerson (1288-1344), que nasceu e trabalhou no sul da França, e que, entre outras coisas, tentou demonstrar o $5^{\circ}$ Postulado de Euclides. O nome coeficiente binomial foi introduzido mais tarde por Michael Stifel (1486?-1567), que mostrou, em torno de 1550, como calcular $(1+x)^{n}$ a partir do desenvolvimento de $(1+x)^{n-1}$. Sabemos também que o matemático árabe Al-Karaji (fins do século X) conhecia a lei de formação dos elementos do triângulo de Pascal,

$$
C_{n+1}^{p+1}=C_{n}^{p+1}+C_{n}^{p}
$$

O primeiro aparccimento do triângulo de Pascal no Ocidente foi no frontispício de um livro de Petrus Apianus (1495-1552). Niccolò Fontana Tartaglia (1499-1559) relacionou os clementos do triângulo de Pascal com as potências de $(x+y)$. Pascal (16231662) publicou um tratado em 1654 mostrando como utilizá-los para achar os coeficientes do desenvolvimento de $(a+b)^{n}$. Jaime Bernoulli (1654-1705), em seu Ars Conjectands, de 1713, usou a interpretação de Pascal para demonstrar que

$$
(x+y)^{n}=\sum_{i=0}^{n}\binom{n}{i} x^{n-i} y^{i}
$$

A segunda parte deste livro de Jaime Bernoulli é dedicada à teoria das combinações e permutações.

Isaac Newton (1646-1727) mostrou como calcular diretamente $(1+x)^{n}$ sem antes calcular $(1+x)^{n-1}$. Ele mostrou que cada coeficiente pode ser determinado, usando o anterior, pela fórmula

$$
\binom{n}{r+1}=\frac{n-r}{r+1}\binom{n}{r}
$$

Em verdade, Newton foi além disso, e mostrou como desenvolver $(x+y)^{r}$, onde $r$ é um número racional, obtendo neste caso um desenvolvimento em série infinita.

- Uma outra direção de generalização do teorema do binômio é considerar potências da forma

$$
(x+y+\cdots+z)^{n}
$$

o chamado teorema mutinomial, que foi descoberto por Leibniz (1646-1716) e demonsitado também por Johann Bernoulli (16671748).

Abraham De Moivre (1667-1754), Daniel Bernoulli (17001782) e Jacques Phillipe Marie Binet (1786-1856) mostraram como achar diretamente os números de Fibonacci*, sem ser necessário calcular todos eles, até o que desejamos. Para isso, De Moivre utilizou pela primeira vez uma técnica extremamente poderosa, a das funções geradoras. Esta técnica, muito útil para estudar sucessões recorrentes, foi bastante desenvolvida por Euler (17071783), em seu livro clássico Introductio in Analysin Infinitorum, onde ele a utiliza para atacar o problema das partiçōes de um inteiro. O interesse de Euler por este problema surgiu devido a uma pergunta que the foi feita pelo matemático francês Phillipe Naudé, que trabalhava em Berlim, em uma carta, na qual, entre outras coisas, perguntava de quantas maneiras um número pode ser escrito como soma de inteiros positivos distintos. Esta pergunta, prontamente respondida por Euler, foi a origem da "teoria das partiçōes" ou "partitio numerorum", como escreveu Euler. Mas suas contribuições à Análise Combinatória não se limitaram a isso. Várias obras suas, muitas delas sobre probabilidades, contêm resultados importantes da Análise Combinatória. Em particular, devemos a ele o enunciado e a solução do Problema das Sete Pontes de Königsberg, um teorema da Teoria dos Grafos, parte muito importante, atualmente, da Análise Combinatória.

[^0]
[^0]:    *Fibonacci, também conhecido por Leonardo de Pisa (11757-1250?)

A Análise Combinatória tem tido um crescimento explosivo nas últimas décadas. A importância de problemas de enumeração tem crescido enormemente, devido a necessidades em teoria dos grafos, em análise de algoritmos, etc. Muitos problemas importantes podem ser modelados matematicamente como problemas de teoria dos grafos (problemas de pesquisa operacional, de armazenamento de informações em bancos de dados nos computadores, e também problemas de matemática "pura", como o famoso problema das 4 cores).

Já em 1937 o matemático húngaro-americano George Pólya (1887-1985) introduziu nova e importante técnica de enumeração, que se tem prestado às mais variadas aplicações, permitindo tratar, de maneira unificada, desde a enumeraçāo do número de isómeros de uma substância, até a enumeraçāo de grafos, principalmente árvores, resolvendo problemas que até então eram atacados somente por métodos "ad hoc". Como disse Pólya, sua teoria é uma maneira de enumerar configurações não- equivalentes relativamente a um grupo de permutações dado. Um exemplo simples de aplicação da teoria do Pólya é o de determinar o número de tetraedros regulares "diferentes" com faces pintadas com duas cores, preto e branco, por exemplo. Podemos ter um tetraedro todo preto, outro todo branco, um com uma face branca e as outras pretas, etc. Dois tetraedros são considerados "diferentes" se um deles não pode ser obtido do outro por meio de rotações.

Outra teoria importante de Combinatória foi criada pelo lógico inglês F. P. Ramsey (1903-1930); ela garante a existência de certas configurações. Um dos exemplos mais simples do chamado teorema de Ramsey afirma que se tivermos no plano um conjunto de $n$ pontos, com $n \geq 6$, no qual não há três pontos colineares, então, se unirmos todos os pontos dois a dois, usando duas cores distintas, por exemplo preto e branco, para traçar os segmentos de reta que unirão os pontos, então forçosamente teremos formado um triângulo cujos lados são todos da mesma cor (preto ou branco).

Diz-se geralmente que a Teoria das Probabilidades originouse com Blaise Pascal (1623-1662) e Pierre de Fermat (1601-1665), devido à curiosidade de um cavalheiro, o Chevalier de Méré, jogador apaixonado, que em cartas discutiu com Pascal problemas relativos à probabilidade de ganhar em certo jogos de cartas. Despertado seu interesse pelo assunto, Pascal correspondeu-se com Fermat sobre o que hoje chamaríamos de probabilidades finitas.

Mas em verdade a teoria elementar das probabilidades já tinha sido objeto de atenção bem antes. Levando em conta o fascínio que os jogos de azar sempre exerceram sobre os homens, estimulando-os a achar maneiras seguras de ganhar, não é de espantar que muito cedo problemas relativos a jogos de cartas ou de dados tenham atraido a atenção de pessoas com mentes mais especulativas. Já na Divina Comédia, de Dante Alighieri (12651321), há uma referência a probabilidades em jogos de dados. Em verdade, o desenvolvimento da Análise Combinatória deve-se em grande parte à necessidade de resolver problemas de contagem originados na teoria das probabilidades.

A primeira obra conhecida em que se estudam as probabilidades é o livro De Ludo Aleat, (Sobre os jogos de Azar), de Jerônimo Cardano (1501-1576), publicado em 1663. É possivel que o interesse de Cardano pelo assunto se deva a sua paixão pelos jogos de azar. Nas palavras de Isac Todhunter, em sua História da Teoria Matemática da Probabilidade, "O livro pode ser bem descrito como um manual para jogadores. Contém muito sobre jogos, com descrições de jogos e com as preocupações que se deve ter para se proteger de adversários dispostos a trapacear; a discussão relativa às probabilidades são parte pequena de seu tratado". Uma tradução para o inglês moderno do livro de Cardano encontra-se no livro Cardano, the Gambling Scholar, de Oysten Ore.

Na parte dedicada à probabilidade Cardano mostra, entre outras coisas, de quantas maneiras podemos obter um número, lançando dois dados. Assim, por exemplo, 10 pode ser obtido de 3 maneiras: 5 em cada dado, 6 no primciro e 4 no segundo, e 4 no

primeiro e 6 no segundo.
Além de Cardano, Johannes Kepler (1571-1630) fez algumas observações sobre probabilidades, em um livro publicado em 1606 (De Stella nova in pede Serpentarii), em que estuda as diferentes opiniões sobre o apararecimento de uma estrela brilhante em 1604 .

Também Galileu (1564-1642) preocupou-se com as probabilidades, estudando os jogos de dados, para responder à pergunta de um amigo: Com três dados, o número 9 e o número 10 podem ser obtidos de seis maneiras distintas, cada um deles. No entanto, a experiência mostra que 10 é obtido mais frequentemente do que 9. Como explicar isso? Galileu estudou cuidadosamente as probabilidades envolvidas c mostrou, corretamente que, de 216 casos possíveis, 27 são favoráveis ao aparecimento do número 10 e 25 são favoráveis ao aparecimento do número 9 .

Malgrado investigações destes precursores, a Teoria das Probabilidades só começa a se desenvolver realmente a partir dos trabalhos de Pascal. Já vimos como Pascal estudou o triângulo aritmético que leva seu nome. Ele o aplicou ao estudo dos jogos de cartas.

Christian Huygens (1629-1695) publicou em 1657 o primeiro tratado de Teoria das Probabilidades, o De Ratiociniis in Ludo Aleae.

A Teoria das Probabilidades não despertou logo grande interesse entre os matemáticos que se seguiram a Pascal e Fermat, os quais estavam atraídos pelas investigações relativas ao cálculo, criado por Newton e Leibnitz. No entanto, percebeu-se imediatamente a utilidade da Teoria das Probabilidades para estudar situações como taxas de mortalidade, prèmios de seguros, etc. São inúmeras, ainda no século XVIII, as publicações estatísticas sobre impostos, doenças, condenações, etc., organizadas pelos governos, que viram logo o poder deste instrumento de observação social. Em 1662, John Graunt (1620-1674) utiliza os registros de

falecimentos para determinar a taxa de mortalidade em Londres. Passou-se em seguida a utilizar a idéia de Graunt no cálculo de rendas vitalícias, que dependem da esperança de vida. A primeira tentativa séria de cálculo de rendas vitalícias é devida a Johan de Witt (1625-1672) juntamente com Johan Hudde (1628-1704), prefeito de Amsterdam, que consultavam frequentemente Huygens sobre o problema.

Outros se interessaram por este problema. O astrônomo Edmund Halley (1656-1742) publicou uma tabela de taxas de mortalidade em 1693, posteriormente utilizada por De Moivre. Euler (1710-1761) e Simpson (1687-1768) também estudaram este problema, que envolve matemática, economia e política. Os primeiros resultados estatísticos realmente utilizados (por quase um século, pelas companhias de seguros inglesas), são as tabelas calculadas por Richard Price (1723-1791) cm 1780, utilizando os registros de falecimento da diocese de Northampton.

No famoso livro de Jaime Bernoulli, Ars Cnjectandi, que já citamos, encontramos um teorema de importância decisiva em Teoria das Probabilidades. Conhecido como Teorema de Bernoulli, é também chamado de Lei dos Grandes Números, nome que lhe foi dado pelo matemático francês Siméon Poisson (1781-1840). Este teorema foi a primeira tentativa de deduzir medidas estatísticas a partir de probabilidades. Ele afirma, por exemplo, que se dois eventos são igualmente prováveis, após um grande número de experimentos eles terão sido obtidos aproximadamente o mesmo número de vezes. O teorema permite também deduzir qual a probabilidade de cada um dos eventos acontecer, sabendo como se comportaram em um grande número de experimentos. A Lei dos Grandes Números deu origem a discussōes conccituais ou filosóficas sobre o conceito de probabilidade.

Jaime Bernoulli foi o primeiro de uma longa linhagem de matemáticos e sábios de uma família suíça. Seu diário mostra que ele começou a interessar-se pelos problemas de combinatória e de probabilidades em torno de 1685. Manteve longa correspondência

sobre o assunto com Leibniz, que levantava objeções ao Teorema de Bernoulli.

Outro matemático que muito se dedicou à teoria das probabilidades e que, possivelmente, só perde para Laplace (1749-1827) em contribuições ao assunto, foi Abraham De Moivre. Protestante francês, foi obrigado a refugiar-se em 1685 na Inglaterra, onde viveu até sua morte. Matemático versátil, com trabalhos importantes em vários campos, era muito respeitado. Newton, por exemplo, já em seus últimos anos de vida, ao lhe perguntarem sobre um problema de matemática, respondeu "procure o Sr. De Moivre, ele conhece estas coisas melhor do que cu".

Além de várias investigações sobre probabilidades, De Moivre escrevel um tratado sobre o assunto que foi usado durante muito tempo, o Doutrina do Acaso, em que estão incluídos muitos de seus trabalhos. Em particular, ele desenvolve a teoria das sucessões recorrentes, e a usa para resolver vários problemas de probabilidades.

Devemos ainda citar o matemático inglês Thomas Bayes (1702- 1761), que iniciou as investigações sobre o problema de achar as probabilidades das causas de um evento observado.

A Teoria das Probabilidades contém muitos problemas interessantes, alguns dos quais conduzem a resultados inesperados ou à primeira vista paradoxais. Tem também dado origem a discussões filosóficas sobre o que é o acaso, o que são probabjidades. ctc. Um problema interessante, muito conhecido, é o chamado problema da agulha de Buffon*: Considere uma área plana, dividida em faixas de larguras iguais. a, por retas paralelas. Lance sobre esta região, ao acaso, uma agulha de comprimento $2 r$, com $2 r<a$. Qual a probabilidade de que a agulha corte uma das paralelas? O resultado, surpreendente à primeira vista, é $4 r / \pi a$.

Certamente o matemático que mais contribuiu para a teoria das probabilidades foi Laplace, famoso também por suas con-

[^0]
[^0]:    *Conteger Lende Lechere, Conde de Buffon (1707-1763), maturalista franciso

tribuições a outras áreas da matemática, como a mecánica analítica, onde atacou o problema da estabilidade do sistema solar. Seus inúmeros trabalhos sobre as probabilidades foram incorporados em seu monumental Tratado Analítico das Probabilidades, onde são discutidos inúmeros problemas de probabilidades, introduzidas técnicas poderosas, como a das funções geradoras, aproximações para probabilidades usando os métodos do cálculo integral, etc. Encontramos neste trabalho, em particular, a integral

$$
\int e^{-t^{2}} d t
$$

relacionada com a Distribuição Normal.

# 1.3 Conjuntos 

Certamente o leitor desta monografia está familiarizado com os rudimentos da teoria dos conjuntos. Assim, o propósito deste capítulo é simplesmente revisar rapidamente essas noções básicas c, ao mesmo tempo, fixar a notação que usaremos nos capítulos posteriores.

Letras maiúsculas, como por exemplo $A, B, \ldots, Y, Z$, indicarão conjuntos. A letra grega $\Omega$ (ômega) representará o conjunto universal em uma situação determinada. Letras minúsculas $a, b, \ldots, y, z, w$, indicarão elementos desses conjuntos.

A relação de pertencer será indicada pela letra grega $\in$ e escreveremos por exemplo, $a \in A$. O conjunto vazio será representado pela letra $\phi$. Um conjunto com um número reduzido de elementos scrá indicado simplesmente listando seus elementos. Por exemplo, o conjunto que consiste nos números 1,2 e 3 será representado por

$$
A=\{1,2,3\}
$$

\{1\} representa o conjunto que tem como único elemento o número 1. Um conjunto pode também ser descrito por uma propriedade $\pi$, comum a todos os seus elementos, e escreveremos

$$
A=\{x \mid x \text { tem a propriedade } \pi\}
$$

Por exemplo,

$$
A=\{x \mid x=2 k, k=1,2, \ldots\}
$$

descreve o conjunto dos inteiros pares positivos. Usaremos o símbolo \#A para representar o número de elementos do conjunto $A$, isto é, a cardinalidade de $A$.

Se todo elemento de um conjunto $A$ é também elemento de um conjunto $B$, diremos que $A$ é um subconjunto de $B$ e escreveremos simbolicamente $A \subset B$. Se $A \subset B$ mas existe um elemento $b \in B$ tal que $b \notin A$, ( $b$ não pertence a $A$ ), diremos que $A$ é um subconjunto próprio de B. A Figura 1.1 ilustra esta situação. Observe que o conjunto vazio é subconjunto de qualquer conjunto $A$. Com efeito, se isso não fosse verdade, deveria haver um elemento $x \in \phi$ tal que $x \notin A$, o que é impossivel.
![img-0.jpeg](img-0.jpeg)

Fig. 1.1

Dados dois conjuntos $A$ e $B$ indicaremos por $A \cup B$ o conjunto dos elementos que pertencem a $A$ on a $B$, isto é, o conjunto dos elementos que pertencem a pelo menos um dos conjuntos $A$ e $B_{i}$ Este conjunto é chamado uniào de $A$ com $H$. Simbolicamente,

$$
A \cup B=\{\omega \in \Omega \mid \omega \in A \quad \text { ou } \quad \omega \in B\}
$$

A parte sombreada da Figura 1.2 ilustra o conjunto $A \cup B$.
![img-1.jpeg](img-1.jpeg)

Fig. 1.2
A união de très conjunlos $A, B, C$ será representada por $A \cup B \cup C$.

$$
A \cup B \cup C=\{\omega \in \Omega \mid \omega \in A \quad \text { ou } \quad \omega \in B \quad \text { ou } \quad \omega \in C\}
$$

Mais geralmente, a união de $n$ conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ é definida analogamente e representada por

$$
\bigcup_{i=1}^{n} A_{i}
$$

Dados dois conjuntos $A$ e $B$, definimos o conjunto intersecção de $A$ e $B$ como o conjunto dos elementos que pertencem simultaneamente a $A$ e a $B$, ou seja,

$$
A \cap B=\{\omega \in \Omega \mid \omega \in A \quad \text { e } \quad \omega \in B\}
$$

A parte sombreada da Figura 1.3 ilustra a intersecção de $A$ e $B$.
![img-2.jpeg](img-2.jpeg)

Fig. 1.3

No caso de termos por exemplo trés conjuntos, $A, B$ e $C$, a intersecção é representada por $A \cap B \cap C$ :

$$
A \cap B \cap C=\{\omega \in \Omega \mid \omega \in A \quad \text { e } \quad \omega \in B \quad \text { e } \quad \omega \in C\}
$$

A intersecção de $n$ conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ é representada por

$$
\bigcap_{i=1}^{n} A_{i}
$$

Dizemos que dois conjuntos $A$ e $B$ são disjuntos se $A \cap B=$ $\phi$. Quando temos mais de dois conjuntos, dizemos que eles são disjuntos quando forem disjuntos tomados 2 a 2. A Figura 1.4 ilustra o caso de très conjuntos disjuntos.

![img-3.jpeg](img-3.jpeg)

Fig. 1.4
Dados um conjunto $A$, chamaremos conjunto complementar de $A$ o conjunto dos elementos de $\Omega$ que não pertencem a $A$. Simbolicamente

$$
A^{c}=\{\omega \in \Omega \mid \omega \notin A\}
$$

A parte sombreada da Figura 1.5 indica o complementar de $A$.
![img-4.jpeg](img-4.jpeg)

Fig. 1.5
Dados dois conjuntos $A$ e $B$, o conjunto

$$
\text { - } A \cap B^{c}=\{\omega \in \Omega \mid \omega \in A \quad \text { e } \quad \omega \notin B\}
$$

é chamado conjunto diferença de $A$ e $B$, é representado geralmente por $A-B$. A parte sombreada da Figura 1.6 mostra a diferença de $A$ e $B$.
![img-5.jpeg](img-5.jpeg)

Fig. 1.6
Se $B \subset A$, a diferença $A-H$ é chamada diferença própria.
O Teroema 1, a seguir, lista as propriedades mais importantes que relacionam os conceitos definidos anteriormente.

# Teorema 1. 

1. Para todo conjunto $A \subset \Omega, A \cup \phi=A, A \cap \phi=\phi$.
2. $A \subset B$ se e somente se $A \cup B=B$.
3. $A \subset B$ se e somente se $A \cap B=A$.
4. $A \cup(B \cup C) \quad(A \cup B) \cup C$.
5. $A \cap(B \cap C)=(A \cap B) \cap C$.
6. $A \cap(B \cup C)=(A \cap B) \cup(A \cap C)$.
7. $A \cup(B \cap C)=(A \cup B) \cap(A \cup C)$.
8. $A \cup A^{c}=\Omega, A \cap A^{c}=\phi, \phi^{c}=\Omega, \Omega^{c}=\phi$.
9. $\left(A^{c}\right)^{c}=A ; A \subset B$ se e somente se $B^{c} \subset A^{c}$.
10. $(A \cup B)^{c}=A^{c} \cap B^{c}$.
11. $(A \cap B)^{c}=A^{c} \cup B^{c}$.

A demonstração deste teorema é deixada como exercício.
Introduximos agora a noção de produto cartesiano de dois conjuntos. Dados dois conjuntos $A$ e $B$, chamaremos de produto

cartesiano de $A$ por $B$ o conjunto de pares ordenados $(a, b)$, onde a é um elemento de $A$ e $b$ é um elemento de $B$. Simbolicamente

$$
A \times B=\{(a, b) \mid a \in A, b \in B\}
$$

Por exemplo. se $A=\{1,2\}$ e $B=\{1,2,3\}$, resulta que

$$
A \times B=\{(1,1),(1,2),(1,3),(2,1),(2,2),(2,3)\}
$$

O produto cartesiano de três conjuntos é definido de forma semelhante tomando ternos em lugar de pares. Em geral, se temos " conjuntos $A_{1}, A_{2}, \ldots, A_{n}$, o produto cartesiano $A_{1} \times A_{2} \times \cdots \times$ $A_{n}$ é definido como o conjunto das $n$-uplas $\left(u_{1}, u_{2}, \ldots, a_{n}\right)$, onde $u_{1} \in A_{1}, u_{2} \in A_{2}, \ldots, a_{n} \in A_{n}$.

A última noção deste capítulo é a de partiçāo de um conjunto.

Definição: Seja $A$ um conjunto finito não-vazio. Uma partição de $A$ é uma familia de conjuntos $A_{1}, A_{2}, \ldots, A_{k}$, todos não-vazios, e tais que:

1) $A_{1} \cup A_{2} \cdots \cup A_{k}=A$
2) $A_{i} \cap A_{j}-\phi \quad$ se $i \neq j$.

Ou seja. os conjuntos $A_{1}, A_{2}, \ldots A_{k}$ são disjuntos dois-adois e sua uniào é o conjunto $A$. Dizemos também que $A$ foi particionudo pelos conjuntos $A_{1}, A_{2}, \ldots, A_{k}$.

# 2. Combinações e Permutações 

### 2.1 Introdução

Neste capítulo são apresentadas as ferramentas básicas que nos permitem determinar o número de elementos de conjuntos formados de acordo com certas regras, sem que seja necessário enumerar seus elementos.

A procura por técnicas de contagem está diretamente vinculada à história da Matemática e à forma pela qual as pessoas tem seu primeiro contato com esta disciplina. A primeira técnica matemática aprendida por uma criança é "contar", ou seja, enumerar os elementos de um conjunto de forma a determinar quantos são os seus elementos. As operaçōes aritméticas são também motivadas (e aprendidas pelas crianças) através de sua aplicação a problemas de contagem.

Por exemplo, a operação de adição é sempre introduzida em conexão com um problema de contagem:

![img-6.jpeg](img-6.jpeg)

Fig. 2.1
A figura 2.1 ilustra um princípio básico de contagem, que podemos chamar de "Princípio de Adição":

Se $A$ e $B$ sâo dois conjuntos disjuntos, com $p$ e q elementos, respectivamente, entäo $A \cup B$ possui $p+q$ elementos.

A seguir apresentamos o "Princípio da Multiplicação", que, ao lado do "Princípio da Adição", constitui a ferramenta básica para resolver os problemas de contagem abordados a nível de $2^{\circ}$ grau. Para motivar tal princípio, consideramos o exemplo a seguir.

Numa sala há 3 homens e 4 mulheres. De quantos modos é possível selecionar um casal homem-mulher? Chamando os homens de $h_{1}, h_{2}, h_{3}$ e as mulheres de $m_{1}, m_{2}, m_{3}, m_{4}$ é fácil ver que há 4 casais nos quais o homem é $h_{1}$, outros 4 nos quais o homem é $h_{2}$ e outros 4 nos quais o homem é $h_{3}$. O número de casais é portanto $4+4+4=3 \times 4=12$.

O exemplo acima ilustra o Principio Fundamental da Enumeração ou Principio da Multiplicação, o qual diz:

Se uma decisão $d_{1}$ pode ser tomada de $x$ maneiras e se, uma - vez tomada a decisão $d_{1}$, a decisão $d_{2}$ puder ser tomada de $y$ maneiras então o número de maneiras de se tomarem as decisões $d_{1}$ e $d_{2}$ é $x y$.

Assim, no exemplo, para formar um casal devemos tomar as decisões
$d_{1}:$ escolha do homem;
$d_{2}:$ escolha da mulher.
Como $d_{1}$ pode ser tomada de 3 maneiras e, depois disso, $d_{2}$ pode ser tomada de 4 manciras, o número de maneiras de se formar um casal (isto é, de tomar as decisões $d_{1}$ e $d_{2}$ ) é $3 \times 4=12$.

Note que o uso do Principio de Multiplicação permite obter o número de elementos do conjunto

$$
\begin{aligned}
& \left\{h_{1} m_{1}, h_{1} m_{2}, h_{1} m_{3}, h_{1} m_{4}, h_{2} m_{1}, h_{2} m_{2}\right. \\
& \left.h_{2} m_{3}, h_{2} m_{4}, h_{3} m_{1}, h_{3} m_{2}, h_{3} m_{3}, h_{3} m_{4}\right\}
\end{aligned}
$$

constituido por todos os casais possíveis, sem que seja necessário enumerar seus elementos.

Exemplo 2.1: Para fazer uma viagem Rio-S.Paulo-Rio, posso usar como transporte o trem, o ônibus ou o avião. De quantos modos posso escolher os transportes se não desejo usar na volta o mesmo meio de transporte usado na ida?

Solução: Há 3 modos de escolher o transporte de ida. Depois disso, há duas alternativas para a volta. A resposta é $3 \times 2=6$.

Exemplo 2.2: Uma bandeira é formada por quatro listras, que devem ser coloridas usando-se apenas as cores amarelo, branco e cinza, não devendo listras adjacentes ter a mesma cor. De quantos modos pode ser colorida a bandeira?

Solução: A primeira listra pode ser colorida de 3 modos, a segunda de 2 modos (não podemos usar a cor empregada na primeira listra), a terceira de 2 modos (não podemos usar a cor empregada na segunda listra) e a quarta de 2 modos (não podemos usar a cor empregada na terceira listra). A resposta é $3 \times 2 \times 2 \times 2=24$.

Exemplo 2.3: Quantos números naturais de três algarismos distintos (na base 10) existem?

Solução: O primeiro algarismo pode ser escolhido de 9 modos (não podemos usar o zero!), o segundo algarismo de 9 modos (não podemos usar o algarismo utilizado anteriormente) e o terceiro de 8 modos (não podemos usar os dois algarismos já empregados anteriormente). A resposta é $9 \times 9 \times 8=648$.

É interessante observar no exemplo 2.3 que se começássemos pelo último algarismo teríamos 10 modos de escolher o último algarismo, 9 modos de escolher o penúltimo algarismo (não podemos usar o algarismo empregado anteriormente) e ... e agora estamos diante de um problema: de quantos modos podemos escolher o primeiro algarismo? A resposta é: depende! Se o algarismo zero tiver sido usado em alguma das últimas casas, a resposta é 8 (não podemos usar os dois algarismos já utilizados anteriormente). Caso contrário, a resposta é 7 (não podemos usar nem o zero nem os dois algarismos usados anteriormente).

É claro que essa dificuldade não teria ocorrido se tivéssemos começado pela escolha do primeiro algarismo do número, escolta essa que é mais problemática do que a dos dois outros algarismos (o primeiro algarismo não pode ser zero!).

Daí a recomendação:
Pequenas dificuldades adiadas costumam transformar-se em grandes dificuldades. Se alguma decisão é mais complicada que as demais, ela deve ser tomada em primeiro lugar.

Exemplo 2.4: Quantos números naturais de 4 algarismos (na base 10), que sejam menores que 5000 e divisíveis por 5 , podem ser formados usando-se apenas os algarismos $2,3,4$ e 5 ?

Solução: Temos:

| Último algarismo | $\longrightarrow$ | 1 modo (tem que ser 5) |
| :--: | :--: | :--: |
| Primeiro algarismo | $\longrightarrow$ | 3 modos (não pode ser 5) |
| Segundo algarismo | $\longrightarrow$ | 4 modos |
| Terceiro algarismo | $\longrightarrow$ | 4 modos |

A resposta é $1 \times 3 \times 4 \times 4 \quad 48$.
Exemplo 2.5: As placas dos automóveis são formadas por duas letras ( $K, Y$ e $W$ inclusive) seguidas por quatro algarismos. Quantas placas podem ser formadas?

Solução: Cada letra pode ser escolhida de 26 modos e cada algarismo de 10 modos distintos. A resposta é

$$
26 \times 26 \times 10 \times 10 \times 10 \times 10=6760000
$$

Exemplo 2.6: Quantos são os números naturais pares que se escrevem (na base 10) com três algarismos distintos?

Solução: O último algarismo do número pode ser escolhido de 5 modos ( $0,2,4,6$ ou 8 ). O primeiro algarismo pode ser escolhido de ... depende! Se o zero foi usado como último algarismo, o primeiro algarismo pode ser escolhido de 9 modos (não podemos usar o algarismo já empregado na última casa). Se o zero não foi usado como último algarismo, o primeiro algarismo só pode ser escolhido de 8 modos (não podemos usar nem o zero nem o algarismo já empregado na última casa).

Para vencer este impasse, temos duas alternativas:
a) "abrir" o problema em casos (que é a alternativa mais natural). Contamos separadamente os números que têm zero como último algarismo e aqueles cujo último algarismo é diferente de zero.

Terminando em zero temos 1 modo de escolher o último algarismo, 9 modos de escolher o primeiro e 8 modos de escolher o do meio, num total de $1 \times 9 \times 8=72$ números.

Terminando em um algarismo diferente de zero temos 4 modos de escolher o último algarismo ( $2,4,6$ ou 8 ), 8 modos de escolher o primeiro algarismo (não podemos usar nem o zero nem o algarismo já usado na última casa) e 8 modos de escolher o algarismo no meio (não podemos usar os dois algarismos já empregados nas casas extremas). Logo, temos $4 \times 8 \times 8=256$ números

terminados em um algarismo diferente de zero. A resposta é, portanto $72 \pm 256=328$.
b) Ignorar uma das restriçöes (que é uma alternativa mais sofisticaída). Ignorando o fato de zero não poder ser primeiro algarismo, teríamos 5 modos de escolher o último algarismo, 9 modos de escolher o primeiro e 8 modos de escolher o do meio, num total de $5 \times 8 \times 9=360$ números. Esses 360 número incluem números começados por zero, que devem ser descontados. Começando em zero temos 1 modo de escolher o primeiro algarismo ( 0 ), 4 modos de escolher o último ( $2,4,6$ ou 8 ) e 8 modos de escolher o do meio (não podemos usar os dois algarismos já empregados nas casas extremas), num total de $1 \times 4 \times 8=32$ números. A resposta é, portanto, $360-32=328$ números.

É claro também que poderíamos ter resolvido o problema determinando todos os números de 3 algarismos distintos $(9 \times 9 \times$ $8=648$ ) e abatendo os números ímpares de 3 algarismos distintos ( 5 na última casa, 8 na primeira e 8 na segunda, num total de $5 \times 8 \times 8=320$ números). A resposta scría $648-320=328$ números.

# Exercícios 

1. Quantas palavras contendo 3 letras diferentes podem ser formadas com um alfabeto de 26 letras?
2. Quantos são os gabaritos possíveis de um teste de 10 questões de múltipla-escolha, com cinco alternativas por questão?
3. Quantos inteiros há entre 1000 e 9999 cujos algarismos são distintos?
4. De quantos modos diferentes podem ser escolhidos um presidente e um secretário de um conselho que tem 12 membros?
5. De quantos modos 3 pessoas podem sentar-se em 5 cadeiras em fila?

6. Quantos números de quatro dígitos são maiores que 2400 e:
a) tèm todos os dígitos diferentes.
b) não têm dígitos iguais a 3,5 ou 6 .
c) tèm as propriedades a) e b) simultâneamente.
7. O conjunto $A$ possui 4 elementos e o conjunto $B$ possui 7 elementos. Quantas são as funçöes $f: A \rightarrow B$ ? Quantas são as funções injetoras $f: A \rightarrow B$ ?
8. Quantos divisores naturais possui o número 360 ? Quantos são pares?
9. Quantos são os números naturais de 4 dígitos que possuem pelo menos dois dígitos iguais?
10. Quantos subconjuntos possui um conjunto que tem $n$ elementos?
11. De quantos modos podemos arrumar 8 torres iguais em um tabuleiro de xadrez $(8 \times 8)$ de modo que não haja duas torres na mesma linha nem na mesma coluna?
12. Em uma banca há 5 exemplares iguais da revista $A, 6$ exemplares iguais da revista B e 10 exemplares iguais da revista C. Quantas coleções não vazias de revistas dessa banca é possível formar?
13. De um baralho comum ( 52 cartas) sacam-se sucessivamente e sem reposição très cartas. Quantas são as extraçöes nas quais a primeira carta é de cópas, a segunda é um rei e a terceira não é uma dama?
14. Quantos números diferentes podem ser formados multiplicando alguns (ou todos) dos números $1,5,6,7,7,9,9,9$ ?
15. Um vagão de metrô tem 10 bancos individuais, sendo 5 de frente e 5 de costas. De 10 passageiros, 4 preferem sentar de frente, 3 preferem sentar de costas e os demais não têm preferência. De quantos modos os passageiros podem se sentar, respeitando-se as preferências?

16. Há duas estradas principais da cidade $A$ até a cidade $B$, ligadas por 10 estradas secundárias. como na ligura 2.2. Quantas rotas livres de auto-interseções há de $A$ até $B$ ?
![img-7.jpeg](img-7.jpeg)

Fig. 2.2
17. Quantos números inteiros entre 100 e 999 são impares e possurm très digitos distintos?
18. Escrevem-se os inteiros de 1 até 222222 . Quantas vezes o algarismo zero é escrito?
19. Quantos sāo os números de 5 algarismos, na base 10 :
a) nos quais o algarismo 2 figura?
b) nos quais o algarismo 2 não figura?
20. Em um concurso há très candidatos e cinco examinadores, devendo cada examinador votar em un candidato. De quantos modos os votos podem ser distribuidos?
21. O código morse usa "palavras" contendo de 1 a 4 "letras", as "letras" sendo ponto e traço. Quantas "palavras" existem no código morse?
22. Fichas podem ser azuis, vermelhas ou amarclas; circulares, retangulares ou triangulares: finas ou grossas. Quantos tipos de fichas existem?

23. Escrevem-se números de cinco dígitos (inclusive os começados por zero) em cartões. Como 0,1 e 8 não se alteram de cabeça para baixo e como 6 de cabeça para baixo se transforma em 9, um só cartão pode representar dois números (por exemplo. 06198 e 86190). Qual é o número mínimo de cartões para representar todos os números de cinco dígitos?
24. No Senado Federal, o Distrito Federal e os 26 estados da federação têm 3 representantes cada. Deve-se formar uma comissão de modo que todos os estados e o Distrito Federal estejam representados por 1 ou 2 senadores. De quantos modos essa comissão pode ser formada?
25. a) Qual é a soma dos divisores inteiros e positivos de 720 ?
b) De quantos modos 720 pode ser decomposto em um produto de dois inteiros positivos?
c) De quantos modos 720 pode ser decomposto em um produto de três inteiros positivos?
d) De quantos modos 144 pode ser decomposto em um produto de dois inteiros positivos?
26. a) Quantas são as palavras de 5 letras distintas de um alfabeto de 26 letras nas quais a letra $A$ figura mas não é a letra inicial da palavra?
b) Refaça o item a) suprimindo a palavra distintas do enunciado.

27. A figura 2.3 mostra um mapa com 4 paises
![img-8.jpeg](img-8.jpeg)

Fig 2.3
a) De quantos modos esse mapa pode ser colorido (cada país com uma cor, paises com uma linha fronteira comum não podem ter a mesma cor) se dispomos de $\lambda$ cores diferentes?
b) Qual o menor valor de $\lambda$ que permite colorir o mapa?
28. Refaça o problema anterior para o mapa na figura 2.4
![img-9.jpeg](img-9.jpeg)

Fig 2.4

29. a) De quantos modos é possivel colocar um rei regro e um rei branco em casas não adjacentes de un tabuleiro de xadrez $(8 \times 8)$ ?
b) Qual seria a resposta se fossem dois reis brancos iguais?

# 2.2 Permutações Simples 

Dados $n$ objetos distintos $a_{1}, a_{2}, \ldots, a_{n}$. de quantos modos é possível ordená-los?

Por exemplo, para os objetos 1.2 .3 há 6 ordenaçōes: 123 , $132,213,231,312$ e 321 . No caso geral temos $n$ modos de escolher o objeto que ocupará o primeiro lugar. $n-1$ modos de escolher o que ocupará o segundo lugar. ..., 1 modo de escolher o objeto que ocupará o último lugar. Portanto,

O número de modos de ordenar " objetos distintos é

$$
n(n-1) \cdots 1=n!
$$

Cada ordenação dos $n$ objetos é chamada uma permutaçäo simples de $n$ objetos e o número de permutaçōes simples de $n$ objetos distintos é representado por $P_{n}$. Assim, $P_{n}=n$ ! (Já que $0!=1$, define-se $P_{0}=1$ ).

Exemplo 2.7: Quantos são os anagramas da palavra PRÁTICO?
Solução: Cada anagrama de PRÁTICO nada mais é que uma ordenação das letras $P . R$. A. T. I. C. O. Assini o número de anagramas de PRÁTICO é $P_{7}=7!=5040$.

Exemplo 2.8: Quantos são os anagramas da palavra PRÁTICO que começam e terminam por consoante?

Solução: A consoante inicial pode ser escoihida de 4 maneiras. a consoante final de 3 manciras e as 5 letarass restantes podem

ser arrumadas entre essas duas consoantes de $P_{5}=5$ ! modos. A resposta é $4 \times 3 \times 5!=1440$.

Excmplo 2.9: De quantos modos 5 rapazes e 5 moças podem se sentar em 5 bancos de dois lugares cada, de morlo que em cada banco fiquem um rapaz e uma moça?

Soluçäo: O primeiro rapaz pode escolher seu lugar de 10 modos, o segundo de 8 modos, o terceiro de 6 modos, o quarto de 4 modos e o quinto de 2 modos. Colocados os rapazes, temos que colocar as 5 moças nos 5 lugares que sobraram, o que pode ser feito de 5 ! modos. A resposta é $10 \times 8 \times 6 \times 4 \times 2 \times 5!=460800$.

Exemplo 2.10: De quantos modos podemos formar uma roda com 5 crianças?
![img-10.jpeg](img-10.jpeg)

Fig. 2.5
Solução: À primeira vista parece que para formar uma roda com as cinco crianças basta escolher uma ordem para elas, o que poderia ser feito de $5!=120$ modos. Entretanto, as rodas $A B C D E$ e $E A B C D$ são iguais, pois na roda o que importa é a posição relativa das crianças entre si e a roda $A B C D E$ pode ser "virada" na roda $E A B C D$. Como cada roda pode ser "virada" de cinco modos, a nossa contagem de 120 rodas contou cada roda 5 vezes c a resposta é $120 / 5=24$.

Exemplo 2.11: De quantos modos podemos dividir 8 pessoas em dois grupos de 4 pessoas cada?

Solução: A divisão pode ser feita colocando as 8 pessoas em fila e dividindo-as de modo que um dos grupos seja formado pelas 4 primeiras pessoas e o outro pelas 4 últimas. Como há 8 ! modos de colocar as pessoas em fila, a resposta parece ser 8 !

Entretanto consideremos a divisão abcd/efgh. Ela é identica à divisão $c f g h / a b c d$ (os grupos formados são os mesmos: um grupo é $\{a, b, c, d\}$ e o outro é $\{c, f, g, h\})$. Não obstante, na nossa contagem de 8 !, essas divisões foram contadas como se fossem distintas. Além disso, divisões como abcd/c fgh e cadb/efgh, que diferem pela ordem dos elementos em cada grupo, apesar de idênticas foram contadas como se fossem distintas. Cada divisão foi contada $2 \times 4!\times 4$ ! vezes ( 2 por causa da ordem dos grupos; 4 ! por causa da ordem dos elementos no $1^{\circ}$ grupo e 4 ! por causa da ordem dos elementos no $2^{\circ}$ grupo).

Se contamos 8 ! divisões e cada divisão foi contada $2 \cdot 4!\cdot 4$ ! vezes, o número de divisões é $\frac{8!}{2 \times 4!\times 4!}=35$.

# Exercícios 

1. Quantos são os anagramas da palavra CAPÍTULO:
a) que começam por consoante e terminam por vogal?
b) que têm as letras $C, A, P$ juntas nessa ordem?
c) que têm as letras $C, A, P$ juntas em qualquer ordem?
d) que têm as vogais e as consoantes intercaladas?
e) que têm a letra $C$ no $1^{\circ}$ lugar e a letra $A$ no $2^{\circ}$ lugar?
f) que têm a letra $C$ no $1^{\circ}$ lugar ou a letra $A$ no $2^{\circ}$ lugar?
g) que têm a letra $C$ no $1^{\circ}$ lugar ou a letra $A$ no $2^{\circ}$ lugar ou a letra $P$ no $3^{\circ}$ lugar?
2. Permutam-se de todos os modos possíveis os algarismos 1 , $2,4,6,7$ 'e escrevem-se os números assim formados em ordem crescente.

a) que lugar ocupa o número 62417 ?
b) qual o múmero que ocupa o 669 lugar?
c) qual o $200^{\circ}$ algarismo escrito?

- d) qual a soma dos números assim formados?

3. De quantos modos é possivel sentar 7 pessoas em cadeiras em fila de modo que duas determinadas pessoas dessas 7 não fiquem juntas?
4. Se $A$ é um conjunto com $n$ elementos, quantas são as funções $f: A \rightarrow A$ bijeloras?
5. De quantos modos é possivel colocar em uma prateleira 5 livros de matemática, 3 de física e 2 de estatística, de modo que livros de um mesmo assunto permaneçam juntos?
6. Quantas são as permutações dos números $(1,2, \ldots, 10)$ nas quais o 5 está situado à direita do 2 e à esquerda do 3 , embora não necessariamente em lugares consecutivos?
7. De quantos modos podemos dividir 12 pessoas:
a) em dois grupos de 6 ?
b) em tres grupos de 4 ?
c) em um grupo de 5 e um grupo de 7 ?
d) em seis grupos de 2 ?
e) em dois grupos de 4 e dois grupos de 2 ?
8. De quantos modos $r$ rapazes e $m$ moças podem se colocar em fila de modo que as moças fiquem juntas?
9. Delegados de 10 países devem se sentar em 10 cadeiras em fila. De quantos modos isso pode ser feito se os delegados do Brasil e de Portugal devem sentar juntos e o do Iraque e o dos Estados Unidos não podem sentar juntos?
10. Um cubo de madeira tem uma face de cada cor. Quantos dados diferentes podemos formar gravando números de 1 a 6 sobre essas faces?

11. Quantos dados diferentes podemos formar gravando números de 1 a 6 sobre as faces indistinguíveis de um cubo de madeira?
12. Resolva o problema anterior para:
a) números de 1 a 4 , tetraedro regular;
b) números de 1 a 8 , octacdro regular;
c) números de 1 a 12 , dodecaedro regular;
d) números de 1 a 20 , icosaedro regular;
e) números de 1 a 8 , prisma hexagonal regular;
f) números de 1 a 5 , pirâmide quadrangular regular.
13. Um campeonato é disputado por 12 clubes em rodadas de 6 jogos cada. De quantos modos é possível selecionar os jogos de primeira rodada?
14. Quantas são as permutações simples dos números $1,2, \ldots, n$ nas quais o elemento que ocupa a $k$ - ésima posição é inferior a $k+4$, para todo $k$ ?
15. Quantas são as permutações simples dos números $1,2, \ldots, n$ nas quais o elemento que ocupa a $k$ - ésima posição é maior que $k-3$, para todo $k$ ?

# 2.3 Combinações Simples 

De quantos modos podemos escolher $p$ objetos distintos entre $n$ objetos distintos dados? Ou, o que é o mesmo, quantos são os subconjuntos com $p$ elementos do conjunto $\left\{a_{1}, a_{2}, \ldots, a_{n}\right\}$ ?

Cada subconjunto com $p$ elementos é chamado de uma combinação simples de classe $p$ dos $n$ objetos $a_{1}, a_{2}, \ldots, a_{n}$. Assim, por exemplo, as combinações simples de classe 3 dos objetos $a_{1}, a_{2}, a_{3}, a_{4}, a_{5}$ são
$\left\{a_{1}, a_{2}, a_{3}\right\} \quad\left\{a_{1}, a_{2}, a_{4}\right\} \quad\left\{a_{1}, a_{2}, a_{5}\right\} \quad\left\{a_{1}, a_{3}, a_{4}\right\} \quad\left\{a_{1}, a_{3}, a_{5}\right\}$
$\left\{a_{1}, a_{4}, a_{5}\right\} \quad\left\{a_{2}, a_{3}, a_{4}\right\} \quad\left\{a_{2}, a_{3}, a_{5}\right\} \quad\left\{a_{2}, a_{4}, a_{5}\right\} \quad\left\{a_{3}, a_{4}, a_{5}\right\}$.

O número de combinações simples de classe $p$ de $n$ objetos é representado por $C_{n}^{p}$. Assim, $C_{5}^{3}=10$.

Analisemos esta resposta: a escolha do $1^{\circ}$ elemento da combinação pode ser feita de 5 modos; a do $2^{\circ}$, de 4 modos e a do $3^{\circ}$, de 3 modos. A resposta parece ser $5 \times 4 \times 3=60$. Entretanto, se pensarmos numa combinação, por exemplo $\left\{a_{1}, a_{2}, a_{3}\right\}$, verificamos que as combinações $\left\{a_{1}, a_{2}, a_{3}\right\},\left\{a_{1}, a_{3}, a_{2}\right\},\left\{a_{2}, a_{1}, a_{3}\right\}$, etc... são idênticas c foram contadas como se fossem diferentes. Com efeito, se dissemos que há 5 modos de escolher o $1^{\circ}$ elemento da combinação é porque estamos considerando as escolhas $a_{1}$ e $a_{2}$ como diferentes e portanto estamos contando $\left\{a_{1}, a_{2}, a_{3}\right\}$ como diferente de $\left\{a_{2}, a_{1}, a_{3}\right\}$. Em suma, na resposta 60 estamos contando cada combinação uma vez para cada ordem de escrever seus elementos. Como em cada combinação us elementos podem ser escritos em $P_{3}=3!=6$ ordens, cada combinação foi contada 6 vezes. Logo, a resposta é $60 / 6=10$.

No caso geral temos

$$
C_{n}^{p}=\frac{n(n-1) \cdots(n-p+1)}{p!}, \quad 0<p \leq n
$$

e $C_{n}^{0}=1$.
Una expressāo alternativa pode ser obtida multiplicando o numeraior e o denominador por $(n-p)$ !. Obtemos

$$
C_{n}^{p}=\frac{n!}{p!(n-p)!}, \quad 0 \leq p \leq n
$$

Exemplo 2.12: Quantas saladas contendo exatamente 4 frutas podemos formar se dispomos de 10 frutas diferentes?
Solução: Para formar uma salada basta escolher 4 das 10 frutas, o que pode ser feito de $C_{10}^{4}=\frac{10.9 \cdot 8 \cdot 7}{4!}=210$ modos.
Exemplo 2.13: Marcam-se 5 pontos sobre uma reta $R$ e 8 pontos sobre uma reta $R^{\prime}$ paralela a $R$. Quantos triângulos existem com vértices em 3 desses 13 pontos?

Solução: Para formar um triângulo ou tomamos um vértice cm $R$ e dois em $R^{\prime}$ ou tomamos um vértice em $R^{\prime}$ e dois em $R$. O número de triângulos do $1^{\circ}$ tipo é $5 \cdot C_{8}^{2}$ e o do $2^{\circ}$ tipo é $8 \cdot C_{5}^{2}$. A resposta é

$$
5 \cdot C_{8}^{2}+8 \cdot C_{5}^{2} \because 5 \cdot \frac{8 \cdot 7}{2!}+8 \cdot \frac{5 \cdot 4}{2!}=140+80=220
$$

Poderiamos também pensar assim:
Para formar um triângulo devemos escolher três pontos, não situados na mesma reta, entre os treze pontos dados. O número de modos de escolher 3 dos 13 pontos é $C_{13}^{3}$. Desse total devemos retirar as $C_{5}^{3}$ escolhas de 3 pontos em $R$ e as $C_{8}^{3}$ escolhas possíveis de 3 pontos em $R^{\prime}$. A resposta é

$$
C_{13}^{3}-C_{5}^{3}-C_{8}^{3}=286-10-56=220
$$

Exemplo 2.14: De quantos modos podemos escolher 6 pessoas, incluindo pelo menos duas mulheres, em um grupo de 7 homens e 4 mulheres?

Solução: As alternativas são:

$$
\begin{array}{ll}
4 \text { homens, } & 2 \text { mulheres } \\
3 \text { homens, } & 3 \text { mulheres } \\
2 \text { homens, } & 4 \text { mulheres }
\end{array}
$$

A resposta é

$$
C_{7}^{4} \cdot C_{4}^{2}+C_{7}^{3} \cdot C_{4}^{3}+C_{7}^{2} \cdot C_{4}^{4}=35 \cdot 6+35 \cdot 4+21 \cdot 1=371
$$

Poderiamos também contar toda as escolhas de 6 pessoas $\left(C_{11}^{6}\right)$ e abater as escolhas sem mulheres $\left(C_{7}^{6}\right)$ e com apenas uma mulher $\left(4 \cdot C_{7}^{5}\right)$. A resposta é

$$
C_{11}^{6}-C_{7}^{6}-4 C_{7}^{5}=462-7-84=371
$$

Um erro muito comum é o seguinte: Como o grupo de 6 pessoas deve conter pelo menos duas mulheres, primeiramente escolhem-se duas mulheres $\left(C_{4}^{2}\right)$, e depois escolhem-se 4 pessoas quaisquer entre as 9 que sobraram $\left(C_{4}^{5}\right)$. Assim, obtem-se a resposta (errada) $C_{4}^{2} \cdot C_{9}^{5}=6 \times 126=756$. A explicação do erro é simples.

Considere, por exemplo, uma seleção com 3 mulheres e 3 homens, $M_{1} M_{2} M_{3} H_{1} H_{2} H_{3}$. Essa seleção foi contada 3 vezes. Uma quando $M_{1}$ e $M_{2}$ foram as mulheres escolhidas inicialmente, outra quando $M_{1}$ e $M_{3}$ foram as mulheres escolhidas inicialmente etc... Já uma seleção com as 4 mulheres, por exemplo, $M_{1} M_{2} M_{3}$ $M_{4} H_{1} H_{2}$ foi contada 6 vezes e obtem-se uma resposta crrada muito maior que a resposta correta.

Exemplo 2.15: De quantos modos podemos dividir 8 pessoas em 2 grupos de 1 pessoas cada?

Soluçäo: O primeiro grupo pode ser escolhido de $C_{8}^{4}$ modos. Escohido o $1^{\circ}$ grupo, sobram 1 pessoas e só há 1 modo de formar o segundo grupo. A resposta parece ser $C_{8}^{4} \times 1$. Entretanto, contamos cada divisão duas vezes. Por exemplo, $\{a, b, c, d\}\{c, f, g, h\}$ é idêntica a $\{c, f, g, h\}\{a, b, c, d\}$ e foi contada como se fosse diferente. A resposta é

$$
\frac{C_{8}^{4} \times 1}{2}=35
$$

É interessante comparar esta solução com a do exemplo 2.11.

# Exercícios 

1. Uma comissão formada por 3 homens e 3 mulheres deve ser escolhida em um grupo de 8 homens e 5 mulheres.
a) Quantas comissões podem ser formadas?

b) Qual seria a resposta se um dos homens não accitasse participar da comissão se nela estivesse determinada mulher?
2. Para a seleção brasileira foram convocados dois goleiros, 6 zagueiros, 7 meios de campo e 4 atacantes. De quantos modos é possível escalar a seleção com 1 golciro, 4 zagueiros, 4 meios de campo e 2 atacantes?
3. Quantas diagonais possui um polígono de $n$ lados?
4. Quantas diagonais possui:
a) um octaedro regular?
b) um icosaedro regular?
c) um dodecaedro regular?
d) um cubo?
e) um prisma hexagonal regular?
5. Tem-se 5 pontos sobre uma reta $R$ e 8 pontos sobre uma reta $R^{\prime}$ paralela a $R$. Quantos quadriláteros convexos com vértices em 4 desses 13 pontos existem?
6. Em um torneio no qual cada participante enfrenta todos os demais uma única vez, são jogadas 780 partidas. Quantos são os participantes?
7. Sejam $I_{m}=\{1,2, \ldots, m\}$ e $I_{n}=\{1,2, \ldots, n\}$, com $m \leq n$. Quantas são as funçōes $f: I_{m} \rightarrow I_{n}$ estritamente crescentes?
8. Um homem tem 5 amigas e 7 amigos. Sua esposa tem 7 amigas e 5 amigos. De quantos modos eles podem convidar 6 amigas e 6 amigos, se cada um deve convidar 6 pessoas?
9. Quantos são os números naturais de 7 dígitos nos quais o dígito 4 figura exatamente 3 vezes e o dígido 8 exatamente 2 vezes?
10. Quantos são os números naturais de 7 dígitos nos quais o dígito 4 figura exatamente 3 vezes e o dígito 8 exatamente 2 vezes?
11. Quantos são os $p$-subconjuntos (isto é, subconjuntos com $p$ elementos) de $\left\{a_{1}, a_{2}, \ldots, a_{n}\right\}$ nos quais:

a) $a_{1}$ figura;
b) $a_{1}$ não figura;
c) $a_{1}$ e $a_{2}$ figuram;
-d) pelo menos um dos clementos $a_{1}, a_{2}$ figura;
c) exatamente um dos elementos $a_{1}, a_{2}$ figura.
12. Considere $n(n>2)$ pontos em um plano, entre os quais não há 3 pontos colineares.
a) Quantas são as retas que contêm dois desses pontos?
b) Qual é o número máximo de pontos de interseção dessas retas?
13. De quantos modos é possível dividir 20 pessoas:
a) em dois grupos de 10 ?
b) em quatro grupos de 5 ?
c) em um grupo de 12 e um de 8 ?
d) em três grupos de 6 e um de 2 ?
14. De um baralho de póquer $(7,8,9,10$, valete, dama, rei c ás, cada um desses grupos aparecendo em 4 naipes: copas, outros, paus, espadas), sacam-se simultaneamente 5 cartas.
a) Quantas são as extrações possiveis?

Quantas são as extrações nas quais se forma:
b) um par (duas cartas cm um mesmo grupo e as outras três em três outros grupos diferentes)?
c) dois pares (duas cartas em um grupo, duas em outro grupo e uma em um terceiro grupo)?
d) uma trinca (três cartas em um grupo e as outras duas em dois outros grupos diferentes)?
e) um "four" (quatro cartas em um grupo e uma em outro grupo)?
f) um "full hand" (três cartas em um grupo e duas em outro grupo)?
g) uma seqüência ( 5 cartas de grupos consecutivos, não sendo todas do mesmo naipe)?

h) um "flush" (5 cartas do mesmo naipe, não sendo clas de 5 grupos consecutivos)?
i) um "straight flush" ( 5 cartas de grupos consecutivos, todas do mesmo naipe)?
j) um "royal straight flush" (10, valete, dama, rei e ás de um mesmo naipe)?
15. O conjunto $A$ possui $p$ elementos e o conjunto $B$ possui $n$ elementos. Determine o número de funçöes $f: A \rightarrow B$ sobrejetoras para:
a) $p=n$;
b) $p=n+1$;
c) $p=n+2$.
16. Considere um conjunto $C$ de 20 pontos do espaço que tem um subconjunto $C$; formado por 8 pontos coplanares. Sabe-se que toda vez que 4 pontos de $C$ são coplanares, entäo eles são pontos de $C_{1}$. Quantos são os planos que contèm pelo menos très pontos de $C$ ?
17. Quantos são os anagramas da palavra CARAGUATATUBA? Quantos começam por vogal?
18. São dados, no plano, $n$ pontos tais que entre as retas por eles determinadas não há duas retas paralelas. Quantos são, no máximo, os pontos de interseção dessas retas que são distintos dos pontos dados?
19. Considere um poligono convexo de $n$ lados e suponha que não há duas de suas diagonais que sejam paralelas nem très que concortam em um mesmo ponto que não seja vértice.
a) Quantos são os pontos de interseção dessas diagonais?
b) Quantos desses pontos de interseção são interiores ao poligono?
c) Quantos são exteriores?
20. Uma fila de cadeiras no cinema tem 20 poltronas. De quantos modos 6 casais podem se sentar nessas poltronas de modo que nenhum marido se sente separado de sua mulher?

21. Nove cientistas trabalham num projeto sigiloso. Por questöes de segurança, os planos são guardados em um: cofre protegido por muitos cadeados de modo que só é possivel alri-los todos se houver pelo menos 5 cientistas presentes.
a) Qual é o número mínimo possível de cadeados?
b) Na situação do item a), quantas chaves cada cientista deve ter?
22. Depois de ter dado um curso, um professor resolve se despedir de seus 7 alunos oferecendo, durante 7 dias consecutivos, 7 jantares para 3 alunos cada. De quantos modos ele pode fazer os convites se ele não deseja que um mesmo par de alunos compareça a mais de um jantar?
23. Formam-se as combinaçöes simples de classe 5 dos clementos $a_{1}, a_{2}, a_{2}, \ldots, a_{12}$, as quais são escritas com os elementos em ordem crescente de índices. Quantas são as combinações nas quais o elemento $a_{8}$ ocupa o $3^{\circ}$ lugar?
24. De quantos modos é possível colocar em fila $h$ homens e $m$ mulheres, todos de alturas diferentes, de modo que os homens entre si e as mulheres entre si fiquem em ordem crescente de alturas?
25. No quadro abaixo, de quantos modos é possível formar a palavra "MATEMÁTICA", partindo de um $M$ e indo sempre para a direita ou para baixo?

|  |  |  |  |  |  |  |  |  | $M$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |  |  | $M$ | $A$ |
|  |  |  |  |  |  |  | $M$ | A | $T$ |
|  |  |  |  |  |  | $M$ | A | $T$ | E |
|  |  |  |  |  | $M$ | A | $T$ | E | $M$ |
|  |  |  |  | $M$ | A | $T$ | E | M | A |
|  |  |  | $M$ | A | $T$ | E | M | A | $T$ |
|  |  | $M$ | A | $T$ | E | M | A | $T$ | I |
|  | $M$ | A | $T$ | E | M | A | T | I | C |
| $M$ | A | $T$ | E | M | A | T | I | C | A |

26. Suponha que $n$ carros estão em fila para entrar em um estacionamento que possui $n$ vagas, lado a lado. Se o $1^{\circ}$ carro pode escoher qualquer vaga e cada um dos outros carros ao estacionar deve justapor-se a um carro já estacionado, quantos são os modos possíveis dos carros ocuparem as $n$ vagas?
27. De quantos modos 15 jogadores podem ser divididos em 3 times de basquetebol de 5 jogadores cada, denominados esperança, confiança e vitória?
28. O conjunto $A$ possui $n$ elementos.
a) Determine o número de relações que podem ser construídas em $A$;
b) Idem, relações reflexivas;
c) Idem, relações simétricas;
d) Idem, relações anti-simétricas;
e) Idem, relações reflexivas e simétricas;
f) Idem, relações reflexivas e anti-simétricas;
g) Idem, relações simétricas c anti-simétricas;
h) Idem, relações reflexivas, simétricas c anti- simétricas.
29. Quantos são os jogos de um campeonatos disputado por 20 clubes, no qual todos se enfrentam uma única vez?
30. Empregando dez consoantes c cinco vogais, calcule o número de palavras de seis letras que se podem formar sem uasr consoantes nem vogais adjacentes:
a) Se são permitidas repetições;
b) Se não são permitidas repetições.
31. De quantos modos se pode iluminar uma sala que possui $m$ lámpadas?
32. Em uma escola, $x$ professores se distribuem em 8 bancas examinadoras de modo que cada professor participa de exatamente duas bancas e cada duas bancas tem exatamente um professor em comum.

a) Calcule $x$;
b) Determine quantos professores há em cada banca.
33. A partir de um conjunto de a atletas formam-se $t$ times de $k$ atletas cada. Todos os atletas participam de um mesmo número de times e cada par de atletas fica junto no mesmo time um mesmo número de vezes. Determine:
a) de quantos times cada atleta participa;
b) em quantos times cada par de atletas fica junto.
34. Mostre que existe um tabuleiro $6 \times 4$, cujas casas são todas pretas ou brancas, no qual nenhum retângulo tem as 4 casas dos vértices da mesma cor. Mostre que, em todo tabuleiro $7 \times 4$ cujas casas são todas pretas ou brancas, sempre existe um retângulo cujas 4 casas extremas têm a mesma cor. (Observação: no tabuleiro casas adjacentes não têm necessariamente cores diferentes).
35. Prove que um produto de $p$ inteiros consecutivos é sempre divisível por $p$ !.
36. Prove, usando um argumento combinatório, que os números abaixo são inteiros para qualquer $n$ natural.
a) $\frac{(2 n)!}{2^{n}}$
b) $\frac{(3 n)!}{2^{n} \cdot 3^{n}}$
c) $\frac{(3 n)!}{n!2^{n} 3^{n}}$
d) $\frac{\left(n^{2}\right)!}{\left(n!\right)^{n-1}}$
e) $\frac{(n!)!}{\left(n!\right)^{(n-1)!}}$.
37. No início de uma festa há 6 rapazes desacompanhados e 10 moças desacompanhadas. Quantos são osr estados possíveis no fim da festa?
38. Prove, usando um argumento combinatório, que

$$
C_{m}^{n} C_{n}^{r}=C_{m}^{r} C_{m-r}^{n-r}
$$

39. Prove que $C_{2 n}^{n}$ é par, se $n \geq 1$.
40. $C_{1000}^{500}$ é divisível por 7 ?

# 2.4 Permutações Circulares 

De quantos modos podemos colocar $n$ objetos distintos em $n$ lugares equiespacados em torno de um círculo, se consideramos equivalentes disposições que possam coincidir por rotação?

A resposta desse problema será representada por $(P C)_{n}$, o número de permutações circulares de $n$ objetos distintos. É fácil ver que $(P C)_{n}$ é em geral. diferente de $P_{n}$. Por exemplo, no caso $n=3$ temos $P_{3} \quad 3!=6$ modos de colocar 3 objetos distintos em 3 lugares.
![img-11.jpeg](img-11.jpeg)

Fig. 2.6

No entanto as três primeiras disposições podem coincidir entre si por rotação e o mesmo ocorre com as trés últimas, de modo que $(P C)_{3}<2$.

Repare que nas permutações simples importam os lugares que os objetos ocupam ao passo que nas permutaçòes circulares

o que importa é apenas a posição relativa dos objetos entre si. Nas três primeiras figuras, olhando os círculos em sentido antihorário, 1 precede 2 , que precede 3 , que precede 1 ; portanto, a posição relativa dos objetos é a mesma. Nas três últimas figuras, 1 precede 3 , que precede 2 , que precede 1 ; portanto, a posição relativa dos objetos é a mesma.

Podemos verificar que $(P C)_{n}=(n-1)$ ! de dois modos:
a) Se não considerássemos equivalentes disposições que possam coincidir por rotação, teríamos $n$ ! disposições. Considerando a equivalência, cada permutação circular é gerada por $n$ disposições. Logo,

$$
(P C)_{n}=\frac{n!}{n}=(n-1)!
$$

b) Como o que importa é a posição relativa dos objetos, há 1 modo de colocar o $1^{\circ}$ objeto no círculo (onde quer que o coloquemos, ele será o único objeto no círculo); há 1 modo de colocar o $2^{\circ}$ objeto (ele será o objeto imediatamente após o primeiro); há 2 modos de colocar o $3^{\circ}$ objeto (imediatamente após o $1^{\circ}$ ou imediatamente após o $2^{\circ}$ ); há 3 modos de colocar o $4^{\circ}$ objeto (imediatamente após o $1^{\circ}$ ou imediatamente após o $2^{\circ}$ ou imediatamente após o $3^{\circ}$ )...; há $n-1$ modos de colocar o $n$-ésimo e último objeto. Logo,

$$
(P C)_{n}=1 \cdot 1 \cdot 2 \cdot 3 \cdots(n-1)=(n-1)!
$$

Exemplo 2.16: Quantas rodas de ciranda podem ser formadas com $n$ crianças?

Solução: Como a roda gira, o que importa não é o lugar de cada criança e sim a posição relativa das crianças entre si. A resposta é

$$
(P C)_{n}=(n-1)!
$$

Exemplo 2.17: De quantos modos podemos formar uma roda de ciranda com 7 crianças, de modo que duas determinadas dessas crianças não fiquem juntas?
Solução: Podemos formar $(P C)_{5}=4$ ! rodas com as cinco outras crianças.
![img-12.jpeg](img-12.jpeg)

Fig. 2.7
Há agora 5 modos de colocar a criança $A$ na roda.
![img-13.jpeg](img-13.jpeg)

Fig. 2.8

Há agora 4 modos de colocar a criança $B$ na roda sem colocá-la junto de $A$. A resposta é

$$
4!\times 5 \times 4=480
$$

# Exercícios 

1. De quantos modos 5 meninos e 5 meninas podem formar uma roda de ciranda de modo que pessoas de mesmo sexo não fiquem jumtas?
2. De quantos modos $n$ crianças podem formar uma roda de ciranda de modo que duas dessas crianças permaneçam juntas? E de modo que $p(p<n)$ dessas crianças permaneçam juntas?
3. De quantos modos $n$ casais podem formar uma roda de ciranda de modo que cada homem permaneça ao lado de sua mulher?
4. De quantos modos $n$ casais podem formar uma roda de ciranda de modo que cada homem permaneça ao lado de sua mulher e que pessoas de mesmo sexo não fiquem juntas?
5. São dados $n$ pontos em círculo. Quantos $n$-ágonos (não necessariamente convexos) existem com vértices nesses pontos?
6. Uma pulscita deve ser cravejada com um rubi, uma esmeralda, um topázio, uma água-marinha, uma turmalina e uma ametista. De quantos modos isso pode ser feito supondo:
a) que a pulseira tem fecho e um relógio engastado no fecho;
b) que a pulseira tem fecho:
c) que a pulseira não tem fecho e o braço só pode entrar na pulseira em um sentido:
d) que a pulseira não tem fecho e o braço pode entrar na pulseira nos dois sentidos.
7. De quantos modos 5 mulheres e 6 homens podem formar uma roda de ciranda de modo que as mulheres permaneçam juntas?
8. Quantos dados diferentes existem se a soma das faces opostas deve ser $? ?$

# 2.5 Permutações de Elementos nem Todos Distintos 

Quantos anagramas possui a palavra "TÁRTARA"? A resposta não é $P_{7}=7!=5040$. Pelo fato de "T'ÁRTARA", ter letras repetidas, obtemos um número de anagramas menor do que o que obteríamos se as letras fossem distintos. $T A R_{1} T A R_{2} A$ e $T A R_{2} T A R_{1} A$ seriam anagramas difcrentes, por exemplo.

O número de anagramas de "TART'ARA" será representado por $P_{7}^{3,2,2}$ ou

$$
\left(\begin{array}{r}
7 \\
3,2,2
\end{array}\right)
$$

número de permutaçōes de 7 letras das quais 3 são iguais a $A, 2$ iguais a $R$ e 2 iguais a $T$.

Para determinar o número de anagramas de TÁRTARA, podemos pensar de dois modos:
a) Para formar um anagrama de "TÁRTARA" temos que arrumar $3 A, 2 R$ e $2 T \mathrm{~cm} 7$ lugares, $\qquad$ O número de modos de cscolher os lugares onde serão colocados os $A$ é $C_{7}^{3}$. Depois disso temos $C_{4}^{2}$ modos de escolher os lugares para colocar os $R$ e, finalmente, um único modo de escolher os lugares para os $T$. Logo,

$$
P_{7}^{3,2,2}=C_{7}^{3} \cdot C_{4}^{2} \cdot 1=35 \times 6 \times 1=210
$$

b) Sc as letras fossem diferentes, obteríamos $P_{7}=7$ ! anagramas. Como os $A$ são iguais, contamos cada anagrama 3! vezes. Analogamente contamos cada anagrama 2! vezes por serem iguais os $R$ e 2 ! vezes por serem iguais os $T$. Logo.

$$
P_{7}^{3,2,2}=\frac{7!}{3!2!2!}=210
$$

É fácil ver que, no caso geral, temos, para $\alpha+\beta+\cdots+k+\lambda=n$,

$$
\begin{aligned}
& P_{n}^{\alpha, \beta, \ldots, k, \lambda}=C_{n}^{\alpha} \cdot C_{n-\alpha}^{\beta} \cdots C_{n-\alpha-\beta-\cdots-k}^{\lambda}= \\
& =\frac{n!}{\alpha!(n-\alpha)!} \frac{(n-\alpha)!}{\beta!(n-\alpha-\beta)!} \cdots \frac{(n-\alpha-\beta-\cdots-k)!}{\lambda!(n-\alpha-\beta-\cdots-k-\lambda)!}= \\
& =\frac{n!}{\alpha!\beta!\ldots \lambda!0!}=\frac{n!}{\alpha!\beta!\ldots \lambda!}
\end{aligned}
$$

resposta à qual chegaríamos diretamente pelo segundo raciocínio. Assim, o número de permutações de $n$ objetos dos quais $\alpha$ são iguais a $a, \beta$ iguais a $b, \ldots, \lambda$ iguais a $l(\alpha+\beta+\cdots+\lambda=n)$ é

$$
P_{n}^{\alpha, \beta, \ldots, \lambda}=\frac{n!}{\alpha!\beta!\ldots \lambda!}
$$

Exemplo 2.18: Quantos são os anagramas da palavra "MATEMÁTICA"?

Solução: Como temos 3 letras $A, 2$ letras $M, 2$ letras $T, 1$ letra $C, 1$ letra $I$ e 1 letra $E$, a resposta é

$$
P_{10}^{3,2,2,1,1,1}=\frac{10!}{3!2!2!1!1!1!}=151200
$$

Exemplo 2.19: Quantos são os anagramas de "URUGUAI" que começam por vogal?
Solução: Temos $P_{6}^{2,1,1,1,1}$ começados em $U, P_{6}^{3,1,1,1}$ começados em $A \varrho P_{6}^{3,1,1,1}$ começados em $I$. A resposta é

$$
P_{6}^{2,1,1,1,1}+2 P_{6}^{3,1,1,1}=360+2 \times 120=600
$$

# Exercícios 

1. A figura 2.9 representa o mapa de uma cidade, na qual há 7 avenidas na direção norte-sul e 6 avenidas na direção leste-oeste.
![img-14.jpeg](img-14.jpeg)

Fig. 2.9
a) Quantos são os trajetos de comprimento mínimo ligando o ponto $A$ ao ponto $B$ ?
b) Quantos desses trajetos passam por $C$ ?
2. Quantos números de 7 dígitos, maiores que 6000000 , podem ser formados usando apenas os algarismos $1,3,6,6,6,8,8$ ?
3. Uma particula, estando no ponto $(x, y)$, pode mover-se para o ponto $(x+1, y)$ ou para o ponto $(x, y+1)$. Quantos são os caminhos que a particula pode tomar para, partindo do ponto $(0,0)$, chegar ao ponto $(a, b)$, onde $a>0$ e $b>0$ ?
4. Uma patícula, estando no ponto $(x, y, z)$, pode mover-se para o ponto $(x+1, y, z)$ ou para o ponto $(x, y+1, z)$ ou para o ponto $(x, y, z+1)$. Quantos são os caminhos que a particula pode tomar par, partindo do ponto $(0,0,0)$, chegar ao ponto $(a, b, c)$, onde $a>$ $0, b>0$ e $c>0$ ?
5. Quantos números de 5 algarismos podem ser formados usando apenas os algarismos $1,1,1,1,2$ e 3 ?

# 2.6 Combinações Completas 

De quantos modos é possivel comprar 4 sorvetes em uma loja que os oferece em 7 sabores?

A resposta não é $C_{7}^{4}=35 . C_{7}^{4}$ seria o modo de escolher 4 sabores difertntes entre os 7 sabores oferecidos, isto é, $C_{7}^{4}$ seria o numero de modos de comprar 4 sorvetes diferentes em uma loja que os oferece em 7 sabores.

A resposta desse problema é representada por $C R_{7}^{4}$, número de combinaçöes completas de classe 4 de 7 objetos. Portanto $C R_{7}^{3}$ é o número de modos de escolher 4 objetos entre 7 objetos distintos, valendo escolher o mesmo objeto mais de uma vez.

De modo geral, $C_{6}^{p}$ é o número de modos de escolher $p$ objetos distintos entre $n$ objetos distintos dados, e $C R_{6}^{p}$ é o número de modos de escolher $p$ objetos distintos ou não entre $n$ objetos distintos dados.

Assim, por exemplo, as combinaçòes completas de classe 3 dos objetos a, b, c, d tomados 3 a 3 são

| aua | aub | bbu | ccu | dda | abr |
| :-- | :-- | :-- | :-- | :-- | :-- |
| bbb | aac | bbr | ccb | ddb | abd |
| ccc | aad | bbd | ccd | ddc | acd |
| ddd |  |  |  |  | bcd |

e $C R_{3}^{3}=20$.
Podemos também interpretar $C R_{b}^{p}$ de outro modo. Voltemos à compra dos 4 sorvetes na loja que os oferece em 7 sabores. Para efetuar a compra devemos escolher valores para os variáveis $x_{1}, x_{2}, \ldots, x_{7}$, onde $x_{1}$ é a quantidade que vamos comprar de sorvetes do $1^{\circ}$ sabor, $x_{2}$ é a quantidade que vamos comprar de sorvetes do $2^{\circ}$ sabor ... $x_{7}$ é a quantidade que vamos comprar de sorvetes do $7^{\circ}$ sabor. É claro que $x_{1}, x_{2}, \ldots, x_{7}$ devem ser inteiros, não negativos (isto é, maiores ou iguais a zero) e que

$$
x_{1}+x_{2}+\cdots \mid x_{7}=4
$$

Comprar 4 sorvetes cm uma loja que os oferece cm 7 sabores é tomar uma solução em inteiros não negativos da equação

$$
x_{1}+x_{2}+\cdots+x_{7}=4
$$

Podemos, portanto, interpretar $C R_{n}^{p}$ de dois modos:
a) $C R_{n}^{p}$ é o número de modos de selecionar $p$ objetos, distintos ou nào, entre $n$ objetos distintos dados.
b) $C R_{n}^{p}$ é o número de soluções da equação $x_{1}+x_{2} \cdots+x_{n}=p$ em inteiros não negativos.

Vamos agora resolver o problema da compra dos sorvetes, isto é, vamos calcular $C R_{7}^{4}$.

Ora, $C R_{7}^{4}$ é o número de soluções cm inteiros não negativos da equação

$$
x_{1}+x_{2}+x_{3}+x_{4}+x_{5}+x_{6}+x_{7}=4
$$

O quadro da figura 2.10 mostra algumas soluções da equação bem como sua representação no esquema bola-traço (cada bola representa uma unidade no valor da incógnita; cada traço é usado para separar duas incógnitas).

| $x_{1}$ | $x_{2}$ | $x_{3}$ | $x_{4}$ | $x_{5}$ | $x_{6}$ | $x_{7}$ |
| :-- | :-- | :-- | :-- | :-- | :-- | :-- |
| 1 | 1 | 1 | 0 | 0 | 0 | 1 |
|  |  |  |  |  |  |  |
| 0 | 2 | 0 | 1 | 0 | 1 | 0 |
|  |  |  |  |  |  |  |

Fig. 2.10
Para formar uma representação devemos arrumar em fila 4 bolas (pois em cada solução o total de unidades nas incógnitas é 4

já que $x_{1}+x_{2}+\cdots+x_{7}=4$ ) e 6 traços (para separar 7 incógnitas, usamos 6 traços). Mas, o número de modos de fazer isso é

$$
P_{4+6}^{4,6}=\frac{10!}{4!6!}=C_{10}^{4}
$$

Logo, $C R_{7}^{4}=C_{10}^{4}=210$.
No caso geral, para calcular $C R_{n}^{p}$, isto é, para determinar o número de soluções inteiras c não negativas de $x_{1}+x_{2}+\cdots+x_{n}=p$ teriamos $p$ bolas e $n-1$ traços. Logo,

$$
C R_{n}^{F}=P_{p+n-1}^{F, n-1}=\frac{(n+p-1)!}{p!(n-1)!}=C_{n+p-1}^{p}
$$

Portanto, $C R_{n}^{F}=C_{n+p-1}^{F}$.
Exemplo 2.20: Quantas são as soluções inteiras e não negativas de $x+y+z=5$ ?
Solução: $\quad C R_{3}^{5}=C_{7}^{5}=21$.
Exemplo 2.21: De quantos modos podemos comprar 3 refrigerantes cm uma loja onde há 5 tipos de refrigerantes?
Solução: $\quad C R_{5}^{3}=C_{7}^{3}=35$.
Exemplo 2.22: Quantas são as soluções inteiras e não-negativas da inequação $x+y+z \leq 5$ ?
Solução: As soluções inteiras não-negativas de $x+y+z \leq 5$ dividern-se em vários grupos: soluções onde $x+y+z=5$, onde $x+y+z=4, \ldots$, onde $x+y+z=0$. A resposta é

$$
\begin{aligned}
& C R_{3}^{5}+C R_{3}^{4}+C R_{3}^{3}+C R_{3}^{2}+C R_{3}^{1}+C R_{3}^{0}= \\
& =C_{7}^{5}+C_{6}^{4}+C_{5}^{3}+C_{4}^{2}+C_{3}^{1}+C_{2}^{0}= \\
& =21+15+10+6+3+1=56
\end{aligned}
$$

Outra solução: Em cada solução inteira não-negativa de

$$
x+y+z \leq 5
$$

defina-se a folga da solução por $f=5-(x+y+z)$.
O quadro a seguir mostra algumas soluções c as respectivas folgas.

| $x$ | $y$ | $z$ | $x+y+z$ | $f$ |
| :--: | :--: | :--: | :--: | :--: |
| 3 | 1 | 1 | 5 | 0 |
| 2 | 0 | 1 | 3 | 2 |
| 1 | 1 | 1 | 3 | 2 |
| 0 | 1 | 0 | 1 | 4 |

É claro que existe uma correspondência biunívoca entre as soluções inteiras não-ncgativas de $x+y+z \leq 5$ e as soluções inteiras nãonegativas de $x+y+z+f=5$.

Logo, o número de soluções inteiras não-negativas da inequação $x+y+z \leq 5$ é igual ao número de soluções inteiras não-negativas de $x+y+z+f \cdots 5$ que é $C R_{4}^{5}=C_{8}^{5}=56$.
Exemplo 2.23: Quantas são as soluções inteiras da equação $x+y+z=20 \operatorname{com} x \geq 2, y \geq 2, z \geq 2$ ?

O problema que sabemos resolver é contar as soluções inteiras com as variáveis sendo maiores ou iguais a zero. Para fazer um problema recair no outro, pomos

$$
x=2+a, \quad y=2+b, \quad z=2+c
$$

A equação $x+y+z=20$ transforma-se em $a+b+c=14$ e as restrições $x, y, z \geq 2$ e inteiros transformam-se cm $a, b, c \geq 0$ e inteiros. A resposta é

$$
C R_{3}^{14}=C_{16}^{14}=120
$$

Excmplo 2.24: Quantos são os anagramas da palavra "PIRACICABA" que não possuem duas letras $A$ juntas?
Solução: O número de modos de arrumar as letras diferentes de $A$ é $P_{7}^{2,2,1,1,1}$. Por exemplo, uma dessas arrumações é

| $-P$ | $-R$ | $-I$ | $-I$ | $-C$ | $-B$ | $-C$ | - |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |

Agora temos que colocar as letras $A$ nos 8 espaços assinalados. Como em nenhum espaço podem entrar duas letras $A$, ocuparemos 3 espaços (uma letra $A$ em cada) e deixaremos 5 espaços vazios. O número de modos de escolher os espaços que ocuparemos é $C_{8}^{3}$. A resposta é

$$
P_{7}^{2,2,1,1,1} \times C_{8}^{3}=1260 \times 56=70560
$$

Poderíamos também pensar assim:
Colocamos as letras $A$ (1 modo)

Agora devemos decidir quantas letras colocaremos em cada um dos 4 espaços. Devemos escolher $x_{1}, x_{2}, x_{3}, x_{4}\left(x_{i}=\mathrm{n}^{0}\right.$ de letras que colocaremos no $i$-ésimo espaço) inteiros não-negativos tais que $x_{1}+x_{2}+x_{3}+x_{4}=7$, com $x_{2} \geq 1$ e $x_{3} \geq 1$ (para impedir que haja duas letras $A$ juntas). Façamos

$$
\begin{aligned}
& x_{2}=1+y_{2} \\
& x_{3}=1+y_{3}
\end{aligned}
$$

e caimos no problema de achar o número de soluções inteiras nãonegativas de $x_{1}+y_{2}+y_{3}+x_{4}=5$, cuja resposta é $C R_{4}^{5}=C_{8}^{5}$. Escolhidas quantas letras irão para cada espaço, por exemplo,

$$
--A--A--A
$$

temos agora que colocar as letras $P, R, B, I, I, C, C$ nessas casas, o que pode ser feito de $P_{7}^{2,2,1,1,1}$ modos. A resposta é

$$
1 \times C_{8}^{5} \times P_{7}^{2,2,1,1,1}=1 \times 56 \times 1260=70560
$$

# Exercícios 

1. Quantas são as soluções inteiras não-negativas de

$$
x+y+z+w=3 ?
$$

2. Quantas são as soluções inteiras não-negativas de

$$
x+y+z+w<6 ?
$$

3. Quantas são as soluções inteiras positivas de $x+y+z=10$ ?
4. Quantas são as soluções inteiras positivas de $x+y+z<10$ ?
5. Quantas são as peças de um dominó comum?
6. $I_{m}=\{1,2, \ldots, m\}$ e $I_{n}=\{1,2, \ldots, n\}$. Quantas são as funções $f: I_{m} \rightarrow I_{n}$ não descrescentes?
7. De quantos modos podemos colocar em fila 7 letras $A, 6$ letras $B$ e 5 letras $C$ de modo que não haja duas letras $B$ juntas?
8. Qual é o número máximo de termos de um polinômio homogêneo do grau $p$ com $n$ variáveis?
9. Qual é o número máximo de termos de um polinómio do grau $p$ com $n$ variáveis?
10. A fábrica $X$ produz 8 tipos de bombons que são vendidos em caixas de 30 bombons (de um mesmo tipo ou sortidos). Quantas caixas diferentes podem ser formadas?
11. De quantos modos podem ser pintados 6 objetos iguais usando 3 cores diferentes?
12. Quantos números inteiros entre 1 e 100000 têm soma dos algarismos igual a 6 ?
13. Quantas são as soluções inteiras não-negativas de

$$
x_{1}+x_{2}+x_{3}+x_{4}+x_{5}+x_{6}=20
$$

nas quais exatamente 3 incógnitas são nulas? Emm quantas pelo menos três são mulas?
14. Os números inteiros compreendidos entre 100000 e 999999 são divididos em classes de modo que dois números diferentes estão na mesma classe se c só se eles têm os mesmos algarismos, diferindo apenas na ordem. Assim, por exemplo, 552221 e 125252 estão na mesma classe. Quantas classes são assim formadas?
15. Quantas são as soluções inteiras não-negativas de $x+y+z+$ $w=20$ nas quais $x>y$ ?
16. Quantos inteiros entre 1 e 100000 , inclusive, têm a propriedade: "cada dígito é menor ou igual ao seu sucessor"?
17. Quantas permutações de 7 letras $A$ e 7 letras $B$, nas quais não há 3 letras $A$ adjacentes, existem?
18. Uma uma contém $n$ bolas, das quais devem ser escolhidas $p$ bolas. Determine:
a) O número $A_{1}^{p}$ de seleções ordenadas, se repetições não são permitidas (essas seleções são denominadas arranjos simples de classe $p$ das $n$ bolas);
b) O número de seleções desordenadas (isto é, seleções que só diferem pela ordem são consideradas iguais), se repetiçōes não são permitidas;
c) O número $A R_{1}^{p}$ de seleções ordenadas, se repetiçōes são permitidas (essas seleções são chamadas de arranjos completos de classe $p$ das $n$ bolas. Também são usados os nomes arranjos com reposição ou arranjos com repetição);
d) O número de seleções desordenadas, se repetiçōes são permitidas.
19. Scjam $A$ e $B$ conjuntos de números naturais com $\# A=p$ e $\# B=n$.
a) Quantas são as funções $f: A \rightarrow B$ ?
b) Quantas são as funções injetoras $f: A \rightarrow B$ ?
c) Quantas são as funções $f: A \rightarrow B$ estritamente crescentes?

d) Quantas são as funçōes $f: A \rightarrow B$ não-decrescentes?
e) Sugira uma definição formal para $C_{n}^{p}, C R_{n}^{p}, A_{n}^{p}$ e $A R_{n}^{p}$.
20. Seja $A$ um conjunto com $\# A=n$.
a) Quantas são as funções $f: A \rightarrow A$ bijetoras?
b) Sugira uma definição formal para $P_{n}$.
21. De quantos modos podemos escolher 3 números, não necessariamente distintos, no conjunto $\{1,2, \ldots, 150\}$ de modo que a soma dos números escolhidos seja divisível por 3? E se os números devessem ser distintos?
22. De quantas maneiras é possível colocar 6 anéis diferentes em 4 dedos?
æ

# 3. Outros Métodos de Contagem 

### 3.1 O Princípio da Inclusão-Exclusão

Na introdução ao capítulo anterior fizemos referência a um princípio elementar de contagem que estabelece que o numero de elementos da uniāo de conjuntos disjuntos é a soma dos números de elementos de cada conjunto.

O Princípio da Inclusão-Exclusão é uma fórmula para contar o número de elementos que pertencem à união de vários conjuntos não necessariamente disjuntos. Na sua versão mais simples, ele afirma que

$$
\#(A \cup B)=\# A+\# B-\#(A \cap B)
$$

A justificativa pode ser obtida de dois modos diferentes:
a) Suponhamos que haja $y$ elementos comuns a $A$ e $B$ a que além disso haja $x$ elementos que pertençam a $A$ e não a $B$ e $z$ elementos que pertençam a $B$ mas não a $A$ (ver figura 3.1).
Temos

$$
\begin{aligned}
\#(A \cup B) & =x+y+z \\
\# A+\# B-\#(A \cap B) & =(x+y)+(y+z)-y \\
& =x+y+z=\#(A \cup B)
\end{aligned}
$$

![img-15.jpeg](img-15.jpeg)

Fig. 3.1
b) $\#(A \cup B)$ é o número de elementos que pertencem a pelo menos um dos conjuntos $A$ e $B$. Para contal os elementos de $A \cup B$ contamos todos os elementos de $A(\# A)$ e todos os de $B(\# B)$. Ao fazermos isso, os elementos de $A \cap B$ foram contados duas vezes, uma em $\# A$ e outra em $\# B$, portanto devemos descontar a segunda contagem desses elementos c obtemos

$$
\#(A \cup B)=\# A+\# B-\#(A \cap B)
$$

Para trés conjuntos $A, B, C$ o Princípio da Inclusão- Exclusão afirma que

$$
\begin{aligned}
\#(A \cup B \cup C) & =\# A+\# B+\# C \\
& -\#(A \cap B)-\#(A \cap C)-\#(B \cap C) \\
& +\#(A \cap B \cap C)
\end{aligned}
$$

I'ma justificativa pode ser:

$$
\begin{aligned}
\#\mid A \cup B \cup C^{\prime} & =\#\lceil(A \cup B) \cup C\rceil \\
& =\#(A \cup B)+\# C-\#\mid(A \cup B) \cap C \mid \\
& =\# A+\# B-\#(A \cap B)+\# C \\
& -\#\left\lvert\,(A \cap C) \cup(B \cap C)\right.
\end{aligned}
$$

$$
\begin{aligned}
& =\# A+\# B-\#(A \cap B)+\# C \\
& -\#(A \cap C)-\#(B \cap C)+\#(A \cap C \cap B \cap C) \\
& =\# A+\# B+\# C+ \\
& -\#(A \cap B)-\#(A \cap C)-\#(B \cap C) \\
& +\#(A \cap B \cap C)
\end{aligned}
$$

Outra justificativa:
$\#(A \cup B \cup C)$ é o número de elementos que pertencem a pelo menos um dos conjuntos $A, B$ e $C$. Para contar os elementos de $A \cup B \cup C$, contamos os elements de $A(\# A)$, de $B(\# B)$ e de $C(\# C)$. Mas então os elementos de $A \cap B$ foram contados duas vezes (uma em $\# A$ e outra em $\# B$ ), o mesmo ocorrendo com os elementos de $A \cap C$ e $B \cap C$. Portanto, devemos descontar uma vez $\#(A \cap B)$, $\#(A \cap C)$ e $\#(B \cap C)$. Mas então os elementos de $A \cap B \cap C$ foram contados trés vezes (em $\# A$, em $\# B$ e em $\# C$ ) e descontados três vezes (em $\#(A \cap B)$, em $\#(A \cap C)$ e em $\#(B \cap C)$ ). Contados três vezes e descontados três vezes significa que eles não estão sendo contados. Devemos pois incluí-los na contagem e obtemos

$$
\begin{aligned}
\#(A \cup B \cup C) & =\# A+\# B+\# C \\
& -\#(A \cap B)-\#(A \cap C)-\#(B \cap C) \\
& +\#(A \cap B \cap C)
\end{aligned}
$$

Para quatro conjuntos teríamos

$$
\begin{aligned}
& \#(A \cup B \cup C \cup D)= \\
& {[\# A+\# B+\# C+\# D]} \\
& -[\#(A \cap B)+\#(A \cap C)+\#(A \cap D) \\
& +\#(B \cap C)+\#(B \cap D)+\#(C \cap D)] \\
& +[\#(A \cap B \cap C)+\#(A \cap B \cap D) \\
& +\#(A \cap C \cap D)+\#(B \cap C \cap D)] \\
& -\#(A \cap B \cap C \cap D)
\end{aligned}
$$

Em suma, o número de elementos da uniāo é obtido somando os números de elementos de cada conjunto, subtraindo os números de elementos das interseçōes dois a dois, somando os das interseçōes três a três, subtraindo os das interseçōes quatro a quatro etc...

A prova do Princípio (usando o modo b) está no Apêndice 1. Uma prova por indução pode também ser obtida usando o modo a.

Exemplo 3.1: Quantos inteiros entre 1 e 1000 são divisíveis por 3 ou 7 ?

Solução: Defina-se:
$A=$ Conjunto dos inteiros entre 1 e 1000 que são divisíveis por 3. $B=$ Conjunto dos inteiros entre 1 e 1000 que são divisíveis por 7 . Queremos calcular $\#(A \cup B)$. Temos

$$
\begin{aligned}
\# A & =\left[\frac{1000}{3}\right]=333 . \quad(\mid \mid=\text { parte inteira }) \\
\# B & =\left[\frac{1000}{7}\right]=142 \\
\#(A \cap B) & \left[\frac{1000}{21}\right]=47
\end{aligned}
$$

(pois $A \cap B$ é o conjunto dos inteiros entre 1 e 1000 que são divisiveis por 3 e 7 , isto é, que são divisiveis por 21 ).

Pelo Princípio da Inclusão-Exclusão, temos

$$
\#(A \cup B)=\# A+\# B-\#(A \cap B)=333+142-47=428
$$

que é a resposta.
Exemplo 3.2: Quantos são os anagramas da palavra CAPÍTULO que têm $C$ em $1^{\circ}$ lugar, ou $A$ em $2^{\circ}$ lugar, ou $P$ em $3^{\circ}$ lugar ou $I$ em $4^{\circ}$ lugar?

Solução: Defina-se:

$A_{1}=$ conjunto dos anagramas de CAPÍTULO que têm $C$ cm $1^{\circ}$ lugar;
$A_{2}=$ conjunto dos anagramas de CAPÍTULO que têm $A$ em $2^{\circ}$ Jugar;
$A_{3}$ conjunto dos anagramas de CAPÍTULO que têm $P$ em $3^{\circ}$ lugar;
$A_{4}=$ conjunto dos anagramas de CAPÍTULO que têm $I \mathrm{~cm} 4^{\circ}$ lugar.

Queremos calcular $\#\left(A_{1} \cup A_{2} \cup A_{3} \cup A_{4}\right)$. Temos.
$\# A_{1}=\# A_{2} \quad \# A_{3}=\# A_{4}=n^{\circ}$ de anagramas de CAPÍTULO que tém uma letra fixa : 7 ! - 5040 .
$\#\left(A_{1} \cap A_{2}\right)=\#\left(A_{1} \cap A_{3}\right)=\#\left(A_{1} \cap A_{4}\right)=\#\left(A_{2} \cap A_{3}\right)=\#\left(A_{2} \cap\right.$ $\left.A_{4}\right)=\#\left(A_{3} \cap A_{4}\right) \quad \mathrm{n}^{\circ}$ de anagramas de CAPÍTULO que têm duas letras fixas $=6!=720$.
$\#\left(A_{1} \cap A_{2} \cap A_{3}\right)=\#\left(A_{1} \cap A_{2} \cap A_{4}\right)-\#\left(A_{1} \cap A_{3} \cap A_{4}\right)=$ $\#\left(A_{2} \cap A_{3} \cap A_{4}\right)=\mathrm{n}^{\circ}$ de anagramas de CAPÍTULO que têm 3 letras fixas $=5!=120$.
$\#\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4}\right)-\mathrm{n}^{\circ}$ de anagramas de CAPÍTULO que têm 4 letras fixas $=4!=24$.

Pelo Princípio da Inclusão-Exclusão,

$$
\begin{aligned}
\#\left(A_{1} \cup A_{2} \cup A_{3} \cup A_{4}\right) & =4 \times 5040-6 \times 720+4 \times 120-24 \\
& =16296
\end{aligned}
$$

que é a resposta.
O Princípio da Inclusão-Fxclusão pode ser generalizado. Provaremos no Apêndice 1 o

Teorema: Scjam $\Omega$ um conjunto, $A_{1}, A_{2}, \ldots, A_{n}$ subconjuntos

de $\Omega e$

$$
\begin{aligned}
& S_{0}=\# \Omega: \\
& S_{1}=\sum_{i=1}^{n}\left(\# A_{i}\right) ; \\
& S_{2}=\sum_{i \leq i<j \leq n} \#\left(A_{i} \cap A_{j}\right) ; \\
& S_{3}=\sum_{i \leq i<j<k \leq n} \#\left(A_{i} \cap A_{j} \cap A_{k}\right) ;
\end{aligned}
$$

(observe que há $C_{n}^{1}$ parcelas em $S_{1}, C_{n}^{2}$ parcelas em $S_{2}$ etc...). Então:
a) O número de elementos de $\Omega$ que pertencem a exatamente $p$ $(p \leq n)$ dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ é

$$
a_{p}=\sum_{k=0}^{n-p}(-1)^{k} C_{p+k}^{k} S_{p+k}
$$

b) O número de elementos de $\Omega$ que pertencem a pelo menos $p(p \leq n)$ dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ é

$$
b_{p}=\sum_{k=0}^{n-p}(-1)^{k} C_{p-k-1}^{k} S_{p+k}
$$

c) O número de elementos do conjunto $A_{1} \cup A_{2} \cup \cdots \cup A_{n}$ é

$$
S_{1}-S_{2}+\cdots+(-1)^{n-1} S_{n}
$$

A parte c) desse teorcma é devida ao matemático português, professor da Escola Naval de Portugal, Daniel Augusto da Silva (1814-1878).

A parte a) do teorema, no caso $p=0$, é conhecida pelo nome de fórmula do crivo e é devida ao algebrista inglês J. J. Sylvester (1814-1897).

A parte a), no caso geral, é devida ao matemático francês Camille Jordan (1858-1922).

Exemplo 3.3: Quantos sāo os inteiros, compreendidos entre 1 e 1000 inclusive, que são divisíveis por exatamente dois dos números $2,3,7$ e 10 ? E por pelo menos dois?

Soluçāo: Defina-se

$$
\begin{aligned}
\Omega & =\{x \in Z \mid 1 \leq x \leq 1000\} \\
A_{1} & =\{x \in \Omega \mid 2 \text { divide } x\} \\
A_{2} & =\{x \in \Omega \mid 3 \text { divide } x\} \\
A_{3} & =\{x \in \Omega \mid 7 \text { divide } x\} \\
A_{4} & =\{x \in \Omega \mid 10 \text { divide } x\}
\end{aligned}
$$

Temos ( $i$ = Parte Inteira)

$$
\begin{aligned}
S_{0} & =\# \Omega=1000 \\
S_{1} & =\# A_{1}+\# A_{2}+\# A_{3}+\# A_{4} \\
& =\left[\frac{1000}{2}\right]+\left[\frac{1000}{3}\right]+\left[\frac{1000}{7}\right]+\left[\frac{1000}{10}\right] \\
& =500+333+142+100=1075 \\
S_{2} & =\#\left(A_{1} \cap A_{2}\right)+\# A_{1} \cap A_{3}\right)+\#\left(A_{1} \cap A_{4}\right)+ \\
& +\#\left(A_{2} \cap A_{3}\right)+\#\left(A_{2} \cap A_{4}\right)+\#\left(A_{3} \cap A_{4}\right)= \\
1 & \left\lvert\, \frac{1000}{6}\right.+\left[\frac{1000}{14}\right]+\left[\frac{1000}{10}\right]+\left[\frac{1000}{21}\right]+\left[\frac{1000}{30}\right]+\left[\frac{1000}{70}\right] \\
& =166+71+100+47+33+14 \\
& =431
\end{aligned}
$$

$$
\begin{aligned}
S_{3} & =\#\left(A_{1} \cap A_{2} \cap A_{3}\right)+\#\left(A_{1} \cap A_{2} \cap A_{4}\right)+ \\
& +\#\left(A_{1} \cap A_{3} \cap A_{4}\right)+\#\left(A_{2} \cap A_{3} \cap A_{4}\right) \\
& =\left[\frac{1000}{42}\right]+\left[\frac{1000}{30}\right]+\left[\frac{1000}{70}\right]+\left[\frac{1000}{210}\right] \\
& =23+33+14+4 \\
& =74 \\
S_{4} & =\#\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4}\right)=\left[\frac{1000}{210}\right]=4
\end{aligned}
$$

Queremos calcular o número de elementos que pertencem a exalamente dois dos conjuntos $A_{1}, A_{2}, A_{3}, A_{4}$. Esse número é

$$
\begin{aligned}
a_{2} & =\sum_{k=0}^{4-2}(-1)^{k} C_{2+k}^{k} S_{2+k} \\
& =(-1)^{0} C_{2}^{0} S_{2}+(-1)^{1} C_{3}^{1} S_{3}+(-1)^{2} C_{4}^{2} S_{4} \\
& -S_{2}-3 S_{3}+6 S_{4} \\
& =431-3 \times 74+6 \times 4=233
\end{aligned}
$$

que é a resposta da primeira pergunta.
Queremos calcular o número de elementos que petencem a pelo menos dois dos conjuntos $A_{1}, A_{2}, A_{3}, A_{4}$. Esse número é

$$
\begin{aligned}
b_{2} & =\sum_{k=0}^{4-2}(-1)^{k} C_{2+k-1}^{k} S_{2+k} \\
& =(-1)^{0} C_{1}^{0} S_{2}+(-1)^{1} C_{2}^{1} S_{3}+(-1)^{2} C_{3}^{2} S_{4} \\
& =S_{2}-2 S_{3}+3 S_{4} \\
& =431-2 \times 74+3 \times 4 \\
& =295
\end{aligned}
$$

que é a resposta da segunda pergunta. Note que os valores de $S_{0}$ e $S_{1}$ não foram utilizados.

Excmplo 3.4: Para cada inteiro positivo $n$ define-se $\varphi(n)$ como sendo o número de inteiros positivos que são primos com $n$ e não são superiores a $n$, isto é, que são primos com $n$ e menores ou iguais a $u$. Assim, por exemplo, $\varphi(12)=4$ pois os inteiros positivos que nào superam 12 e são primos com 12 são 1.5 .7 e 11 . e $\varphi(7)=6$ pois os inteiros positivos que nào superam 7 e são primos com 7 sào 1.2 .3 .4 .5 .6 .

A funçäo $\varphi$ é chamada de Função $\varphi$ de Euler (1707-1783).
O valor de $\varphi(n)$ pode ser calculado a partir da decomposição de $n$ em fatores primos. Se a decomposição de $n$ cm fatores primos é

$$
n=p_{1}^{j_{1}} \cdot p_{2}^{j_{2}} \cdots p_{r}^{j_{r}} \quad\left(p_{1}, p_{2}, \ldots, p_{r} \text { primos distintos }\right)
$$

entäo

$$
\varphi(n)=u\left(1-\frac{1}{p_{1}}\right)\left(1-\frac{1}{p_{2}}\right) \cdots\left(1-\frac{1}{p_{r}}\right)
$$

Assim, por exemplo, como as decomposições de 120 e 729 em fatores primos são $120=2^{3} \times 3 \times 5$ e $729 \cdot 3^{6}$, temos

$$
\varphi(120)=120\left(1-\frac{1}{2}\right)\left(1-\frac{1}{3}\right)\left(1-\frac{1}{5}\right)=32
$$

e

$$
\varphi(729)=729\left(1-\frac{1}{3}\right)=486
$$

ou seja, no conjunto $\{1,2, \ldots, 120\}$ há 32 múmeres primos com 120 e no conjunto $\{1,2, \ldots, 729\}$ há 486 números primos com 729 .

- Para justificar a fórmula, defina-se:
$\Omega=$ Conjunto dos inteiros positivos menores ou iguais a $n$;
$A_{i}=$ Conjunto dos elementos de $\Omega$ que sào múltiplos de $p_{i}(1 \leq$ $i \leq x$ ).

Queremos determinar o número de elementos de $\Omega$ que sio primos com $n$, ou seja, o número de elementos de $\Omega$ que não pertencem a nenhum dos conjuntos $A_{1}, A_{2}, \ldots, A_{r}$.
$\varphi(n)$ é pois o número de elementos de $\Omega$ que pertencem a exatamente zero dos conjuntos $A_{1}, A_{2}, \ldots, A_{r}$. Temos

$$
\begin{gathered}
A_{i} \quad\left\{p_{i}, 2 p_{i}, \ldots, \frac{n}{p_{i}} p_{i}\right\} \\
\#\left(A_{i}\right)-\frac{n}{p_{i}} \\
A_{i} \cap A_{j}=\left\{p_{i} p_{j}, 2 p_{i} p_{j}, \ldots, \frac{n}{p_{i} p_{j}} p_{i} p_{j}\right\} \\
\#\left(A_{i} \cap A_{j}\right)=\frac{n}{p_{i} p_{j}} \quad(i / j)
\end{gathered}
$$

e assim sucessivamente. Logo:

$$
\begin{aligned}
& S_{0}=\# \Omega=n \\
& S_{1}=\sum \#\left(A_{i}\right)=\sum \frac{n}{p_{i}} \\
& S_{2}=\sum_{i<j} \#\left(A_{i} \cap A_{j}\right)=\sum_{i<j} \frac{n}{p_{i} p_{j}}
\end{aligned}
$$

Assim,

$$
\begin{aligned}
\varphi(n) & -a_{0} \\
& =\sum_{k=0}^{r}(-1)^{k} C_{0+k}^{k} S_{0+k} \\
& =S_{0}-S_{1}+S_{2}-\cdots+(-1)^{r} S_{r} \\
& =n-\left(\frac{n}{p_{1}}+\frac{n}{p_{2}}+\cdots+\frac{n}{p_{r}}\right)+ \\
& +\left(\frac{n}{p_{1} p_{2}}+\frac{n}{p_{1} p_{3}}+\cdots+\frac{n}{p_{r-1} p_{r}}\right)-\cdots
\end{aligned}
$$

$$
\begin{aligned}
& +(-1)^{r} \frac{n}{p_{1} p_{2} \cdots p_{r}} \\
& =n\left(1-\frac{1}{p_{1}}\right)\left(1-\frac{1}{p_{2}}\right) \cdots\left(1-\frac{1}{p_{r}}\right)
\end{aligned}
$$

# Exercícios 

1. Quantos inteiros entre 1 e 1000 inclusive:
a) são divisiveis por pelo menos três dos números $2,3,7$ e 10 ?
b) não são divisiveis por nenhum dos números $2,3,7$ e 10 ?
c) são divisiveis por exatamente um dos números $2,3,7$ e 10 ?
d) são divisiveis por pelo menos um dos números $2,3,7$ e 10 ?
2. Quantos inteiros entre 1000 e 10000 inclusive não são divisiveis nem por 2 , nem por 3 e nem por 5 ?
3. Lançam-se 3 dados. Em quantos dos $6^{3}$ resultados possiveis a soma dos pontos é 12 ?
4. Quantas sāo as soluçòes inteiros não-negativas de $x+y+z=$ 12 nas quais pelo menos uma incógnita é maior que 7 ?
5. Se $\# A=n$ e $\# B=p(n \geq p)$, quantas sāo as $f: A \rightarrow B$ sobrejctoras?
6. Determine o número de permutaçōes de $(1,2,3,4,5,6)$ nas quais nem o 4 ocupa o $4^{\circ}$ lugar nem o 6 ocupa o $6^{\circ}$ lugar.
7. Quantos são os inteiros de $n$ dígitos, que têm todos os dígitos pertencentes an conjunto $\{1,2,3\}$ ? Em quantos deles os inteiros 1, 2 e 3 figuram todos?
8. Determine o número de permutaçōes das lctas $A A B B C C D D$ nas quais não há letras iguais adjacentes.
8. Quantos inteiros entre 1 e 1000000 não são nem quadrados perfeitos nem cubos perfeitos?

10. Determine o número de permutações de $(1,2, \ldots, n)$ nas quais não figuram (em posições consccutivas e na ordem dada) nem o par 12, nem o par $23, \ldots$, nem o par $(n-1) n$.
11. Oito crianças estão sentadas em torno de um carrossel. De quantos modos elas podem trocar de lugar de modo que cada criança passe a ter uma criança diferente a sua direita?
12. Calcule $\varphi(360)$.
13. Quantas espécies de polígonos regulares de 100 lados existem?
14. Se $p$ é um primo, quanto vale $\varphi(p)$ ?
15. Quantos são os elementos do conjunto $\{1,2, \ldots, 500\}$ que são divisíveis por 3 ou 5 mas não são divisíveis por 7 ?
16. a) De quantos modos podemos distribuir $\mu$ partículas distintas por $n$ niveis distintos? (em Física essa distribuição de partículas por níveis de energia é chamada de estatística de Boltzmann).
b) Em quantas dessas distribuiçöes todos os níveis ficam ocupados?
17. a) De quantos modos podemos distribuir $\mu$ partículas iguais por $n$ níveis distintos? (em Física essa distribuição é chamada de estatística de Bose-Einstein).
b) Em quantas dessas distribuiçöes todos os níveis ficam ocupados?
18. De quantos modos podemos distribuir $\mu$ partículas iguais por $n$ níveis distintos se nenhum nível pode conter mais de uma partícula? (em Física essa distribuição é chamada de estatística de Fermi-Dirac).

# 3.2 Permutações Caóticas 

Lina permutaçâo dos múmeros $(1,2, \ldots, n)$ é dita caótica (ou desordenamento) quando nenhum número está no seu lugar primitivo. Assim, as permutaçòes 2143 e 3142 são caóticas mas 1342 não é ( 1 está no seu lugar primitivo). Para calcular o número $D_{n}$ de permutaçòes caóticas de $(1,2, \ldots, n)$, defina-se $A_{i}$ - conjunto das permutaçôes de $(1,2, \ldots, n)$ em que o número $i$ ocupa o $i$-ésimo lugar, $i \in\{1,2, \ldots, n\}$.

Queremos calcular o número de elementos do conjunto $\Omega$ das permutaçôes de $(1,2, \ldots, n)$ que pertencem a exatamente zero dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$. Temos:

$$
\begin{aligned}
& S_{0}=\#(\Omega)=n! \\
& S_{1}=\sum_{i=1}^{n} \#\left(A_{i}\right)=\sum_{i=1}^{n}(n-1)!=n \cdot(n-1)!=n! \\
& S_{2}=\sum_{1 \leq i<j \leq n} \#\left(A_{i} \cap A_{j}\right)=\sum_{1 \leq i<j \leq n}(n-2)!=C_{n}^{2} \cdot(n-2)!=\frac{n!}{2!} \\
& S_{3}=\sum_{1 \leq i<j<k \leq n} \#\left(A_{i} \cap A_{j} \cap A_{k}\right) \\
& =\sum_{1 \leq i<j<k \leq n}(n-3)!=C_{n}^{3} \cdot(n-3)!=\frac{n!}{3!} \\
& S_{n}=C_{n}^{n} \cdot(n-n)!=\frac{n!}{n!}
\end{aligned}
$$

O número de clementos de $\Omega$ que pertencem a exatamente

zero dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ é

$$
\begin{aligned}
& a_{0} \sum_{k=0}^{n-0}(-1)^{k} C_{0+k}^{k} S_{0+k} \\
& \sum_{k=0}^{n}(-1)^{k} S_{k} \\
&=S_{0}-S_{1} \mid S_{2}-S_{3}+\cdots+(-1)^{n} S_{n} \\
&=n!-n!+\frac{n!}{2!}-\frac{n!}{3!}+\cdots+(-1)^{n} \frac{n!}{n!} \\
& \left.\left.\quad n!\left[\frac{1}{0!}-\frac{1}{1!}+\frac{1}{2!}-\frac{1}{3!}+\cdots+\frac{(-1)^{n}}{n!}\right]\right.
\end{aligned}
$$

Logo, o número de permutações caóticas de $(1,2, \ldots, n)$ é

$$
D_{n} \quad n!\left[\frac{1}{0!}-\frac{1}{1!}+\frac{1}{2!}-\frac{1}{3!}+\cdots+\frac{(-1)^{n}}{n!}\right]
$$

Assim, por exemplo,

$$
\begin{aligned}
D_{n} & =4!\left[\frac{1}{0!}-\frac{1}{1!}+\frac{1}{2!}-\frac{1}{3!}+\frac{1}{4!}\right] \\
& =24\left(1-1+\frac{1}{2}-\frac{1}{6}+\frac{1}{24}\right) \\
& =9
\end{aligned}
$$

Realmente, as permutações caóticas de (1,2,3,4) são 2143, $3142,3241,4123,3412,4312,2413,2341,4321$. É interessante olservar que $D_{n}$ é aproximadamente igual a $n!/ \mathrm{c}$; mais

precisamente, $D_{n}$ é o inteiro mais próximo de $n!/ e$.

| $n$ | $D_{n}$ | $n!/ e$ |
| :--: | :--: | :--: |
| 1 | 0 | $0,3 \ldots$ |
| 2 | 1 | $0,7 \ldots$ |
| 3 | 2 | $2,2 \ldots$ |
| 4 | 9 | $8,8 \ldots$ |
| 5 | 44 | $44,1 \ldots$ |
| $\vdots$ | $\vdots$ | $\vdots$ |

Olserve que nossa afirmação é verdadeira para $n-1$ e para $n=2$. Vamos prová-la para $n>2$. Com efeito sabemos que

$$
e^{x}=\frac{1}{0!}+\frac{x}{1!}+\frac{x^{2}}{2!}+\frac{x^{3}}{3!}+\cdots
$$

e portanto que

$$
e^{-1}-\frac{1}{0!}-\frac{1}{1!}+\frac{1}{2!}-\frac{1}{3!}+\cdots
$$

Ora, $D_{n}$ é inteiro e

$$
\begin{aligned}
\left|D_{n}-\frac{n!}{e}\right| & \cdots\left|n!\left(\frac{1}{0!}-\frac{1}{1!}+\cdots+\frac{(-1)^{n}}{n!}\right)-\right. \\
& \left.-n!\left(\frac{1}{0!}-\frac{1}{1!}+\frac{1}{2!}-\cdots\right)\right| \\
& =n!\left|\frac{(-1)^{n+1}}{(n+1)!}+\frac{(-1)^{n+2}}{(n+2)!}+\cdots\right| \\
& \leq n!\left(\frac{1}{(n+1)!}+\frac{1}{(n+2)!}+\cdots\right) \\
& =\frac{1}{n+1}+\frac{1}{(n+1)(n+2)}+\frac{1}{(n+1)(n+2)(n+3)}+\cdots
\end{aligned}
$$

$$
\begin{aligned}
& \leq \frac{1}{n+1}+\frac{1}{(n+1)^{2}}+\frac{1}{(n+1)^{3}}+\cdots \\
& =\frac{\frac{1}{n+1}}{1-\frac{1}{n+1}} \\
& =\frac{1}{n}<\frac{1}{2}
\end{aligned}
$$

Ou seja,

$$
\left|D_{n}-\frac{n!}{e}\right|<\frac{1}{2}
$$

se $n>2$. Logo, para $n>2, D_{n}$ é um inteiro situado a uma distância menor que $1 / 2$ do número $n!/ \mathrm{c}$. Assim, $D_{n}$ é o inteiro mais próximo de $n!/ c$, se $n>2$.

# Exercícios 

1. Suponha $\# A=n$. Quantas são as funçōes $f: A \rightarrow A$ para as quais a cquação $f(x)$ : $x$ não possui solução? Quantas são as funções $f: A \rightarrow A$ bijetoras para as quais a equação $f(x)-x$ não possui solução?
2. Quantas são as permutações de $(1,2,3,4,5,6,7)$ que têm exatamente 3 elementos no seu lugar primitivo?
3. Determine o número de permutações caóticas de $(1,2,3,4,5,6,7$, $8,9,10)$ nas quais os números $1,2,3,4,5$ ocupam, em alguma ordem, os cinco primeiros lugares.
4. De quantos modos é possível colocar 8 torres brancas em um tabuleiro de xadrez $8 \times 8$ de modo que nenhuma torre fique na diagonal branca e não haja duas torres na mesma linha ou na mesma coluna?
5. Prove que, se $n \geq 3, D_{n}=(n-1)\left(D_{n-1}+D_{n-2}\right)$.

6. Prove que (delinindo $D_{0} \quad$ !)

- $n!=\binom{n}{0} D_{n}+\binom{n}{1} D_{n-1}+\binom{n}{2} D_{n-2}+\cdots+\binom{n}{n} D_{0}$.

7. Prove que $D_{n}-n D_{n-1}+(-1)^{n}$ para $n \geq 2$.
8. Dois médicos devem examinar. durante uma mesma hora, 6 pacientes, gastando 10 minutos com cada paciente. Cada um dos 6 pacientes deve ser examinado pelos dois médicos. De quantos modos pode ser feito um horário compatível?
9. Quantas são as permutaçòes de $(1,2, \ldots, 2 n)$ nas quais nenhum número impar ocupa o seu lugar primitivo?

# 3.3 Os Lemas de Kaplansky 

De quantos modos é possivel formar um $p$-subconjunto (isto é, um subconjunto com $p$ elementos) de $\{1,2, \ldots, n\}$ no qual não haja numero conserutivos? Por exemplo, para $n=6$ e $p-3$, podemos obter a partir de $\{1,2,3,4,5,6\}$ os seguintes 3 -subconjuntos nos quais nào há elementos consecutivos:

$$
\{1,3,5\}, \quad\{1,3,6\}, \quad\{1,4,6\}, \quad\{2,4,6\}
$$

Poderíamos ter concluido que há quatro 3 -subconjuntos de $\{1,2,3$, $4,5.6\}$ sem elementos consecutivos sem necessidade de enumerálos exaustivamente. Ao formar um subconjunto, marcamos com o sinal + os elementos do conjunto que farão parte do subconjunto e com o sinal - os elementos que não farão parte do subconjunto. Assim,
$\{1,3,5\}$ seria representado por $+-+-+-$;
$\{2.3,6\}$ (que não é um subconjunto válido pois 2 e 3 são consecutivos) seria marcado $-++--+$.

Ora, para formar um 3-subconjunto sem elementos consecutivos devemos colocar 3 sinais + e 3 sinais - em fila, sem que haja dois sinais + consecutivos. Para fazer isso, colocamos os sinais - ( 1 modo), e colocamos os sinais + nos 4 espaços assinalados, na figura 3.2, com no máximo um sinal por espaço ( $C_{n}^{3}$ modos). A resposta é então, $1 \times C_{n}^{3}=4$.

# $\cup \cup \cup \cup$ 

Fig. 3.2
No caso geral temos $p$ sinais $+, n-p$ sinais - para arrumar sem que haja dois sinais + consecutivos. Temos 1 modo de colocar os sinais - e $C_{n-p+1}^{p}$ modos de colocar os sinais + .

Acabamos de obter o
Primeiro Lema de Kaplansky: O número de p-subconjuntos de $\{1,2, \ldots, n\}$ nos quais não há números consecutivos é

$$
f(n, p)=C_{n-p+1}^{p}
$$

Exemplo 3.5: As três provas de um vestibular devem ser realizadas na primeira semana do ano. De quantos modos é possivel escolher os dias das provas de modo que não haja provas em dias consecutivos?

Solução: Devemos formar um subconjunto de 3 elementos no conjunto dos 7 dias da primeira semana, de morlo que não haja dias consecutivos no subconjunto. A resposta é

$$
f(7,3)=C_{7-3+1}^{3}=C_{5}^{3} \div 10
$$

Exemplo 3.6: Uma fila tem 15 cadeiras nas quais devem sentarse 5 homens, de modo que não fiquem dois homens sentados em cadeiras contiguas. De quantos modos isso pode ser feito?

Solução: Devemos inicialmente escolher 5 cadeiras sem que haja cadeiras consecutivas. Isso pode ser feito de $f(15,5)=C_{15-5+1}^{5}=$ $C_{11}^{5}$ modos; escolhidas as 5 cadeiras, devemos designar a cada homem uma cadeira, o que pode ser feito de $P_{5}=5$ ! modos. A resposta é $C_{11}^{5} \times 5!=55440$.

Exemplo 3.7: Quantos são os anagramas da palavra MISSISSIPI nos quais não há duas letas $S$ consecutivas?

Solução: Devemos colocar as letras de MISSISSIPI nas casas abaixo:

Devemos inicialmente escolher 4 casas sem que haja casas consecutivas para colocar as letras $S$, o que pode ser feito de $f(10,4)=C_{10-4+1}^{4}=C_{7}^{4}=35$ modos.

Agora devemos arrumar as letras restantes ( 4 letras $l, 1$ letra $M$ e 1 letra $P$ ) nas 6 casas restantes, o que pode ser feito de

$$
P_{6}^{4,1,1}=\frac{6!}{4!1!1!}=30
$$

modos. A resposta é $35 \times 30=1050$.
Suponhamos agora que os elementos de $\{1,2, \ldots, n\}$ estejam arrumados em circulo, como na figura 3.3.
![img-16.jpeg](img-16.jpeg)

Fig. 3.3

Agora os elementos " 1 " e " $n$ " são consecutivos. De quantos modos é possivel formar um $p$-subconjunto de $\{1,2, \ldots, n\}$ no qual não haja números consecutivos? Ora, o número total de subconjuntos será a soma do número de subconjuntos nos quais o elemento " 1 " figura com o número de subconjuntos nos quais o elemento " 1 " não figura.
a) Subconjuntos nos quais o elemento " 1 " figura. Para formálos devemos escolher $p-1$ elementos em $\{3,4, \ldots, n-1\}$ (pois se o " 1 " figura, o " 2 " e o " $n$ " não podem figurar) para serem os companheiros do " 1 " no subconjunto, não podendo ser escolhidos elementos consecutivos. O número de modos de que isso pode ser feito é

$$
f(n-3 ; p-1)=C_{n-3-(p-1)+1}^{p-1}=C_{n-p-1}^{p-1}
$$

b) Subconjuntos nos quais o elemento " 1 " não figura. Para formá-los devemos escolher $p$ elementos em $\{2,3, \ldots, n\}$, não podendo ser escolhidos elementos consecutivos. Isso pode ser feito de $f(n-1, p)=C_{n-1-p+1}^{p}=C_{n-p}^{p}$ modos. Portanto, a resposta é

$$
\begin{aligned}
C_{n-p-1}^{p-1}+C_{n-p}^{p} & =\frac{(n-p-1)!}{(p-1)!(n-2 p)!}+\frac{(n-p)!}{p!(n-2 p)!} \\
& =\frac{(n-p-1)!p+(n-p)!}{p!(n-2 p)!} \\
& =(n-p-1)!\frac{p+(n-p)}{p!(n-2 p)!} \\
& =n \frac{(n-p-1)!}{p!(n-2 p)!} \\
& =\frac{n}{n-p} \frac{(n-p)!}{p!(n-2 p)!} \\
& =\frac{n}{n-p} C_{n-p}^{p}
\end{aligned}
$$

Acabamos de obter o

Segundo Lema de Kaplansky: O número de $p$-subconjuntos de $\{1,2, \ldots, n\}$ nos quais não há números consecutivos é, considerando 1 e $n$ como consecutivos, igual a

$$
g(n, p)=\frac{n}{n-p} C_{n-p}^{p}
$$

Os Lemas de Kaplansky foram construíios em 1943 pelo matemático canadense-americano Irving Kaplansky para a resolução do chamado Problema de Lucas que se encontra no Apêndice 2.

Exemplo 3.8: Hugo deve ter aula de tênis três vezes por semana, durante um semestre. Quantos são os modos de escolher os dias de aula, se Hugo não deseja ter aulas em dias consecutivos?

Solução: Hugo deve escolher 3 dos elementos do conjunto domingo, segunda, terço, quarto, quinto, sexta, sábado, não podendo escolher dois dias consecutivos e sendo o domingo e o sábado dias consecutivos. O número de modos de fazer isso é

$$
g(7,3)=\frac{7}{7-3} C_{7-3}^{3}=\frac{7}{4} \cdot 4=7
$$

# Exercícios 

1. 5 pessoas devem se sentar em 15 cadciras colocadas em torno de uma mesa circular. De quantos modos isso pode ser feito se não deve haver ocupação simultânea de duas cadciras adjacentes?
2. Dado um decágono, quantos são os triângulos cujos vértices são vértices não-consecutivos do decágono?
3. De quantos modos podemos formar uma seqüência de $p$ elementos iguais a 1 c $q$ elementos iguais a 0 sc dois elementos iguais a zero não podem ser adjacentes?

4. De quantos modos podemos formar uma seqüencia de $p$ elementos iguais a 2 , $q$ elementos iguais a 1 e $r$ elementos iguais a 0 se dois elementos iguais a zero não podem ser adjacentes?
5. De quantos modos é possível formar uma roda de ciranda com 7 meninas e 12 meninos sem que haja duas meninas em posições adjacentes?
6. Quantos são os anagramas de araraquara que não possiuem duas letras a consecutivas?
7. (Generalização do $1^{\circ}$ Lema de Kaplansky).

De quantos modos é possível formar um $p$-subconjunto de $\{1,2, \ldots, n\}$ de modo que entre cada dois elementos escolhidos para o subconjunto haja, no conjunto, pelo menos $r$ elementos não escolhidos para o subconjunto?
8. (Generalização do $2^{\circ}$ Lema de Kaplansky). Refaça o problema anterior no caso circular. Nesse caso, por exemplo, tomando $n=6$, o conjunto $\{1,2,3,4,5,6\}$ é tal que entre 1 e 4 há dois elementos, entre 5 e 1 há um elemento, entre 6 e 4 há três elementos. (Sugestão: divida os subconjuntos em dois grupos: aqueles que contêm algum dos elementos $1,2, \ldots, r$ e os que não contêm nenhum dos elementos $\{1,2, \ldots, r\})$.

# 3.4 O Princípio da Reflexão 

Uma partícula, estando no ponto $(x, y)$, pode se movimentar para o ponto $(x+1, y+1)$ ou para o ponto $(x+1, y-1)$.
a) Quantos são os trajetos possíveis da partícula de $(0,0)$ a $(8,6)$ ?

![img-17.jpeg](img-17.jpeg)

Fig. 3.4
Os movimentos permitidos para a partícula são de subida $S:(x, y) \rightarrow(x+1, y+1)$ ou de descida, $D:(x, y) \rightarrow(x+1, y-1)$. Na figura 3.4 o trajeto descrito pela partícula foi SSDSSSSS.

Para que ela vá de $(0,0)$ a $(8,6)$ devemos ter $S+D=8$ (em cada movimento, de subida ou descida, a abscissa da particula avança uma unidade. Como de $(0,0)$ a $(8,6)$ sua abscissa avançou 8 unidades, o total de movimentos de subida e descida deve ser 8) e $S-D=6$ (cm cada movimento de subida a ordenada aumenta uma unidade e em cada movimento de descida a ordenada diminui uma unidade). Daí $S=7$ e $D=1$.

O número de trajetos é $P_{8}^{7,1}=\frac{8!}{7!1!}=8$.
Iima interessante paráfrase desse problema é a seguinte: numa eleição há 8 eleitores e dois candidatos. Se o candidato $S$ ganha por 6 votos de diferença, de quantos modos pode marchar a apuração?

O gráfico indica cm cada ponto $(x, y)$ quantos votos já foram apurados $(x)$ e qual a vantagem do candidato $A(y)$.

Por exemplo, a presença do ponto (3,1) no gráfico do trajeto indica que quando o $3^{\text {u }}$ voto acaba de ser apurado, o candidato $S$ tem uma vantagem de um voto.

b) Quantos são os trajetos de $(0,0)$ a $(10,4)$ ?

Temos $S+D=10$ e $S-D=4$. Logo, $S=7, D=3$ e a resposta é

$$
P_{10}^{7.3}=\frac{10!}{7!3!}=120
$$

Parafraseando, em uma eleição com 2 candidatos $S$ e $D$ e 10 eleitores, a qual é vencida pelo candidato $S$ por 4 votos de diferença, há 120 modos de marchar a apuração.
c) Quantos desses trajetos tocam na reta $y=-1$ ?

Todo trajeto de $(0,0)$ a $(10,4)$ que toque na reta $y=-1$ pode ser transformado, por uma reflexão em torno da reta $y=-1$ do trecho do trajeto entre $(0,0)$ e o primeiro toque na reta $y=-1$, em um trajeto do ponto $(0,-2)$ até o ponto $(10,4)$. Reciprocamente, todo trajeto do ponto $(0,-2)$ até o ponto $(10,4)$ (um tal trajeto obrigatoriamente toca na reta $y=-1$ ) pode ser transformado (por uma reflexão em torno da reta $y=-1$ do trecho entre $(0,0)$ e o primeiro toque na reta $y=-1$ ) em um trajeto de $(0,0)$ a $(10,4)$ que toca na reta $y=-1$.
![img-18.jpeg](img-18.jpeg)

Fig. 3.5

Acabamos de provar que o número de trajetos de $(0,0)$ a $(10,4)$ que tocam na reta $y=-1$ é igual ao número de caminhos de $(0,-2)$ a $(10,4)$. Esse último é fácil de calcular. Temos $S+D=10$ e $S-D \cdot 6$; sendo $S=8$ e $D=2$. A resposta é $P_{10}^{8,2}=45$.

Parafraseando, em uma eleição com dois candidatos, 10 eleitores, vencida pelo candidato $S$ por 4 votos de diferença, em 45 das 120 possiveis marchas da apuração, o candidato perdedor em: algum momento esteve em vantagem. É interessante observar como as aparéncias enganam. O candidato $S$ tem $70 \%$ da votação. No entanto em $45 / 120=37,5 \%$ das apurações possíveis em algum momento ele está em desvantagem.

A técnica usada para resolver a parte c) é conhecida pelo nome de Princípio da Reflexão.

# Exercícios 

1. Numa fila de cinema. $m$ pessoas tem notas de $\mathrm{R} \$ 5,00$ e $n(n<$ $m$ ) pessoas tem notas de R $\$ 10,00$. A entrada custa $\mathrm{R} \$ 5,00$.
a) Quantas são as filas possíveis?
b) Quantas são as filas que terão problemas de troco se a bilheteria começa a trabalhar sem troco?
c) Quantas são as filas que terão problemas de troco se a bilheteria começa a trabalhar com duas notas de $\mathrm{R} \$ 5,00$ ?
2. Numa eleição com dois candidatos $A$ e $B$, há 20 eleitores e o candidato $A$ vence por $15 \times 5$. Quantas são as marchas da apuração:
a) Possíveis?
b) Nas quais o candidato $A$ permanece em vantagem (nem sequer cmpata) desde o primeiro voto apurado?
c) Nas quais o candidato $A$ permanece sempre em vantagem on empatado com o candidato $B$ ?

# 3.5 O Princípio de Dirichlet 

A Análise Combinatória não se ocupa apenas com a contagem de elementos de conjuntos. Muitas vezes, o que se deseja é determinar a existência ou não de conjuntos satisfazendo a certas propriedades. Uma ferramenta simples para resolver alguns desses problemas é o Principio das gavetas de Dirichlet*.

Princípio das gavetas de Dirichlet: Se $n$ objetos forem colocados em no máximo, $n-1$ gavetas então pelo menos uma delas conterá pelo menos dois objetos.

Prova: (por absurdo) Se cada uma das gavetas contiver, no máximo, um objeto, o número total de objetos nelas colocados será, no máximo, $n-1$, o que é uma contradição.

Exemplo 3.9: Dado um conjunto de 13 pessoas, pelo menos duas delas aniversariam no mesmo mês.

Exemplo 3.10: Escolha, dentre os elementos do conjunto $\{1,2, \ldots, 200\}, 101$ números ao acaso. Mostre que, entre os números escolhidos, há dois números tais que um deles divide o outro.

Solução: Observe, em primeiro lugar, que qualquer inteiro $n$ se escreve sob a forma $n=2^{r} b$, onde $r$ é um inteiro não-negativo e $b$ é um inteiro ímpar. Por exemplo, $36=2^{2} \cdot 9,25=2^{0} \cdot 25$, $16=2^{4} \cdot 1$.

Assim, se $n \in\{1,2, \ldots, 200\}, n=2^{r} b$ e $b$ é um dos inteiros ímpares $1,3,5, \ldots, 199$. Ora, há 100 possibilidades para $b$. Se escolhemos 101 números, dois deles terão o mesmo $b$. Sejam esses número $n_{1}=2^{r_{1}} b$ e $n_{2}=2^{r_{2}} b$. Se $r_{1}<r_{2}, n_{1}$ divide $n_{2}$. Se $r_{2}<r_{1}, n_{2}$ divide $n_{1}$, o que conclui a demonstração.

Exemplo 3.11: Escolhem-se 5 pontos ao acaso sobre a superfície de um quadrado de lado 2. Mostre que pelo menos um dos segmentos que eles determinam tem comprimento menor que ou igual a $\sqrt{2}$.

[^0]
[^0]:    *Fetor Custav Lejeune Dirichlet (1805- 1859), matemático alemào.

Solução: Divida o quadrado de lado 2 em quatro quadrados de lado 1. Dos 5 pontos, pelo menos dois pertencerão a um mesmo quadrado de lado 1. A distância entre esses dois pontos será no máximo igual à diagonal do quadrado que é $\sqrt{2}$, o que conclui a demonstração.
![img-19.jpeg](img-19.jpeg)

Fig. 3.8
Exemplo 3.12: Mostre que em um conjunto de $n$ pessoas há sempre duas pessoas que conhecem exatamente o mesmo número de pessoas do conjunto. (Obs.: Se $a$ conhece $b, b$ conhece $a$, ou seja, "conhecer" é uma relação simétrica.)

Solução: Observe, em primeiro lugar, que qualquer das pessoas do conjunto conhece no mínimo 0 e no máximo $n-1$ das outras pessoas. Observe, em segundo lugar, que se alguma das pessoas conhece todas as outras $n-1$ pessoas então é impossível que haja alguma pessoa conhecendo 0 outras. Usemos agora o princípio de Dirichlet pondo na $1^{\text {a }}$ gaveta as pessoas que conhecem 0 outras, na $2^{a}$ gaveta as pessoas que conhecem 1 outra,..., na $n^{a}$ gaveta as pessoas que conhecem $n-1$ outras. Apesar de termos $n$ gavetas, as $n$ pessoas são colocadas em, no máximo, $n-1$ gavetas, pois pela segunda observação a primeira e a última das gavetas não podem ser ocupadas simultaneamente.

Exemplo 3.13: É dado um conjunto $A=\left\{a_{1}, a_{2}, \ldots, a_{m}\right\}$ de $m$ números inteiros $(m>1)$. Mostre que existem naturais $r$ e $l$,

$1 \leq r \leq l \leq m$, tais que $a_{r}+a_{r+1}+\cdots+a_{l}$ é múltiplo de $m$.
Solução: Considere as somas

$$
\begin{aligned}
S_{1} & =a \\
S_{2} & =a_{1}+a_{2} \\
S_{3} & =a_{1}+a_{2}+a_{3} \\
& \vdots \\
S_{m} & =a_{1}+a_{2}+a_{3}+\cdots+a_{m}
\end{aligned}
$$

Se alguma dessas somas (digamos $S_{j}$ ) for divisível por $m$, a demonstração está concluída (nesse caso $r=1$ e $l=j$ ). Caso contrário, nenhuma dessas somas divididas por $m$ deixará o resto nulo. Os restos possíveis são, portanto, $1,2, \ldots, m-1$. Como há $m$ somas e apenas $m-1$ restos possíveis, pelo princípio de Dirichlet, há duas delas, que chamaremos de $S_{i}$ e $S_{j}$, que divididas por $m$ deixam restos iguais. Suponha $i>j$. Então

$$
S_{i}-S_{j}=a_{j+1}+a_{j+2}+\cdots+a_{i}
$$

é múltiplo de $m$ e o resultado está demonstrado $(r=j+1, l=i)$.
O princípio de Dirichlet pode ser reformulado do modo seguinte:

Se $m$ objetos sáo colocados em $n$ gavetas, entäo pelo menos uma gaveta contém $[(m-1) / n \mid+1$ objetos.
(Obs: $|x|$ é o maior inteiro menor que ou igual a $x$ ).
Prova: Se cada gaveta contiver no máximo $[(m-1) / n]$ objetos, então o número de objetos será no máximo

$$
n\left[\frac{m-1}{n}\right] \leq n \cdot \frac{m-1}{n}=m-1<m
$$

o que é uma contradição.

Excmplo 3.14: Em um grıpo de 40 pessoas, pelo menos 4 pessoas têm o mesmo signo.

Solução: Com efeito, colocando cada pessoa (objeto) na gaveta do seu signo, temos $m=40$ e $n=12$. Logo, pelo menos uma gaveta conterá $\left[\frac{40-1}{12}\right]+1=4$ objetos.

Há ainda outra formulação possível:
Sejam $n$ gavetas e seja $\mu$ um inteiro positivo dado. Coloupuemos $a_{1}$ objetos na $1^{3}$ gaveta, $a_{2}$ objetos na $2^{3}$ gaveta e assim sucessivamente até $a_{n}$ objetos na $n$-ésima gaveta. Então se a média $\left(a_{1}+a_{2}+\cdots+a_{n}\right) / n$ for maior que $\mu$, uma das gavetas conterá pelo menos $\mu+1$ objetos.

Prova: Se todos os $a_{i}$ fossem menores que $\mu+1$, teríamos

$$
\begin{gathered}
a_{1} \leq \mu \\
a_{2} \leq \mu \\
\vdots \\
a_{n} \leq \mu
\end{gathered}
$$

Daí, $a_{1}+a_{2}+\cdots+a_{n} \leq n \mu \mathrm{e}$

$$
\frac{a_{1}+a_{2}+\cdots+a_{n}}{n} \leq \mu
$$

o que é uma contradição.
Em suma, se uma média aritmética de números for major que $\mu$ então pelo menos um dos números é maior que $\mu$.

Exemplo 3.15: São dados dois discos $A$ e $B$, cada um deles dividido em 200 setores iguais, os quais estão pintados de branco ou de preto. No disco $A$ há 100 setores brancos e 100 setores pretos, em ordem desconhecida. No disco $B$ não sabemos quantos setores são brancos. Colocuemos o disco $A$ sobre o disco $B$, de modo que os setores de $A$ fiquem exatamente sobre os setores de

B. É possivel então, rodando o disco $A$, obter uma posição na qual pelo menos 100 setores de $A$ tenham a mesma cor que os correspondentes de $B$.

Prova: Coloque $A$ sobre $B$. Seja $a_{1}$ o número de setores sobrepostos que têm cores coincidentes. Gire $A$ de um setor (isto é de $360^{\circ} / 200$ ) mantendo $B$ fixo. Seja então $a_{2}$ o número de setores sobrepostos que têm cores coincidentes. Continue com esse processo até obter $a_{200}$. Então o número total de coincidências é $a_{1}+a_{2}+\cdots+a_{200}=100 \times 200$.

Com efeito, fixe um setor do disco $B$ (preto, por exemplo). Como $A$ tem 100 setores pretos, haverá 100 posiçōes em que esse setor de $B$ terá a mesma cor que o correspondente setor de $A$. Assim o número total de coincidências será 100 vezes o número de setores de $B$.

Daí temos

$$
\frac{\left(a_{1}+a_{2}+\cdots+a_{200}\right)}{200}:-100>99
$$

Se a média é maior que 99 , pelo menos um dos $a_{i}$ é também maior que 99 , ou seja, algum $a_{i}$ é maior que ou igual a 100 . Em suma, em alguma posição o número de coincidências é maior que ou igual a 100 .

# Exercícios 

1. Em uma gaveta há 12 meias brancas e 12 meias pretas. Quantas meias devemos retirar ao acaso para termos certeza de obter um par de meias da mesma cor?
2. 63127 candidatos compareceram a uma prova do vestibular ( 25 questōes de múltipla-escolha com 5 alternativas por questão). Considere a afirmação: "Pelo menos dois candidatos responderam de modo idêntico as $k$ primeiras questōes da prova". Qual é o

maior valor de $k$ para o qual podemos garantir que a afirmação acima é verdadeira?
3. Refaça o problema anterior para a afirmação: "Pelo menos 4 candidatos responderam de modo idêntico as $k$ primeiras questões da prova".
4. Um ponto $(x, y, z)$ do $\mathbf{R}^{3}$ é inteiro se todas suas coordenadas são inteiras.
a) Considere um conjunto de nove pontos inteiros do $\mathbf{R}^{3}$. Mostre que o ponto médio de algum dos segmentos que ligam esses pontos é inteiro.
b) Dê um exemplo de um conjunto de oito pontos inteiros do $\mathbf{R}^{3}$ tais que nenhum dos pontos médios dos segmentos que ligam esses pontos é inteiro.
5. Qual é o número mínimo de pessoas que deve haver em um grupo para que possamos garantir que nele haja pelo menos 5 pessoas nascidas no mesmo més?
6. Mostre que em todo $(n+1)$ subconjunto de $\{1,2, \ldots, 2 n\}$ há um par de elementos tais que um deles divide o outro.
7. Prove que todo número natural tem um múltiplo que se escreve, na base 10 , apenas com os algarismos 0 e 1.
8. Prove que em qualquer conjunto de 52 inteiros existe um par de inteiros cuja soma ou cuja diferença é divisível por 100 .
9. Prove que dado qualquer conjunto de dez inteiros positivos de dois dígitos cada, é possível obter dois subconjuntos disjuntos cujos elementos têm a mesma soma.
10. Considere 1990 pontos em um plano. Prove que quaisquer très semiplanos, tais que cada um deles contém mais de 1327 desses pontos, tèm interseção não-vazia.
11. Mostre que se escolhemos 800 pontos dentro de um cubo de aresta 10 , pelo menos um dos segmentos determinados por esses pontos tem comprimento menor que 2.

12. Sejam $x$ um número real e $n$ um inteiro positivo. Mostre que entre os números $x, 2 x, 3 x, \ldots,(n-1) x$ existe um cuja distância a algum inteiro é, no máximo, $1 / n$.
13. Um mestre de xadrez, preparando-se para um torneio, joga, durante onze semanas, pelo menos uma partida por dia mas não mais que doze partidas por semana. Prove que existe um conjunto de dias consecutivos durante os quais ele joga exatamente 20 partidas.
14. Seja $n$ um inteiro ímpar maior que 1 e seja $A$ uma matriz $n \times$ $n$ simétrica tal que cada linha e cada coluna de $A$ é formada pelos números $\{1,2, \ldots, n\}$ escritos em alguma ordem. Mostre que cada um dos inteiros $\{1,2, \ldots, n\}$ aparece na diagonal principal de $A$.
15. Prove que se o conjunto $\{1,2, \ldots, 1978\}$ é partido em 6 subconjuntos, em algum desses subconjuntos existe um elemento que é igual a à soma de dois elementos, não necessariamente distintos, do mesmo subconjunto.

# 4. Números Binomiais 

### 4.1 O Triângulo de Pascal

Chamamos de Triângulo de Pascal o quadro

| $C_{0}^{0}$ |  |  |  |  | 1 |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $C_{1}^{0}$ | $C_{1}^{1}$ |  |  |  | 1 | 1 |  |  |  |
| $C_{2}^{0}$ | $C_{2}^{1}$ | $C_{2}^{2}$ |  |  | 1 | 2 | 1 |  |  |
| $C_{3}^{0}$ | $C_{3}^{1}$ | $C_{3}^{2}$ | $C_{3}^{3}$ |  | 1 | 3 | 3 | 1 |  |
| $C_{4}^{0}$ | $C_{4}^{1}$ | $C_{4}^{2}$ | $C_{4}^{3}$ | $C_{4}^{4}$ | 1 | 4 | 6 | 4 | 1 |

formado pelos números $C_{n}^{p}$ (chamados Números Binomiais, Coeficientes Binomiais ou ainda Números Combinatórios). Se contamos as linhas c colunas do Triângulo começando em zero, o elemento da linha $n$ e coluna $p$ é $C_{n}^{p}$.

Uma propriedade dos números binomiais que nos permite construir rapidamente o Triângulo de Pascal é a
Relação de Stifel: $C_{n}^{p}+C_{n}^{p+1}=C_{n+1}^{p+1}$.
Ou seja, somando dois elementos consecutivos de uma mesma linha obtemos o elemento situado abaixo da última parcela.

Justificativa: Consideremos um grupo formado por uma mulher e $n$ homens. O número de modos de selecionat nesse grupo

um subgrupo formado por $p+1$ pessoas é $C_{n+1}^{p+1}$. O número de modos de selecionar um subgrupo formado pela mulher e por $p$ homens é $1 \times C_{n}^{p}=C_{n}^{p}$ e o número de modos de selecionar um subgrupo de $p+1$ pessoas formado só por homens é $C_{n}^{p+1}$.

1
![img-20.jpeg](img-20.jpeg)

Fig. 4.1

Como o número total de subgrupos é a soma do número de subgrupos dos quais a mulher participa com o número de subgrupos dos quais a mulher não participa. temos

$$
C_{n+1}^{p+1}=C_{n}^{p}+C_{n}^{p+1}
$$

Repare que no triângulo de Pascal a linha $n$ começa cm $C_{n}^{0}$ e termina em $C_{n}^{n}$. Portanto $C_{n}^{p}$ (que está na linha $n$ avançado em $p$ coluna sem relação ao início da linha) e $C_{n}^{n-p}$ (que está na linha $n$ atrasado em $p$ colunas em relação ao fim da linha) são elementos da linha $n$ que estão situados em posições equidistantes dos extremos. Números como $C_{n}^{p}$ e $C_{n}^{n-p}$ são chamados de Combinaçöes Complementares. Assim, por exemplo, a complementar de $C_{12}^{4}$ é $C_{12}^{12-4}=C_{12}^{8}$.
Relação das Combinações Complementares: $C_{n}^{p}=C_{n}^{n-p}$. Ou seja, em uma mesma linha do triângulo de Pascal, elementos equidistantes dos extremos sâo iguais.

# Justificativa: 

$$
C_{n}^{n-p}=\frac{n!}{(n-p)![n-(n-p)!]}=\frac{n!}{(n-p)!p!}=C_{n}^{p}
$$

Teorema das Linhas: $C_{n}^{0}+C_{n}^{1}+C_{n}^{2}+\cdots+C_{n}^{n}=2^{n}$. On seja, a soma dos elementos da linha $n$ vale $2^{n}$.

Justificativa: $C_{n}^{p}$ é o número de subconjuntos com $p$ elementos do conjunto $A=\{1,2, \ldots, n\}$. Então $C_{n}^{0}+C_{n}^{1}+C_{n}^{2}+\cdots+C_{n}^{n}$ é o número total de subconjuntos de $A$. Mas, para formar um subconjunto de $A=\{1,2, \ldots, n\}$ devemos marcar cada elemento de $A$ com o sinal + (indicando que o elemento foi escolhido para o subconjunto) ou com o sinal - (indicando que o elemento não foi escolhido). Como o número de modos de marcar os elementos é, $2 \times 2 \times \cdots \times 2=2^{n}$, provamos que o número de subconjuntos de um conjunto com $n$ elementos é

$$
C_{n}^{0}+C_{n}^{1}+\cdots+C_{n}^{n}=2^{n}
$$

Exemplo 4.1: Qual é o valor da soma

$$
S=C_{n}^{1}+2 C_{n}^{2}+3 C_{n}^{3}+\cdots+n C_{n}^{n} ?
$$

Solução:

$$
\begin{aligned}
S & =\sum_{k=1}^{n} k C_{n}^{k} \\
& =\sum_{k=1}^{n} k \frac{n!}{k!(n-k)!} \\
& =\sum_{k=1}^{n} \frac{n!}{(k-1)!(n-k)!} \\
& =\sum_{k=1}^{n} n \frac{(n-1)!}{(k-1)!(n-k)!}
\end{aligned}
$$

$$
\begin{aligned}
& =\sum_{k=1}^{n} n C_{n-1}^{k-1} \\
& =n \sum_{k=1}^{n} C_{n-1}^{k-1} \\
& =n\left[C_{n-1}^{0}+C_{n-1}^{1}+C_{n-1}^{2}+\cdots+C_{n-1}^{n-1}\right] \\
& =n \cdot 2^{n-1}
\end{aligned}
$$

# Teorema das Colunas: 

$$
C_{p}^{p}+C_{p+1}^{p}+C_{p+2}^{p}+\cdots+C_{p+n}^{p}=C_{p+n+1}^{p+1}
$$

Ou seja, a soma dos clementos de uma coluna do triângulo (começando no primeiro elemento da coluna) é igual ao elemento que está avançado uma linha e uma coluna sobre a última parcela da soma.

1
1
1
1
1
1
1
1
1
10
10
![img-21.jpeg](img-21.jpeg)

Fig. 4.2

Justificativa: Apliquemos a relação de Stifel aos elementos da

coluna $p+1$ :

$$
\begin{aligned}
& C_{p+1}^{p+1}=C_{p}^{p+1}+C_{p}^{p} \\
& C_{p+2}^{p+1}=C_{p+1}^{p+1}+C_{p+1}^{p} \\
& C_{p+3}^{p+1}=C_{p+2}^{p+1}+C_{p+2}^{p} \\
& \vdots \\
& C_{p+n}^{p+1}: C_{p+n-1}^{p+1}+C_{p+n-1}^{p} \\
& C_{p-n+1}^{p+1}=C_{p+n}^{p+1}+C_{p+n}^{p}
\end{aligned}
$$

Somando (e simplificando parcelas iguais que aparecem em membros opostos) obtemos

$$
\begin{aligned}
C_{p+n+1}^{p+1} & =C_{p}^{p+1}+C_{p}^{p}+C_{p+1}^{p}+C_{p+2}^{p}+ \\
& +\cdots+C_{p+n-1}^{p}+C_{p+n}^{p}
\end{aligned}
$$

Observando que $C_{p}^{p+1}=0$, temos

$$
\begin{aligned}
C_{p+n+1}^{p-1} & =C_{p}^{p}+C_{p+1}^{p}+C_{p+2}^{p} \\
& +\cdots+C_{p+n-1}^{p}+C_{p+n}^{p}
\end{aligned}
$$

Exemplo 4.2: Qual é o valor da soma

$$
S=1 \cdot 2 \cdot 3+2 \cdot 3 \cdot 4+3 \cdot 4 \cdot 5+\cdots+50 \cdot 51 \cdot 52 ?
$$

Soluçäo:

$$
\begin{aligned}
S & =\sum_{k=1}^{50} k(k+1)(k+2) \\
& =\sum_{k=1}^{50} 3!C_{k+2}^{3} \\
& =6\left|C_{3}^{3}+C_{4}^{3}+\cdots\right| C_{52}^{3} \\
& =6 C_{53}^{4} \\
& =1756950
\end{aligned}
$$

Exemplo 4.3: Qual é o valor da soma

$$
S-1^{2}+2^{2}+\cdots+n^{2} ?
$$

Soluçāo: A soma pedicla é $S=\sum_{k=1}^{n} k^{2}$.
O exemplo anterior nos mostrou como calcular uma soma na qual cada parccia ó um produto de inteiros consecutivos. Vamos tentar transformar o polinômio do $2^{\circ}$ grau $k^{2}$ cm um polinômio do $2^{\circ}$ grau no qual apareçam cm vez de produtos de inteiros iguais, produtos de inteiros consecutivos, isto é, vamos tentar obter uma identidade do tipo

$$
k^{2} \equiv A k(k+1)+B k+C
$$

Temos

$$
\begin{aligned}
& k^{2} \equiv A k^{2}+(A+B) k+C \\
& A=1, \quad A+B=0, \quad C=0
\end{aligned}
$$

isto é,

$$
\begin{aligned}
& A=1, \quad B=-1, \quad C=0 \\
& k^{2} \equiv k(k+1)-k
\end{aligned}
$$

Entāo,

$$
\begin{aligned}
S & =\sum_{k=1}^{n} k^{2} \\
& =\sum_{k=1}^{n}|k(k+1)-k| \\
& 2 \sum_{k=1}^{n} C_{k+1}^{2}-\sum_{k=1}^{n} C_{k}^{\frac{1}{2}} \\
& =2 C_{n+2}^{3}-C_{n+1}^{2} \\
& -2 \frac{(n+2)(n+1) n}{6}-\frac{(n+1) n}{2}
\end{aligned}
$$

$$
\begin{aligned}
& =n(n+1)\left[\frac{n+2}{3}-\frac{1}{2}\right] \\
& =\frac{n(n+1)(2 n+1)}{6}
\end{aligned}
$$

Excmplo 4.4: Calcule o valor da soma

$$
S=2 \cdot 1^{2}+5 \cdot 2^{2}+8 \cdot 3^{2}+\cdots+(3 n-1) \cdot n^{2}
$$

Soluçäo:

$$
S=\sum_{k=1}^{n}(3 k-1) k^{2}=\sum_{k=1}^{n}\left(3 k^{3}-k^{2}\right)
$$

Seja

$$
3 k^{3}-k^{2} \equiv A k(k+1)(k+2)+B k(k+1)+C k+D
$$

Temos

$$
3 k^{3}-k^{2}==A k^{3}+(3 A+B) k^{2}+(2 A+B+C) k+D
$$

donde

$$
\begin{gathered}
A=3, \quad 3 A+B=-1, \quad 2 A+B+C=0, \quad D=0 \\
A=3, \quad B=-10, \quad C=4, \quad D=0 \\
3 k^{3}-k^{2}=3 k(k+1)(k+2)-10 k(k+1)+4 k
\end{gathered}
$$

Logo,

$$
\begin{aligned}
S & =\sum_{k=1}^{n}[3 k(k+1)(k+2)-10 k(k+1)+4 k] \\
& =\sum_{k=1}^{n}\left[3 \cdot 3!C_{k+2}^{3}-10 \cdot 2!C_{k+1}^{2}+4 C_{k}^{1}\right] \\
& =18 \sum_{k=1}^{n} C_{k+2}^{3}-20 \sum_{k=1}^{n} C_{k+1}^{2}+4 \sum_{k=1}^{n} C_{k}^{1} \\
& =18 C_{n+3}^{4}-20 C_{n+2}^{3}+4 C_{n+1}^{2} \\
& =18 \frac{(n+3)(n+2)(n+1) n}{24}-20 \frac{(n+2)(n+1) n}{6}+ \\
& +4 \frac{(n+1) n}{2} \\
& =(n+1) n\left[\frac{3(n+3)(n+2)}{4}-10 \frac{n+2}{3}+2\right] \\
& =\frac{(n+1) n\left(9 n^{2}+5 n-2\right)}{12}
\end{aligned}
$$

Teorema das Diagonais:

$$
C_{n}^{0}+C_{n+1}^{1}+C_{n+2}^{2}+\cdots+C_{n+p}^{p}-C_{n+p+1}^{p}
$$

Ou seja, a soma dos elementos de uma diagonal (isto é, de uma paralela à hipotenusa), do triângulo de Pascal (começando no primeiro elemento da diagonal) é igual ao elemento que está imediatamente abaixo da última parccla.

![img-22.jpeg](img-22.jpeg)

Justificativa: Temos

$$
\begin{aligned}
C_{n}^{0}+C_{n+1}^{1}+C_{n+2}^{2}+\cdots \mid C_{n+p}^{p}= & C_{n}^{n}+C_{n+1}^{n}+C_{n+2}^{n} \\
& +\cdots+C_{n+p}^{n} \\
= & C_{n+p+1}^{n+1} \\
= & C_{n+p+1}^{p}
\end{aligned}
$$

usando sucessivamente Combinações Complementares, o Teorema das Colunas e Combinações Complementares.

I'm outro fato importante é o seguinte
Teorema: $C_{n}^{p}<C_{n}^{p+1}$ se $p<\frac{n-1}{2}$ e $C_{n}^{p} \geqslant C_{n}^{p+1}$ se $p>\frac{n-1}{2}$.
Justificativa:

$$
\begin{aligned}
C_{n}^{p+1}-C_{n}^{p} & =\frac{n!}{(p+1)!(n-p-1)!}-\frac{n!}{p!(n-p)!} \\
& =\frac{n!(n-p)-n!(p+1)}{(p+1)!(n-p) 1} \\
& \frac{n!(n-1-2 p)}{(p+1)!(n-p)!}
\end{aligned}
$$

Como $n!,(p+1)$ ! e $(n-p)$ ! sāo positivos, o sinal de $C_{n}^{p+1}-C_{n}^{p}$ é o mesmo de $n-1-2 p$. Logo,

$$
C_{n}^{p+1}-C_{n}^{p}>0 \text { se } n-1-2 p>0
$$

e

$$
C_{n}^{p+1}-C_{n}^{p}<0 \text { se } n-1-2 p<0
$$

ou seja,

$$
C_{n}^{p}<C_{n}^{p-1} \text { se } p<\frac{n-1}{2}
$$

e

$$
C_{n}^{p}>C_{n}^{p-1} \text { se } p>\frac{n-1}{2}
$$

O que significa esse teorema? Ele afirma que na primeira metade de cada linha os elementos estāo em ordem crescente (cada termo é menor que o seguinte, $C_{n}^{p}<C_{n}^{p-1}$ ) e que na segunda metade os elementos estāo em ordem decrescente (cada termo é maior que o anterior, $C_{n}^{p}>C_{n}^{p-1}$ ).

Encertamos esta seção com algumas observaçōes: a expressão

$$
\binom{n}{p} \quad \frac{n(n-1) \cdots(n-p+1)}{p!}
$$

faz sentido para qualquer $n$ real, desde que $p$ seja um inteiro positivo. Definiremos entāo para qualquer $n$ real e qualquer $p$ inteiro não-negativo o binomial de $n$ sobre $p$ por

$$
\binom{n}{p}=\frac{n(n-1) \cdots(n-p+1)}{p!} \quad(p>0) \quad \text { e } \quad\binom{n}{0}-1
$$

Assim, por exemplo, temos

$$
\begin{aligned}
& \binom{1 / 2}{3}=\frac{\frac{1}{2}\left(\frac{1}{2}-1\right)\left(\frac{1}{2}-2\right)}{3!}=\frac{1}{16} \\
& \binom{-5}{4}=\frac{(-5)(-6)(-7)(-8)}{4!}=70
\end{aligned}
$$

e

$$
\binom{3}{5}=\frac{3 \cdot 2 \cdot 1 \cdot 0 \cdot(-1)}{5!}=0
$$

É claro que se $n$ é inteiro não-negativo,

$$
\binom{n}{p}=\frac{n(n-1) \cdots(n-p+1)}{p!}
$$

é igual a $C_{n}^{p}$, número de $p$-subconjuntos de um conjunto com $n$ elementos. Se $n$ não é inteiro não-negativo, $C_{n}^{p}$ não tem sentido mas

$$
\binom{n}{p}=\frac{n(n-1) \cdots(n-p+1)}{p!}
$$

continua tendo sentido.
É interessante observar que mesmo se $n$ não for um inteiro não-negativo continua sendo verdade a Relação de Stifel

$$
\text { a) } \quad\binom{n}{p}+\binom{n}{p+1}=\binom{n+1}{p+1}
$$

e o Teorema das Diagonais
b) $\binom{n}{0}+\binom{n+1}{1}+\cdots+\binom{n+p}{p}=\binom{n+p+1}{p}$.

Enquanto que o Teorema das Linhas
c) $\binom{n}{0}+\binom{n}{1}+\cdots\binom{n}{n}=2^{n}$,
o Teorema das Colunas
d) $\binom{p}{p}+\binom{p+1}{p}+\cdots+\binom{p+n}{p}=\binom{p+n+1}{p+1}$,
e o Teorema das Combinações Complementares
e) $\binom{n}{p}=\binom{n}{n-p}$,
não têm sentido se $n$ não for um inteiro não-negativo.

# Exercícios 

1. Prove, fazendo as contas, a relação de Stifel:

$$
\binom{n+1}{p+1}=\binom{n}{p}+\binom{n}{p+1}
$$

supondo $n$ um real qualquer e $p$ inteiro não-negativo.
2. Prove, por um processo análogo ao usado no texto para provar a relação de Stifel, que

$$
C_{n+2}^{p+2}=C_{n}^{F}+2 C_{n}^{p+1}+C_{n}^{p+2}
$$

3. Prove, fazendo as contas, que

$$
\binom{n+2}{p+2}=\binom{n}{p}+2\binom{n}{p+1}+\binom{n}{p+2}
$$

supondo $n$ um real qualquer e $p$ inteiro não-negativo.
4. Usando a relação de Stifel, escreva as sete primeiras linhas do triângulo de Pascal.
5. Prove, usando um argumento combinatório, que $C_{n}^{F}=C_{n}^{n-F}$.
6. Se $A$ possui 512 subconjuntos, qual é o número de elementos de $A$ ?
7. Determine um conjunto que possua exatamente 48 subconjuntos.
8. $X$ é um subconjunto próprio de $A$ se $X \subset A$ e $X \neq A ; X$ é um subconjunto não-trivial de $A$ se $X \subset A$ e $X \neq A$ e $X \neq \phi$. Se $A$ possui 5 clementos, quantos são os subconjuntos próprios de A? Quantos são os subconjuntos não-triviais de $A$ ?
9. Tem-se $n$ comprimidos de substâncias distintas, solúveis em água e incapazes de reagir entre si. Quantas soluções distintas

podern ser obtidas dissolvendo-se um ou mais desses comprimidos em um copo com água?
10. Quantos coquetéis (misturas de duas ou mais bebidas) podem ser feitos a partir de 7 ingredientes distintos?
11. Em uma sala há 7 lámpadas. De quantos modos pode ser iluminada a sala?
12. Calcule $\sum_{k=0}^{n}(k+1) C_{n}^{k}$.
13. Calcule o valor de $\sum_{k=0}^{n} k^{2} C_{n}^{k}$.
14. Calcule o valor de $\sum_{k=0}^{n} \frac{C_{n}^{k}}{k+1}$.
15. Prove, por indução, o Teorema das Linhas.
16. Prove, por indução, o Teorema das Colunas.
17. Calcule o valor da soma

$$
S=50 \cdot 51+51 \cdot 52+\cdots+100 \cdot 101
$$

18. Calcule o valor da soma

$$
S=1^{3}+2^{3}+3^{3}+\cdots+n^{3}
$$

19. Calcule o valor de

$$
S=\sum_{k=1}^{n} k(2 k+1)
$$

20. Calcule o valor da soma

$$
S=\sum_{k=1}^{n}(2 k-1)^{2}(k+2)
$$

21. Calcule o valor de

$$
S=C_{n}^{0}-C_{n}^{1}+C_{n}^{2}-\cdots+(-1)^{p} C_{n}^{p}
$$

22. Tern-se uma rede de caminhos (figura 4.4). Do ponto $A$ partem $2^{1000}$ homens. Metade parte na direção $l$ e metade na direção $m$. Ao chegar ao primeiro cruzamento cada grupo se divide: uma metade segue na direção $l$, a outra na direção $m$. O mesmo ocorre em cada cruzamento. Numcremos as linhas e os cruzamentos em cada linha a partir do zero; assim, $A$ é o zeroésimo cruzamento da linha zero. Quantos homens chegam ao $k$ ésimo cruzamento da linha $n$ ?
![img-23.jpeg](img-23.jpeg)

Fig. 4.4
23. Prove que todo poliòmio $P(x)$ de grau $p$ pode ser escrito na forma
$P(x) \equiv A_{0}+A_{1} x+A_{2} x(x+1)+\cdots+A_{p} x(x+1) \cdots(x \mid p-1)$.
24. Calcule $C R_{n}^{0}+C R_{n}^{1}+C R_{n}^{2}+\cdots+C R_{n}^{p}$.
25. Prove, usando um argumento combinatório, a Fórmula de Euler

$$
C_{m}^{0} C_{h}^{p}+C_{m}^{1} C_{h}^{p-1}+C_{m}^{2} C_{h}^{p-2}+\cdots+C_{m}^{p} C_{h}^{0}=C_{m+h}^{p}
$$

26. Prove, a partir da Fórmula de Euler, a Fórmula de Lagrange (1736-1813)

$$
\left(C_{n}^{0}\right)^{2}+\left(C_{n}^{1}\right)^{2}+\left(C_{n}^{2}\right)^{2}+\cdots+\left(C_{n}^{n}\right)^{2}=C_{2 n}^{n}
$$

27. Calcule o valor da soma

$$
S=C_{n}^{0} C_{n}^{2}+C_{n}^{1} C_{n}^{3}+\cdots+C_{n}^{n-2} C_{n}^{n}
$$

28. Calcule $\sum_{k=0}^{n} k\binom{n}{k}^{2}$.
29. Determine $p$ para que $C_{10}^{p}$ seja máximo.
30. Determine $p$ para que $C_{21}^{p}$ seja máximo.
31. Resolva a cquação $C_{41}^{p}=C_{41}^{2 p-1}$.
32. Resolva a equação $C_{15-p}^{2 p}=C_{15-p}^{9-p}$.
33. Prove que em cada coluna (exceto a coluna zero) os elementos do triângulo de Pascal estão em ordem crescente.
34. O número de Fibonacci $F_{n}$ é definido como a soma dos elementos da $n$-ésima "diagonal inversa" do Triângulo de Pascal:
![img-24.jpeg](img-24.jpeg)

Fig. 4.5

Prove que $F_{n+2}=F_{n+1}+F_{n}$.
35. $A$ é o conjunto $\{1,2, \ldots, n\}$ e $p$ é um natural tal que $1<$ $p<n$.
a) Quantos são os $p$-subconjuntos de $A$ nos quais o elemento mínimo é igual a $k$ ?
b) Formados todos os $p$-subconjuntos de $A$, em cada um deles considera-se o elemento mínimo do subconjunto. Quanto vale a média aritmética desses mínimos?
36. Prove que

$$
(-1)^{n}\binom{-n}{k-1}=(-1)^{k}\binom{-k}{n-1}
$$

37. Para que valor de $k$,

$$
\binom{2 n+k}{n} \cdot\binom{2 n-k}{n}
$$

( $n$ dado) é máximo?
38. Calcule

$$
\sum_{k=0}^{m}\binom{n}{k}\binom{n-k}{m-k} \quad(m<n)
$$

39. Calcule

$$
\sum_{k=0}^{n}\binom{n}{k}\binom{m}{k} \quad(n \geq m)
$$

40. Prove, por indução, o Teorema das Diagonais.

# 4.2 O Binômio de Newton 

Teorema: Se $x$ e a sâo mimeros reais e $n$ é um inteiro positivo,

$$
\begin{gathered}
(x+a)^{n}=\sum_{k=0}^{n}\binom{n}{k} a^{k} x^{n-k}= \\
=\binom{n}{0} a^{0} x^{n}+\binom{n}{1} a^{1} x^{n-1}+\binom{n}{2} a^{2} x^{n-2}+\cdots+\binom{n}{n} n^{n} x^{0}
\end{gathered}
$$

Observe que:
i) O desenvolvimento de $(x+a)^{n}$ possui $n+1$ termos.
ii) Os coeficientes do desenvolvimento de $(x+a)^{n}$ são os elementos da linha $n$ do Triângulo de Pascal.
iii) Fescrevendo os termos do desenvolvimento na ordem acima (isto é, ordenados segundo as potências decrescentes de $x$ ), o termo de ordem $k+1$ é

$$
T_{k+1}=\binom{n}{k} a^{k} x^{n-k}
$$

Prova: Temos

$$
(x+a)^{n} \quad(x+a)(x+a) \cdots(x+a)
$$

Cada termo do produto é obtido escolhendo-se em cada parênteses um $x$ ou um $a$ c multiplicando-se os escolhidos. Para cada valor de $k, 0 \leq k \leq n$, se escolhermos $a \mathrm{~cm} k$ dos parênteses, $x$ será escolhido em $n-k$ dos parênteses c o produto será igual a $a^{k} x^{n-k}$ $(0 \leq k \leq n)$. Isso pode ser feito de $\binom{n}{k}$ modos. Então $(x+a)^{n}$ é uma soma onde há, para cada $k \in\{0,1, \ldots, n\},\binom{n}{k}$ parcelas iguais a $a^{k} x^{n-k}$, isto é,

$$
(x+a)^{n}=\sum_{k=0}^{n} C_{n}^{k} a^{k} x^{n-k}
$$

Exemplo 4.5: Olhando para o triângulo de Pascal

| 1 |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: |
| 1 | 1 |  |  |  |  |
| 1 | 2 | 1 |  |  |  |
| 1 | 3 | 3 | 1 |  |  |
| 1 | 4 | 6 | 4 | 1 |  |

Obtemos

$$
\begin{aligned}
(x+a)^{0} & =1 a^{0} x^{0}=1 \\
(x+a)^{1} & =1 a^{0} x^{1}+1 a^{1} x^{0}=x+a \\
(x+a)^{2} & =1 a^{0} x^{2}+2 a^{1} x^{1}+1 a^{2} x^{0}=x^{2}+2 a x+a^{2} \\
(x+a)^{3} & =1 a^{0} x^{3}+3 a^{1} x^{2}+3 a^{2} x^{1}+1 a^{3} x^{0} \\
& =x^{3}+3 a x^{2}+3 a^{2} x+a^{3} \\
(x+a)^{4} & =1 a^{0} x^{4}+4 a^{1} x^{3}+6 a^{2} x^{2}+4 a^{3} x^{1}+1 a^{4} x^{0} \\
& =x^{4}+4 a x^{3}+6 a^{2} x^{2}+4 a^{3} x+a^{4}
\end{aligned}
$$

Exemplo 4.6: Determine o coeficiente de $x^{2}$ no desenvolvimento de $\left(x^{3}-1 / x^{2}\right)^{9}$.
Solução: O termo genérico do desenvolvimento é

$$
\begin{aligned}
T_{k+1} & =\binom{9}{k}\left(\frac{-1}{x^{2}}\right)^{k}\left(x^{3}\right)^{9-k} \\
& =\binom{9}{k} \frac{(-1)^{k}}{x^{2 k}} x^{27-3 k} \\
& =(-1)^{k}\binom{9}{k} x^{27-5 k}
\end{aligned}
$$

No termo em $x^{2}$ temos $27-5 k=2, k=5$. O termo em $x^{2}$ é

$$
T_{6}=(-1)^{5}\binom{9}{5} \cdot x^{2}=-126 x^{2}
$$

Resposta: -126 .
Exemplo 4.7: Determine o termo máximo do desenvolvimento de $(1+1 / 3)^{65}$.

Solução: O termo genérico do desenvolvimento é

$$
T_{k+1}=\binom{65}{k}\left(\frac{1}{3}\right)^{k} 1^{65-k}=\binom{65}{k} \cdot \frac{1}{3^{k}}
$$

$T_{k+1}>T_{k}$ (on seja, cada termo é maior que o anterior) se

$$
\binom{65}{k} \frac{1}{3^{k}}>\binom{65}{k-1} \frac{1}{3^{k-1}}
$$

isto é,

$$
\frac{65!}{k!(65-k)!3^{k}}>\frac{65!}{(k-1)!(66-k)!} \frac{1}{3^{k-1}}
$$

Assim,

$$
\frac{(66-k)!}{(65-k)!}>\frac{k!}{(k-1)!} \frac{3^{k}}{3^{k-1}} \cdot \frac{65!}{65!}
$$

isto é, $66-k>k \cdot 3 \cdot 1$, isto é, $k<16,5$. Logo, $T_{k+1}>T_{k}$ para $k \in\{1,2, \ldots, 16\}$ c, analogamente, $T_{k+1}<T_{k}$ para $k \in$ $\{17,18, \ldots, 65\}$. Logo,

$$
T_{1}<T_{2}<T_{3}<\cdots<T_{16}<T_{17}>T_{18}>\cdots>T_{66}
$$

Segue-se, então, que o termo máximo é $T_{17}=\binom{65}{16} \frac{1}{3^{18}}$.
Resposta: $\binom{65}{16} \frac{1}{3^{18}}$.
Exemplo 4.8: Qual é a soma dos coeficientes do desenvolvimento de $\left(x^{3}-2 x^{2}\right)^{15}$ ?

Solução: Ora, se

$$
P(x)=A_{0}+A_{1} x+A_{2} x^{2}+\cdots+A_{n} x^{n}
$$

temos

$$
P(1)=A_{0}+A_{1}+A_{2}+\cdots+A_{n}
$$

Em suma, a soma dos coeficientes de um polinômio em $x$ é o valor numérico do polinômio para $x=1$. A resposta é, portanto

$$
\left(1^{3}-2 \cdot 1^{2}\right)^{15}=-1
$$

Exemplo 4.9: Se na fórmula do binômio fizermos $x=a=1$, obtemos

$$
2^{n}=\binom{n}{0}+\binom{n}{1}+\binom{n}{2}+\cdots+\binom{n}{n}
$$

que dá uma outra prova do Teorema das Linhas. Se na fórmula do binômio fizermos $x=1, a=-1$ obtemos

$$
0=\binom{n}{0}-\binom{n}{1}+\binom{n}{2}+\cdots+(-1)^{n}\binom{n}{n}
$$

que é resultado importante, usado no Apêndice 1 para provar o Princípio da Inclusão-Exclusão.

Exemplo 4.10: Calcule:
a) $\sum_{k=0}^{n}\binom{n}{k} x^{k}$;
b) $\sum_{k=0}^{n} k\binom{n}{k} x^{k}$;
c) $\sum_{k=0}^{n} k\binom{n}{k}$.

Solução:
a) $\sum_{k=0}^{n}\binom{n}{k} x^{k}=(1+x)^{n}$, pela fórmula do binômio.

b)

$$
\begin{aligned}
\sum_{k=0}^{n} k\binom{n}{k} x^{k} & =\sum_{k=1}^{n} k\binom{n}{k} x^{k} \\
& =\sum_{k=1}^{n} k \frac{n(n-1) \cdots(n-k+1)}{1 \cdot 2 \cdots k} x^{k} \\
& =\sum_{k=1}^{n} n\binom{n-1}{k-1} x^{k} \\
& =n x \sum_{k=1}^{n}\binom{n-1}{k-1} x^{k-1} \\
& =n x\left[\binom{n-1}{0}+\binom{n-1}{1} x+\cdots+\binom{n-1}{n-1} x^{n-1}\right] \\
& =n x(1+x)^{n-1}
\end{aligned}
$$

Uma solução mais sofisticada seria

$$
\sum_{k=0}^{n}\binom{n}{k} x^{k}=(1+x)^{n}
$$

Derivando obtemos

$$
\sum_{k=0}^{n} k\binom{n}{k} x^{k-1}=n(1+x)^{n-1}
$$

Multiplicando ambos os membros por $x$ obtemos

$$
\sum_{k=0}^{n} k\binom{n}{k} x^{k}=n x(1+x)^{n-1}
$$

c) Fazendo $x=1 \mathrm{~cm}$ b) obtemos

$$
\sum_{k=0}^{n} k\binom{n}{k}=n \cdot 2^{n-1}
$$

Exemplo 4.11: Considere o desenvolvimento de $(x+a)^{n}$ ordenado do modo usual, isto é, segundo as potências decrescentes de $x$. Calcule a soma dos termos de ordem par desse desenvolvimento.

Solução: Temos

$$
\begin{aligned}
(x+a)^{n} & =T_{1}+T_{2}+T_{3}+T_{4}+\cdots \\
(x-a)^{n} & =T_{1}-T_{2}+T_{3}-T_{4}+\cdots
\end{aligned}
$$

Daí

$$
(x+a)^{n}-(x-a)^{n}=2\left[T_{2}+T_{4}+\cdots\right]
$$

e

$$
T_{2}+T_{4}+\cdots=\frac{(x+a)^{n}-(x-a)^{n}}{2}
$$

que é a resposta.
Exemplo 4.12: No desenvolvimento de $(x+a)^{n}$ ordenado de modo usual, temos

$$
T_{k+1}=\binom{n}{k} a^{k} x^{n-k}=\frac{n-k+1}{k}\binom{n}{k-1} a^{k} x^{n-k}
$$

e

$$
T_{k}=\binom{n}{k-1} a^{k-1} x^{n-k+1}
$$

Daí resulta

$$
T_{k+1}=\frac{n-k+1}{k} \frac{a}{x} T_{k}
$$

Portanto, para obter $T_{k+1}$ a partir de $T_{k}$ basta aumentar o expoente de $a$ em uma unidade, diminuir o expoente de $x$ em uma unidade e multiplicar o coeficiente de $T_{k}$ pelo expoente de $x$ em $T_{k}$ e dividir o produto pelo expoente de a (em $T_{k}$ ) aumentado de um unidade. Isso nos permite obter rapidamente desenvolvimentos. Por exemplo,

$$
(x+a)^{5}=x^{5}+5 a x^{4}+10 a^{2} x^{3}+10 a^{3} x^{2}+5 a^{4}+a^{5}
$$

Os coeficientes foram obtidos assim:
$1, \frac{1 \times 5}{1}=5, \frac{5 \times 4}{2}=10 ; \frac{10 \times 3}{3}=10 ; \frac{10 \times 2}{4}=5, \frac{5 \times 1}{5}=1$.
Encerramos esta seção observando que na realidade a fórmula do binômio

$$
(x+a)^{n}=\sum_{k=0}^{\infty}\binom{n}{k} a^{k} x^{n-k}
$$

é válida ainda que $n$ não seja um inteiro positivo. Prova- se (veja algum livro de Cálculo que fale sobre a série binomial) que a fórmula acima é válida para todo $x$ tal que $|x|>|a|$. Assim, por exemplo,

$$
(1+a)^{n}=1+n a+\frac{n(n-1)}{2!} a^{2}+\cdots
$$

para todo $a$ tal que $|a|<1$ c todo $n$ real.

# Exercícios 

1. Determine o termo central do desenvolvimento de

$$
\left(x^{2}-\frac{1}{x}\right)^{8}
$$

2. Determine o quinto termo do desenvolvimento de

$$
\left(2 x-\frac{1}{x^{2}}\right)^{7}
$$

a) Supondo o desenvolvimento ordenado segundo as potências crescentes da primeira parcela;
b) Supondo-o ordenado segundo as potências decrescentes da primeira parcela.

3. Determine o termo independente de $x$ no desenvolvimento de

$$
\left(x^{2}+\frac{1}{x^{3}}\right)^{10}
$$

4. Determine o coeficiente de $x^{3}$ no desenvolvimento de

$$
\left(2 x^{4}-\frac{1}{x}\right)^{12}
$$

5. Determine o coeficiente de $x^{28}$ no desenvolvimento de

$$
(x+2)^{20} \cdot\left(x^{2}-1\right)^{5}
$$

6. Determine o coeficiente de $x^{n}$ no desenvolvimento de

$$
(1-x)^{2}(1+x)^{n}
$$

7. Para que valores de $n$ o desenvolvimento de

$$
\left(2 x^{2}-\frac{1}{x^{3}}\right)^{n}
$$

possui um termo independente de $x$ ?
8. Calcule o termo máximo e o termo minimo do desenvolvimento de $(1+1 / 2)^{120}$.
9. Determine a soma dos coeficientes do desenvolvimento de

$$
\left(2 x^{2}-3 y\right)^{1991}
$$

10. Calcule a soma dos coeficientes dos termos de ordem par do desenvolvimento de $\left(2 x^{2}-3 y\right)^{n}$.
11. Qual é o maior dos números $a=101^{50}$ e $b=100^{50}+99^{50}$ ?

12. Calcule $\sum_{k=0}^{n} C_{n}^{k} 2^{k}$.
13. Calcule $\sum_{k=0}^{n} k\binom{n}{k} 3^{k}$.
14. Determine o coeficiente de $x^{6}$ no desenvolvimento de

$$
\left(2 x+\frac{1}{x^{2}}\right)^{3} \cdot\left(x^{2}+\frac{1}{2 x}\right)^{3}
$$

15. Calcule o valor da soma

$$
C_{20}^{0}-\frac{C_{20}^{1}}{2}+\frac{C_{20}^{2}}{2}-\cdots+\frac{C_{20}^{20}}{2^{20}}
$$

16. Prove que $\left[(2+\sqrt{3})^{n}\right]$ é ímpar para todo $n$ natural (Obs: $|\rangle=$ parte inteira).
17. A é um conjunto com $n$ elementos e $B$ é um seu $p$-subconjunto.
a) Quantos são os conjuntos $X$ tais que $B \subset X \subset A$ ?
b) Quantos são os pares ordenados $(Y, Z)$ tais que $Y \subset Z \subset$ $A$ ?
18. Partindo de

$$
(x+1)^{n} \cdot(1+x)^{n}=(x+1)^{2 n}
$$

e igualando coeficientes adequados, prove mais uma vez a Fórmula de Lagrange:

$$
\left(C_{n}^{0}\right)^{2}+\left(C_{n}^{1}\right)^{2}+\cdots+\left(C_{n}^{n}\right)^{2}=C_{2 n}^{n}
$$

19. Partindo de

$$
(x+1)^{n} \cdot(x+1)^{m}=(x+1)^{m+h}
$$

e igualando coeficientes adequados, prove mais uma vez a Fórmula de Euler

$$
C_{m}^{0} C_{h}^{p}+C_{m}^{\frac{1}{2}} C_{h}^{p-1}+\cdots+C_{m}^{p} C_{h}^{0}=C_{m+h}^{p}
$$

20. Prove que $47^{47}+77^{77}$ é divisível por 4 .
21. Calcule o valor de:
a) $C_{n}^{1}+C_{n}^{3}+C_{n}^{5}+\cdots$;
b) $C_{n}^{0}+C_{n}^{2}+C_{n}^{4}+\cdots$.
22. Calcule o valor das somas
a) $S_{1}=\binom{n}{1}+3\binom{n}{3}+5\binom{n}{5}+\cdots$;
b) $S_{2}=2\binom{n}{2}+4\binom{n}{4}+6\binom{n}{6}+\cdots$.
23. Calcule o valor da soma

$$
\binom{n}{0}-2\binom{n}{1}+3\binom{n}{2}-\cdots+(-1)^{n}(n+1)\binom{n}{n}
$$

24. Demonstre por indução a Fómula do Binómio.
25. Qual é o termo máximo da seqüência de termo geral $a_{n}=$ $\frac{(2 n+1) 5^{n}}{n!}$ ?
26. Calcule $\sum_{k=0}^{n} k(k-1) C_{n}^{k} 2^{k}$.
27. Calcule $\sum_{k=0}^{n} k^{2} C_{n}^{k} 5^{k}$.

# 4.3. Polinômio de Leibniz 

Podemos obter uma generalização da fórmula do binômio.

## Teorema:

$$
\left(x_{1}+x_{2}+\cdots+x_{p}\right)^{n}=\sum \frac{n!}{\alpha_{1}!\alpha_{2}!\cdots \alpha_{p}!} x_{1}^{\alpha_{1}} x_{2}^{\alpha_{2}} \cdots x_{p}^{\alpha_{p}}
$$

estendendo-se o somatório a todos os valores inteiros não-negativos de $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{p}$ tais que $\alpha_{1}+\alpha_{2}+\cdots+\alpha_{p}=n$.

## Prova:

$$
\begin{aligned}
\left(x_{1}+x_{2}+\cdots+x_{p}\right)^{n}= & \left(x_{1}+x_{2}+\cdots+x_{p}\right) \cdots \\
& \cdots\left(x_{1}+x_{2}+\cdots+x_{p}\right)
\end{aligned}
$$

O termo genérico do produto é obtido escolhendo-se em cada parênteses um $x_{i}$ e multiplicando-se os escolhidos. Ora, se em $\alpha_{1}$ dos parênteses escolhermos $x_{1}$, em $\alpha_{2}$ dos parênteses escolhermos $x_{2}$ etc... obteremos $x_{1}^{\alpha_{1}} x_{2}^{\alpha_{2}} \cdots x_{p}^{\alpha_{p}}\left(\alpha_{1}, \alpha_{2}, \cdots, \alpha_{p}\right.$ inteiros não-negativos e $\left.\alpha_{1}+\alpha_{2}+\cdots+\alpha_{p}=n\right)$. O termo $x_{1}^{\alpha_{1}} x_{2}^{\alpha_{2}} \cdots x_{p}^{\alpha_{p}}$ aparece tantas vezes quantos são os modos de escolhermos nos $n$ parênteses $\alpha_{1}$ deles para pegarmos o $x_{1}$ para fator, $\alpha_{2}$ dentre os que sobraram para pegarmos o $x_{2}$ como fator etc... Mas isso pode ser feito de

$$
C_{n}^{\alpha_{1}} \cdot C_{n-\alpha_{1}}^{\alpha_{2}} \cdots C_{n-\alpha_{1}-\cdots-\alpha_{n}}^{\alpha_{n}},=\frac{n!}{\alpha_{1}!\alpha_{2}!\cdots \alpha_{n}!}
$$

modos. Logo, $x_{1}^{\alpha_{1}} x_{2}^{\alpha_{2}} \cdots x_{p}^{\alpha_{p}}$ aparece no desenvolvimento

$$
\frac{n!}{\alpha_{1}!\alpha_{2}!\cdots \alpha_{n}!}
$$

vezes.
Exemplo 4.13: Calcule $\left(x^{2}+2 x-1\right)^{4}$.

Soluçäo:

$$
\begin{aligned}
\left(x^{2}+2 x-1\right)^{4} & =\sum \frac{4!}{\alpha_{1}!\alpha_{2}!\alpha_{3}!}\left(x^{2}\right)^{\alpha_{1}}(2 x)^{\alpha_{2}}(-1)^{\alpha_{3}} \\
& =\sum \frac{24}{\alpha_{1}!\alpha_{2}!\alpha_{3}!} 2^{\alpha_{2}}(-1)^{\alpha_{3}} x^{2 \alpha_{1}+\alpha_{2}}
\end{aligned}
$$

onde $\alpha_{1}, \alpha_{2}, \alpha_{3}$ são inteiros não-negativos tais que $\alpha_{1}+\alpha_{2}+\alpha_{3}=4$.
Abaixo temos uma tabela dos valores possíveis de $\alpha_{1}, \alpha_{2}, \alpha_{3}$ e os corespondentes termos do desenvolvimento.

| $\alpha_{1}$ | $\alpha_{2}$ | $\alpha_{3}$ | $T$ |
| :--: | :--: | :--: | :--: |
| 4 | 0 | 0 | $x^{8}$ |
| 0 | 4 | 0 | $16 x^{4}$ |
| 0 | 0 | 4 | 1 |
| 3 | 1 | 0 | $8 x^{7}$ |
| 3 | 0 | 1 | $-4 x^{6}$ |
| 1 | 0 | 3 | $-4 x^{2}$ |
| 1 | 3 | 0 | $32 x^{5}$ |
| 0 | 1 | 3 | $-8 x$ |
| 0 | 3 | 1 | $-32 x^{3}$ |
| 2 | 1 | 1 | $-24 x^{5}$ |
| 1 | 2 | 1 | $-48 x^{4}$ |
| 1 | 1 | 2 | $24 x^{3}$ |
| 2 | 2 | 0 | $24 x^{6}$ |
| 2 | 0 | 2 | $6 x^{4}$ |
| 0 | 2 | 2 | $24 x^{2}$ |

Somando e reduzindo os termos semelhantes obtemos

$$
\begin{gathered}
\left(x^{2}+2 x-1\right)^{4}= \\
x^{8}+8 x^{7}+20 x^{6}+8 x^{5}-26 x^{4}-8 x^{3}+20 x^{2}-8 x+1 .
\end{gathered}
$$

Exemplo 4.14: Determine o coeficiente de $x^{4}$ no desenvolvimento de $\left(x^{2}-x+2\right)^{6}$.

Solução:

$$
\begin{aligned}
\left(x^{2}-x+2\right)^{6} & =\sum \frac{6!}{\alpha_{1}!\alpha_{2}!\alpha_{3}!}\left(x^{2}\right)^{\alpha_{1}}(-x)^{\alpha_{2}} 2^{\alpha_{3}} \\
& =\sum \frac{6!}{\alpha_{1}!\alpha_{2}!\alpha_{3}}(-1)^{\alpha_{2}} 2^{\alpha_{3}} x^{2 \alpha_{1}+\alpha_{2}}
\end{aligned}
$$

Para que o expoente de $x$ seja 4 devemos ter

$$
\begin{aligned}
& \alpha_{1}+\alpha_{2}+\alpha_{3}=6 \\
& 2 \alpha_{1}+\alpha_{2}=4
\end{aligned}
$$

As soluções são

| $\alpha_{1}$ | $\alpha_{2}$ | $\alpha_{3}$ | Termo |
| :--: | :--: | :--: | :--: |
| 0 | 4 | 2 | $60 x^{4}$ |
| 1 | 2 | 3 | $480 x^{4}$ |
| 2 | 0 | 4 | $240 x^{4}$ |

Somando, o termo em $x^{4}$ do desenvolvimento é $780 x^{4}$. A resposta é portanto, 780 .

Exemplo 4.15: Deduza uma fórmula para o cálculo do quadrado de um polinômio.

Solução:

$$
\left(x_{1}+x_{2}+\cdots+x_{n}\right)^{2}=\sum \frac{2!}{\alpha_{1}!\alpha_{2}!\cdots \alpha_{n}!} x_{1}^{\alpha_{1}} x_{2}^{\alpha_{2}} \cdots x_{n}^{\alpha_{n}}
$$

onde $\alpha_{1}, \alpha_{2}, \ldots, \alpha_{n}$ são inteiros não-negativos tais que $\alpha_{1}+\alpha_{2}+$ $\cdots+\alpha_{n}=2$. Há dois tipos de soluções para a cquação acima.

i) Um dos $\alpha$ é igual a 2 e os demais são iguais a zero. Obteremos então termos da foram $x_{i}^{2}(1 \leq i \leq n)$.
ii) Dois dos $\alpha$ são iguais a 1 e os demais são iguais a zero. Obteremos então termos da forma $2 x_{i} x_{j}(1 \leq i<j \leq n)$. Logo,

$$
\left(x_{1}+x_{2}+\cdots+x_{n}\right)^{2}=\sum_{i=1}^{n} x_{i}^{2}+2 \sum_{1 \leq i<j \leq n} x_{i} x_{j}
$$

isto é, o quadrado de um polinômio é igual à soma dos quadrados dos seus termos mais a soma dos duplos produtos dos seus termos. Assim, por exemplo,

$$
\begin{gathered}
\left(x^{2}+3 x+1\right)^{2}= \\
x^{4}+9 x^{2}+1+2\left(x^{2}\right)(3 x)+2\left(x^{2}\right)(1)+2(3 x) 1= \\
=x^{4}+6 x^{3}+11 x^{2}+6 x+1
\end{gathered}
$$

# Exercícios 

1. Determine o coeficiente de $x^{17}$ no desenvolvimento de

$$
\left(1+x^{5}+x^{7}\right)^{20}
$$

2. Determine a soma dos coeficientes do desenvolvimento de

$$
\left(x^{3}-3 x+1\right)^{1822}
$$

3. Quantos termos possui o desenvolvimento de

$$
\left(x_{1}+x_{2}+x_{3}+x_{4}\right)^{20} ?
$$

4. Deduza uma fórmula para o cálculo do cubo de um polinômio.

# 5. Probabilidade 

A teoria do azar consiste em reduzir todos os acontecimentos do mesmo gênero a um certo número de casos igualmente possíveis, ou seja, tais que estejamos igualmente inseguros sobre sua existência, e em determinar o número de casos favoráveis ao acontecimento cuja probabilidade é buscada. A razão deste número para o de todos os casos possíveis é a medida dessa probabilidade, a qual é portanto uma fração cujo numerador é o número de casos favoráveis e cujo denominador é o número de todos os casos possíveis.

Pierre Simon Laplace
Ensaio filosófico sobre as Probabilidades

### 5.1 Introdução

Uma das aplicações mais importantes dos resultados anteriores é na Teoria das Probabilidades.

Diremos que um experimento é determinístico quando repetido em condiçōes semelhantes conduz a resultados essencialmente

idênticos. Os experimentos que repetidos sob as mesmas condiçōes produzem resultados geralmente diferentes serāo chamados experimentos aleatórios. Fenômenos aleatórios acontecem constantemente em nossa vida diária. São frequentes perguntas tais como: choverá amanhã? Qual será a temperatura máxima no próximo domingo? Qual será o número de ganhadores da Loteria Esportiva? Quantos habitantes terá o Brasil no ano 2000 ?

A Teoria das Probabilidades é o ramo da Matemática que cria, desenvolve e em geral pesquisa modelos que podem ser utilizados para estudar experimentos ou fenômenos aleatórios.

O modelo matemático utilizado para estudar um fenômeno aleatório particular varia em sua complexidade matemática, dependendo do fenômeno estudado. Mas todos esses modelos têm ingredientes básicos comuns. O que vamos fazer agora é estudar uma série de fenômenos aleatórios relativamente simples e interessantes, e fixar uma série de idéias e noções que são totalmente gerais.

# 5.2 Espaço Amostral e Probabilidades de Laplace 

Nesta seção vamos tratar de um caso particular da situação geral que será desenvolvida na seção seguinte. Este caso particular é muito importante, e a maior parte dos exemplos e exercícios deste capítulo são relativos a esta seção.

A definição de probabilidade como quociente do número de "casos favoráveis" sobre o número de "casos possíveis" foi a primeira definição formal de probabilidade, c apareceu pela primeira vez em forma clara na obra Liber de Ludo Aleae de Jerônimo Cardano (1501-1576). A probabilidade introduzida nesta seção tem, como veremos, várias propriedades. Elas serão tomadas como definição de uma função de conjunto que também chamaremos probabilidade na seção seguinte.

Consideremos o seguinte experimento aleatório: jogue um dado e observe o número mostrado na face de cima.

A primeira tarefa consiste em descrever todos os possíveis resultados do experimento e calcular o seu número. De outra forma: explicitar qual é o conjunto de possiveis resultados do experimento e calcular o numero de elementos contidos nele. Este conjunto é chamado Espaço Amostral. É fácil descrevê-lo em nosso exemplo:

$$
\Omega=\{1,2, \ldots, 6\}, \quad \#(\Omega)=6
$$

Os elementos do espaço amostral são chamados eventos elementares. Os subconjuntos do espaço amostral serão chamados eventos. Por exemplo, o subconjunto

$$
A=\{2,4,6\}
$$

é o evento que acontece se o número mostrado na face de cima é par.

Passamos agora à segunda etapa: a de calcular a probabilidade de um evento $A$. Consideremos o caso do evento $A=\{2,4,6\}$ de nosso exemplo. É claro intuitivamente que se repetimos o experimento um grande número de vezes obteremos um número par em aproximadamente a metade dos casos; ou seja o evento $A$ vai ocorrer mais ou menos a metade das vezes. O que está por trás dessa intuição é o seguinte:
a) os eventos elementares são todos igualmente "prováveis";
b) o número de elementos de $A(\#(A)=3)$ é justamente a metade dos elementos de $\Omega(\#(\Omega)=6)$.
Estas considerações motiva a definição de probabilidade de um evento como $A$, da seguinte forma

$$
\text { probabilidade de } A=\frac{\#(A)}{\#(\Omega)}=\frac{3}{6}=\frac{1}{2}
$$

Laplace referia-se aos elementos de $A$ (ou eventos elementares que compõem $A$ ) como os casos favoráveis. Os elementos do

espaço amostral $\Omega$ eram chamados casos possiveis. Defina então

$$
\text { probabilidade }=\frac{\text { número de casos favoráveis }}{\text { número de casos possíveis }}
$$

Vamos então resumir as considerações feitas até agora, que permitem a utilização desta definição de probabilidade.

Suponha que os experimentos aleatórios têm as seguintes características:
a) Há um número finito (digamos $n$ ) de eventos elementares (casos possíveis). A união de todos os eventos elementares é o espaço amostral $\Omega$.
b) Os eventos elementares são igualmente prováveis.
c) Todo evento $A$ é um união de $m$ eventos elementares onde $m \leq n$.

Definimos então

$$
\begin{aligned}
\text { Probabilidade de } A=P(A) & =\frac{\text { número de casos favoráveis }}{\text { número de casos possíveis }} \\
& =\frac{\#(A)}{\#(\Omega)}=\frac{m}{n}
\end{aligned}
$$

Conseqüências imediatas desta definição são as seguintes propriedades:

1) Para todo evento $A, 0 \leq P(A) \leq 1$;
2) $P(\Omega)=1$;
3) $P(\phi)=0$ (porque $\#(\phi)=0$ );
4) Se $A \cap B=\phi$ então $P(A \cup B)=P(A)+P(B)$.

Exemplo 5.1: Três moedas são jogadas simultaneamente. Qual é a probabilidade de obter 2 caras? Qual é a probabilidade de obter pelo menos 2 caras?

Solução: Vamos indicar com $H$, cara e com $T$ coroa. O espaço amostral é então

$$
\begin{aligned}
\bullet \quad \Omega= & \{(H H H),(H H T),(H T H),(H T T),(T H H] \\
& (T H T),(T T H), T T T)\}
\end{aligned}
$$

Donde:

$$
\#(\Omega)=\text { casos possíveis }=8
$$

Se $A$ indica o evento "obter 2 caras" temos que

$$
A=\{(H H T),(H T H),(T H H)\}
$$

Assim $\#(A)=3$ e portanto

$$
P(A)=\frac{\#(A)}{\#(\Omega)}=\frac{3}{8}
$$

Se $B$ denota o evento "obter pelo menos duas caras" temos

$$
B=\{(H H T),(H T H),(T H H),(H H H)\}
$$

Resulta que $\#(B)=4$ e $P(B)=\frac{4}{8}=\frac{1}{2}$.
Exemplo 5.2: Dois dados são jogados simultaneamente. Calcular a probabilidade de que a soma dos números mostrados nas faces de cima seja 7.

Solução: O espaço amostral $\Omega$ consiste de todos os pares ( $i, j$ ) onde $i$ e $j$ são inteiros positivos compreendidos entre 1 e 6. A figura 5.1 descreve o espaço amostral completamente.

|  |  | Número do segundo dado |  |  |  |  |  |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | 1 | 2 | 3 | 4 | 5 | 6 |
|  | 1 | $(1,1)$ | $(1,2)$ | $(1,3)$ | $(1,4)$ | $(1,5)$ | $(1,6)$ |
|  | 2 | $(2,1)$ | $(2,2)$ | $(2,3)$ | $(2,4)$ | $(2,5)$ | $(2,6)$ |
|  | 3 | $(3,1)$ | $(3,2)$ | $(3,3)$ | $(3,4)$ | $(3,5)$ | $(3,6)$ |
|  | 4 | $(4,1)$ | $(4,2)$ | $(4,3)$ | $(4,4)$ | $(4,5)$ | $(4,6)$ |
|  | 5 | $(5,1)$ | $(5,2)$ | $(5,3)$ | $(5,4)$ | $(5,5)$ | $(5,6)$ |
|  | 6 | $(6,1)$ | $(6,2)$ | $(6,3)$ | $(6,4)$ | $(6,5)$ | $(6,6)$ |

Fig. 5.1
O número de eventos elementares (casos possíveis) é igual a $\#(\Omega)=36$. Seja $A$ o conjunto dos pares $(i, j)$ tais que $i+j=7$. Esses pares estão sombreados na figura 5.1. Temos que $\#(A)=6$ e portanto

$$
P(A)=\frac{\#(A)}{\#(\Omega)}=\frac{6}{36}=\frac{1}{6}
$$

Na maior parte dos problemas concretos o Espaço Amostral não é descrito com tanto cuidado. Este é um costume generalizado (e às vezes perigoso). Nos exemplos seguintes não descreveremos precisamente o Espaço Amostral, mas o leitor é aconselhado em todos os casos a defini-lo com precisão.

Exemplo 5.3: Dois dados são jogados simultaneamente. Calcular a probabilidade de que o máximo seja maior ou igual a 3.

Solução: Os pares tais que o máximo e menor que 3 são ( 1,1 ), $(1,2),(2,1)$ e $(2,2)$. Portanto o número daqueles nos quais o máximo é maior ou igual a 3 é 32 e a probabilidade procurada $32 / 36=8 / 9$.

Exemplo 5.4: Suponhamos que de $n$ objetos escolhemos $r$ ao acaso com reposição. Qual é a probabilidade de que nenhum objeto seja escolhido mais de uma vez?
Solução: O número de casos possiveis é igual a $n^{r}$. O número de casos favoráveis é igual a $n(n-1)(n-2) \cdots(n-r+1)$ ( $r$ fatores).

A probabilidade é portanto igual a

$$
\frac{n(n-1)(n-2) \cdots(n-r+1)}{n^{r}}
$$

Uma aplicação interessante deste resultado é a seguinte: suponhamos que o aniversário de uma pessor possa cair com igual probabilidade em qualquer dos dias do ano. Se $r$ pessoas são escolhidas ao acaso, a probabilidade de que todas façam anos em dias diferentes é dada pela fórmula anterior com $n=365$.

A tabela 5.1 dá aproximações por excesso desta probabilidade, para diferentes valores de $r$; por exemplo, para $r=30$ a probabilidade é menor do que 0,30 . Os resultados são bastantes surpreendentes; em um grupo com 35 pessoas, por exemplo, a probabilidade de duas delas terem nascido no mesmo dia do ano, (aniversários no mesmo dia) é maior do que $80 \%$.

| $r$ | Probabilidade $\leq$ |  |
| :--: | :--: | :--: |
| 5 | 0,98 |  |
| 10 | 0,89 |  |
| 15 | 0,75 |  |
| 20 | 0,59 |  |
| 25 | 0,44 |  |
| 30 | 0,30 |  |
| 35 | 0,19 |  |
| 40 | 0,11 |  |
| 50 | 0,03 |  |
| 60 | 0,006 | $i$ |

Tabela 5.1

Exemplo 5.5: Para a Copa do Mundo 24 países são divididos em seis grupos, com 4 países cada um. Supondo que a escolha do grupo de cada pais é feita ao acaso, calcular a probabilidade de que dois países determinados $A$ e $B$ se encontrem no mesmo grupo. (Na realidade a escolha não é feita de forma completamente alcatória).

Solução: Vamos tomar como espaço amostral o conjunto de todas as permutações de 24 elementos; ou seja o número de casos possíveis é 24! Consideremos o diagrama da figura 5.2, que

| 1 | 2 | 3 | 4 | 5 | 6 |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |

Fig. 5.2
representa os 24 times divididos em 6 grupos. Quantas permutações existem tais que $A$ e $B$ pertencem ao primeiro grupo? $A$ pode ser colocado em 4 lugares; restam para $B$ três lugares e os times restantes podem ser dispostos em 22! formas diferentes. Portanto o número de permutações com $A$ e $B$ no primeiro grupo é

$$
4 \times 3 \times 22!
$$

A probabilidade procurada é portanto

$$
\frac{6 \cdot 4 \cdot 3 \cdot 22!}{24!}=\frac{3}{23} \approx 0.13
$$

# 5.3 Espaços de Probabilidade 

Vamos introduzir agora a noção geral de probabilidade e provar várias propriedades que são conseqüências mais ou menos imediata da definição.

Definição 5.1: Seja $\Omega$ um espaço amostral (conjunto). Uma função $P$ definida para todos os subconjuntos de $\Omega$ (chamados eventos) é chamada uma probabilidade se

1) $0 \leq P(A) \leq 1$, para todo evento $A \subset \Omega$;
2) $P(\phi)=0, P(\Omega)=1$;
3) Se $A$ e $B$ são eventos disjuntos (também clamados mutuamente exclusivos) $P(A \cup B)=P(A)+P(B)$.

A probabilidade que usamos até agora e que continuaremos usando na maior parte deste trabalho é a que se obtém definido $P(A)$ como o quociente do número de elementos contidos em $A$ (casos favoráveis) pelo número de elementos de $\Omega$ (casos possíveis). Existem muitas probabilidades (ou seja, funções com as propriedades 1,2 e 3 da definição 5.1) que não são desta forma particular. Um exemplo simples se obtém tomando $\Omega=\{0,1\}$ e definindo

$$
P(\phi)=0, \quad P(\Omega)=1, \quad P(\{0\})=2 / 3, \quad P(\{1\})=1 / 3
$$

Em geral, sejam $\Omega$ um conjunto com $n$ elementos,

$$
\Omega=\left\{w_{1}, w_{2}, \ldots, w_{n}\right\}
$$

e $p_{1}, p_{2}, \ldots, p_{n} n$ números não-negativos e tais que $p_{1}+p_{2}+\cdots+$ $p_{n}=1$; Definamos $P\left(\left\{w_{i}\right\}\right)=p_{i}, i=1,2, \ldots, n$ e, em geral, para $A \subset \Omega, P(A)=$ soma dos $P\left(\left\{w_{i}\right\}\right)=$ soma dos $p_{i}$ com $w_{i} \in A$ (ou seja $P(A)$ é a soma das probabilidades dos elementos pertencentes a $A$ ). A função $P$ assim obtida é uma probabilidade sobre $\Omega$. Em geral ela é diferente da probabilidade de Laplace introduzida na seção 5.2. Se $p_{1}=p_{2}=\cdots=p_{n}=1 / n$ obtemos a probabilidade de Laplace como caso particular.

Várias conseqüências simples e úteis dà definição de probabilidade estão contidas nas seguintes proposições.

Proposição 5.1: $P\left(A^{c}\right)=1-P(A)$.

Demonstração: Sabemos que

$$
1=P(\Omega)=P\left(A \cup A^{c}\right)=P(A)+P\left(A^{c}\right)
$$

Portanto

$$
P\left(A^{c}\right)=1-P(A)
$$

Um resultado mais geral está contido na seguinte
Proposição 5.2: Se $A \subset B$ então $P(A)=P(B)-P(B-A)$.
Demonstração: Como $B=A \cup(B-A)$, temos

$$
P(B)=P(A \cup(B-A))=P(A)+P(B-A)
$$

e portanto $P(A)=P(B)-P(B-A)$.
Corolário: Se $A \subset B$ então $P(A) \leq P(B)$.
Demonstração: Como $P(A)=P(B)-P(B-A)$ e $P(B-A) \geq$ 0 (porque $P$ é uma probabilidade) resulta que $P(A) \leq P(B)$.

Proposição 5.3: $\quad P(A \cup B)=P(A)+P(B)-P(A \cap B)$.
Demonstração: Temos que

$$
\begin{aligned}
& P(A)=P(A-B)+P(A \cap B) \\
& P(B)=P(B-A)+P(A \cap B)
\end{aligned}
$$

Somando:
$P(A)+P(B)=P(A-B)+P(B-A)+P(A \cap B)+P(A \cap B)$.

# Portanto 

$$
P(A \cup B)=P(A)+P(B)-P(A \cap B)
$$

Com as mesmas técnicas usadas para descrever e provar o Princípio da Inclusão-Exclusão pode-se estabelecer uma fórmula para $P\left(A_{1} \cup A_{2} \cup A_{n}\right)$ onde $A_{1}, A_{2}, \ldots, A_{n}$ são $n$ eventos. Como, salvo modificações evidentes, a demonstração é a mesma, enunciamos o resultado sem apresentar uma prova.

# Proposição 5.4: 

$$
\begin{aligned}
P\left(A_{1} \cup A_{2} \cup \cdots \cup A_{n}\right) & =P\left(A_{1}\right)+P\left(A_{2}\right)+\cdots+P\left(A_{n}\right)+ \\
& -P\left(A_{1} \cap A_{2}\right)-\cdots-P\left(A_{n-1} \cap A_{n}\right)+ \\
& +P_{k}^{\prime} A_{1} \cap A_{2} \cap A_{3}\right)+\cdots+ \\
& +(-1)^{n-1} P\left(A_{1} \cap A_{2} \cap \cdots \cap A_{n}\right)
\end{aligned}
$$

As propricdades provadas nas proposições anteriores são válidas para qualquer probabilidade; ou seja, para qualquer função de conjuntos satisfazendo as condições da definição 5.1. Note-se que sobre o mesmo espaço amostral $\Omega$ é possivel definir muitas probabilidades diferentes. Um fenômeno aleatório é representado matematicamente por um par de objetos: o espaço amostral $\Omega$ (ou conjunto de eventos elementares) e uma probabilidade $P$ definida sobre os subconjuntos (eventos) de $\Omega$. O par $(\Omega, P)$ é chamado Espaço de Probabilidades.

Introduzimos a noção de Espaço Amostral como um objeto univocamente determinado por um dado fenômeno aleatório. Isso não é estritamente certo, como podemos ver pelo seguinte exemplo simples: joguemos uma moeda duas vezes c observemos o número de caras obtidas.

Representemos como anteriormente cara e coroa com as letras $H$ e $T$. Podemos tomar como espaço amostral

$$
\Omega_{1}-\{(H, H),(H, T),(T, H),(T, T)\}
$$

e como $P_{1}$ a probabilidade que faz todos os eventos elementares (pontos de $\Omega_{1}$ ) igualmente prováveis. Mas, como o que estamos

observando neste experimento é o número de caras, poderíamos tomar como espaço amostral o conjunto $\Omega_{2}=\{0,1,2\}$ correspondente a observar 0 caras, 1 cara, ou 2 caras. E como definimos $P_{2}$ ? Se queremos um modelo que "represente" o fenômeno real (no sentido de que as freqüências relativas "aproximem" as probabilidades do modelo) deveriamos definir $P_{2}$ da seguinte forma

$$
P_{2}(0)=P_{2}(2)=\frac{1}{4}, \quad P_{2}(1)=\frac{1}{2}
$$

Temos então dois espaços de probabilidades $\left(\Omega_{1}, P_{1}\right)$ e $\left(\Omega_{2}, P_{2}\right)$ que representam o mesmo fenómeno aleatório. Existe algum motivo que determine a preferência de um modelo sobre um outro? A resposta é afirmativa: um modelo em que os eventos elementares sejam igualmente prováveis é mais conveniente porque facilita geralmente os cálculos de quase todas as probabilidades. As técnicas desenvolvidas nos Capítulos 2 e 3 podem ser utilizadas com proveito. Nos exemplos seguintes as propriedades das probabilidades serão usadas na maior parte dos casos sem referência específica. A probabilidade será quase sempre a introduzida na seção 5.2 .

Exemplo 5.6: Uma recepcionista recebeu $n$ chapéus, mas estes ficaram totalmente misturados. Decidiu, então devolvê-los a esmo. Calcular a probabilidade de que nenhum homem receba o seu. (É interessante tentar adivinhar o comportamento dessa probabilidade quando $n$ é grande, antes de efetuar o cálculo.)

Solução: O número de casos possíveis é igual ao das permutações de $n$ elementos, que é $n$ !. O número de casos favoráveis é igual ao dos permutações caóticas de um conjunto com $n$ elementos. Este número foi calculado na seção 3.2 e é igual a

$$
n!\left[\frac{1}{2!}-\frac{1}{3!}+\frac{1}{4!}-\cdots+(-1)^{n} \frac{1}{n!}\right]
$$

A probabilidade buscada é igual ao quociente destes números; é portanto igual a

$$
\frac{1}{2!}-\frac{1}{3!}+\frac{1}{4!}-\cdots+(-1)^{n} \frac{1}{n!}
$$

Esta probabilidade se estabiliza rapidamente quando $n$ aumenta; para $n \geq 4$ a variação é menor que 0,01 . ( 0 limite desta expressão quando $n \rightarrow \infty$ é $e^{-1} \approx 0,37$.)

Exemplo 5.7: Uma loteria tem $N$ números e só um prêmio. Um jogador compra $n$ bilhetes em uma extração. Outro compra só um bilhete em $n$ extrações diferentes. (Ambos os jogadores apostam portanto a mesma importância). Qual deles tem maior probabilidade de ganhar o prêmio?
Solução: Se todo o dinheiro é jogado numa única vez a probabilidade de ganhar é $n / N$. Para calcular a outra probabilidade procedemos da seguinte maneira. Vamos calcular primeiro a probabilidade de não ganhar. O número de casos possíveis é igual a $N^{n}$. Os casos favoráveis (neste caso não ganhar) são $(N-1)^{n}$. Portanto a probabilidade de não ganhar é igual a

$$
\frac{(N-1)^{n}}{N^{n}}=\left(\frac{N-1}{N}\right)^{n}=\left(1-\frac{1}{N}\right)^{n}
$$

e a de ganhar

$$
1-\left(1-\frac{1}{N}\right)^{n}
$$

Temos que comparar agora $n / N$ e $1-(1-/ N)^{n}$. Afirmamos que

$$
\frac{n}{N} \geq 1-\left(1-\frac{1}{N}\right)^{n}
$$

ou equivalentemente,

$$
1-\frac{n}{N} \leq\left(1-\frac{1}{N}\right)^{n}
$$

A demonstração desta desigualdade é feita no Apêndice 3. É interessante observar a conclusão deste resultado: jogar tudo 'de uma só vez é melhor do que ir jogando aos poucos. Em outras palavras, o jogo "frio" é melhor (porém, em geral, parece provocar menos "satisfação", porque joga-se menos tempo). Esta conclusão é válida em geral para quase todos os jogos de azar.

Exemplo 5.8: Seis bolas diferentes são colocadas em três urnas diferentes. Qual é a probabilidade de que todas as urnas estejam ocupadas?

Solução: A escolha da urna em que cada uma das 6 bolas é colocada pode ser feita de 3 modos diferentes. Logo, pelo Princípio da Multiplicação, o número de casos possíveis é

$$
\#(\Omega)=3 \times 3 \times 3 \times 3 \times 3 \times 3=3^{6}
$$

Para contar os casos favoráveis sejam $A_{1}$ o conjunto de distribuições de bolas pelas urnas que deixam vazia a primeira uma, $A_{2}$ o conjunto das distribuições que deixam vazia a segunda uma e $A_{3}$ das distribuições que deixam vazia a terceira.

Temos agora:

$$
\begin{aligned}
& \#\left(A_{1}\right)=\#\left(A_{2}\right)=\#\left(A_{3}\right)=2^{6} \\
& \#\left(A_{1} \cap A_{2}\right)=\#\left(A_{1} \cap A_{3}\right)=\#\left(A_{2} \cap A_{3}\right)=1 \\
& \#\left(A_{1} \cap A_{2} \cap A_{3}\right)=0
\end{aligned}
$$

Portanto, pelo Princípio de Inclusão-Exclusão,

$$
\#\left(A_{1} \cup A_{2} \cup A_{3}\right)=3 \times 2^{6}-1-1-1=3\left(2^{6}-1\right)
$$

e

$$
P\left(A_{1} \cup A_{2} \cup A_{3}\right)=\frac{3\left(2^{6}-1\right)}{3^{6}}=\frac{2^{6}-1}{3^{5}}=\frac{63}{243}=\frac{7}{27}
$$

Assim, a probabilidade procurada é

$$
P\left\{\left(A_{1} \cup A_{2} \cup A_{3}\right)^{c}\right\}=1-\frac{7}{27}=\frac{27-7}{27}=\frac{20}{27}
$$

Exemplo 5.9: Um número entre 1 e 300 é escolhido aleatoriamentc. Calcular a probabilidade de que ele seja divisível por 3 ou por 5 .

Solução: Scjam $A$ e $B$ os eventos que acontecem se o número escolhido for divisível por 3 e por 5 respectivamente. Temos que calcular $P(A \cup B)$. Os números entre 1 e 300 divisíveis por 3 são 100; os divisíveis por 5 são $300 / 5=60$, e os divisíveis por 3 e 5 simultaneamente são $300 / 15=20$.

Temos portanto

$$
\begin{aligned}
& P(A)=\frac{100}{300}=\frac{1}{3} \\
& P(B)=\frac{60}{300}=\frac{1}{5} \\
& P(A \cap B)=\frac{20}{300}=\frac{1}{15}
\end{aligned}
$$

Assim,

$$
P(A \cup B)=P(A)+P(B)-P(A \cap B)=\frac{1}{3}+\frac{1}{5}-\frac{1}{15}=\frac{7}{15}
$$

Excmplo 5.10: Um torneio é disputado por 4 times $A, B, C$ e $D$. É 3 vezes mais provável que $A$ vença do que $B, 2$ vezes mais provável que $B$ vença"do que $C$ e é 3 vezes mais provável que $C$ vença do que $D$. Quais as probabilidades de ganhar para cada um dos times?
Solução: Vamos indicar com

$$
\Omega=\left\{w_{1}, w_{2}, w_{3}, w_{4}\right\}
$$

o espaço amostral que consiste dos quatro possiveis resultados do experimento:
$w_{1}$ corresponde a que $A$ ganhe o torncio;
$w_{2}$ corresponde a que $B$ ganhe o torneio;
$w_{3}$ corresponde a que $C$ ganhe o torneio;
$w_{4}$ corresponde a que $D$ ganhe o torncio.

Seja $p=P\left(w_{4}\right)$. Temos

$$
\begin{aligned}
& P\left(w_{3}\right)=3 p, \quad P\left(w_{2}\right)=2 P\left(w_{3}\right)=6 p \\
& P\left(w_{1}\right)=3 P\left(w_{2}\right)=18 p
\end{aligned}
$$

Como a soma das probabilidades tem que ser igual a 1 , resulta que

$$
p+3 p+6 p+18 p=1
$$

ou seja $28 p=1$, de onde $p=\frac{1}{28}$.
Portanto

$$
P\left(w_{4}\right)=\frac{1}{28}, \quad P\left(w_{3}\right)=\frac{3}{28}, \quad P\left(w_{2}\right)=\frac{6}{28}, \quad P\left(w_{1}\right)=\frac{18}{28}
$$

Exemplo 5.11: Seja $P$ uma probabilidade sobre os eventos (subconjuntos) de um espaço amostral $\Omega$. Sejam $A$ e $B$ eventos tais que $P(A)=\frac{2}{3}$ e $P(B)=\frac{4}{9}$.
Prove que:
a) $P(A \cup B) \geq \frac{2}{3}$;
b) $\frac{2}{9} \leq P\left(A \cap B^{c}\right) \leq \frac{5}{9}$;
c) $\frac{1}{9} \leq P(A \cap B) \leq \frac{4}{9}$.

Soluçäo:
a) $P(A \cup B) \geq P(A)=\frac{2}{3}$;

b)

$$
\begin{aligned}
P\left(A \cap B^{c}\right) & \leq P\left(B^{c}\right)=1-P(B)=\frac{5}{9} \\
P\left(A \cap B^{c}\right) & =P(A-B)=P(A)-P(A \cap B) \\
& \geq P(A)-P(B)=\frac{2}{3}-\frac{4}{9}=\frac{2}{9}
\end{aligned}
$$

c)

$$
\begin{aligned}
P(A \cap B) & \leq P(B)=\frac{4}{9} \\
P(A \cap B) & =P(B)-P(B-A) \\
& \geq P(B)-P\left(A^{c}\right)=\frac{4}{9}-\frac{1}{3}=\frac{1}{9}
\end{aligned}
$$

# Exercícios 

1. Uma caixa contém 20 peças em boas condições e 15 em más condições. Uma amostra de 10 peças é extraída. Calcular a probabilidade de que ao menos uma peça na amostra seja deficituosa.
2. (Póquer com dados) Cinco dados são jogados simultaneamente e os resultados são classificados em:
$A_{1}=$ todos diferentes;
$A_{2}=$ um par;
$A_{3}=$ dois pares;
$A_{4}=$ três iguais;
$A_{5}=$ full (três iguais e dois iguais);
$A_{6}=$ quatro iguais (pôquer);
$A_{7}=$ cinco iguais;
$A_{8}=$ uma seqüência.
Calcular as probabilidades de $A_{i} i=1,2, \ldots, 8$.

3. Uma cidade tem 30000 habitantes e très jornais $A, B$ c $C$. Uma pesquisa de opinião revela que:

12000 lêem $A$;
8000 lêem $B$;
7000 lêem $A$ e $B$;
6000 lêem $C$;
4500 lêem $A$ e $C$;
1000 lêem $B$ e $C$;
500 lêem $A, B$ e $C$.
Qual é a probabilidade de que um habitante leia:
a) pelo menos um jornal;
b) só um jornal.
4. Os algarismos $1,2,3,4,5$ são escritos em 5 cartões diferentes. Este cartōes são escolhidos (sem reposição) aleatoriamente e os algarismos que vão aparecendo são escritos da esquerda para a direita, formando um número de cinco algarismos.
a) Calcular a probabilidade de que o número escrito seja par.
b) Se a escolha fosse com reposição qual seria a probabilidade?
5. Colocam-se aleatoriamente $b$ bolas em $b$ urnas. Calcular a probabilidade de que exatamente uma urna seja deixada desocupada.
6. Dez pessoas são separadas em dois grupos de 5 pessoas cada um. Qual é a probabilidade de que duas pessoas determinadas $A$ e $B$ façam parte do mesmo grupo?
7. 5 homens e 5 mulheres compram 10 cadeiras consecutivas na mesma fila de um teatro. Supondo que se sentaram aleatoriamente nas 10 cadeiras, calcular:
a) A probabilidade de que homens e mulheres se sentem em cadeiras alternadas;
b) A probabilidade de que as mulheres se sentem juntas.

8. Um número entre 1 e 200 é escolhido aleatoriamente. Calcular a probabilidade de que seja divisivel por 5 ou por 7.
9. Uma moeda foi cunhada de tal forma que é 4 vezes mais provável dar cara do que coroa. Calcular as probabilidade de cara e coroa.
10. Aos números inteiros entre 1 e $n$ são designadas probabilidades proporcionais aos seus valores. Calcular $P(i)$ para $1 \leq i \leq$ $n$.
11. Três dados são jogados simultaneamente. Calcular a probabilidade de obter 12 como soma dos resultados dos três dados.
12. Dois dados são jogados simultaneamente. Calcular a probabilidade de obter 7 como soma dos resultados.
13. Consideremos uma urna contendo $n$ bolas, das quais $n_{1} \geq 1$ são brancas e $n_{2} \geq 1$ são pretas com $n=n_{1}+n_{2}$. Escolhe-se, ao acaso, uma amostra de $r$ bolas, com $r \leq n_{1}$ e $r \leq n_{2}$. Qual a probabilidade de que exatamente $k$ das bolas nessa amostra sejam brancas, sc $0 \leq k \leq r$.
14. Uma moeda cquilibrada (probabildade de cara $=$ probabilidade de coroa $=1 / 2$ ) é jogada $n$ vezes. Calcular a probabilidade de obter-se exatamente $k$ caras, $0 \leq k \leq n$.
15. Sejam $A$ e $B$ eventos tais que

$$
P(A)=\frac{1}{2}, \quad P(B)=\frac{1}{4}, \quad \text { e } \quad P(A \cap B)=\frac{1}{5}
$$

Calcular:
a) $P(A \cup B)$;
b) $P\left(A^{c}\right)$;
c) $P\left(B^{c}\right)$;
d) $P\left(A \cap B^{c}\right)$;
e) $P\left(A^{c} \cap B\right)$;
f) $P\left(A^{c} \cap B^{c}\right)$;

g) $P\left(A^{c} \cup B^{c}\right)$.
16. Uma urna contém 4 bolas brancas, 4 bolas pretas e 4 bolas vermelhas. Sacam-se 6 bolas dessa urna. Determine a probabilidade de serem sacadas 2 bolas de cada cor:
a) supondo a extração com reposição;
b) supondo a extração sem reposição.
17. No jogo da Sena são sorteadas 6 dezenas distintas entre as dezenas $01-02-\cdots-50$. O apostador escolhe 6 dessas 50 dezenas e é premiado se são sorteadas 4 (quadra), 5 (quina), 6 (Sena Principal) das dezenas por ele escolhidas ou se as dezenas sorteadas são escolhidas aumentadas (Sena Anterior) ou diminuídas (Sena Posterior) de uma unidade ( $50+1=01,01-1=50$ ). Determine a probabilidade de um apostador fazer:
a) uma quadra;
b) uma quina;
c) a Sena Principal;
d) a Sena Anterior ou a Posterior.
18. No jogo da Loto são sorteadas 5 dezenas distintas entre as dezenas $01-02-\cdots-99-00$. O apostador escolhe $6,7,8,9$ ou 10 dezenas e é premiado se são sorteadas 3 (terno), 4 (quadra) ou 5 (quina) das dezenas escolhidas. Determine a probabilidade de um apostador que escolheu 10 dezenas fazer:
a) um terno;
b) uma quadra;
c) a quina.
19. Na Loteria Esportiva há 13 jogos e o apostador deve indicar em cada um deles a vitória do time 1 , a vitória do time 2 ou o empate. Um jogador é premiado:
a) com 10 pontos, se acerta os resultados dos 10 primeiros jogos e erra os dos 3 últimos;
b) com 11 pontos, se acerta os resultados dos 10 primeiros jogos e acerta apenas um dos resultados dos 3 últimos;

c) com 12 pontos, se acerta os resultados dos 10 primeiros jogos e acerta apenas dois dos resultados dos 3 últimos;
d) com 13 pontos; se acerta os resultados dos 13 jogos.

Supondo que em cada jogo os resultados possíveis tenham probabilidade iguais, determine a probabilidade de um apostador ser premiado:
a) com 10 pontos;
b) com 11 pontos;
c) com 12 pontos;
d) com 13 pontos.
20. Escolhem-se ao acaso duas peças de um dominó. Qual é a probabilidade delas possuirem um número comum?
21. Há 8 carros estacionados em 12 vagas em fila.
a) Qual é a probabilidade das vagas vazias serem consecutivas?
b) Qual é a probabilidade de não haver duas vagas vazias consecutivas?
22. Cinco homens e cinco mulheres sentam-se aleatoriamente em dez cadeiras em círculo. Calcule:
a) A probabildade de os homens e as mulheres se sentarem em lugares alternados.
b) A probabilidade das mulheres se sentarem juntas.
23. Uma caixa contém $2 n$ sorvetes, $n$ de cóco e $n$ de chocolate. Em um grupo de $2 n$ pessoas, $a(a<n)$ pessoas preferem cóco e $b(b<n)$ pessoas preferem chocolate. As demais não têm preferência. Os sorvetes são distribuídos ao acaso. Qual é a probabilidade de todas as preferências serem respeitadas?
24. Em um armário há $n$ pares de sapatos. Retiram-se ao acaso $p$ pés de sapatos desse armário. Qual a probabilidade de haver entre esses pés exatamente $k$ pares de sapatos?

25. Colocam-se ao acaso $n$ botões em um tabuleiro $n \times n$, não sendo permitido haver dois botōes em uma mesma casa. Qual é a probabilidade de não haver dois botōes nem na mesma linha nem na mesma coluna?
26. Um polígono regular de $2 n+1$ lados está inscrito em um círculo. Escolhem-se 3 dos seus vértices, formando-se um triângulo. Qual é a probabilidade do centro do círculo se interior ao triângulo?
27. Nos cartōes da Sena, as dezenas são apresentadas em um quadro com 5 linhas e 10 colunas. Determine a probabilidade das 6 dezenas sorteadas:
a) pertencerem à mesma linha;
b) pertencerem a apenas duas linhas, 5 numa linha e 1 na outra;
c) idem, 4 numa linha e 2 na outra;
d) idem, 3 numa linha e 3 na outra;
e) pertencerem a apenas três linhas, duas em cada;
f) pertencerem a linhas diferentes.
28. Tem-se $n$ urnas. Bolas são colocadas ao acaso nas urnas, uma de cada vez, até que alguma urna receba duas bolas. Qual é a probabilidade de colocarmos exatamente $p$ bolas nas urnas?
29. Um carro estaciona entre $n$ outros em fila e não numa ponta. Quando o dono retorna ainda estão estacionados $m$ dos $n$ carros. Qual é a probabilidade das duas vagas adjacentes ao seu carro estarem vazias?
30. Se $n$ homens, entre os quais João e Pedro, são postos ao acaso em uma fila, qual é a probabilidade de haver exatamente $m$ pessoas entre João e Pedro?
31. Em um grupo de 10 pessoas, quatro são sorteadas para ganhar um prêmio. Qual é a probabilidade de uma particular pessoa ser sorteada?
32. Doze pessoas são divididas em três grupos de 4. Qual é a probabilidade de duas determinadas pessoas ficarem no mesmo grupo?

33. Em um roda são colocadas, ao acaso, $n$ pessoas. Qual é a probabilidade de duas determinadas dessas pessoas ficarem juntas?
34. João e Pedro lançam, cada um, um dado não-tendencioso. Qual é a probabilidade do resultado de João ser maior ou igual ao resultado de Pedro?
35. Qual é a probabilidade de uma permutação dos números $(1,2, \ldots, 10)$ ter exatamente 5 elementos no seu lugar primitivo?
36. $P(A)=\frac{1}{2}, P(B)=\frac{1}{3}, P(C)=\frac{1}{4}, P(A \cap B)=\frac{1}{5}, P(A \cap C)=$ $\frac{1}{6}, P(B \cap C)=0$. Calcule:
a) $P(A \cup B \cup C)$;
b) $P[A-(B \cup C)]$
c) $P(A \cap(B \cup C)]$
d) $P([(A \cap B) \cup C)]$.
37. $P(A)=\frac{1}{3}, P(B)=\frac{1}{4}, P(C)=\frac{1}{6}, P(A \cap B)=\frac{1}{6}, P(A \cap C)=$ $P(B \cap C)=\frac{1}{10}, P(A \cap B \cap C)=\frac{1}{12}$. Determine a probabilidade de ocorrencia de:
a) Exatamente um dos eventos $A, B, C$;
b) Exatamente dois dos eventos $A, B, C$;
c) Pelo menos dois desses eventos;
d) No máximo dois desses eventos;
e) No máximo um desses eventos.

# 5.4. Probabilidades Condicionais 

Consideremos o experimento que consiste em jogar um dado nãoviciado. Sejam $\Omega=\{1,2, \ldots, 6\}, A=\{2,4,6\}$ e $B=\{1,24\}$. Temos que $P(B) \#(B) / \#(\Omega)=3 / 6=1 / 2$. Esta é a probabilidade de $B$ a priori, quer dizer, antes que o experimento se realize. Suponhamos que, uma vez realizado o experimento, alguém nos

informe que o resultado do mesmo é um número par, isto é, que $A$ ocorreu. Nossa opinião sobre a ocorrencia de $B$ se modifica com esta informação, já que, então, somente poderá ter ocorrido $B$ se o resultado do experimento tiver sido 2. Esta opinião é quantificada com a introdução de uma "probabilidade a posteriori" ou, como vamos chamá-la doravante, probabilidade condicional de $B$ dado $A$, definida por

$$
\frac{\#(B \cap A)}{\#(A)}=\frac{1}{3}
$$

Introduzimos em geral a seguinte
Definição 5.2: Dados dois eventos $A$ e $B$, a probabilidade condicional de $B$ dado $A$ é o número $P(A \cap B) / P(A)$. Representaremos este número pelo símbolo $P(B / A)$. Temos então simbolicamente

$$
P(B / A)=\frac{P(A \cap B)}{P(A)}
$$

Note-se que este número só está definido quando $P(A)>0$.
A equação (5.1) é também escrita como

$$
P(A \cap B)=P(A) P(B / A)
$$

Se $P(B)>0$ temos também

$$
P(A \cap B)=P(B) \cdot P(A / B)
$$

Antes de passar aos exemplos indicaremos algumas propriedades básicas da noção de probabilidade condicional.

Proposição 5.5: Seja A tal que $P(A)>0$. Então
a) $P(\phi / A)=0, \quad P(\Omega / A)=1, \quad 0 \leq P(B / A) \leq 1$.
b) $P((B \cup C) / A)=P(B / A)+P(C / A)$, se $B \cap C=\phi$. Ou seja, fixado $A$ a probabilidade condicional é outra probabilidade sobre o espaço amostral $\Omega$.

# Demonstração: 

a) $P(\phi / A)=\frac{P(\phi \cap A)}{P(A)}=\frac{P(\phi)}{P(A)}=\frac{0}{P(A)}=0$,

$$
P(\Omega / A)=\frac{P(\Omega \cap A)}{P(A)}=\frac{P(A)}{P(A)}=1
$$

Como $0 \leq P(A \cap B) \leq P(A)$ temos

$$
0 \leq \frac{P(A \cap B)}{P(A)} \leq 1
$$

isto é,

$$
0 \leq P(B / A) \leq 1
$$

b) $P((B \cup C) / A)=\frac{P((B \cup C) \cap A)}{P(A)}$

$$
\begin{aligned}
& =\frac{P((B \cap A) \cup(C \cap A))}{P(A)} \\
& =\frac{P(B \cap A)}{P(A)}+\frac{P(C \cap A)}{P(A)} \\
& =P(B / A)+P(C / A)
\end{aligned}
$$

Proposição 5.6: (Teorema do produto) Se

$$
P\left(A_{1} \cap A_{2} \cap \cdots \cap A_{n}\right) \neq 0
$$

entāo

$$
\begin{gathered}
P\left(A_{1} \cap A_{2} \cap \cdots \cap A_{n}\right)= \\
=P\left(A_{1}\right) P\left(A_{2} / A_{1}\right) P\left(A_{3} /\left(A_{1} \cap A_{2}\right)\right) \cdots \\
\cdots P\left(A_{n} /\left(A_{1} \cap A_{2} \cap \cdots \cap A_{n-1}\right)\right.
\end{gathered}
$$

Esboço da Demonstração: Para dois conjuntos $A_{1}$ e $A_{2}$ a fórmula é válida proque coincide com (5.2). Verifiquemos a fórmula para três conjuntos $(n=3) A_{1}, A_{2}$ e $A_{3}$.

Temos

$$
\begin{aligned}
P\left(A_{1} \cap A_{2} \cap A_{3}\right) & =P\left(A_{3} /\left(A_{1} \cap A_{2}\right)\right) P\left(A_{1} \cap A_{2}\right) \\
& =P\left(A_{3} /\left(A_{1} \cap A_{2}\right)\right) P\left(A_{2} / A_{1}\right) P\left(A_{1}\right)
\end{aligned}
$$

que é o resultado desejado. No caso geral o raciocínio é semelhante e usa o Princípio de Indução Completa.

Exemplo 5.12: Um grupo de pessoas está classficado da seguinte forma:

|  | fala <br> inglês | fala <br> alemão | fala <br> francês |
| :--: | :--: | :--: | :--: |
| homens | 92 | 35 | 47 |
| mulheres | 101 | 33 | 52 |

Escolhe-se uma pessoa ao acaso. Sabendo-se que esta pessoa fala francês, qual é a probabilidade de que seja homem?

Solução: Seja $A$ o cvento que ocorre se a pessoa escolhida fala francês e $B$ se a pessoa escolhida é homem. Temos

$$
\begin{gathered}
P(A)=\frac{47+92}{360}=\frac{99}{360} \\
P(A \cap B)=\frac{47}{360}
\end{gathered}
$$

e portanto

$$
P(B / A)=\frac{P(A \cap B)}{P(A)}=\frac{47 / 360}{99 / 360}=\frac{47}{99}
$$

Note-se que

$$
P(B / A)=\frac{47}{99}=\frac{47}{47+52}=\frac{\# A(\cap B)}{\#(A)}
$$

Isto sempre acontecerá se, na probabilidade considerada, todos os pontos do espaço amostral são igualmente prováveis.
Exemplo 5.13: Numa prova há 7 perguntas do tipo verdadeirofalso. Calcular a probabilidade de acertarmos todas as 7 se:
a) escolhermos aleatoriamente as 7 respostas,
b) escolhermos aleatoriamente as respostas mas sabendo que há mais respostas "verdadeiro" do que "falso".

Solução:
a) Há $2^{7}=128$ possibilidades e portanto $P$ |acertas os 7 testes $=$ $\frac{1}{28}$.
b) Seja $A$ o conjunto de todos os pontos com mais respostas "V" do que "F". Temos que

$$
\#(A)=\binom{7}{4}+\binom{7}{5}+\binom{7}{6}+\binom{7}{7}=35+21+7+1=64
$$

e portanto a probabilidade buscada é igual a $1 / 64$.
Exemplo 5.14: Sabe-se que $80 \%$ dos pênaltis marcados a favor do Brasil são cobrados por jogadores do Flamengo. A probabilidade de um pênalti ser convertido é de $40 \%$ se o cobrador for do Flamengo e de $70 \%$ em caso contrário. Um pênalti a favor do Brasil acabou de ser marcado:
a) Qual a probabilidade do pênalti ser cobrado por um jogador do Flamengo e ser convertido?

Solução:
A probabilidade desejada é:
$P($ "cobrador é do Flamengo" $e$ "pênalti é convertido") $=P(F \cap C)$.

Pelo Teorema do Produto:

$$
P(F \cap C)=P(F) \cap P(C / F)=0,8 \times 0,4=0,32
$$

Note que, ainda pelo Teorema do Produto, poderíamos ter escrito:

$$
P(F \cap C)=P(C) \cdot P(F / C)
$$

No entanto, as probabilidades que ocorrem no lado direito da igualdade não estão explícitas no enunciado.
b) Qual a probabilidade do pênalti ser convertido?

Solução: Note que, do enunciado, apenas sabemos as probabilidades condicionais do pênalti ser convertido, dado que o batedor seja do Flamengo ou pertença a um outro clube. Para fazer uso dessas probabilidades condicionais, decompomos o evento $C$ : "o pênalti é convertido" na união de dois eventos disjuntos: "o cobrador é do Flamengo e o pênalti é convertido" e "o cobrador não é do Flamengo e o pênalti é convertido".

Isto é:

$$
C=(F \cap C) \cup(\bar{F} \cap C)
$$

Logo

$$
P(C)=P(F \cap C)+P(\bar{F} \cap C)
$$

Cada uma das probabilidade do lado direito pode ser calculada com auxílio do Teorema do Produto.

$$
\begin{aligned}
& P(F \cap C)=P(F) \cdot P(C / F)=0,8 \times 0,4=0,32 \\
& P(\bar{F} \cap C)=P(\bar{F}) \cdot P(C / \bar{F})=0,2 \times 0,7=0,14
\end{aligned}
$$

Logo,

$$
P(C)=0,32+0,14=0,46
$$

Uma forma prática de resolver problemas como este é recorrer a diagrama de árvore. Tais diagramas são úteis sempre que o experimento aleatório possua diversos estágios.

O diagrama apropriado para o problema em questão é dado na figura 5.3.

![img-25.jpeg](img-25.jpeg)

Fig. 5.3

Os números em cada ramo representam as probabilidades condicionais do evento associado ao final do ramo, dado a sequiência de eventos que nos conduziu ao início do ramo.

A decomposição do evento "pénalti é convertido" em eventos disjuntos é feita, no diagrama, tomando-se todos os caminhos sobre a árvore que levam a este evento. A probabilidade correspondente a cada caminho é calculada usando o Teorema do Produto.

Desta forma, temos novamente:

$$
P(C)=0,8 \times 0,4+0,2 \times 0,7=0,46
$$

c) Um pênalti foi marcado a favor do Brasil e acabou de ser desperdiçado. Qual é a probabilidade de que o cobrador tenha sido um jogador do Flamengo?

Solução: A probabilidade pedida é uma probabilidade condicional $(P(F / \bar{C}))$ que não é explicitamente dada no enunciado.

Para calculá-la recorremos à definição de probabilidade codicional e ao diagrama de árvore introduzido no item (b).
![img-26.jpeg](img-26.jpeg)

Fig. 5.4
Temos

$$
\begin{aligned}
& P(F / \bar{C})=\frac{P(F \cap \bar{C})}{P(\bar{C})} \\
& P(F \cap \bar{C})=0,8 \times 0,6=0,48
\end{aligned}
$$

(siga o caminho correspondente na árvore);
$P(\bar{C})=0,8 \times 0,6+0,2 \times 0,3=0,54$
(siga os caminhos na árvore que levam a "não verte");
$P(F / \bar{C})=\frac{0,48}{0,54} \approx 0,89$.
(Observe que o fato de o pênalti ter sido desperdiçado fez com que a probabilidade "a posteriori" do batedor ser do Flamengo $(0,89)$ fosse maior do que a probabilidade "a priori" do jogador escolhido ser do Flamengo $(0,8)$.).

Exemplo 5.15: Consideremos dois dados: um deles equilibrado $(P(\{1\})=P(\{2\})=\cdots=P(\{6\})=1 / 6)$ e outro viciado com $P(\{1\})=1 / 2$ e $P(\{2\})=\cdots=P(\{6\})=1 / 10$. Escolhe-se um -dos dados ao acaso e se efetuam dois lançamentos, obtendo-se dois uns. Qual a probabilidade condicional de que o dado escolhido tenha sido o viciado?

Solução:
![img-27.jpeg](img-27.jpeg)

Fig. 5.5
Temos

$$
\begin{aligned}
& P[\text { observar dois uns }]=\frac{1}{2} \cdot \frac{1}{4}+\frac{1}{2} \cdot \frac{1}{36}=\frac{5}{36} \\
& P[\text { dado viciado e dois uns }]=\frac{1}{2} \cdot \frac{1}{4}=\frac{1}{8}
\end{aligned}
$$

A probabilidade buscada é então igual a

$$
\frac{1 / 8}{5 / 36}=\frac{9}{10}
$$

Exempo 5.16: Marina quer enviar uma carta a Verônica. A probabilidade de que Marina escreva a carta é de $8 / 10$. A probabilidade de que o correio não a perca é de $9 / 10$. A probabilidade

de que o carteiro a entregue é de $9 / 10$. Dado que Verônica não recebeu a carta, qual é a probabilidade condicional de que Marina não a tenha escrito?
Solução:
![img-28.jpeg](img-28.jpeg)

Fig. 5.6

$$
\begin{aligned}
P(\text { não escreve } \mid \text { não recebe }) & =\frac{P(\text { não escreve })}{P(\text { não recebe })}= \\
& =\frac{2 / 10}{\frac{2}{10}+\frac{8}{10} \frac{1}{10}+\frac{8}{10} \frac{2}{10} \frac{1}{10}}=\frac{25}{44}
\end{aligned}
$$

Os três últimos exemplos poderiam também ter sido resolvidos utilizando os dois resultados gerais a seguir.

Proposição 5.7: (Teorema da Probabilidade Total) Se B é um evento contido numa uniāo de eventos disjuntos

$$
\begin{gathered}
A_{1}, A_{2}, \ldots, A_{n}, e \\
P\left(A_{1}\right)>0, P\left(A_{2}\right)>0, \ldots, P\left(A_{n}\right)>0
\end{gathered}
$$

entāo
$P(B)=P\left(A_{1}\right) P\left(B / A_{1}\right)+P\left(A_{2}\right) P\left(B / A_{2}\right)+\cdots+P\left(A_{n}\right) P\left(B / A_{n}\right)$.

A figura 5.7 ilustra a situação do teorema.
![img-29.jpeg](img-29.jpeg)

Fig. 5.7

Demonstração: Temos que

$$
B=\left(A_{1} \cap B\right) \cup\left(A_{2} \cap B\right) \cup \cdots \cup\left(A_{n} \cap B\right)
$$

Então,

$$
\begin{aligned}
P(B) & =P\left(A_{1} \cap B\right)+P\left(A_{2} \cap B\right)+\cdots+P\left(A_{n} \cap B\right)= \\
& P\left(A_{1}\right) \cdot P\left(B / A_{1}\right)+P\left(A_{2}\right) \cdot P\left(B / A_{2}\right)+\cdots+ \\
& +\cdots+P\left(A_{n}\right) \cdot P\left(B / A_{n}\right)
\end{aligned}
$$

Proposição 5.8: (Teorema de Bayes) Nas condiçōes da proposiçōes anterior, se $P(B)>0$, então, para $i, i=1,2, \ldots, n$,

$$
P\left(A_{i} / B\right)=\frac{P\left(A_{i}\right) \cdot P\left(B / A_{i}\right)}{P\left(A_{1}\right) \cdot P\left(B / A_{1}\right)+\cdots+P\left(A_{n}\right) \cdot P\left(B / A_{n}\right)}
$$

Demonstração: Temos que

$$
\begin{aligned}
P\left(A_{i} / B\right) & =\frac{P\left(B \cap A_{i}\right)}{P(B)} \\
& =\frac{P\left(A_{i}\right) \cdot P\left(B / A_{i}\right)}{P(B)}
\end{aligned}
$$

Usando a identidade obtida na proposição anterior obtemos a fórmula pedida.

Exemplo 5.17: Durante o mês de agosto a probabilidade de chuva em um dia determinado é de 4/10. O Fluminense ganha um jogo em um dia com chuva com probabilidade $6 / 10$ e em um dia sem chuva com probabilidade de $4 / 10$. Sabendo-se que o Fluminense ganhou um jogo naquele dia de agosto, qual a probabilidade de que choveu nesse dia?

Solução: Utilizando o Teorema de Bayes temos

$$
\begin{gathered}
P[\text { choveu/ganhou }]= \\
=\frac{P[\text { choveul } P[\text { ganhou/choveul }]}{P[\text { choveul } P[\text { ganhou/chove }]]+P[\text { nãa choveul } P[\text { ganhou } / \text { não choveu }]} \\
=\frac{\frac{1}{10} \cdot \frac{1}{10}+\frac{1}{10} \cdot \frac{1}{10}}{10}=\frac{1}{2}
\end{gathered}
$$

Exemplo 5.18: Num exame há 3 respostas para cada pergunta e apenas uma delas é certa. Portanto, para cada pergunta, um aluno tem probabilidade $1 / 3$ de escolher a resposta certa se ele está adivinhando e 1 se sabe a resposta. Um estudante sabe $30 \%$ das resposta do exame. Se ele deu a resposta correta para uma das perguntas, qual é a probabilidade de que a adivinhou?

Solução: Utilizando o Teorema de Bayes temos

$$
P[\text { adivinhou/resposta correta }]=\frac{0,70 \times \frac{1}{3}}{0,70 \times \frac{1}{3}+0,30 \times 1}=\frac{7}{16}
$$

A árvore corespondente é dada na figura 5.8.
![img-30.jpeg](img-30.jpeg)

Fig. 5.8

Introduzimos finalmente a noção de independência de eventos. A definição que se encontra mais abaixo capta a idéia intuitiva da não influência de um evento $A$ sobre a ocorrência ou não de outro evento $B$. De outra forma: a ocorrência de $A$ não melhora nossa posição para "predizer" a ocorrência de $B$. Esta idéia é formalizada dizendo que a probabilidade condicional de $B$ dado $A$ é igual a probabilidade de $B$. Em símbolos

$$
P(B / A)=P(B) \quad(P(A)>0)
$$

Esta identidade é equivalente a

$$
\frac{P(B \cap A)}{P(A)}=P(B)
$$

Isto é:

$$
P(B \cap A)=P(B) \cdot P(A)
$$

(que é válida mesmo que se tenha $P(A)=0$ ). Esta última identidade é tomada como definição da independência de dois eventos. Temos então

Definição 5.3: Dois eventos $A$ e $B$ são chamados independentes se

$$
P(A \cap B)=P(A) \cdot P(B)
$$

Uma conseqüência imediata desta definição é que o vazio $\phi$ e o espaço amostral $\Omega$ são independentes de qualquer outro evento, porque, se $A$ é um evento, então:

$$
P(A \cap \phi)=P(\phi)=0=P(\phi) \cdot P(A)
$$

e

$$
P(A \cap \Omega)=P(A)=P(A) \cdot 1=P(A) \cdot P(\Omega)
$$

Exemplo 5.19: Treze cartas são escolhidas de um baralho comum de 52 cartas. Seja $A$ o evento "o ás de copas está entre as 13 cartas" e $B$ o evento "as 13 cartas são do mesmo naipe". Provar que $A$ e $B$ são independentes.

Solução:

$$
\begin{aligned}
& P(A)=\frac{\binom{51}{12}}{\binom{52}{13}}=\frac{51!13!39!}{12!39!52!}=\frac{13}{52}=\frac{1}{4} \\
& P(B)=\frac{4}{\binom{52}{13}} \\
& P(A \cap B)=\frac{1}{\binom{52}{13}}
\end{aligned}
$$

Portanto $P(A \cap B)=P(A) P(B)$ ou seja $A$ e $B$ são eventos independentes.

A extensão da noção de independência para $n$ eventos $A_{1}, A_{2}, \ldots, A_{n}$ é feita naturalmente pensando no Teorcma do Produto. Dizemos que eles são independentes se para toda escolha de

um número arbitrário deles, a probabilidade da interseção é igual ao produto das probabilidades. Formalmente:

Definição 5.4: $A_{1}, A_{2}, \ldots, A_{n}$ são independentes se $\forall k$, e $\forall i_{1}, i_{2}, \ldots, i_{k}$, tem-se

$$
P\left(A_{i_{1}} \cap A_{i_{2}} \cap \cdots \cap A_{i_{k}}\right)=P\left(A_{i_{1}}\right) \cdot P\left(A_{i_{2}}\right) \cdots P\left(A_{i_{k}}\right)
$$

Nota: Para provar que 2 eventos são independentes só devemos verificar uma identidade. Para provar que 3 eventos são independentes temos que verificar 4 identidades. Em geral, para provar que $n$ eventos são independentes, é necessário verificar $2^{n}-n-1$ identidades ( $2^{n}-n-1$ é igual ao número de subconjuntso com 2 ou mais elementos contidos num conjunto de $n$ elementos). Não é suficiente verificar todas as identidades tomando os subconjuntos de a dois elementos, como o seguinte exemplo mostra.

Seja $\Omega$ o espaço amostral apresentado na figura 5.9 com 4 pontos $w_{1}, w_{2}, w_{3}$ e $w_{4}$, e $P$ a probabilidade que associa a cada ponto o valor $1 / 4$.
![img-31.jpeg](img-31.jpeg)

Fig. 5.9

Sejam

$$
C=\left\{w_{1}, w_{3}\right\}, \quad L=\left\{w_{3}, w_{4}\right\} \quad \text { e } \quad D=\left\{w_{2}, w_{3}\right\}
$$

três eventos correspondentes à primeira coluna, à segunda linha e à diagonal, respectivamente.

Resulta que

$$
\begin{gathered}
P(C)=P(L)=P(D)=\frac{1}{2} \\
P(C \cap L)=P(C \cap D)=P(L \cap D)=P\left(w_{3}\right)=\frac{1}{4}
\end{gathered}
$$

Ou seja, tomados dois a dois os eventos são independentes. Mas os três simultaneamente não são independentes porque

$$
P(C \cap L \cap D)=P\left(w_{3}\right)=\frac{1}{4} \neq \frac{1}{8}=P(C) \cdot P(L) \cdot P(D)
$$

Exemplo 5.20: Um jogador deve enfrentar, em um torneio, dois outros $A$ e $B$. Os resultados dos jogos são independentes e as probabilidades dele ganhar de $A$ e de $B$ são $1 / 3$ e $2 / 3$ respectivamente. O jogador vencerá o torneio se ganhar dois jogos consecutivos, de um série de 3. Que série de jogos é mais favorável para o jogador: $A B A$ ou $B A B$ ?
Solução: A probabilidade do jogador vencer se escolher a primeira série $A B A$ é (ganha de $A$, ganha de $B$ ou perde para $A$, ganha de $B$ e ganha de $A$ )

$$
\frac{1}{3} \cdot \frac{2}{3}+\frac{2}{3} \cdot \frac{2}{3} \cdot \frac{1}{3}=\frac{10}{27}
$$

A probabilidade do jogador vencer se escolher a segunda série $B A B$ é

$$
\frac{2}{3} \cdot \frac{1}{3}+\frac{1}{3} \cdot \frac{1}{3} \cdot \frac{2}{3}=\frac{8}{27}
$$

Ou seja, a primeira série é mais favorável. Este resultado pode parecer surpreendente, pois $A$, o adversário mais difícil, comparece

duas vezes na primeira série. O que acontece intuitivamente é que o jogo com $A$ na segunda série é decisivo. Na primeira série, o jogador tem duas chances para derrotar $A$.
$\cdot$Exemplo 5.21: A probabilidade de fechamento de cada relé do circuito apresentado na figura 5.10 é igual a $p, 0<p<1$.
![img-32.jpeg](img-32.jpeg)

Fig. 5.10

Se todos os relés funcionam independentemente, qual é a probabilidade de que haja corrente circulando entre os terminais $A$ e $B$ ?
Soluçäo: Seja $A_{i}$ o evento que ocorre se o relé está fechado, $i=$ $1,2,3,4,5$.

Seja $C$ o evento que ocorre se há corrente entre os terminais A e B. Queremos calcular $P(C)$. Temos

$$
\begin{aligned}
P(C)= & P\left[\left(A_{1} \cap A_{2} \cap A_{3}\right) \cup\left(A_{1} \cap A_{4} \cap A_{5}\right) \cup\right. \\
& \cup\left(A_{1} \cap A_{2} \cap A_{5}\right) \cup\left(A_{1} \cap A_{4} \cap A_{3}\right) \\
= & P\left(A_{1} \cap A_{2} \cap A_{3}\right)+P\left(A_{1} \cap A_{4} \cap A_{5}\right)+ \\
& +P\left(A_{1} \cap A_{2} \cap A_{5}\right)+P\left(A_{1} \cap A_{4} \cap A_{3}\right)+ \\
& -P\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4} \cap A_{5}\right) \mid+ \\
& -P\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{5}\right)+ \\
& -P\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4}\right)+ \\
& -P\left(A_{1} \cap A_{3} \cap A_{4} \cap A_{5}\right)+
\end{aligned}
$$

$$
\begin{aligned}
& -P\left(A_{1} \cap A_{2} \cap A_{4} \cap A_{5}\right)+ \\
& -P\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4} \cap A_{5}\right)+ \\
& +P\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4} \cap A_{5}\right)+ \\
& +P\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4} \cap A_{5}\right)+ \\
& +P\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4} \cap A_{5}\right)+ \\
& +P\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4} \cap A_{5}\right)+ \\
& -P\left(A_{1} \cap A_{2} \cap A_{3} \cap A_{4} \cap A_{5}\right) \\
& =4 p^{3}-p^{5}-4 p^{4}-p^{5}+4 p^{5}-p^{5}=4 p^{3}-4 p^{4}+p^{5} .
\end{aligned}
$$

No cálculo utilizamos a fórmula para calcular a probabilidade da união de 4 eventos não disjuntos e o fato dos eventos serem independentes.

Obtemos uma solução mais simples para o problema se prestarmos mais atenção à estrutura do circuito. Observe que para circular corrente entre $A$ e $B$ é necessário que o relé 1 esteja fechado e que pelo menos um entre 2 e 4 e pelo menos um entre 3 e 5 também o estejam.

Desta forma $C=A_{1} \cap\left(A_{2} \cup A_{4}\right) \cap\left(A_{3} \cup A_{5}\right)$. Logo

$$
\begin{aligned}
P(C)= & P\left(A_{1}\right) \cdot P\left(A_{2} \cup A_{4}\right) \cdot P\left(A_{3} \cup A_{5}\right) \\
= & P\left(A_{1}\right) \cdot\left(P\left(A_{2}\right)+P\left(A_{4}\right)-P\left(A_{2} \cap A_{4}\right)\right) \\
& \cdot\left(P\left(A_{3}\right)+P\left(A_{5}\right)-P(A \cap A)\right)
\end{aligned}
$$

# Exercícios 

1. Escolhe-se ao acaso um número entre 1 e 50 . Se o número é primo qual é a probabilidade de que seja ímpar?
2. Uma moeda é jogada 6 vezes. Sabendo-se que no primeiro lançamento deu coroa, calcular a probabilidade condicional de que o número de caras nos seis lançamentos supere o número de coroas.
3. Uma moeda é jogada 4 vezes. Sabendo que o primeiro resultado foi cara, calcular a probabilidade condicional de obter pelo menos 2 caras.
4. Jogeu um dado duas vezes. Calcule a probabilidade condicional de obter 3 na primeira jogada, sabendo que a soma dos resultados foi 7 .
5. Duas máquinas $A$ e $B$ produzem 3000 peças em um dia. A máquina $A$ produz 1000 peças, das quais $3 \%$ são defeituosas. A máquina $B$ produz as restantes 2000 , das quais $1 \%$ são defeituosas. Da produção total de um dia uma peça é escolhida ao acaso e, examinando-a, constata-se que é defeituosa. Qual é a probabilidade de que a peça tenha sido produzida pela máquina $A$ ?
6. Três urnas I,II e III contêm respectivamente 1 bola branca e 2 pretas, 2 brancas e 1 preta e 3 brancas e 2 pretas. Uma urna é escolhida ao acaso e dela é retirada uma bola, que é branca. Qual é a probabilidade condicional de que a urna escolhida foi a II?
7. Um estudante resolve um teste com questōes do tipo verdadei-ro-falso. Ele sabe dar a solução correta para $40 \%$ das questōes. Quando ele responde uma questão cuja solução conhece, dá a resposta correta, e nos outros casos decide na cara ou coroa. Se uma questão foi respondida corretamente, qual é a probabilidade de que ele sabia a resposta?
8. Se $A$ e $B$ são eventos independentes tais que

$$
P(A)=1 / 3 \quad \text { e } \quad P(B)=1 / 2
$$

Calcule

$$
P(A \cup B), \quad P\left(A^{c} \cup B^{c}\right) \text { e } P\left(A^{c} \cap B\right)
$$

9. Sejam $A$ e $B$ dois eventos independentes tais que

$$
P(A)=1 / 4 \quad \text { e } \quad P(A \cup B)=1 / 3
$$

Calcule $P(B)$.
10. Uma moeda equilibrada é jogada duas vezes. Sejam $A$ e $B$ os eventos:

A: cara na primeira jogada;
B: cara na segunda jogada. Verifique que $A$ e $B$ são independentes.
11. Com as mesmas hipóteses do exemplo 5.11 Calcule a probabilidade de que haja corrente circulando entre os terminais $A$ e B.
![img-33.jpeg](img-33.jpeg)

Fig. 5.11
12. Provar que se $A, B$ e $C$ são eventos independentes, então
a) $A, B^{c}$ são independentes;
b) $A^{c}, B, C^{c}$ são independentes.

Nota: Em geral se $A_{1}, A_{2}, \ldots, A_{r}$ são independentes, então $B_{1}, B_{2}, \ldots, B_{r}$ são independentes onde $B_{i}$ é igual a algum dos $A_{j}$ ou $A_{j}^{c}, i=1,2, \ldots, r$.

13. (Problema dos Encontros de Montmort*) Forma-se, ao acaso, uma permutação simples dos números $1,2, \ldots, n$. Caso o número $i$ ocupe o $i$-ésimo lugar, dizemos que há um encontro na posição t. Calcule a probabilidade de na permutação formada:
a) haver exatamente $k$ encontros $(k \leq n)$;
b) haver um encontro na posição $i$ dado que há exatamente $k$ encontros na permutação;
c) haver um encontro na posição $i$ e não haver um encontro na posição $j(i \neq j)$;
d) haver um encontro na posição $i$ dado que não há encontro na posição $j(i \neq j)$.
14. Jogue um dado duas vezes. Considere os eventos:
$\mathrm{A}=$ o resultado do $1^{\circ}$ lançamento é par;
$\mathrm{B}=$ o resultado do $2^{\circ}$ lançamento é par;
$\mathrm{C}=$ a soma dos resultados é par.
$A$ e $B$ são independentes? e $A$ e $C$ ? e $B$ e $C$ ? e $A, B$ e $C$ ?
15. Uma pessoa com um molho de $n$ chaves tenta abrir uma porta. Apenas uma das chaves consegue abrir a porta. Qual é a probabilidade dela só coseguir abrir a porta na $k$-ésima tentativa:
a) supondo que após cada tentativa mal sucedida ela descarta a chave usada;
b) supondo que ela não faz isso.
16. (Problema de Chevalier de Méré) Determine a probabilidade de obter:
a) ao menos um 6 em quatro lançamentos de um dado
b) ao menos um duplo 6 em 24 lançamentos de um par de dados.
17. A probabilidade de um homem ser canhoto é $\frac{1}{10}$. Qual é a probabilidade de, em um grupo de 10 homens, haver pelo menos um canhoto?
[^0]
[^0]:    *Pierre Remond de Montmort (1678-1719)

18. Sacam-se, sucessivamente e sem reposição, duas cartas de um baralho comum ( 52 cartas). Calcule a probabilidade de a $1^{a}$ carta ser uma dama e a $2^{a}$ ser de copas.
19. Repartem-se as 52 cartas de um baralho comum por 4 parceiros, $N, S, E, W$, recebendo cada um 13 cartas. Para cada $k \in$ $\{1,2,3,4\}$ defina $N_{k}$ como sendo o evento " $N$ recebeu pelo menos $k$ ases" e defina analogamente $S_{k}, E_{k}, W_{k}$. Calcule as probabilidades de
a) $W_{1}^{c}$
b) $N_{2} \cap S_{2}$
c) $N_{1}^{c} \cap S_{1}^{c}$
d) $W_{2}-W_{3}$
e) $N_{1} \cap S_{1} \cap E_{1} \cap W_{1}$
f) $N_{3} \cap W_{1}$
g) $\left(N_{2} \cup S_{2}\right) \cap E_{2}$
h) $E_{2}$, na certeza de $W_{1}$.
20. Um exame de laboratório tem eficiência de $95 \%$ para detectar uma doença quando essa doença existe de fato.

Entretanto o teste aponta um resultado "falso positivo" para $1 \%$ das pessoas sadias testadas. Se $0,5 \%$ da população tem a doença, qual é a probabilidade de uma pessoa ter a doença dado que o seu exame foi positivo?
21. Uma urna contém 10 bolas numeradas de 1 a 10 . Sacam-se, com reposição, 4 bolas dessa urna. Sejam $X$ e $Y$ respectivamente o mínimo e o máximo dos números das bolas sacadas. Calcule:
a) $P(X>3)$
b) $P(X<3)$
c) $P(X=3)$
d) $P(Y<5)$
e) $P(Y>5)$
f) $P(Y=5)$
g) $P(X=3$ e $Y=9)$
h) $P(X=3 \mid Y=9)$

22. Resolva o problema anterior supondo extração sem reposição.
23. A lança uma moeda não-viciada $n+1$ vezes c $B$ lança a mesma moeda $n$ vezes. Qual é a probabilidade de $A$ obter mais caras que $B$ ?
24. Quantas pessoas você deve entrevistar para ter probabilidade igual ou superior a 0,5 de encontrar pelo menos uma que aniversarie hoje?
25. $2 N$ rapazes e $2 N$ moças são divididos ao acaso em dois grupos de $2 N$ pessoas cada. Qual a probabilidade de em cada grupo haver tantos rapazers quanto moças?
26. Uma urna contém 3 bolas vermelhas e 7 bolas brancas. $A$ e $B$ sacam altemadamente, sem reposição, bolas dessa urna até que uma bola vermelha seja retirada. $A$ saca a $1^{a}$ bola. Qual é a probabilidade de $A$ sacar a bola vermelha?
27. Em uma cidade com $n+1$ habitantes, uma pessoa conta um boato para uma outra pessoa, a qual por sua vez o conta para uma terceira pessoa, etc... Calcule a probabilidade do boato ser contado $m$ vezes:
a) sem retornar à primeira pessoa;
b) sem repetir nenhuma pessoa.
28. Em uma cidade, as pessoas falam a verdade com probabilidade $\frac{1}{3}$. Suponha que $A$ faz uma afirmação e que $D$ diz que $C$ diz que $B$ diz que $A$ falou a verdade. Qual é a probabilidade de $A$ ter falado a verdade?
29. Uma uma contém a bolas azuis e $b$ bolas brancas. Sacamse sucessivamente bolas dessa urna e, cada vez que uma bola é sacada, ela é devolvida à urna e são acrescentadas à urna mais $p$ bolas de mesma cor que a bola sacada. Seja $A_{i}$ o evento "a $i$-ésima bola sacada é azul". Calcule
a) $P\left(A_{1}\right)$;
b) $P\left(A_{2}\right)$;

c) $P\left(A_{3}\right)$;
d) $P\left(A_{2} / A_{1}\right)$;
e) $P\left(A_{1} / A_{2}\right)$.
30. $2^{n}$ jogadores de igual habilidade disputam um torncio. Eles são divididos em grupos de 2 , ao acaso, e jogadores de um mesmo grupo jogam entre si. Os perdedores são climinados e os vencedores são divididos novamente en grupos de 2 e assim por diante até restar apenas um jogador que é proclamado campeão. Qual é a probabilidade de dois jogadores $A$ e $B$ se enfrentarem durante o torneio? Qual é a probabilidade do jogador $A$ jogar exatamente $k$ partidas?
31. Em um torneio como o descrito no exercício anterior, os jogadores tem habilidades diferentes e não há surpresas nos resultados (se $A$ é melhor que $B, A$ vence $B$ ). Qual é a probabilidade do segundo melhor jogador ser vice-campeão do torneio?
32. Sacam-se, com reposição, $n(n>1)$ bolas de uma urna que contém 9 bolas numeradas de 1 a 9 . Qual é a probabilidade do produto dos números das $n$ bolas extraídas ser divisível por 10 ?
33. Quantas vezes, no mínimo, se deve lançar um dado não tendencioso para que a probabilidade de obter algum 6 seja superior a 0,9 ?
34. Um júri de 3 pessoas tem dois jurados que decidem corretamente (cada um) com probabilidade $p$ e um terceiro jurado que decide por cara ou coroa. As decisões são tomadas por maioria. Outro júri tem probabilidade $p$ de tomar uma decisão correta. Qual dos júris tem maior probabilidade de acerto?
35. Um dia você captura dez peixes em um lago, marca-os e coloca-os de novo no lago. Dois dias após, você captura vinte peixes no mesmo lago e constata que dois desses peixes haviam sido marcados por você.
a) se o lago possui $k$ peixes, qual era a probabilidade de, capturando vinte peixes, encontrar dois peixes marcados?

b) para que valor de $k$ essa probabilidade é máxima?
36. Um prisioneiro possui 50 bolas brancas, 50 bolas pretas e duas urnas iguais. O prisioneiro deve colocar do modo que preferir as bolas nas duas urnas (nenhuma das urnas pode ficar vazia). As urnas serão embaralhadas e o prisioneiro deverá, de olhos fechados, escolher uma urna e, nesta urna, uma bola. Se a bola for branca ele será libertado e, caso contrário, condenado. Como deve proceder o prisioneiro para maximizar a probabilidade de ser libertado?
37. Qual é a probabilidade de, em um grupo de 4 pessoas:
a) haver alguma coincidência de signos zodiacais?
b) as quatro terem o mesmo signo?
c) duas terem um mesmo signo e, as outras duas, outro signo?
d) três terem um mesmo signo e, a outra, outro signo?
e) todas serem signos diferentes?
38. Deseja-se estimar a probabilidade $p$ de um habitante de determinada cidade ser um consumidor de drogas. Para iso realizamse entrevistas com alguns habitantes da cidade. Não se deseja perguntar diretamente ao entrevistado se ele usa drogas, pois ele poderia se recusar a responder ou, o que seria pior, mentir. Adotase então o seguinte procedimento: propõe-se ao entrevistado duas perguntas do tipo SIM-NÃO:

1) Você usa drogas?
II) seu aniversário é anterior ao dia 2 de julho?

Pede-se ao entrevistado que jogue uma moeda, longe das vistas do entrevistador, e que se o resultado for cara, responda à primeira pergunta e, se for coroa, responda à segunda pergunta.
a) sendo $p_{1}$ a probabilidade de um habitante da cidade responder sim, qual é a relação entre $p$ e $p_{1}$ ?
b) se foram realizadas 1000 entrevistas c obtidos 600 sim é razoável imaginar que $p_{1} \approx 0,6$. Qual seria, então, sua estimativa de $p$ ?

39. Uma firma fabrica "chips" de computador. Em um lote de 1000 "chips", uma amostra de 10 "chips" revelou 1 "chip" defeituoso. Supondo que no lote houvesse $k$ "chips" defeituosos:
a) Calcule a probabilidade de em uma amostra de 20 "chips" haver exatamente um "chip" defeituoso.
b) Determine o valor de $k$ que maximiza a probabilidade calculada no item a).

# 5.5. A Distribuição Binomial 

Consideremos agora um experimento com apenas dois resultados possíveis, que chamaremos de sucesso e fracasso.

Por exemplo:
a) Jogamos uma moeda não-viciada e pomos sucesso $=$ cara, fracasso $=$ coroa.
b) Jogamos um dado não viciado e pomos sucesso $=0$ resultado é 5 ou 6 ; fracasso $=0$ resultado é $1,2,3$ ou 4.
c) De uma urna que contém 6 bolas brancas e 4 bolas pretas, sacamos uma bola e pomos sucesso $=$ a bola é preta; fracasso $=$ a bola é branca.

Chamaremos de $p$ a probabilidade de sucesso e $q=1-p$ a probabilidade de fracasso. Nos nossos exemplos os valores de $p$ são $\frac{1}{2}, \frac{2}{6}$ e $\frac{4}{10}$, respectivamente.

Suponhamos agora que façamos repetições (provas) do nosso experimento, realizando-o um número fixo $n$ de vezes.

Assim, por exemplo, no caso $n=3$ jogamos a moeda três vezes, jogamos o dado três vezes, sacamos sucessivamente 3 bolas da urna.

Suponhamos ainda que a probabilidade $p$ de sucesso mantenha-se constante ao longo das provas. Isso, no exemplo a, significa

que a probabilidade de obter cara em qualquer dos lançamentos é $1 / 2$.

Suponhamos finalmente que as provas sejam independentes, isto é, que o conhecimento do resultados de algumas provas não altere as probabilidades dos resultados das demais. Isso, no exemplo $c$, significa que as bolas são sacadas com reposição.

O problema que queremos resolver é o seguinte: Qual é a probabilidade de obtemos $k$ sucessos nesses $n$ provas?

A probabilidade de nessas $n$ provas obtemos $k$ sucessos e, em conseqüências, $n-k$ fracassos em uma ordem pré-determinada, por exemplo, os sucessos na $k$ primeiras provas e os fracassos nas demais:

$$
\frac{S S \cdots S}{k \text { vezes }} \frac{F F \cdots F}{n-k \text { vezes }}
$$

é

$$
\underbrace{p p p \cdots p}_{k \text { fatores }} \underbrace{(1-p) \cdots(1-p)}_{n-k \text { fatores }}=p^{k}(1-p)^{n-k}
$$

pois as provas são independentes.
É claro que, em outra ordem, a probabilidade seria a mesma pois apenas a ordem dos fatores se alteraria. A probabilidade de obtemos $k$ sucessos e $n-k$ fracassos em qualquer ordem é $p^{k}(1-p)^{n-k}$ multiplicado pelo número de ordem possíveis que é $\binom{n}{k}$ (para escolher uma ordem basta escolher em quais das $n$ provas ocorrerão os $k$ sucessos). Acabamos de provar o

Teorema Binomial: A probabilidade de ocorrerem exatamente $k$ sucessos em uma seqüência de $n$ provas independentes, na qual a probabilidade de sucesso em cada prova é $p$, é igual a

$$
\binom{n}{k} p^{k}(1-p)^{n-k}
$$

Exemplo 5.23: Jogamos uma moeda não-viciada 10 vezes. Qual é a probabilidade de obtermos exatamente 5 caras?
Solução: Pondo sucesso = cara, temos $p=1 / 2$ em cada prova e as provas são independentes. Queremos achar a probabilidade dc $k=5$ sucessos em $n=10$ provas. Pelo teorema binomial, a resposta é

$$
\binom{10}{5}\left(\frac{1}{2}\right)^{5}\left(1-\frac{1}{2}\right)^{5}=\frac{252}{1024}=\frac{63}{256}
$$

Exemplo 5.24: Um aluno marca ao acaso as respostas em um teste múltipla-escolha com 10 questöes e cinco alternativas por questão. Qual é a probabilidade dcle acertar exatamente 4 questöes?

Solução: Pondo sucesso = acerto, temos $p=1 / 5 \mathrm{~cm}$ cada prova, e as provas são independentes.

A probabilidade $p_{k}$ dele acertar $k$ questões é a probabilidade dele obter $k$ sucessos em $n=10$ provas. Pelo teorema binomial,

$$
p_{k}=\binom{10}{k}\left(\frac{1}{5}\right)^{k}\left(1-\frac{1}{5}\right)^{10-k}=\binom{10}{k} \frac{4^{10-k}}{5^{10}}
$$

A probabilidade dele acertar exatamente $k=4$ questões é

$$
p_{4}=\binom{10}{4} \frac{4^{6}}{5^{10}}=\frac{172032}{1953125} \approx 0,088
$$

E a probabilidade dele acertar pelo menos 4 questōes é

$$
\begin{aligned}
& 1-p_{0}-p_{1}-p_{2}-p_{3}= \\
& 1-\binom{10}{0} \frac{4^{10}}{5^{10}}-\binom{10}{1} \frac{4^{0}}{5^{10}}-\binom{10}{2} \frac{4^{8}}{5^{10}}-\binom{10}{3} \frac{4^{7}}{5^{10}} \\
& =\frac{1180409}{9765625} \approx 0,121
\end{aligned}
$$

Exemplo 5.25: Joga-se uma moeda não-viciada. Qual é a probabilidade de serem obtidas 5 caras antes de 3 coroas?

Solução: Pondo sucesso = cara, queremos a probabilidade de ocorrerem 5 sucessos antes que ocorram 3 fracassos. Ora, ocorrerão 5 sucessos antes que ocorram 3 fracassos se e só se nas 7 primeiras provas ocorrerem pelo menos 5 sucessos.

Como a probabilidade de $k$ sucessos em 7 provas é

$$
p_{k}=\binom{7}{k}\left(\frac{1}{2}\right)^{k}\left(1-\frac{1}{2}\right)^{7-k}=\binom{7}{k} \frac{1}{2^{7}}
$$

a resposta é

$$
p_{5}+p_{6}+p_{7}=\frac{\binom{7}{5}}{2^{7}}+\frac{\binom{7}{6}}{2^{7}}+\frac{\binom{7}{7}}{2^{7}}=\frac{29}{128} \approx 0,23
$$

# Exercícios 

1. Sacam-se, com reposição, 4 bolas de uma urna que contém 7 bolas brancas e 3 bolas pretas. Qual a probabilidade de serem sacadas 2 bolas de cada cor? Qual seria a resposta no caso sem reposição?
2. Lança-se um dado não viciado até a obtenção do terceiro 6. Seja $X$ o número do lançamento em que isso ocorre. Calcule:
a) $P(X=10)$;
b) $P(X>10)$;
c) $P(X<10)$.
3. Dois adversários $A$ e $B$ disputam um série de 10 partidas. A probabilidade de $A$ ganhar uma partida é 0,6 e não há empates. Qual é a probabilidade de $A$ ganhar a série?
4. Dois adversários $A$ e $B$ disputam uma série de partidas. $O$ primeiro que obtiver 12 vitórias ganha a série. No momento o resultado é $6 \times 4$ a favor de $A$. Qual é a probabilidade de $A$

ganhar a série sabendo que em cada partida as probabilidades de $A$ e $B$ vencerem são respectivamente 0,4 e 0,6 ?
5. Motores de avião funcionam independentemente e cada motor tem um probabilidade $p$ de falhar durante um vôo. Um avião voa com segurança se a maioria de seus motores funciona. Para que valores de $p$ um avião com 3 motores é preferível a um avião com 5 motores?
6. Suponha que uma característica (como a cor dos olhos, por exemplo) dependa de um par de genes. Representemos por $A$ um gen dominante e por a um gen recessivo. Assim um indivíduo com genes $A A$ é dominante puro, um com genes aa é um recessivo puro e um com genes $A a$ é um híbrido. Dominantes puros e híbridos são semelhantes em relação à característica. Filhos recebem um gen do pai e um da mãe. Suponha que pai e mãe sejam híbridos e tenham 4 filhos.
a) Qual é a probabilidade do primeiro filho ser um recessivo puro?
b) Qual é a probabilidade de exatamente um dos 4 filhos ser um recessivo puro?
7. (O problema das caixas de fósforos de Banach*) Um matemático sai de casa todos os dias com duas caixas de fósforos, cada uma com $n$ palitos. Toda vez que ele quer acender um cigarro, ele pega (ao acaso) uma das caixas e retira daí um palito. O matemático é meio distraído, de modo que quando ele retira o último palito de uma caixa, ele não percebe que a caixa fica vazia. Como ele fuma muito, em certa hora ele pega uma caixa e constata que ela está vazia. Qual é a probabilidade de nesse momento a outra caixa conter exatamente $k(0 \leq k \leq n)$ palitos?
8. Lança-se repetidamente um par de dados não tendenciosos. Qual é a probabilidade de obtermos duas somas iguais a 7 antes de obtermos três somas iguais a 3 ?
9. Uma moeda tem probabilidade 0,4 de dar cara. Lançando-a 12 vezes qual o mais provável valor do número de caras obtidas?

[^0]
[^0]:    *Stefan Banach (1892-1945), matemático polonês

# Apêndice 1 

## Demonstração do Princípio da Inclusão-Exclusão.

Seja $\Omega$ um conjunto.
Sejam $A_{1}, A_{2}, \ldots, A_{n}$ subconjuntos de $\Omega$ e sejam

$$
\begin{aligned}
& S_{0}=\#(\Omega) \\
& S_{1}=\sum_{i=1}^{n} \#\left(A_{i}\right) \\
& S_{2}=\sum_{l \leq i<j \leq n} \#\left(A_{i} \cap A_{j}\right) \\
& S_{3}=\sum_{l \leq i<j<k \leq n} \#\left(A_{i} \cap A_{j} \cap A_{k}\right) \cdots
\end{aligned}
$$

então:
a) O número de elementos de $\Omega$ que pertencem a exatamente $p$ dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ é

$$
a_{p}=\sum_{k=0}^{n-p}(-1)^{k}\binom{p+k}{k} S_{p+k}
$$

b) O número de elementos de $\Omega$ que pertecem a pelo menos $p$ dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ é

$$
b_{p}=\sum_{k=0}^{n-p}(-1)^{k}\binom{p+k-1}{k} S_{p+k}
$$

c) O número de elementos do conjunto $A_{1} \cup A_{2} \cup \cdots \cup A_{n}$ é

$$
S_{1}-S_{2}+\cdots+(-1)^{n-1} S_{n}
$$

Demonstração do caso a: Como é óbvio que, se um elemento de $\Omega$ pertence a menos do que $p$ dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$, ele não é contado na soma $a_{p}$, o que devemos provar é que se um elemento de $\Omega$ pertence a exatamente $p$ dos conjuntos então ele é contado uma vez na soma $a_{p}$ e que se um elemento pertence a mais do que $p$ dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ então ele não é contado na soma $a_{p}$.

Ora, a soma $a_{p}$ é

$$
\binom{p}{0} S_{p}-\binom{p+1}{1} S_{p+1}+\binom{p+2}{2} S_{p+2}-\cdots+(-1)^{n-p}\binom{n}{n-p} S_{n}
$$

Um elemento de $\Omega$ que pertence a exatamente $p$ dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ é contado uma vez em $S_{p}$ e não é contado em $S_{p+1}, S_{p+2}, \ldots, S_{n}$. Logo, ele é contado $\binom{p}{0} \cdot 1=1$ vez.

Um elemento de $\Omega$ que pertence a exatamente $p+j(j>$ $0, p+j \leq n$ ) dos conjuntos $A_{1}, A_{2}, \ldots, A_{n}$ é contado em $\binom{p+j}{p}$ das parcelas de $S_{p}$, em $\binom{p+j}{p+1}$ das parcelas de $S_{p+1}$ etc...

Logo, o número de vezes que ele é contado na soma $a_{p}$ é:

$$
\begin{aligned}
\cdot\left(\begin{array}{l}
p \\
0
\end{array}\right)\binom{p+j}{p} & -\binom{p+1}{1}\binom{p+j}{p+1}+\cdots+(-1)^{n-p}\binom{n}{n-p}\binom{p+j}{n} \\
& =\sum_{k=0}^{j}(-1)^{k}\binom{p+k}{k}\binom{p+j}{p+k} \\
& =\sum_{k=0}^{j} \frac{(p+k)!(p+j)!}{k!p!(p+k)!(j-k)!} \\
& =\frac{(p+j)!}{p!} \sum_{k=0}^{j}(-1)^{k} \frac{1}{k!(j-k)!} \\
& =\frac{(p+j)!}{p!j!} \sum_{k=0}^{j}(-1)^{k}\binom{j}{k} \\
& =\binom{p+j}{p}(1-1)^{j}=0
\end{aligned}
$$

Demonstração do caso b: Temos

$$
\begin{aligned}
b_{p} & =a_{p}+a_{p+1}+a_{p+2}+\cdots+a_{n-1}+a_{n}= \\
& =\sum_{k=0}^{n-p}(-1)^{k}\binom{p+k}{k} S_{p+k}+\sum_{k=0}^{n-p-1}(-1)^{k}\binom{p+1+k}{k} S_{p+1+k}+ \\
& +\sum_{k=0}^{n-p-2}(-1)^{k}\binom{p+2+k}{k} S_{p+2+k}+\cdots+ \\
& +\cdots+\sum_{k=0}^{1}(-1)^{k}\binom{n-1+k}{k} S_{n-1+k}+ \\
& +\sum_{k=0}^{0}(-1)^{k}\binom{n+k}{k} S_{n+k}
\end{aligned}
$$

O coeficiente de $S_{p+j}(0 \leq j \leq n-p)$ no $2^{\circ}$ membro é

$$
\begin{gathered}
(-1)^{j}\binom{p+j}{j}+(-1)^{j-1}\binom{p+j}{j-1}+(-1)^{j-2}\binom{p+j}{j-2}+\cdots+ \\
+\cdots+(-1)^{1}\left(p^{i+j}\right)+(-1)^{0}\left(p_{0}^{p+j}\right) \\
=(-1)^{j}\left[\left(p^{+j-1}\right)+\binom{p+j-1}{j-1}\right] \\
+(-1)^{j-1}\left[\left(p_{j-1}^{+j-1}\right)+\binom{p+j-1}{j-2}\right] \\
+(-1)^{j-2}\left[\left(p_{j-2}^{+j-1}\right)+\binom{p+j-1}{j-3}\right]+\cdots+ \\
+\cdots+(-1)^{1}\left[\left(p_{1}^{+j-1}\right)+\binom{p+j-1}{0}\right] \\
+(-1)^{0}\left(p_{0}^{+j-1}\right) \\
=(-1)^{j}\binom{p+j-1}{j}
\end{gathered}
$$

Logo,

$$
b_{p}=\sum_{j=0}^{n-p}(-1)^{j}\binom{p+j-1}{j} S_{p+j}=\sum_{k=0}^{n-p}(-1)^{k}\binom{p+k-1}{k} S_{p+k}
$$

# Demonstração do caso c: 

$$
\begin{aligned}
\#\left(A_{1} \cup A_{2} \cup \cdots \cup A_{n}\right) & =b_{1} \\
& =\sum_{j=0}^{n-1}(-1)^{j}\binom{j}{j} S_{j+1} \\
& =S_{1}-S_{2}+\cdots+(-1)^{n-1} S_{n}
\end{aligned}
$$

De modo análogo, prova-se a versão probabilística do princípio da Inclusão-Exclusão.

Sejam $A_{1}, A_{2}, \ldots, A_{n}$ eventos e sejam

$$
\begin{aligned}
& S_{0}=1 \\
& S_{1}=\sum_{i=1}^{n} P\left(A_{i}\right) \\
& S_{2}=\sum_{l \leq i<j \leq n} P\left(A_{i} \cap A_{j}\right) \\
& S_{3}=\sum_{l \leq i<j<k \leq n} P\left(A_{i} \cap A_{j} \cap A_{k}\right)
\end{aligned}
$$

então:
a) A probabilidade de ocorrência de exatamente $p$ dos eventos $A_{1}, A_{2}, \ldots, A_{n}$ é

$$
a_{p}=\sum_{k=0}^{n-p}(-1)^{k}\binom{p+k}{k} S_{p+k}
$$

b) A probabilidade de ocorrência de pelo menos $p$ dos eventos $A_{1}, A_{2}, \ldots, A_{n}$ é

$$
b_{p}=\sum_{k=0}^{n-p}(-1)^{k}\binom{p+k-1}{k} S_{p+k}
$$

c) A probabilidade de ocorrência do evento $A_{1} \cup A_{2} \cup \cdots \cup A_{n}$ é

$$
S_{1}-S_{2}+\cdots+(-1)^{n-1} S_{n}
$$

# Apêndice 2 

## A Solução de Kaplansky para o Problema de Lucas.

Tem-se $n(n>1)$ casais que devem se sentar em $2 n$ cadeiras diferentes em torno de um círculo de modo que pessoas de mesmo sexo não se sentem juntas e que nenhum homem fique ao lado de sua mulher. De quantos modos isso pode ser feito?

Numeremos os lugares de 1 a $2 n$. A exigência de pessoas de mesmo sexo não se sentarem juntas exige que os homens ocupem os lugares pares e as mulheres os ímpares ou vice-versa. Escolhido qual o sexo que ocupará os lugares ímpares ( 2 modos), devemos colocar os homens nos lugares a eles reservados ( $n$ ! modos). Só falta agora colocar as $n$ mulheres nos $n$ lugares restantes, sendo vedada a colocação de alguma mulher ao lado de seu marido.

A resposta do problema de Lucas é $2(n!) U_{n}$ onde $U_{n}$ é o número de modos de colocar as $n$ mulheres nos $n$ lugares vazios, sendo vedada a colocação de alguma mulher ao lado de seu marido. Calculemos $U_{n}$.

A figura A1 ilustra o caso $n=5$. Devemos colocar as cinco mulheres $M_{1}, M_{2}, M_{3}, M_{4}, M_{5}$ nos lugares agora numerados $1,2,3,4,5$ de modo que $M_{1}$ não pode ocupar os lugares 5 e $1, M_{2}$

não pode ocupar 1 e $2, M_{3}$ não pode ocupar 2 e $3, M_{4}$ não pode ocupar 3 e 4 e $M_{5}$ não pode ocupar 4 e 5 .

Definamos, para $1 \leq i \leq n$,
$\Omega=$ conjunto das permutações das mulheres;
$A_{i}=$ conjunto das permutações das mulheres em que $M_{i}$ ocupa o $i$-ésimo lugar;
$A_{i}^{\prime}=$ conjunto das permutações das mulheres em que $M_{i}$ ocupa o $(i-1)$-ésimo lugar. (OBS: $1-1=n$ ).
![img-34.jpeg](img-34.jpeg)

Fig. A1

Arrumemos os $2 n$ conjuntos na ordem

$$
A_{1}^{\prime}, A_{1}, A_{2}^{\prime}, A_{2}, \ldots, A_{n}^{\prime}, A_{n}
$$

Queremos determinar $U_{n}$, número de elementos de $\Omega$ que não pertencem a nenhum dos conjuntos $A_{1}^{\prime}, A_{1}, A_{2}^{\prime}, A_{2}, \ldots, A_{n}^{\prime}, A_{n}$.

Pelo Princípio da Inclusão-Exclusão,

$$
U_{n}=a_{0}=\sum_{k=0}^{2 n}(-1)^{k} C_{0+k}^{k} S_{0+k}=\sum_{k=0}^{2 n}(-1)^{k} S_{k}
$$

Para calcular $S_{k}$ observemos que:
i) Uma interseção de $k$ dos conjuntos $A_{1}^{\prime}, A_{1}, A_{2}^{\prime}, A_{2}, \ldots, A_{n}^{\prime}$, $A_{n}$ que contenha dois conjuntos consecutivos (imaginandoos em circulo!) é vazia. Por exemplo, $A_{1}^{\prime} \cap A_{1} \cap \cdots$ é vazia pois $M_{1}$ não pode ocupar simultaneamente os lugares 1 e $n ; A_{n} \cap A_{1}^{\prime} \cap \cdots$, é vazia pois o $n$-ésimo lugar não pode ser ocupado simultaneamente por $M_{n}$ e $M_{1}$.
ii) Uma interseção de $k$ dos conjuntos $A_{1}^{\prime}, A_{1}, A_{2}^{\prime}, A_{2}, \ldots, A_{n}^{\prime}$, $A_{n}$ que não contenha dois conjuntos consecutivos (imaginan-do-os em círculos) é uma permutação de $n$ elementos com $k$ elementos em posições pré-fixadas e, portanto, possui $(n-k)$ ! elementos $(k \leq n)$.
iii) Há, pelo segundo Lema de Kaplansky,

$$
g(2 n, k)=\frac{2 n}{2 n-k}\binom{2 n-k}{k} \text { interseções do tipo ii). }
$$

Logo, $S_{k}$ é uma soma com

$$
\frac{2 n}{2 n-k}\binom{2 n-k}{k}
$$

parcelas iguais a $(n-k)$ ! e com as demais parcelas nulas. Portanto,

$$
S_{n}=\frac{2 n}{(2 n-k)}\binom{2 n-k}{k}(n-k)!
$$

(Observe que essa fórmula vale para $k=0$ pois $S_{0}=n!$ ).
Logo,

$$
U_{n}=\sum_{k=0}^{n}(-1)^{k} \cdot \frac{2 n}{2 n-k}\binom{2 n-k}{k}(n-k)!
$$

e a resposta do problema de Lucas* é

$$
2 \cdot(n!) U_{n} \quad(n>1)
$$

[^0]
[^0]:    *Edouard Lucas (1842-1891), matemático francês.

# Apêndice 3 

Demonstração da desigualdade $\left(1-\frac{1}{N}\right)^{n} \geq 1-\frac{n}{N}$

$$
\begin{aligned}
\left(1-\frac{1}{N}\right)^{n} & =\left(1-\frac{1}{N}\right)^{n-1}\left(1-\frac{1}{N}\right) \\
& =\left(1-\frac{1}{N}\right)^{n-1}-\frac{1}{N}\left(1-\frac{1}{N}\right)^{n-1} \\
& \geq\left(1-\frac{1}{N}\right)^{n-1}-\frac{1}{N}
\end{aligned}
$$

Com o mesmo raciocínio aplicado agora a

$$
\left(1-\frac{1}{N}\right)^{n-1}
$$

temos

$$
\left(1-\frac{1}{N}\right)^{n-1} \geq\left(1-\frac{1}{N}\right)^{n-2}-\frac{1}{N}
$$

e portanto

$$
\left(1-\frac{1}{N}\right)^{n} \geq\left(1-\frac{1}{N}\right)^{n-2}-\frac{2}{N}
$$

Continuando temos

$$
\left(1-\frac{1}{N}\right)^{n} \geq\left(1-\frac{1}{N}\right)^{n-3}-\frac{3}{N}
$$

# Apêndice 3 

e finalmente

$$
\left(1-\frac{1}{N}\right)^{n} \geq\left(1-\frac{1}{N}\right)^{n-n}-\frac{n}{N}=1-\frac{n}{N}
$$

o que prova a desigualdade.

# Respostas dos Exercícios 

## Seção 2.1

1) $15600 ;$ 2) 9765625 ; 3) 4536 ; 4) 132 ; 5) 60 ; 6a) 3864 ; 6b) 1567 ; 6c) 560 ; 7a) 2401 ; 7b) 840 ; 8a) 24 ; 8b) 18 ; 9) 4464 ; 10) $2^{n}$; 11) 40320 ; 12) 461 ; 13) 2350 ; 14) 48 ; 15) 43200 ; 16) 2048 ; 17) 320 ; 18) 108642 ; 19a) 37512 ; 19b) 52488 ; 20) 243 ; 21) 30 ; 22) 18 ; 23) 98475 ; 24) $6^{27}$; 25a) 2418 ; 25b) 15 ; 25c) 48 ; 25d) 8 ; 26a) 1214400 ; 26b) 1658775 ; 27a) $\lambda(\lambda-1)\left(\lambda^{2}-3 \lambda+3\right)$; 27b) 2 ; 28a) $\lambda(\lambda-1)(\lambda-2)(\lambda-3) ; 28 b) 4 ; 29 a) 3612 ; 29 b) 1806$

## Seção 2.2

1a) 11520 ;
1b) 720 ;
1c) 4320 ;
1d) 1152 ;
1e) 720 ;
1f) $9360 ; 1 \mathrm{~g}) 13080 ; 2 \mathrm{a}) 81^{\circ} 2 \mathrm{~b}) 46721 ; 2 \mathrm{c}) 1 ; 2 \mathrm{~d}) 5333280$;
3) 3600 ; 4) $n!; 5$ ) 8640 ; 6) 604800 ; 7a) 462 ; 7b) 5775 ; 7c) 792 ; 7d) 10395 ; 7e) 51975 ; 8) $m!(r+1)!; 9) 564480$; 10) 720 ; 11) 30 ; 12a) 2 ; 12b) 1680 ; 12c) 7983360 ; 12d) $\frac{200}{160} \approx 4 \times 10^{16} ; 12$ e) 3360 ; 12f) 30 ; 13) 10395 ; 14) $6 \times 4^{n-3}$; 15) $2 \times 3^{n-2}$;

# Seção 2.3 

1a) $560 ; 1 \mathrm{~b})$ 434; 2) $6300 ; 3) \frac{n(n-3)}{2}$; 4a) 3; 4b) 36; 4c) 100; 4d) 4; 4e) 18; 5) 280; 6) 40; 7) $C_{n}^{m}$; 8) 267148 ; 9) $12960 ; 10) 14976 ; 11 \mathrm{a}) C_{n-1}^{p-1} ; 11 \mathrm{~b}) C_{n-1}^{p} ; 11 \mathrm{c}) C_{n-2}^{p-2}$; 11d) $2 C_{n-2}^{p-1}+C_{n-2}^{p-2}=C_{n}^{p}-C_{n-2}^{p} ; 11$ e) $2 C_{n-2}^{p-1} ; 12$ a) $C_{n}^{2} ; 12 \mathrm{~b}$ ) $\frac{n^{4}-6 n^{4}+11 n^{2}+2 n}{8} ; 13 \mathrm{a}) \frac{C_{22}^{42}}{2!}=92378 ; 13 \mathrm{~b}) \frac{C_{28}^{8} \times C_{3}^{3} \times C_{16}^{8} \times 1}{88864376 ; 13 \mathrm{c})} C_{20}^{12} \times 1=125970 ; 13 \mathrm{~d}) \frac{C_{2 a}^{8} \times C_{14}^{2} \times C_{8}^{8} \times 1}{3!}=$ $543182640 ; 14 \mathrm{a}) 201376 ; 14 \mathrm{~b}) 107520 ; 14 \mathrm{c}) 24192 ; 14 \mathrm{~d})$ 10752; 14e) 224; 14f) 1344; 14g) 4080; 14h) 208; 14i) 16; 14j) 4; 15a) $n!; 15$ b) $\frac{(n+1)!n}{2} ; 15 \mathrm{c}) \frac{(n+2)!n(3 n+1)}{25}$; 16) 1085; 17a) $12972960 ; 17$ b) $6985440 ; 18) \frac{n(n-1)(n-2)(n-3)}{8}$; 19a) $\frac{n}{8}\left(n^{3}-10 n^{2}+35 n-34\right)$; 19b) $\frac{n(n-1)(n-2)(n-3)}{24} ; 19 \mathrm{c})$ $\frac{n(n-3)(n-4)(n-5)}{12} ; 20) 138378240 ; 21$ a) 126; 21b) 70; 22) $151200 ; 23) 126 ; 24) \frac{(m+h)!}{m!h!} ; 25) 512 ; 26) 2^{n-1} ; 27)$ $756756 ; 28 \mathrm{a}) 2^{n^{2}} ; 28 \mathrm{~b}) 2^{n^{2}-n} ; 28 \mathrm{c}) 2^{\frac{n^{2}+n}{2}} ; 28 \mathrm{~d}) 2^{n} \times 3^{\frac{n^{2}-n}{2}}$ 28e) $2^{\frac{n^{2}-n}{2}} ; 28 \mathrm{f}) 3^{\frac{n^{2}-n}{2}} ; 2 \mathrm{sg}) 2^{n} ; 28 \mathrm{~h}) 1 ; 29) 190 ; 30 \mathrm{a})$ $250000 ; 30 \mathrm{~b}) 86400 ; 31) 2^{m}-1 ; 32 \mathrm{a}) 28 ; 32 \mathrm{~b}) 7 ; 33 \mathrm{a})$ $\frac{t k}{a} ; 33 \mathrm{~b}) \frac{t k(k-1)}{a(a-1)} ; 34 \mathrm{a})$ As linhas são $P P B B, P B P B, P B B P$, $B P P B, B P B P, B B P P ; 37) 424051 ; 40)$ Não.

## Seção 2.4

1) $2880 ; 2 \mathrm{a}) 2 \times(n-2)!; 2 \mathrm{~b}) p!\times(n-p)!; 3)(n-1)! \times 2^{n}$;
2) $2 \times(n-1)!$;
3) $\frac{(n-1)!}{2}$;
4) 720
5) 360
6) 120
7) 6 d ) 60
8) 7) $86400 ; 8) 2$.

## Seção 2.5

1a) 462 ;
1b) 210
2) 300
3) $\frac{(a+k)!}{a!b!}$;
4) $\frac{(a+b+c)!}{a!b!c!}$;
5) 30 .

# Seção 2.6 

1) 20 ;
2) 126 ;
3) 36 ;
4) 84 ;
5) 28 ;
6) $\frac{(m+n-1)!}{(n-1)!m!}$;
7) $1359072 ; 8) \frac{(n+p-1)!}{(n-1)!p!}$;
8) $\frac{(n+p)!}{n!p!}$;
9) $\frac{(n+p)!}{n!p!}$;
10) $10295472 ; 11) 28$;
11) 210 ;
12) 13a) $3420 ; 13$ b) 3711 ;
13) $5004 ; 15) 825$;
14) 2001 ;
15) 1016 ;
16) $\frac{n!}{(n-p)!}$;
17) $\frac{n!}{p!(n-p)!}$;
18b) $n^{p}$;
18d) $\frac{(n+p-1)!}{(n-1)!p!}$;
18e) $n^{p}$;
19a) $n^{p}$;
19b) $\frac{n!}{(n-p)!}$;
19c) $\frac{n!}{p!(n-p)!}$;
19d) $\frac{(n+p-1)!}{(n-1)!p!}$;
19e) Sejam $A \in B$ conjuntos ordenados com $\# A=p$ e $\# B=n . C_{n}^{p}$ é o número de funções $f: A \rightarrow B$ estritamente crescentes, $C R_{n}^{p}$ é o número de funções $f: A \rightarrow B$ não-decrescentes, $A_{n}^{p}$ é o número de funções $f: A \rightarrow B$ injetoras e $A R_{n}^{p}$ é o número de funções $f: A \rightarrow B ; 20$ a) $n!; 20$ b) $P_{n}$ é o número de bijeções $f: A \rightarrow A$ onde $\# A=n ; 21$ a) 191300 ;
20b) 183800
21) 60480 .

## Seção 3.1

1a) 62 ;
1b) 286 ;
1c) 419 ;
1d) 714 ;
2) 2400 ;
3) 25 ;
4) 45 ;
5) $\sum_{k=0}^{p}(-1)^{k} C_{p}^{k}(p-k)^{n}$;
6) 504 ;
7a) $3^{n}$;
7b) $3^{n}-3$.
$2^{n}+3 ;$
6) 864 ;
7) $998910 ; 10) \sum_{k=0}^{n-1}(-1)^{k} C_{n-1}^{k}(n-k)!$
11) 1625 ;
12) 96 ;
13) 20 ;
14) $p-1$;
15) 200
16a) $n^{\mu}$;
16b) $\sum_{k=0}^{n}(-1)^{k} C_{n}^{k}(n-k)^{\mu} ; 17$ a) $\frac{(n+\mu-1)!}{\mu!(n-1)!} ; 17$ b) $\frac{(\mu-1)!}{(n-1)!(\mu-n)!} ; 18$ ) $\frac{n!}{\mu!(n-\mu)!}$.

## Seção 3.2

1a) $(n-1)^{n}$;
1b) $n!\left[\frac{1}{1!!}-\frac{1}{1!}+\frac{1}{2!}-\cdots+\frac{(-1)^{n}}{n!}\right]$;
2) 315 ;
3) 1936;
4) 14833 ;
5) 190800
6) $\sum_{k=0}^{n}(-1)^{k} C_{n}^{k}(2 n-k)!$.

# Seção 3.3 

1) $45360 ;$ 2) 50 ; 3) $\frac{(p+1)!}{q!(p-q+1)!}$; 4) $C_{p+q}^{p} \times C_{p+q+1}^{r}$; 5) $\frac{(11!)^{2}}{10} \approx$ $1,6 \times 10^{14}$; 6) 120 ; 7) $C_{n-(p-1) r}^{p}$; 8) $\frac{n}{n-p r} C_{n-p r}^{p}$.

## Seção 3.4

1a) $(m+n)!$; 1b) $\frac{n}{m+1}(m+n)!$; 1c) $(m+n)!\frac{n(n-1)(n-2)}{(m+3)(m+2)(m+1)}$
2a) 15504 ; 2b) 7752 ; 2c) 10659.

## Seção 3.5

1) 3 ; 2) 6 ; 3) 6 ; 4 b) $\{(0,0,0) ;(0,0,1) ;(0,1,0) ;(1,0,0) ;(1,1,0)$; $(1,0,1) ;(0,1,1) ;(1,1,1)\} ; 5) 49$.

## Seção 4.1

6) 9 ; 7) Impossivel; 8a) 31 ; 8b) 30 ; 9) $2^{n}-1$; 10) 120 ; 11) 127 ; 12) $(n+2) 2^{n-1}$; 13) $(n+1) n 2^{n-2}$; 14) $\frac{2^{n+1}-1}{n+1}$; 17) $301750 ; 18) \frac{n^{2}(n+1)^{2}}{4} ; 19) \frac{n(n+1)(4 n+5)}{5} ; 20) \frac{6 n^{4}+20 n^{3}-3 n^{2}-5 n}{6}$; 21) $(-1)^{p} C_{n-1}^{p} ; 22) C_{n}^{k} \cdot 2^{1000-n} ; 24) C_{n+p}^{p} ; 27) C_{2 n}^{n-2} ; 28)$ $n C_{2 n-1}^{n-1} ; 29) p=5 ; 30) p=10$ ou $p=11 ; 31) p=1$ ou $p=14 ; 32) p=3 ; 35 a) C_{n-k}^{p-1} ; 35 b) \frac{n+1}{p+1} ; 37) k=0 ; 38)$ $2^{m}\binom{n}{m} ; 39)\binom{n+m}{n}$.

## Seção 4.2

1) $T_{5}=70 x^{4}$; 2a) $T_{5}=\frac{-560}{x^{2}}$; 2b) $T_{5}=\frac{280}{x^{2}}$; 3) $T_{5}=210$;
2) -1760 ; 5) 755 ; 6) $\frac{n^{2}-5 n+2}{2}$; 7) $n$ múltiplo de 5 ; 8) 0 termo máximo é $T_{41}=\frac{C_{100}^{20}}{2^{48}}$ e o termo mínimo é $T_{121}=\frac{1}{2^{128}}$; 9) -1 ; 10) $\frac{(-1)^{n}-5^{n}}{2}$; 11) $a ; 12) 3^{n} ; 13) 3 n \cdot 4^{n-1} ; 14) 24$; 15) $\frac{1}{2^{28}} ; 17$ a) $2^{n-p} ; 17$ b) $3^{n} ; 21$ a) $2^{n-1} ; 21$ b) $2^{n-1} ; 22$ ) $S_{1}=S_{2}=n 2^{n-2} ; 23) 0 ; 25) a_{5}=\frac{6875}{24} ; 26) 4 n(n-1) 3^{n-2}$; 27) $5 n(5 n+1) 6^{n-2}$.

# Seção 4.3 

1) 3420 ; 2) i; 3) 1771 ; 4) $\left(x_{1}+x_{2}+\cdots+x_{n}\right)^{3}=\sum x_{i}^{3}+$ $3 \sum_{i, j} x_{i}^{2} x_{j}+6 \sum_{i<j<k} x_{i} x_{j} x_{k}$

## Seção 5.3

1) 0,999 aproximadamente; 2) $P\left(A_{1}\right)=\frac{5}{64}, P\left(A_{2}\right)=\frac{26}{54}, P\left(A_{3}\right)=$ $\frac{25}{108}, P\left(A_{4}\right)=\frac{25}{162}, P\left(A_{5}\right)=\frac{25}{648}, P\left(A_{6}\right)=\frac{25}{1296}, P\left(A_{7}\right)=\frac{1}{1296}$, $P\left(A_{8}\right)=\frac{5}{162} ; 3 \mathrm{a}) \frac{7}{18} ; 3 \mathrm{~b}) \frac{1}{12} ; 4 \mathrm{a}) \frac{2}{5} ; 4 \mathrm{~b}) \frac{2}{5} ; 5) \frac{b-1}{2} \cdot \frac{(b-1)!}{b^{k-2}}$; 6) $\frac{4}{9} ; 7 \mathrm{a}) \frac{1}{126} ; 7 \mathrm{~b}) \frac{1}{42} ; 8) \frac{63}{200} ; 9) \frac{4}{5} \mathrm{e} \frac{1}{5} ; 10) \frac{21}{n(n+1)} ; 11)$ $\frac{25}{216} ; 12) \frac{1}{6} ; 13) \frac{\left({ }_{1}^{n}\right)\left({ }_{n}^{n_{n}}\right)}{(n)} ; 14) \frac{\left({ }_{1}^{n}\right)}{2^{n}} ; 15 \mathrm{a}) \frac{15}{20} ; 15 \mathrm{~b}) \frac{1}{2} ; 15 \mathrm{c})$ $\frac{3}{4} ; 15 \mathrm{~d}) \frac{5}{16} ; 15 \mathrm{e}) \frac{1}{20} ; 15 \mathrm{f}) \frac{9}{20} ; 15 \mathrm{~g}) \frac{4}{5} ; 16 \mathrm{a}) \frac{10}{81} ; 16 \mathrm{~b})$ $\frac{18}{77} 17 \mathrm{a}) \frac{313}{529090} ; 17 \mathrm{~b}) \frac{22}{1324225} ; 17 \mathrm{c}) \frac{15890700}{15890700} ; 17 \mathrm{~d}) \frac{7545350}{7545350}$; 18a) $\frac{333}{209132} ; 18$ b) $\frac{15}{59752} ; 18 \mathrm{c}) \frac{15}{298760} ; 19 \mathrm{a}) \frac{8}{1594323} ; 19 \mathrm{~b})$ $\frac{3}{531441} ; 19 \mathrm{c}) \frac{2}{531441} ; 19 \mathrm{~d}) \frac{1}{1594323} ; 20) \frac{7}{18} ; 21 \mathrm{a}) \frac{1}{25} ; 21 \mathrm{~b})$ $\frac{1}{55} ; 22 \mathrm{a}) \frac{1}{55} ; 21 \mathrm{~b}) \frac{14}{55} ; 22 \mathrm{a}) \frac{1}{126} ; 22 \mathrm{~b}) \frac{5}{126} ; 23) \frac{\left({ }_{n}^{2 n-2-k}\right)}{\binom{2 n}{n}}$ 24) $\frac{\left({ }_{1}^{n}\right)\left({ }_{k-2 k}^{n-k}\right)^{2 k-2 k}}{\binom{2 n}{k}} ; 25) \frac{n!}{\binom{n}{n}} ; 26) \frac{n+1}{2(2 n-1)} ; 27 \mathrm{a}) \frac{1}{15134} ; 27 \mathrm{~b})$ $\frac{6}{7507} ; 27 \mathrm{c}) \frac{90}{7507} ; 27 \mathrm{~d}) \frac{480}{52969} ; 27 \mathrm{e}) \frac{6075}{108938} ; 27 \mathrm{f}) 0 ; 28)$ $\frac{n(n-1) \cdots(n-p+2)(p-i)}{n^{2}} ; 29) \frac{(n-m)(n-m-1)}{n(n-1)} ; 30) \frac{2(n-m-1)}{n(n-1)} ; 31)$ $\frac{2}{5} ; 32) \frac{3}{11} ; 33) \frac{2}{n-1} ; 34) \frac{1}{12} ; 35) \frac{11}{3006} ; 36 \mathrm{a}) \frac{43}{60} ; 36 \mathrm{~b}) \frac{2}{15}$; 36c) $\frac{11}{30} ; 36 \mathrm{~d}) \frac{3}{20} ; 37 \mathrm{a}) \frac{4}{15} ; 37 \mathrm{~b}) \frac{7}{60} ; 37 \mathrm{c}) 0,2 ; 37 \mathrm{~d}) \frac{11}{12}$; 37 e$) 0,8$.

## Seção 5.4

1) $\frac{14}{15} ;$ 2) $\frac{3}{16} ;$ 3) $\frac{7}{8} ;$ 4) $\frac{1}{5} ;$ 5) $\frac{3}{5} ;$ 6) $\frac{5}{12} ;$ 7) $\frac{4}{2} ; 8 \mathrm{a})$ $\frac{2}{3} ; 8 \mathrm{~b}) \frac{2}{8} ; 8 \mathrm{c}) \frac{1}{3} ;$ 9) $\frac{1}{9} ; 11) p^{2}+4 p^{3}-8 p^{4}+5 p^{5}-p^{6}$; 13a) $\left\{\frac{1}{6!}-\frac{1}{1!}+\cdots+\frac{(-1)^{n-k}}{n-k!}\right\} \frac{1}{k!} ; 13 \mathrm{~b}) \frac{k}{n} ; 13 \mathrm{c}) \frac{n-2}{n(n-1)} ; 13 \mathrm{~d})$ $\frac{n-2}{(n-1)^{2}} ; 14)$ Sim, Sim, Sim e Não; 15a) $\frac{1}{n} ; 15 \mathrm{~b}), \frac{(n-1)^{k-1}}{n^{k}}$;

16a) $\frac{671}{1296} \approx 0,518 ; 16$ b) $1-\left(\frac{35}{36}\right)^{24} \approx 0,491 ; 17) 1-0,9^{10} \approx$ $0,65 ; 18) \quad \frac{1}{52} ; 19 \mathrm{a}) \quad \frac{6327}{201825} \approx 0,30 ; 19 \mathrm{~b}) \quad \frac{468}{201825} \approx 0,02 ; 19 \mathrm{c})$ $\frac{40}{832} \approx 0,06 \quad 19 \mathrm{~d}) \quad \frac{4436}{20832} \approx 0,21 ; 19 \mathrm{e}) \quad \frac{2197}{204325} \approx 0,11 ; 19 \mathrm{f})$ $\frac{286}{201827} \approx 0,01 ; 19 \mathrm{~g}) \quad \frac{936}{20825} \approx 0,04 ; 19 \mathrm{~h}) \quad \frac{1391}{7249} \approx 0,19 ; 20)$ $\frac{95}{294} \approx 0,32 ; 21 \mathrm{a}) 0,2401 ; 21 \mathrm{~b}) 0,5904 ; 21 \mathrm{c}) 0,1695 ; 21 \mathrm{~d})$ $0,0256 ; 21 \mathrm{e}) 0,9375 ; 21 \mathrm{f}) 0,0369 ; 21 \mathrm{~g}) 0,0434 ; 21 \mathrm{~h}) \frac{434}{2465}$; 22a) $\frac{1}{6} ; 22 \mathrm{~b}) \quad \frac{2}{3} ; 22 \mathrm{c}) \quad \frac{1}{6} ; 22 \mathrm{~d}) \quad \frac{1}{210} ; 22 \mathrm{e}) \quad \frac{41}{42} ; 22 \mathrm{f}) \quad \frac{4}{105}$; 22g) $\frac{1}{21} ; 22 \mathrm{~h}) \quad \frac{2}{28} ; 23) \quad \frac{1}{2} ; 24) 253 ; 25) \frac{\left(\frac{2 n}{n}\right)^{2}}{\left(\frac{4 n}{5 n}\right)} ; 26) \quad \frac{7}{12}$; 27a) $\left(\frac{n-1}{n}\right)^{m-1} ; 27 \mathrm{~b}) \quad \frac{n!}{(n-m)!n^{m}} ; 28) \quad \frac{13}{41} ; 29 \mathrm{a}) \quad \frac{a}{a+b} ; 29 \mathrm{~b})$ $\frac{a}{a+b} ; 29 \mathrm{c}) \quad \frac{a}{a+b} ; 29 \mathrm{~d}) \quad \frac{a+p}{a+b+p} ; 29 \mathrm{e}) \quad \frac{a+p}{a+b+p} ; 30 \mathrm{a}) \quad \frac{1}{2^{k-1}} ; 30 \mathrm{~b})$ $\frac{1}{2^{k}}$, se $k<n ; \frac{1}{2^{n-1}}$ se $k=n ; 31) \quad \frac{2^{n-1}}{2^{n}-1} ; 32) \quad \frac{9^{n}-8^{n}-5^{n}+4^{n}}{9^{n}} ; 33$ ) 13; 34) As probabilidades são iguais; 35a) $\frac{\left(\frac{19}{2}\right)\left(\frac{k-10}{2}\right)}{(13)} ; 35 \mathrm{~b}) 99$ ou 100; 36) Uma urna recebe uma bola branca e a outra recebe as 99 bolas restantes; 37a) $\frac{41}{96} ; 37 \mathrm{~b}) \quad \frac{1}{1728} ; 37 \mathrm{c}) \quad \frac{11}{576} ; 37 \mathrm{~d})$ $\frac{11}{432} ; 37 \mathrm{e}) \quad \frac{55}{96} ; 38 \mathrm{a}) \quad p_{1}=\frac{1+2 p}{4} ; 38 \mathrm{~b}) 0,7 ; 39 \mathrm{a}) \frac{\left(\frac{11}{11}\right)\left(\frac{1006-k}{14}\right)}{\left(\frac{1889}{20}\right)} ;$ 39b) $k=50$.

# Seção 5.5 

1a) $0,2646 ; 1 \mathrm{~b}) 0,3 ; 2 \mathrm{a}) \frac{78125}{1679616} \approx 0,05 ; 2 \mathrm{~b}) \frac{1953125}{2519424} \approx$ $0,78 ; 2 \mathrm{c}) \quad \frac{808723}{5038848} \approx 0,18 ; 3$ ) Aproximadamente 0,$63 ; 4$ ) Aproximadamente 0,$43 ; 5) p>\frac{1}{2} ; 6 \mathrm{a}) \frac{1}{4} ; 6 \mathrm{~b}) \frac{27}{64} ; 7) \frac{\left(2 n-k_{1}\right.}{22 n-k}$; 8) $\frac{243}{256} ; 9) 5$.

# Bibliografia 

## Análise Combinatória

Os livros abaixo abordam mais ou menos as mesmas coisas que este livro, com o mesmo grau de complexidade.
[1] "Mathematics of Choice" - Ivan Niven-Random House, The L. W. Singer Company - Nova Iorque - 1972 - Coleção "New Mathematical Library" volume 15 - 202 páginas.

Aborda também números de Fibonacci, números de Catalán, funçōes geratrizes e partiçōes de um inteiro.
[2] "Lições de Análise Combinatória" - Rio Nogueira - $2^{\text {a }}$ Edição - Editora Fundo de Cultura - Rio de Janeiro - 1972 - 158 páginas.

Contém cerca de 100 exercícios resolvidos e aborda também funçōes geratrizes.
[3] "Lições de Análise Combinatória" - F. A. Lacaz Netto - $4^{a}$ Edição - Livraria Nobel - São Paulo - 1956 - 158 páginas.

Contém 180 problemas, em sua maioria resolvidos.
[4] "Triângulo de Pascal" - V. A. Uspenski - Tradução para o espanhol de L. B. Ermolaev - Editora Mir - Moscou - 1978 - 38 páginas.

[5] "i de Cuantas Formas?" - N. Vilenkin -
Tradução para o espanhol de Juan Jose Tolosa - Editora Mir - Moscou - 1972 - 219 páginas. Um curso sob a forma de problemas, contém 439 problemas, todos resolvidos ou com solução indicada. Aborda também relações de recorrência.

Os livros a seguir abordam principalmente lópicos um pouco mais avançados.
[6] "Introduction to Combinatorics" - Gerald Berman e K. D. Fryer - Academic Press - Londres - 1972 - 300 páginas.

Aborda Permutações e Combinações, Princípio da Inclusão-Exclusão, Relações de recorrência, Funções Geratrizes, Princípio de Dirichlet, Pavimentações do Plano, Polinômios Cromáticos, o Problema das Quatro Cores, o Lema de Sperner, Mapas na esfera, Teorema de Euler, Configurações Combinatórias, Números de Stirling, Números de Fibonacci, Quadrados Latinos e Partições de Inteiros.
[7] "Introduction to Combinatorial Mathematics" - C. L. Liu - McGraw Hill - Nova Iorque - 1968 - 393 páginas.

Aborda Permutações e Combinações, Funções Geratrizes, Relações de Recorrência, Partições de Inteiros, Princípio da Inclusão-Exclusão, Permutações com Posições Restritas, Polinômios de Torres, Teoria da Contagem de Polya, Grafos, Circuitos Eulerianos e Hamiltonianos, Números Cromáticos, Configurações Combinatórias, Redes, Programação Linear, Programação Dinâmica e Designações.
[8] "Applied Cominatorics" - Alan Tucker - John Wiley and Sons - $2^{\text {a }}$ Edição - Nova Iorque 1984 - 447 páginas.

Aborda Grafos, Circuitos Eulerianos e Hamiltonianos, Colorações, Árvores, Redes, Permutações e Combinações, Funções Geratrizes, Relações de Recorrência, Princípio da Inclusão-Exclusão, Polinômios de Torres, Permutações com Posições Restritas, Teoria da

Contagem de Polya, Modelagem Combinatória em Teoria da Computação e Jogos com Grafos.
[9] "Basic Techniques of Combinatorial Theory" - Daniel I. A. Cohen - John Wiley and Sons - Nova Iorque - 1978 - 297 páginas.

Aborda Permutações e Combinações, Funções Geratrizes, Números de Stirling e de Catalán, Princípio de Dirichlet, Teorema de Ramsey, Princípio da Inclusão- Exclusão, Teoria da Contagem de Polya e Grafos.
[10] "Elementary Combinatorial Analysis" - Martin Eisen - Gordon and Breach - Nova Iorque - 1969 - 233 páginas.

Aborda Permutações e Combinações, Binómio de Newton e Polinômio de Leibniz, Funçōes Geratrizes, Princípio da Inclusão-Exclusão, Probabilidade, Função de Möebius e Teoria da Contagem de Polya.
[11] "A First Course in Combinatorial Mathematics" - Ian Anderson - Clarendon Press - Oxford - $2^{\text {a }}$ Edição - 1989 - 134 páginas.

Aborda Permutações e Combinações, Triângulo de Pascal, Binômio de Newton, Designações, Recorrência, Princípio da Inclusão-Exclusão, Polinômios de Torres, Configurações Combinatórias, Códigos Corretores de Erros e Empacotamento de Esferas.
[12] "Applied Combinatorics" - Fred S. Roberts - Prentice Hall - New Jersey - 1984 - 606 páginas.

Aborda História da Combinatória, Permutações e Combinações, Triângulo de Pascal, Probabilidade, Algoritmós, Grafos, Funçōes Geratrizes, Relações de Recorrência, Princípio da Inclusão-Exclusão, Teoria da Contagem de Polya, Princípio de Dirichlet, Teoria de Ramsey, Configurações Combinatórias, Códigos Corretores de Erros, Sistemas de Representantes Distintos e Problemas de Otimização.

[13] "Introductory Combinatorics" - Richard A. Brualdi - North Holland - Nova Iorque - 1977 - 374 páginas.

Aborda Princípio de Dirichlet, Teorema de Ramsey, Permutações e Combinações, Triângulo de Pascal, Princípio da Inclusão-Exclusão, Relações de Recorrência, Funções Geratrizes, Configurações Combinatórias, Grafos, Colorações e Problemas de Otimização.
[14] "Combinatorial Mathematics" - Herbert John Ryser - The Mathematical Association of America - The Carus Mathematical Monographs volume 14 - 1965 - 154 páginas.

Aborda o Principio da Inclusão-Exclusão, Permutações Caóticas, Permanentes, Relaçōes de Recorrência, o Problema de Lucas, Teorema de Ramsey, Partições de Inteiros, Configurações Combinatórias, Matrizes de zeros e uns.
[15] "Discrete Mathematics: Applied Combinatorics and Graph Theory" - Michael Townsend - The Benjamin Cummings Publishing Co. Inc. - Califórnia - 1987 - 387 páginas.

Aborda Indução, Combinações e Permutações, Funçōes Geratrizes, Relações de Recorrência, Princípio da Inclusão-Exclusão, Grafos, Circuitos Eulerianos e Hamiltonianos, Designações e Colorações.

# Probabilidade 

[16] "Fifty Challenging Problems in Probability with Solutions" - Frederick Mosteller - Addison - Wesley - Massachussets 1965 - 88 páginas.

Contém 56 problemas interessantíssimos de Probabilidade; todos resolvidos.

Os livros a seguir são excelentes textos para um curso de probabilidade em nivel de Graduação.

[17] "A First Course in Probability" - Sheldon Ross - Mac Millan Publishing Company, Inc - Nova Iorque - 1976 - 305 páginas.

Aborda Combinatória, Probabilidade, Variáveis Aleatórias Unidimensionais, Variáveis Aleatórias Multidimensionais, Esperanças e Teoremas Limites.
[18] "Modern Probability Theory and its Applications" - Emanuel Parzen - John Wiley and Sons e Toppan Printing Company LTD - Japão 1960 - 464 páginas.

Aborda Probabilidade, Variáveis Aleatórias Unidimensionais e Multidimensionais e Teoremas Limites.
[19] "Probabilidade: Aplicações à estatistica" - Paul L. Meyer - Tradução de Ruy Lourenço Filho - LTC - Rio de Janeiro - $2^{\text {a }}$ edição - 1983 - 426 páginas. Título original: "Introductory Probability and Statistical Applications".

Aborda Combinatória, Probabilidade, Variáveis Aleatórias Unidimensionais e Bidimensionais, Funções de Variáveis Aleatórias, Esperanças, Funçōes Geratrizes de Momentos, Confiabilidade, Teoremas Limites, Distribuiçōes Amostrais, Estimação e Testes.
[20] "Introdução à Teoria da Probabilidade" - Paul G. Hoel, Sidney C. Port, Charles J. Stone - Livraria Interciência - Rio de Janeiro - 1978 - Tradução de Fernando Yassov Chiyoshi - 269 páginas. Título original: "Introduction to Probability Theory".

Aborda Combinatória, Probabilidade, Variáveis Aleatórias Unidimensionais e Multidimensionais, Esperanças, Teoremas Limites, Funçōes Geratrizes de Momentos e Funçōes Características, Passeio Aleatório e Processo de Poisson.
[21] "Introdução à Teoria das Probabilidades e suas Aplicações" - William Feller - Edgard Blucher - São Paulo - 1976 - 236 páginas. Tradução de Flávio Wagner Rodrigues e Maria Elisa Fini.

Este é um clássico; um livro que influenciou várias gerações (a primeira edição é de 1950). O livro, no original, é em dois volumes com 17 capítulos no primeiro volume e 19 no segundo volume. A tradução para o Português contém ós 10 primeiros capítulos do primeiro volume.

Aborda Combinatória, Probabilidade, Passeio Aleatório, Distribuições Discretas Univariadas, Distribuição Normal, Esperanças e Teoremas Limites.

# Apêndice 3 

Demonstração da desigualdade $\left(1-\frac{1}{N}\right)^{n} \geq 1-\frac{2}{N}$

$$
\begin{aligned}
\left(1-\frac{1}{N}\right)^{n} & =\left(1-\frac{1}{N}\right)^{n-1}\left(1-\frac{1}{N}\right) \\
& -\left(1-\frac{1}{N}\right)^{n-1}-\frac{1}{N}\left(1-\frac{1}{N}\right)^{n-1} \\
& \geq\left(1-\frac{1}{N}\right)^{n-1}-\frac{1}{N}
\end{aligned}
$$

Com o mesmo raciocínio aplicado agora a

$$
\left(1-\frac{1}{N}\right)^{n-1}
$$

temos

$$
\left(1-\frac{1}{N}\right)^{n-1} \geq\left(1-\frac{1}{N}\right)^{n-2}-\frac{1}{N}
$$

e portanto

$$
\left(1-\frac{1}{N}\right)^{n} \geq\left(1-\frac{1}{N}\right)^{n-2}-\frac{2}{N}
$$

Continuando temos

$$
\left(1-\frac{1}{N}\right)^{n} \geq\left(1-\frac{1}{N}\right)^{n-3}-\frac{3}{N}
$$

e finalmente

$$
\left(1-\frac{1}{N}\right)^{n} \geq\left(1-\frac{1}{N}\right)^{n-n}-\frac{n}{N}=1-\frac{n}{N}
$$

o que prova a desigualdade.

This document was created with Win2PDF available at http://www.win2pdf.com. The unregistered version of Win2PDF is for evaluation or non-commercial use only. This page will not be added after purchasing Win2PDF.

