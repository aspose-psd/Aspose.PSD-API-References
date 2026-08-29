---
title: "PathStructure.Length"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PathStructure-Eigenschaft. Gibt die OSTypeStructure-Länge in Bytes zurück"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
{{< psd/tize >}}
## PathStructure.Length property

Gibt die Länge des [`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) in Bytes zurück.

```csharp
public override int Length { get; }
```

## Beispiele

Der folgende Code demonstriert die Fähigkeit, eine Datei mit der PathStructure-Struktur zu laden.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Siehe auch

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


