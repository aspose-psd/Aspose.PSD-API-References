---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Aspose.PSD για Αναφορά API .NET
description: Ο χώρος ονομάτων περιέχει επίπεδα μορφής αρχείου PSD.
type: docs
weight: 210
url: /el/net/aspose.psd.fileformats.psd.layers/
---
Ο χώρος ονομάτων περιέχει επίπεδα μορφής αρχείου PSD.

## Τάξεις

| Τάξη | Περιγραφή |
| --- | --- |
| [BlendRange](./blendrange/) | Το εύρος ανάμειξης. |
| [ChannelInformation](./channelinformation/) | Οι πληροφορίες καναλιού. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Η ενότητα μάσκας καθολικού επιπέδου. |
| [Layer](./layer/) | Το επίπεδο psd. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Δεδομένα σειρών ανάμειξης επιπέδων. |
| [LayerGroup](./layergroup/) | Κατηγορία επιπέδου ομάδας |
| [LayerHashCalculator](./layerhashcalculator/) | Υπολογιστής κατακερματισμού για επίπεδα PSD. Μπορεί να χρησιμοποιηθεί για την εύρεση ίσων ή διαφορετικών επιπέδων σε διαφορετικά αρχεία PSD |
| [LayerMaskData](./layermaskdata/) | Καθορίζει την βασική κλάση LayerMaskData που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας επιπέδου στο αρχείο PSD. Μπορεί να βοηθήσει στην τροποποίηση των αρχείων Adobe® Photoshop® μέσω προγραμματισμού και στην αυτοματοποίηση της επεξεργασίας μορφής PSD. Εάν το επίπεδο έχει μόνο μάσκα ράστερ, το ImageData περιέχει το ράστερ μάσκα δεδομένων bytes. Εάν το επίπεδο έχει μόνο μια μάσκα διανύσματος, το ImageData περιέχει τα byte δεδομένων με ραστεροποιημένα (αποθηκευμένα) μάσκα διανύσματος. Εάν το επίπεδο έχει και μάσκες επιπέδου και διανύσματος, το ImageData περιέχει τη μάσκα ράστερ και τη μάσκα ραστεροποιημένου διανύσματος συνδυαστικά. ο[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)Το μήκος των byte πρέπει να είναι ίσο Πλάτος * Ύψος του[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) ιδιότητες. Σημειώστε ότι η απλή κατάργηση / προσθήκη / ενημέρωση των LayerMaskData δεν αρκεί για το σωστό saving επειδή τα κανάλια δεν ενημερώνονται. αν και μπορεί να παρέχει σωστή απόδοση. Το[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) θα πρέπει να χρησιμοποιηθεί μέθοδος για αυτό. |
| [LayerMaskDataFull](./layermaskdatafull/) | Καθορίζει την κλάση LayerMaskDataFull η οποία περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο αρχείο PSD layer όταν το επίπεδο έχει μάσκες επιπέδων και διανυσμάτων. Διαφορετικά, α[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) χρησιμοποιείται. Το ImageData περιέχει τη μάσκα ράστερ και τη ραστεροποιημένη διανυσματική μάσκα συνδυαστικά. Το μήκος των byte ImageData πρέπει να είναι ίσο MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Καθορίζει την κλάση LayerMaskDataShort που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στο αρχείο PSD layer όταν το επίπεδο έχει μόνο μάσκα ράστερ ή διανύσματος αλλά όχι και τα δύο. Διαφορετικά, α[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) χρησιμοποιείται. Εάν το επίπεδο έχει μόνο μια μάσκα ράστερ, το ImageData περιέχει τα byte δεδομένων μάσκας ράστερ. Εάν το επίπεδο έχει μόνο μια μάσκα διανύσματος, το ImageData περιέχει τη διανυσματική μάσκα ραστεροποιημένη (αποθηκευμένη) byte δεδομένων. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)Το μήκος των byte πρέπει να είναι ίσο Πλάτος * Ύψος του[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) ιδιότητες. |
| [LayerResource](./layerresource/) | Αντιπροσωπεύει πληροφορίες επιπέδου. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Καθορίστε το μητρώο πόρων επιπέδου για τη φόρτωση αρχείων PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Κατηγορία διαχείρισης συνδεδεμένων επιπέδων. |
| [SectionDividerLayer](./sectiondividerlayer/) | Το επίπεδο διαιρέτη τομής για την επισήμανση των ορίων του φακέλου (ομάδα επιπέδων). |
| [TextLayer](./textlayer/) | Το επίπεδο κειμένου class |
## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Βασική διεπαφή για ρυθμίσεις πλήρωσης |
| [ILayerResourceLoader](./ilayerresourceloader/) | Ο φορτωτής πόρων επιπέδου. |
## Απαρίθμηση

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [LayerFlags](./layerflags/) | Το επίπεδο flags |
| [LayerMaskFlags](./layermaskflags/) | Η μάσκα στρώματος flags |


