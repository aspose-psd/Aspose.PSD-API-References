---
title: FXidResource.FXidResource
second_title: Aspose.PSD για Αναφορά API .NET
description: FXidResource κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουFXidResource τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

Αρχικοποιεί μια νέα παρουσία του[`FXidResource`](../) τάξη.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| key | Int32 | Το κλειδί πόρων. |
| version | Int32 | Η έκδοση. |
| filterEffectMasks | FilterEffectMaskData[] | Οι μάσκες του εφέ φίλτρου. |

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


