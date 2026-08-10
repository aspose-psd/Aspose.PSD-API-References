---
title: "Enum LeadingType"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Enum Aspose.PSD.FileFormats.Psd.LeadingType. Tipe leading Photoshop yang merupakan jarak antara baris"
type: docs
weight: 4030
url: /id/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Tipe leading Photoshop (tipe jarak antar baris).

```csharp
public enum LeadingType
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| BottomToBottom | `0` | Leading bottom-to-bottom. |
| TopToTop | `1` | Leading top-to-top. |

## Contoh

Kode berikut menunjukkan dukungan mode leading Bottom-to-bottom dan Top-to-Top dari pengaturan Paragraph.

```csharp
[C#]

string input = "leadingMode.psd";
string output = "output_leadingMode.png";

using (var psdImage = (PsdImage)Image.Load(input, new PsdLoadOptions()))
{
    IText text1 = ((TextLayer)psdImage.Layers[1]).TextData;
    foreach (var textPortion in text1.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.TopToTop; // Change LeadingType value   
    }
    text1.Items[8].Text = "TopToTop";
    text1.Items[8].Style.FillColor = Color.ForestGreen;
    text1.UpdateLayerData();

    IText text2 = ((TextLayer)psdImage.Layers[2]).TextData;
    foreach (var textPortion in text2.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.BottomToBottom; // Change LeadingType value   
    }
    text2.Items[8].Text = "BottomToBottom";
    text2.Items[8].Style.FillColor = Color.ForestGreen;
    text2.UpdateLayerData();

    psdImage.Save(output, new PngOptions());
}
```

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


