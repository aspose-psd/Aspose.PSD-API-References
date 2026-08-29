---
title: "FilterEffectMaskData.Channels"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FilterEffectMaskData प्रॉपर्टी। चैनल प्राप्त करता है।"
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/channels/
---
{{< psd/tize >}}
## FilterEffectMaskData.Channels property

चैनलों को प्राप्त करता है।

```csharp
public ChannelInformation[] Channels { get; }
```

## उदाहरण

यह उदाहरण दिखाता है कि FXidResource संसाधन की गुणों को कैसे प्राप्त और सेट किया जाए।

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

// सहेजने के बाद जाँच करें
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

### देखें भी

* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


