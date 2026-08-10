---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής FilterEffectMaskData. Αρχικοποιεί μια νέα παρουσία της κλάσης FilterEffectMaskData"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

Αρχικοποιεί μια νέα παρουσία της κλάσης [`FilterEffectMaskData`](../).

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | String | Το GUID του πόρου. |
| ορθογώνιο | Rectangle | Το ορθογώνιο των καναλιών. |
| pixelsDepth | Int32 | Το βάθος εικονοστοιχείων. |
| maxChannels | Int32 | Η μέγιστη τιμή των καναλιών. |
| channels | ChannelInformation[] | Τα κανάλια. |
| userMask | ChannelInformation | Η μάσκα χρήστη. |
| maskRectangle | Rectangle | Το ορθογώνιο μάσκα φύλλου. |
| sheetMask | ChannelInformation | Η μάσκα φύλλου. |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


