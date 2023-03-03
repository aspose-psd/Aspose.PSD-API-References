---
title: FilterEffectMaskData.FilterEffectMaskData
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FilterEffectMaskData नर्मत. क एक नय उदहरण प्ररंभ करत हैFilterEffectMaskData वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/filtereffectmaskdata/
---
## FilterEffectMaskData constructor

का एक नया उदाहरण प्रारंभ करता है[`FilterEffectMaskData`](../) वर्ग.

```csharp
public FilterEffectMaskData(string guid, Rectangle rectangle, int pixelsDepth, int maxChannels, 
    ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, 
    ChannelInformation sheetMask)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| guid | String | संसाधन गाइड। |
| rectangle | Rectangle | चैनल आयताकार। |
| pixelsDepth | Int32 | पिक्सेल गहराई। |
| maxChannels | Int32 | अधिकतम चैनल मान। |
| channels | ChannelInformation[] | चैनल। |
| userMask | ChannelInformation | उपयोगकर्ता का मुखौटा। |
| maskRectangle | Rectangle | शीट मास्क आयत। |
| sheetMask | ChannelInformation | चादर का मुखौटा। |

### उदाहरण

यह उदाहरण दर्शाता है कि FXidResource संसाधन के गुणों को कैसे प्राप्त और सेट किया जाए।

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

// सेव करने के बाद चेक करें
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

### यह सभी देखें

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [ChannelInformation](../../../aspose.psd.fileformats.psd.layers/channelinformation/)
* class [FilterEffectMaskData](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../filtereffectmaskdata/)
* सभा [Aspose.PSD](../../../)


