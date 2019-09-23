**Homework 2**  
====
Kuanye Li  
5180219103330


## Problem 1
P: Tom is a blue cat.  
Q: Tom is a black cat.  
Because Tom can't be a blue cat and a black cat at the same time.  
Formalize: (P∧¬Q)∨(¬P∧Q)


## Problem 2  
A n-variable connective has 2^n rows in it's truth table.  
So we can define **2^(2^n)** n-variable connectives.  
  
A well-formed formula with n propositional variables needs **2^n** rows to build the truth table.  


## Problem 3  
¬P = ¬(P∨F) = P↓F  
P∨Q = ¬(P↓Q)  
P∧Q = ¬(¬P∨¬Q) = ¬P↓¬Q = (P↓F)↓(Q↓F)  
P→Q = ¬P∨Q = ¬(¬P↓Q) = ((P↓F)↓Q)↓F  
P↔Q = (P→Q)∧(Q→P) = (((P↓F)↓Q)↓F)∧(((Q↓F)↓P)↓F)  


## Problem 4  
A = (P∧¬Q)∨(¬P∧Q)∨(¬P∧¬Q)  
B = (P∨¬Q)∧(P∨Q)  


## Problem 5  
(P→Q)∧P = (¬P∨Q)∧P = (¬P∧P)∨(Q∧P) = F∨(Q∧P) = P∧Q  
¬(P↔Q) = ¬((P→Q)∧(Q→P)) = ¬(¬P∨Q)∨¬(¬Q∨P) = (P∧¬Q)∨(¬P∧Q)  
(P∨Q)↔(P∧Q) = ¬(((P∨Q)∧¬(P∧Q))∨(¬(P∨Q)∧(P∧Q))) = ¬((P∨Q)∧(¬P∨¬Q)) = (P∧Q)∨(¬P∧¬Q)  

## Problem 6  
* Way 1  

| P | Q | (P ↔ Q) ↔ ((P ∧ ¬Q) ∨ (Q ∧ ¬P))| 
| :----: | :----: | :----: | 
|T       |T       |F       |
|T       |F       |F       |
|F       |T       |F       |
|F       |F       |F       |

* Way 2  

In **Problem 5** we prove:  
¬(P↔Q) = (P∧¬Q)∨(¬P∧Q)  

 (P ↔ Q) ↔ ((P ∧ ¬Q) ∨ (Q ∧ ¬P)) = (P ↔ Q) ↔ (¬(P↔Q)) = F  

 * So the formula is a contradiction.


