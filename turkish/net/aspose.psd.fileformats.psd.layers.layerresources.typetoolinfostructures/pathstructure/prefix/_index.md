---
title: "PathStructure.Prefix"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PathStructure özelliği. TypeTool yol biçimi için eski yol önekini alır veya ayarlar."
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

Eski yol önekini alır veya ayarlar (TypeTool yol formatı için).

```csharp
[Obsolete("Prefix is kept for compatibility and is ignored during save. PathStructure always writes the txtu payload signature when Path is changed.")]
public string Prefix { get; set; }
```

### Property Value

Yol öneki.

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


