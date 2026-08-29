---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "PsdColorPalette ιδιότητα. Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα είναι συμπαγής"
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

Λαμβάνει μια τιμή που υποδεικνύει εάν η παλέτα είναι συμπαγής.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` εάν η παλέτα είναι συμπαγής· διαφορετικά, `false`.

## Σχόλια

Η συμπαγής παλέτα σημαίνει ότι η εικόνα θα περιέχει μόνο τις καθορισμένες καταχωρίσεις παλέτας, εάν είναι δυνατόν· με άλλα λόγια, η εικόνα θα είναι πιο συμπαγής και θα καταλαμβάνει λιγότερο χώρο· διαφορετικά θα υπάρχουν καταχωρίσεις 2^BitsPerPixel και η εικόνα θα διατηρεί περισσότερο χώρο για όλες τις πιθανές καταχωρίσεις παλέτας. Ο ορισμός αυτής της τιμής σε true και η αλλαγή των καταχωρίσεων της παλέτας μπορεί να προκαλέσει ποινή απόδοσης, καθώς μπορεί να συμβεί μετακίνηση δεδομένων, γι' αυτό χρησιμοποιήστε το προσεκτικά.

### Δείτε επίσης

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


