---
title: "Enum TextOrientation"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Enum Aspose.PSD.FileFormats.Psd.TextOrientation. Enumerasi untuk mode orientasi teks"
type: docs
weight: 4480
url: /id/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

Enumerasi untuk mode orientasi teks.

```csharp
public enum TextOrientation
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Horizontal | `0` | Orientasi teks horizontal. |
| Vertical | `2` | Orientasi teks vertikal. |

## Contoh

Kode berikut menunjukkan kemampuan mengedit properti TextOrientation baru. Ini tidak memengaruhi rendering saat ini, tetapi hanya memungkinkan Anda mengedit nilai properti.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Pembacaan yang benar
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // Pembacaan yang benar
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Lihat Juga

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


