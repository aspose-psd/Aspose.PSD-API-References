---
title: "FilterEffectMaskData.FilterEffectMaskData"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FilterEffectMaskData कंस्ट्रक्टर। FilterEffectMaskData क्लास का नया इंस्टेंस इनिशियलाइज़ करता है"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
{{< psd/tize >}}
## FilterEffectMaskData constructor

[`FilterEffectMaskData`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| guid | String | संसाधन guid। |
| आयत | Rectangle | चैनलों का आयत। |
| pixelsDepth | Int32 | पिक्सेल गहराई। |
| maxChannels | Int32 | अधिकतम चैनलों का मान। |
| channels | ChannelInformation[] | चैनल्स। |
| userMask | ChannelInformation | उपयोगकर्ता मास्क। |
| maskRectangle | Rectangle | शीट मास्क आयत। |
| sheetMask | ChannelInformation | शीट मास्क। |

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

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


