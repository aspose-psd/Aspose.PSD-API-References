---
title: "IRasterImagePixelLoader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο φορτωτής εικονοστοιχείων raster image."
type: docs
weight: 136
url: /el/java/com.aspose.psd/irasterimagepixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IRasterImageRawDataLoader](../../com.aspose.psd/irasterimagerawdataloader)
```
public interface IRasterImagePixelLoader extends IRasterImageRawDataLoader
```

Ο φορτωτής εικονοστοιχείων raster image.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Φορτώνει εικονοστοιχεία μερικώς (ανά μπλοκ). |
### loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public abstract void loadPartialPixels(Rectangle rectangle, IPartialPixelLoader partialPixelLoader)
```


Φορτώνει εικονοστοιχεία μερικώς (ανά μπλοκ).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |
| partialPixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Ο μερικός φορτωτής. |

