---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.PSD för Java API-referens"
description: "Den 64‑bitars ARGB‑pixel‑läsaren."
type: docs
weight: 131
url: /sv/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Den 64‑bitars ARGB‑pixel‑läsaren.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Bearbetar de inlästa pixlarna. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Bearbetar de inlästa pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Pixelrektangeln. |
| pixlar | long[] | De 64-bitars ARGB-pixlarna. |
| start | [Point](../../com.aspose.psd/point) | Startpunkten för pixlarna. Om den inte är lika med (vänster,överkant) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](../../com.aspose.psd/point) | Slutpunkten för pixlarna. Om den inte är lika med (höger,nederkant) betyder det att vi inte har en fullständig rektangel. |

