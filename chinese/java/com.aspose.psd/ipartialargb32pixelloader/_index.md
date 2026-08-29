---
title: "IPartialArgb32PixelLoader"
second_title: "Aspose.PSD 的 Java API 参考"
description: "符合部分加载的 32 位 ARGB 像素。"
type: docs
weight: 130
url: /zh/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

符合部分加载的 32 位 ARGB 像素。
## Methods

| Method | 描述 |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | 处理已加载的像素。 |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


处理已加载的像素。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | 像素矩形。 |
| 像素 | int[] | ARGB 格式的像素 |
| start | [Point](../../com.aspose.psd/point) | 起始像素点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| end | [Point](../../com.aspose.psd/point) | 结束像素点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

