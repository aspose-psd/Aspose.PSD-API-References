---
title: "Enum TextOrientation"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.TextOrientation enum. Aufzählung für den Textorientierungsmodus"
type: docs
weight: 4480
url: /de/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

Aufzählung für den Textorientierungsmodus.

```csharp
public enum TextOrientation
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Horizontal | `0` | Die horizontale Textorientierung. |
| Vertical | `2` | Die vertikale Textorientierung. |

## Beispiele

Der folgende Code demonstriert die Möglichkeit, die neue TextOrientation-Eigenschaft zu bearbeiten. Dies wirkt sich derzeit nicht auf das Rendering aus, sondern erlaubt lediglich das Bearbeiten des Eigenschaftswerts.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Korrektes Lesen
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
        // Korrektes Lesen
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Siehe auch

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


