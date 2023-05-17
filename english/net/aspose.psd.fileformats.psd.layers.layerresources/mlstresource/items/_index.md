---
title: MlstResource.Items
second_title: Aspose.PSD for .NET API Reference
description: MlstResource property. Gets or sets the structures
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
{{< psd/tize >}}
## MlstResource.Items property

Gets or sets the structures.

```csharp
public OSTypeStructure[] Items { get; }
```

## Examples

The following code demonstrates support of MlstResource resource that gives a low-level mechanism to manipulate the layer states.

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // Disable layer 1 on frame 1
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### See Also

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../mlstresource/)
* assembly [Aspose.PSD](../../../)


