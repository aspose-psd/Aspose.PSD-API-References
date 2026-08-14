---
title: "IRasterImagePixelLoader Κλάση"
type: docs
weight: 2010
url: /el/python-net/aspose.psd/irasterimagepixelloader/
---

**Summary:** The raster image pixel loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImagePixelLoader

**Inheritance:** IRasterImageRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| διατίθεται_ακατέργαστα_δεδομένα | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν υποστηρίζεται η φόρτωση ακατέργαστων δεδομένων. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Λαμβάνει τις τρέχουσες ρυθμίσεις ακατέργαστων δεδομένων. Σημειώστε ότι όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή. |
## **Methods**
| **Name** | **Περιγραφή** |
| :- | :- |
| [load_partial_pixels(rectangle, partial_pixel_loader)](#load_partial_pixels_rectangle_partial_pixel_loader_1) | Φορτώνει εικονοστοιχεία μερικώς (ανά μπλοκ). |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2) | Φορτώνει ακατέργαστα δεδομένα. |


### Method: load_partial_pixels(rectangle, partial_pixel_loader) {#load_partial_pixels_rectangle_partial_pixel_loader_1}


```
 load_partial_pixels(rectangle, partial_pixel_loader) 
```

Φορτώνει εικονοστοιχεία μερικώς (ανά μπλοκ).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα pixel. |
| partial_pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Ο μερικός φορτωτής pixel. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Φορτώνει ακατέργαστα δεδομένα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν τα ακατέργαστα δεδομένα. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων για χρήση με τα φορτωμένα δεδομένα. Σημειώστε ότι εάν τα δεδομένα δεν είναι στη μορφή που έχει οριστεί, θα πραγματοποιηθεί μετατροπή δεδομένων. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Ο φορτωτής ακατέργαστων δεδομένων. |

