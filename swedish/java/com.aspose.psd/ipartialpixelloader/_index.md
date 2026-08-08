---
title: "IPartialPixelLoader"
second_title: "Aspose.PSD för Java API-referens"
description: "Uppfyller pixlarna som laddas delvis."
type: docs
weight: 132
url: /sv/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Uppfyller pixlarna som laddas delvis.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Bearbetar de inlästa pixlarna. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Bearbetar de inlästa pixlarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Pixelrektangeln. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Pixlarna. |
| start | [Point](../../com.aspose.psd/point) | Startpunkten för pixlarna. Om den inte är lika med (vänster,överkant) betyder det att vi inte har en fullständig rektangel. |
| end | [Point](../../com.aspose.psd/point) | Slutpunkten för pixlarna. Om den inte är lika med (höger,nederkant) betyder det att vi inte har en fullständig rektangel. |

