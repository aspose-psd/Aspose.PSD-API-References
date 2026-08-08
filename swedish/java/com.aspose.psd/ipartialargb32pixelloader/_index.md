---
title: "IPartialArgb32PixelLoader"
second_title: "Aspose.PSD för Java API-referens"
description: "Uppfyller de 32‑bitars ARGB‑pixlarna som laddas delvis."
type: docs
weight: 130
url: /sv/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Uppfyller de 32‑bitars ARGB‑pixlarna som laddas delvis.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Bearbetar de inlästa pixlarna. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Bearbetar de inlästa pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Pixelrektangeln. |
| pixlar | int[] | Pixlarna i argb-format |
| start | [Point](../../com.aspose.psd/point) | Startpunkten för pixlarna. Om den inte är lika med (vänster,överkant) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](../../com.aspose.psd/point) | Slutpunkten för pixlarna. Om den inte är lika med (höger,nederkant) betyder det att vi inte har en fullständig rektangel. |

