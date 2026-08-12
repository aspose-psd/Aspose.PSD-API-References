---
title: "TextLayer.TransformMatrix"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad TextLayer. Obtiene o establece la matriz de transformación"
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
{{< psd/tize >}}
## TextLayer.TransformMatrix property

Obtiene o establece la matriz de transformación

```csharp
public double[] TransformMatrix { get; set; }
```

### Property Value

La matriz de transformación

## Ejemplos

El siguiente código demuestra cómo obtener el tamaño de fuente para cualquier porción de texto en la capa de texto.

```csharp
[C#]

// Tamaño de fuente extraído incorrecto
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // API antigua (usando la fuente del primer párrafo)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Comprobando el tamaño de fuente base
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Comprobando el tamaño de fuente real
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Nueva API (Una capa de texto puede contener cualquier cantidad de tamaños de fuente)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Comprobando el tamaño de fuente de la porción base
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Comprobando el tamaño de fuente de la porción real
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Ver también

* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


