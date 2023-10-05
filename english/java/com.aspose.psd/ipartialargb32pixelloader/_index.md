---
title: IPartialArgb32PixelLoader
second_title: Aspose.PSD for Java API Reference
description: Conforms to the 32-bit ARGB pixels loaded partially.
type: docs
weight: 131
url: /java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Conforms to the 32-bit ARGB pixels loaded partially.
## Methods

| Method | Description |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Processes the loaded pixels. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Processes the loaded pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The pixels rectangle. |
| pixels | int[] | The pixels in argb format |
| start | [Point](../../com.aspose.psd/point) | The start pixels point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.psd/point) | The end pixels point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

