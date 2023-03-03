---
title: FXidResource.FilterEffectMasks
second_title: Aspose.PSD για Αναφορά API .NET
description: FXidResource ιδιοκτησία. Λαμβάνει τις μάσκες εφέ φίλτρου.
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/
---
## FXidResource.FilterEffectMasks property

Λαμβάνει τις μάσκες εφέ φίλτρου.

```csharp
public FilterEffectMaskData[] FilterEffectMasks { get; }
```

### Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να αποκτήσετε και να ορίσετε ιδιότητες του πόρου FXidResource.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
int maskLength = 369;

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

using (var psdImage = (PsdImage)Image.Load(inputFilePath))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }

    psdImage.Save(output);
}

// έλεγχος μετά την αποθήκευση
using (var psdImage = (PsdImage)Image.Load(output))
{
    FXidResource fXidResource = (FXidResource)psdImage.GlobalLayerResources[3];

    AssertAreEqual(resLength, fXidResource.Length);
    foreach (var maskData in fXidResource.FilterEffectMasks)
    {
        AssertAreEqual(maskLength, maskData.Length);
    }
}
```

### Δείτε επίσης

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* συνέλευση [Aspose.PSD](../../../)


