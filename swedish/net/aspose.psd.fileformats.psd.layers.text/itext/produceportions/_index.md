---
title: "IText.ProducePortions"
second_title: "Aspose.PSD för .NET API‑referens"
description: "IText method. Skapar de nya delarna med inmatade eller standardparametrar"
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

Skapar de nya delarna med angivna eller standardparametrar.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| portionsOfText | String[] | Delarna av texten för att skapa nya [`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | En stil som, om den inte är null, kommer att tillämpas i den nya [`ITextPortion`](../../itextportion/), annars blir den standard. |
| paragraphPrototype | ITextParagraph | Ett stycke som, om det inte är null, kommer att tillämpas i den nya [`ITextPortion`](../../itextportion/), annars blir det standard. |

### Returvärde

Returnerar de nya delarna [`ITextPortion`](../../itextportion/) baserat på inmatningsparametrar.

## Exempel

Följande exempel visar hur du kan rendera olika stilar i ett textlager i Aspose.PSD

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

### Se även

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


