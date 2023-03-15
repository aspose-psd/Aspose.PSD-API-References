---
title: IText.ProducePortions
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: IText तरक. इनपुट य डफ़ल्ट पैरमटर के सथ नए हस्से तैयर करत है.
type: docs
weight: 70
url: /hi/net/aspose.psd.fileformats.psd.layers.text/itext/produceportions/
---
## IText.ProducePortions method

इनपुट या डिफ़ॉल्ट पैरामीटर के साथ नए हिस्से तैयार करता है.

```csharp
public ITextPortion[] ProducePortions(string[] portionsOfText, ITextStyle stylePrototype, 
    ITextParagraph paragraphPrototype)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portionsOfText | String[] | नया बनाने के लिए पाठ के भाग[`ITextPortion`](../../itextportion/). |
| stylePrototype | ITextStyle | एक शैली जो, यदि अशक्त नहीं है, नए में लागू की जाएगी, अन्यथा डिफ़ॉल्ट होगा। |
| paragraphPrototype | ITextParagraph | एक पैराग्राफ जो, यदि शून्य नहीं है, नए में लागू किया जाएगा, अन्यथा डिफ़ॉल्ट होगा। |

### प्रतिलाभ की मात्रा

नए हिस्से लौटाता है[`ITextPortion`](../../itextportion/) इनपुट मापदंडों के आधार पर।

### उदाहरण

निम्न उदाहरण दर्शाता है कि आप Aspose.PSD में एक पाठ परत में विभिन्न शैलियों को कैसे प्रस्तुत कर सकते हैं

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

    newPortions[0].Style.Underline = true; // पाठ शैली संपादित करें "ई = एमसी"
    newPortions[1].Style.FontBaseline = FontBaseline.Superscript; // पाठ शैली संपादित करें "2\r"
    newPortions[2].Style.FauxBold = true; // पाठ शैली संपादित करें "बोल्ड"
    newPortions[3].Style.FauxItalic = true; // पाठ शैली संपादित करें "इटैलिक\r"
    newPortions[3].Style.BaselineShift = -25; // पाठ शैली संपादित करें "इटैलिक\r"
    newPortions[4].Style.FontCaps = FontCaps.SmallCaps; // पाठ शैली संपादित करें "लोअरकेसटेक्स्ट"

    foreach (var newPortion in newPortions)
    {
        textData.AddPortion(newPortion);
    }

    textData.UpdateLayerData();
    img.Save(outputFile);
}
```

### यह सभी देखें

* interface [ITextPortion](../../itextportion/)
* interface [ITextStyle](../../itextstyle/)
* interface [ITextParagraph](../../itextparagraph/)
* interface [IText](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* सभा [Aspose.PSD](../../../)


