---
title: IPartialPixelLoader
second_title: Aspose.PSD for Java API Reference
description: Conforms to the pixels loaded partially.
type: docs
weight: 133
url: /java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Conforms to the pixels loaded partially.
## Methods

| Method | Description |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Processes the loaded pixels. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Processes the loaded pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The pixels rectangle. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | The pixels. |
| start | [Point](../../com.aspose.psd/point) | The start pixels point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.psd/point) | The end pixels point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

