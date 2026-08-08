---
title: "IPartialArgb32PixelLoader"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Cumple con los píxeles ARGB de 32 bits cargados parcialmente."
type: docs
weight: 130
url: /es/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Cumple con los píxeles ARGB de 32 bits cargados parcialmente.
## Métodos

| Método | Descripción |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Procesa los píxeles cargados. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Procesa los píxeles cargados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de píxeles. |
| píxeles | int[] | Los píxeles en formato argb |
| start | [Point](../../com.aspose.psd/point) | El punto de píxeles inicial. Si no es igual a (left,top) significa que no tenemos un rectángulo completo. |
| end | [Point](../../com.aspose.psd/point) | El punto de píxeles final. Si no es igual a (right,bottom) significa que no tenemos un rectángulo completo. |

