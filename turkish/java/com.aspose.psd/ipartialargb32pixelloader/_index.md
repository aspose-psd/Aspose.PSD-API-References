---
title: "IPartialArgb32PixelLoader"
second_title: "Java için Aspose.PSD API Referansı"
description: "Kısmen yüklenen 32-bit ARGB piksellerine uyar."
type: docs
weight: 130
url: /tr/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Kısmen yüklenen 32-bit ARGB piksellerine uyar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Yüklenen pikselleri işler. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Yüklenen pikselleri işler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksel dikdörtgeni. |
| piksel | int[] | ARGB formatındaki pikseller |
| start | [Point](../../com.aspose.psd/point) | Başlangıç piksel noktası. (left,top) ile eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |
| end | [Point](../../com.aspose.psd/point) | Bitiş piksel noktası. (right,bottom) ile eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |

