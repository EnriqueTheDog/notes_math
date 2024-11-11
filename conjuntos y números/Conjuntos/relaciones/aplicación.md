
Una aplicación es una [[relaciones entre conjuntos|relación]] entre dos conjuntos $A$ y $B$ en la que cualquier elemento de $A$ está relacionado únicamente con un elemento de $B$. Es lo que comúnmente llamamos **función**.

$F:A\longrightarrow B$ es una aplicación si para cada $x\in A$ existe un único $y\in B$ tal que $F(x)=y$.

## elementos de la aplicación
### conjunto original

En $F:A\longrightarrow B$, $A$ es el conjunto original o **dominio** de f. Se denota $Orig(f)$ o $Dom(f)$.
### conjunto final

En $F:A\longrightarrow B$, $b$ es el conjunto final de f.
### conjunto imagen

Se llama conjunto imagen, recorrido o **rango** de $f$ al conjunto$$f(A)=\{y\in B|\exists x\in A, f(x)=y\}=\{f(x)|x\in A\}$$Es decir, el conjunto de todos los posibles "outputs" de la aplicación. Se denota $Im(f)$.
### imagen de x

El elemento resultado de $f(x)$ se denomina imagen de $x$ en $f$.
### original de y

El *original* de $y$ es$$f^{-1}(y)=\{x\in A|f(x)=y\}$$
Se denomina también **imagen inversa** de $y$ por $f$.
### conjunto de aplicaciones

El conjunto de todas las aplicaciones de $A$ a $B$ se denota $\mathscr{F}(A,B)$ o $B^{A}$, y $\mathscr{F}(A)$ si $A=B$.

## propiedades de la aplicación
### aplicación constante
#nosentiende 

Una aplicación se dice constante si$$f:A\longrightarrow B \iff \forall x, x'\in A,\ f(x)=f(x')$$
La [[#imagen de x|imagen]] de cada elemento de A es siempre el mismo elemento de B
### proyección canónica

La proyección canónica del conjunto $A$ en el [[relación de equivalencia#conjunto cociente|conjunto cociente]] se escribe $$p:A\longrightarrow A/\mathcal{E}$$$$x \longmapsto p(x)=[x]$$
O sea, la aplicación que asigna a cada elemento su [[relación de equivalencia#clase de equivalencia|clase de equivalencia]].

### relación de equivalencia a partir de una aplicación

Una aplicación $f:A\longrightarrow B$ permite definir una [[relación de equivalencia]] $\mathcal{E}f$ en $A$:$$x\mathcal{E}fy\iff f(x)=f(y)$$
#nosentiende 
Considerando la [[#proyección canónica|aplicación canónica]] y la aplicación $\tilde{f}$, que asigna a cada [[relación de equivalencia#clase de equivalencia|clase de equivalencia]] la [[aplicación#imagen de x|imagen]] mediante $f$ de uno cualquiera de sus representantes:
$$\tilde{f}:A\longrightarrow B$$
$$[x]\longmapsto \tilde{f}([x])=f(x)$$
### relación inversa de una aplicación

Como una aplicación $f:A\longrightarrow B$ es una relación $f\subset AB$, existe una relación inversa $f^{-1}$
$$f^{-1}=\{(y,x)\in BA|f(x)=y\}=\{f(x),x|x\in A\}$$
La relación inversa de una aplicación no tiene por qué ser también una aplicación.

### igualdad de aplicaciones

Dadas las aplicaciones $f:A\longrightarrow B$ y $g:A'\longrightarrow B'$

$$
\begin{equation}
  f=g\iff\begin{cases}
    A=A'\\
    B=B'\\
    f(x)=g(x)\ \forall x\in A
  \end{cases}
\end{equation}$$
## inyección, sobreyección y biyección
### aplicación sobreyectiva
(ver [[composición de aplicaciones]], [[aplicación identidad]])

$$\forall y \in B, \exists x \in A (f(x)=y)$$
Es aquella en la que cada $y$ en el [[aplicación#conjunto final|conjunto final]] $B$ es [[aplicación#imagen de x|imagen]] de, al menos, un $x$ en el [[aplicación#conjunto original|conjunto original]].

Sea $f\in \mathscr{F}(A,B)$

$f$ es una aplicación sobreyectiva *si y solo si* existe una aplicación $h\in \mathscr{F}(B,A)$ tal que $f\circ h=I_B$. H es una [[#aplicación inyectiva]].

Siendo $A$ un conjunto de $n$ elementos, y $B$ un conjunto de $m$ elementos

Si $n<m$ no existen aplicaciones sobreyectivas de $A$ a $B$  
### aplicación inyectiva
(ver [[composición de aplicaciones]], [[aplicación identidad]])

$$\forall x,x'\in A,\ f(x)=f(x')\longrightarrow x=x'$$
Es aquella en la que cada $x$ en el [[#conjunto original]] tiene una  [[aplicación#imagen de x|imagen]] distinta. No hay dos $x$ con la misma imagen $y$.

Sea $f\in \mathscr{F}(A,B)$

$f$ es una aplicación inyectiva *si y solo si* existe una aplicación $g\in \mathscr{F}(B,A)$ tal que $g\circ f=I_A$. H es una [[#aplicación sobreyectiva]].

Siendo $A$ un conjunto de $n$ elementos, y $B$ un conjunto de $m$ elementos

- Si $n\le m$ el número de aplicaciones inyectivas de $A$ a $B$ distintas es $m(m-1)...(m-n+1)$
- Si $n>m$, no existen aplicaciones inyectivas de $A$ a $B$
### aplicación biyectiva

Se dice que una aplicación es biyectiva cuando es [[#aplicación inyectiva|inyectiva]] y [[#aplicación sobreyectiva|sobreyectiva]] al mismo tiempo.

$\forall y\in B$ existe un único $x\in A$ tal que $f(x)=y$.

Cada $x$ en el  [[aplicación#conjunto original|conjunto original]] tiene una  [[aplicación#imagen de x|imagen]] distinta, y cada $y$ en el [[aplicación#conjunto final|conjunto final]] es imagen de un $x$ distinto.

Una aplicación es biyectiva *si y solo si* existe una aplicación $g\in \mathscr{F}(A,B)$ tal que $f\circ g=I_B$ y $g\circ f = I_A$ .

O sea, que si $f$ es biyectiva, la [[aplicación#relación inversa de una aplicación|relación inversa]] $f^{-1}$ **también es una aplicación**.

Siendo $A$ un conjunto de $n$ elementos, y $B$ un conjunto de $m$ elementos

-  Si $n=m$ hay $n!$ aplicaciones distintas que son biyectivas de $A$ a $B$
-  Si $n\ne m$ no hay aplicaciones biyectivas de $A$ a $B$
#### composición de biyectivas
(ver [[composición de aplicaciones]])

Sean $f\in \mathscr{F}(A.B)$ y $g\in \mathscr{F}(B,C)$ dos aplicaciones biyectivas. Entonces la aplicación $g\circ f\in \mathscr{F}(A,C)$ también es biyectiva.

Su inversa es $(g\circ f)^{-1}=f^{-1}\circ g^{-1}$

Sea $f\in \mathscr{F}(A,B)$ una [[#aplicación inyectiva]] de $A$ a $B$ 

Esta da lugar a una aplicación biyectiva de $A$ al [[#conjunto imagen]].$$Im(f)=f(A)$$O sea, que $\hat{f} \in \mathscr{F}(A,f(A))$ coincide con $f$ sobre $A$ y es una biyección.yes, ahor