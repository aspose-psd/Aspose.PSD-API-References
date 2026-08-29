---
title: "FXidResource.FXidResource"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "FXidResource कंस्ट्रक्टर। FXidResource क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
{{< psd/tize >}}
## FXidResource constructor

[`FXidResource`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कुंजी | Int32 | संसाधन कुंजी। |
| संस्करण | Int32 | संस्करण. |
| filterEffectMasks | FilterEffectMaskData[] | फ़िल्टर प्रभाव मास्क। |

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

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


