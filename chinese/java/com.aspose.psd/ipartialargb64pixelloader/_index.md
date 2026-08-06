---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.PSD 的 Java API 参考"
description: "64 位 ARGB 像素加载器。"
type: docs
weight: 131
url: /zh/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

64 位 ARGB 像素加载器。
## Methods

| Method | 描述 |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | 处理已加载的像素。 |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


处理已加载的像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 像素矩形。 |
| 像素 | long[] | 64 位 ARGB 像素。 |
| start | [Point](../../com.aspose.psd/point) | 起始像素点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| end | [Point](../../com.aspose.psd/point) | 结束像素点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

