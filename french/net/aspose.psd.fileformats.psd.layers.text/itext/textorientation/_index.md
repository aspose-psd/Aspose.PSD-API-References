---
title: IText.TextOrientation
second_title: Référence de l'API Aspose.PSD pour .NET
description: IText propriété. Obtient ou définit lorientation du texte.
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers.text/itext/textorientation/
---
## IText.TextOrientation property

Obtient ou définit l'orientation du texte.

```csharp
public TextOrientation TextOrientation { get; set; }
```

### Valeur de la propriété

L'orientation du texte.

### Exemples

Le code suivant montre la possibilité de modifier la nouvelle propriété TextOrientation. Cela n'affecte pas le rendu pour le moment, mais vous permet uniquement de modifier la valeur de la propriété.

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

### Voir également

* enum [TextOrientation](../../../aspose.psd.fileformats.psd/textorientation/)
* interface [IText](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itext/)
* Assemblée [Aspose.PSD](../../../)


