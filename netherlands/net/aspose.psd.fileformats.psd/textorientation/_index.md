---
title: Enum TextOrientation
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.TextOrientation opsomming. Opsomming voor tekstoriëntatiemodus.
type: docs
weight: 4010
url: /nl/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

Opsomming voor tekstoriëntatiemodus.

```csharp
public enum TextOrientation
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Horizontal | `0` | De horizontale tekstoriëntatie. |
| Vertical | `2` | De verticale tekstoriëntatie. |

### Voorbeelden

De volgende code demonstreert de mogelijkheid om de nieuwe eigenschap TextOrientation te bewerken. Dit heeft op dit moment geen invloed op de weergave, maar u kunt alleen de eigenschapswaarde bewerken.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Correct lezen
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
        // Correct lezen
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Zie ook

* naamruimte [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* montage [Aspose.PSD](../../)


