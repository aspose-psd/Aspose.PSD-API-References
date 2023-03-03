---
title: Class LayerMaskDataFull
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull τάξη. Καθορίζει την κλάση LayerMaskDataFull η οποία περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο αρχείο PSD layer όταν το επίπεδο έχει μάσκες επιπέδων και διανυσμάτων. Διαφορετικά αLayerMaskDataShort χρησιμοποιείται. Το ImageData περιέχει τη μάσκα ράστερ και τη ραστεροποιημένη διανυσματική μάσκα συνδυαστικά. Το μήκος των byte ImageData πρέπει να είναι ίσο MaskRectangle.Width  MaskRectangle.Height.
type: docs
weight: 2250
url: /el/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Καθορίζει την κλάση LayerMaskDataFull η οποία περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο αρχείο PSD layer όταν το επίπεδο έχει μάσκες επιπέδων και διανυσμάτων. Διαφορετικά, α[`LayerMaskDataShort`](../layermaskdatashort/) χρησιμοποιείται. Το ImageData περιέχει τη μάσκα ράστερ και τη ραστεροποιημένη διανυσματική μάσκα συνδυαστικά. Το μήκος των byte ImageData πρέπει να είναι ίσο MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Παίρνει ή ορίζει το χρώμα φόντου. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Λαμβάνει ή ρυθμίζει τη θέση της μάσκας κάτω στρώματος. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Λαμβάνει το μέγεθος των δεδομένων μάσκας στρώματος. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Παίρνει ή ορίζει το προεπιλεγμένο χρώμα. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Λαμβάνει ή ορίζει τη θέση μάσκας κάτω ράστερ που περικλείει στο επίπεδο εικόνας PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Λαμβάνει ή ορίζει τη θέση που περικλείει την αριστερή μάσκα ράστερ στο επίπεδο αρχείου PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Λαμβάνει ή ορίζει τη θέση που περικλείει τη δεξιά μάσκα ράστερ στο επίπεδο αρχείου PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Λαμβάνει ή ορίζει την επάνω θέση που περικλείει τη μάσκα ράστερ στο επίπεδο εικόνας PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Λαμβάνει ή ορίζει τις σημαίες μάσκας επιπέδου. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Λαμβάνει ή ορίζει τα δεδομένα μάσκας επιπέδου (ή συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Λαμβάνει ή ορίζει τη θέση μάσκας του αριστερού στρώματος. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Παίρνει ή ρυθμίζει τη μάσκα[`Rectangle`](../../aspose.psd/rectangle/)της μάσκας στρώματος στο αρχείο PSD. Παίρνει ιδιότητες αριστερά, δεξιά, πάνω και κάτω και δημιουργεί[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Λαμβάνει ή ορίζει τις σημαίες μάσκας επιπέδου που χρησιμοποιούνται για μάσκα χρήστη/ράστερ. Για διανυσματική μάσκα χρησιμοποιείται η ιδιότητα Flags. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Λαμβάνει ή ορίζει τη σωστή θέση μάσκας στρώσης. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Λαμβάνει ή ρυθμίζει τη θέση της μάσκας ανώτερης στρώσης. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Λαμβάνει ή ορίζει τα δεδομένα μάσκας χρήστη (raster) ενός επιπέδου στο αρχείο PSD. (Υπάρχει μια βαθμολογημένη διανυσματική μάσκα στην ιδιότητα MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Λαμβάνει ή ορίζει το ορθογώνιο μάσκας χρήστη (που περικλείει) στο επίπεδο εικόνας PSD.. |

### Δείτε επίσης

* class [LayerMaskData](../layermaskdata/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* συνέλευση [Aspose.PSD](../../)


