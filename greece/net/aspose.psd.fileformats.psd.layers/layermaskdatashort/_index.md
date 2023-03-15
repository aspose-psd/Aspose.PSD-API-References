---
title: Class LayerMaskDataShort
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort τάξη. Καθορίζει την κλάση LayerMaskDataShort που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο αρχείο PSD layer όταν το επίπεδο έχει μόνο μάσκα ράστερ ή διανύσματος αλλά όχι και τα δύο. Διαφορετικά αLayerMaskDataFull χρησιμοποιείται. Εάν το επίπεδο έχει μόνο μια μάσκα ράστερ το ImageData περιέχει τα byte δεδομένων μάσκας ράστερ. Εάν το επίπεδο έχει μόνο μια μάσκα διανύσματος το ImageData περιέχει τη διανυσματική μάσκα ραστεροποιημένη αποθηκευμένη byte δεδομένων. ImageDataΤο μήκος των byte πρέπει να είναι ίσο Πλάτος  Ύψος τουMaskRectangle ιδιότητες.
type: docs
weight: 2260
url: /el/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Καθορίζει την κλάση LayerMaskDataShort που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο αρχείο PSD layer όταν το επίπεδο έχει μόνο μάσκα ράστερ ή διανύσματος αλλά όχι και τα δύο. Διαφορετικά, α[`LayerMaskDataFull`](../layermaskdatafull/) χρησιμοποιείται. Εάν το επίπεδο έχει μόνο μια μάσκα ράστερ, το ImageData περιέχει τα byte δεδομένων μάσκας ράστερ. Εάν το επίπεδο έχει μόνο μια μάσκα διανύσματος, το ImageData περιέχει τη διανυσματική μάσκα ραστεροποιημένη (αποθηκευμένη) byte δεδομένων. [`ImageData`](../layermaskdata/imagedata/)Το μήκος των byte πρέπει να είναι ίσο Πλάτος * Ύψος του[`MaskRectangle`](../layermaskdata/maskrectangle/) ιδιότητες.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Λαμβάνει ή ρυθμίζει τη θέση της μάσκας κάτω στρώματος. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Λαμβάνει το μέγεθος των δεδομένων μάσκας στρώματος. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Παίρνει ή ορίζει το προεπιλεγμένο χρώμα. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Λαμβάνει ή ορίζει τις σημαίες μάσκας επιπέδου. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Λαμβάνει ή ορίζει τα δεδομένα μάσκας επιπέδου (ή συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Λαμβάνει ή ορίζει τη θέση μάσκας του αριστερού στρώματος. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Παίρνει ή ρυθμίζει τη μάσκα[`Rectangle`](../../aspose.psd/rectangle/)της μάσκας στρώματος στο αρχείο PSD. Παίρνει ιδιότητες αριστερά, δεξιά, πάνω και κάτω και δημιουργεί[`Rectangle`](../../aspose.psd/rectangle/) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Λαμβάνει ή ρυθμίζει τη μάσκα στρώματος. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Λαμβάνει ή ορίζει τη σωστή θέση μάσκας στρώσης. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Λαμβάνει ή ρυθμίζει τη θέση της μάσκας ανώτερης στρώσης. |

### Δείτε επίσης

* class [LayerMaskData](../layermaskdata/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* συνέλευση [Aspose.PSD](../../)


