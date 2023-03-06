---
title: Enum TextOrientation
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.TextOrientation Sıralama. Metin yönü modu için numaralandırma.
type: docs
weight: 4010
url: /tr/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

Metin yönü modu için numaralandırma.

```csharp
public enum TextOrientation
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| Horizontal | `0` | Yatay metin yönü. |
| Vertical | `2` | Dikey metin yönü. |

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

* ad alanı [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* toplantı [Aspose.PSD](../../)


