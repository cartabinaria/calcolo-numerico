---
tags:
  - category/note
  - status/finished
  - topic/calcolo-numerico
date: 04-10-2024 13:29:16
links:
  - "[[lecture-26092024092021|Lecture 26092024092021]]"
  - "[[lecture-30092024131914|Lecture 30092024131914]]"
  - "[[lecture-05112024094126|Lecture 05112024094126]]"
---
# Algoritmi per la risoluzione di sistemi lineari
---
## Introduzione
> Il calcolo numerico si occupa anche di trovare **[[algoritmo|algoritmi]] per il calcolo della soluzione di [[sistema-lineare|sistemi lineari]]**. In particolare, definito un sistema lineare quadrato ($m = n$) come
> $$A\underline{x} = \underline{b}$$
> possiamo garantire che abbia una e una sola soluzione se $A$ _non è singolare_, ossia il [[determinante|determinante]] $\det(A) \neq 0$[^1].
> Una volta determinato ciò, usiamo un algoritmo per calcolare la soluzione in modo efficiente.

## Metodi
Esistono due classi di algoritmi del genere:
- **metodi diretti** --> utilizzano formule matematiche per ottenere la _soluzione precisa_, ma sono _poco efficienti_
- **metodi iterativi** --> utilizzano algoritmi iterativi per ottenere una _soluzione approssimativa_ (per via dell'[[errore-di-troncamento|errore di troncamento]]), ma sono _molto efficienti_

### Metodi diretti
Un'idea _naif_ potrebbe essere quella di sfruttare la seguente relazione per calcolare la soluzione del sistema $Ax = b$:
$$Ax = b \iff A^{-1}Ax = A^{-1}b \iff x = A^{-1}b$$

Il problema, qui, sta nel calcolo della [[matrice-invertibile|matrice inversa]], particolarmente dispendioso in termini di [[complessita-computazionale|complessità computazionale]] ($O(n^{3})$).

Si preferiscono, piuttosto, metodi come:
- [[fattorizzazione-lu|fattorizzazione LU]]
- [[fattorizzazione-di-cholesky|fattorizzazione di Cholesky]]

### Metodi iterativi
L'unico metodo iterativo studiato è il:
- [[metodo-dei-gradienti-coniugati|metodo dei gradienti coniugati]]

## Referenze
[^1]: lo sappiamo dal [[determinante-teoremone|teoremone]]