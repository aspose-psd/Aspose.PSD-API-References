---
title: "IPartialPixelLoader"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Voldoet aan de gedeeltelijk geladen pixels."
type: docs
weight: 132
url: /nl/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Voldoet aan de gedeeltelijk geladen pixels.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Verwerkt de geladen pixels. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Verwerkt de geladen pixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De pixels rechthoek. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | De pixels. |
| start | [Point](../../com.aspose.psd/point) | Het startpixelpunt. Als het niet gelijk is aan (left,top) betekent dat het geen volledige rechthoek is. |
| end | [Point](../../com.aspose.psd/point) | Het eindpixelpunt. Als het niet gelijk is aan (right,bottom) betekent dat het geen volledige rechthoek is. |

