---
title: "IOrderedShape"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Stellt eine geordnete Form dar."
type: docs
weight: 129
url: /de/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Stellt eine geordnete Form dar. Eine geordnete Form ist eine kontinuierliche Menge von Punkten mit einem Start‑ und Endpunkt. Die kontinuierliche Punktmenge ist mittels einer spezifischen Regel verbunden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Ruft den Endpunkt der Form ab. |
| [getStartPoint()](#getStartPoint--) | Ruft den Startpunkt der Form ab. |
| [isClosed()](#isClosed--) | Ruft einen Wert ab, der angibt, ob die geordnete Form geschlossen ist. |
| [reverse()](#reverse--) | Kehrt die Reihenfolge der Punkte für diese Form um. |
| [setClosed(boolean value)](#setClosed-boolean-) | Setzt einen Wert, der angibt, ob die geordnete Form geschlossen ist. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Ruft den Endpunkt der Form ab.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Ruft den Startpunkt der Form ab.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Gibt einen Wert zurück, der angibt, ob die geordnete Form geschlossen ist. Beim Verarbeiten einer geschlossenen geordneten Form haben die Start- und Endpunkte keine Bedeutung.

**Returns:**
boolesch -  true  wenn diese geordnete Form geschlossen ist; andernfalls  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


Kehrt die Reihenfolge der Punkte für diese Form um.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Setzt einen Wert, der angibt, ob die geordnete Form geschlossen ist. Beim Verarbeiten einer geschlossenen geordneten Form haben die Start- und Endpunkte keine Bedeutung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | true  wenn diese geordnete Form geschlossen ist; andernfalls  false . |

