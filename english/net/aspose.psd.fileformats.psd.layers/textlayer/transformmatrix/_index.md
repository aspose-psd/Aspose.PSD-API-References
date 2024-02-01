---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD for .NET API Reference
description: TextLayer property. Gets or sets the transform matrix
type: docs
weight: 70
url: /net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

Gets or sets the transform matrix

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

The transform matrix

## Examples

The following code demonstrates how to get font size for any text portion in the text layer.

```csharp
[C#]

// Extracted wrong Font size 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Old API (Using the first paragraph font)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Checking the base font size
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Checking real font size
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // New API (One text layer may contain any quantity of font sizes)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Checking the base portion font size
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Checking real portion font size
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### See Also

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


