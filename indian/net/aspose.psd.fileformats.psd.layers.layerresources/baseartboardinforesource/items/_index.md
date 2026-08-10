---
title: "BaseArtboardInfoResource.Items"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "BaseArtboardInfoResource प्रॉपर्टी। OSTypeStructure आइटम्स को प्राप्त या सेट करता है।"
type: docs
weight: 10
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/items/
---
{{< psd/tize >}}
## BaseArtboardInfoResource.Items property

[`OSTypeStructure`](../../ostypestructure/) आइटम्स को प्राप्त या सेट करता है।

```csharp
public OSTypeStructure[] Items { get; set; }
```

## उदाहरण

निम्नलिखित कोड आर्टबोर्ड संसाधनों के समर्थन को दर्शाता है।

```csharp
[C#]

string srcFile = "artboard1.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    ArtDResource artDResource = (ArtDResource)psdImage.GlobalLayerResources[2];

    ArtBResource artBResource1 = (ArtBResource)psdImage.Layers[2].Resources[7];
    ArtBResource artBResource2 = (ArtBResource)psdImage.Layers[5].Resources[7];

    LyvrResource lyvrResource1 = (LyvrResource)psdImage.Layers[2].Resources[9];
    LyvrResource lyvrResource2 = (LyvrResource)psdImage.Layers[5].Resources[9];

    var countStruct = (IntegerStructure)artDResource.Items[0];
    AssertAreEqual(2, countStruct.Value);

    var presetNameStruct1 = (StringStructure)artBResource1.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct1.Value);

    var presetNameStruct2 = (StringStructure)artBResource2.Items[2];
    AssertAreEqual("iPhone X\0", presetNameStruct2.Value);

    AssertAreEqual(160, lyvrResource1.Version);
    AssertAreEqual(160, lyvrResource2.Version);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}
```

### देखें भी

* class [OSTypeStructure](../../ostypestructure/)
* class [BaseArtboardInfoResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


