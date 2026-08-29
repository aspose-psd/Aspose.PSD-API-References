---
title: "TextFontInfo.Style"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti TextFontInfo. Mendapatkan gaya font yang diurai dari nama subkeluarga"
type: docs
weight: 50
url: /id/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
{{< psd/tize >}}
## TextFontInfo.Style property

Mendapatkan gaya font yang diurai dari nama subkeluarga

```csharp
public FontStyle Style { get; }
```

### Property Value

Gaya font yang diurai dari nama subkeluarga

## Contoh

Kode berikut menunjukkan cara Aspose.PSD mendapatkan properti pemformatan inline dari Text Layer.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Muat gambar yang ada ke dalam instance kelas PsdImage
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

        // mendapatkan font yang terdapat dalam lapisan teks
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

### Lihat Juga

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


