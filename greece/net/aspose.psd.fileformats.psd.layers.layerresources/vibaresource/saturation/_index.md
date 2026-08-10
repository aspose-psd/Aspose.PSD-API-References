---
title: "VibAResource.Saturation"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "VibAResource ιδιότητα. Επιστρέφει ή ορίζει την τιμή κορεσμού"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/saturation/
---
{{< psd/tize >}}
## VibAResource.Saturation property

Λαμβάνει ή ορίζει την τιμή κορεσμού

```csharp
public int Saturation { get; set; }
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


