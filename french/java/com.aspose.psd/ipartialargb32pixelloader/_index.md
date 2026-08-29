---
title: "IPartialArgb32PixelLoader"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Conforme aux pixels ARGB 32 bits chargés partiellement."
type: docs
weight: 130
url: /fr/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Conforme aux pixels ARGB 32 bits chargés partiellement.
## Méthodes

| Méthode | Description |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Traite les pixels chargés. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Traite les pixels chargés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des pixels. |
| pixels | int[] | Les pixels au format argb |
| start | [Point](../../com.aspose.psd/point) | Le point de départ des pixels. S'il n'est pas égal à (left,top) cela signifie que nous n'avons pas un rectangle complet. |
| end | [Point](../../com.aspose.psd/point) | Le point de fin des pixels. S'il n'est pas égal à (right,bottom) cela signifie que nous n'avons pas un rectangle complet. |

