# Lista de exercícios 3

**Conteúdo:**
- Capítulo 4 (Números Binomiais, Triângulo de Pascal, Binômio de Newton, Polinômio de Leibniz)
- Capítulo 5 (Probabilidade, Probabilidades Condicionais, Distribuição Binomial)

---

# Números Binomiais e Triângulo de Pascal

## Parte 1 – Identidades e Relação de Stifel

1. Prove, fazendo as contas, que
   $$\binom{n+2}{p+2}=\binom{n}{p}+2\binom{n}{p+1}+\binom{n}{p+2}$$
   supondo $n$ um real qualquer e $p$ inteiro não-negativo. *(Seção 4.1, Exercício 3)*

2. Prove, usando um argumento combinatório, que $C_{n}^{p}=C_{n}^{n-p}$. *(Seção 4.1, Exercício 5)*

---

## Parte 2 – Teoremas do Triângulo (Linhas, Colunas e Diagonais)

3. Calcule o valor da soma:
   $$S=50 \cdot 51+51 \cdot 52+\cdots+100 \cdot 101$$
   *(Seção 4.1, Exercício 17)*

---

## Parte 3 – Equações envolvendo Binomiais

4. Resolva a equação $C_{41}^{p}=C_{41}^{2 p-1}$. *(Seção 4.1, Exercício 31)*

5. Resolva a equação $C_{15-p}^{2 p}=C_{15-p}^{9-p}$. *(Seção 4.1, Exercício 32)*

6. Determine $p$ para que $C_{10}^{p}$ seja máximo. *(Seção 4.1, Exercício 29)*

---

## Parte 4 – Binômio de Newton

7. Determine o termo independente de $x$ no desenvolvimento de:
   $$\left(x^{2}+\frac{1}{x^{3}}\right)^{10}$$
   *(Seção 4.2, Exercício 3)*

8. Determine o coeficiente de $x^{n}$ no desenvolvimento de:
   $$(1-x)^{2}(1+x)^{n}$$
   *(Seção 4.2, Exercício 6)*

9. Para que valores de $n$ o desenvolvimento de:
   $$\left(2 x^{2}-\frac{1}{x^{3}}\right)^{n}$$
   possui um termo independente de $x$? *(Seção 4.2, Exercício 7)*

10. Calcule a soma dos coeficientes dos termos de ordem par do desenvolvimento de $\left(2 x^{2}-3 y\right)^{n}$. *(Seção 4.2, Exercício 10)*

---

## Parte 5 – Polinômio de Leibniz

11. Determine o coeficiente de $x^{17}$ no desenvolvimento de:
    $$\left(1+x^{5}+x^{7}\right)^{20}$$
    *(Seção 4.3, Exercício 1)*

12. Determine a soma dos coeficientes do desenvolvimento de:
    $$\left(x^{3}-3 x+1\right)^{1822}$$
    *(Seção 4.3, Exercício 2)*

13. Quantos termos possui o desenvolvimento de:
    $$\left(x_{1}+x_{2}+x_{3}+x_{4}\right)^{20}?$$
    *(Seção 4.3, Exercício 3)*

---

# Probabilidade

## Parte 1 – Espaço Amostral e Probabilidades de Laplace

14. Uma caixa contém 20 peças em boas condições e 15 em más condições. Uma amostra de 10 peças é extraída. Calcular a probabilidade de que ao menos uma peça na amostra seja defeituosa. *(Seção 5.3, Exercício 1)*

15. Colocam-se aleatoriamente $b$ bolas em $b$ urnas. Calcular a probabilidade de que exatamente uma urna seja deixada desocupada. *(Seção 5.3, Exercício 5)*

16. Dez pessoas são separadas em dois grupos de 5 pessoas cada um. Qual é a probabilidade de que duas pessoas determinadas $A$ e $B$ façam parte do mesmo grupo? *(Seção 5.3, Exercício 6)*

17. 5 homens e 5 mulheres compram 10 cadeiras consecutivas na mesma fila de um teatro. Supondo que se sentaram aleatoriamente nas 10 cadeiras, calcular:
    a) A probabilidade de que homens e mulheres se sentem em cadeiras alternadas;
    b) A probabilidade de que as mulheres se sentem juntas.
    *(Seção 5.3, Exercício 7)*

18. Há 8 carros estacionados em 12 vagas em fila.
    a) Qual é a probabilidade das vagas vazias serem consecutivas?
    b) Qual é a probabilidade de não haver duas vagas vazias consecutivas?
    *(Seção 5.3, Exercício 21)*

