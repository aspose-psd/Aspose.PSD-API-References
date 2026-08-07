---
title: "IRasterImageArgb32PixelLoader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο φορτωτής εικονοστοιχείων raster image 32-bit ARGB."
type: docs
weight: 135
url: /el/java/com.aspose.psd/irasterimageargb32pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageRawDataLoader](../../com.aspose.psd/irasterimagerawdataloader)
```
public interface IRasterImageArgb32PixelLoader extends IRasterImageRawDataLoader
```

Ο φορτωτής εικονοστοιχείων raster image 32-bit ARGB.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Φορτώνει εικονοστοιχεία 32-bit ARGB μερικώς (ανά μπλοκ). |
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public abstract void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Φορτώνει εικονοστοιχεία 32-bit ARGB μερικώς (ανά μπλοκ).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Ο μερικός φορτωτής pixel. |

