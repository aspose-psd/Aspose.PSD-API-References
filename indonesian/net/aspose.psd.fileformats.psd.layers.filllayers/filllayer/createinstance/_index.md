---
title: FillLayer.CreateInstance
second_title: Aspose.PSD untuk Referensi .NET API
description: FillLayer metode. Bangun instance baru dariFillLayer kelas berdasarkan jenis isian.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

Bangun instance baru dari[`FillLayer`](../) kelas berdasarkan jenis isian.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| fillType | FillType | Jenis lapisan pengisi. |

### Nilai Pengembalian

Mengembalikan instance baru dari[`FillLayer`](../) kelas berdasarkan jenis isian.

### Contoh

Contoh berikut menunjukkan cara menambahkan lapisan tipe FillLayer saat runtime.

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

### Lihat juga

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* perakitan [Aspose.PSD](../../../)


