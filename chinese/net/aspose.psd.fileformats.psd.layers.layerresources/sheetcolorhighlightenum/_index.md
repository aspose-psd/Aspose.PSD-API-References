---
title: "SheetColorHighlightEnum 枚举"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum 枚举。Sheet 颜色设置的可能颜色。它是 PS 中图层列表里图层的 UI 装饰颜色。"
type: docs
weight: 3320
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

Sheet 颜色设置的可能颜色。它是 PS 中图层列表的 UI 装饰颜色。

```csharp
public enum SheetColorHighlightEnum : short
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| NoColor | `0` | 未指定颜色。 |
| Red | `1` | 红色。 |
| Orange | `2` | 橙色。 |
| Yellow | `3` | 黄色。 |
| Green | `4` | 绿色。 |
| Blue | `5` | 蓝色。 |
| Violet | `6` | 紫色。 |
| Gray | `7` | 灰色。 |

## 示例

以下示例演示了如何在 Aspose.PSD 中更改 Sheet Color Highlight（Sheet 颜色设置）。

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// 在文件中，图层高亮的颜色顺序如下：
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// 图层 Sheet Color 用于可视化地高亮图层。
// 例如，您可以在 PSD 中更新某些图层，然后通过颜色高亮您想要吸引注意的图层。
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // 颜色应当反转
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // lcrl 资源始终出现在 PSD 文件资源列表中。
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // 样式表颜色的反转。设置图层颜色高亮。
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


