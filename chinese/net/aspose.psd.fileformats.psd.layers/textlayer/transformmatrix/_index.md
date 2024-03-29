---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD for .NET API 参考
description: TextLayer 财产. 获取或设置变换矩阵
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

获取或设置变换矩阵

```csharp
public double[] TransformMatrix { get; set; }
```

### 适当的价值

变换矩阵

### 例子

以下代码演示了如何获取文本层中任何文本部分的字体大小。

```csharp
[C#]

// 提取错误的字体大小 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // 旧 API（使用第一段字体）
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // 检查基本字体大小
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 检查真实字体大小
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // 新 API（一个文本层可以包含任意数量的字体大小）
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // 检查基本部分字体大小
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 检查实部字体大小
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### 也可以看看

* class [TextLayer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* 部件 [Aspose.PSD](../../../)


