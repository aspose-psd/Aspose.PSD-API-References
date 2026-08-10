---
title: "Κλάση PostResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PostResource κλάση. Κλάση PostResource. Ρυθμίσεις στρώματος Posterize"
type: docs
weight: 3300
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/
---
{{< psd/tize >}}
## PostResource class

Κλάση PostResource. Ρυθμίσεις στρώσης Posterize.

```csharp
public class PostResource : AdjustmentLayerResource
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [PostResource](postresource/)() | Ο προεπιλεγμένος κατασκευαστής. |

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Λαμβάνει το κλειδί πόρου του επιπέδου. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/length/) { get; } | Λαμβάνει το μήκος του πόρου του επιπέδου σε bytes. |
| [Levels](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/) { get; set; } | Επίπεδα του Posterize layer. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Λαμβάνει την ελάχιστη έκδοση psd που απαιτείται για τον πόρο του επιπέδου. 0 υποδεικνύει ότι δεν υπάρχουν περιορισμοί. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Λαμβάνει την υπογραφή. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/save/)(StreamContainer, int) | Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Επιστρέφει ένα String που αντιπροσωπεύει αυτήν την περίπτωση. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/typetoolkey/) | Το κλειδί πληροφοριών του εργαλείου τύπου. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα χειρισμού του PostResource.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### Δείτε επίσης

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


