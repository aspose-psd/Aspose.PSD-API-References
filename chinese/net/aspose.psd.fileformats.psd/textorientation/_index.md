---
title: Enum TextOrientation
second_title: Aspose.PSD for .NET API 参考
description: Aspose.PSD.FileFormats.Psd.TextOrientation 枚举. 文本方向模式的枚举
type: docs
weight: 4010
url: /zh/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

文本方向模式的枚举。

```csharp
public enum TextOrientation
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Horizontal | `0` | 水平文本方向。 |
| Vertical | `2` | 垂直文本方向。 |

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

* 命名空间 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 部件 [Aspose.PSD](../../)


