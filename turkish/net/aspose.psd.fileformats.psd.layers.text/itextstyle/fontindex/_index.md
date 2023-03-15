---
title: ITextStyle.FontIndex
second_title: Aspose.PSD for .NET API Referansı
description: ITextStyle mülk. Yazı tipi indeksini alır.
type: docs
weight: 110
url: /tr/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
## ITextStyle.FontIndex property

Yazı tipi indeksini alır.

```csharp
public int FontIndex { get; }
```

### Mülk değeri

Yazı tipi.

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

* interface [ITextStyle](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* toplantı [Aspose.PSD](../../../)


