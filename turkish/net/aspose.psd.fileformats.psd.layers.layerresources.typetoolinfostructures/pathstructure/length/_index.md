---
title: PathStructure.Length
second_title: Aspose.PSD for .NET API Referansı
description: PathStructure mülk. Şunu alırOSTypeStructure bayt cinsinden uzunluk.
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

Şunu alır:[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) bayt cinsinden uzunluk.

```csharp
public override int Length { get; }
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


