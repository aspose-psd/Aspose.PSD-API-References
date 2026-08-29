---
title: "PathStructure.Key"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PathStructure. Mendapatkan kunci struktur"
type: docs
weight: 20
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
{{< psd/tize >}}
## PathStructure.Key property

Mendapatkan kunci struktur.

```csharp
public override int Key { get; }
```

## Contoh

Kode berikut menunjukkan kemampuan memuat file dengan struktur PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Lihat Juga

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


