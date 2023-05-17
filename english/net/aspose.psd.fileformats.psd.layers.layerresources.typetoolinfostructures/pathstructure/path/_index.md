---
title: PathStructure.Path
second_title: Aspose.PSD for .NET API Reference
description: PathStructure property. Gets or sets the path
type: docs
weight: 40
url: /net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
{{< psd/tize >}}
## PathStructure.Path property

Gets or sets the path.

```csharp
public string Path { get; set; }
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* assembly [Aspose.PSD](../../../)


