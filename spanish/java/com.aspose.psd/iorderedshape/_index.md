---
title: "IOrderedShape"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Representa una forma ordenada."
type: docs
weight: 129
url: /es/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Representa una forma ordenada. Una forma ordenada es un conjunto continuo de puntos que tiene un punto de inicio y un punto final. El conjunto continuo de puntos está conectado mediante una regla específica.
## Métodos

| Método | Descripción |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Obtiene el punto final de la forma. |
| [getStartPoint()](#getStartPoint--) | Obtiene el punto inicial de la forma. |
| [isClosed()](#isClosed--) | Obtiene un valor que indica si la forma ordenada está cerrada. |
| [reverse()](#reverse--) | Invierte el orden de los puntos de esta forma. |
| [setClosed(boolean value)](#setClosed-boolean-) | Establece un valor que indica si la forma ordenada está cerrada. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Obtiene el punto final de la forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Obtiene el punto inicial de la forma.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Obtiene un valor que indica si la forma ordenada está cerrada. Al procesar una forma ordenada cerrada, los puntos de inicio y fin no tienen significado.

**Returns:**
boolean -  true  si esta forma ordenada está cerrada; de lo contrario,  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


Invierte el orden de los puntos de esta forma.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Establece un valor que indica si la forma ordenada está cerrada. Al procesar una forma ordenada cerrada, los puntos de inicio y fin no tienen significado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true  si esta forma ordenada está cerrada; de lo contrario,  false . |

