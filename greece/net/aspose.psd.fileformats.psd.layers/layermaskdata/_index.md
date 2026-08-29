---
title: "Κλάση LayerMaskData"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData class. Ορίζει τη βασική κλάση LayerMaskData η οποία περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στρώσης στο αρχείο PSD. Μπορεί να βοηθήσει στην προγραμματιστική τροποποίηση αρχείων Adobe Photoshop και στην αυτοματοποίηση επεξεργασίας μορφής PSD. Εάν η στρώση έχει μόνο μια raster μάσκα, το ImageData περιέχει τα bytes των δεδομένων της raster μάσκας. Εάν η στρώση έχει μόνο μια vector μάσκα, το ImageData περιέχει τα bytes των δεδομένων της vector μάσκας που έχουν αποθηκευτεί στην cache. Εάν η στρώση έχει και raster και vector μάσκες, το ImageData περιέχει τη raster μάσκα και τη rasterized vector μάσκα συνδυασμένα. Το μήκος των bytes του ImageData πρέπει να είναι ίσο με Width  Height των ιδιοτήτων MaskRectangle. Σημειώστε ότι η απλή αφαίρεση / προσθήκη / ενημέρωση του LayerMaskData δεν είναι αρκετή για σωστή αποθήκευση, επειδή τα κανάλια δεν ενημερώνονται, αν και μπορεί να παρέχει σωστή απόδοση. Η μέθοδος AddLayerMask πρέπει να χρησιμοποιηθεί για αυτό."
type: docs
weight: 2440
url: /el/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

Ορίζει τη βασική κλάση LayerMaskData η οποία περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στρώσης στο αρχείο PSD. Μπορεί να βοηθήσει στην προγραμματιστική τροποποίηση αρχείων Adobe® Photoshop® και στην αυτοματοποίηση επεξεργασίας μορφής PSD. Εάν η στρώση έχει μόνο μια raster μάσκα, το ImageData περιέχει τα bytes των δεδομένων της raster μάσκας. Εάν η στρώση έχει μόνο μια vector μάσκα, το ImageData περιέχει τα bytes των δεδομένων της vector μάσκας που έχουν rasterized (cached). Εάν η στρώση έχει και raster και vector μάσκες, το ImageData περιέχει τη raster μάσκα και τη rasterized vector μάσκα συνδυασμένα. Τα bytes του [`ImageData`](./imagedata/) πρέπει να έχουν μήκος ίσο με Width * Height των ιδιοτήτων [`MaskRectangle`](./maskrectangle/). Σημειώστε ότι η απλή αφαίρεση / προσθήκη / ενημέρωση του LayerMaskData δεν είναι αρκετή για σωστή αποθήκευση, επειδή τα κανάλια δεν ενημερώνονται· αν και μπορεί να παρέχει σωστή απόδοση. Η μέθοδος [`AddLayerMask`](../layer/addlayermask/) πρέπει να χρησιμοποιηθεί για αυτό.

```csharp
public abstract class LayerMaskData
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της κάτω μάσκας στρώσης. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Λαμβάνει το μέγεθος των δεδομένων μάσκας στρώσης. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Λαμβάνει ή ορίζει τις σημαίες της μάσκας στρώσης. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Λαμβάνει ή ορίζει τα δεδομένα μάσκας στρώσης (ή τη συνδυασμένη / τελική μάσκα εάν υπάρχει vector μάσκα) στο αρχείο PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας στρώσης. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Λαμβάνει ή ορίζει το [`Rectangle`](../../aspose.psd/rectangle/) της μάσκας στρώσης στο αρχείο PSD. Παίρνει τις ιδιότητες left, right, top και bottom και δημιουργεί το [`Rectangle`](../../aspose.psd/rectangle/). |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας στρώσης. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της πάνω μάσκας στρώσης. |

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


