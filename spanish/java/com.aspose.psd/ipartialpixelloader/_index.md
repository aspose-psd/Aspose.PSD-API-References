---
title: "IPartialPixelLoader"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Cumple con los píxeles cargados parcialmente."
type: docs
weight: 132
url: /es/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Cumple con los píxeles cargados parcialmente.
## Métodos

| Método | Descripción |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Procesa los píxeles cargados. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Procesa los píxeles cargados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de píxeles. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Los píxeles. |
| start | [Point](../../com.aspose.psd/point) | El punto de píxeles inicial. Si no es igual a (left,top) significa que no tenemos un rectángulo completo. |
| end | [Point](../../com.aspose.psd/point) | El punto de píxeles final. Si no es igual a (right,bottom) significa que no tenemos un rectángulo completo. |

