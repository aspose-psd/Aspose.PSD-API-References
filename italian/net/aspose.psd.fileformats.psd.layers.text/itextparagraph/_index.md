---
title: ITextParagraph
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Linterfaccia per lavorare con il paragrafo
type: docs
weight: 3460
url: /it/net/aspose.psd.fileformats.psd.layers.text/itextparagraph/
---
## ITextParagraph interface

L'interfaccia per lavorare con il paragrafo

```csharp
public interface ITextParagraph
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoHyphenate](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autohyphenate) { get; set; } | Ottiene o imposta un valore che indica se [sillabazione automatica]. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/autoleading) { get; set; } | Ottiene o imposta l'interlinea automatica. |
| [Burasagari](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/burasagari) { get; set; } | Ottiene o imposta un valore che indica se questo[`ITextParagraph`](../itextparagraph) è burasagiri. |
| [ConsecutiveHyphens](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/consecutivehyphens) { get; set; } | Ottiene o imposta i trattini consecutivi. |
| [EndIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/endindent) { get; set; } | Ottiene o imposta il rientro finale. |
| [EveryLineComposer](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/everylinecomposer) { get; set; } | Ottiene o imposta un valore che indica se [ogni line composer]. |
| [FirstLineIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/firstlineindent) { get; set; } | Ottiene o imposta il rientro della prima riga. |
| [GlyphSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/glyphspacing) { get; set; } | Ottiene o imposta la spaziatura dei glifi. |
| [Hanging](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hanging) { get; set; } | Ottiene o imposta un valore che indica se questo[`ITextParagraph`](../itextparagraph) è sospeso. |
| [HyphenatedWordSize](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/hyphenatedwordsize) { get; set; } | Ottiene o imposta la dimensione della parola con trattino. |
| [Justification](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/justification) { get; set; } | Ottiene o imposta la giustificazione. |
| [KinsokuOrder](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/kinsokuorder) { get; set; } | Ottiene o imposta l'ordine kinsoku. |
| [LeadingType](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/leadingtype) { get; set; } | Ottiene o imposta il tipo dell'interlinea. |
| [LetterSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/letterspacing) { get; set; } | Ottiene o imposta la spaziatura delle lettere. |
| [PostHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/posthyphen) { get; set; } | Ottiene o imposta il trattino del post. |
| [PreHyphen](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/prehyphen) { get; set; } | Ottiene o imposta il trattino pre. |
| [SpaceAfter](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spaceafter) { get; set; } | Ottiene o imposta lo spazio dopo. |
| [SpaceBefore](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/spacebefore) { get; set; } | Ottiene o imposta lo spazio prima. |
| [StartIndent](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/startindent) { get; set; } | Ottiene o imposta il rientro iniziale. |
| [WordSpacing](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/wordspacing) { get; set; } | Ottiene o imposta la spaziatura delle parole. |
| [Zone](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/zone) { get; set; } | Ottiene o imposta la zona. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/apply)(ITextParagraph) | Applica il paragrafo specificato. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextparagraph/isequal)(ITextParagraph) | Determina se il paragrafo specificato è uguale. |

### Esempi

Nell'esempio seguente viene illustrato che l'allineamento del testo tramite ITextPortion per le lingue da destra a sinistra funziona correttamente.

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

Nell'esempio di codice seguente vengono illustrate le parti di testo di modifica e il relativo stile di testo.

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

            // Controllo del testo di ogni porzione
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // Controllo dei dati dei paragrafi
            // I paragrafi hanno una giustificazione diversa
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // Tutte le altre proprietà del primo e del secondo paragrafo sono uguali
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

            // Controllo dei dati di stile
            // Gli stili hanno colori e dimensioni del carattere diversi
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

            // Esempio di modifica del testo
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // Esempio di rimozione di porzioni di testo
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // Esempio di aggiunta di una nuova porzione di testo
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // Esempio di modifica di paragrafi e stili per porzioni
            // Imposta la giusta giustificazione
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // Colori diversi per ogni stile. Verrà modificato, ma il rendering non è completamente supportato
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // Carattere diverso. Verrà modificato, ma il rendering non è completamente supportato
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

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
