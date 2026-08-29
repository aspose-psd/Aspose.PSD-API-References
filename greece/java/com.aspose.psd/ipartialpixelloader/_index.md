---
title: "IPartialPixelLoader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Συμμορφώνεται με τα pixel που φορτώνονται εν μέρει."
type: docs
weight: 132
url: /el/java/com.aspose.psd/ipartialpixelloader/
---
```
public interface IPartialPixelLoader
```

Συμμορφώνεται με τα pixel που φορτώνονται εν μέρει.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-) | Επεξεργάζεται τα φορτωμένα pixel. |
### process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-com.aspose.psd.Color---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, Color[] pixels, Point start, Point end)
```


Επεξεργάζεται τα φορτωμένα pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο των pixel. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Τα pixel. |
| start | [Point](../../com.aspose.psd/point) | Το σημείο εκκίνησης των pixel. Αν δεν είναι ίσο με (αριστερά,πάνω), σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |
| end | [Point](../../com.aspose.psd/point) | Το σημείο λήξης των pixel. Αν δεν είναι ίσο με (δεξιά,κάτω), σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |

