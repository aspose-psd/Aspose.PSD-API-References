---
title: "IRasterImageRawDataLoader"
second_title: "Aspose.PSD for Java API Αναφορά"
description: "Ο φορτωτής ακατέργαστων δεδομένων raster image."
type: docs
weight: 137
url: /el/java/com.aspose.psd/irasterimagerawdataloader/
---
```
public interface IRasterImageRawDataLoader
```

Ο φορτωτής ακατέργαστων δεδομένων raster image.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getRawDataSettings()](#getRawDataSettings--) | Λαμβάνει τις τρέχουσες ρυθμίσεις ακατέργαστων δεδομένων. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Λαμβάνει μια τιμή που υποδεικνύει εάν υποστηρίζεται η φόρτωση ακατέργαστων δεδομένων. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Φορτώνει ακατέργαστα δεδομένα. |
### getRawDataSettings() {#getRawDataSettings--}
```
public abstract RawDataSettings getRawDataSettings()
```


Λαμβάνει τις τρέχουσες ρυθμίσεις ακατέργαστων δεδομένων. Σημειώστε ότι όταν χρησιμοποιείτε αυτές τις ρυθμίσεις, τα δεδομένα φορτώνονται χωρίς μετατροπή.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings) - The current raw data settings.
### isRawDataAvailable() {#isRawDataAvailable--}
```
public abstract boolean isRawDataAvailable()
```


Λαμβάνει μια τιμή που υποδεικνύει εάν υποστηρίζεται η φόρτωση ακατέργαστων δεδομένων.

**Returns:**
boolean -  true  εάν υποστηρίζεται η φόρτωση ακατέργαστων δεδομένων· διαφορετικά,  false .
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public abstract void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Φορτώνει ακατέργαστα δεδομένα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Το ορθογώνιο από το οποίο θα φορτωθούν ακατέργαστα δεδομένα. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Οι ρυθμίσεις ακατέργαστων δεδομένων για χρήση με τα φορτωμένα δεδομένα. Σημειώστε ότι εάν τα δεδομένα δεν είναι στη συγκεκριμένη μορφή, θα γίνει μετατροπή δεδομένων. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Ο φορτωτής ακατέργαστων δεδομένων. |

