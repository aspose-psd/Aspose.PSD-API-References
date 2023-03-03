---
title: Class LayerMaskData
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData τάξη. Καθορίζει την βασική κλάση LayerMaskData που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας επιπέδου στο αρχείο PSD. Μπορεί να βοηθήσει στην τροποποίηση των αρχείων Adobe Photoshop μέσω προγραμματισμού και στην αυτοματοποίηση της επεξεργασίας μορφής PSD. Εάν το επίπεδο έχει μόνο μάσκα ράστερ το ImageData περιέχει το ράστερ μάσκα δεδομένων bytes. Εάν το επίπεδο έχει μόνο μια μάσκα διανύσματος το ImageData περιέχει τα byte δεδομένων με ραστεροποιημένα αποθηκευμένα μάσκα διανύσματος. Εάν το επίπεδο έχει και μάσκες επιπέδου και διανύσματος το ImageData περιέχει τη μάσκα ράστερ και τη μάσκα ραστεροποιημένου διανύσματος συνδυαστικά. οImageDataΤο μήκος των byte πρέπει να είναι ίσο Πλάτος  Ύψος τουMaskRectangle ιδιότητες. Σημειώστε ότι η απλή κατάργηση / προσθήκη / ενημέρωση των LayerMaskData δεν αρκεί για το σωστό saving επειδή τα κανάλια δεν ενημερώνονται. αν και μπορεί να παρέχει σωστή απόδοση. ΤοAddLayerMask θα πρέπει να χρησιμοποιηθεί μέθοδος για αυτό.
type: docs
weight: 2240
url: /el/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

Καθορίζει την βασική κλάση LayerMaskData που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας επιπέδου στο αρχείο PSD. Μπορεί να βοηθήσει στην τροποποίηση των αρχείων Adobe® Photoshop® μέσω προγραμματισμού και στην αυτοματοποίηση της επεξεργασίας μορφής PSD. Εάν το επίπεδο έχει μόνο μάσκα ράστερ, το ImageData περιέχει το ράστερ μάσκα δεδομένων bytes. Εάν το επίπεδο έχει μόνο μια μάσκα διανύσματος, το ImageData περιέχει τα byte δεδομένων με ραστεροποιημένα (αποθηκευμένα) μάσκα διανύσματος. Εάν το επίπεδο έχει και μάσκες επιπέδου και διανύσματος, το ImageData περιέχει τη μάσκα ράστερ και τη μάσκα ραστεροποιημένου διανύσματος συνδυαστικά. ο[`ImageData`](./imagedata/)Το μήκος των byte πρέπει να είναι ίσο Πλάτος * Ύψος του[`MaskRectangle`](./maskrectangle/) ιδιότητες. Σημειώστε ότι η απλή κατάργηση / προσθήκη / ενημέρωση των LayerMaskData δεν αρκεί για το σωστό saving επειδή τα κανάλια δεν ενημερώνονται. αν και μπορεί να παρέχει σωστή απόδοση. Το[`AddLayerMask`](../layer/addlayermask/) θα πρέπει να χρησιμοποιηθεί μέθοδος για αυτό.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Λαμβάνει ή ορίζει τη σωστή θέση μάσκας στρώσης. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Λαμβάνει ή ρυθμίζει τη θέση της μάσκας ανώτερης στρώσης. |

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* συνέλευση [Aspose.PSD](../../)


