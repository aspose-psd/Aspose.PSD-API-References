---
title: "TextLayer.GetFonts"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode TextLayer. Obtient l'ensemble de polices du calque texte"
type: docs
weight: 90
url: /fr/net/aspose.psd.fileformats.psd.layers/textlayer/getfonts/
---
{{< psd/tize >}}
## TextLayer.GetFonts method

Obtient l'ensemble des polices du calque de texte.

```csharp
public TextFontInfo[] GetFonts()
```

### Valeur de retour

L'ensemble de polices du calque texte.

## Exemples

Le code suivant montre comment Aspose.PSD récupère les propriétés du formatage en ligne du calque de texte.

```csharp
[C#]

string sourceFile = "inline_formatting.psd";
List<ITextPortion> regularText = new List<ITextPortion>();
List<ITextPortion> boldText = new List<ITextPortion>();
List<ITextPortion> italicText = new List<ITextPortion>();

// Chargez une image existante dans une instance de la classe PsdImage
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

        // récupère les polices contenues dans le calque de texte
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

### Voir aussi

* class [TextFontInfo](../../../aspose.psd.fileformats.psd.layers.text/textfontinfo/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


