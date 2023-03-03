---
title: IText.TextOrientation
second_title: Aspose.PSD für .NET-API-Referenz
description: IText eigendom. Ruft die Textausrichtung ab oder legt sie fest.
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Ruft die Textausrichtung ab oder legt sie fest.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Eigentumswert

Die Textausrichtung.

### Beispiele

Der folgende Code demonstriert die Möglichkeit, die neue TextOrientation-Eigenschaft zu bearbeiten. Dies wirkt sich im Moment nicht auf das Rendern aus, sondern ermöglicht Ihnen nur, den Eigenschaftswert zu bearbeiten.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Richtiges Lesen
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
        // Richtiges Lesen
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Siehe auch

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* Montage [Aspose.PSD](../../../)


