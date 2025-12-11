---
title: Interface ITextStyle
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.Text.ITextStyle interface. Interface to work with Text Style
type: docs
weight: 3920
url: /net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---
{{< psd/tize >}}
## ITextStyle interface

Interface to work with Text Style

```csharp
public interface ITextStyle
```

## Properties

| Name | Description |
| --- | --- |
| [AutoKerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autokerning/) { get; set; } | Gets or sets the auto kerning. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autoleading/) { get; set; } | Gets or sets a value indicating whether [automatic leading]. |
| [BaselineShift](../../aspose.psd.fileformats.psd.layers.text/itextstyle/baselineshift/) { get; set; } | The baseline shift. |
| [ContextualAlternates](../../aspose.psd.fileformats.psd.layers.text/itextstyle/contextualalternates/) { get; set; } | The contextual alternates used to connect letters together. |
| [DiscretionaryLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/discretionaryligatures/) { get; set; } | The discretionary ligatures used to connect letters, especially in script fonts. |
| [FauxBold](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxbold/) { get; set; } | Gets or sets the faux bold is enabled. |
| [FauxItalic](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxitalic/) { get; set; } | Gets or sets the faux bold is enabled. |
| [FillColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fillcolor/) { get; set; } | Gets or sets the color of the fill. |
| [FontBaseline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontbaseline/) { get; set; } | The font baseline. |
| [FontCaps](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontcaps/) { get; set; } | The font caps. |
| [FontIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/) { get; } | Gets the font index. |
| [FontName](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontname/) { get; set; } | Gets or sets the font name. |
| [FontSize](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontsize/) { get; set; } | Gets or sets the size of the font. |
| [Fractions](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fractions/) { get; set; } | The fractions symbols can be replaced with special glyph. |
| [HindiNumbers](../../aspose.psd.fileformats.psd.layers.text/itextstyle/hindinumbers/) { get; set; } | Gets or sets a value indicating whether [hindi numbers]. |
| [HorizontalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/horizontalscale/) { get; set; } | The horizontal scale. |
| [IsStandardVerticalRomanAlignmentEnabled](../../aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/) { get; set; } | Gets or sets the standard vertical Roman alignment. This based on BaselineDirection resource value applies only when text orientation is Vertical. |
| [Kerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/kerning/) { get; set; } | Gets or sets the kerning. |
| [LanguageIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/languageindex/) { get; } | Gets the language index. |
| [Leading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/leading/) { get; set; } | Gets or sets the leading. |
| [NoBreak](../../aspose.psd.fileformats.psd.layers.text/itextstyle/nobreak/) { get; set; } | Gets ot sets the no break value. |
| [StandardLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/standardligatures/) { get; set; } | The standard contextual ligatures used to connect letters together. |
| [Strikethrough](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strikethrough/) { get; set; } | Gets or sets a value indicating whether [strikethrough]. |
| [StrokeColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strokecolor/) { get; set; } | Gets or sets the color of the stroke. |
| [Tracking](../../aspose.psd.fileformats.psd.layers.text/itextstyle/tracking/) { get; set; } | Gets or sets the tracking. |
| [Underline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/underline/) { get; set; } | Gets or sets a value indicating whether [underline]. |
| [VerticalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/verticalscale/) { get; set; } | The vertical scale. |

## Methods

| Name | Description |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextstyle/apply/)(ITextStyle) | Applies the specified style. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextstyle/isequal/)(ITextStyle) | Determines whether the specified style is equal. |

## Examples

The following example demonstrates how you can render different styles in one text layer in Aspose.PSD

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

The following code demonstrates how to get font size for any text portion in the text layer.

```csharp
[C#]

// Extracted wrong Font size 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Old API (Using the first paragraph font)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Checking the base font size
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Checking real font size
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // New API (One text layer may contain any quantity of font sizes)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Checking the base portion font size
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Checking real portion font size
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

The following code example demonstrates the editing text portions and their text style.

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

            // Checking text of every portion
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Checking paragraphs data
            // Paragraphs have different justification
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // All other properties of first and second paragraph are equal
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

            // Checking style data
            // Styles have different colors and font size
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

            // Example of text editing
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Example of text portions removing
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Example of adding new text portion
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Example of paragraph and style editing for portions
            // Set right justification
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Different colors for each style. The will be changed, but rendering is not fully supported
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Different font. The will be changed, but rendering is not fully supported
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

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../)


