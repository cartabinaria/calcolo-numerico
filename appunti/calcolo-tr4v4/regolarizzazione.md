---
tags:
  - category/note
  - status/finished
  - topic/calcolo-numerico
date: 30-10-2024 13:44:21
links:
  - "[[lecture-15102024091721|Lecture 15102024091721]]"
---
# Regolarizzazione
---
## Introduzione
> La **regolarizzazione** è una _tecnica usata nell'[[approssimazione-di-dati|approssimazione di dati]] per risolvere il problema dell'[[overfitting|overfit]]_.

## Idea
> _Non è possibile diagnosticare l'overfit_, ma _è possibile risolverlo_.

Questa è l'idea alla base della regolarizzazione. Per cui **si introduce a forza l'overfit e poi si risolve**.

Nel caso dell'[[approssimazione-ai-minimi-quadrati|approssimazione ai minimi quadrati]], introdurre l'overfit significa _porre il grado del modello approssimante $d$ sicuramente più alto di quanto si stima debba essere_. Quindi, si risolve l'overfit **ponendo il maggior numero possibile di valori di $\alpha$ ([[vettore|vettore]] dei coefficienti) a 0**. Infatti questo porta ad _annullare "l'effetto" di termini di grado alto_, risolvendo l'overfit.

## Tecniche
Esistono molte tecniche di regolarizzazione, di cui si ricordano:
- [[regolarizzazione-alla-tikhonov|regolarizzazione alla Tikhonov]]
- [[metodo-lasso|metodo LASSO]]

## Referenze