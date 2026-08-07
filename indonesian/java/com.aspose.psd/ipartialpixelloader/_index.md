---
title: "IPartialPixelLoader"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mematuhi piksel yang dimuat sebagian."
type: docs
weight: 132
url: /id/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Mematuhi piksel yang dimuat sebagian.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Memproses piksel yang dimuat. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Memproses piksel yang dimuat.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Persegi panjang piksel. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Piksel. |
| start | [Point](../../com.aspose.psd/point) | Titik piksel awal. Jika tidak sama dengan (left,top) berarti bukan persegi panjang penuh yang kita miliki. |
| end | [Point](../../com.aspose.psd/point) | Titik piksel akhir. Jika tidak sama dengan (right,bottom) berarti bukan persegi panjang penuh yang kita miliki. |

