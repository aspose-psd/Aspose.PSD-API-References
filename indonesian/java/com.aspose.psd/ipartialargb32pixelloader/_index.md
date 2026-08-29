---
title: "IPartialArgb32PixelLoader"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mematuhi piksel ARGB 32-bit yang dimuat sebagian."
type: docs
weight: 130
url: /id/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Mematuhi piksel ARGB 32-bit yang dimuat sebagian.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Memproses piksel yang dimuat. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Memproses piksel yang dimuat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang piksel. |
| piksel | int[] | Piksel dalam format argb |
| start | [Point](../../com.aspose.psd/point) | Titik piksel awal. Jika tidak sama dengan (left,top) berarti bukan persegi panjang penuh yang kita miliki. |
| end | [Point](../../com.aspose.psd/point) | Titik piksel akhir. Jika tidak sama dengan (right,bottom) berarti bukan persegi panjang penuh yang kita miliki. |

