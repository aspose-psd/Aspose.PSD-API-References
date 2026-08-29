---
title: "TiffStreamReader.ReadULongArray"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος TiffStreamReader. Διαβάζει έναν πίνακα μη υπογεγραμμένων ακεραίων τιμών από τη ροή"
type: docs
weight: 200
url: /el/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readulongarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadULongArray method

Διαβάζει έναν πίνακα τιμών μη υπογεγραμμένων ακεραίων από τη ροή.

```csharp
public uint[] ReadULongArray(long position, long count)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| θέση | Int64 | Η θέση από την οποία θα διαβαστεί. |
| πλήθος | Int64 | Ο αριθμός των στοιχείων. |

### Τιμή Επιστροφής

Ο πίνακας των μη υπογεγραμμένων ακεραίων τιμών.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentOutOfRangeException | count;Συνολικός αριθμός byte είναι αρνητικός. + count + x4= + totalBytes |

### Δείτε επίσης

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


