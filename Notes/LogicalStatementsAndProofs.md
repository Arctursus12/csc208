# Logical Statements and Proofs


## Logical Statements and Proofs

* $P \land Q$ is read "P and Q", and is called a **conjunction**.
* $P \lor Q$ is read "P or Q", and is called a **disjunction**.
* $P \implies Q$ is read "if P then Q", and is called an **implication**
  or **conditional**.
* $P \iff Q$ is read "P if and only if Q", and is called a **biconditional**.
* $\lnot P$ is read "not P", and is called a **negation**.


## Truth Conditions for Connectives

* $P \land Q$ is true when both P and Q are true. 
* $P \lor Q$ is true when both P or Q or both are true. 
* $P \implies Q$ is true when P is false and Q is true or both. 
* $P \iff Q$ is true when P and Q both true, or both false. 
* $\lnot P$ is true when P is false. 


## Direct Proofs of Implications. 

To prove an implication $P \land Q$, you get to assume P is true, and you have
to deduce Q from it. 


## Converse and Contrapositive 

* The **converse** of an implication $P \implies Q$ is the implication
  $Q \implies P$. The converse is *not* logically equivelent to the original
  implication.
* The **contrapositive** of an implication $P \implies Q$ is the implication
  $\lnot Q \implies \lnot P$. The contrapositive  *is* logically equivelent to
  the original implication.


## If and only if 

$P \iff Q$ is logically equivalent to $(P \implies Q) \land (Q \implies P)$. 


## Necessary and Sufficient

* "P is necessary for Q" means $Q \implies P$.
* "P is sufficient for Q" means $P \implies Q$.
* If P is necessary and sufficient for Q, then $P \iff Q$.
