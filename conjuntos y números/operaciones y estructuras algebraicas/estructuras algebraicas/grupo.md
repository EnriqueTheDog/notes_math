
Siendo $G$ un conjunto, y $\star$ una [[operación interna]] en $G$, se dice que $(G,\star)$ es un grupo si cumple las siguientes condiciones:
1) $\star$ es [[asociación|asociativa]]
2) Existe un [[operación interna#elemento neutro|elemento neutro]] de $\star$ en $G$
3) Para todo $a\in G$ existe en $G$ un [[operación interna#elemento simétrico|elemento simétrico]] de $a$ respecto de $\star$

Si, además, es [[conmutación|conmutativa]], se dice que $G$ es un **grupo conmutativo** o abeliano.
## propiedades del grupo

1) **Propiedad cancelativa**: $$\forall a,b,c \in G,\ (a\star b = a\star c) \implies b=c$$
2) Para todo $a,b\in G$, existe un único $x\in G$ tal que $a\star x = b$
3) Si $a^{-1}$ y $b^{-1}$ son [[operación interna#elemento simétrico|elementos simétricos]] de $a$ y $b$, entonces$$(a\star b)^{-1}=b^{-1}\star a^{-1}$$
Notar que la propiedad cancelativa indica que, en un grupo $(G,\star)$, la [[aplicación]] $f_a:G\longrightarrow G$, con $a\in G$, tal que $f_a(x)=a\star x$, para todo $x\in G$, es [[aplicación#aplicación inyectiva|inyectiva]].
## grupo ordenado

Sea $(G,+)$ un grupo conmutativo, $0$ el [[operación interna#elemento neutro|elemento neutro]] y $-a$ el [[operación interna#elemento simétrico|elemento simétrico]] de $a$
Sea una [[relación de orden]] $\leq$ definida sobre $G$
Se dice que $(G,+,\leq)$ es un grupo ordenado si la relación de orden es compatible con la suma, es decir$$\forall a,b,c\in G,\ \ a\leq b\implies a+c\leq b+c$$
El elemento $a\in G$ es **positivo** si se cumple que $0\leq a$, y **negativo** si se da lo contrario
El conjunto de los elementos positivos de $G$ se denota por $G_+$

Si la relación de orden es [[relación de orden#relación de orden total|total]], se dice que el grupo es un **grupo totalmente ordenado**.
### propiedades del grupo ordenado

1. $$a\leq b \iff b-a\in G_+$$
2. $$a\leq b\land a'\leq b' \implies a+a'\leq b+b'$$
3. $$a\leq b \implies -b\leq -a$$