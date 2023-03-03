---
title: VibAResource.Save
second_title: Aspose.PSD για Αναφορά API .NET
description: VibAResource μέθοδος. Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής.
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

Αποθηκεύει τον πόρο στο καθορισμένο κοντέινερ ροής.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| streamContainer | StreamContainer | Το κοντέινερ ροής για αποθήκευση. |
| psdVersion | Int32 | Η έκδοση PSD. |

### Παραδείγματα

Το ακόλουθο παράδειγμα κώδικα δείχνει την υποστήριξη του πόρου VibAResource.

```csharp
[C#]

// Παράδειγμα υποστήριξης ανάγνωσης και εγγραφής Vibration Resource κατά τη διάρκεια εκτέλεσης.
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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* συνέλευση [Aspose.PSD](../../../)


