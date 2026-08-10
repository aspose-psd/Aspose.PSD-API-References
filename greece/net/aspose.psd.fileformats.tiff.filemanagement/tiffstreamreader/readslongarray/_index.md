---
title: "TiffStreamReader.ReadSLongArray"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "TiffStreamReader μέθοδος. Διαβάζει έναν πίνακα υπογεγραμμένων τιμών ακέραιου από τη ροή."
type: docs
weight: 140
url: /el/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readslongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadSLongArray method

Διαβάζει έναν πίνακα τιμών υπογεγραμμένων ακεραίων από τη ροή.

```csharp
public int[] ReadSLongArray(long position, long count)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| θέση | Int64 | Η θέση από την οποία θα διαβαστεί. |
| πλήθος | Int64 | Ο αριθμός των στοιχείων. |

### Τιμή Επιστροφής

Ο πίνακας των υπογεγραμμένων τιμών ακέραιου.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | count;Συνολικός αριθμός byte είναι αρνητικός. + count + x4= + totalBytes |

### Δείτε επίσης

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


