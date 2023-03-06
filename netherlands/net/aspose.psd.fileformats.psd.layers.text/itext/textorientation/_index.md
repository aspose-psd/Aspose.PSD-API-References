---
title: IText.TextOrientation
second_title: Aspose.PSD voor .NET API-referentie
description: IText eigendom. Hiermee wordt de tekstoriëntatie opgehaald of ingesteld.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Hiermee wordt de tekstoriëntatie opgehaald of ingesteld.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Eigendoms-waarde

De oriëntatie van de tekst.

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

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* montage [Aspose.PSD](../../../)


