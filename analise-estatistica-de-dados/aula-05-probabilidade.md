---
title: Análise Estatística de Dados - Aula 05
author: Marco Vídero
description: Notas de aula
---

# Aula 05 - Probabilidade

## Probabilidade

### Conceitos básicos

#### Experimentos aleatórios

**Experimentos aleatórios**: São aqueles em que o processo de experimentação está sujeito a incertezas, logo, não é possível controlar todas as circunstâncias relevantes e, portanto, não é possível prever com exatidão os resultados individuais.

Características de um experimento aleatório: a\) Poderá ser repetido um grande número de vezes sob as mesmas condições iniciais; b\) Não podemos afirmar que um resultado particular ocorrerá, porém, podemos descrever o conjunto de todos os resultados possíveis do experimento; c\) Um experimento repetido um grande número de vezes, surgirá uma regularidade nos resultados - regularidade estatística, tornando possível construir um modelo matemático preciso com o qual se analisará o experimento.

A **Teoria da Probabilidade** é utilizada para descrever matematicamente experimentos cujos resultados não podem ser completamente pré-determinados, ou seja, visa definir um modelo matemático que seja adequado à descrição e interpretação de fenômenos aleatórios.

**Modelo probabilístico** é definido por: a\) Um espaço amostral $\(\Omega\)$; b\) Uma probabilidade, $P\(.\)$, para cada ponto amostral.

**Espaço amostral** $\(\Omega\)$: conjunto de todos os resultados possíveis de um experimento aleatório. Exemplos de experimentos aleatórios e seus respectivos espaços amostrais:

> **E1**: Jogar uma moeda e observar a face superior. **$\Omega = {Cara; Coroa}$** **E2**: Jogar um dado e observar a face superior. **$\Omega = {1, 2, 3, 4, 5, 6}$**

**Evento**: Qualquer subconjunto de um espaço amostral. Representado pelas letras latinas maiúsculas $A, B, C, \cdots$ Um resultado é um ponto amostral.

> Experimento: **jogar um dado.** Espaço amostral: **${1,2,3,4,5,6}$** Evento $\Rightarrow$ a face é par: **${2,4,6}$** Ponto amostral: um resultado **${2}$**

#### Operações com eventos

Ao realizar um experimento aleatório diz-se que o evento A ocorreu se o resultado observado for um elemento do subconjunto A. Dados dois eventos A e B de um mesmo espaço amostral:

* $A \cap B$ é o evento em que A e B ocorrem simultaneamente;
* $A \cup B$ é o evento em que A ocorre ou B ocorre \(ou ambos ocorrem\);
* $A^c$ é o evento em que A não ocorre.

**Exemplo**: Jogar um dado e observar a face superior.

$\Omega = {1, 2, 3, 4, 5, 6}$

* Evento $B$: representa sair face par $\Rightarrow B = {2, 4, 6}$
* Evento $C$: representa sair uma face ímpar $\Rightarrow C = {1, 3, 5}$
* Evento $D$: representa sair uma face maior que 3 $\Rightarrow D = {4, 5, 6}$
* Evento $E$: representa sair face 1 $\Rightarrow E = {1}$
* Evento $B \cap D$: representa sair uma face par e maior que 3 $\Rightarrow {2, 4, 6} \cap {4, 5, 6} = {4, 6}$
* Evento $B \cap C$: representa sair uma face par e ímpar $\Rightarrow {2, 4, 6} \cap {1, 3, 5} = ; \emptyset$
* Evento $B \cup D$: representa sair uma face par ou maior que 3 $\Rightarrow {2, 4, 6} \cup {4, 5, 6} = {2, 4, 5, 6}$
* Evento $B \cup C$: representa sair uma face par ou ímpar $\Rightarrow {2, 4, 6} \cup {1, 3, 5} = {1, 2, 3, 4, 5, 6} = \Omega$
* Evento $B^c = C$
* Evento $C^c = B$

**Exemplos**

1. Suponha duas urnas contendo, cada uma, quatro bolas numeradas de 1 a 4. Considera-se o experimento que consiste, em retirar, ao acaso, uma bola de cada urna. Descreva o espaço amostral. Determine os seguintes eventos:

   > $\Omega = {\(1,1\),\(1,2\),\(1,3\),\(1,4\), \(2,1\),\(2,2\),\(2,3\),\(2,4\), \(3,1\),\(3,2\),\(3,3\),\(3,4\), \(4,1\),\(4,2\),\(4,3\),\(4,4\)}$

a. a soma do número de pontos é ímpar.

> $A = {\(1,2\),\(1,4\),\(2,1\),\(2,3\),\(3,2\),\(3,4\),\(4,1\),\(4,3\)}$

b. a bola extraída da primeira urna contém o número dois.

> $B = {\(2,1\),\(2,2\),\(2,3\),\(2,4\)}$

1. Sejam A, B e C três eventos quaisquer. Estabeleça uma expressão para os eventos abaixo:

   a. A e B ocorrem

   > $A \cap B$

