---
title: "IOrderedShape"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en ordnad form."
type: docs
weight: 129
url: /sv/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Representerar en ordnad form. En ordnad form är en kontinuerlig uppsättning punkter som har en startpunkt och en slutpunkt. Den kontinuerliga uppsättningen av punkter är kopplad med en specifik regel.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Hämtar den avslutande formpunkten. |
| [getStartPoint()](#getStartPoint--) | Hämtar startpunkten för formen. |
| [isClosed()](#isClosed--) | Hämtar ett värde som indikerar om den ordnade formen är sluten. |
| [reverse()](#reverse--) | Vänder ordningen på punkterna för denna form. |
| [setClosed(boolean value)](#setClosed-boolean-) | Ställer in ett värde som indikerar om den ordnade formen är sluten. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Hämtar den avslutande formpunkten.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Hämtar startpunkten för formen.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Hämtar ett värde som indikerar om den ordnade formen är sluten. Vid bearbetning av en sluten ordnad form har start- och slutpunkterna ingen betydelse.

**Returns:**
boolean -  true  om den här ordnade formen är sluten; annars,  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


Vänder ordningen på punkterna för denna form.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Ställer in ett värde som indikerar om den ordnade formen är sluten. Vid bearbetning av en sluten ordnad form har start- och slutpunkterna ingen betydelse.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true  om den här ordnade formen är sluten; annars,  false . |

