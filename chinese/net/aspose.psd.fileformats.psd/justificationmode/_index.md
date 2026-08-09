---
title: "枚举 JustificationMode"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode 枚举。文本对齐模式"
type: docs
weight: 1690
url: /zh/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

文本对齐模式。

```csharp
public enum JustificationMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Left | `0` | 左对齐文本。在从左到右模式下，左位置是左。在从右到左模式下，左位置是右。 |
| Right | `1` | 右对齐文本。在从左到右模式下，右位置是右。在从右到左模式下，右位置是左。 |
| Center | `2` | 居中文本。 |

## 示例

以下代码演示了如何使用 JustificationMode 枚举来设置文本段落的对齐方式。

```csharp
[C#]

string src = "source1107.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (var image = (PsdImage) Image.Load(src))
{
    var txtLayer = image.AddTextLayer("Text line1\rText line2\rText line3",
        new Rectangle(200, 200, 500, 500));
    var portions = txtLayer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Left;
    portions[1].Paragraph.Justification = JustificationMode.Right;
    portions[2].Paragraph.Justification = JustificationMode.Center;

    foreach (var portion in portions)
    {
        portion.Style.FontSize = 24;
    }

    txtLayer.TextData.UpdateLayerData();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### 另请参阅

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


