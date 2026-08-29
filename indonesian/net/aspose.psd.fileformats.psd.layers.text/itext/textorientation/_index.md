---
title: "IText.TextOrientation"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "IText properti. Mendapatkan atau mengatur orientasi teks"
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
{{< psd/tize >}}
## IText.TextOrientation property

Mendapatkan atau mengatur orientasi teks.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Property Value

Orientasi teks.

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


