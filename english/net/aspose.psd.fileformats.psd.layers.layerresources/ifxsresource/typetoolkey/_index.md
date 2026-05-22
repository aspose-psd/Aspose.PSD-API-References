---
title: IfxsResource.TypeToolKey
second_title: Aspose.PSD for .NET API Reference
description: IfxsResource field. The type tool info key
type: docs
weight: 20
url: /net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

The type tool info key.

```csharp
public const int TypeToolKey;
```

## Examples

The following code demonstrates the support of IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // Example has 2 group layers with effects
    // Group layer with one effect
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Group layer with many effects
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Get the number of effects and verify their quantity
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // One effect in the group layer is in resource 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Two or more effects in a group layer are in resource 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Add a third shadow to a group layer with multiple effects
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### See Also

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


