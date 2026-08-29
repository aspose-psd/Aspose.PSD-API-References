---
title: "IPartialArgb64PixelLoader"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Le chargeur de pixels ARGB 64 bits."
type: docs
weight: 131
url: /fr/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Le chargeur de pixels ARGB 64 bits.
## Méthodes

| Méthode | Description |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Traite les pixels chargés. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Traite les pixels chargés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des pixels. |
| pixels | long[] | Les pixels ARGB 64 bits. |
| start | [Point](../../com.aspose.psd/point) | Le point de départ des pixels. S'il n'est pas égal à (left,top) cela signifie que nous n'avons pas un rectangle complet. |
| end | [Point](../../com.aspose.psd/point) | Le point de fin des pixels. S'il n'est pas égal à (right,bottom) cela signifie que nous n'avons pas un rectangle complet. |

