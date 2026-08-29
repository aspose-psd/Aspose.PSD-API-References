---
title: "PathStructure.Prefix"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PathStructure. Mendapatkan atau mengatur awalan jalur"
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

Mendapatkan atau mengatur awalan jalur.

```csharp
public string Prefix { get; set; }
```

### Property Value

Jalur lengkap.

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


