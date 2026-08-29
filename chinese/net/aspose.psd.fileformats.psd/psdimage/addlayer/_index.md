---
title: "PsdImage.AddLayer"
second_title: "Aspose.PSD for .NET API 参考"
description: "PsdImage 方法。添加图层"
type: docs
weight: 390
url: /zh/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
{{< psd/tize >}}
## PsdImage.AddLayer method

添加图层。

```csharp
public void AddLayer(Layer layer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | 图层 | 图层。 |

## 示例

以下示例演示了在 Aspose.PSD 中使用简易构造函数版本时，如何在新创建的图层上绘图

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // 使用 Pen 工具绘制矩形
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // 使用蓝色实心画刷绘制另一个矩形
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 另请参阅

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


