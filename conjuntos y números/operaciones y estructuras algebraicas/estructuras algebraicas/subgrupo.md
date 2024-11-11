
Se dice que $H$ es un subgrupo del [[grupo]] $(G,\star)$ si $(H,\star)$ es también un grupo.

Sabemos que como $G$ es [[asociación|asociativo]], $H$ también lo es. Por tanto solo queda comprobar si $H$ cumple con el resto de [[grupo#propiedades del grupo|propiedades de los grupos]]:
1) Si $\forall a,b\in H, a\star b\in H$
2) $e\in H$, siendo $e$ el [[operación interna#elemento neutro|elemento neutro]] de $\star$ en $G$
3) $\forall a\in H, a^{-1}\in H$

Todo esto se puede condensar en la fórmula siguiente:

> [!NOTE] Fórmula del subgrupo
> $H$ es un subgrupo de $G$ *si y solo si* $H\subset G$ y $\forall a,b\in H, a\star b^{-1}\in H$

## congruencia módulo subgrupo

Sea $(G,\star)$ un [[grupo]] conmutativo y $H$ un subgrupo.
La relación $\mathcal{R}_H$ en $G$, para todo $a,b\in G$, que cumple que: $$a\mathcal{R}_Hb \iff a\star b^{-1}\in H$$
Es una [[relación de equivalencia]] que se conoce como **congruencia módulo H**.

- Es reflexiva: $a\star a^{-1}=e\in H$
- Es simétrica: $(a\star b^{-1})^{-1}=b\star a^{-1}\in H$, y por tanto $b\mathcal{R}_Ha$
- Es transitiva: $(a\star b^{-1})\star (b\star c^{-1})=a\star c^{-1}\in H$
## otras propiedades de los subgrupos

- Toda [[relación de equivalencia#clase de equivalencia|clase de equivalencia]] de $R_H$ es [[equipotencia de conjuntos|equipotente]] a $H$ $$[a]=a\star H=\{a\star h|h\in H\}$$
- Si $card(G)$ es finito, cualquier subgrupo cumple que $card(H)$ es divisor de $card(G)$