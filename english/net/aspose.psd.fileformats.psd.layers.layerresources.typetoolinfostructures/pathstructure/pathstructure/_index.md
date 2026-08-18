---
title: PathStructure.PathStructure
second_title: Aspose.PSD for .NET API Reference
description: PathStructure constructor. Initializes a new instance of the PathStructure class
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure(ClassID) {#constructor}

Initializes a new instance of the [`PathStructure`](../) class.

```csharp
public PathStructure(ClassID keyName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| keyName | ClassID | The key name. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)

---

## PathStructure(ClassID, string) {#constructor_1}

Initializes a new instance of the [`PathStructure`](../) class with a path.

```csharp
public PathStructure(ClassID keyName, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| keyName | ClassID | The key name. |
| path | String | The path string. |

### See Also

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


