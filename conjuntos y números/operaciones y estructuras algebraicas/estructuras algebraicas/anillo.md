
Sea $A$ un conjunto y sean $+$ y $·$ dos [[operación interna|operaciones internas]] definidas en $A$.

$(A,+,·)$ es un anillo si cumple lo siguiente:
1) $(A,+)$ es un [[grupo]] conmutativo
2) La operación $·$ es [[asociación|asociativa]]
3) La operación · es [[distribución|distributiva]] respecto de la operación $+$

Si, además, $·$ es [[conmutación|conmutativa]], se dice que $(A,+,·)$ es un **anillo conmutativo**.

Si $(A,+,·)$ es un anillo con [[operación interna#elemento neutro|elemento neutro]] para el producto, siendo este distinto del elemento neutro de la suma, se dice de $(A,+,·)$ que es un **anillo unitario**.
## propiedades del anillo

Siendo $(A,+,·)$ un anillo

1. Para todo $a\in A$, $$a·0=0·a=0$$Decimos que 0 es *absorbente* para el producto.
2. Para todo $a,b\in A$, $$(-a)b = a(-b) = -(ab)$$ $$(-a)(-b) = ab$$
3. Si el anillo $A$ es conmutativo:
	1. $(a+b)^2=a^2+b^2+2ab$
	2. $(a+b)(a-b)=a^2-b^2$
	3. $(a+b)^n=(_0^n)a^n+(_1^n)a^{n-1}b+...+(_{n-1}n)ab^{n-1}+(_n^n)b^n = \sum_{p=0}^n (_p^n)a^{n-p}b^p$ para todo $n\in \mathbb{N}^*$ (binomio de Newton) #nosentiende 
## divisor de cero

En un anillo $(A,+,·)$, el elemento $a\in A, a \ne 0$ es **divisor de cero** si existe $b\in A. b\ne 0$
tal que $ab=0$

Un elemento invertible no puede ser divisor de cero.

Un anillo sin divisores de 0 es un **anillo íntegro**.

(Ojo, que si el anillo no es [[conmutación|conmutativo]] para $·$, puede tener divisores de cero tanto "por la izquierda" como "por la derecha", porque $ab\ne ba$)
## anillo ordenado

Se dice que $(A,+,·,\leq)$ es un anillo ordenado si se cumple lo siguiente:

1) $$\forall a,b,c\in A,\ \ a\leq b \implies a+c\leq b+c$$
2) $$\forall a,b\in A,\ \ 0\leq a\land 0\leq b \implies 0\leq ab$$
Si la relación de orden es [[relación de orden#relación de orden total|total]], decimos que $A$ es un **anillo totalmente ordenado**.
Si además el anillo es un [[cuerpo]] hablaremos de **cuerpo ordenado**.
### propiedades del anillo ordenado

Todo anillo ordenado $(A,+,·,\leq)$ es un grupo ordenado, $(A,+,\leq)$, por lo que en un anillo ordenado se satisfacen todas las [[grupo#propiedades del grupo ordenado|propiedades]] del grupo ordenado.

Si el anillo es **totalmente ordenado**, se satisfacen estas propiedades:
1. $a\leq b\iff b-a\in A_+$
2. $a\leq b \land a'\leq b' \implies a+a'\leq b+b'$
3. $a\leq b \implies -b\leq -a$
4. $a\leq b \land 0\leq c \implies ac\leq bc$
5. $a\leq b \land c\leq 0 \implies bc\leq ac$
6. $\forall a\in A,\ \ a^2\geq 0$ 
7. Si $A$ es un **anillo unitario** entonces $0< 1$
8. $\forall a\in A, \ \ |a|\geq0$, y $|a|=0\iff a=0$
9. $\forall a,b \in A, \ \ |ab|=|a||b|$
10. $\forall a,b\in A, \ \ |a+b|\leq|a|+|b|$

### valor absoluto

En un anillo **totalmente ordenado** se define el valor absoluto de $a\in A$ mediante$$|a|=\begin{cases} 0\leq a \implies a\\a\leq0\implies -a\end{cases}$$