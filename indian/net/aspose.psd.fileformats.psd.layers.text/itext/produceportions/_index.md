---
title: "IText.ProducePortions"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "IText मेथड। इनपुट या डिफ़ॉल्ट पैरामीटर के साथ नए भाग उत्पन्न करता है"
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
{{< psd/tize >}}
## IText.ProducePortions method

इनपुट या डिफ़ॉल्ट पैरामीटर के साथ नई भाग उत्पन्न करता है।

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| portionsOfText | String[] | नए [`ITextPortion`](../../itextportion/) बनाने के लिए टेक्स्ट के भाग। |
| stylePrototype | ITextStyle | एक स्टाइल जो, यदि नल नहीं है, तो नए [`ITextPortion`](../../itextportion/) में लागू होगी, अन्यथा डिफ़ॉल्ट होगी। |
| paragraphPrototype | ITextParagraph | एक पैराग्राफ जो, यदि नल नहीं है, तो नए [`ITextPortion`](../../itextportion/) में लागू होगा, अन्यथा डिफ़ॉल्ट होगा। |

### रिटर्न वैल्यू

इनपुट पैरामीटर के आधार पर नए भाग [`ITextPortion`](../../itextportion/) लौटाता है।

## उदाहरण

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में एक टेक्स्ट लेयर में विभिन्न शैलियों को कैसे रेंडर कर सकते हैं।

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

### देखें भी

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


