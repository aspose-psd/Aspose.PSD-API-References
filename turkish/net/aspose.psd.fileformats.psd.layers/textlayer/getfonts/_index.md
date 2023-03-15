---
title: TextLayer.GetFonts
second_title: Aspose.PSD for .NET API Referansı
description: TextLayer yöntem. Metin katmanının yazı tipi kümesini alır.
type: docs
weight: 80
url: /tr/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
## TextLayer.GetFonts method

Metin katmanının yazı tipi kümesini alır.

```csharp
public TextFontInfo[] GetFonts()
```

### Geri dönüş değeri

Metin katmanının yazı tipleri kümesi.

### Örnekler

Aşağıdaki kod, Aspose.PSD'nin Metin Katmanı'nın satır içi biçimlendirme özelliklerini nasıl elde ettiğini gösterir.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
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

        // metin katmanında bulunan yazı tiplerini alır
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

### Ayrıca bakınız

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* toplantı [Aspose.PSD](../../../)


