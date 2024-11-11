
Sean $G$ y $G'$ dos conjuntos donde se tiene definida una [[operación interna]] $+$ y $·$ respectivamente.
Sea $f: G\longrightarrow G'$ una [[aplicación]].
Se dice que $f$ es un homomorfismo si cumple que
$$\forall a,b\in G\ \ f(a+b)=f(a)·f(b)$$

El homomorfismo se llama **endomorfismo** cuando $G=G'$ y la operación interna es la misma.

Un homomorfismo [[aplicación#aplicación biyectiva|biyectivo]] es llamado **isomorfismo**.

Un endomorfismo biyectivo se denomina **automorfismo**.

## propiedades del homomorfismo

1. Si $f:G\longrightarrow G'$ es un homomorfismo, entonces la operación de $G'$ es una operación interna cuando se restringe al [[aplicación#conjunto imagen|conjunto imagen]] $f(G)$ 
2. Si $f:G\longrightarrow G'$ y $g:G'\longrightarrow G''$ son homomorfismos entonces la [[composición de aplicaciones|composición]] $g\circ f:G\longrightarrow G''$ es también un homomorfismo.
3. Si $f:G\longrightarrow G'$ es un isomorfismo, entonces la aplicación inversa $f^{-1}:G'\longrightarrow G$ también es un isomorfismo.

### propiedades del isomorfismo

Un isomorfismo entre dos conjuntos dotados de operaciones internas define una [[relaciones entre conjuntos|relación]] entre ambos que satisface las siguientes propiedades:

1. Es [[reflexión|reflexiva]] pues la aplicación de identidad $I_G$ es un isomorfismo.
2. Es [[simetría|simétrica]] pues la aplicación inversa de cualquier isomorfismo es también un isomorfismo
3. Es [[transición|transitiva]] pues si $f:G\longrightarrow G'$ y $g:G'\longrightarrow G''$ son isomorfismos entonces la [[composición de aplicaciones|composición]] $g\circ f:G\longrightarrow G''$ es también un isomorfismo.

## homomorfismos de grupos

Sea $f: G\longrightarrow G'$ un homomorfismo entre dos [[grupo|grupos]].

1. $f(0_G)=0_{G'}$
2. $f(-a)=-f(a)$ para todo $a\in G$
3. Si $H$ es un subgrupo de $G$ entonces $$f(H)=\{a'\in G'|\exists a\in H, f(a)=a'\}$$es un subgrupo de $G'$
4. Si $H'$ es un subgrupo de $G'$ entonces$$f^{-1}(H')=\{a\in G|f(a)\in H'\}$$ es un subgrupo de $G$.

De entre los subgrupos que determina un homomorfismo $f$ mediante las propiedades 3 y 4, son importantes las siguientes
### conjunto imagen del homomorfismo

El [[aplicación#conjunto imagen|conjunto imagen]] $Im(f)=f(G)$

Sean $(G,+)$ y $(G',+)$ dos [[grupo|grupos]] y $f:G\longrightarrow G$ un homomorfismo. Se tiene que:

1. $Im(f)$ es un [[subgrupo]] de $G'$
2. $f$ es [[aplicación#aplicación sobreyectiva|sobreyectivo]] *si y solo si* $Im(f)=G'$

### núcleo del homomorfismo

El **núcleo** del homomorfismo es $f^{-1}(\{0_{G'}\})$ y se denota $Ker(f)$, es decir$$Ker(f)=\{a\in G|f(a)=0_{G'}\}$$
Sean $(G,+)$ y $(G',+)$ dos [[grupo|grupos]] y $f:G\longrightarrow G$ un homomorfismo. Se tiene que:
1. $Ker(f)$ es un [[subgrupo]] de $G'$
2. $f$ es [[aplicación#aplicación inyectiva|inyectivo]] *si y solo si* $Ker(f) = {0_G}$
## homomorfismos de anillos y cuerpos

Para [[anillo|anillos]] y [[cuerpo|cuerpos]], los homomorfismos extienden su propiedad a las dos operaciones.
Si $(A,+,·)$ y $(A',+,·)$ son dos anillos, para que $f:A\longrightarrow A$ sea un homomorfismo de anillos se tiene que cumplir que$$i)\ f(a+b)=f(a)+f(b)$$$$ii)\ f(ab)=f(a)f(b)$$
Satisfacen todas las propiedades anteriores

En particular, se tiene que $Im(f)=f(A)$ es a su vez un anillo.
También se tiene que si el anillo $A$ es conmutativo entonces $Ker(f)$ es un [[ideal]] de $A$.

Un **homomorfismo de cuerpos** hace lo mismo que un homomorfismo de anillos.
## homomorfismos de conjuntos ordenados

Si tenemos dos [[conjunto ordenado|conjuntos ordenados]] $(U,\leq)$ y $(V,\preceq)$, una [[aplicación]] $f:U\longrightarrow V$ es un homomorfismo de estructuras de orden si es creciente, es decir$$\forall u,u'\in U\ \ \ u\leq u'\implies f(u)\preceq f(u')$$
Cuando la aplicación f sea [[aplicación#aplicación biyectiva|biyectiva]] hablaremos de **isomorfismo** de estructuras ordenadas.