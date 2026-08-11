---
title: "ITextStyle.FontIndex"
second_title: "Aspose.PSD for .NET API Reference"
description: "ITextStyle プロパティ。フォントインデックスを取得します"
type: docs
weight: 110
url: /ja/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
{{< psd/tize >}}
## ITextStyle.FontIndex property

フォントインデックスを取得します。

```csharp
public int FontIndex { get; }
```

### Property Value

フォントです。

## 例

以下のコードは、Aspose.PSD がテキストレイヤーのインライン書式設定のプロパティを取得する方法を示しています。

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// 既存の画像を PsdImage クラスのインスタンスにロードします。
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{

    var layers = psdImage.Layers;
    for (int index = 0; index < layers.Length; index++)
    {
        var layer = layers[index];
        if (!(layer is TextLayer))
        {
            continue;
        }

        var textLayer = (TextLayer)layer;

        // テキストレイヤーに含まれるフォントを取得します
        var fonts = textLayer.GetFonts();
        var textPortions = textLayer.TextData.Items;

        foreach (var textPortion in textPortions)
        {
            TextFontInfo font = fonts[textPortion.Style.FontIndex];
            if (font != null)
            {
                switch (font.Style)
                {
                    case FontStyle.Regular:
                        regularText.Add(textPortion);
                        break;
                    case FontStyle.Bold:
                        boldText.Add(textPortion);
                        break;
                    case FontStyle.Italic:
                        italicText.Add(textPortion);
                        break;
                    default:
                        throw new ArgumentOutOfRangeException();
                }
            }
        }
    }
}
```

### 関連項目

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


