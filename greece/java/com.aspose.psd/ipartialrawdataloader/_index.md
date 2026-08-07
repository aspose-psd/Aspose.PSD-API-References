---
title: "IPartialRawDataLoader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο φορτωτής μερικών δεδομένων."
type: docs
weight: 133
url: /el/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

Ο φορτωτής μερικών δεδομένων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Επεξεργάζεται τα φορτωμένα δεδομένα. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Επεξεργάζεται τα φορτωμένα δεδομένα. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Επεξεργάζεται τα φορτωμένα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο δεδομένων. |
| δεδομένα | byte[] | Τα ακατέργαστα δεδομένα. |
| start | [Point](../../com.aspose.psd/point) | Το σημείο εκκίνησης δεδομένων. Εάν δεν είναι ίσο με (left,top) σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |
| end | [Point](../../com.aspose.psd/point) | Το σημείο λήξης δεδομένων. Εάν δεν είναι ίσο με (right,bottom) σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Επεξεργάζεται τα φορτωμένα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο δεδομένων. |
| δεδομένα | byte[] | Τα ακατέργαστα δεδομένα. |
| start | [Point](../../com.aspose.psd/point) | Το σημείο εκκίνησης δεδομένων. Εάν δεν είναι ίσο με (left,top) σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |
| end | [Point](../../com.aspose.psd/point) | Το σημείο λήξης δεδομένων. Εάν δεν είναι ίσο με (right,bottom) σημαίνει ότι δεν έχουμε πλήρες ορθογώνιο. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Οι επιλογές φόρτωσης. |

