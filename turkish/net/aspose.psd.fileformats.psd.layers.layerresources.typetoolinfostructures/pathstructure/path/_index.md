---
title: PathStructure.Path
second_title: Aspose.PSD for .NET API Referansı
description: PathStructure mülk. Yolu alır veya ayarlar.
type: docs
weight: 40
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
## PathStructure.Path property

Yolu alır veya ayarlar.

```csharp
public string Path { get; set; }
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


