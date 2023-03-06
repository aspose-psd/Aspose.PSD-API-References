---
title: IText.ProducePortions
second_title: Aspose.PSD voor .NET API-referentie
description: IText methode. Produceert de nieuwe delen met invoer of standaardparameters.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

Produceert de nieuwe delen met invoer- of standaardparameters.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| portionsOfText | String[] | De tekstgedeelten om nieuwe te maken[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Een stijl die, indien niet null, wordt toegepast in de nieuwe, anders zal standaard zijn. |
| paragraphPrototype | ITextParagraph | Een paragraaf die, indien niet null, zal worden toegepast in de nieuwe, anders zal standaard zijn. |

### Winstwaarde

Retourneert de nieuwe delen[`ITextPortion`](../../itextportion/) op basis van invoerparameters.

### Voorbeelden

Het volgende voorbeeld laat zien hoe u verschillende stijlen in één tekstlaag kunt renderen in Aspose.PSD

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

    newPortions[0].Style.Underline = true; // bewerk tekststijl "E=mc"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // bewerk tekststijl "2\r"
    newPortions[2].Style.FauxBold = true; // bewerk tekststijl "Vet"
    newPortions[3].Style.FauxItalic = true; // bewerk tekststijl "Cursief\r"
    newPortions[3].Style.BaselineShift = -25; // bewerk tekststijl "Cursief\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // bewerk tekststijl "Kleine letters"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

### Zie ook

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* montage [Aspose.PSD](../../../)


