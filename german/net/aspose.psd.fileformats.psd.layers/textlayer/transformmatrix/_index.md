---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD für .NET-API-Referenz
description: TextLayer eigendom. Holt oder setzt die Transformationsmatrix
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

Holt oder setzt die Transformationsmatrix

```csharp
public double[] TransformMatrix { get; set; }
```

### Eigentumswert

Die Transformationsmatrix

### Beispiele

Der folgende Code zeigt, wie Sie die Schriftgröße für einen beliebigen Textabschnitt in der Textebene abrufen.

```csharp
[C#]

// Falsche Schriftgröße extrahiert 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Alte API (mit der Schriftart des ersten Absatzes)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Überprüfen der Basisschriftgröße
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Überprüfen der tatsächlichen Schriftgröße
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Neue API (Eine Textebene kann beliebig viele Schriftgrößen enthalten)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Überprüfen der Schriftgröße des Basisteils
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Überprüfung der Schriftgröße des realen Teils
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Siehe auch

* class [TextLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* Montage [Aspose.PSD](../../../)


