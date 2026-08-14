---
title: "LayerMaskDataShort Κλάση"
type: docs
weight: 990
url: /el/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---

**Summary:** Defines the LayerMaskDataShort class which contains information about the mask data in the PSD file layer<br/>            when the layer has only raster or vector mask but not both. Otherwise, a [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) is used.<br/>            If the layer has only a raster mask the ImageData contains the raster mask data bytes.<br/>            If the layer has only a vector mask the ImageData contains the vector mask rasterized (cached) data bytes.<br/>            The [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) bytes length should be equal Width * Height of [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataShort

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LayerMaskDataShort()](#LayerMaskDataShort__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης LayerMaskDataShort |
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
| padding | short | r/w | Λαμβάνει ή ορίζει το padding της μάσκας στρώσης. |
| δεξιά | int | r/w | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας στρώματος. |
| επάνω | int | r/w | Λαμβάνει ή ορίζει τη θέση της πάνω μάσκας στρώματος. |


### Constructor: LayerMaskDataShort() {#LayerMaskDataShort__1}


```
 LayerMaskDataShort() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης LayerMaskDataShort

