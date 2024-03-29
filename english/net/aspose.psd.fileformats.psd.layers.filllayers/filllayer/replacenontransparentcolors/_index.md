---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD for .NET API Reference
description: FillLayer method. Replaces all nontransparent colors with new color and preserves original alpha value to save smooth edges. Note if you use it on images without transparency all colors will be replaced with a single one
type: docs
weight: 40
url: /net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

Replaces all non-transparent colors with new color and preserves original alpha value to save smooth edges. Note: if you use it on images without transparency, all colors will be replaced with a single one.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Parameter | Type | Description |
| --- | --- | --- |
| newColorArgb | Int32 | New color ARGB value to replace non transparent colors with. |

## Examples

The following code demonstrates the support of the CMYK ColorMode 16 bit and the ability to drawing by using Aspose.PSD.Graphics class.

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### See Also

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


