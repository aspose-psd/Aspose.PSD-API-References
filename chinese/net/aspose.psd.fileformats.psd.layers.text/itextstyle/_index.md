---
title: ITextStyle
second_title: Aspose.PSD for .NET API 参考
description: 使用文本样式的界面
type: docs
weight: 3480
url: /zh/net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---
## ITextStyle interface

使用文本样式的界面

```csharp
public interface ITextStyle
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AutoKerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autokerning) { get; set; } | 获取或设置自动字距调整。 |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autoleading) { get; set; } | 获取或设置一个值，指示是否[自动领先]. |
| [BaselineShift](../../aspose.psd.fileformats.psd.layers.text/itextstyle/baselineshift) { get; set; } | 基线偏移。 |
| [ContextualAlternates](../../aspose.psd.fileformats.psd.layers.text/itextstyle/contextualalternates) { get; set; } | 用于将字母连接在一起的上下文替代词。 |
| [DiscretionaryLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/discretionaryligatures) { get; set; } | 用于连接字母的任意连字，尤其是在脚本字体中。 |
| [FauxBold](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxbold) { get; set; } | 获取或设置启用仿粗体。 |
| [FauxItalic](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxitalic) { get; set; } | 获取或设置启用仿粗体。 |
| [FillColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fillcolor) { get; set; } | 获取或设置填充的颜色。 |
| [FontBaseline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontbaseline) { get; set; } | 字体基线。 |
| [FontCaps](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontcaps) { get; set; } | 字体大写。 |
| [FontIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex) { get; } | 获取字体索引。 |
| [FontName](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontname) { get; set; } | 获取或设置字体名称。 |
| [FontSize](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontsize) { get; set; } | 获取或设置字体大小。 |
| [Fractions](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fractions) { get; set; } | 分数符号可以用特殊字形替换。 |
| [HindiNumbers](../../aspose.psd.fileformats.psd.layers.text/itextstyle/hindinumbers) { get; set; } | 获取或设置一个值，指示是否 [印地语数字]. |
| [HorizontalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/horizontalscale) { get; set; } | 水平刻度。 |
| [Kerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/kerning) { get; set; } | 获取或设置字距调整。 |
| [LanguageIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/languageindex) { get; } | 获取语言索引。 |
| [Leading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/leading) { get; set; } | 获取或设置前导。 |
| [StandardLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/standardligatures) { get; set; } | 用于将字母连接在一起的标准上下文连字。 |
| [Strikethrough](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strikethrough) { get; set; } | 获取或设置一个值，指示是否[删除线]. |
| [StrokeColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strokecolor) { get; set; } | 获取或设置描边的颜色。 |
| [Tracking](../../aspose.psd.fileformats.psd.layers.text/itextstyle/tracking) { get; set; } | 获取或设置跟踪。 |
| [Underline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/underline) { get; set; } | 获取或设置一个值，指示是否[下划线]. |
| [VerticalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/verticalscale) { get; set; } | 垂直刻度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextstyle/apply)(ITextStyle) | 应用指定的样式。 |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextstyle/isequal)(ITextStyle) | 判断指定样式是否相等 |

### 例子

以下示例演示了如何在 Aspose.PSD 的一个文本层中呈现不同的样式

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

    newPortions[0].Style.Underline = true; // 编辑文本样式“E=mc”
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // 编辑文本样式 "2\r"
    newPortions[2].Style.FauxBold = true; // 编辑文本样式“粗体”
    newPortions[3].Style.FauxItalic = true; // 编辑文本样式“斜体\r”
    newPortions[3].Style.BaselineShift = -25; // 编辑文本样式“斜体\r”
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // 编辑文本样式“小写文本”

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

以下代码演示了如何获取文本层中任何文本部分的字体大小。

```csharp
[C#]

// 提取错误的字体大小 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // 旧 API（使用首段字体）
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // 检查基本字体大小
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 检查实际字体大小
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // 新 API（一个文本层可以包含任意数量的字体大小）
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // 检查基本部分的字体大小
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // 检查实际部分字体大小
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
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
