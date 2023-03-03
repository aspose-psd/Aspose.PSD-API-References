---
title: TextFontInfo.Style
second_title: Referencia de API de Aspose.PSD para .NET
description: TextFontInfo propiedad. Obtiene el estilo de fuente analizado del nombre de la subfamilia
type: docs
weight: 50
url: /es/net/aspose.psd.fileformats.psd.layers.text/textfontinfo/style/
---
## TextFontInfo.Style property

Obtiene el estilo de fuente analizado del nombre de la subfamilia

```csharp
public FontStyle Style { get; }
```

### El valor de la propiedad

Estilo de fuente analizado del nombre de la subfamilia

### Ejemplos

El siguiente código demuestra cómo Aspose.PSD obtiene las propiedades del formato en línea de la capa de texto.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Carga una imagen existente en una instancia de la clase PsdImage
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

        // obtiene las fuentes que contiene en la capa de texto
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

* enum [FontStyle](../../../aspose.psd/fontstyle/)
* class [TextFontInfo](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.Text](../../textfontinfo/)
* asamblea [Aspose.PSD](../../../)


