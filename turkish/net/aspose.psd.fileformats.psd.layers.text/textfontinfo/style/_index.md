---
title: TextFontInfo.Style
second_title: Aspose.PSD for .NET API Referansı
description: TextFontInfo mülk. Alt aile adı den çözümlenen yazı tipi stilini alır
type: docs
weight: 50
url: /tr/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

Alt aile adı 'den çözümlenen yazı tipi stilini alır

```csharp
public FontStyle Style { get; }
```

### Mülk değeri

Alt aile adı 'den ayrıştırılan yazı tipi stili

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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* toplantı [Aspose.PSD](../../../)


