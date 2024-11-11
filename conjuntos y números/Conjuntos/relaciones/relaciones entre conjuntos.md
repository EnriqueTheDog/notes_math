#nosentiende

Todo subconjunto $\mathcal{R}\subset AB$ es una **relación** o *correspondencia* entre $A$ y $B$
Se denota $$\mathcal{R}:A\longrightarrow B$$
Dado un elemento $(x,y)\in \mathcal{R}\subset AB$, se dice que $x\in A$ está **relacionado** con $y\in B$ mediante la relación $\mathcal{R}$ y se escribe$$x\mathcal{R}y$$
Si no están relacionados, se denota $x\centernot{\mathcal{R}}y$
## propiedades de las relaciones

Una relación $\mathcal{R}$ definida en un conjunto $U$, $\mathcal{R}\subset UU$, puede tener las siguientes propiedades
### propiedad reflexiva

La relación $\mathcal{R}$ es reflexiva *si y solo si* $$\{(x,x)|x\in U\}\subset \mathcal{R}$$
es decir $$\forall x \in U, x\mathcal{R}x$$
Todo elemento $x$ de $U$ encuentra una relación consigo mismo.

Si una relación es reflexiva, la representación de su grafo contiene la diagonal $x=y$
### propiedad simétrica

La relación $\mathcal{R}$ es simétrica *si y solo si* $$\mathcal{R}^{-1}\subset \mathcal{R}$$
es decir $$\forall x, y\in U, x\mathcal{R}y \longrightarrow y\mathcal{R}x$$
Todo par de elementos encuentra un par de elementos iguales en orden inverso.

Si una relación es simétrica, la representación de su grafo es simétrica respecto de la diagonal $x=y$.
### propiedad antisimétrica

La relación $\mathcal{R}$ es antisimétrica *si y solo si* $$\mathcal{R}^{-1}\cap\mathcal{R}\subset\{(x,x)|x\in U\}$$
es decir $$\forall x, y\in U, ((x\mathcal{R}y \land y\mathcal{R}x) \longrightarrow x=y)$$
Ningún par de elementos encuentra otro par de elementos iguales en orden inverso. Es contradictoria con la propiedad simétrica.
### propiedad transitiva

La relación $\mathcal{R}$ es transitiva *si y solo si* $$\mathcal{R}\circ \mathcal{R}\subset\mathcal{R}$$
es decir $$\forall x,y,z\in U, ((x\mathcal{R}y\land y\mathcal{R}z) \longrightarrow x\mathcal{R}z)$$
Todo elemento $x$ encuentra una relación con un elemento $z$ (en realidad el mismo $x$) "a través" de $y$.
## subconjuntos de una relación
### relación inversa

Se llama relación inversa de $\mathcal{R}$ al conjunto $\mathcal{R}^{-1}\subset BA$ tal que $$\mathcal{R}^{-1}=\{(y,x)\in BA| (x,y) \in \mathcal{R}\subset AB\}$$
Es decir, es lo mismo pero cambiando el orden de los miembros de cada pareja.

### conjunto original

Es el conjunto de $x$ que satisfacen todos los $y$
$$\mathcal(R)^{-1}(B)=\{x \in A|\exists y \in B, x\mathcal{R} y\}$$

### conjunto imagen de la relación

El conjunto de $y$ que satisfacen todas las $x$
$$\mathcal(R)^{-1}(A)=\{y \in B|\exists x \in A, x\mathcal{R} y\}$$

### conjunto imagen del elemento mediante correspondencia

El [[conjunto imagen]] del elemento $x\in A$ mediante correspondencia con $\mathcal{R}$
$$\mathcal{R}(x) = \{y \in B|(x,y) \in \mathcal{R}\} = \{y \in B| x\mathcal{R}y\}$$

### conjunto original del elemento mediante correspondencia

El [[conjunto original]] de $y\in B$ mediante la correspondencia $\mathcal{R}$
$$\mathcal{R}^{-1}(y) = \{x\in A|(x,y) \in \mathcal{R}\} = \{x \in A|x\mathcal{R}y\}$$

### conjunto de todas las relaciones entre A y B

Es el conjunto de las partes $\mathcal{P}(AB)$