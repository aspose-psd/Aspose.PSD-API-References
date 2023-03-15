---
title: Enum JustificationMode
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.JustificationMode enum. Mode perataan teks.
type: docs
weight: 1650
url: /id/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

Mode perataan teks.

```csharp
public enum JustificationMode
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Left | `0` | Teks rata kiri. |
| Right | `1` | Teks rata kanan. |
| Center | `2` | Teks tengah. |

### Contoh

Kode berikut menunjukkan dukungan enum JustificationMode untuk menyetel perataan teks untuk bagian teks.

```csharp
[C#]

string src = "source1107.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (var image = (PsdImage) Image.Load(src))
{
    var txtLayer = image.AddTextLayer("Text line1\rText line2\rText line3",
        new Rectangle(200, 200, 500, 500));
    var portions = txtLayer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Left;
    portions[1].Paragraph.Justification = JustificationMode.Right;
    portions[2].Paragraph.Justification = JustificationMode.Center;

    foreach (var portion in portions)
    {
        portion.Style.FontSize = 24;
    }

    txtLayer.TextData.UpdateLayerData();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Lihat juga

* ruang nama [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* perakitan [Aspose.PSD](../../)


