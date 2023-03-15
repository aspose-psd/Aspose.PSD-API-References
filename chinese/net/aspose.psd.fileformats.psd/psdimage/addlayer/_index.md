---
title: PsdImage.AddLayer
second_title: Aspose.PSD for .NET API 参考
description: PsdImage 方法. 添加图层
type: docs
weight: 370
url: /zh/net/aspose.psd.fileformats.psd/psdimage/addlayer/
---
## PsdImage.AddLayer method

添加图层。

```csharp
public void AddLayer(Layer layer)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| layer | Layer | 图层。 |

### 例子

下面的示例演示了如果在 Aspose.PSD 中使用简单的构造函数版本，您可以如何在新创建的图层上绘图

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

    // 用钢笔工具画一个矩形
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // 用蓝色实心画笔绘制另一个矩形
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### 也可以看看

* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [PsdImage](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 部件 [Aspose.PSD](../../../)