b. A ou B ocorrem

> $A \cup B$

c. B ocorre, mas A não ocorre;

> $B \cap A^c$ ou $B \cap A^c$

d. A não ocorre; $A^c$

e. não ocorre A e não ocorre B;

f. A e B ocorrem, mas C não corre;

g. somente A ocorre, mas B e C não ocorrem.

**Questão 1**

Descrever o espaço amostral \($\Omega$\) e eventos associados a cada um dos experimentos a seguir: \(a\) E1: Lançar uma moeda três vezes, sucessivamente, e anotar a sequência de caras \(C\) e coroas \(K\). Evento A1: Sair pelo menos duas caras.

> $\Omega = {\(c,c,c\),\(c,c,k\),\(c,k,c\),\(c,k,k\), \(k,c,c\),\(k,c,k\),\(k,k,c\),\(k,k,k\)}$ $A1 = {\(c,c,c\),\(c,c,k\),\(c,k,c\),\(k,c,c\)}$

\(b\) E2: Lançar uma moeda e um dado, simultaneamente, e registrar os resultados. Evento A2: Obtenção de face impar no dado.

> $\Omega = {\(c,1\),\(c,2\),\(c,3\),\(c,4\),\(c,5\),\(c,6\), \(k,1\),\(k,2\),\(k,3\),\(k,4\),\(k,5\),\(k,6\)}$ $A2 = {\(c,1\),\(c,3\),\(c,5\),\(k,1\),\(k,3\),\(k,5\)}$

**Questão 2**

Dados $P\(A\) = \frac{1}{2}; P\(B\) = \frac{3}{8}; P\(A \cap B\) = \frac{1}{8}$, calcule: \(a\) $P\(A \cup B\)$

> $P\(A \cup B\) = P\(A\)+P\(B\)-P\(A \cap B\) = \frac{1}{2} + \frac{3}{8} - \frac{1}{8} = \frac{1}{2} + \frac{2}{8} = \frac{4+2}{8} = \frac{6}{8} = \frac{3}{4}$

\(b\) $P\(A^c \cap B^c\)$

> $P\(A^c \cap B^c\) = 1 - P\(A \cup B\) = 1 - \frac{3}{4} = \frac{4-3}{4} = \frac{1}{4}$

\(c\) $P\(A^c \cup B^c\)$

> $P\(A^c \cup B^c\) = 1 - P\(A \cap B\) = 1 - \left\( \frac{1}{2} - \frac{3}{8} \right\) = 1 - \frac{4-3}{8} = 1 - \frac{1}{8} = \frac{7}{8}$

\(d\) $P\(A \cap B^c\)$

> $P\(A \cap B^c\) = P\(A\) - P\(A \cap B\) = \frac{1}{2} - \frac{1}{8} = \frac{4-1}{8} = \frac{3}{8}$

**Questão 3 \(2h23m30s\)**

Uma associação de indústrias transformadoras de resinas plásticas é composta de 20 empresas que produzem sacos plásticos \(S\), 10 que produzem garrafas \(G\), 8 que produzem utensílios domésticos \(U\) e 2 que se encarregam de brinquedos \(B\). Ao escolhermos uma empresa ao acaso, achar a probabilidade de que:

> $S: n\(S\) = 20$ $G: n\(G\) = 10$ $U: n\(U\) = 8$ $B: n\(B\) = 2$ $\Omega: n\(\Omega\) = 40$

\(a\) seja uma indústria que produza sacos plásticos ou utensílios domésticos;

> $P\(S \cup U\) = P\(S\) + P\(U\) = \frac{20}{40} + \frac{8}{40} = \frac{28}{40} = \frac{14}{20} = \frac{7}{10} = 0,7 = 70\%$

\(b\) seja uma indústria produtora de sacos plásticos ou brinquedos;

> $P\(S \cup B\) = P\(S\) + P\(B\) = \frac{20}{40} + \frac{2}{40} = \frac{22}{40} = \frac{11}{20}$

\(c\) não seja uma indústria que produza garrafas.

> $P\(G^c\) = 1 - P\(G\) = 1 - \frac{10}{40} = 1 - \frac{1}{4} = \frac{3}{4}$

**Questão 4**

Um empreiteiro apresentou orçamentos separados para a execução da parte elétrica e da parte de encanamento de um edifício. Ele acha que a probabilidade de ganhar a concorrência da parte elétrica é de 1/2. Caso ele ganhe a parte elétrica, a probabilidade de ganhar a parte de encanamento é de 3/4; caso contrário, essa probabilidade é de 1/3. Qual a probabilidade de ele:

> $A = Elétrica$ $B = Encanamento$ $P\(A\) = \frac{1}{2}$ $P\(B\|A\) = \frac{3}{4}$ $P\(B\|A^c\) = \frac{1}{3}$

\(a\) ganhar os dois contratos;

> $P\(A \cap B\) = P\(A\) \times P\(B\)$

\(b\) ganhar apenas um contrato.

> $P\(A \cap B^c\) + P\(A^c \cap B\)$

