---
title: FXidResource.FilterEffectMasks
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: FXidResource संपत्त. फ़ल्टर प्रभव मस्क प्रप्त करत है
type: docs
weight: 20
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/filtereffectmasks/
---
## FXidResource.FilterEffectMasks property

फ़िल्टर प्रभाव मास्क प्राप्त करता है।

```csharp
public FilterEffectMaskData[] FilterEffectMasks { get; }
```

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


