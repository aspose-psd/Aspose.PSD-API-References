---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "ITextStyle properti. Mendapatkan atau mengatur penyelarasan Romawi vertikal standar. Ini berdasarkan nilai sumber BaselineDirection hanya berlaku ketika orientasi teks Vertikal"
type: docs
weight: 170
url: /id/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Mendapatkan atau mengatur perataan Romawi vertikal standar. Ini berdasarkan nilai sumber BaselineDirection hanya berlaku ketika orientasi teks Vertikal.

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## Contoh

Kode berikut menunjukkan dukungan properti IsStandardVerticalRomanAlignmentEnabled yang baru.

```csharp
[C#]

// Kode berikut menunjukkan kemampuan mengedit properti IsStandardVerticalRomanAlignmentEnabled yang baru.
// Ini tidak memengaruhi rendering saat ini, tetapi hanya memungkinkan Anda mengedit nilai properti.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Pembacaan yang benar
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
        // Pembacaan yang benar
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Lihat Juga

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


