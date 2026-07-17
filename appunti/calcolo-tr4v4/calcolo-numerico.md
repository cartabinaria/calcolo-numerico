---
tags:
  - "#category/moc"
  - "#status/finished"
  - topic/calcolo-numerico
date: 16-09-2024 10:19:47
---
# Calcolo numerico
---
## Lezioni
### Ultima lezione
<!-- QueryToSerialize: TABLE WITHOUT ID file.link AS Lezione, file.inlinks AS Note FROM #category/lecture AND #topic/calcolo-numerico SORT file.ctime DESC LIMIT 1 -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link AS Lezione, file.inlinks AS Note FROM #category/lecture AND #topic/calcolo-numerico SORT file.ctime DESC LIMIT 1 -->

| Lezione                    | Note                                                                                                                                                           |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [[lecture-05112024094126|Lecture 05112024094126]] | <ul><li>[[calcolo-numerico|Calcolo numerico]]</li><li>[[algoritmi-per-la-risoluzione-di-sistemi-lineari|Algoritmi per la risoluzione di sistemi lineari]]</li><li>[[cgls|CGLS]]</li><li>[[metodo-dei-gradienti-coniugati|Metodo dei gradienti coniugati]]</li></ul> |
<!-- SerializedQuery END -->

### Lista
<!-- QueryToSerialize: TABLE WITHOUT ID file.link AS Lezione, date AS Data FROM #category/lecture AND #topic/calcolo-numerico SORT file.ctime DESC -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link AS Lezione, date AS Data FROM #category/lecture AND #topic/calcolo-numerico SORT file.ctime DESC -->

| Lezione                                                           | Data                |
| ----------------------------------------------------------------- | ------------------- |
| [[lecture-05112024094126|Lecture 05112024094126]] | 05-11-2024 09:41:26 |
| [[lecture-11112024131700|Lecture 11112024131700]] | 11-11-2024 13:17:00 |
| [[lecture-12112024091405|Lecture 12112024091405]] | 12-11-2024 09:14:05 |
| [[lecture-04112024131513|Lecture 04112024131513]] | 04-11-2024 13:15:13 |
| [[lecture-22102024092339|Lecture 22102024092339]] | 22-10-2024 09:23:39 |
| [[lecture-21102024132104|Lecture 21102024132104]] | 21-10-2024 13:21:04 |
| [[lecture-15102024091721|Lecture 15102024091721]] | 15-10-2024 09:17:21 |
| [[lecture-14102024131954|Lecture 14102024131954]] | 14-10-2024 13:19:54 |
| [[lecture-08102024093421|Lecture 08102024093421]] | 08-10-2024 09:34:21 |
| [[lecture-07102024132143|Lecture 07102024132143]] | 07-10-2024 13:21:43 |
| [[lecture-30092024131914|Lecture 30092024131914]] | 30-09-2024 13:19:14 |
| [[lecture-26092024092021|Lecture 26092024092021]] | 26-09-2024 09:20:21 |
| [[lecture-24092024092227|Lecture 24092024092227]] | 24-09-2024 09:22:27 |
| [[lecture-23092024132935|Lecture 23092024132935]] | 23-09-2024 13:29:35 |
| [[lecture-16092024131302|Lecture 16092024131302]] | 16-09-2024 13:13:02 |
| [[lecture-16092024152034|Lecture 16092024152034]] | 16-09-2024 15:20:34 |
<!-- SerializedQuery END -->

### Da processare
<!-- QueryToSerialize: TABLE WITHOUT ID file.link as Lezione, filter(file.tags, (t) => t="#status/pending" OR t="#status/ongoing") AS Status FROM #category/lecture AND #topic/calcolo-numerico AND (#status/pending OR #status/ongoing) SORT date DESC -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link as Lezione, filter(file.tags, (t) => t="#status/pending" OR t="#status/ongoing") AS Status FROM #category/lecture AND #topic/calcolo-numerico AND (#status/pending OR #status/ongoing) SORT date DESC -->

| Lezione | Status |
| ------- | ------ |
<!-- SerializedQuery END -->

