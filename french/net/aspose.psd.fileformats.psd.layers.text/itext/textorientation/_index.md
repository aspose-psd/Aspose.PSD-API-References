---
title: "IText.TextOrientation"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "IText propriété. Obtient ou définit l'orientation du texte"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
{{< psd/tize >}}
## IText.TextOrientation property

Obtient ou définit l'orientation du texte.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Property Value

L'orientation du texte.

## Exemples

Le code suivant démontre la capacité de modifier la nouvelle propriété TextOrientation. Cela n'affecte pas le rendu pour le moment, mais permet uniquement de modifier la valeur de la propriété.

```csharp
[C#]

string src = "1336test.psd";
string output = "out_1336test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Vertical)
    {
        // Lecture correcte
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }

    textLayer.TextData.TextOrientation = TextOrientation.Horizontal;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    if (textLayer.TextData.TextOrientation == TextOrientation.Horizontal)
    {
        // Lecture correcte
    }
    else
    {
        throw new Exception("Incorrect reading of TextOrientation property value");
    }
}
```

### Voir aussi

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


