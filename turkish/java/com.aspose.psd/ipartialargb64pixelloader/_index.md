---
title: "IPartialArgb64PixelLoader"
second_title: "Java için Aspose.PSD API Referansı"
description: "64-bit ARGB piksel yükleyicisi."
type: docs
weight: 131
url: /tr/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

64-bit ARGB piksel yükleyicisi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Yüklenen pikselleri işler. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Yüklenen pikselleri işler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksel dikdörtgeni. |
| piksel | long[] | 64 bit ARGB pikselleri. |
| start | [Point](../../com.aspose.psd/point) | Başlangıç piksel noktası. (left,top) ile eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |
| end | [Point](../../com.aspose.psd/point) | Bitiş piksel noktası. (right,bottom) ile eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |

