---
title: "IPartialArgb32PixelLoader"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Voldoet aan de gedeeltelijk geladen 32-bit ARGB-pixels."
type: docs
weight: 130
url: /nl/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Voldoet aan de gedeeltelijk geladen 32-bit ARGB-pixels.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Verwerkt de geladen pixels. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Verwerkt de geladen pixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De pixels rechthoek. |
| pixels | int[] | De pixels in argb‑formaat |
| start | [Point](../../com.aspose.psd/point) | Het startpixelpunt. Als het niet gelijk is aan (left,top) betekent dat het geen volledige rechthoek is. |
| end | [Point](../../com.aspose.psd/point) | Het eindpixelpunt. Als het niet gelijk is aan (right,bottom) betekent dat het geen volledige rechthoek is. |

