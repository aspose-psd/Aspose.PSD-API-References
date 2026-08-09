---
title: "TextLayer.Resize"
second_title: "Aspose.PSD for .NET API 参考"
description: "TextLayer 方法。调整图像大小。使用默认的 LeftTopToLeftTop"
type: docs
weight: 100
url: /zh/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

调整图像大小。使用默认的 LeftTopToLeftTop。

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newWidth | Int32 | 新的宽度。 |
| newHeight | Int32 | 新的高度。 |
| resizeType | ResizeType | 调整转换的类型 [`ResizeType`](../../../aspose.psd/resizetype/) |

## 示例

以下代码演示了使用参数选择缩放机制的 TextLayer.Resize 函数。

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // 它设置文本图层的新大小
    const int NewWidth = 250;
    const int NewHeight = 250;

    // 它设置 resize 函数如何调整图层大小的机制（默认值）
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // 这里使用的文本图层新的缩放机制
    // 不仅图层，文本图层的变换矩阵也将被更改
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // delta 的原因是默认字体不同
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

### 另请参阅

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


