---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ο χώρος ονομάτων περιέχει στρώματα μορφής αρχείου PSD"
type: docs
weight: 230
url: /el/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
Ο χώρος ονομάτων περιέχει στρώματα μορφής αρχείου PSD.

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | Η κλάση στρώματος artboard. |
| [BlendRange](./blendrange/) | Η περιοχή ανάμειξης. |
| [ChannelInformation](./channelinformation/) | Οι πληροφορίες καναλιού. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Η ενότητα γενικής μάσκας στρώσης. |
| [Layer](./layer/) | Η στρώση psd. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Τα δεδομένα περιοχών ανάμειξης στρώσης. |
| [LayerGroup](./layergroup/) | Κλάση ομάδας στρώσης |
| [LayerHashCalculator](./layerhashcalculator/) | Υπολογιστής κατακερματισμού για στρώσεις PSD. Μπορεί να χρησιμοποιηθεί για την εύρεση ίδιων ή διαφορετικών στρώσεων σε διαφορετικά αρχεία PSD. |
| [LayerMaskData](./layermaskdata/) | Ορίζει τη βασική κλάση LayerMaskData που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στρώσης στο αρχείο PSD. Μπορεί να βοηθήσει στην προγραμματιστική τροποποίηση αρχείων Adobe® Photoshop® και στην αυτοματοποίηση επεξεργασίας μορφής PSD. Εάν η στρώση έχει μόνο ραστρογραφική μάσκα, το ImageData περιέχει τα byte δεδομένων της ραστρογραφικής μάσκας. Εάν η στρώση έχει μόνο διανυσματική μάσκα, το ImageData περιέχει τα byte δεδομένων της διανυσματικής μάσκας που έχουν ραστεροποιηθεί (cached). Εάν η στρώση έχει και τις δύο, ραστρογραφική και διανυσματική μάσκα, το ImageData περιέχει τη ραστρογραφική μάσκα και τη ραστεροποιημένη διανυσματική μάσκα συνδυασμένα. Το μήκος των byte του [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) πρέπει να είναι ίσο με Πλάτος * Ύψος του [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) ιδιοτήτων. Σημειώστε ότι η απλή αφαίρεση / προσθήκη / ενημέρωση του LayerMaskData δεν αρκεί για σωστή αποθήκευση, επειδή τα κανάλια δεν ενημερώνονται· ωστόσο μπορεί να παρέχει σωστή απόδοση. Η μέθοδος [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) πρέπει να χρησιμοποιηθεί για αυτό. |
| [LayerMaskDataFull](./layermaskdatafull/) | Ορίζει τη κλάση LayerMaskDataFull που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στη στρώση αρχείου PSD όταν η στρώση έχει και ραστρογραφική και διανυσματική μάσκα. Διαφορετικά, χρησιμοποιείται ένα [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/). Το ImageData περιέχει τη ραστρογραφική μάσκα και τη ραστεροποιημένη διανυσματική μάσκα συνδυασμένα. Το μήκος των byte του ImageData πρέπει να είναι ίσο με τις ιδιότητες MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Ορίζει τη κλάση LayerMaskDataShort που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στη στρώση αρχείου PSD όταν η στρώση έχει μόνο ραστρογραφική ή διανυσματική μάσκα, αλλά όχι και τις δύο. Διαφορετικά, χρησιμοποιείται ένα [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/). Εάν η στρώση έχει μόνο ραστρογραφική μάσκα, το ImageData περιέχει τα byte δεδομένων της ραστρογραφικής μάσκας. Εάν η στρώση έχει μόνο διανυσματική μάσκα, το ImageData περιέχει τα byte δεδομένων της διανυσματικής μάσκας που έχουν ραστεροποιηθεί (cached). Το μήκος των byte του [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) πρέπει να είναι ίσο με Πλάτος * Ύψος των ιδιοτήτων του [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). |
| [LayerResource](./layerresource/) | Αναπαριστά πληροφορίες στρώσης. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Ορίστε το μητρώο πόρων στρώσης για τη φόρτωση αρχείων PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Κλάση διαχειριστή συνδεδεμένων στρώσεων. |
| [SectionDividerLayer](./sectiondividerlayer/) | Η στρώση διαχωριστή ενότητας για τον καθορισμό των ορίων του φακέλου (ομάδας στρώσεων). |
| [ShapeLayer](./shapelayer/) | Στρώση σχήματος. Συμπυκνώνει τη λογική εργασίας με τη στρώση σχήματος και τους σχετικούς πόρους. |
| [TextLayer](./textlayer/) | Η κλάση στρώσης κειμένου |
## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Βασική διεπαφή για ρυθμίσεις γεμίσματος |
| [ILayerResourceLoader](./ilayerresourceloader/) | Ο φορτωτής πόρων στρώσης. |
| [IShapeLayer](./ishapelayer/) | Περιγράφει τις ιδιότητες της στρώσης σχήματος. |
## Απαρίθμηση

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [LayerFlags](./layerflags/) | Οι σημαίες της στρώσης |
| [LayerMaskFlags](./layermaskflags/) | Οι σημαίες μάσκας στρώσης |


