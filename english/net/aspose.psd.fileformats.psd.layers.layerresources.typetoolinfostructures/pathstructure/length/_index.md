---
title: PathStructure.Length
second_title: Aspose.PSD for .NET API Reference
description: PathStructure property. Gets the OSTypeStructure length in bytes
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
{{< psd/tize >}}
## PathStructure.Length property

Gets the [`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) length in bytes.

```csharp
public override int Length { get; }
```

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


