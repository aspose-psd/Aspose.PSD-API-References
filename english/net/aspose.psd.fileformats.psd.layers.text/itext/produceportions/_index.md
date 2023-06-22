---
title: IText.ProducePortions
second_title: Aspose.PSD for .NET API Reference
description: IText method. Produces the new portions with input or default parameters
type: docs
weight: 70
url: /net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

Produces the new portions with input or default parameters.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| Parameter | Type | Description |
| --- | --- | --- |
| portionsOfText | String[] | The portions of text to create new [`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | A style that, if not null, will be applied in the new , otherwise will be default. |
| paragraphPrototype | ITextParagraph | A paragraph that, if not null, will be applied in the new , otherwise will be default. |

### Return Value

Returns the new portions [`ITextPortion`](../../itextportion/) based on input parameters.

## Examples

The following example demonstrates how you can render different styles in one text layer in Aspose.PSD

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

### See Also

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


