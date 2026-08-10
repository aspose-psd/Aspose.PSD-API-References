---
title: "Κλάση LayerMaskDataShort"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort κλάση. Ορίζει την κλάση LayerMaskDataShort που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο επίπεδο αρχείου PSD όταν το επίπεδο έχει μόνο raster ή vector μάσκα αλλά όχι και τα δύο. Διαφορετικά χρησιμοποιείται μια LayerMaskDataFull. Εάν το επίπεδο έχει μόνο raster μάσκα, το ImageData περιέχει τα bytes των δεδομένων raster μάσκας. Εάν το επίπεδο έχει μόνο vector μάσκα, το ImageData περιέχει τα bytes των δεδομένων vector μάσκας που έχουν rasterized cached. Το μήκος των bytes του ImageData πρέπει να είναι ίσο με Width  Height των ιδιοτήτων MaskRectangle."
type: docs
weight: 2460
url: /el/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

Ορίζει την κλάση LayerMaskDataShort που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο επίπεδο αρχείου PSD όταν το επίπεδο έχει μόνο raster ή vector μάσκα αλλά όχι και τα δύο. Διαφορετικά, ένα [`LayerMaskDataFull`](../layermaskdatafull/) χρησιμοποιείται. Εάν το επίπεδο έχει μόνο raster μάσκα, το ImageData περιέχει τα bytes των δεδομένων raster μάσκας. Εάν το επίπεδο έχει μόνο vector μάσκα, το ImageData περιέχει τα bytes των δεδομένων vector μάσκας rasterized (cached). Το [`ImageData`](../layermaskdata/imagedata/) μήκος των bytes πρέπει να είναι ίσο με Width * Height του [`MaskRectangle`](../layermaskdata/maskrectangle/) ιδιοτήτων.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `LayerMaskDataShort`. |

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
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Λαμβάνει ή ορίζει το padding της μάσκας επιπέδου. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας στρώσης. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της πάνω μάσκας στρώσης. |

### Δείτε επίσης

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


