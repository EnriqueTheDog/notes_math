#nosentiende 

Una partición de un conjunto $U$ es una [[familia de conjuntos|familia]] $P$ de subconjuntos no vacíos de $U$ [[conjuntos disjuntos|disjuntos]] dos a dos y cuya unión es el conjunto $U$. Es decir:
1. $\forall A, B\in P, A=B\lor A\cap B= \emptyset$
2. $$\bigcup_{A\in P}A=U$$
Toda [[relación de equivalencia]] $\mathcal{E}$ en un conjunto $U$ genera una partición en ese conjunto. Las clases de $U\setminus \mathcal{E}$, si se unen, forman el conjunto $U$.

Recíprocamente, toda partición $P$ de $U$ permite definir una relación de equivalencia: $$x\mathcal{E}y \iff \lnot \exists A \in P\ (\{x,y\}\subset A)$$