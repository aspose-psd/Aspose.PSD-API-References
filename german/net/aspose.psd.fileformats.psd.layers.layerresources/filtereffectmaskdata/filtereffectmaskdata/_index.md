---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "FilterEffectMaskData Konstruktor. Initialisiert eine neue Instanz der FilterEffectMaskData-Klasse"
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

Initialisiert eine neue Instanz der [`FilterEffectMaskData`](../)-Klasse.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| GUID | String | Die Ressourcen-GUID. |
| Rechteck | Rectangle | Das Kanalrechteck. |
| pixelsDepth | Int32 | Die Pixeltiefe. |
| maxChannels | Int32 | Der Maximalwert der Kanäle. |
| channels | ChannelInformation[] | Die Kanäle. |
| userMask | ChannelInformation | Die Benutzer-Maske. |
| maskRectangle | Rectangle | Das Rechteck der Blattmaske. |
| sheetMask | ChannelInformation | Die Blattmaske. |

## Beispiele

Dieses Beispiel zeigt, wie Eigenschaften der FXidResource-Ressource gelesen und geschrieben werden.

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

// nach dem Speichern prüfen
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

### Siehe auch

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


