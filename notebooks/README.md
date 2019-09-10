
## **Exercício 1**

$~$

**Distribuição:**

|   X/Y   |  Y=0 |  Y=1  | Marg. X |
|:-------:|:----:|:-----:|:-------:|
|   X=0   |  1/6 |  3/8  |  13/24  |
|   X=1   |  1/8 |  1/3  |  11/24  |
| Marg. Y | 7/24 | 17/24 |    1    |

$~$

**a)** $P(X)$ e $P(Y)$

**Resposta:**

 - $P(X=x) = \{\frac{13}{24}, \frac{11}{24}\}$

 - $P(Y=y) = \{\frac{7}{24}, \frac{17}{24}\}$

$~$
$~$

**b)** $P(X=0|Y=0)$

$\frac{P({X=0} \bigcap {Y=0})}{P(Y=0)} = \frac{1}{6}\times\frac{24}{7} = \frac{24}{42} = \frac{4}{7}$

$\frac{P({X=1} \bigcap {Y=0})}{P(Y=0)} = \frac{1}{8}\times\frac{24}{7} = \frac{24}{56} = \frac{3}{7}$

**Resposta:**

 - $P(X=0|Y=0) = \frac{4}{7}$

$~$
$~$

**c)** $E[X]$ e $E[Y]$

$E[X] = \sum_kx_kP(x_k)$

$E[X] = 0 \times \frac{13}{24} + 1 \times \frac{11}{24}$

$E[Y] = 0 \times \frac{7}{24} + 1 \times \frac{17}{24}$


**Resposta:**

 - $E[X] = \frac{11}{24}$
 
 - $E[Y] = \frac{17}{24}$

$~$
$~$

**d)** São independentes? Por quê?

Resposta:

X e Y NÃO são independentes, pois a probabilidade do evento Y não afeta X, de acordo com a formulação:

$P(X|Y) = P(X)P(Y)$

Verificamos:

$P(X=x|Y=0) = P(X=x)P(Y=0)$

Por fim temos:

$P(X=0|Y=0) = P(X=0)P(Y=0) => \frac{4}{7} = \frac{13}{24}\times\frac{7}{24} => \frac{4}{7} \neq \frac{91}{576}$

$P(X=1|Y=0) = P(X=1)P(Y=0) => \frac{3}{7} = \frac{11}{24}\times\frac{7}{24} => \frac{3}{7} \neq \frac{77}{576}$

$~$
$~$

---

## **Exercício 2**

$~$

**Distribuição:**

|   X/Y   | Y=0 | Y=1 | Marg. X |
|:-------:|:---:|:---:|:-------:|
|   X=0   |  0  | 1/4 |   1/4   |
|   X=1   | 3/8 | 3/8 |   3/4   |
| Marg. Y | 3/8 | 5/8 |    1    |

$~$

**a)** $H(X), H(Y), H(X,Y)$

Sendo: $H(X) = -\Sigma_x p(x)log_2[p(x)]$

$H(X) = H(\frac{1}{4}, \frac{3}{4})$

$H(X) = -((\frac{1}{4} \times log_2[\frac{1}{4}]) + (\frac{3}{4} \times log_2[\frac{3}{4}]))$

$H(X) = -((\frac{1}{4} \times -2) + (\frac{3}{4} (log_2[3]-2)))$

$H(X) = -((-\frac{1}{2}) + (\frac{3}{4} (log_2[3]-2)))$

$H(X) = 0.8112$

---

$H(Y) = H(\frac{3}{8}, \frac{5}{8})$

$H(Y) = -((\frac{3}{8} \times log_2[\frac{3}{8}]) + (\frac{5}{8} \times log_2[\frac{5}{8}]))$

$H(Y) = -((\frac{3}{8} (log_2(3)-3)) + (\frac{5}{8} (log_2(5)-3)))$

$H(Y) = 0.9544$

---

Calculando $H(X, Y)$

Sendo: $H(X, Y) = -\Sigma_x\Sigma_y p(x, y) log_2[p(x, y)]$

$H(X, Y) = -((\frac{1}{4} log_2(\frac{1}{4}))+(\frac{3}{8} log_2(\frac{3}{8}))+(\frac{3}{8} log_2(\frac{3}{8})))$

$H(X, Y) = 1.5612$

---

**Resposta:**

$H(X) = 0.8112$

$H(Y) = 0.9544$

$H(X, Y) = 1.5612$

$~$

**b)** $H(X|Y)$ e $H(Y|X)$



$~$

**c)** $I(X, Y)$



```python

```
