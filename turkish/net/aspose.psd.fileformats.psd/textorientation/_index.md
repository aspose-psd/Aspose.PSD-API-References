---
title: "Enum TextOrientation"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.TextOrientation enum. Metin yönlendirme modu için enum"
type: docs
weight: 4510
url: /tr/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

Metin yönlendirme modu için enum.

```csharp
public enum TextOrientation
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Horizontal | `0` | Yatay metin yönlendirmesi. |
| Vertical | `2` | Dikey metin yönlendirmesi. |

## Örnekler

Aşağıdaki kod, yeni TextOrientation özelliğini düzenleme yeteneğini gösterir. Bu şu anda renderlamayı etkilemez, ancak yalnızca özellik değerini düzenlemenize izin verir.

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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


