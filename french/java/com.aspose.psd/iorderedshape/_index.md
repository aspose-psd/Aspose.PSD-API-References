---
title: "IOrderedShape"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente une forme ordonnée."
type: docs
weight: 129
url: /fr/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Représente une forme ordonnée. Une forme ordonnée est un ensemble continu de points ayant un point de départ et un point d'arrivée. L'ensemble continu de points est connecté selon une règle spécifique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Obtient le point final de la forme. |
| [getStartPoint()](#getStartPoint--) | Obtient le point de départ de la forme. |
| [isClosed()](#isClosed--) | Obtient une valeur indiquant si la forme ordonnée est fermée. |
| [reverse()](#reverse--) | Inverse l'ordre des points pour cette forme. |
| [setClosed(boolean value)](#setClosed-boolean-) | Définit une valeur indiquant si la forme ordonnée est fermée. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Obtient le point final de la forme.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Obtient le point de départ de la forme.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Obtient une valeur indiquant si la forme ordonnée est fermée. Lors du traitement d'une forme ordonnée fermée, les points de départ et d'arrivée n'ont aucune signification.

**Returns:**
booléen -  true  si cette forme ordonnée est fermée ; sinon,  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


Inverse l'ordre des points pour cette forme.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Définit une valeur indiquant si la forme ordonnée est fermée. Lors du traitement d'une forme ordonnée fermée, les points de départ et d'arrivée n'ont aucune signification.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true  si cette forme ordonnée est fermée ; sinon,  false . |

