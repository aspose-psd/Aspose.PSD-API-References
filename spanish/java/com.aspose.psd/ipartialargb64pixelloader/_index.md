---
title: "IPartialArgb64PixelLoader"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El cargador de píxeles ARGB de 64 bits."
type: docs
weight: 131
url: /es/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

El cargador de píxeles ARGB de 64 bits.
## Métodos

| Método | Descripción |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Procesa los píxeles cargados. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Procesa los píxeles cargados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de píxeles. |
| píxeles | long[] | Los píxeles ARGB de 64 bits. |
| start | [Point](../../com.aspose.psd/point) | El punto de píxeles inicial. Si no es igual a (left,top) significa que no tenemos un rectángulo completo. |
| end | [Point](../../com.aspose.psd/point) | El punto de píxeles final. Si no es igual a (right,bottom) significa que no tenemos un rectángulo completo. |

