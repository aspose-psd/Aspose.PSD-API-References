---
title: "IPartialArgb32PixelLoader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Συμμορφώνεται με τα 32-bit ARGB pixel που φορτώνονται εν μέρει."
type: docs
weight: 130
url: /el/java/com.aspose.psd/ipartialargb32pixelloader/
---
```
public interface IPartialArgb32PixelLoader
```

Συμμορφώνεται με τα 32-bit ARGB pixel που φορτώνονται εν μέρει.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Επεξεργάζεται τα φορτωμένα pixel. |
### process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#process-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Επεξεργάζεται τα φορτωμένα pixel.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο των pixel. |
| pixels | int[] | Τα pixel σε μορφή ARGB |
| start | [Point](../../com.aspose.psd/point) | Το σημείο εκκίνησης των pixel. Αν δεν είναι ίσο με (αριστερά,πάνω), σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |
| end | [Point](../../com.aspose.psd/point) | Το σημείο λήξης των pixel. Αν δεν είναι ίσο με (δεξιά,κάτω), σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |

