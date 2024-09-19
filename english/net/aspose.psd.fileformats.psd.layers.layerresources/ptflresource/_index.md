---
title: Class PtFlResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PtFlResource class. Class PtFlResource. Contains Pattern Fill Layer Data
type: docs
weight: 3210
url: /net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
{{< psd/tize >}}
## PtFlResource class

Class PtFlResource. Contains Pattern Fill Layer Data.

```csharp
public class PtFlResource : FillLayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [PtFlResource](ptflresource/)(string, string) | Initializes a new instance of the `PtFlResource` class. |

## Properties

| Name | Description |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/) { get; set; } | Gets or sets a value indicating whether [align with layer]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/) { get; set; } | Gets or sets the angle. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/) { get; set; } | Gets or sets a value indicating whether this instance is linked with layer. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length/) { get; } | Gets the layer resource length in bytes. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/) { get; set; } | Gets or sets the offset. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid/) { get; set; } | Gets or sets the pattern identifier. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname/) { get; set; } | Gets or sets the name of the pattern. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale/) { get; set; } | Gets or sets the scale. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/signature/) { get; } | Gets the layer resource signature. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey/) | The type tool info key. |

## Examples

The following example demonstrates the support of the loading and editing a PtFlResource resource.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // Reading
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // Editing
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // We haven't pattern data in PattResource, so we can add it.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


