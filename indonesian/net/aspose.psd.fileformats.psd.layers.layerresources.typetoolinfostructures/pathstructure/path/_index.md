---
title: "PathStructure.Path"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PathStructure. Mendapatkan atau mengatur jalur"
type: docs
weight: 40
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
{{< psd/tize >}}
## PathStructure.Path property

Mendapatkan atau mengatur jalur.

```csharp
public string Path { get; set; }
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


