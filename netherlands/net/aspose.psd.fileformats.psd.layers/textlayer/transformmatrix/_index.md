---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD voor .NET API-referentie
description: TextLayer eigendom. Haalt of stelt de transformatiematrix in
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

Haalt of stelt de transformatiematrix in

```csharp
public double[] TransformMatrix { get; set; }
```

### Eigendoms-waarde

De transformatiematrix

### Voorbeelden

De volgende code laat zien hoe u de lettergrootte kunt krijgen voor elk tekstgedeelte in de tekstlaag.

```csharp
[C#]

// Verkeerde lettergrootte uitgepakt 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Oude API (met gebruik van het eerste alinea-lettertype)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // De basislettergrootte controleren
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Controle van de werkelijke lettergrootte
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Nieuwe API (één tekstlaag kan een willekeurige hoeveelheid lettergroottes bevatten)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // De lettergrootte van het basisgedeelte controleren
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Controleren van de werkelijke lettergrootte van een portie
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Zie ook

* class [TextLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* montage [Aspose.PSD](../../../)


