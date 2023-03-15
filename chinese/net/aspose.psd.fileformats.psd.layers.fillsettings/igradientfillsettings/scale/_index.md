---
title: IGradientFillSettings.Scale
second_title: Aspose.PSD for .NET API 参考
description: IGradientFillSettings 财产. 获取或设置比例
type: docs
weight: 100
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

获取或设置比例。

```csharp
public int Scale { get; set; }
```

### 适当的价值

规模.

### 例子

下面的例子演示了如何使用 Scale 属性来缩放带有渐变的 FillLayer。

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // 获取填充层
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // 更新比例值
    settings.Scale = 200;
    fillLayer.Update(); // 更新像素数据

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 也可以看看

* interface [IGradientFillSettings](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* 部件 [Aspose.PSD](../../../)


