---
title: Class VscgResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.VscgResource class. Vector Stroke Content Data resource
type: docs
weight: 3340
url: /net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/
---
{{< psd/tize >}}
## VscgResource class

Vector Stroke Content Data resource.

```csharp
public class VscgResource : LayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [VscgResource](vscgresource/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/items/) { get; } | Gets or sets the array of structure items. **Warning:** The `Items` array values must match with the `KeyForData` property, which determines the type of fill settings stored in the structures within `Items`. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| [KeyForData](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/keyfordata/) { get; } | Gets integer key that defines what kind of fill settings is stored in the resource: * Color - 0x536f436f - SoCoResource.TypeToolKey * Gradient - 0x4764466c - GdFlResource.TypeToolKey * Pattern - 0x5074466c - PtFlResource.TypeToolKey Warning! The value of property KeyForData should match the type of Fill settings stored in Items structures. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/length/) { get; } | Gets the layer resource length in bytes. |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vscgresource/typetoolkey/) | The type tool info key. |

## Examples

The following code demonstrates the support of VscgResource.

```csharp
[C#]

string sourceFile = "StrokeInternalFill_src.psd";
string outputFile = "StrokeInternalFill_res.psd";

void AreEqual(double expected, double current, double tolerance = 0.1)
{
    if (Math.Abs(expected - current) > tolerance)
    {
        throw new Exception(
            $"Values is not equal.\nExpected:{expected}\nResult:{current}\nDifference:{expected - current}");
    }
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(89.8, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(219.6, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(34.2, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);

    ((DoubleStructure)rgbColorStructure.Structures[0]).Value = 255d; // Red
    ((DoubleStructure)rgbColorStructure.Structures[1]).Value = 0d; // Green
    ((DoubleStructure)rgbColorStructure.Structures[2]).Value = 0d; // Blue

    image.Save(outputFile);
}

// checking changes
using (PsdImage image = (PsdImage)Image.Load(outputFile))
{
    VscgResource vscgResource = (VscgResource)image.Layers[1].Resources[0];
    DescriptorStructure rgbColorStructure = (DescriptorStructure)vscgResource.Items[0];

    AreEqual(255, ((DoubleStructure)rgbColorStructure.Structures[0]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[1]).Value);
    AreEqual(0, ((DoubleStructure)rgbColorStructure.Structures[2]).Value);
}
```

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


