---
title: IText.TextOrientation
second_title: Aspose.PSD for .NET API Referansı
description: IText mülk. Metin yönünü alır veya ayarlar.
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Metin yönünü alır veya ayarlar.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Mülk değeri

Metin yönü.

### Örnekler

Aşağıdaki kod, yeni TextOrientation özelliğini düzenleme yeteneğini gösterir. Bu, şu anda işlemeyi etkilemez, ancak yalnızca özellik değerini düzenlemenize izin verir.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Doğru okuma
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
        // Doğru okuma
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Ayrıca bakınız

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* toplantı [Aspose.PSD](../../../)


