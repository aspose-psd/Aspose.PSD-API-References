---
title: Class AiRasterImageSection
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Ai.AiRasterImageSection classe. La section Image raster AI
type: docs
weight: 1280
url: /fr/net/aspose.psd.fileformats.ai/airasterimagesection/
---
## AiRasterImageSection class

La section Image raster AI

```csharp
public sealed class AiRasterImageSection
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Angle](../../aspose.psd.fileformats.ai/airasterimagesection/angle/) { get; } | Obtient l'angle. |
| [Height](../../aspose.psd.fileformats.ai/airasterimagesection/height/) { get; } | Obtient la hauteur. |
| [ImageRectangle](../../aspose.psd.fileformats.ai/airasterimagesection/imagerectangle/) { get; } | Obtient le rectangle de l'image. |
| [LeftBottomShift](../../aspose.psd.fileformats.ai/airasterimagesection/leftbottomshift/) { get; } | Obtient le décalage inférieur gauche. |
| [Name](../../aspose.psd.fileformats.ai/airasterimagesection/name/) { get; } | Obtient le nom de l'image raster. |
| [OffsetX](../../aspose.psd.fileformats.ai/airasterimagesection/offsetx/) { get; } | Obtient le décalage X. |
| [OffsetY](../../aspose.psd.fileformats.ai/airasterimagesection/offsety/) { get; } | Obtient le décalage Y. |
| [Pixels](../../aspose.psd.fileformats.ai/airasterimagesection/pixels/) { get; } | Obtient le tableau de pixels de couleur int. |
| [Width](../../aspose.psd.fileformats.ai/airasterimagesection/width/) { get; } | Obtient la largeur. |

### Exemples

Le code suivant montre comment charger les paramètres des images raster dans des fichiers au format AI.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* Assemblée [Aspose.PSD](../../)


