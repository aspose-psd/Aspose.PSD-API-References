---
title: ITextParagraph
second_title: Aspose.PSD for .NET API 参考
description: 处理段落的界面
type: docs
weight: 3410
url: /zh/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
## ITextParagraph interface

处理段落的界面

```csharp
public interface ITextParagraph
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate) { get; set; } | 获取或设置一个值，指示是否[自动连字符]。 |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading) { get; set; } | 获取或设置自动行距。 |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari) { get; set; } | 获取或设置一个值，该值指示此[`ITextParagraph`](../itextparagraph)是否为 burasagiri。 |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens) { get; set; } | 获取或设置连续的连字符。 |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent) { get; set; } | 获取或设置结束缩进。 |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer) { get; set; } | 获取或设置一个值，表示是否[每行作曲家]。 |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent) { get; set; } | 获取或设置第一行缩进。 |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing) { get; set; } | 获取或设置字形间距。 |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging) { get; set; } | 获取或设置一个值，该值指示此[`ITextParagraph`](../itextparagraph)是否挂起。 |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize) { get; set; } | 获取或设置连字符的大小。 |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification) { get; set; } | 获取或设置对正。 |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder) { get; set; } | 获取或设置 kinsoku 顺序。 |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype) { get; set; } | 获取或设置前导的类型。 |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing) { get; set; } | 获取或设置字母间距。 |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen) { get; set; } | 获取或设置后连字符。 |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen) { get; set; } | 获取或设置前连字符。 |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter) { get; set; } | 获取或设置后面的空格。 |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore) { get; set; } | 获取或设置之前的空间。 |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent) { get; set; } | 获取或设置开始缩进。 |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing) { get; set; } | 获取或设置字间距。 |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone) { get; set; } | 获取或设置区域。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply)(ITextParagraph) | 应用指定的段落。 |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal)(ITextParagraph) | 判断指定段落是否相等。 |

### 例子

下面的例子演示了通过ITextPortion的Text Alignment for right-to-left语言工作正常。

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

下面的代码示例演示了编辑文本部分及其文本样式。

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

            // 检查每个部分的文本
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // 检查段落数据
            // 段落有不同的理由
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            //第一段和第二段的所有其他属性相等
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

            // 检查样式数据
            // 样式有不同的颜色和字体大小
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

            // 文本编辑示例
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // 删除文本部分的示例
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // 添加新文本部分的示例
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // 部分段落和样式编辑示例
            // 设置右对齐
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // 每种样式的颜色不同。将更改，但不完全支持渲染
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // 不同的字体。将更改，但不完全支持渲染
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

### 也可以看看

* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text)
* 部件 [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