## Note
- Argomenti
	- Numeri finiti ed errori
		- [[codifica-floating-point|Codifica floating-point]]
		- [[errore-nel-calcolo-numerico|Errore nel calcolo numerico]]
		- [[aritmetica-floating-point|Aritmetica floating-point]]
	- Algebra lineare numerica
		- [[algoritmi-per-il-calcolo-delle-radici-di-una-funzione|Algoritmi per il calcolo delle radici di una funzione]]
		- [[algoritmi-per-la-risoluzione-di-sistemi-lineari|Algoritmi per la risoluzione di sistemi lineari]]
		- [[problema-dei-minimi-quadrati|Problema dei minimi quadrati]]
	- [[approssimazione-di-dati|Approssimazione di dati]]
		- [[approssimazione-ai-minimi-quadrati|Approssimazione ai minimi quadrati]]
		- [[regolarizzazione|Regolarizzazione]]
		- [[interpolazione|Interpolazione]]
	- [[ottimizzazione-di-dati|Ottimizzazione di dati]]
		- [[metodo-di-discesa-del-gradiente|Metodo di discesa del gradiente]]
		- [[metodo-dei-gradienti-coniugati|Metodo dei gradienti coniugati]], [[cgls|CGLS]]
	- [[problemi-inversi|Problemi inversi]]
		- [[imaging|Imaging]]
	- Introduzione, esercitazioni e applicazioni a Python

- Homeworks
	- [[calcolo-numerico-hw. 1|Calcolo numerico - HW. 1]]
	- [[calcolo-numerico-hw. 2|Calcolo numerico - HW. 2]]
	- [[calcolo-numerico-hw. 3|Calcolo numerico - HW. 3]]

<!-- QueryToSerialize: TABLE WITHOUT ID file.link AS Note, filter(file.tags, (t) => t="#status/pending" OR t="#status/ongoing" OR t="#status/finished") AS Status FROM #category/note AND #topic/calcolo-numerico SORT file.ctime DESC -->
<!-- SerializedQuery: TABLE WITHOUT ID file.link AS Note, filter(file.tags, (t) => t="#status/pending" OR t="#status/ongoing" OR t="#status/finished") AS Status FROM #category/note AND #topic/calcolo-numerico SORT file.ctime DESC -->

