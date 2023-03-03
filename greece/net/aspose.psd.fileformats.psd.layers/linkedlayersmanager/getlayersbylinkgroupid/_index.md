---
title: LinkedLayersManager.GetLayersByLinkGroupId
second_title: Aspose.PSD για Αναφορά API .NET
description: LinkedLayersManager μέθοδος. Λαμβάνει επίπεδα ανά αναγνωριστικό ομάδας συνδέσμων.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
## LinkedLayersManager.GetLayersByLinkGroupId method

Λαμβάνει επίπεδα ανά αναγνωριστικό ομάδας συνδέσμων.

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| linkGroupId | Int16 | Το αναγνωριστικό της ομάδας συνδέσμων. |

### Επιστρεφόμενη Αξία

Η συστοιχία στρώσεων.

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* συνέλευση [Aspose.PSD](../../../)


