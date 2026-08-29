---
title: "FXidResource.FXidResource"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής FXidResource. Αρχικοποιεί μια νέα παρουσία της κλάσης FXidResource"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
{{< psd/tize >}}
## FXidResource constructor

Αρχικοποιεί μια νέα παρουσία της κλάσης [`FXidResource`](../).

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | Int32 | Το κλειδί του πόρου. |
| έκδοση | Int32 | Η έκδοση. |
| filterEffectMasks | FilterEffectMaskData[] | Οι μάσκες εφέ φίλτρου. |

## Παραδείγματα

Αυτό το παράδειγμα δείχνει πώς να λαμβάνετε και να ορίζετε ιδιότητες του πόρου FXidResource.

```csharp
[C#]

string inputFilePath = "psdnet414_3.psd";
string output = "out_psdnet414_3.psd";

int resLength = 1144;
long maskLength = 369;

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

// ελέγξτε μετά την αποθήκευση
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


