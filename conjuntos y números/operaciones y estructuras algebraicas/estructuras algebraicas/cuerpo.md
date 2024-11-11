
Un cuerpo es un [[anillo]] conmutativo unitario en el que todo elemento no nulo es invertible respecto del producto.

Sea $\mathbb{K}$ un conjunto y sean $+$ y $·$ dos operaciones internas definidas en $\mathbb{K}$.

$(\mathbb{K},+,·)$ es un cuerpo si se cumple que:

1) Las operaciones $+$ y $·$ son [[asociación|asociativas]] en $\mathbb{K}$
2) Las operaciones $+$ y $·$ son [[conmutación|conmutativas]] en $\mathbb{K}$
3) La operación $·$ es [[distribución|distributiva]] respecto de $+$ en $\mathbb{K}$
4) Existen en $\mathbb{K}$ [[operación interna#elemento neutro|elementos neutros]] de $+$ y $·$
5) Para todo $a\in \mathbb{K}$ existe un $-a$ ([[operación interna#elemento simétrico|simétrico]] respecto de $+$)
6) Para todo $a\in \mathbb{K}$ existe un $a^{-1}$ (simétrico respecto de $·$)

Dicho de otra manera, $\mathbb{K}$ es un cuerpo si:
1) $(\mathbb{K},+)$ es un [[grupo]] conmutativo
2) $(\mathbb{K}^*,·)$ es un grupo conmutativo (un cuerpo no puede tener [[anillo#divisor de cero|divisores de cero]])
3) La operación $·$ es [[distribución|distributiva]] respecto de $+$ en $\mathbb{K}$

Notar que el cuerpo $(\mathbb{K},+,·)$ es un anillo conmutativo, por lo que satisface todas las [[anillo#propiedades del anillo|propiedades]] de estos. Del mismo modo, $(\mathbb{K},·)$ es un grupo, por lo que satisface todas sus [[grupo#propiedades del grupo|propiedades]].
## propiedades de los cuerpos

En un cuerpo $(\mathbb{K},+,·)$

- $$\forall a\in \mathbb{K}, a·0=0·a=0$$
- No hay divisores de cero, por lo que$$a·b=0\iff \begin{cases} a=0\\b=0 \end{cases}$$
- Por la [[grupo#propiedades del grupo|propiedad cancelativa]] en $(\mathbb{K^*,·})$ $$ab=ac\land a\ne 0\iff b=c$$
- Si $a\ne 0$ y $b\in \mathbb{K}$, la ecuación$$ax+b=0$$ tiene una única solución en $\mathbb{K}$, y es$$x=-ba^{-1}$$
## cuerpo ordenado

Si el cuerpo cumple con los requisitos para ser un [[anillo#anillo ordenado|anillo ordenado]], decimos que es un cuerpo ordenado.
### propiedades del cuerpo ordenado

Un cuerpo **totalmente** ordenado comparte las [[anillo#propiedades del anillo ordenado|propiedades]] del anillo ordenado, y además tiene las siguientes:

1. $a>0\implies a^{-1}>0$
2. $0<a\leq b\implies b^{-1}\leq a^{-1}$
3. $a\leq b <0\implies b^{-1}\leq a^{-1}$