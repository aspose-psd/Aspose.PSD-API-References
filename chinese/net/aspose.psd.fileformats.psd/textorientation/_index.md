---
title: "枚举 TextOrientation"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.TextOrientation 枚举。文本方向模式的枚举"
type: docs
weight: 4480
url: /zh/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

文本方向模式的枚举。

```csharp
public enum TextOrientation
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Horizontal | `0` | 水平文本方向。 |
| Vertical | `2` | 垂直文本方向。 |

## 示例

以下代码演示了编辑新 TextOrientation 属性的能力。此操作目前不会影响渲染，只是允许您编辑属性值。

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // 正确读取
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
        // 正确读取
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


