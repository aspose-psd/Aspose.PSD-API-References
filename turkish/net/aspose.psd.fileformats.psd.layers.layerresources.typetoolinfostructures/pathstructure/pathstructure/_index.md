---
title: PathStructure.PathStructure
second_title: Aspose.PSD for .NET API Referansı
description: PathStructure inşaatçı. Yeni bir örneğini başlatır.PathStructure sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Yeni bir örneğini başlatır.[`PathStructure`](../) sınıf.

```csharp
public PathStructure(ClassID keyName)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| keyName | ClassID | Anahtar adı. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* toplantı [Aspose.PSD](../../../)


