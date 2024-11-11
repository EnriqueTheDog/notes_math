#chuleta

Siendo $A,B,C$ subconjuntos de $U$ tales que
$$A = \{x \in U | Px\}$$
$$B = \{x \in U | Qx\}$$
$$C = \{x \in U | Rx\}$$

| [[leyes de idempotencia (conjuntos)]]                                                |                                                                    |
| ------------------------------------------------------------------------------------ | ------------------------------------------------------------------ |
| $$A\cup A = A$$                                                                      | $$P_x\lor P_x \iff P_x$$                                           |
| $$A\cap A = A$$                                                                      | $$P_x\land P_x \iff P_x$$                                          |
| [[leyes conmutativas (conjuntos)]]                                                   |                                                                    |
| $$A\cup B=B\cup A$$                                                                  | $$P_x \lor Q_x=Q_x\lor P_x$$                                       |
| $$A\cap B=B\cap A$$                                                                  | $$P_x \land Q_x=Q_x\land P_x$$                                     |
| $$A\ \triangle \ B = B\ \triangle \ A $$                                             |                                                                    |
| [[leyes distributivas (conjuntos)]]                                                  |                                                                    |
| $$A\cap(B\cup C)=(A\cap B)\cup(A\cap C)$$                                            | $$P_x\lor (Q_x \land R_x) \iff (P_x \lor R_x)\land(P_x\lor R_x)$$  |
| $$A\cup(B\cap C)=(A\cup B)\cap(A\cup C)$$                                            | $$P_x\land (Q_x \lor R_x) \iff (P_x \land R_x)\lor(P_x\land R_x)$$ |
| [[leyes asociativas (conjuntos)]]                                                    |                                                                    |
| $$(A\cup B) \cup C = A \cup (B\cup C)$$                                              | $$(P_x\lor Q_x)\lor R_x = P_x\lor (Q_x\lor R_x)$$                  |
| $$(A\cap B) \cap C = A \cap (B\cap C)$$                                              | $$(P_x\land Q_x)\land R_x = P_x\land (Q_x\land R_x)$$              |
| [[leyes de identidad (conjuntos)]]                                                   |                                                                    |
| $$A\cup \emptyset = A$$                                                              | $$P_x \lor 0 \iff P_x$$                                            |
| $$A\cup U = U$$                                                                      | $$P_x \lor 1 \iff 1$$                                              |
| $$A\cap \emptyset = \emptyset$$                                                      | $$P_x \land 0 \iff 0$$                                             |
| $$A \cap U = A$$                                                                     | $$P_x \land 1 \iff P_x$$                                           |
| [[complementario de un conjunto#leyes del complementario\|leyes del complementario]] |                                                                    |
| $$A\cup \bar{A} = U$$                                                                | $$P_x \lor \lnot P_x \iff 1$$                                      |
| $$A \cap \bar{A}= \emptyset$$                                                        | $$P_x \land \lnot P_x = 0$$                                        |
| $$\overline{(\overline{A})}=A$$                                                      | $$\lnot(\lnot P_x) \iff P_x$$                                      |
| $$\bar{U} = \emptyset$$                                                              | $$\lnot(1) \iff 0$$                                                |
| $$\bar{\emptyset}=U$$                                                                | $$\lnot(0) \iff 1$$                                                |
| [[leyes de De Morgan (conjuntos)]]                                                   |                                                                    |
| $$\overline{(A\cup B)} = \overline{A}\cap \overline{B}$$                             | $$\lnot(P_x\lor Q_x) \iff \lnot P_x \land \lnot Q_x$$              |
| $$\overline{(A\cap B)} = \overline{A}\cup \overline{B}$$                             | $$\lnot(P_x\land Q_x) \iff \lnot P_x \lor \lnot Q_x$$              |

