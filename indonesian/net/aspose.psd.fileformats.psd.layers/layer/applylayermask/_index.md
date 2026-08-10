---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Layer. Menerapkan masker lapisan ke lapisan lalu menghapus masker"
type: docs
weight: 350
url: /id/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Menerapkan masker lapisan ke lapisan, kemudian menghapus masker.

```csharp
public void ApplyLayerMask()
```

## Contoh

Kode berikut menunjukkan fitur untuk menerapkan masker ke lapisan.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Lihat Juga

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


