---
title: "IOrderedShape"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Rappresenta una forma ordinata."
type: docs
weight: 129
url: /it/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Rappresenta una forma ordinata. Una forma ordinata è un insieme continuo di punti con un punto di inizio e un punto di fine. L'insieme continuo di punti è collegato usando una regola specifica.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Ottiene il punto finale della forma. |
| [getStartPoint()](#getStartPoint--) | Ottiene il punto iniziale della forma. |
| [isClosed()](#isClosed--) | Ottiene un valore che indica se la forma ordinata è chiusa. |
| [reverse()](#reverse--) | Inverte l'ordine dei punti per questa forma. |
| [setClosed(boolean value)](#setClosed-boolean-) | Imposta un valore che indica se la forma ordinata è chiusa. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Ottiene il punto finale della forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Ottiene il punto iniziale della forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Ottiene un valore che indica se la forma ordinata è chiusa. Quando si elabora una forma ordinata chiusa, i punti di inizio e fine non hanno significato.

**Returns:**
boolean -  true  se questa forma ordinata è chiusa; altrimenti,  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


Inverte l'ordine dei punti per questa forma.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Imposta un valore che indica se la forma ordinata è chiusa. Durante l'elaborazione di una forma ordinata chiusa i punti di inizio e fine non hanno significato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | true  se questa forma ordinata è chiusa; altrimenti,  false . |

