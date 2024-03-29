---
title: IText.ProducePortions
second_title: Aspose.PSD per riferimento API .NET
description: IText metodo. Produce le nuove porzioni con parametri di input o di default.
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

Produce le nuove porzioni con parametri di input o di default.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| portionsOfText | String[] | Le porzioni di testo da creare nuove[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Uno stile che, se non nullo, verrà applicato nel nuovo, altrimenti sarà predefinito. |
| paragraphPrototype | ITextParagraph | Un comma che, se non nullo, sarà applicato nel nuovo, altrimenti sarà predefinito. |

### Valore di ritorno

Restituisce le nuove porzioni[`ITextPortion`](../../itextportion/) in base ai parametri di input.

### Esempi

L'esempio seguente dimostra come è possibile eseguire il rendering di stili diversi in un livello di testo in Aspose.PSD

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

### Guarda anche

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* assemblea [Aspose.PSD](../../../)


