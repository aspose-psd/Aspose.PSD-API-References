---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD per riferimento API .NET
description: TextLayer proprietà. Ottiene o imposta la matrice di trasformazione
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

Ottiene o imposta la matrice di trasformazione

```csharp
public double[] TransformMatrix { get; set; }
```

### Valore della proprietà

La matrice di trasformazione

### Esempi

Il codice seguente mostra come ottenere la dimensione del carattere per qualsiasi porzione di testo nel livello di testo.

```csharp
[C#]

// Dimensione carattere errata errata 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Vecchia API (utilizzando il carattere del primo paragrafo)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Controllo della dimensione del carattere di base
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Controllo della dimensione reale del carattere
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Nuova API (un livello di testo può contenere qualsiasi quantità di dimensioni dei caratteri)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Controllo della dimensione del carattere della parte di base
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Controllo della dimensione del carattere della parte reale
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Guarda anche

* class [TextLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* assemblea [Aspose.PSD](../../../)


