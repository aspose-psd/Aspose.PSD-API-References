---
title: "PathStructure.Path"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PathStructure özelliği. TypeTool yol biçimi için yolu alır veya ayarlar"
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
{{< psd/tize >}}
## PathStructure.Path property

Yolu alır veya ayarlar (TypeTool yol formatı için).

```csharp
public string Path { get; set; }
```

### Property Value

Tam yol.

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


