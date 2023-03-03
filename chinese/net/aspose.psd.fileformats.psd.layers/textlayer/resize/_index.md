---
title: TextLayer.Resize
second_title: Aspose.PSD for .NET API 参考
description: TextLayer 方法. 调整图像大小默认值LeftTopToLeftTop使用.
type: docs
weight: 90
url: /zh/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

调整图像大小。默认值LeftTopToLeftTop使用.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新宽度. |
| newHeight | Int32 | 新高度. |
| resizeType | ResizeType | 调整大小转换的类型[`ResizeType`](../../../aspose.psd/resizetype/) |

### 例子

下面的代码演示了带有参数的 TextLayer.Resize 函数来选择调整大小的机制。

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // 它设置文本层的新大小
    const int NewWidth = 250;
    const int NewHeight = 250;

    // 它设置调整大小函数如何调整图层大小的机制（默认值）
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // 使用此处调整文本层大小的新机制
    // 不仅是图层，文本图层的变换矩阵也会发生变化
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // delta 的原因是不同的默认字体
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // 一切正常
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### 也可以看看

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* 部件 [Aspose.PSD](../../../)


