---
title: Class LclrResource
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource 班级. Class LclrResource. 此资源包含有关图层列表中图层颜色的信息是 PS这只是
type: docs
weight: 2620
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Class LclrResource. 此资源包含有关图层列表中图层颜色的信息是 PS。这只是

```csharp
public class LclrResource : LayerResource
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | 初始化一个新的实例`LclrResource`类. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | 初始化一个新的实例`LclrResource`类. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | 初始化一个新的实例`LclrResource`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | 获取或设置图层的颜色。 |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | 获取图层资源键。 |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | 获取以字节为单位的图层资源长度。 |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | 获取 psd 版本。 |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | 获取签名. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | 将资源保存到指定的流容器中。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | 返回一个String代表这个实例. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | 类型工具信息键。 |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 部件 [Aspose.PSD](../../)


