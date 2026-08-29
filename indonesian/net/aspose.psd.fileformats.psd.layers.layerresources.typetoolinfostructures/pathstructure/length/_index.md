---
title: "PathStructure.Length"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PathStructure. Mendapatkan panjang OSTypeStructure dalam byte"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
{{< psd/tize >}}
## PathStructure.Length property

Mendapatkan panjang [`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) dalam byte.

```csharp
public override int Length { get; }
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


