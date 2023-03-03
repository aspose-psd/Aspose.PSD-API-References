---
title: TextFontInfo.Style
second_title: Aspose.PSD for .NET API リファレンス
description: TextFontInfo 財産. サブファミリ名 から解析されたフォント スタイルを取得します
type: docs
weight: 50
url: /ja/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

サブファミリ名 から解析されたフォント スタイルを取得します

```csharp
public FontStyle Style { get; }
```

### プロパティ値

サブファミリー名から解析されたフォント スタイル

### 例

次のコードは、Aspose.PSD がテキスト レイヤーのインライン フォーマットのプロパティを取得する方法を示しています。

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// 既存の画像を PsdImage クラスのインスタンスにロードします
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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* 組み立て [Aspose.PSD](../../../)


