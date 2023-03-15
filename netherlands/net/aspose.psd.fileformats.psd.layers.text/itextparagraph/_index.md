---
title: Interface ITextParagraph
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.Layers.Text.ITextParagraph koppel. De interface om met paragraaf te werken
type: docs
weight: 3520
url: /nl/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
## ITextParagraph interface

De interface om met paragraaf te werken

```csharp
public interface ITextParagraph
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [automatische woordafbreking]. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading/) { get; set; } | Haalt of stelt de automatische interlinie in. |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari/) { get; set; } | Haalt of stelt een waarde in die aangeeft of dit`ITextParagraph`is burasagiri. |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens/) { get; set; } | Haalt of stelt de opeenvolgende koppeltekens in. |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent/) { get; set; } | Haalt of stelt de eindinspringing in. |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer/) { get; set; } | Haalt of stelt een waarde in die aangeeft of [elke regelsamensteller]. |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent/) { get; set; } | Haalt of stelt de inspringing van de eerste regel in. |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing/) { get; set; } | Haalt de glyph-afstand op of stelt deze in. |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging/) { get; set; } | Haalt of stelt een waarde in die aangeeft of dit`ITextParagraph` hangt. |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize/) { get; set; } | Hiermee wordt de grootte van het afgebroken woord opgehaald of ingesteld. |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification/) { get; set; } | Haalt of stelt de rechtvaardiging in. |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder/) { get; set; } | Haalt of stelt de kinsoku-volgorde in. |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype/) { get; set; } | Haalt of stelt het type van de regel in. |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing/) { get; set; } | Haalt of stelt de letterafstand in. |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen/) { get; set; } | Haalt of stelt het koppelteken in. |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen/) { get; set; } | Haalt het pre-koppelteken op of stelt het in. |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter/) { get; set; } | Haalt of stelt de spatie achter in. |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore/) { get; set; } | Haalt of stelt de spatie ervoor in. |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent/) { get; set; } | Haalt of stelt de startinspringing in. |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing/) { get; set; } | Haalt of stelt de woordafstand in. |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone/) { get; set; } | Krijgt of stelt de zone in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply/)(ITextParagraph) | Past de gespecificeerde alinea toe. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal/)(ITextParagraph) | Bepaalt of de opgegeven alinea gelijk is. |

### Voorbeelden

Het volgende voorbeeld laat zien dat de tekstuitlijning via ITextPortion voor rechts-naar-links-talen correct werkt.

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

Het volgende codevoorbeeld demonstreert de bewerkingstekstgedeelten en hun tekststijl.

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

            // Controle van de tekst van elke portie
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Alineagegevens controleren
            // Alinea's hebben een andere motivering
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // Alle andere eigenschappen van de eerste en tweede alinea zijn gelijk
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

            // Stijlgegevens controleren
            // Stijlen hebben verschillende kleuren en lettergroottes
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

            // Voorbeeld van tekstbewerking
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Voorbeeld van het verwijderen van tekstgedeelten
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Voorbeeld van het toevoegen van een nieuw tekstgedeelte
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Voorbeeld van alinea- en stijlbewerking voor gedeelten
            // Stel de juiste rechtvaardiging in
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Verschillende kleuren voor elke stijl. Het wordt gewijzigd, maar weergave wordt niet volledig ondersteund
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Ander lettertype. Het wordt gewijzigd, maar weergave wordt niet volledig ondersteund
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

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* montage [Aspose.PSD](../../)


