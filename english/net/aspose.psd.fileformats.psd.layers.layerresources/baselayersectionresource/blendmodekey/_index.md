---
title: BaseLayerSectionResource.BlendModeKey
second_title: Aspose.PSD for .NET API Reference
description: BaseLayerSectionResource property. Gets or sets the blend mode key
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.layerresources/baselayersectionresource/blendmodekey/
---
{{< psd/tize >}}
## BaseLayerSectionResource.BlendModeKey property

Gets or sets the blend mode key.

```csharp
public BlendMode BlendModeKey { get; set; }
```

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | BlendModeKey must be 4 characters in length. |

## Examples

The following code demonstrates support of LsdkResource.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string srcFile = "123 1.psd";
string outFile = "output.psd";

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).Length, 4);
    psdImage.Save(outFile);
}

// check after saving
using (var psdImage = (PsdImage)Image.Load(outFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    AssertAreEqual((psdImage.Layers[8].Resources[3] as LsdkResource).Length, 4);
}
```

### See Also

* enum [BlendMode](../../../aspose.psd.fileformats.core.blending/blendmode/)
* class [BaseLayerSectionResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


