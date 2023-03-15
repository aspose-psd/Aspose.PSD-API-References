---
title: TextFontInfo.Style
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: TextFontInfo संपत्त. फ़न्ट शैल क सबफ़ैमल नम से पर्स कय जत है
type: docs
weight: 50
url: /hi/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

फ़ॉन्ट शैली को सबफ़ैमिली नाम से पार्स किया जाता है

```csharp
public FontStyle Style { get; }
```

### संपत्ति मूल्य

फ़ॉन्ट शैली उपपरिवार नाम से पार्स की गई

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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* सभा [Aspose.PSD](../../../)


