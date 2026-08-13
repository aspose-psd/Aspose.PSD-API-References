---
title: "PathStructure.Length"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PathStructure özelliği. OSTypeStructure uzunluğunu bayt olarak alır."
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
{{< psd/tize >}}
## PathStructure.Length property

[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) uzunluğunu bayt cinsinden alır.

```csharp
public override int Length { get; }
```

## Örnekler

Aşağıdaki kod, PathStructure yapısıyla dosya yükleme yeteneğini gösterir.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Ayrıca Bakınız

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


