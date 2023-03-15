---
title: Enum TextOrientation
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.TextOrientation opsomming. Aufzählung für Textausrichtungsmodus.
type: docs
weight: 4010
url: /de/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

Aufzählung für Textausrichtungsmodus.

```csharp
public enum TextOrientation
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Horizontal | `0` | Die horizontale Textausrichtung. |
| Vertical | `2` | Die vertikale Textausrichtung. |

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

* namensraum [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* Montage [Aspose.PSD](../../)


