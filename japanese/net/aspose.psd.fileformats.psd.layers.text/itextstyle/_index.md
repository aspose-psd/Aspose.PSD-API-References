---
title: Interface ITextStyle
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.Text.ITextStyle インターフェース. Text Style を操作するためのインターフェイス
type: docs
weight: 3540
url: /ja/net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---
## ITextStyle interface

Text Style を操作するためのインターフェイス

```csharp
public interface ITextStyle
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoKerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autokerning/) { get; set; } | 自動カーニングを取得または設定します。 |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autoleading/) { get; set; } | [自動送り]かどうかを示す値を取得または設定します。 |
| [BaselineShift](../../aspose.psd.fileformats.psd.layers.text/itextstyle/baselineshift/) { get; set; } | ベースライン シフト。 |
| [ContextualAlternates](../../aspose.psd.fileformats.psd.layers.text/itextstyle/contextualalternates/) { get; set; } | 文字を接続するために使用される文脈上の代替文字. |
| [DiscretionaryLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/discretionaryligatures/) { get; set; } | 特にスクリプト フォントで、文字を接続するために使用される任意の合字。 |
| [FauxBold](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxbold/) { get; set; } | フェイクボールドが有効になっていることを取得または設定します. |
| [FauxItalic](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxitalic/) { get; set; } | フェイクボールドが有効になっていることを取得または設定します. |
| [FillColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fillcolor/) { get; set; } | 塗りつぶしの色を取得または設定します。 |
| [FontBaseline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontbaseline/) { get; set; } | フォントのベースライン。 |
| [FontCaps](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontcaps/) { get; set; } | フォント caps. |
| [FontIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/) { get; } | フォント インデックスを取得します。 |
| [FontName](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontname/) { get; set; } | フォント名を取得または設定します。 |
| [FontSize](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontsize/) { get; set; } | フォントのサイズを取得または設定します。 |
| [Fractions](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fractions/) { get; set; } | 分数記号は特別なグリフに置き換えることができます. |
| [HindiNumbers](../../aspose.psd.fileformats.psd.layers.text/itextstyle/hindinumbers/) { get; set; } | [ヒンディー数字] かどうかを示す値を取得または設定します。 |
| [HorizontalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/horizontalscale/) { get; set; } | 水平スケール。 |
| [IsStandardVerticalRomanAlignmentEnabled](../../aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/) { get; set; } | 標準の垂直ローマン配置を取得または設定します。 これは BaselineDirection リソース値に基づいており、テキストの向きがVertical . |
| [Kerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/kerning/) { get; set; } | カーニングを取得または設定します。 |
| [LanguageIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/languageindex/) { get; } | 言語インデックスを取得します。 |
| [Leading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/leading/) { get; set; } | 先頭を取得または設定します。 |
| [NoBreak](../../aspose.psd.fileformats.psd.layers.text/itextstyle/nobreak/) { get; set; } | ブレークなし値を取得または設定します。 |
| [StandardLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/standardligatures/) { get; set; } | 文字同士を接続するために使用される標準的な文脈上の合字. |
| [Strikethrough](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strikethrough/) { get; set; } | [取り消し線]. かどうかを示す値を取得または設定します。 |
| [StrokeColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strokecolor/) { get; set; } | ストロークの色を取得または設定します。 |
| [Tracking](../../aspose.psd.fileformats.psd.layers.text/itextstyle/tracking/) { get; set; } | トラッキングを取得または設定します。 |
| [Underline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/underline/) { get; set; } | [下線]. かどうかを示す値を取得または設定します。 |
| [VerticalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/verticalscale/) { get; set; } | 垂直スケール。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextstyle/apply/)(ITextStyle) | 指定したスタイルを適用します。 |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextstyle/isequal/)(ITextStyle) | 指定されたスタイルが等しいかどうかを判断します。 |

### 例

次の例は、Aspose.PSD の 1 つのテキスト レイヤーでさまざまなスタイルをレンダリングする方法を示しています。

```csharp
[C#]

string sourceFile = "text212.psd";
string etalonFile = "Ethalon_text212.psd";
string outputFile = "Output_text212.psd";

using (var img = (PsdImage)Image.Load(sourceFile))
{
    TextLayer textLayer = (TextLayer)img.Layers[1];
    IText textData = textLayer.TextData;
    ITextStyle defaultStyle = textData.ProducePortion().Style;
    ITextParagraph defaultParagraph = textData.ProducePortion().Paragraph;
    defaultStyle.FillColor = Color.DimGray;
    defaultStyle.FontSize = 51;

    textData.Items[1].Style.Strikethrough = true;

    ITextPortion[] newPortions = textData.ProducePortions(
        new string[]
        {
          "E=mc", "2\r", "Bold", "Italic\r",
          "Lowercasetext"
        },
        defaultStyle,
        defaultParagraph);

    newPortions[0].Style.Underline = true; // テキストスタイル「E=mc」を編集
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // テキスト スタイル "2\r" を編集
    newPortions[2].Style.FauxBold = true; // テキストスタイル「太字」を編集
    newPortions[3].Style.FauxItalic = true; // テキスト スタイル "Italic\r" を編集します
    newPortions[3].Style.BaselineShift = -25; // テキスト スタイル "Italic\r" を編集します
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // テキスト スタイル "Lowercasetext" を編集します

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

次のコードは、テキスト レイヤー内の任意のテキスト部分のフォント サイズを取得する方法を示しています。

```csharp
[C#]

// 間違ったフォント サイズを抽出しました 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // 古い API (最初の段落のフォントを使用)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // ベースフォントサイズのチェック
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 実際のフォントサイズをチェック
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // 新しい API (1 つのテキスト レイヤーに任意の数のフォント サイズを含めることができます)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // ベース部分のフォントサイズチェック
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 実部フォントサイズチェック
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

次のコード例は、テキスト部分の編集とそのテキスト スタイルを示しています。

```csharp
[C#]

const double Tolerance = 0.0001;
var filePath = "ThreeColorsParagraphs.psd";
var outputPath = "ThreeColorsParagraph_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < im.Layers.Length; i++)
    {
        var layer = im.Layers[i] as TextLayer;

        if (layer != null)
        {
            var portions = layer.TextData.Items;

            if (portions.Length != 4)
            {
                throw new Exception();
            }

            // すべての部分のテキストをチェック
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // 段落データのチェック
            // 段落ごとに正当性が異なります
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // 最初と 2 番目の段落の他のすべてのプロパティは等しい
            for (int j = 0; j < portions.Length; j++)
            {
                var paragraph = portions[j].Paragraph;

                if (Math.Abs(paragraph.AutoLeading - 1.2) > Tolerance ||
                    paragraph.AutoHyphenate != false ||
                    paragraph.Burasagari != false ||
                    paragraph.ConsecutiveHyphens != 8 ||
                    Math.Abs(paragraph.StartIndent) > Tolerance ||
                    Math.Abs(paragraph.EndIndent) > Tolerance ||
                    paragraph.EveryLineComposer != false ||
                    Math.Abs(paragraph.FirstLineIndent) > Tolerance ||
                    paragraph.GlyphSpacing.Length != 3 ||
                    Math.Abs(paragraph.GlyphSpacing[0] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[1] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[2] - 1) > Tolerance ||
                    paragraph.Hanging != false ||
                    paragraph.HyphenatedWordSize != 6 ||
                    paragraph.KinsokuOrder != 0 ||
                    paragraph.LetterSpacing.Length != 3 ||
                    Math.Abs(paragraph.LetterSpacing[0]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[1]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[2]) > Tolerance ||
                    paragraph.LeadingType != LeadingMode.Auto ||
                    paragraph.PreHyphen != 2 ||
                    paragraph.PostHyphen != 2 ||
                    Math.Abs(paragraph.SpaceBefore) > Tolerance ||
                    Math.Abs(paragraph.SpaceAfter) > Tolerance ||
                    paragraph.WordSpacing.Length != 3 ||
                    Math.Abs(paragraph.WordSpacing[0] - 0.8) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[1] - 1.0) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[2] - 1.33) > Tolerance ||
                    Math.Abs(paragraph.Zone - 36.0) > Tolerance)
                {
                    throw new Exception();
                }
            }

            // スタイルデータのチェック
            // スタイルによって色とフォント サイズが異なります
            if (Math.Abs(portions[0].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[1].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[2].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[3].Style.FontSize - 10) > Tolerance)
            {
                throw new Exception();
            }

            if (portions[0].Style.FillColor != Color.FromArgb(255, 145, 0, 0) ||
                portions[1].Style.FillColor != Color.FromArgb(255, 201, 128, 2) ||
                portions[2].Style.FillColor != Color.FromArgb(255, 18, 143, 4) ||
                portions[3].Style.FillColor != Color.FromArgb(255, 145, 42, 100))
            {
                throw new Exception();
            }

            for (int j = 0; j < portions.Length; j++)
            {
                var style = portions[j].Style;

                if (style.AutoLeading != true ||
                    style.HindiNumbers != false ||
                    style.Kerning != 0 ||
                    style.Leading != 0 ||
                    style.StrokeColor != Color.FromArgb(255, 175, 90, 163) ||
                    style.Tracking != 50)
                {
                    throw new Exception();
                }
            }

            // テキスト編集の例
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // テキスト部分の削除例
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // 新しいテキスト部分を追加する例
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // 部分の段落とスタイルの編集の例
            // 右揃えを設定
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // スタイルごとに異なる色。は変更されますが、レンダリングは完全にはサポートされていません
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // 別のフォント。は変更されますが、レンダリングは完全にはサポートされていません
            portions[0].Style.FontSize = 6;
            portions[1].Style.FontSize = 8;
            portions[2].Style.FontSize = 10;

            layer.TextData.UpdateLayerData();

            im.Save(outputPath, new PsdOptions(im));

            break;
        }
    }
}
```

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* 組み立て [Aspose.PSD](../../)


