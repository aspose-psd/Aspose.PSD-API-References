---
title: "क्लास FXidResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.FXidResource क्लास। फ़िल्टर इफ़ेक्ट्स संसाधन में चैनल, एक यूज़र मास्क और स्मार्ट फ़िल्टर के लिए एक शीट मास्क शामिल हैं।"
type: docs
weight: 2720
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---
{{< psd/tize >}}
## FXidResource class

फ़िल्टर इफ़ेक्ट्स रिसोर्स में चैनल, एक यूज़र मास्क, और स्मार्ट फ़िल्टर के लिए शीट मास्क शामिल हैं।

```csharp
public sealed class FXidResource : LayerResource
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [FXidResource](fxidresource/)(int, int, FilterEffectMaskData[]) | `FXidResource` क्लास का एक नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [FilterEffectMasks](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/) { get; } | फ़िल्टर इफ़ेक्ट मास्क प्राप्त करता है। |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/length/) { get; } | बाइट्स में लेयर रिसोर्स की लंबाई प्राप्त करता है। |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है। |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | हस्ताक्षर प्राप्त करता है। |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/version/) { get; } | संस्करण को प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/save/)(StreamContainer, int) | निर्दिष्ट स्ट्रीम कंटेनर में रिसोर्स को सहेजता है। |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | इस उदाहरण का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| const [FEidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/feidtypetoolkey/) | टाइप टूल जानकारी कुंजी FEid। |
| const [FXidTypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidtypetoolkey/) | टाइप टूल जानकारी कुंजी FXid। |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


