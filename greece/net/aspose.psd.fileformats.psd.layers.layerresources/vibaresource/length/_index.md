---
title: "VibAResource.Length"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "VibAResource ιδιότητα. Επιστρέφει το μήκος του πόρου του επιπέδου σε bytes"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/
---
{{< psd/tize >}}
## VibAResource.Length property

Λαμβάνει το μήκος του πόρου του επιπέδου σε bytes.

```csharp
public override int Length { get; }
```

## Παραδείγματα

Το παρακάτω παράδειγμα κώδικα δείχνει την υποστήριξη του πόρου VibAResource.

```csharp
[C#]

// Παράδειγμα υποστήριξης ανάγνωσης και εγγραφής του πόρου Δόνησης σε χρόνο εκτέλεσης.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### Δείτε επίσης

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


