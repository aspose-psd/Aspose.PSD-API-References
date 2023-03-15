---
title: TextLayer.GetFonts
second_title: Aspose.PSD untuk Referensi .NET API
description: TextLayer metode. Mendapat kumpulan font dari lapisan teks.
type: docs
weight: 80
url: /id/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
## TextLayer.GetFonts method

Mendapat kumpulan font dari lapisan teks.

```csharp
public TextFontInfo[] GetFonts()
```

### Nilai Pengembalian

Set font dari lapisan teks.

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

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* perakitan [Aspose.PSD](../../../)


