---
title: Class FilterEffectMaskData
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FilterEffectMaskData कक्ष. फ़ल्टर मस्क डेट क्लस.
type: docs
weight: 2480
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---
## FilterEffectMaskData class

फ़िल्टर मास्क डेटा क्लास.

```csharp
public sealed class FilterEffectMaskData
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [FilterEffectMaskData](filtereffectmaskdata/)(string, Rectangle, int, int, ChannelInformation[], ChannelInformation, Rectangle, ChannelInformation) | का एक नया उदाहरण प्रारंभ करता है`FilterEffectMaskData` वर्ग. |

## गुण

| नाम | विवरण |
| --- | --- |
| [Channels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/channels/) { get; } | चैनल प्राप्त करता है। |
| [GUID](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/guid/) { get; } | GUID प्राप्त करता है. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/length/) { get; } | बाइट्स में फ़िल्टर मास्क डेटा लंबाई प्राप्त करता है। |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maskrectangle/) { get; } | शीट मास्क आयत प्राप्त करता है। |
| [MaxChannels](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/maxchannels/) { get; } | चैनलों की अधिकतम संख्या प्राप्त करता है। |
| [PixelsDepth](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/pixelsdepth/) { get; } | पिक्सल गहराई प्राप्त करता है। |
| [Rectangle](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/rectangle/) { get; } | चैनल आयत प्राप्त करता है। |
| [SheetMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/sheetmask/) { get; } | शीट मास्क प्राप्त करता है। |
| [UserMask](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/usermask/) { get; } | उपयोगकर्ता मास्क प्राप्त करता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| [SaveData](../../aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/savedata/)(StreamContainer) | संसाधन को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |

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

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* सभा [Aspose.PSD](../../)


