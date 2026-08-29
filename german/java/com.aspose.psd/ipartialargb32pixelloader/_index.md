---
title: "IPartialArgb32PixelLoader"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Entspricht den teilweise geladenen 32‑Bit‑ARGB‑Pixeln."
type: docs
weight: 130
url: /de/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Entspricht den teilweise geladenen 32‑Bit‑ARGB‑Pixeln.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Verarbeitet die geladenen Pixel. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Verarbeitet die geladenen Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Pixelrechteck. |
| Pixel | int[] | Die Pixel im ARGB-Format. |
| start | [Point](../../com.aspose.psd/point) | Der Start-Pixelpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](../../com.aspose.psd/point) | Der End-Pixelpunkt. Wenn er nicht gleich (rechts,unten) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |

