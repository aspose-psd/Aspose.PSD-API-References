---
title: "IPartialPixelLoader"
second_title: "Java için Aspose.PSD API Referansı"
description: "Kısmen yüklenen piksellere uyar."
type: docs
weight: 132
url: /tr/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Kısmen yüklenen piksellere uyar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Yüklenen pikselleri işler. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Yüklenen pikselleri işler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Piksel dikdörtgeni. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Piksel. |
| start | [Point](../../com.aspose.psd/point) | Başlangıç piksel noktası. (left,top) ile eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |
| end | [Point](../../com.aspose.psd/point) | Bitiş piksel noktası. (right,bottom) ile eşit değilse, bunun tam bir dikdörtgen olmadığını ifade eder. |

