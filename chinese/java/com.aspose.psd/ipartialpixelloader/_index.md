---
title: "IPartialPixelLoader"
second_title: "Aspose.PSD 的 Java API 参考"
description: "符合部分加载的像素。"
type: docs
weight: 132
url: /zh/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

符合部分加载的像素。
## Methods

| Method | 描述 |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | 处理已加载的像素。 |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


处理已加载的像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 像素矩形。 |
| pixels | [Color\[\]](../../com.aspose.psd/color) | 像素。 |
| start | [Point](../../com.aspose.psd/point) | 起始像素点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| end | [Point](../../com.aspose.psd/point) | 结束像素点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

