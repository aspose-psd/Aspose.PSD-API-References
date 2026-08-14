---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /el/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Κλάση** | **Περιγραφή** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | Η κλάση στρώσης artboard. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | Η περιοχή ανάμειξης. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | Οι πληροφορίες καναλιού. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | Η ενότητα μάσκας παγκόσμιου στρώματος. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Βασική διεπαφή για ρυθμίσεις γεμίσματος |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | Ο φορτωτής πόρων στρώσης. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Περιγράφει τις ιδιότητες της στρώσης Shape. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Η στρώση psd. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | Τα δεδομένα περιοχών ανάμειξης στρώσης. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Κλάση ομάδας στρώσης |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | Υπολογιστής κατακερματισμού για στρώσεις PSD. Μπορεί να χρησιμοποιηθεί για την εύρεση ίδιων ή διαφορετικών στρώσεων σε διαφορετικά αρχεία PSD. |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | Ορίζει τη βασική κλάση LayerMaskData που περιέχει πληροφορίες σχετικά με τα δεδομένα μάσκας στρώσης στο αρχείο PSD.<br/>            Μπορεί να βοηθήσει στην προγραμματιστική τροποποίηση αρχείων Adobe® Photoshop® και στην αυτοματοποίηση επεξεργασίας μορφής PSD.<br/>            Εάν η στρώση έχει μόνο μια ραστερ μάσκα, το ImageData περιέχει τα byte δεδομένων της ραστερ μάσκας.<br/>            Εάν η στρώση έχει μόνο μια διανυσματική μάσκα, το ImageData περιέχει τα byte δεδομένων της διανυσματικής μάσκας που έχουν ραστεροποιηθεί (cached).<br/>            Εάν η στρώση έχει και τις δύο, στρώση και διανυσματικές μάσκες, το ImageData περιέχει τη ραστερ μάσκα και τη ραστεροποιημένη διανυσματική μάσκα συνδυασμένα.<br/>            Τα bytes του [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) πρέπει να είναι ίσα με Πλάτος * Ύψος των ιδιοτήτων [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/).<br/>            Σημειώστε ότι η απλή αφαίρεση / προσθήκη / ενημέρωση του LayerMaskData δεν αρκεί για σωστή αποθήκευση<br/>            επειδή τα κανάλια δεν ενημερώνονται· ωστόσο μπορεί να παρέχει σωστή απόδοση.<br/>            Η μέθοδος [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) πρέπει να χρησιμοποιηθεί για αυτό. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | Ορίζει τη κλάση LayerMaskDataFull που περιέχει πληροφορίες για τα δεδομένα μάσκας στη στρώση αρχείου PSD<br/>            όταν η στρώση έχει και στρώση και διανυσματικές μάσκες. Διαφορετικά, χρησιμοποιείται ένα [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/).<br/>            Το ImageData περιέχει τη ραστερ μάσκα και τη ραστεροποιημένη διανυσματική μάσκα συνδυασμένα.<br/>            Το μήκος των bytes του ImageData πρέπει να είναι ίσο με τις ιδιότητες MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | Ορίζει τη κλάση LayerMaskDataShort που περιέχει πληροφορίες για τα δεδομένα μάσκας στη στρώση αρχείου PSD<br/>            όταν η στρώση έχει μόνο ραστερ ή διανυσματική μάσκα αλλά όχι και τις δύο. Διαφορετικά, χρησιμοποιείται ένα [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/).<br/>            Εάν η στρώση έχει μόνο ραστερ μάσκα, το ImageData περιέχει τα byte δεδομένων της ραστερ μάσκας.<br/>            Εάν η στρώση έχει μόνο διανυσματική μάσκα, το ImageData περιέχει τα byte δεδομένων της διανυσματικής μάσκας που έχουν ραστεροποιηθεί (cached).<br/>            Τα bytes του [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) πρέπει να είναι ίσα με Πλάτος * Ύψος των ιδιοτήτων [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/). |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Αναπαριστά πληροφορίες στρώσης. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | Ορίστε το μητρώο πόρων στρώσης για τη φόρτωση αρχείων PSD. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Κλάση διαχειριστή συνδεδεμένων στρώσεων. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | Η στρώση διαχωριστή ενότητας για την επισήμανση των ορίων του φακέλου (ομάδας στρώσεων). |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Στρώση Shape. Περιλαμβάνει τη λογική εργασίας με τη στρώση Shape και τους σχετικούς πόρους. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Η κλάση στρώσης κειμένου |
## **Enumerations**
| **Enumeration** | **Περιγραφή** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | Οι σημαίες της στρώσης |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | Οι σημαίες μάσκας στρώσης |
