---
title: "Gränssnitt IShapeLayer"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.Layers.IShapeLayer-gränssnitt. Beskriver egenskaperna för Shape-lagret."
type: docs
weight: 2260
url: /sv/net/aspose.psd.fileformats.psd.layers/ishapelayer/
---
{{< psd/tize >}}
## IShapeLayer interface

Beskriver egenskaperna för Formlager.

```csharp
public interface IShapeLayer
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Fill](../../aspose.psd.fileformats.psd.layers/ishapelayer/fill/) { get; set; } | Fyllningsinställningar som används för att fylla den interna ytan av former. |
| [Path](../../aspose.psd.fileformats.psd.layers/ishapelayer/path/) { get; } | Mängden Paths som finns i ett Shape-lager. |
| [Stroke](../../aspose.psd.fileformats.psd.layers/ishapelayer/stroke/) { get; set; } | Streckinställningar för former. |

## Exempel

Följande kod visar stöd för rendering av formstreck.

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

// Kontrollera ändrade data.
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

### Se även

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


