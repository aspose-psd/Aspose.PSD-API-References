---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti Layer. Mendapatkan atau mengatur pencampuran elemen terpotong"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Mendapatkan atau mengatur pencampuran elemen yang dipotong.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

Pencampuran elemen terpotong.

## Contoh

Kode berikut menunjukkan dukungan properti BlendClippedElements.

```csharp
[C#]

string sourceFile = "example_source.psd";
string outputPsd = "example_output.psd";
string outputPng = "example_output.png";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    image.Layers[1].BlendClippedElements = false;
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Lihat Juga

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