19. Colocam-se ao acaso $n$ botões em um tabuleiro $n \times n$, não sendo permitido haver dois botões em uma mesma casa. Qual é a probabilidade de não haver dois botões nem na mesma linha nem na mesma coluna? *(Seção 5.3, Exercício 25)*

20. Um carro estaciona entre $n$ outros em fila e não numa ponta. Quando o dono retorna ainda estão estacionados $m$ dos $n$ carros. Qual é a probabilidade das duas vagas adjacentes ao seu carro estarem vazias? *(Seção 5.3, Exercício 29)*

21. Se $n$ homens, entre os quais João e Pedro, são postos ao acaso em uma fila, qual é a probabilidade de haver exatamente $m$ pessoas entre João e Pedro? *(Seção 5.3, Exercício 30)*

22. Doze pessoas são divididas em três grupos de 4. Qual é a probabilidade de duas determinadas pessoas ficarem no mesmo grupo? *(Seção 5.3, Exercício 32)*

23. $P(A)=\frac{1}{2}, P(B)=\frac{1}{3}, P(C)=\frac{1}{4}, P(A \cap B)=\frac{1}{5}, P(A \cap C)=\frac{1}{6}, P(B \cap C)=0$. Calcule:
    a) $P(A \cup B \cup C)$;
    b) $P[A-(B \cup C)]$;
    c) $P[A \cap (B \cup C)]$;
    d) $P[(A \cap B) \cup C]$.
    *(Seção 5.3, Exercício 36)*

---

## Parte 2 – Probabilidades Condicionais

24. Uma moeda é jogada 6 vezes. Sabendo-se que no primeiro lançamento deu coroa, calcular a probabilidade condicional de que o número de caras nos seis lançamentos supere o número de coroas. *(Seção 5.4, Exercício 2)*

25. Duas máquinas $A$ e $B$ produzem 3000 peças em um dia. A máquina $A$ produz 1000 peças, das quais $3\%$ são defeituosas. A máquina $B$ produz as restantes 2000, das quais $1\%$ são defeituosas. Da produção total de um dia uma peça é escolhida ao acaso e, examinando-a, constata-se que é defeituosa. Qual é a probabilidade de que a peça tenha sido produzida pela máquina $A$? *(Seção 5.4, Exercício 5)*

26. Três urnas I, II e III contêm respectivamente 1 bola branca e 2 pretas, 2 brancas e 1 preta e 3 brancas e 2 pretas. Uma urna é escolhida ao acaso e dela é retirada uma bola, que é branca. Qual é a probabilidade condicional de que a urna escolhida foi a II? *(Seção 5.4, Exercício 6)*

27. Um estudante resolve um teste com questões do tipo verdadeiro-falso. Ele sabe dar a solução correta para $40\%$ das questões. Quando ele responde uma questão cuja solução conhece, dá a resposta correta, e nos outros casos decide na cara ou coroa. Se uma questão foi respondida corretamente, qual é a probabilidade de que ele sabia a resposta? *(Seção 5.4, Exercício 7)*

28. (Problema dos Encontros de Montmort) Forma-se, ao acaso, uma permutação simples dos números $1,2, \ldots, n$. Caso o número $i$ ocupe o $i$-ésimo lugar, dizemos que há um encontro na posição $i$. Calcule a probabilidade de na permutação formada:
    a) haver exatamente $k$ encontros $(k \leq n)$;
    b) haver um encontro na posição $i$ dado que há exatamente $k$ encontros na permutação;
    c) haver um encontro na posição $i$ e não haver um encontro na posição $j$ ($i \neq j$);
    d) haver um encontro na posição $i$ dado que não há encontro na posição $j$ ($i \neq j$).
    *(Seção 5.4, Exercício 13)*

29. Uma pessoa com um molho de $n$ chaves tenta abrir uma porta. Apenas uma das chaves consegue abrir a porta. Qual é a probabilidade dela só conseguir abrir a porta na $k$-ésima tentativa:
    a) supondo que após cada tentativa mal sucedida ela descarta a chave usada;
    b) supondo que ela não faz isso.
    *(Seção 5.4, Exercício 15)*

30. Um exame de laboratório tem eficiência de $95\%$ para detectar uma doença quando essa doença existe de fato. Entretanto o teste aponta um resultado "falso positivo" para $1\%$ das pessoas sadias testadas. Se $0,5\%$ da população tem a doença, qual é a probabilidade de uma pessoa ter a doença dado que o seu exame foi positivo? *(Seção 5.4, Exercício 20)*

31. $A$ lança uma moeda não-viciada $n+1$ vezes e $B$ lança a mesma moeda $n$ vezes. Qual é a probabilidade de $A$ obter mais caras que $B$? *(Seção 5.4, Exercício 23)*

