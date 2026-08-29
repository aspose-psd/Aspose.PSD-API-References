---
title: "IPartialPixelLoader"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Entspricht den teilweise geladenen Pixeln."
type: docs
weight: 132
url: /de/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Entspricht den teilweise geladenen Pixeln.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Verarbeitet die geladenen Pixel. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Verarbeitet die geladenen Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Pixelrechteck. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Die Pixel. |
| start | [Point](../../com.aspose.psd/point) | Der Start-Pixelpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](../../com.aspose.psd/point) | Der End-Pixelpunkt. Wenn er nicht gleich (rechts,unten) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |

