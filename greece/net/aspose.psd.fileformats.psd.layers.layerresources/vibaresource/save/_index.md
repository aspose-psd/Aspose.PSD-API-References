---
title: "VibAResource.Save"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "VibAResource method. Αποθηκεύει το πόρο στο καθορισμένο κοντέινερ ροής"
type: docs
weight: 50
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
{{< psd/tize >}}
## VibAResource.Save method

Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | StreamContainer | Το stream container για αποθήκευση. |
| psdVersion | Int32 | Η έκδοση PSD. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


