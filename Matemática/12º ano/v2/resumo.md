## Domínio

### Domínio de uma função composta $g∘f \begingroup\color{gray} = g(f(x)) \endgroup$

$D_{g∘f} = \{ x \isin \R : x \isin D_f \land f(x) \isin D_g \}$

### Função par e ímpar

* $f$ é **par** se $f(-x) = f(x), \forall x \in D_f$  
  (Simetria em relação ao eixo das ordenadas)
* $f$ é **ímpar** se $f(-x) = -f(x), \forall x \in D_f$  
  (Simetria em relação à origem do referencial)

## Casos notáveis

### Quadrado do binómio

$(a+b)^2 = a^2 + 2ab + b^2$  
$(a-b)^2 = a^2 - 2ab + b^2$

### Diferença de quadrados

$a^2 - b^2 = (a+b)(a-b)$

## ??

```
D    | d
     |_______
  r    q
```

$\frac{D}{d} = q + \frac{r}{d}$

## Transformações geométricas do gráfico de uma função

### Contrações e dilatações

$g(x) = a f(b x), \quad a,b > 0$

O gráfico de $g$ obtém-se do gráfico de $f$ por uma **dilatação vertical** de coeficiente $a$ e **contração horizontal** de coeficiente $b$.

$h(x) = a f(b x), \quad a,b < 0$

O gráfico de $g$ obtém-se do gráfico de $f$ por uma **contração vertical** de coeficiente $a$ e **dilatação horizontal** de coeficiente $b$.

> Transformações geométricas do gráfico de uma função: contrações e dilatações – #EstudoEmCasa 2020/2021  
> <https://estudoemcasa.dge.mec.pt/2020-2021/10o/matematica-a/25>

### Translações

$g(x) = f(x - \begingroup\color{red} c \endgroup) + \begingroup\color{blue} d \endgroup \quad \rightarrow \vec{v}(\begingroup\color{red} c \endgroup,\begingroup\color{blue} d \endgroup)$

O gráfico de $g$ obtém-se do gráfico de $f$ por uma translação de vetor $(\begingroup\color{red} c \endgroup,\begingroup\color{blue} d \endgroup)$.

$h(x) = f(x + \begingroup\color{red} c \endgroup) - \begingroup\color{blue} d \endgroup \quad \rightarrow \vec{w}(- \begingroup\color{red} c \endgroup, - \begingroup\color{blue} d \endgroup)$

O gráfico de $h$ obtém-se do gráfico de $f$ por uma translação de vetor $(- \begingroup\color{red} c \endgroup, - \begingroup\color{blue} d \endgroup)$.

> Transformações geométricas do gráfico de uma função: Translações – #EstudoEmCasa 2020/2021  
> <https://estudoemcasa.dge.mec.pt/2020-2021/10o/matematica-a/24>

## Continuidade

Uma função real de variável real diz-se contínua se for contínua em todos os pontos do seu domínio.
São exemplos de funções contínuas estudadas no atual Ensino Secundário as seguintes funções ou famílias de funções:

- Funções polinomiais
- Funções racionais (quociente de dois polinómios)
- Funções exponenciais da forma $f(x) = a^x \quad \text{com } a \isin \R^+ \, \backslash \{1\}$
- Funções logarítmicas da forma $f(x) = log_a x \quad \text{com } a \isin \R^+ \, \backslash \{1\}$
- Função seno
- Função cosseno
- Função tangente

> função contínua – infopédia  
> <https://www.infopedia.pt/apoio/artigos/$funcao-continua>

## Assíntotas

### Assíntotas verticais

Dado um referencial cartesiano e $f$ uma f.r.v.r, diz-se que a reta de equação $x=a$ ($a \isin \R$) é uma **assíntota vertical** ao gráfico de $f$ se pelo menos um dos limites laterais de f no ponto $a$ é infinito. $\lim_{x \to a^\plusmn} f(x) = \plusmn \infin$  
Diz-se que é unilateral se tal se verificar apenas num dos limites laterais e bilateral se se verificar nos dois.

### Assíntotas não verticais

Dado um referencial cartesiano e $f$ uma f.r.v.r., diz-se que a reta de equação $y=mx+b$ ($m,b \isin \R$) é uma **assíntota não vertical** ao gráfico de $f$ em:

