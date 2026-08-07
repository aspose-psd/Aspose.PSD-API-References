---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.PSD für Java API-Referenz"
description: "Der 64‑Bit‑ARGB‑Pixel‑Lader."
type: docs
weight: 131
url: /de/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Der 64‑Bit‑ARGB‑Pixel‑Lader.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Verarbeitet die geladenen Pixel. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Verarbeitet die geladenen Pixel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Das Pixelrechteck. |
| Pixel | long[] | Die 64-Bit-ARGB-Pixel. |
| start | [Point](../../com.aspose.psd/point) | Der Start-Pixelpunkt. Wenn er nicht gleich (links,oben) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |
| end | [Point](../../com.aspose.psd/point) | Der End-Pixelpunkt. Wenn er nicht gleich (rechts,unten) ist, bedeutet das, dass wir kein vollständiges Rechteck haben. |

