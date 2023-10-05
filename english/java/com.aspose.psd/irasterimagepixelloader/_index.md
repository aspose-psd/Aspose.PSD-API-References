---
title: IRasterImagePixelLoader
second_title: Aspose.PSD for Java API Reference
description: The raster image pixel loader.
type: docs
weight: 137
url: /java/com.aspose.psd/irasterimagepixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageRawDataLoader](../../com.aspose.psd/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

The raster image pixel loader.
## Methods

| Method | Description |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Loads pixels partially (by blocks). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


Loads pixels partially (by blocks).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | The rectangle to load pixels from. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | The partial loader. |

