---
title: Interface ITextParagraph
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.Text.ITextParagraph インターフェース. paragraph で動作するインターフェイス
type: docs
weight: 3520
url: /ja/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
## ITextParagraph interface

paragraph で動作するインターフェイス

```csharp
public interface ITextParagraph
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate/) { get; set; } | [自動ハイフン] かどうかを示す値を取得または設定します。 |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading/) { get; set; } | 自動行送りを取得または設定します。 |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari/) { get; set; } | これが`ITextParagraph`ブラサギリです. |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens/) { get; set; } | 連続するハイフンを取得または設定します。 |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent/) { get; set; } | 終了インデントを取得または設定します。 |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer/) { get; set; } | [すべての行コンポーザー] かどうかを示す値を取得または設定します。 |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent/) { get; set; } | 最初の行のインデントを取得または設定します。 |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing/) { get; set; } | グリフの間隔を取得または設定します。 |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging/) { get; set; } | これが`ITextParagraph`ぶら下がっています. |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize/) { get; set; } | ハイフンでつながれた単語のサイズを取得または設定します。 |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification/) { get; set; } | 位置合わせを取得または設定します。 |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder/) { get; set; } | 禁則順序を取得または設定します。 |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype/) { get; set; } | 先頭のタイプを取得または設定します。 |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing/) { get; set; } | 文字間隔を取得または設定します。 |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen/) { get; set; } | ポスト ハイフンを取得または設定します。 |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen/) { get; set; } | プレハイフンを取得または設定します。 |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter/) { get; set; } | 後のスペースを取得または設定します。 |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore/) { get; set; } | 前のスペースを取得または設定します。 |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent/) { get; set; } | 開始インデントを取得または設定します。 |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing/) { get; set; } | 単語間隔を取得または設定します。 |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone/) { get; set; } | ゾーンを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply/)(ITextParagraph) | 指定された段落を適用します。 |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal/)(ITextParagraph) | 指定された段落が等しいかどうかを判断します。 |

### 例

次の例は、右から左へ記述する言語の ITextPortion によるテキストの配置が正しく機能することを示しています。

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


