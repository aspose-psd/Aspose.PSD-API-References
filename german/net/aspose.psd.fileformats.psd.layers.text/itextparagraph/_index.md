---
title: ITextParagraph
second_title: Aspose.PSD für .NET-API-Referenz
description: Die Schnittstelle zum Arbeiten mit Absatz
type: docs
weight: 3460
url: /de/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
## ITextParagraph interface

Die Schnittstelle zum Arbeiten mit Absatz

```csharp
public interface ITextParagraph
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [automatische Silbentrennung]. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading) { get; set; } | Holt oder setzt den automatischen Zeilenabstand. |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`ITextParagraph`](../itextparagraph) ist burasagiri. |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens) { get; set; } | Holt oder setzt die aufeinanderfolgenden Bindestriche. |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent) { get; set; } | Ruft den Einzug am Ende ab oder legt ihn fest. |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [jeder Zeilenkomponist]. |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent) { get; set; } | Holt oder setzt den Einzug der ersten Zeile. |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing) { get; set; } | Ruft den Glyphenabstand ab oder legt ihn fest. |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`ITextParagraph`](../itextparagraph) hängt. |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize) { get; set; } | Ruft die Größe des Worts mit Bindestrich ab oder legt sie fest. |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification) { get; set; } | Ruft die Begründung ab oder legt sie fest. |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder) { get; set; } | Ruft die Kinsoku-Reihenfolge ab oder legt sie fest. |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype) { get; set; } | Ruft den Typ des Zeilenabstands ab oder legt ihn fest. |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing) { get; set; } | Ruft den Buchstabenabstand ab oder legt ihn fest. |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen) { get; set; } | Ruft den Post-Bindestrich ab oder legt ihn fest. |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen) { get; set; } | Ruft den Prä-Bindestrich ab oder legt ihn fest. |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter) { get; set; } | Ruft das Leerzeichen danach ab oder legt es fest. |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore) { get; set; } | Holt oder setzt das Leerzeichen davor. |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent) { get; set; } | Ruft den Starteinzug ab oder legt ihn fest. |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing) { get; set; } | Ruft den Wortabstand ab oder legt ihn fest. |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone) { get; set; } | Ruft die Zone ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply)(ITextParagraph) | Wendet den angegebenen Absatz an. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal)(ITextParagraph) | Bestimmt, ob der angegebene Absatz gleich ist. |

### Beispiele

Das folgende Beispiel zeigt, dass die Textausrichtung durch ITextPortion für rechts-nach-links-Sprachen ordnungsgemäß funktioniert.

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

Das folgende Codebeispiel veranschaulicht die Bearbeitung von Textabschnitten und deren Textstil.

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

            // Prüfen des Textes jedes Teils
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Absatzdaten prüfen
            // Absätze haben unterschiedliche Begründung
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

            // Stildaten prüfen
            // Stile haben unterschiedliche Farben und Schriftgrößen
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

            // Beispiel für Textbearbeitung
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Beispiel für das Entfernen von Textteilen
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Beispiel für das Hinzufügen eines neuen Textabschnitts
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Beispiel für die Bearbeitung von Absätzen und Stilen für Portionen
            // Richtige Ausrichtung setzen
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Unterschiedliche Farben für jeden Stil. Das wird geändert, aber das Rendern wird nicht vollständig unterstützt
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Andere Schriftart. Das wird geändert, aber das Rendern wird nicht vollständig unterstützt
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

* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
