---
title: "IOrderedShape"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Stelt een geordende vorm voor."
type: docs
weight: 129
url: /nl/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Stelt een geordende vorm voor. Een geordende vorm is een doorlopende reeks punten met een startpunt en eindpunt. De doorlopende reeks punten is verbonden met behulp van een specifieke regel.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Haalt het eindpunt van de vorm op. |
| [getStartPoint()](#getStartPoint--) | Haalt het startpunt van de vorm op. |
| [isClosed()](#isClosed--) | Haalt een waarde op die aangeeft of de geordende vorm gesloten is. |
| [reverse()](#reverse--) | Keert de volgorde van punten voor deze vorm om. |
| [setClosed(boolean value)](#setClosed-boolean-) | Stelt een waarde in die aangeeft of de geordende vorm gesloten is. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Haalt het eindpunt van de vorm op.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Haalt het startpunt van de vorm op.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Haalt een waarde op die aangeeft of de geordende vorm gesloten is. Bij het verwerken van een gesloten geordende vorm hebben het start- en eindpunt geen betekenis.

**Returns:**
boolean - true als deze geordende vorm gesloten is; anders false.
### reverse() {#reverse--}
```
public abstract void reverse()
```


Keert de volgorde van punten voor deze vorm om.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Stelt een waarde in die aangeeft of de geordende vorm gesloten is. Bij het verwerken van een gesloten geordende vorm hebben de begin- en eindpunten geen betekenis.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | true als deze geordende vorm gesloten is; anders false. |

