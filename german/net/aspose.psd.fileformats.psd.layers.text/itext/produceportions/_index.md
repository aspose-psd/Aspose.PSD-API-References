---
title: "IText.ProducePortions"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "IText-Methode. Erzeugt die neuen Portionen mit Eingabe- oder Standardparametern"
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

Erzeugt die neuen Abschnitte mit Eingabe- oder Standardparametern.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portionsOfText | String[] | Die Textportionen, um neue [`ITextPortion`](../../itextportion/) zu erstellen. |
| stylePrototype | ITextStyle | Ein Stil, der, falls nicht null, im neuen [`ITextPortion`](../../itextportion/) angewendet wird, andernfalls wird der Standardstil verwendet. |
| paragraphPrototype | ITextParagraph | Ein Absatz, der, falls nicht null, im neuen [`ITextPortion`](../../itextportion/) angewendet wird, andernfalls wird der Standardabsatz verwendet. |

### Rückgabewert

Gibt die neuen Portionen [`ITextPortion`](../../itextportion/) basierend auf den Eingabeparametern zurück.

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

### Siehe auch

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


