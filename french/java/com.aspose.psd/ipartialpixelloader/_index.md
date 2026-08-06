---
title: "IPartialPixelLoader"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Conforme aux pixels chargés partiellement."
type: docs
weight: 132
url: /fr/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Conforme aux pixels chargés partiellement.
## Méthodes

| Méthode | Description |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Traite les pixels chargés. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Traite les pixels chargés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des pixels. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Les pixels. |
| start | [Point](../../com.aspose.psd/point) | Le point de départ des pixels. S'il n'est pas égal à (left,top) cela signifie que nous n'avons pas un rectangle complet. |
| end | [Point](../../com.aspose.psd/point) | Le point de fin des pixels. S'il n'est pas égal à (right,bottom) cela signifie que nous n'avons pas un rectangle complet. |

