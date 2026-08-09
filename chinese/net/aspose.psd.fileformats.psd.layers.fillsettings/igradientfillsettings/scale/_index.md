---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD for .NET API 参考"
description: "IGradientFillSettings 属性。获取或设置以百分比表示的归一化渐变比例"
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

获取或设置 **normalized** 渐变比例（百分比）。

```csharp
public int Scale { get; set; }
```

### Property Value

比例。

## 示例

以下示例演示如何使用 Scale 属性对带有渐变的 FillLayer 进行缩放。

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // 获取填充图层
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
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 另请参阅

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


