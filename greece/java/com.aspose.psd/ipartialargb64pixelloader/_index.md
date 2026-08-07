---
title: "IPartialArgb64PixelLoader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο φορτωτής 64-bit ARGB pixel."
type: docs
weight: 131
url: /el/java/com.aspose.psd/ipartialargb64pixelloader/
---

**All Implemented Interfaces:**
[com.aspose.psd.IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
```
public interface IPartialArgb64PixelLoader extends IPartialArgb32PixelLoader
```

Ο φορτωτής 64-bit ARGB pixel.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)](#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-) | Επεξεργάζεται τα φορτωμένα pixel. |
### process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end) {#process64-com.aspose.psd.Rectangle-long---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process64(Rectangle pixelsRectangle, long[] pixels, Point start, Point end)
```


Επεξεργάζεται τα φορτωμένα pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο των pixel. |
| pixels | long[] | Τα 64-bit ARGB pixel. |
| start | [Point](../../com.aspose.psd/point) | Το σημείο εκκίνησης των pixel. Αν δεν είναι ίσο με (αριστερά,πάνω), σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |
| end | [Point](../../com.aspose.psd/point) | Το σημείο λήξης των pixel. Αν δεν είναι ίσο με (δεξιά,κάτω), σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |

