---
title: "TextLayer.TransformMatrix"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "TextLayer-Eigenschaft. Gibt die Transformationsmatrix zurück oder legt sie fest"
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

Liest oder setzt die Transformationsmatrix

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

Die Transformationsmatrix

## Beispiele

Der folgende Code zeigt, wie man die Schriftgröße für beliebige Textabschnitte in der Textebene ermittelt.

```csharp
[C#]

// Falsche Schriftgröße extrahiert 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Alte API (Verwendung der ersten Absatzschriftart)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Überprüfung der Basis-Schriftgröße
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Überprüfung der tatsächlichen Schriftgröße
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Neue API (Eine Textebene kann beliebig viele Schriftgrößen enthalten)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Überprüfung der Basis-Abschnittsschriftgröße
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Überprüfung der tatsächlichen Abschnittsschriftgröße
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Siehe auch

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


