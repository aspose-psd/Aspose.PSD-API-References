---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD for .NET API 参考"
description: "FillLayer 方法。将所有非透明颜色替换为新颜色，并保留原始的 alpha 值以保持平滑的边缘。注意，如果在没有透明度的图像上使用，它会将所有颜色替换为单一颜色。"
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

将所有非透明颜色替换为新颜色，并保留原始 alpha 值以保持平滑边缘。注意：如果在没有透明度的图像上使用，它会将所有颜色替换为单一颜色。

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newColorArgb | Int32 | 用于替换非透明颜色的新颜色 ARGB 值。 |

## 示例

下面的代码演示了对 CMYK ColorMode 16 位的支持以及使用 Aspose.PSD.Graphics 类进行绘图的能力。

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

### 另请参阅

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


