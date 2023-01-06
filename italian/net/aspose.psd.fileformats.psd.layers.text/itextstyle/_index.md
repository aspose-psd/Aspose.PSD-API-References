---
title: ITextStyle
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Interfaccia per lavorare con Stile testo
type: docs
weight: 3480
url: /it/net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---
## ITextStyle interface

Interfaccia per lavorare con Stile testo

```csharp
public interface ITextStyle
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoKerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autokerning) { get; set; } | Ottiene o imposta la crenatura automatica. |
| [AutoLeading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/autoleading) { get; set; } | Ottiene o imposta un valore che indica se [interlinea automatica]. |
| [BaselineShift](../../aspose.psd.fileformats.psd.layers.text/itextstyle/baselineshift) { get; set; } | Lo spostamento della linea di base. |
| [ContextualAlternates](../../aspose.psd.fileformats.psd.layers.text/itextstyle/contextualalternates) { get; set; } | Le alternative contestuali utilizzate per collegare le lettere insieme. |
| [DiscretionaryLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/discretionaryligatures) { get; set; } | Le legature discrezionali utilizzate per collegare le lettere, specialmente nei caratteri di script. |
| [FauxBold](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxbold) { get; set; } | Ottiene o imposta il grassetto falso è abilitato. |
| [FauxItalic](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fauxitalic) { get; set; } | Ottiene o imposta il grassetto falso è abilitato. |
| [FillColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fillcolor) { get; set; } | Ottiene o imposta il colore del riempimento. |
| [FontBaseline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontbaseline) { get; set; } | La linea di base del carattere. |
| [FontCaps](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontcaps) { get; set; } | I caratteri maiuscoli. |
| [FontIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex) { get; } | Ottiene l'indice dei caratteri. |
| [FontName](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontname) { get; set; } | Ottiene o imposta il nome del carattere. |
| [FontSize](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fontsize) { get; set; } | Ottiene o imposta la dimensione del carattere. |
| [Fractions](../../aspose.psd.fileformats.psd.layers.text/itextstyle/fractions) { get; set; } | I simboli delle frazioni possono essere sostituiti con glifi speciali. |
| [HindiNumbers](../../aspose.psd.fileformats.psd.layers.text/itextstyle/hindinumbers) { get; set; } | Ottiene o imposta un valore che indica se [numeri hindi]. |
| [HorizontalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/horizontalscale) { get; set; } | La scala orizzontale. |
| [Kerning](../../aspose.psd.fileformats.psd.layers.text/itextstyle/kerning) { get; set; } | Ottiene o imposta la crenatura. |
| [LanguageIndex](../../aspose.psd.fileformats.psd.layers.text/itextstyle/languageindex) { get; } | Ottiene l'indice della lingua. |
| [Leading](../../aspose.psd.fileformats.psd.layers.text/itextstyle/leading) { get; set; } | Ottiene o imposta l'interlinea. |
| [StandardLigatures](../../aspose.psd.fileformats.psd.layers.text/itextstyle/standardligatures) { get; set; } | Le legature contestuali standard utilizzate per collegare le lettere insieme. |
| [Strikethrough](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strikethrough) { get; set; } | Ottiene o imposta un valore che indica se [strikethrough]. |
| [StrokeColor](../../aspose.psd.fileformats.psd.layers.text/itextstyle/strokecolor) { get; set; } | Ottiene o imposta il colore del tratto. |
| [Tracking](../../aspose.psd.fileformats.psd.layers.text/itextstyle/tracking) { get; set; } | Ottiene o imposta il tracciamento. |
| [Underline](../../aspose.psd.fileformats.psd.layers.text/itextstyle/underline) { get; set; } | Ottiene o imposta un valore che indica se [underline]. |
| [VerticalScale](../../aspose.psd.fileformats.psd.layers.text/itextstyle/verticalscale) { get; set; } | La scala verticale. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Apply](../../aspose.psd.fileformats.psd.layers.text/itextstyle/apply)(ITextStyle) | Applica lo stile specificato. |
| [IsEqual](../../aspose.psd.fileformats.psd.layers.text/itextstyle/isequal)(ITextStyle) | Determina se lo stile specificato è uguale. |

### Esempi

L'esempio seguente mostra come eseguire il rendering di stili diversi in un livello di testo in Aspose.PSD

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

    newPortions[0].Style.Underline = true; // modifica lo stile del testo "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // modifica lo stile del testo "2\r"
    newPortions[2].Style.FauxBold = true; // modifica lo stile del testo "Grassetto"
    newPortions[3].Style.FauxItalic = true; // modifica lo stile del testo "Corsivo\r"
    newPortions[3].Style.BaselineShift = -25; // modifica lo stile del testo "Corsivo\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // modifica lo stile del testo "Testo minuscolo"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

Il codice seguente illustra come ottenere la dimensione del carattere per qualsiasi parte di testo nel livello di testo.

```csharp
[C#]

// Dimensione carattere errata estratta 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Vecchia API (usando il carattere del primo paragrafo)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Controllo della dimensione del carattere di base
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Controllo della dimensione reale del carattere
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Nuova API (un livello di testo può contenere qualsiasi quantità di dimensioni dei caratteri)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Controllo della dimensione del carattere della parte di base
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Controllo della dimensione del carattere della porzione reale
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
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