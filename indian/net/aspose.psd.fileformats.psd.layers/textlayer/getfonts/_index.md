---
title: "TextLayer.GetFonts"
second_title: "Aspose.PSD for .NET API रेफ़रेंस"
description: "TextLayer मेथड। टेक्स्ट लेयर के फ़ॉन्ट सेट को प्राप्त करता है"
type: docs
weight: 90
url: /hi/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
{{< psd/tize >}}
## TextLayer.GetFonts method

टेक्स्ट लेयर के फ़ॉन्ट सेट को प्राप्त करता है।

```csharp
public TextFontInfo[] GetFonts()
```

### रिटर्न वैल्यू

टेक्स्ट लेयर का फ़ॉन्ट सेट।

## उदाहरण

निम्नलिखित कोड दर्शाता है कि Aspose.PSD टेक्स्ट लेयर की इनलाइन फ़ॉर्मेटिंग की प्रॉपर्टीज़ को कैसे प्राप्त करता है।

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// एक मौजूदा छवि को PsdImage क्लास के एक इंस्टेंस में लोड करें।
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

        // टेक्स्ट लेयर में मौजूद फ़ॉन्ट्स को प्राप्त करता है
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

### देखें भी

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


