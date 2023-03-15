---
title: VibAResource.Length
second_title: Aspose.PSD για Αναφορά API .NET
description: VibAResource ιδιοκτησία. Λαμβάνει το μήκος του πόρου του επιπέδου σε byte.
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/
---
## VibAResource.Length property

Λαμβάνει το μήκος του πόρου του επιπέδου σε byte.

```csharp
public override int Length { get; }
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


