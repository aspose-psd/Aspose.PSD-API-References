---
title: "LayerMaskData Κλάση"
type: docs
weight: 970
url: /el/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Summary:** Defines base LayerMaskData class which contains information about the layer mask data in the PSD file.<br/>            It can help to modify Adobe® Photoshop® files programmatically and automate PSD format editing.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            If the layer has both layer and vector masks the ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.<br/>            Notice, that just removing / adding / updating the LayerMaskData is not enough for correct saving<br/>            because channels are not updated; though it may provide correct rendering.<br/>            The [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) method should be used for that.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| bottom | int | r/w | Λαμβάνει ή ορίζει τη θέση του κάτω μάσκας στρώματος. |
| data_size | int | r | Λαμβάνει το μέγεθος των δεδομένων μάσκας στρώματος. |
| default_color | byte | r/w | Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Λαμβάνει ή ορίζει τις σημαίες της μάσκας στρώματος. |
| image_data | byte | r/w | Λαμβάνει ή ορίζει τα δεδομένα μάσκας στρώματος (ή συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD. |
| αριστερά | int | r/w | Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας στρώματος. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Λαμβάνει ή ορίζει τη μάσκα [Rectangle](/psd/python-net/aspose.psd/rectangle/) της μάσκας στρώματος στο αρχείο PSD.<br/>            Παίρνει τις ιδιότητες αριστερά, δεξιά, πάνω και κάτω και δημιουργεί [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| δεξιά | int | r/w | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας στρώματος. |
| επάνω | int | r/w | Λαμβάνει ή ορίζει τη θέση της πάνω μάσκας στρώματος. |


