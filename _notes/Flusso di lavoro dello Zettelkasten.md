---
title: Flusso di lavoro dello Zettelkasten
---

Il seguente diagramma riassume il flusso di entrata delle note che compongono uno [[Zettelkasten]]:

```mermaid
graph TD
	a((Sorgente)) --> b[Nota Letteraria] --> f
	c((Idea)) --> d[Nota Transitoria]
	b -->|Elaborazione| e[Nota Permanente]
	d -->|Elaborazione| e
	e --> f[(Zettelkasten)] -.-> g[Note di Progetto]

```

Ci sono tre tipi di note:
- **transitorie**: appunti di idee volanti, pensieri non strutturati, etc
- **permanenti**:
	- **letterarie**: appunti su materiale letto, con riferimenti bibliografici
	- **zettel**: rielaborazione dei concetti con parole proprie, rispetto al criterio di [[atomicità]] e [[interconnessione]]
- **di progetto**: note scritte per un progetto e scartate al suo termine
	- commenti agli scritti
	- collezioni di letteratura legata al progetto
	- outline
	- stralci di bozza
	- promemoria
	- liste di cose da fare

# Sorgenti

- Ahrens, Sönke. *How to take Smart Notes*, CreateSpace, 2017


