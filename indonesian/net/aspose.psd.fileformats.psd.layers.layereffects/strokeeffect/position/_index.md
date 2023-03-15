---
title: StrokeEffect.Position
second_title: Aspose.PSD untuk Referensi .NET API
description: StrokeEffect Properti. Mendapat atau mengatur posisi efek goresan untuk mengontrol penyelarasan goresan Anda ke konten lapisan PSD. Nilainya bisaInside untuk menggambar goresan di dalam konten lapisan PSD atauOutside untuk menggambar goresan di sekitar konten lapisan PSD danCenter untuk menggambar stroke baik di dalam maupun di luar.
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
## StrokeEffect.Position property

Mendapat atau mengatur posisi efek goresan untuk mengontrol penyelarasan goresan Anda ke konten lapisan PSD. Nilainya bisaInside untuk menggambar goresan di dalam konten lapisan PSD, atauOutside untuk menggambar goresan di sekitar konten lapisan PSD, danCenter untuk menggambar stroke baik di dalam maupun di luar.

```csharp
public StrokePosition Position { get; set; }
```

### Contoh

Contoh ini mendemonstrasikan kemampuan untuk menambahkan efek goresan dengan berbagai jenis isian seperti Warna, Gradien, atau Pola.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Menambahkan isian Warna, pada posisi Di dalam
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Menambahkan isian Warna, pada posisi Luar
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Menambahkan isian Warna, di posisi Tengah
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Menambahkan Gradient fill, pada posisi Inside
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Menambahkan pengisian Gradien, pada posisi Luar
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Menambahkan pengisian Gradien, di posisi Tengah
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Menambahkan isian Pola, pada posisi Di dalam
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Menambahkan isian Pola, pada posisi Luar
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Menambahkan isian Pola, di posisi Tengah
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Lihat juga

* enum [StrokePosition](../../strokeposition/)
* class [StrokeEffect](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../strokeeffect/)
* perakitan [Aspose.PSD](../../../)


