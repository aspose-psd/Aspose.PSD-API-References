---
title: Interface ITextPortion
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.Text.ITextPortion इंटरफेस. इंटरफ़ेस पठ भगं में हेरफेर करने के लए
type: docs
weight: 3530
url: /hi/net/aspose.psd.fileformats.psd.layers.text/itextportion/
---
## ITextPortion interface

इंटरफ़ेस पाठ भागों में हेरफेर करने के लिए

```csharp
public interface ITextPortion
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Paragraph](../../aspose.psd.fileformats.psd.layers.text/itextportion/paragraph/) { get; } | शैली सेट करता है। |
| [Style](../../aspose.psd.fileformats.psd.layers.text/itextportion/style/) { get; } | शैली प्राप्त करता है। |
| [Text](../../aspose.psd.fileformats.psd.layers.text/itextportion/text/) { get; set; } | टेक्स्ट प्राप्त या सेट करता है। |

### उदाहरण

निम्न उदाहरण दर्शाता है कि दाएँ-से-बाएँ भाषाओं के लिए ITextPortion के माध्यम से पाठ संरेखण ठीक से काम करता है।

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
}
```

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

निम्न कोड प्रदर्शित करता है कि पाठ परत में किसी पाठ भाग के लिए फ़ॉन्ट आकार कैसे प्राप्त करें।

