---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: Aspose.PSD για Αναφορά API .NET
description: FilterEffectMaskData κατασκευαστής. Αρχικοποιεί μια νέα παρουσία τουFilterEffectMaskData τάξη.
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

Αρχικοποιεί μια νέα παρουσία του[`FilterEffectMaskData`](../) τάξη.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| guid | String | Ο οδηγός πόρων. |
| rectangle | Rectangle | Τα κανάλια είναι ορθογώνια. |
| pixelsDepth | Int32 | Το βάθος των pixel. |
| maxChannels | Int32 | Η μέγιστη τιμή καναλιών. |
| channels | ChannelInformation[] | Τα κανάλια. |
| userMask | ChannelInformation | Η μάσκα χρήστη. |
| maskRectangle | Rectangle | Το ορθογώνιο μάσκα φύλλου. |
| sheetMask | ChannelInformation | Η σεντόνι μάσκα. |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* συνέλευση [Aspose.PSD](../../../)