| Note                                                                                                                         | Status                             |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| [[algoritmo-iterativo|Algoritmo iterativo]]                                                                     | <ul><li>#status/finished</li></ul> |
| [[variazione-totale|Variazione totale]]                                                                         | <ul><li>#status/finished</li></ul> |
| [[rumore-bianco|Rumore bianco]]                                                                                 | <ul><li>#status/finished</li></ul> |
| [[psf|PSF]]                                                                                                     | <ul><li>#status/finished</li></ul> |
| [[matrice-di-convoluzione|Matrice di convoluzione]]                                                             | <ul><li>#status/finished</li></ul> |
| [[sottomatrice|Sottomatrice]]                                                                                   | <ul><li>#status/finished</li></ul> |
| [[centro-di-una-matrice|Centro di una matrice]]                                                                 | <ul><li>#status/finished</li></ul> |
| [[matrice-estesa|Matrice estesa]]                                                                               | <ul><li>#status/finished</li></ul> |
| [[convoluzione|Convoluzione]]                                                                                   | <ul><li>#status/finished</li></ul> |
| [[imaging|Imaging]]                                                                                             | <ul><li>#status/finished</li></ul> |
| [[cgls|CGLS]]                                                                                                   | <ul><li>#status/finished</li></ul> |
| [[metodo-dei-gradienti-coniugati|Metodo dei gradienti coniugati]]                                               | <ul><li>#status/finished</li></ul> |
| [[problemi-inversi|Problemi inversi]]                                                                           | <ul><li>#status/finished</li></ul> |
| [[principio-di-massima-discrepanza|Principio di massima discrepanza]]                                           | <ul><li>#status/finished</li></ul> |
| [[fattorizzazione-ai-valori-singolari-troncata|Fattorizzazione ai valori singolari troncata]]                   | <ul><li>#status/finished</li></ul> |
| [[condizioni-discrete-di-picard|Condizioni discrete di Picard]]                                                 | <ul><li>#status/finished</li></ul> |
| [[condizione-di-wolfe|Condizione di Wolfe]]                                                                     | <ul><li>#status/finished</li></ul> |
| [[metodo-di-discesa-del-gradiente|Metodo di discesa del gradiente]]                                             | <ul><li>#status/finished</li></ul> |
| [[funzione-coerciva|Funzione coerciva]]                                                                         | <ul><li>#status/finished</li></ul> |
| [[funzione-convessa|Funzione convessa]]                                                                         | <ul><li>#status/finished</li></ul> |
| [[nodi-di-chebyshev-gauss-lobatto|Nodi di Chebyshev-Gauss-Lobatto]]                                             | <ul><li>#status/finished</li></ul> |
| [[interpolazione|Interpolazione]]                                                                               | <ul><li>#status/finished</li></ul> |
| [[ottimizzazione-di-dati|Ottimizzazione di dati]]                                                               | <ul><li>#status/finished</li></ul> |
| [[metodo-lasso|Metodo LASSO]]                                                                                   | <ul><li>#status/finished</li></ul> |
| [[regolarizzazione-alla-tikhonov|Regolarizzazione alla Tikhonov]]                                               | <ul><li>#status/finished</li></ul> |
| [[regolarizzazione|Regolarizzazione]]                                                                           | <ul><li>#status/finished</li></ul> |
| [[approssimazione-ai-minimi-quadrati|Approssimazione ai minimi quadrati]]                                       | <ul><li>#status/finished</li></ul> |
| [[problema-test|Problema test]]                                                                                 | <ul><li>#status/finished</li></ul> |
| [[approssimazione-di-dati|Approssimazione di dati]]                                                             | <ul><li>#status/finished</li></ul> |
| [[fattorizzazione-ai-valori-singolari|Fattorizzazione ai valori singolari]]                                     | <ul><li>#status/finished</li></ul> |
| [[fattorizzazione-agli-autovalori|Fattorizzazione agli autovalori]]                                             | <ul><li>#status/finished</li></ul> |
| [[problema-dei-minimi-quadrati|Problema dei minimi quadrati]]                                                   | <ul><li>#status/finished</li></ul> |
| [[norma-matriciale|Norma matriciale]]                                                                           | <ul><li>#status/finished</li></ul> |
| [[norma-vettoriale|Norma vettoriale]]                                                                           | <ul><li>#status/finished</li></ul> |
| [[numero-di-condizione|Numero di condizione]]                                                                   | <ul><li>#status/finished</li></ul> |
| [[errore-inerente|Errore inerente]]                                                                             | <ul><li>#status/finished</li></ul> |
| [[errore-algoritmico|Errore algoritmico]]                                                                       | <ul><li>#status/finished</li></ul> |
| [[fattorizzazione-di-cholesky|Fattorizzazione di Cholesky]]                                                     | <ul><li>#status/finished</li></ul> |
| [[fattorizzazione-lu|Fattorizzazione LU]]                                                                       | <ul><li>#status/finished</li></ul> |
| [[algoritmi-per-la-risoluzione-di-sistemi-lineari|Algoritmi per la risoluzione di sistemi lineari]]             | <ul><li>#status/finished</li></ul> |
| [[velocita-di-convergenza|Velocità di convergenza]]                                                             | <ul><li>#status/finished</li></ul> |
| [[algoritmo-di-bisezione|Algoritmo di bisezione]]                                                               | <ul><li>#status/finished</li></ul> |
| [[algoritmo-di-newton|Algoritmo di Newton]]                                                                     | <ul><li>#status/finished</li></ul> |
| [[contrazione|Contrazione]]                                                                                     | <ul><li>#status/finished</li></ul> |
| [[mappa|Mappa]]                                                                                                 | <ul><li>#status/finished</li></ul> |
| [[algoritmo-dell-iterazione-di-punto-fisso|Algoritmo dell'iterazione di punto fisso]]                           | <ul><li>#status/finished</li></ul> |
| [[punto-fisso|Punto fisso]]                                                                                     | <ul><li>#status/finished</li></ul> |
| [[errore-di-troncamento|Errore di troncamento]]                                                                 | <ul><li>#status/finished</li></ul> |
| [[algoritmi-per-il-calcolo-delle-radici-di-una-funzione|Algoritmi per il calcolo delle radici di una funzione]] | <ul><li>#status/finished</li></ul> |
| [[aritmetica-floating-point|Aritmetica floating-point]]                                                         | <ul><li>#status/finished</li></ul> |
| [[errore-di-arrotondamento|Errore di arrotondamento]]                                                           | <ul><li>#status/finished</li></ul> |
| [[errore-nel-calcolo-numerico|Errore nel calcolo numerico]]                                                     | <ul><li>#status/finished</li></ul> |
| [[codifica-floating-point|Codifica floating-point]]                                                             | <ul><li>#status/finished</li></ul> |
| [[conversione-binario-decimale|Conversione binario-decimale]]                                                   | <ul><li>#status/finished</li></ul> |
<!-- SerializedQuery END -->

## Referenze
- [virtuale](https://virtuale.unibo.it/course/view.php?id=65887)
- [dynamik]()
- [github](https://devangelista2.github.io/calcolo-numerico/intro.html)