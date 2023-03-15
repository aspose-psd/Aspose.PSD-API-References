---
title: VibAResource.PsdVersion
second_title: Aspose.PSD για Αναφορά API .NET
description: VibAResource ιδιοκτησία. Λαμβάνει την έκδοση psd.
type: docs
weight: 40
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/
---
## VibAResource.PsdVersion property

Λαμβάνει την έκδοση psd.

```csharp
public override int PsdVersion { get; }
```

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

* class [VibAResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* συνέλευση [Aspose.PSD](../../../)


