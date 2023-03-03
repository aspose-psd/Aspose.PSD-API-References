---
title: IText.TextOrientation
second_title: Aspose.PSD for .NET API 参考
description: IText 财产. 获取或设置文本方向
type: docs
weight: 30
url: /zh/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

获取或设置文本方向。

```csharp
public TextOrientation TextOrientation { get; set; }
```

### 适当的价值

文本方向。

### 例子

以下代码演示了编辑新 TextOrientation 属性的能力。这暂时不会影响渲染，但只允许您编辑属性值。

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // 正确读法
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // 正确读法
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### 也可以看看

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* 部件 [Aspose.PSD](../../../)


