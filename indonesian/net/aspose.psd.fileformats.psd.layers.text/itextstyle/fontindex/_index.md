---
title: ITextStyle.FontIndex
second_title: Aspose.PSD untuk Referensi .NET API
description: ITextStyle Properti. Mendapat indeks font.
type: docs
weight: 110
url: /id/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
## ITextStyle.FontIndex property

Mendapat indeks font.

```csharp
public int FontIndex { get; }
```

### Nilai properti

Font.

### Contoh

Kode berikut menunjukkan bagaimana Aspose.PSD mendapatkan properti pemformatan sebaris dari Lapisan Teks.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Memuat gambar yang ada ke dalam instance kelas PsdImage
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

        // mendapatkan font yang ada di lapisan teks
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

### Lihat juga

* interface [ITextStyle](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* perakitan [Aspose.PSD](../../../)


