---
title: TextLayer.GetFonts
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: TextLayer तरक. पठ परत क फ़न्ट सेट प्रप्त करत है.
type: docs
weight: 80
url: /hi/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
## TextLayer.GetFonts method

पाठ परत का फ़ॉन्ट सेट प्राप्त करता है.

```csharp
public TextFontInfo[] GetFonts()
```

### प्रतिलाभ की मात्रा

पाठ परत का फ़ॉन्ट सेट।

### उदाहरण

निम्न कोड दर्शाता है कि कैसे Aspose.PSD पाठ परत के इनलाइन स्वरूपण के गुण प्राप्त करता है।

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// मौजूदा छवि को PsdImage वर्ग के उदाहरण में लोड करें
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{

    var layers = psdImage.Layers;
    for (int index = 0; index < layers.Length; index++)
    {
        var layer = layers[index];
        if (!(layer is TextLayer))
        {
            continue;
        }

        var textLayer = (TextLayer)layer;

        // टेक्स्ट लेयर में शामिल फोंट प्राप्त करता है
        var fonts = textLayer.GetFonts();
        var textPortions = textLayer.TextData.Items;

        foreach (var textPortion in textPortions)
        {
            TextFontInfo font = fonts[textPortion.Style.FontIndex];
            if (font != null)
            {
                switch (font.Style)
                {
                    case FontStyle.Regular:
                        regularText.Add(textPortion);
                        break;
                    case FontStyle.Bold:
                        boldText.Add(textPortion);
                        break;
                    case FontStyle.Italic:
                        italicText.Add(textPortion);
                        break;
                    default:
                        throw new ArgumentOutOfRangeException();
                }
            }
        }
    }
}
```

### यह सभी देखें

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* सभा [Aspose.PSD](../../../)


