---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode FillLayer. Membuat instance baru dari kelas FillLayer berdasarkan tipe isian"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Membuat instance baru dari kelas [`FillLayer`](../) berdasarkan tipe isian.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillType | FillType | Tipe lapisan isian. |

### Nilai Kembalian

Mengembalikan instance baru dari kelas [`FillLayer`](../) berdasarkan tipe isian.

## Contoh

Contoh berikut menunjukkan cara menambahkan lapisan tipe FillLayer pada waktu berjalan.

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### Lihat Juga

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


