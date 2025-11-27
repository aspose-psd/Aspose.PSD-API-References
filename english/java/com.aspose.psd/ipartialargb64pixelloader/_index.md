---
title: IPartialArgb64PixelLoader
second_title: Aspose.PSD for Java API Reference
description: The 64-bit ARGB pixels loader.
type: docs
weight: 131
url: /java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

The 64-bit ARGB pixels loader.
## Methods

| Method | Description |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Processes the loaded pixels. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Processes the loaded pixels.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | The pixels rectangle. |
| pixels | long[] | The 64-bit ARGB pixels. |
| start | [Point](../../com.aspose.psd/point) | The start pixels point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](../../com.aspose.psd/point) | The end pixels point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

