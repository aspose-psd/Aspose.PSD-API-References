---
title: "Enum JustificationMode"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. テキスト配置モード"
type: docs
weight: 1690
url: /ja/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

テキスト配置モードです。

```csharp
public enum JustificationMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Left | `0` | 左揃えテキストです。左から右へのモードでは、左位置は左です。右から左へのモードでは、左位置は右です。 |
| Right | `1` | 右揃えテキストです。左から右へのモードでは、右位置は右です。右から左へのモードでは、右位置は左です。 |
| Center | `2` | 中央揃えテキストです。 |

## 例

次のコードは、JustificationMode 列挙体のサポートを示し、テキスト部分の配置を設定します。

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

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


