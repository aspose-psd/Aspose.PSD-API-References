---
title: "LinkedLayersManager.GetLinkGroupId"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος LinkedLayersManager. Λαμβάνει το ID της ομάδας συνδέσμων που σχετίζεται με το επίπεδο"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/
---
{{< psd/tize >}}
## LinkedLayersManager.GetLinkGroupId method

Λαμβάνει το αναγνωριστικό ομάδας σύνδεσης που σχετίζεται με το στρώμα.

```csharp
public short GetLinkGroupId(Layer layer)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στρώση | Στρώση | Το στρώμα. |

### Τιμή Επιστροφής

Το αναγνωριστικό ομάδας σύνδεσης.

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς μπορείτε να χειριστείτε τα συνδεδεμένα στρώματα στο Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // συνδέστε όλα τα στρώματα σε μία συνδεδεμένη ομάδα
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // λαμβάνει το αναγνωριστικό για ένα στρώμα
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // λαμβάνει όλα τα συνδεδεμένα στρώματα με βάση το αναγνωριστικό ομάδας σύνδεσης.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // αποσυνδέστε κάθε στρώμα από την ομάδα
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // επιστρέφει NULL για ένα αναγνωριστικό ομάδας σύνδεσης που δεν έχει στρώματα στην ομάδα.
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


