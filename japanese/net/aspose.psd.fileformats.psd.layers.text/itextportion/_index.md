---
title: "インターフェイス ITextPortion"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.Text.ITextPortion インターフェイス。テキスト部分を操作するためのインターフェイス"
type: docs
weight: 3950
url: /ja/net/aspose.psd.fileformats.psd.layers.text/itextportion/
---
{{< psd/tize >}}
## ITextPortion interface

テキスト部分を操作するインターフェイス

```csharp
public interface ITextPortion
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Paragraph](../../aspose.psd.fileformats.psd.layers.text/itextportion/paragraph/) { get; } | スタイルを設定します。 |
| [Style](../../aspose.psd.fileformats.psd.layers.text/itextportion/style/) { get; } | スタイルを取得します。 |
| [Text](../../aspose.psd.fileformats.psd.layers.text/itextportion/text/) { get; set; } | テキストを取得または設定します。 |

## 例

次の例は、右から左への言語に対して ITextPortion を使用したテキスト配置が正しく機能することを示しています。

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

次の例は、Aspose.PSD のテキストレイヤーで異なるスタイルをレンダリングする方法を示しています。

```csharp
[C#]

string sourceFile = "text212.psd";
string etalonFile = "Output_text212.psd";
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

    newPortions[0].Style.Underline = true; // edit text style "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // edit text style "2\r"
    newPortions[2].Style.FauxBold = true; // edit text style "Bold"
    newPortions[3].Style.FauxItalic = true; // edit text style "Italic\r"
    newPortions[3].Style.BaselineShift = -25; // edit text style "Italic\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // edit text style "Lowercasetext"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

次のコードは、テキストレイヤー内の任意のテキスト部分のフォントサイズを取得する方法を示しています。

```csharp
[C#]

// 誤ったフォントサイズが抽出されました
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // 旧 API（最初の段落フォントを使用）
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // 基本フォントサイズを確認しています
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 実際のフォントサイズを確認しています
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // 新 API（1 つのテキストレイヤーは任意の数のフォントサイズを含むことができます）
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // 基本部分のフォントサイズを確認しています
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 実際の部分のフォントサイズを確認しています
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

以下のコード例は、テキスト部分とそのテキストスタイルの編集を示しています。

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

            // 各部分のテキストをチェックしています
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // 段落データをチェックしています
            // 段落の配置が異なります
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // 最初と2番目の段落の他のすべてのプロパティは等しいです
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
                    paragraph.LeadingType != LeadingType.BottomToBottom ||
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

            // スタイルデータをチェックしています
            // スタイルの色とフォントサイズが異なります
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

            // 部分に対する段落とスタイルの編集例
            // 右揃えに設定する
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // 各スタイルの色が異なります。変更は可能ですが、レンダリングは完全にサポートされていません
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // フォントが異なります。変更は可能ですが、レンダリングは完全にサポートされていません
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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../)


