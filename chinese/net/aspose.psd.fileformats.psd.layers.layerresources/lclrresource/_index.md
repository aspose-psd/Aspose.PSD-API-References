---
title: "类 LclrResource"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource 类。类 LclrResource。此资源包含关于 PS 中图层列表中图层颜色的信息。仅此而已。"
type: docs
weight: 2930
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
{{< psd/tize >}}
## LclrResource class

类 LclrResource。此资源包含关于 PS 中图层列表中图层颜色的信息。仅此

```csharp
public class LclrResource : LayerResource
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | 初始化 `LclrResource` 类的新实例。 |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | 初始化 `LclrResource` 类的新实例。 |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | 初始化 `LclrResource` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | 获取或设置图层的颜色。 |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | 获取图层资源的字节长度。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | 获取图层资源所需的最低 PSD 版本。0 表示没有限制。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 获取签名。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | 类型工具信息键。 |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


