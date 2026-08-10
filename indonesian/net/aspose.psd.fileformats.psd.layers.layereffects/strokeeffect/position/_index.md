---
title: "StrokeEffect.Position"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "StrokeEffect property. Mendapatkan atau mengatur posisi efek stroke untuk mengontrol perataan stroke Anda terhadap konten lapisan PSD. Nilai dapat berupa Inside untuk menggambar stroke di dalam konten lapisan PSD atau Outside untuk menggambar stroke di sekitar konten lapisan PSD dan Center untuk menggambar stroke baik di dalam maupun di luar"
type: docs
weight: 70
url: /id/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
{{< psd/tize >}}
## StrokeEffect.Position property

Mendapatkan atau mengatur posisi efek goresan untuk mengontrol perataan goresan Anda terhadap konten lapisan PSD. Nilainya dapat berupa Inside untuk menggambar goresan di dalam konten lapisan PSD, atau Outside untuk menggambar goresan di sekitar konten lapisan PSD, dan Center untuk menggambar goresan baik di dalam maupun di luar.

```csharp
public StrokePosition Position { get; set; }
```

## Contoh

Contoh ini menunjukkan kemampuan menambahkan efek goresan dengan berbagai jenis isi seperti Warna, Gradien, atau Pola.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Menambahkan isi Warna, pada posisi Dalam
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Menambahkan isi Warna, pada posisi Luar
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Menambahkan isi Warna, pada posisi Tengah
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Menambahkan isi Gradien, pada posisi Dalam
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Menambahkan isi Gradien, pada posisi Luar
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Menambahkan isi Gradien, pada posisi Tengah
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Menambahkan isi Pola, pada posisi Dalam
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Menambahkan isi Pola, pada posisi Luar
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Menambahkan isi Pola, pada posisi Tengah
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### Lihat Juga

* enum [StrokePosition](../../strokeposition/)
* class [StrokeEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


