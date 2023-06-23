---
title: PathStructure.Prefix
second_title: Aspose.PSD for .NET API Reference
description: PathStructure property. Gets or sets the path prefix
type: docs
weight: 50
url: /net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

Gets or sets the path prefix.

```csharp
public string Prefix { get; set; }
```

### Property Value

The full path.

## Examples

The following code demonstrates ability to load file with PathStructure structure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### See Also

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


