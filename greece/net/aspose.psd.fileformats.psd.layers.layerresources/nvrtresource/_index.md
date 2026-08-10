---
title: "Κλάση NvrtResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κλάση Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource. Κλάση NvrtResource. Πόρος του στρώματος προσαρμογής Invert Adjustment Layer"
type: docs
weight: 3180
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
{{< psd/tize >}}
## NvrtResource class

Κλάση NvrtResource. Πόρος της Invert Adjustment Layer.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | Αρχικοποιεί μια νέα παρουσία της κλάσης `NvrtResource`. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | Αρχικοποιεί μια νέα παρουσία της κλάσης `NvrtResource`. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρου του επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Λαμβάνει την υπογραφή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | Το κλειδί πληροφοριών του εργαλείου τύπου. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να αποκτήσετε το NvdrResource.

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
                    // Το NvdrResource υποστηρίζεται.
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


