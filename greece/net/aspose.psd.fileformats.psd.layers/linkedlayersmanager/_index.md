---
title: Class LinkedLayersManager
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager τάξη. Κατηγορία διαχείρισης συνδεδεμένων επιπέδων.
type: docs
weight: 3400
url: /el/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
## LinkedLayersManager class

Κατηγορία διαχείρισης συνδεδεμένων επιπέδων.

```csharp
public sealed class LinkedLayersManager
```

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | Λαμβάνει επίπεδα ανά αναγνωριστικό ομάδας συνδέσμων. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | Λαμβάνει το αναγνωριστικό ομάδας συνδέσμων που σχετίζεται με το επίπεδο. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | Συνδέει τα επίπεδα εισόδου και επιστρέφει LingGroupId. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | Αποσυνδέει το επίπεδο.. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς μπορείτε να χειριστείτε συνδεδεμένα επίπεδα στο Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // συνδέστε όλα τα επίπεδα σε μια συνδεδεμένη ομάδα
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // παίρνει αναγνωριστικό για ένα επίπεδο
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // λαμβάνει όλα τα συνδεδεμένα επίπεδα ανά αναγνωριστικό ομάδας συνδέσμων.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // αποσυνδέστε κάθε επίπεδο από την ομάδα
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // ανακτά το NULL για ένα αναγνωριστικό ομάδας συνδέσμων που δεν έχει επίπεδα στην ομάδα.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Δείτε επίσης

* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* συνέλευση [Aspose.PSD](../../)

