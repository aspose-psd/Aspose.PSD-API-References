---
title: Enum TextOrientation
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.TextOrientation uppräkning. Uppräkning för textorienteringsläge.
type: docs
weight: 4010
url: /sv/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

Uppräkning för textorienteringsläge.

```csharp
public enum TextOrientation
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Horizontal | `0` | Den horisontella textorienteringen. |
| Vertical | `2` | Den vertikala textorienteringen. |

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

* namnutrymme [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* hopsättning [Aspose.PSD](../../)


