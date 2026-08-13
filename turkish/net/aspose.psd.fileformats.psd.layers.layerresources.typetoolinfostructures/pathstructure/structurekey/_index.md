---
title: "PathStructure.StructureKey"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PathStructure alanı. Yapı anahtarını tanımlar"
type: docs
weight: 60
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/structurekey/
---
{{< psd/tize >}}
## PathStructure.StructureKey field

Yapı anahtarını tanımlar.

```csharp
public const int StructureKey;
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