* $+\infin \quad \text{se} \quad \lim_{x \to +\infin} [\begingroup\color{green} f(x) \endgroup - \begingroup\color{blue} (mx+b) \endgroup] = 0$
* $-\infin \quad \text{se} \quad \lim_{x \to -\infin} [\begingroup\color{green} f(x) \endgroup - \begingroup\color{blue} (mx+b) \endgroup] = 0$

Por outro lado, se a reta de equação $y=mx+b$ é uma assíntota não vertical ao gráfico de f em $+\infin$ ou $-\infin$, então:

* $m = \lim_{x \to \plusmn \infin} \frac{f(x)}{x}$
* $b = \lim_{x \to \plusmn \infin} [f(x) - mx]$

## Teorema de Bolzano-Cauchy

Dada uma f.r.v.r. $f$ contínua num intervalo $I = [a,b] , \ (a<b)$, para qualquer valor $k = \R$ do intervalo aberto de extremos $f(a)$ e $f(b)$, com $f(a) \neq f(b)$), existe $c = ]a,b[$ tal que $f(c) = k$

### Exemplo

$f(x) = x^3 + 2x^2 - 5$

**Objetivo:** Mostrar que a equação $f(x) = - \pi$ é possível (tem pelo menos uma solução) no intervalo $]-1,1[$

**⓪ Determinar o domínio da função**

$D_f = \R$

**① Justificar a continuidade da função no intervalo fechado $[a,b]$**

A função $f$ é contínua em $[-1,1]$ por se tratar de uma função polinomial.

**② Determinar as imagens dos extremos do intervalo $[a,b]$**

* $f(-1) = … = -2 \qquad (> - \pi)$
* $f(1) = … = -4 \qquad (< - \pi)$

$-4 < - \pi < -2$  
$f(1) < - \pi < f(-1)$

**③ Concluir invocando o Teorema de Bolzano-Cauchy**

Como $f$ é contínua em $[-1,1]$ e $f(1) < - \pi < f(-1)$, pelo Teorema de Bolzano-Cauchy, pode concluir-se que $\begingroup\color{teal} \exist c \isin \ ]-1,1[ \ : f(c) = - \pi \endgroup$. Logo, a equação $f(x) = - \pi$ é possível no intervalo $]-1,1[$.

## Corolário do Teorema de Bolzano-Cauchy

Se $f$ é uma função contínua em $[a,b]$ e $f(a) \times f(b) < 0$, ou seja, $f(a)$ e $f(b)$ têm sinais contrários, então a função $f$ tem pelo menos um zero (a equação $f(x) = 0$ é possível; tem pelo menos uma solução) em $]a,b[$.

### Exemplo 1

$f(x) = x^2 + x -1 - \sqrt{x+2}$

**Objetivo:** Mostrar que a $f$ tem pelo menos um zero no intervalo $]1,2[$

**⓪ Determinar o domínio da função**

$D_f = \{x \isin \R : x+2 \geqslant 0 \} = \{x \isin \R : x \geqslant -2 \} = [-2, + \infin[$

$[1,2] \subset [-2, + \infin[$

**① Justificar a continuidade da função no intervalo fechado $[a,b]$**

A função $f$ é contínua em $[1,2]$ por resultar de operações sucessivas entre funções contínuas ($f$ é a diferença entre duas funções contínuas, uma polinomial e uma potência de expoente racional de uma função polinomial).

**② Determinar as imagens dos extremos do intervalo $[a,b]$**

* $f(1) = … = 1 - \sqrt{3} \qquad (< 0)$
* $f(2) = … = 3 \qquad (> 0)$

$f(1) \times f(2) < 0$

**③ Concluir invocando o Corolário do Teorema de Bolzano-Cauchy**

Como $f$ é contínua em $[1,2]$ e $f(1) \times f(2) < 0$, pelo Corolário do Teorema de Bolzano-Cauchy, pode concluir-se que $\begingroup\color{teal} \exist c \isin \ ]1,2[ \ : f(c) = 0 \endgroup$, ou seja, $f$ tem pelo menos um zero em $]1,2[$.

### Exemplo 2

$f(x) = \cos x$  
$g(x) = x$

**Objetivo:** Mostrar que a equação $f(x) = g(x)$ é possível em $]0,\frac{\pi}{2}[$

Nestes casos, deve-se criar uma nova função.

$f(x) = g(x) \iff \cos x = x \iff \cos x - x = 0$

Seja $h(x) = \cos x - x$

Provar que $h(x) = 0$ é possível em $]0,\frac{\pi}{2}[$ é provar que $f(x) = g(x)$ é possível no mesmo intervalo.

**[...]**

Como $h$ é contínua em $[0,\frac{\pi}{2}]$ e $h(0) \times h(\frac{\pi}{2}) < 0$, pelo Corolário do Teorema de Bolzano-Cauchy, pode concluir-se que $\begingroup\color{teal} \exist c \isin \ ]0,\frac{\pi}{2}[ \ : h(c) = 0 \endgroup$. Logo, a equação $f(x) = g(x)$ é possível em $]0,\frac{\pi}{2}[$.

## Taxa média de variação

Geometricamente, representa o declive da reta secante ao gráfico de f que passa pelos pontos $A(a, f(a))$ e $B(b, f(b))$.

$$\text{t.m.v}_{[a,b]} = \frac{f(b) - f(a)}{b - a} = m_{AB}$$

## Taxa instantânea de variação ou derivada de uma função num ponto

$$f'(x_0) = \lim_{x \to x_0} \frac{f(x) - f(x_0)}{x - x_0}$$

$$\text{OU}$$

$$f'(x_0) = \lim_{h \to 0} \frac{f(x_0 + h) - f(x_0)}{h}$$

Se uma função admite derivada num ponto, então a função é diferenciável (ou derivável) nesse ponto.

Geometricamente, **a derivada de uma função num ponto representa o declive da reta tangente ao gráfico da função nesse ponto.**

## Segunda derivada de uma função no ponto

$$f''(x_0) = \lim_{x \to x_0} \frac{f'(x) - f'(x_0)}{x - x_0}$$

$$\text{OU}$$

$$f''(x_0) = \lim_{h \to 0} \frac{f'(x_0 + h) - f'(x_0)}{h}$$

## Derivada

### Derivada de uma função composta

$(f∘g)'(x) = f'(g(x)) \times g'(x)$

## Limites

### Limites notáveis

#### Antigo limite notável

$\lim_{x \to 0} \frac{\ln(x+1)}{x} \begingroup\color{red} = 1 \qquad \text{(Costumava ser um limite notável)} \endgroup$

**Como resolver:**

Mudança de variável: $y = \ln(x+1)$  
$y = \ln(x+1) \iff x+1 = e^y \iff x = e^y - 1$

Se $x \to 0, \ y \to 0$

$\lim_{y \to 0} \frac{y}{e^y - 1} = \frac{1}{\lim_{y \to 0} \frac{e^y -1}{y}} = \frac{1}{1} = 1$

## Trigonometria

* $\sin \alpha = \frac{\text{cateto oposto}}{\text{hipotenusa}}$
* $\cos \alpha = \frac{\text{cateto adjacente}}{\text{hipotenusa}}$
* $\tan \alpha = \frac{\text{cateto oposto}}{\text{cateto adjacente}}$

$\sin^2 \alpha + \cos^2 \alpha = 1 \qquad \text{(Fórmula fundamental da trigonometria)}$

$\tan \alpha = \frac{\sin \alpha}{\cos \alpha}$

### Tabela de valores

| $\alpha$ | $\sin$ | $\cos$ | $\tan$ |
| --- | --- | --- | --- |
| 0 | 0 | 1 | 0 |
| $\frac{\pi}{6}$ | $\frac{1}{2}$ | $\frac{\sqrt{3}}{2}$ | $\frac{\sqrt{3}}{3}$ |
| $\frac{\pi}{4}$ | $\frac{\sqrt{2}}{2}$ | $\frac{\sqrt{2}}{2}$ | 1 |
| $\frac{\pi}{3}$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{2}$ | $\sqrt{3}$ |

### Período

$\text{p.p.m.} = 2 \pi$

$\cos(bx) \longrightarrow P = \frac{2 \pi}{|b|}$

## Números complexos

* $i^1 = i$
* $i^2 = -1$
* $i^3 = -i$
* $i^4 = 1$
* $i^5 = i$  
  $…$

$i^{325} = i^{4 \times 81 + 1} = i^1 = i$
