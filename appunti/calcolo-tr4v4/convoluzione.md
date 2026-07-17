---
tags:
  - category/note
  - status/finished
  - topic/calcolo-numerico
  - topic/introduzione-all-apprendimento-automatico
date: 24-11-2024 13:46:29
links:
  - "[[lecture-11112024131700|Lecture 11112024131700]]"
  - "[[lecture-20112025131650|Lecture 20112025131650]]"
---
# Convoluzione
---
## Introduzione
> La **convoluzione** è un'operazione matematica principalmente applicata su [[matrice|matrici]] che consente di combinare un [[matrice-di-convoluzione|kernel]] $K \in \mathbb{R}^{D \times D}$ (con $D$ dispari) con una immagine $A \in \mathbb{R}^{M \times N}$ per ottenere un'immagine modificata $C \in \mathbb{R}^{M \times N}$, tale che
> $$C = [K * (A|B)]$$
> dove $B \in \mathbb{R}^{(M+(D-1)) \times (N+(D-1))}$ è l'[[matrice-estesa|estensione]] di $A$ (necessaria per applicare il kernel sui bordi di $A$).
> Solitamente, $C$ viene calcolata come
> $$C_{(i, j)} = \sum\limits_{m=1}^{D} \sum\limits_{n=1}^{D} K(m,n) W_{(i,j)}(m,n)$$
> dove $W_{(i,j)}$ è la [[sottomatrice|sottomatrice]] $D \times D$ di $B$ [[centro-di-una-matrice|centrata]] in $(i+\frac{D-1}{2},j+\frac{D-1}{2})$.

## Stride
Associata a una convoluzione, si definisce lo **stride**: questo è **il numero di passi con cui voglio spostare il filtro**. Potrei infatti non guardare tutti i pixel uno alla volta (stride=1), ma saltarne alcuni!

Con stride pari a 2, per esempio, il risultato finale avrà la metà dei pixel.

## Referenze