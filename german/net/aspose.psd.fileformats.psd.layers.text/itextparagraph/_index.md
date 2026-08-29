---
title: "Schnittstelle ITextParagraph"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.Text.ITextParagraph Schnittstelle. Die Schnittstelle zum Arbeiten mit Absätzen"
type: docs
weight: 3940
url: /de/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
{{< psd/tize >}}
## ITextParagraph interface

Die Schnittstelle zur Arbeit mit Absätzen

```csharp
public interface ITextParagraph
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, ob [automatic hyphenate]. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading/) { get; set; } | Ruft den automatischen Zeilenabstand ab oder legt ihn fest. |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, ob dieses `ITextParagraph` burasagiri ist. |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens/) { get; set; } | Ruft die aufeinanderfolgenden Bindestriche ab oder legt sie fest. |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent/) { get; set; } | Ruft den Endeinzug ab oder legt ihn fest. |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, ob [every line composer]. |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent/) { get; set; } | Ruft den Erstzeileneinzug ab oder legt ihn fest. |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing/) { get; set; } | Ruft den Glyphenabstand ab oder legt ihn fest. |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging/) { get; set; } | Ruft den Wert ab oder legt ihn fest, der angibt, ob dieses `ITextParagraph` hängend ist. |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize/) { get; set; } | Ruft die Größe des getrennten Wortes ab oder legt sie fest. |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification/) { get; set; } | Ruft die Ausrichtung ab oder legt sie fest. |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder/) { get; set; } | Ruft die Kinsoku-Reihenfolge ab oder legt sie fest. |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype/) { get; set; } | Ruft den Typ des Zeilenabstands ab oder legt ihn fest. |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing/) { get; set; } | Ruft den Buchstabenabstand ab oder legt ihn fest. |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen/) { get; set; } | Ruft den nachfolgenden Bindestrich ab oder legt ihn fest. |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen/) { get; set; } | Ruft den vorangestellten Bindestrich ab oder legt ihn fest. |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter/) { get; set; } | Ruft den Abstand danach ab oder legt ihn fest. |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore/) { get; set; } | Ruft den Abstand davor ab oder legt ihn fest. |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent/) { get; set; } | Ruft den Starteinzug ab oder legt ihn fest. |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing/) { get; set; } | Ruft den Wortabstand ab oder legt ihn fest. |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone/) { get; set; } | Ruft die Zone ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply/)(ITextParagraph) | Wendet den angegebenen Absatz an. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal/)(ITextParagraph) | Bestimmt, ob der angegebene Absatz gleich ist. |

## Beispiele

Das folgende Beispiel zeigt, dass die Textausrichtung über ITextPortion für Rechts-nach-Links-Sprachen korrekt funktioniert.

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


