
Se llama así al par formado por un conjunto y una [[relación de orden]] definida sobre el mismo.

Por ejemplo, $(\mathbb{R} , \leq)$ 
## elementos del conjunto ordenado
### conjunto acotado

Dados un conjunto ordenado $(U, \leq)$ y un subconjunto $A\subset U$
Decimos que $A$ está **acotado** si tiene cotas superiores e inferiores.
#### cotas superiores

Las cotas superiores del conjunto $A$ serían $$u\in U \ (\forall x\in A, x \leq u)$$
El elemento mayor de $A$ y todos los superiores en $U$
Si existe una cota superior de $A$, se dice que está *acotado superiormente*.
#### cotas inferiores

Las cotas inferiores del conjunto $A$ serían $$d\in U \ (\forall x\in A, d \leq x)$$
El elemento menor de $A$ y todos los inferiores en $U$
Si existe una cota inferior de $A$, se dice que está *acotado inferiormente*.
### máximo

$$M\in A \ (\forall x\in A \ x\leq M)$$
Es decir, el elemento mayor de $A$.
### mínimo 

$$m\in A\ (\forall x\in A\ m\leq x)$$
Es decir, el elemento menor de $A$.
### supremo

El supremo de $A$ es la [[#cotas superiores|cota superior]] $S\in U$ tal que $S\leq u$ para toda cota superior $u$ de $A$.
Se denota $sup(A)$.

En un conjunto ordenado $(U,\leq)$ se tiene que:
- el supremo de $A$ es el mínimo de las cotas superiores.
- si un conjunto tiene [[#máximo]], también tiene supremo, y $sup(A)=máx(A)$.
### ínfimo

El ínfimo de $A$ es la [[#cotas inferiores|cota inferior]] $i\in U$ tal que $d\leq i$ para toda cota inferior $d$ de $A$.
Se denota $ínf(A)$.

En un conjunto ordenado $(U,\leq)$ se tiene que:
- el supremo de $A$ es el máximo de las cotas inferiores.
- si un conjunto tiene [[#mínimo]], también tiene ínfimo, e $ínf(A)=mín(A)$.
### maximal

El maximal del conjunto $A$ es un $M\in A$ tal que
$$\centernot{\exists}x\in A, x\neq M (M\leq x)$$
Si el orden de $U$ es un [[relación de orden#relación de orden total|orden total]], maximal = [[#máximo]] en $A$.
### minimal

El minimal de un conjunto $A$ es un $m\in A$ tal que $$\centernot{\exists}x\in A, x\neq m (x\leq m)$$Si el orden de $U$ es un [[relación de orden#relación de orden total|orden total]], minimal = [[#mínimo]] en $A$.
## propiedades de los conjuntos ordenados
### propiedad del buen orden

Se dice que un conjunto ordenado $(U,\leq)$ está *bien ordenado* cuando cualquier subconjunto no vacío del mismo posee [[#mínimo]].

El orden de $\mathbb{N}$ es un buen orden. El **principio de buena ordenación** de $\mathbb{N}$ se enuncia:

> [!NOTE] principio de buena ordenación de $\mathbb{N}$
> Todo conjunto no vacío de números naturales tiene mínimo
### propiedad del supremo

Se dice que un conjunto ordenado $(U,\leq)$ cumple la propiedad del supremo si y solo si cualquier subconjunto no vacío $A$ [[#cotas superiores|acotado superiormente]] posee [[#supremo]].

> [!NOTE] axioma del supremo de $\mathbb{R}$
> todo conjunto no vacío de $\mathbb{R}$ acotado superiormente tiene un supremo