```csharp
[C#]

// निकाला गया गलत फ़ॉन्ट आकार 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // पुराना एपीआई (पहले पैराग्राफ फ़ॉन्ट का उपयोग करके)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // आधार फ़ॉन्ट आकार की जाँच करना
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // वास्तविक फ़ॉन्ट आकार की जाँच करना
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // नया एपीआई (एक पाठ परत में फ़ॉन्ट आकार की कितनी भी मात्रा हो सकती है)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // आधार भाग फ़ॉन्ट आकार की जाँच करना
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // वास्तविक भाग फ़ॉन्ट आकार की जाँच करना
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

निम्नलिखित कोड उदाहरण संपादन पाठ भागों और उनकी पाठ शैली को प्रदर्शित करता है।

```csharp
[C#]

const double Tolerance = 0.0001;
var filePath = "ThreeColorsParagraphs.psd";
var outputPath = "ThreeColorsParagraph_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    for (int i = 0; i < im.Layers.Length; i++)
    {
        var layer = im.Layers[i] as TextLayer;

        if (layer != null)
        {
            var portions = layer.TextData.Items;

            if (portions.Length != 4)
            {
                throw new Exception();
            }

            // हर हिस्से का टेक्स्ट चेक करना
            if (portions[0].Text != "Old " ||
                portions[1].Text != "color" ||
                portions[2].Text != " text\r" ||
                portions[3].Text != "Second paragraph\r")
            {
                throw new Exception();
            }

            // पैराग्राफ डेटा की जाँच करना
            // पैराग्राफ का अलग औचित्य है
            if (
                (int)portions[0].Paragraph.Justification != 0 ||
                (int)portions[1].Paragraph.Justification != 0 ||
                (int)portions[2].Paragraph.Justification != 0 ||
                (int)portions[3].Paragraph.Justification != 2)
            {
                throw new Exception();
            }

            // पहले और दूसरे पैराग्राफ के अन्य सभी गुण समान हैं
            for (int j = 0; j < portions.Length; j++)
            {
                var paragraph = portions[j].Paragraph;

                if (Math.Abs(paragraph.AutoLeading - 1.2) > Tolerance ||
                    paragraph.AutoHyphenate != false ||
                    paragraph.Burasagari != false ||
                    paragraph.ConsecutiveHyphens != 8 ||
                    Math.Abs(paragraph.StartIndent) > Tolerance ||
                    Math.Abs(paragraph.EndIndent) > Tolerance ||
                    paragraph.EveryLineComposer != false ||
                    Math.Abs(paragraph.FirstLineIndent) > Tolerance ||
                    paragraph.GlyphSpacing.Length != 3 ||
                    Math.Abs(paragraph.GlyphSpacing[0] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[1] - 1) > Tolerance ||
                    Math.Abs(paragraph.GlyphSpacing[2] - 1) > Tolerance ||
                    paragraph.Hanging != false ||
                    paragraph.HyphenatedWordSize != 6 ||
                    paragraph.KinsokuOrder != 0 ||
                    paragraph.LetterSpacing.Length != 3 ||
                    Math.Abs(paragraph.LetterSpacing[0]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[1]) > Tolerance ||
                    Math.Abs(paragraph.LetterSpacing[2]) > Tolerance ||
                    paragraph.LeadingType != LeadingMode.Auto ||
                    paragraph.PreHyphen != 2 ||
                    paragraph.PostHyphen != 2 ||
                    Math.Abs(paragraph.SpaceBefore) > Tolerance ||
                    Math.Abs(paragraph.SpaceAfter) > Tolerance ||
                    paragraph.WordSpacing.Length != 3 ||
                    Math.Abs(paragraph.WordSpacing[0] - 0.8) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[1] - 1.0) > Tolerance ||
                    Math.Abs(paragraph.WordSpacing[2] - 1.33) > Tolerance ||
                    Math.Abs(paragraph.Zone - 36.0) > Tolerance)
                {
                    throw new Exception();
                }
            }

            // शैली डेटा की जाँच करना
            // शैलियों में अलग-अलग रंग और फ़ॉन्ट आकार होते हैं
            if (Math.Abs(portions[0].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[1].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[2].Style.FontSize - 12) > Tolerance ||
                Math.Abs(portions[3].Style.FontSize - 10) > Tolerance)
            {
                throw new Exception();
            }

            if (portions[0].Style.FillColor != Color.FromArgb(255, 145, 0, 0) ||
                portions[1].Style.FillColor != Color.FromArgb(255, 201, 128, 2) ||
                portions[2].Style.FillColor != Color.FromArgb(255, 18, 143, 4) ||
                portions[3].Style.FillColor != Color.FromArgb(255, 145, 42, 100))
            {
                throw new Exception();
            }

            for (int j = 0; j < portions.Length; j++)
            {
                var style = portions[j].Style;

                if (style.AutoLeading != true ||
                    style.HindiNumbers != false ||
                    style.Kerning != 0 ||
                    style.Leading != 0 ||
                    style.StrokeColor != Color.FromArgb(255, 175, 90, 163) ||
                    style.Tracking != 50)
                {
                    throw new Exception();
                }
            }

            // पाठ संपादन का उदाहरण
            portions[0].Text = "Hello ";
            portions[1].Text = "World";

            // पाठ के भाग निकालने का उदाहरण
            layer.TextData.RemovePortion(3);
            layer.TextData.RemovePortion(2);

            // नया पाठ भाग जोड़ने का उदाहरण
            var createdPortion = layer.TextData.ProducePortion();
            createdPortion.Text = "!!!\r";
            layer.TextData.AddPortion(createdPortion);

            portions = layer.TextData.Items;

            // भागों के लिए अनुच्छेद और शैली संपादन का उदाहरण
            // सही औचित्य सेट करें
            portions[0].Paragraph.Justification = JustificationMode.Right;
            portions[1].Paragraph.Justification = JustificationMode.Right;
            portions[2].Paragraph.Justification = JustificationMode.Right;

            // प्रत्येक शैली के लिए अलग-अलग रंग। बदल दिया जाएगा, लेकिन रेंडरिंग पूरी तरह से समर्थित नहीं है
            portions[0].Style.FillColor = Color.Aquamarine;
            portions[1].Style.FillColor = Color.Violet;
            portions[2].Style.FillColor = Color.LightBlue;

            // अलग फ़ॉन्ट। बदल दिया जाएगा, लेकिन रेंडरिंग पूरी तरह से समर्थित नहीं है
            portions[0].Style.FontSize = 6;
            portions[1].Style.FontSize = 8;
            portions[2].Style.FontSize = 10;

            layer.TextData.UpdateLayerData();

            im.Save(outputPath, new PsdOptions(im));

            break;
        }
    }
}
```

### यह सभी देखें

* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Text](../../aspose.psd.fileformats.psd.layers.text/)
* सभा [Aspose.PSD](../../)


