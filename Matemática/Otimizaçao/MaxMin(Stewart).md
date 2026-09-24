# Apresentação:

Expliração extraída do livro do _Stewart_ (Cálculo, Vol.1 & Vol.2), no capítulo de valores Máximos e Mínimos. Não é exatamente o melhor conteúdo sobre otimização convexa, mas é o mais acessível. O objetivo aqui é estruturar uma linha de raciocínio para se lidar com problemas de otimização.

# Valores Máximo e Mínimo (Uma Variável):

O caso de uma variável é simplesmente um caso particular $n$-dimensional, todavia, a título de introdução e para não confundimento do conteúdo, não vamos dar um passo maior do que a perna e começar de leve, como os livros didáticos fazem.

## 1. Definição: Min Max Global(Absoluto)

Seja $c$ um número no domínio $D$ de uma função $f$. Então $f(c)$ é o

* Valor **Máximo Absoluto** de $f$ em $D$ se $f(c) \ge f(x),\ \forall{x \in D}$
* Vaçpr **Mínimo Absoluto** de $f$ em $D$ se $f(c) \le f(x),\ \forall{x \in D}$

## 2.  Definição: Min Max Local

* valor **Máximo Local** de $f$ se $f(c) \ge f(x)$ quando $x$ está próximo de $c$.
* Valor **Mínimo Local** de $f$ se $f(c) \le f(x)$ quando $x$ está próximo $c$.

## 3. o Teorema de Valor Extremo:

Se $f$ for contínua em um intervalo fechado [a,b], então $f$ assume um valor **máximo absoluto** $f(c)$ e um valor **mínimo absoluto** $f(d)$ em certos números $c$ e $d$ em [a,b].

## 4. Teorema de Fermat:

Se $f$ tiver um máximo ou **mínimo local** em $c$ e se $f'(c)$ existir, então $f'(c)=0$. (Isso é garantido sobre pressuposição de convexidade de $f$, mas o livro não comenta nada sobre.)

## Definição: Valor (ou número) crítico

Um **número crítico** de uma função $f$ é um número $c$ no domínio de $f$ tal que $f'(c)=0$ ou $f'(c)$ não existe. Se $f$ tiver um máximo ou mínimo local em $c$, então $c$ é um número crítico de $f$.

## Método do Intervalo fechado (Regra de Fermat):

Para encontrar os valores máximo  e mínimos absolutos de uma função contínua $f$ em um intervalo fechado [a,b]:

1. Encontre os valores de $f$ nos **números críticos** de $f$ em (a,b);
2. Encontre os valores de $f$ nas extremidades do intervalo;
3. O maior valor entre as etapas $1$ e $2$ é o **valor máximo absoluto**, ao passo que o menor desses valores é o **valor mínimo absoluto**.


# Valores Máximo e Mínimo (para mais de uma variável):

Tratato a questão apra uma variável, vamos ver a questão para uma função $n$-dimensional.

## Definição: Máximo e Mínimo Local e Global:

Uma função de duas variáveis tem um **máximo local** em $(a,b)$ se $f(x,y)\le f(a,b)$ quando $(x,y)$ está próximo de $(a,b)$. (Isso significa que $f(x,y) \le f(a,b)$ para todos os pontos $(x,y)$ em alguma bola aberta com centro $(a,b)$). O número $f(a,b)$ é chamado **valor máximo local**. Se $f(x,y) \ge f(a,b)$ quando $(x,y)$ está próximo $(a,b)$, então $f$ tem um **mínimo local** em $(a,b)$ e $f(a,b)$ é um **valor mínimo local.**

Se as inequações definidas acima valerem $\forall{(x,y)}$ no domínio de $f$, então $f$ tem um **Máximo Absoluto (Global)** ou **Mínimo Absoluto (Global)** em $(a,b)$

## Teorema: Pontos Críticos

Se $f$ tem um máximo ou mínimo local em $(a,b)$ e as **derivadas parciais de primeira ordem** de $f$ existirem nesses pontos, então $f_x(a,b)=0$ e $f_y(a,b)=0$.

## Teste da Segunda Derivada:

Supoonha que as **segundas derivadas parciais** de $f$ sejam contínuas em umabola aberta com centro em $(a,b)$, e suponha que $f_x(a,b)=0$ assim como $f_y(a,b)=0$, (ou seja, $(a,b)$ é um ponto crítico de f). Seja,

$$D=D(a,b)=f_{xx}(a,b)f_{yy}(a,b)-[f_{xy}(a,b)]^2$$

1. Se $D \gt 0$ e $f_{xx}(a,b) \gt 0$, então $f(a,b) $é um **Mínimo local**;
2. Se $D \gt 0$ e $f_{xx}(a,b) \lt 0$, então $f(a,b) $é um **Máximo local**;
3. Se $D \lt 0$, então $f(a,b)$ **não** é o **mínimo nem máximo local**.

**Observações:**
* Se $D \lt 0$, o ponto $(a,b)$ é chamado de **ponto de sela** de $f$ e o gráfico $f$ cruza seu plano tangente em $(a,b)$.
* Se $D = 0$, não dá nenhuma informação: $(a,b)$ pode tanto ser um ponto de **máximo local** ou **mínimo local**, quanto pode ser um **ponto de sela** também.

$$\mathbf{D} = \left| \begin{array}{cc}
f_{xx} & f_{xy} \\
f_{yx} & f_{yy}
\end{array} \right| = f_{xx} f_{yy} - (f_{xy})^2
$$