32. Uma urna contém 3 bolas vermelhas e 7 bolas brancas. $A$ e $B$ sacam alternadamente, sem reposição, bolas dessa urna até que uma bola vermelha seja retirada. $A$ saca a $1^a$ bola. Qual é a probabilidade de $A$ sacar a bola vermelha? *(Seção 5.4, Exercício 26)*

33. Em uma cidade, as pessoas falam a verdade com probabilidade $\frac{1}{3}$. Suponha que $A$ faz uma afirmação e que $D$ diz que $C$ diz que $B$ diz que $A$ falou a verdade. Qual é a probabilidade de $A$ ter falado a verdade? *(Seção 5.4, Exercício 28)*

34. $2^n$ jogadores de igual habilidade disputam um torneio. Eles são divididos em grupos de 2, ao acaso, e jogadores de um mesmo grupo jogam entre si. Os perdedores são eliminados e os vencedores são divididos novamente em grupos de 2 e assim por diante até restar apenas um jogador que é proclamado campeão. Qual é a probabilidade de dois jogadores $A$ e $B$ se enfrentarem durante o torneio? Qual é a probabilidade do jogador $A$ jogar exatamente $k$ partidas? *(Seção 5.4, Exercício 30)*

35. Em um torneio como o descrito no exercício anterior, os jogadores têm habilidades diferentes e não há surpresas nos resultados (se $A$ é melhor que $B$, $A$ vence $B$). Qual é a probabilidade do segundo melhor jogador ser vice-campeão do torneio? *(Seção 5.4, Exercício 31)*

36. Um prisioneiro possui 50 bolas brancas, 50 bolas pretas e duas urnas iguais. O prisioneiro deve colocar do modo que preferir as bolas nas duas urnas (nenhuma das urnas pode ficar vazia). As urnas serão embaralhadas e o prisioneiro deverá, de olhos fechados, escolher uma urna e, nesta urna, uma bola. Se a bola for branca ele será libertado e, caso contrário, condenado. Como deve proceder o prisioneiro para maximizar a probabilidade de ser libertado? *(Seção 5.4, Exercício 36)*

---

## Parte 3 – Distribuição Binomial

37. Sacam-se, com reposição, 4 bolas de uma urna que contém 7 bolas brancas e 3 bolas pretas. Qual a probabilidade de serem sacadas 2 bolas de cada cor? Qual seria a resposta no caso sem reposição? *(Seção 5.5, Exercício 1)*

38. Lança-se um dado não viciado até a obtenção do terceiro 6. Seja $X$ o número do lançamento em que isso ocorre. Calcule:
    a) $P(X=10)$;
    b) $P(X>10)$;
    c) $P(X<10)$.
    *(Seção 5.5, Exercício 2)*

39. Motores de avião funcionam independentemente e cada motor tem uma probabilidade $p$ de falhar durante um voo. Um avião voa com segurança se a maioria de seus motores funciona. Para que valores de $p$ um avião com 3 motores é preferível a um avião com 5 motores? *(Seção 5.5, Exercício 5)*

40. Suponha que uma característica (como a cor dos olhos, por exemplo) dependa de um par de genes. Representemos por $A$ um gene dominante e por $a$ um gene recessivo. Assim um indivíduo com genes $AA$ é dominante puro, um com genes $aa$ é um recessivo puro e um com genes $Aa$ é um híbrido. Dominantes puros e híbridos são semelhantes em relação à característica. Filhos recebem um gene do pai e um da mãe. Suponha que pai e mãe sejam híbridos e tenham 4 filhos.
    a) Qual é a probabilidade do primeiro filho ser um recessivo puro?
    b) Qual é a probabilidade de exatamente um dos 4 filhos ser um recessivo puro?
    *(Seção 5.5, Exercício 6)*

41. (O problema das caixas de fósforos de Banach) Um matemático sai de casa todos os dias com duas caixas de fósforos, cada uma com $n$ palitos. Toda vez que ele quer acender um cigarro, ele pega (ao acaso) uma das caixas e retira daí um palito. O matemático é meio distraído, de modo que quando ele retira o último palito de uma caixa, ele não percebe que a caixa fica vazia. Como ele fuma muito, em certa hora ele pega uma caixa e constata que ela está vazia. Qual é a probabilidade de nesse momento a outra caixa conter exatamente $k$ ($0 \leq k \leq n$) palitos? *(Seção 5.5, Exercício 7)*

42. Lança-se repetidamente um par de dados não tendenciosos. Qual é a probabilidade de obtermos duas somas iguais a 7 antes de obtermos três somas iguais a 3? *(Seção 5.5, Exercício 8)*
