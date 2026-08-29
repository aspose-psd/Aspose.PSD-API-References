---
title: "IText.ProducePortions"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método IText. Produce las nuevas porciones con parámetros de entrada o predeterminados"
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

Produce las nuevas porciones con los parámetros de entrada o predeterminados.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portionsOfText | String[] | Las porciones de texto para crear un nuevo [`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | Un estilo que, si no es nulo, se aplicará en el nuevo [`ITextPortion`](../../itextportion/), de lo contrario será el predeterminado. |
| paragraphPrototype | ITextParagraph | Un párrafo que, si no es nulo, se aplicará en el nuevo [`ITextPortion`](../../itextportion/), de lo contrario será el predeterminado. |

### Valor devuelto

Devuelve las nuevas porciones [`ITextPortion`](../../itextportion/) basadas en los parámetros de entrada.

## Ejemplos

El siguiente ejemplo muestra cómo puedes renderizar diferentes estilos en una capa de texto en Aspose.PSD

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

### Ver también

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


