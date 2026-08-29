---
title: "Schnittstelle ITextStyle"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.Text.ITextStyle Schnittstelle. Schnittstelle zur Arbeit mit Textstil"
type: docs
weight: 3960
url: /de/net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---
{{< psd/tize >}}
## ITextStyle interface

Schnittstelle zur Arbeit mit Textstil

```csharp
public interface ITextStyle
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoKerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autokerning/) { get; set; } | Liest oder setzt das automatische Kerning. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autoleading/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [automatic leading]. |
| [BaselineShift](../../aspose.psd.fileformats.psd.layers.text/itextstyle/baselineshift/) { get; set; } | Der Grundlinienversatz. |
| [ContextualAlternates](../../aspose.psd.fileformats.psd.layers.text/itextstyle/contextualalternates/) { get; set; } | Die kontextabhängigen Alternativen, die zum Verbinden von Buchstaben verwendet werden. |
| [DiscretionaryLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/discretionaryligatures/) { get; set; } | Die fakultativen Ligaturen, die zum Verbinden von Buchstaben verwendet werden, insbesondere in Schreibschriftarten. |
| [FauxBold](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxbold/) { get; set; } | Liest oder setzt, ob Faux‑Bold aktiviert ist. |
| [FauxItalic](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxitalic/) { get; set; } | Liest oder setzt, ob Faux‑Bold aktiviert ist. |
| [FillColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fillcolor/) { get; set; } | Liest oder setzt die Füllfarbe. |
| [FontBaseline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontbaseline/) { get; set; } | Die Schriftgrundlinie. |
| [FontCaps](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontcaps/) { get; set; } | Die Großbuchstaben der Schrift. |
| [FontIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/) { get; } | Liest den Schriftindex. |
| [FontName](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontname/) { get; set; } | Liest oder setzt den Schriftnamen. |
| [FontSize](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontsize/) { get; set; } | Liest oder setzt die Größe der Schriftart. |
| [Fractions](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fractions/) { get; set; } | Die Bruchzeichen können durch ein spezielles Glyph ersetzt werden. |
| [HindiNumbers](../../aspose.psd.fileformats.psd.layers.text/itextstyle/hindinumbers/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [hindi numbers]. |
| [HorizontalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/horizontalscale/) { get; set; } | Die horizontale Skalierung. |
| [IsStandardVerticalRomanAlignmentEnabled](../../aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/) { get; set; } | Liest oder setzt die standardmäßige vertikale römische Ausrichtung. Dieser, basierend auf dem BaselineDirection-Ressourcenwert, gilt nur, wenn die Textausrichtung vertikal ist. |
| [Kerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/kerning/) { get; set; } | Liest oder setzt das Kerning. |
| [LanguageIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/languageindex/) { get; } | Liest den Sprachindex. |
| [Leading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/leading/) { get; set; } | Liest oder setzt den Zeilenabstand. |
| [NoBreak](../../aspose.psd.fileformats.psd.layers.text/itextstyle/nobreak/) { get; set; } | Liest oder setzt den No-Break-Wert. |
| [StandardLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/standardligatures/) { get; set; } | Die standardmäßigen kontextuellen Ligaturen, die zum Verbinden von Buchstaben verwendet werden. |
| [Strikethrough](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strikethrough/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [strikethrough]. |
| [StrokeColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strokecolor/) { get; set; } | Liest oder setzt die Farbe des Strichs. |
| [Tracking](../../aspose.psd.fileformats.psd.layers.text/itextstyle/tracking/) { get; set; } | Liest oder setzt das Tracking. |
| [Underline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/underline/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [underline]. |
| [VerticalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/verticalscale/) { get; set; } | Die vertikale Skalierung. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextstyle/apply/)(ITextStyle) | Wendet den angegebenen Stil an. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextstyle/isequal/)(ITextStyle) | Bestimmt, ob der angegebene Stil gleich ist. |

## Beispiele

Das folgende Beispiel zeigt, wie Sie verschiedene Stile in einer Textebene in Aspose.PSD rendern können.

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

Der folgende Code zeigt, wie man die Schriftgröße für beliebige Textabschnitte in der Textebene ermittelt.

```csharp
[C#]

// Falsche Schriftgröße extrahiert 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Alte API (Verwendung der ersten Absatzschriftart)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Überprüfung der Basis-Schriftgröße
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Überprüfung der tatsächlichen Schriftgröße
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Neue API (Eine Textebene kann beliebig viele Schriftgrößen enthalten)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Überprüfung der Basis-Abschnittsschriftgröße
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Überprüfung der tatsächlichen Abschnittsschriftgröße
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

Das folgende Codebeispiel demonstriert das Bearbeiten von Textabschnitten und deren Textstil.

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

            // Überprüfen des Textes jedes Abschnitts
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Überprüfen der Absatzdaten
            // Absätze haben unterschiedliche Ausrichtung
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // Alle anderen Eigenschaften des ersten und zweiten Absatzes sind gleich
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

            // Überprüfen der Stildaten
            // Stile haben unterschiedliche Farben und Schriftgröße
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

            // Beispiel für die Textbearbeitung
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Beispiel für das Entfernen von Textabschnitten
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Beispiel für das Hinzufügen eines neuen Textabschnitts
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Beispiel für Absatz- und Stilbearbeitung für Abschnitte
            // Rechte Ausrichtung festlegen
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Unterschiedliche Farben für jeden Stil. Diese werden geändert, aber die Darstellung wird nicht vollständig unterstützt
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Andere Schriftart. Diese wird geändert, aber die Darstellung wird nicht vollständig unterstützt
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

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../)


