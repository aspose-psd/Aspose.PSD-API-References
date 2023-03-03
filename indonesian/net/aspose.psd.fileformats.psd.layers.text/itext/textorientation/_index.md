---
title: IText.TextOrientation
second_title: Aspose.PSD untuk Referensi .NET API
description: IText Properti. Mendapat atau mengatur orientasi teks.
type: docs
weight: 30
url: /id/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Mendapat atau mengatur orientasi teks.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Nilai properti

Orientasi teks.

### Contoh

Kode berikut menunjukkan kemampuan untuk mengedit properti TextOrientation baru. Ini tidak memengaruhi rendering saat ini, tetapi hanya memungkinkan Anda untuk mengedit nilai properti.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Bacaan yang benar
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
        // Bacaan yang benar
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Lihat juga

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* perakitan [Aspose.PSD](../../../)


