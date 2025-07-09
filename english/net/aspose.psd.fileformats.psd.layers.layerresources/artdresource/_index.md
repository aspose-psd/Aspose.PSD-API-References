---
title: Class ArtDResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.ArtDResource class. The Artboard info data for GlobalLayerResources
type: docs
weight: 2510
url: /net/aspose.psd.fileformats.psd.layers.layerresources/artdresource/
---
{{< psd/tize >}}
## ArtDResource class

The Artboard info data for [`GlobalLayerResources`](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/).

```csharp
public sealed class ArtDResource : BaseArtboardInfoResource
```

## Constructors

| Name | Description |
| --- | --- |
| [ArtDResource](artdresource/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/items/) { get; set; } | Gets or sets the [`OSTypeStructure`](../ostypestructure/) items. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/length/) { get; } |  |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/artdresource/typetoolkey/) | The type tool info key. |

## Examples

The following code demonstrates the support of Artboard resources.

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

### See Also

* class [BaseArtboardInfoResource](../baseartboardinforesource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


