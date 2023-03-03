---
title: FXidResource.FXidResource
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FXidResource नर्मत. क एक नय उदहरण प्ररंभ करत हैFXidResource वर्ग.
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/fxidresource/
---
## FXidResource constructor

का एक नया उदाहरण प्रारंभ करता है[`FXidResource`](../) वर्ग.

```csharp
public FXidResource(int key, int version, FilterEffectMaskData[] filterEffectMasks)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | Int32 | संसाधन कुंजी। |
| version | Int32 | संस्करण। |
| filterEffectMasks | FilterEffectMaskData[] | फ़िल्टर प्रभाव मास्क। |

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

* class [FilterEffectMaskData](../../filtereffectmaskdata/)
* class [FXidResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../fxidresource/)
* सभा [Aspose.PSD](../../../)


