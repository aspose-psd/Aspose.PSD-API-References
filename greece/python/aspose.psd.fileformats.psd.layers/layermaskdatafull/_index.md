---
title: "LayerMaskDataFull Κλάση"
type: docs
weight: 980
url: /el/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Summary:** Defines the LayerMaskDataFull class which contains information about the mask data in the PSD file layer<br/>            when the layer has both layer and vector masks. Otherwise, a [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) is used.<br/>            The ImageData contains the raster mask and the rasterized vector mask combined.<br/>            The ImageData bytes length should be equal MaskRectangle.Width * MaskRectangle.Height properties.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.LayerMaskDataFull

**Inheritance:** LayerMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Περιγραφή** |
| :- | :- |
| [LayerMaskDataFull()](#LayerMaskDataFull__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης LayerMaskDataFull |
## **Properties**
| **Name** | **Type** | **Access** | **Περιγραφή** |
| :- | :- | :- | :- |
| background_color | byte | r/w | Λαμβάνει ή ορίζει το χρώμα φόντου. |
| bottom | int | r/w | Λαμβάνει ή ορίζει τη θέση του κάτω μάσκας στρώματος. |
| data_size | int | r | Λαμβάνει το μέγεθος των δεδομένων μάσκας στρώματος. |
| default_color | byte | r/w | Λαμβάνει ή ορίζει το προεπιλεγμένο χρώμα. |
| enclosing_bottom | int | r/w | Λαμβάνει ή ορίζει τη θέση του κάτω περιβάλλοντος raster μάσκας στο στρώμα εικόνας PSD. |
| enclosing_left | int | r/w | Λαμβάνει ή ορίζει τη θέση του αριστερού περιβάλλοντος raster μάσκας στο στρώμα αρχείου PSD. |
| enclosing_right | int | r/w | Λαμβάνει ή ορίζει τη θέση του δεξιού περιβάλλοντος raster μάσκας στο στρώμα αρχείου PSD. |
| enclosing_top | int | r/w | Λαμβάνει ή ορίζει τη θέση του πάνω περιβάλλοντος raster μάσκας στο στρώμα εικόνας PSD. |
| flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Λαμβάνει ή ορίζει τις σημαίες της μάσκας στρώματος. |
| image_data | byte | r/w | Λαμβάνει ή ορίζει τα δεδομένα μάσκας στρώματος (ή συνδυασμένη / τελική μάσκα εάν υπάρχει διανυσματική μάσκα) στο αρχείο PSD. |
| αριστερά | int | r/w | Λαμβάνει ή ορίζει τη θέση της αριστερής μάσκας στρώματος. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Λαμβάνει ή ορίζει τη μάσκα [Rectangle](/psd/python-net/aspose.psd/rectangle/) της μάσκας στρώματος στο αρχείο PSD.<br/>            Παίρνει τις ιδιότητες αριστερά, δεξιά, πάνω και κάτω και δημιουργεί [Rectangle](/psd/python-net/aspose.psd/rectangle/) |
| real_flags | [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags) | r/w | Λαμβάνει ή ορίζει τις σημαίες μάσκας στρώσης που χρησιμοποιούνται για τη μάσκα χρήστη / raster. Για τη διανυσματική μάσκα χρησιμοποιείται η ιδιότητα Flags. |
| δεξιά | int | r/w | Λαμβάνει ή ορίζει τη θέση της δεξιάς μάσκας στρώματος. |
| επάνω | int | r/w | Λαμβάνει ή ορίζει τη θέση της πάνω μάσκας στρώματος. |
| user_mask_data | byte | r/w | Λαμβάνει ή ορίζει τα δεδομένα μάσκας χρήστη (raster) ενός στρώματος στο αρχείο PSD. (Υπάρχει rasterized διανυσματική μάσκα στην ιδιότητα MaskData). |
| user_mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Λαμβάνει ή ορίζει το ορθογώνιο (περιβάλλει) της μάσκας χρήστη στο στρώμα εικόνας PSD.. |


### Constructor: LayerMaskDataFull() {#LayerMaskDataFull__1}


```
 LayerMaskDataFull() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης LayerMaskDataFull

