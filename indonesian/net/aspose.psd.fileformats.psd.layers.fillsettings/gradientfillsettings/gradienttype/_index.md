---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD untuk Referensi .NET API
description: GradientFillSettings Properti. Mendapat atau menyetel jenis gradien.
type: docs
weight: 90
url: /id/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

Mendapat atau menyetel jenis gradien.

```csharp
public GradientType GradientType { get; set; }
```

### Nilai properti

Jenis gradien.

### Contoh

Kode berikut menyimpan gambar dengan berbagai jenis gradien dan menunjukkan cara Aspose.PSD menggambar gradien.

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Lihat juga

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* perakitan [Aspose.PSD](../../../)


