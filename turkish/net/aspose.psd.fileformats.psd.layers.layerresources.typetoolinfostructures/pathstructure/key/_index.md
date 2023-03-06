---
title: PathStructure.Key
second_title: Aspose.PSD for .NET API Referansı
description: PathStructure mülk. Yapı anahtarını alır.
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
## PathStructure.Key property

Yapı anahtarını alır.

```csharp
public override int Key { get; }
```

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


