---
title: "IRasterImagePixelLoader"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El cargador de píxeles de imagen raster."
type: docs
weight: 136
url: /es/java/com.aspose.psd/irasterimagepixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageRawDataLoader](../../com.aspose.psd/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

El cargador de píxeles de imagen raster.
## Métodos

| Método | Descripción |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Carga píxeles parcialmente (por bloques). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


Carga píxeles parcialmente (por bloques).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo desde el cual cargar los píxeles. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | El cargador parcial. |

