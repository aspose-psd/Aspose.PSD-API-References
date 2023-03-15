---
title: LayerGroup.IsOpen
second_title: Aspose.PSD για Αναφορά API .NET
description: LayerGroup ιδιοκτησία. Λαμβάνει ή θέτει ο φάκελος open εάν έχει οριστεί σεαληθής από την ομάδα θα είναι σε ανοιχτή κατάσταση κατά την εκκίνηση διαφορετικά σε ελαχιστοποιημένη κατάσταση.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

Λαμβάνει ή θέτει ο φάκελος open εάν έχει οριστεί σε`αληθής` από την ομάδα θα είναι σε ανοιχτή κατάσταση κατά την εκκίνηση, διαφορετικά σε ελαχιστοποιημένη κατάσταση.

```csharp
public bool IsOpen { get; set; }
```

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να ανοίξετε και να κλείσετε το LayerGroup (Folder) χρησιμοποιώντας την ιδιότητα IsOpen.

```csharp
[C#]

// Παράδειγμα ανάγνωσης και εγγραφής ιδιότητας IsOpen κατά το χρόνο εκτέλεσης.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### Δείτε επίσης

* class [LayerGroup](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* συνέλευση [Aspose.PSD](../../../)


