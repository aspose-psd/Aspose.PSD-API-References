---
title: "Κλάση LayerMaskDataFull"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull class. Ορίζει τη κλάση LayerMaskDataFull η οποία περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στη στρώση του αρχείου PSD όταν η στρώση έχει και raster και vector μάσκες. Διαφορετικά χρησιμοποιείται η LayerMaskDataShort. Το ImageData περιέχει τη raster μάσκα και τη rasterized vector μάσκα συνδυασμένα. Το μήκος των bytes του ImageData πρέπει να είναι ίσο με τις ιδιότητες MaskRectangle.Width  MaskRectangle.Height."
type: docs
weight: 2450
url: /el/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

Ορίζει τη κλάση LayerMaskDataFull η οποία περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στη στρώση του αρχείου PSD όταν η στρώση έχει και raster και vector μάσκες. Διαφορετικά, χρησιμοποιείται ένα [`LayerMaskDataShort`](../layermaskdatashort/). Το ImageData περιέχει τη raster μάσκα και τη rasterized vector μάσκα συνδυασμένα. Το μήκος των bytes του ImageData πρέπει να είναι ίσο με τις ιδιότητες MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Λαμβάνει ή ορίζει το χρώμα φόντου. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της κάτω μάσκας στρώσης. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Λαμβάνει το μέγεθος των δεδομένων μάσκας στρώσης. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της κάτω raster μάσκας που περιβάλλει τη στρώση εικόνας PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της αριστερής raster μάσκας που περιβάλλει τη στρώση του αρχείου PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της δεξιάς raster μάσκας που περιβάλλει τη στρώση του αρχείου PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της πάνω raster μάσκας που περιβάλλει τη στρώση εικόνας PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Λαμβάνει ή ορίζει τις σημαίες της μάσκας στρώσης. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Λαμβάνει ή ορίζει τα δεδομένα μάσκας στρώσης (ή τη συνδυασμένη / τελική μάσκα εάν υπάρχει vector μάσκα) στο αρχείο PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας στρώσης. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Λαμβάνει ή ορίζει το [`Rectangle`](../../aspose.psd/rectangle/) της μάσκας στρώσης στο αρχείο PSD. Παίρνει τις ιδιότητες left, right, top και bottom και δημιουργεί το [`Rectangle`](../../aspose.psd/rectangle/). |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Λαμβάνει ή ορίζει τις σημαίες της μάσκας στρώσης που χρησιμοποιούνται για τη μάσκα χρήστη / raster. Για τη vector μάσκα χρησιμοποιείται η ιδιότητα Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας στρώσης. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Λαμβάνει ή ορίζει τη θέση της πάνω μάσκας στρώσης. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Λαμβάνει ή ορίζει τα δεδομένα της μάσκας χρήστη (raster) μιας στρώσης στο αρχείο PSD. (Υπάρχει μια rasterized vector μάσκα στην ιδιότητα MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Λαμβάνει ή ορίζει το ορθογώνιο της μάσκας χρήστη (περιβάλλον) στη στρώση εικόνας PSD.. |

### Δείτε επίσης

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


