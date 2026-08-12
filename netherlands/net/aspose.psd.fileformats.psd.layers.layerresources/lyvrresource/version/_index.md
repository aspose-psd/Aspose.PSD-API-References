---
title: "LyvrResource.Version"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "LyvrResource eigenschap. Haalt de Photoshop-versie van de laag op of stelt deze in"
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/version/
---
{{< psd/tize >}}
## LyvrResource.Version property

Haalt op of stelt de Photoshop-versie van een laag in.

```csharp
public int Version { get; set; }
```

## Voorbeelden

De volgende code demonstreert de ondersteuning van Artboard-resources.

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

### Zie ook

* class [LyvrResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


