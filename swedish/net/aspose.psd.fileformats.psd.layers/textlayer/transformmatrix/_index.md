---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD för .NET API-referens
description: TextLayer fast egendom. Hämtar eller ställer in transformationsmatrisen
type: docs
weight: 70
url: /sv/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

Hämtar eller ställer in transformationsmatrisen

```csharp
public double[] TransformMatrix { get; set; }
```

### Fastighetsvärde

Transformeringsmatrisen

### Exempel

Följande kod visar hur man får teckenstorlek för valfri textdel i textlagret.

```csharp
[C#]

// Extraherade fel teckenstorlek 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Gammalt API (med teckensnittet första stycket)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Kontrollerar bastypsnittsstorleken
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Kontrollerar verklig teckenstorlek
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Nytt API (ett textlager kan innehålla valfri mängd teckenstorlekar)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Kontrollerar basdelens teckenstorlek
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Kontrollerar verklig del teckenstorlek
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Se även

* class [TextLayer](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* hopsättning [Aspose.PSD](../../../)


