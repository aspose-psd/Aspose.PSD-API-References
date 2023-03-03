---
title: FillLayer.ReplaceNonTransparentColors
second_title: Aspose.PSD for .NET API 参考
description: FillLayer 方法. 用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘 注意如果您在没有透明度的图像上使用它所有颜色将被替换为一个颜色
type: docs
weight: 40
url: /zh/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

用新颜色替换所有非透明颜色并保留原始 alpha 值以保存平滑边缘。 注意：如果您在没有透明度的图像上使用它，所有颜色将被替换为一个颜色。

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newColorArgb | Int32 | 用于替换非透明颜色的新颜色 ARGB 值。 |

### 例子

下面的代码演示了对 CMYK ColorMode 16 位的支持以及使用 Aspose.PSD.Graphics 类进行绘图的能力。

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### 也可以看看

* class [FillLayer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* 部件 [Aspose.PSD](../../../)


