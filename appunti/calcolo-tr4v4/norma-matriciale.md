---
tags:
  - category/note
  - status/finished
  - topic/calcolo-numerico
date: 04-10-2024 16:10:58
links:
  - "[[lecture-30092024131914|Lecture 30092024131914]]"
---
# Norma matriciale
---
## Introduzione
> Per **norma matriciale**, un'estensione della [[norma-vettoriale|norma vettoriale]], si intende una generica [[funzione-matematica|funzione]]
> $$\| \cdot \|: \mathbb{R}^{n} \times \mathbb{R}^{m} \to \mathbb{R}$$
> tale che:
> 1. $\|A\| \geq 0 \ \ \ \forall A \in \mathbb{R}^{n \times m}, \|A\| = 0 \iff A = \underline{\underline{0}}$
> 2. $\alpha \in \mathbb{R}, \|\alpha A\| = |\alpha| \|A\|$
> 3. $\forall A, B \in \mathbb{R}^{n \times m}, \|A+B\| \leq \|A\| + \|B\|$ ([[disuguaglianza-triangolare|disuguaglianza triangolare]])

## Tipologie
Le più importanti norme matriciali sono:
- **[[norma-di-frobenius|norma di Frobenius]]** --> $\|A\|_{F} = \sqrt{\sum\limits_{i=1}^{m}{\sum\limits_{j=1}^{n}{{a_{ij}}^{2}}}}$, ossia l'equivalente matriciale della [[norma-euclidea|norma euclidea]];
- **norma 2** --> $\|A\|_{2} = \sqrt{p(A^{T}A)}$ dove $p(M)$ è il [[raggio-spettrale|raggio spettrale]], ossia il _massimo [[autovalore|autovalore]] in modulo_;
- **norma 1** --> $\|A\|_{1} = \max_{1 \leq j \leq n} \sum\limits_{i=1}^{m}{|a_{ij}|}$

## Referenze