---
title: "IColorPalette.IsCompactPalette"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "IColorPalette ιδιότητα. Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται συμπαγής παλέτα"
type: docs
weight: 40
url: /el/net/aspose.psd/icolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## IColorPalette.IsCompactPalette property

Λαμβάνει μια τιμή που υποδεικνύει εάν χρησιμοποιείται συμπαγής παλέτα.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` εάν χρησιμοποιείται η συμπαγής παλέτα· διαφορετικά, `false`.

## Σχόλια

Η συμπαγής παλέτα σημαίνει ότι η εικόνα θα περιέχει μόνο τις καθορισμένες καταχωρίσεις παλέτας, εάν είναι δυνατόν· με άλλα λόγια, η εικόνα θα είναι πιο συμπαγής και θα καταλαμβάνει λιγότερο χώρο· διαφορετικά θα υπάρχουν καταχωρίσεις 2^BitsPerPixel και η εικόνα θα διατηρεί περισσότερο χώρο για όλες τις πιθανές καταχωρίσεις παλέτας. Ο ορισμός αυτής της τιμής σε true και η αλλαγή των καταχωρίσεων της παλέτας μπορεί να προκαλέσει ποινή απόδοσης, καθώς μπορεί να συμβεί μετακίνηση δεδομένων, γι' αυτό χρησιμοποιήστε το προσεκτικά.

### Δείτε επίσης

* interface [IColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


