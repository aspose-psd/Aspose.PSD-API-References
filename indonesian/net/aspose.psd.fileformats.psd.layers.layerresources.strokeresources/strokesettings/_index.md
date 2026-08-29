---
title: "Class StrokeSettings"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.StrokeSettings class. Pengaturan goresan untuk Bentuk"
type: docs
weight: 3420
url: /id/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/
---
{{< psd/tize >}}
## StrokeSettings class

Pengaturan goresan pada Bentuk.

```csharp
public class StrokeSettings : IStrokeSettings
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [StrokeSettings](strokesettings/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Enabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/enabled/) { get; set; } | Mendapatkan atau mengatur apakah Stroke diaktifkan. |
| [Fill](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/fill/) { get; set; } | Mendapatkan atau mengatur pengaturan Isi dari Goresan. |
| [LineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linealignment/) { get; set; } | Mendapatkan atau mengatur perataan garis gaya Goresan. |
| [LineCap](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linecap/) { get; set; } | Mendapatkan atau mengatur tipe cap garis Stroke. |
| [LineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linedashset/) { get; set; } | Mendapatkan atau mengatur array garis putus-putus. |
| [LineJoin](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linejoin/) { get; set; } | Mendapatkan atau mengatur tipe sambungan garis Stroke. |
| [Size](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/size/) { get; set; } | Mendapatkan atau mengatur lebar garis Stroke. |

## Contoh

Kode berikut menunjukkan dukungan rendering Stroke Bentuk.

```csharp
[C#]

string sourceFile = "StrokeShapeTest.psd";
string outputFilePsd = "StrokeShapeTest.out.psd";
string outputFilePng = "StrokeShapeTest.out.png";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer = image.Layers[1];
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    fillSettings.Color = Color.GreenYellow;
    shapeLayer.Update();

    ShapeLayer shapeLayer2 = (ShapeLayer)image.Layers[3];
    GradientFillSettings gradientSettings = (GradientFillSettings)shapeLayer2.Fill;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;
    gradientSettings.Dither = true;
    gradientSettings.Reverse = true;
    gradientSettings.AlignWithLayer = false;
    gradientSettings.Angle = 20;
    gradientSettings.Scale = 50;
    solidGradient.ColorPoints[0].Location = 100;
    solidGradient.ColorPoints[1].Location = 4000;
    solidGradient.TransparencyPoints[0].Location = 200;
    solidGradient.TransparencyPoints[1].Location = 3800;
    solidGradient.TransparencyPoints[0].Opacity = 90;
    solidGradient.TransparencyPoints[1].Opacity = 10;
    shapeLayer2.Update();

    ShapeLayer shapeLayer3 = (ShapeLayer)image.Layers[5];
    StrokeSettings strokeSettings = (StrokeSettings)shapeLayer3.Stroke;
    strokeSettings.Size = 15;
    ColorFillSettings strokeFillSettings = (ColorFillSettings)strokeSettings.Fill;
    strokeFillSettings.Color = Color.GreenYellow;
    shapeLayer3.Update();

    image.Save(outputFilePsd);
    image.Save(outputFilePng, new PngOptions());
}

// Periksa data yang berubah.
using (PsdImage image = (PsdImage)Image.Load(outputFilePsd))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    AssertAreEqual(Color.GreenYellow, fillSettings.Color);

    ShapeLayer shapeLayer2 = (ShapeLayer)image.Layers[3];
    GradientFillSettings gradientSettings = (GradientFillSettings)shapeLayer2.Fill;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;
    AssertAreEqual(true, gradientSettings.Dither);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.AlignWithLayer);
    AssertAreEqual(20.0, gradientSettings.Angle);
    AssertAreEqual(50, gradientSettings.Scale);
    AssertAreEqual(100, solidGradient.ColorPoints[0].Location);
    AssertAreEqual(4000, solidGradient.ColorPoints[1].Location);
    AssertAreEqual(200, solidGradient.TransparencyPoints[0].Location);
    AssertAreEqual(3800, solidGradient.TransparencyPoints[1].Location);
    AssertAreEqual(90.0, solidGradient.TransparencyPoints[0].Opacity);
    AssertAreEqual(10.0, solidGradient.TransparencyPoints[1].Opacity);

    ShapeLayer shapeLayer3 = (ShapeLayer)image.Layers[5];
    StrokeSettings strokeSettings = (StrokeSettings)shapeLayer3.Stroke;
    ColorFillSettings strokeFillSettings = (ColorFillSettings)strokeSettings.Fill;
    AssertAreEqual(15.0, strokeSettings.Size);
    AssertAreEqual(Color.GreenYellow, strokeFillSettings.Color);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Lihat Juga

* interface [IStrokeSettings](../istrokesettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


