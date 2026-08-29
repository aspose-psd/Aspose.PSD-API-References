---
title: "IRasterImagePixelLoader"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pemuat piksel raster image."
type: docs
weight: 136
url: /id/java/com.aspose.psd/irasterimagepixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageRawDataLoader](../../com.aspose.psd/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

Pemuat piksel raster image.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Memuat piksel secara parsial (per blok). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


Memuat piksel secara parsial (per blok).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang untuk memuat piksel dari. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Pemuat parsial. |

