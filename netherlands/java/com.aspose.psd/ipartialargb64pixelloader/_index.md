---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De 64-bit ARGB-pixel lader."
type: docs
weight: 131
url: /nl/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

De 64-bit ARGB-pixel lader.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Verwerkt de geladen pixels. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Verwerkt de geladen pixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | De pixels rechthoek. |
| pixels | long[] | De 64‑bit ARGB-pixels. |
| start | [Point](../../com.aspose.psd/point) | Het startpixelpunt. Als het niet gelijk is aan (left,top) betekent dat het geen volledige rechthoek is. |
| end | [Point](../../com.aspose.psd/point) | Het eindpixelpunt. Als het niet gelijk is aan (right,bottom) betekent dat het geen volledige rechthoek is. |

