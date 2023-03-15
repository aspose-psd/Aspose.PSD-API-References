---
title: IText.ProducePortions
second_title: Aspose.PSD för .NET API-referens
description: IText metod. Producerar de nya delarna med indata eller standardparametrar.
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

Producerar de nya delarna med indata eller standardparametrar.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portionsOfText | String[] | De delar av text som ska skapas nya[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | En stil som, om den inte är null, kommer att tillämpas i den nya, annars kommer att vara standard. |
| paragraphPrototype | ITextParagraph | En paragraf som, om den inte är null, kommer att tillämpas i den nya, annars kommer att vara standard. |

### Returvärde

Returnerar de nya portionerna[`ITextPortion`](../../itextportion/) baserat på ingångsparametrar.

### Exempel

Följande exempel visar hur du kan rendera olika stilar i ett textlager i Aspose.PSD

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

    newPortions[0].Style.Underline = true; // redigera textstil "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // redigera textstil "2\r"
    newPortions[2].Style.FauxBold = true; // redigera textstil "Fet"
    newPortions[3].Style.FauxItalic = true; // redigera textstil "Kursiv\r"
    newPortions[3].Style.BaselineShift = -25; // redigera textstil "Kursiv\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // redigera textstil "Små bokstäver"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

### Se även

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* hopsättning [Aspose.PSD](../../../)


