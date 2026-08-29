---
title: "IRasterImagePixelLoader"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Il caricatore di pixel raster."
type: docs
weight: 136
url: /it/java/com.aspose.psd/irasterimagepixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageRawDataLoader](../../com.aspose.psd/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

Il caricatore di pixel raster.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Carica i pixel parzialmente (a blocchi). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


Carica i pixel parzialmente (a blocchi).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo da cui caricare i pixel. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Il caricatore parziale. |

