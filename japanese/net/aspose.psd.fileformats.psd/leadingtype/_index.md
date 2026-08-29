---
title: "Enum LeadingType"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.LeadingType enum. Photoshop の行間タイプ（行間の距離の種類）"
type: docs
weight: 4030
url: /ja/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Photoshop のリーディングタイプ（行間の距離の種類）。

```csharp
public enum LeadingType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| BottomToBottom | `0` | 下から下への行間。 |
| TopToTop | `1` | 上から上への行間。 |

## 例

以下のコードは、Paragraph 設定から Bottom-to-bottom と Top-to-Top の行間モードのサポートを示しています。

```csharp
[C#]

string input = "leadingMode.psd";
string output = "output_leadingMode.png";

using (var psdImage = (PsdImage)Image.Load(input, new PsdLoadOptions()))
{
    IText text1 = ((TextLayer)psdImage.Layers[1]).TextData;
    foreach (var textPortion in text1.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.TopToTop; // Change LeadingType value   
    }
    text1.Items[8].Text = "TopToTop";
    text1.Items[8].Style.FillColor = Color.ForestGreen;
    text1.UpdateLayerData();

    IText text2 = ((TextLayer)psdImage.Layers[2]).TextData;
    foreach (var textPortion in text2.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.BottomToBottom; // Change LeadingType value   
    }
    text2.Items[8].Text = "BottomToBottom";
    text2.Items[8].Style.FillColor = Color.ForestGreen;
    text2.UpdateLayerData();

    psdImage.Save(output, new PngOptions());
}
```

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


