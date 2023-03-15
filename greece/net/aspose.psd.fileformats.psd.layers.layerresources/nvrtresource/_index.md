---
title: Class NvrtResource
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource τάξη. Κλάση NvrtResource. Πόρος του επιπέδου προσαρμογής Invert Adjustment.
type: docs
weight: 2840
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
## NvrtResource class

Κλάση NvrtResource. Πόρος του επιπέδου προσαρμογής Invert Adjustment.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## Κατασκευαστές

| Ονομα | Περιγραφή |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | Αρχικοποιεί μια νέα παρουσία του`NvrtResource` τάξη. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | Αρχικοποιεί μια νέα παρουσία του`NvrtResource` τάξη. |

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/key/) { get; } | Λαμβάνει το κλειδί πόρων επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/psdversion/) { get; } | Λαμβάνει την έκδοση PSD. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Παίρνει την υπογραφή. |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει αString που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | Το κλειδί πληροφοριών εργαλείου τύπου. |

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει πώς να αποκτήσετε NvrtResource.

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // Υποστηρίζεται το NvrtResource.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### Δείτε επίσης

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* συνέλευση [Aspose.PSD](../../)


