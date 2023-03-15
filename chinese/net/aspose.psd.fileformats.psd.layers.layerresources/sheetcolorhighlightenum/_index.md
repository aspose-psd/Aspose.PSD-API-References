---
title: Enum SheetColorHighlightEnum
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum 枚举. Sheet颜色设置的可能颜色 PS 图层列表中图层的UI装饰色
type: docs
weight: 2970
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
## SheetColorHighlightEnum enumeration

Sheet颜色设置的可能颜色。 PS 图层列表中图层的UI装饰色

```csharp
public enum SheetColorHighlightEnum : short
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| NoColor | `0` | 未指定颜色。 |
| Red | `1` | 红色。 |
| Orange | `2` | 橙色。 |
| Yellow | `3` | 黄色。 |
| Green | `4` | 绿色。 |
| Blue | `5` | 蓝色。 |
| Violet | `6` | 紫色。 |
| Gray | `7` | 灰色。 |

### 例子

以下示例演示如何更改 Aspose.PSD 中的工作表颜色突出显示（工作表颜色设置）

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// 在文件中图层高亮的颜色是按照这个顺序的
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

// Layer Sheet Color 用于在视觉上突出显示图层。 
// 例如，您可以更新 PSD 中的一些图层，然后用颜色突出显示您想要引起注意的图层。
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // 颜色应该反转
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
            // lcrl 资源始终出现在 psd 文件资源列表中。
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

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


