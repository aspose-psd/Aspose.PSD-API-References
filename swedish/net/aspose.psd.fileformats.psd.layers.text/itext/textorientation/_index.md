---
title: IText.TextOrientation
second_title: Aspose.PSD för .NET API-referens
description: IText fast egendom. Hämtar eller ställer in textorienteringen.
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Hämtar eller ställer in textorienteringen.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Fastighetsvärde

Textorienteringen.

### Exempel

Följande kod visar möjligheten att redigera den nya TextOrientation-egenskapen. Detta påverkar inte renderingen för tillfället, utan låter dig bara redigera egenskapsvärdet.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Korrekt läsning
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
        // Korrekt läsning
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Se även

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* hopsättning [Aspose.PSD](../../../)


