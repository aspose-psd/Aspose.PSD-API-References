---
title: IText.ProducePortions
second_title: Aspose.PSD für .NET-API-Referenz
description: IText methode. Erzeugt die neuen Portionen mit Eingabe oder Standardparametern.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

Erzeugt die neuen Portionen mit Eingabe- oder Standardparametern.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| portionsOfText | String[] | Die Textabschnitte neu erstellen[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Ein Stil, der, wenn er nicht null ist, im neuen angewendet wird, andernfalls wird Standard sein. |
| paragraphPrototype | ITextParagraph | Ein Absatz, der, wenn er nicht null ist, im neuen angewendet wird, andernfalls wird Standard sein. |

### Rückgabewert

Gibt die neuen Portionen zurück[`ITextPortion`](../../itextportion/) basierend auf Eingabeparametern.

### Beispiele

Das folgende Beispiel zeigt, wie Sie verschiedene Stile in einer Textebene in Aspose.PSD rendern können

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

    newPortions[0].Style.Underline = true; // Textstil bearbeiten "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // Textstil "2\r" bearbeiten
    newPortions[2].Style.FauxBold = true; // Textstil "Fett" bearbeiten
    newPortions[3].Style.FauxItalic = true; // Textstil "Kursiv\r" bearbeiten
    newPortions[3].Style.BaselineShift = -25; // Textstil "Kursiv\r" bearbeiten
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // Textstil "Lowercasetext" bearbeiten

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
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* Montage [Aspose.PSD](../../../)


