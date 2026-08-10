---
title: "TiffOptions.ColorMap"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα TiffOptions. Λαμβάνει ή ορίζει το χάρτη χρωμάτων"
type: docs
weight: 70
url: /el/net/aspose.psd.imageoptions/tiffoptions/colormap/
---
{{< psd/tize >}}
## TiffOptions.ColorMap property

Λαμβάνει ή ορίζει το χάρτη χρωμάτων.

```csharp
public ushort[] ColorMap { get; set; }
```

### Property Value

Ο χάρτης χρωμάτων.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| ArgumentNullException | τιμή |
| [TiffImageException](../../../aspose.psd.coreexceptions.imageformats/tiffimageexception/) | Ο χάρτης χρωμάτων μπορεί να οριστεί μόνο για δείγματα ανά εικονοστοιχείο ίσα με 1. ή Τα bits ανά δείγμα δεν ορίζονται. |
| ArgumentOutOfRangeException | τιμή;Το μήκος του πίνακα πρέπει να αντιστοιχεί στον ακόλουθο τύπο: 3 * (2**BitsPerSample). |

### Δείτε επίσης

* class [TiffOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


