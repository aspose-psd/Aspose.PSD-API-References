---
title: "IPartialArgb32PixelLoader Κλάση"
type: docs
weight: 1910
url: /el/python-net/aspose.psd/ipartialargb32pixelloader/
---

**Summary:** Conforms to the 32-bit ARGB pixels loaded partially.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialArgb32PixelLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Επεξεργάζεται τα φορτωμένα pixel. |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Επεξεργάζεται τα φορτωμένα pixel.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο των pixel. |
| pixels | int | Τα 32-bit ARGB pixels. |
| start | [Point](/psd/python-net/aspose.psd/point) | Το σημείο εκκίνησης των pixel. Εάν δεν είναι ίσο με (left,top) σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |
| end | [Point](/psd/python-net/aspose.psd/point) | Το σημείο λήξης των pixel. Εάν δεν είναι ίσο με (right,bottom) σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |

