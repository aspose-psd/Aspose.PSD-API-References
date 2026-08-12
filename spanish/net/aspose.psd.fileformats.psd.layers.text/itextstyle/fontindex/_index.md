---
title: "ITextStyle.FontIndex"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "ITextStyle propiedad. Obtiene el índice de fuente"
type: docs
weight: 110
url: /es/net/aspose.psd.fileformats.psd.layers.text/itextstyle/fontindex/
---
{{< psd/tize >}}
## ITextStyle.FontIndex property

Obtiene el índice de la fuente.

```csharp
public int FontIndex { get; }
```

### Property Value

La fuente.

## Ejemplos

El siguiente código demuestra cómo Aspose.PSD obtiene propiedades del formato en línea de la capa de texto.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Cargar una imagen existente en una instancia de la clase PsdImage
using (var psdImage = (PsdImage)Image.Load(sourceFile))
{

    var layers = psdImage.Layers;
    for (int index = 0; index < layers.Length; index++)
    {
        var layer = layers[index];
        if (!(layer is TextLayer))
        {
            continue;
        }

        var textLayer = (TextLayer)layer;

        // obtiene fuentes que contiene la capa de texto
        var fonts = textLayer.GetFonts();
        var textPortions = textLayer.TextData.Items;

        foreach (var textPortion in textPortions)
        {
            TextFontInfo font = fonts[textPortion.Style.FontIndex];
            if (font != null)
            {
                switch (font.Style)
                {
                    case FontStyle.Regular:
                        regularText.Add(textPortion);
                        break;
                    case FontStyle.Bold:
                        boldText.Add(textPortion);
                        break;
                    case FontStyle.Italic:
                        italicText.Add(textPortion);
                        break;
                    default:
                        throw new ArgumentOutOfRangeException();
                }
            }
        }
    }
}
```

### Ver también

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


