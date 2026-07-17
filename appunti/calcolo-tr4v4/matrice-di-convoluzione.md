---
tags:
  - category/note
  - status/finished
  - topic/calcolo-numerico
  - topic/introduzione-all-apprendimento-automatico
date: 24-11-2024 14:24:43
links:
  - "[[lecture-11112024131700|Lecture 11112024131700]]"
  - "[[lecture-20112025131650|Lecture 20112025131650]]"
---
# Matrice di convoluzione
---
## Introduzione
> La **matrice di convoluzione** (o **kernel**) è una [[matrice|matrice]] quadrata $K \in \mathbb{R}^{D \times D}$ con $D$ dispari che viene utilizzata per applicare la [[convoluzione|convoluzione]] ad una immagine $A \in \mathbb{R}^{M \times N}$.

## Filtri
A seconda dei valori contenuti nella matrice di convoluzione, si possono ottenere diversi effetti. Ad esempio:
- se $K$ contiene valori tutti uguali, si ottiene un _filtro di media_;
- se $K$ contiene valori positivi e negativi, con somma nulla, si ottiene un _filtro di edge detection_.
- ecc...

In particolare, dobbiamo vedere il **kernel come una sorta di pattern che vogliamo cercare all'interno della matrice in input** (di solito un'immagine). L'**output della convoluzione, infatti, non sarà altro che il grado di correlazione tra il filtro e la griglia su cui questo è applicata**.
![[convoluzione-1.png]]

### Categorie
I filtri si dividono principalmente in filtri:
- **a somma 0** - cercano un pattern nell'input;
- **a somma 1** - definiscono delle trasformazioni dell'input;

### Esempi
#### Derivata
Esiste un filtro, molto particolare, che cattura il passaggio da una zona scura a una chiara:
$$[-1 \ \ 0 \ \ 1]$$
![[convoluzione-filtro-derivata.png]]

## Referenze