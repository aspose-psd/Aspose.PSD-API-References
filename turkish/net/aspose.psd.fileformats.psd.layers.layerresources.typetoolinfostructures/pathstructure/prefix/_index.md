---
title: PathStructure.Prefix
second_title: Aspose.PSD for .NET API Referansı
description: PathStructure mülk. Yol önekini alır veya ayarlar.
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
## PathStructure.Prefix property

Yol önekini alır veya ayarlar.

```csharp
public string Prefix { get; set; }
```

### Mülk değeri

Tam yol.

### Örnekler

Aşağıdaki kod, PathStructure yapısına sahip dosya yükleme yeteneğini gösterir.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Ayrıca bakınız

* class [PathStructure](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* toplantı [Aspose.PSD](../../../)


