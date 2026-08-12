---
title: "Klasse LyvrResource"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LyvrResource class. De resource die de Photoshop-versie van een laag vertegenwoordigt"
type: docs
weight: 3150
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/
---
{{< psd/tize >}}
## LyvrResource class

De resource die de Photoshop-versie van een laag vertegenwoordigt.

```csharp
public sealed class LyvrResource : LayerResource
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [LyvrResource](lyvrresource/)() | De standaardconstructor. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Haalt de laagresource-sleutel op. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/length/) { get; } |  |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Haalt de minimale PSD-versie op die vereist is voor laagresource. 0 geeft geen beperkingen aan. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Haalt de handtekening op. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/version/) { get; set; } | Haalt op of stelt de Photoshop-versie van een laag in. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/save/)(StreamContainer, int) | Slaat de resource op in de opgegeven streamcontainer. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Retourneert een String die deze instantie vertegenwoordigt. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/typetoolkey/) | De type-tool-informatiesleutel. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


