---
title: Enum JustificationMode
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.JustificationMode 列挙. テキスト配置モード.
type: docs
weight: 1650
url: /ja/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

テキスト配置モード.

```csharp
public enum JustificationMode
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| Left | `0` | 左揃えのテキスト。 |
| Right | `1` | 右揃えのテキスト。 |
| Center | `2` | 中央のテキスト。 |

### 例

次のコードは、テキスト部分のテキスト配置を設定するための JustificationMode 列挙型のサポートを示しています。

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

* 名前空間 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 組み立て [Aspose.PSD](../../)


