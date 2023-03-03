---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD untuk Referensi .NET API
description: ITextStyle Properti. Mendapat atau menyetel perataan Romawi vertikal standar. Ini berdasarkan nilai sumber daya BaselineDirection hanya berlaku jika orientasi teks adalahVertical .
type: docs
weight: 170
url: /id/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Mendapat atau menyetel perataan Romawi vertikal standar. Ini berdasarkan nilai sumber daya BaselineDirection hanya berlaku jika orientasi teks adalahVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Contoh

Kode berikut menunjukkan dukungan untuk properti IsStandardVerticalRomanAlignmentEnabled yang baru.

```csharp
[C#]

// Kode berikut mendemonstrasikan kemampuan untuk mengedit properti IsStandardVerticalRomanAlignmentEnabled yang baru.
// Ini tidak memengaruhi rendering saat ini, tetapi hanya memungkinkan Anda untuk mengedit nilai properti.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Bacaan yang benar
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Bacaan yang benar
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Lihat juga

* interface [ITextStyle](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* perakitan [Aspose.PSD](../../../)


