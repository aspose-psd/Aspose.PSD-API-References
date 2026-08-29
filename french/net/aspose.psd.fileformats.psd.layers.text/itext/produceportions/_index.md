---
title: "IText.ProducePortions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "IText méthode. Produit les nouvelles portions avec des paramètres d'entrée ou par défaut"
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

Produit les nouvelles portions avec les paramètres d'entrée ou par défaut.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| portionsOfText | String[] | Les portions de texte pour créer le nouveau [`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Un style qui, s'il n'est pas nul, sera appliqué dans le nouveau [`ITextPortion`](../../itextportion/), sinon il sera par défaut. |
| paragraphPrototype | ITextParagraph | Un paragraphe qui, s'il n'est pas nul, sera appliqué dans le nouveau [`ITextPortion`](../../itextportion/), sinon il sera par défaut. |

### Valeur de retour

Renvoie les nouvelles portions [`ITextPortion`](../../itextportion/) basées sur les paramètres d'entrée.

## Exemples

L'exemple suivant montre comment vous pouvez rendre différents styles dans une couche de texte dans Aspose.PSD

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

### Voir aussi

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


