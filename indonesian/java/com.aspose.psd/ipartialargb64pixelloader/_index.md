---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Pemuat piksel ARGB 64-bit."
type: docs
weight: 131
url: /id/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Pemuat piksel ARGB 64-bit.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Memproses piksel yang dimuat. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Memproses piksel yang dimuat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang piksel. |
| piksel | long[] | Piksel ARGB 64-bit. |
| start | [Point](../../com.aspose.psd/point) | Titik piksel awal. Jika tidak sama dengan (left,top) berarti bukan persegi panjang penuh yang kita miliki. |
| end | [Point](../../com.aspose.psd/point) | Titik piksel akhir. Jika tidak sama dengan (right,bottom) berarti bukan persegi panjang penuh yang kita miliki. |

