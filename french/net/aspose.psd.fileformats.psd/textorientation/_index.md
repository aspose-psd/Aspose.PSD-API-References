---
title: Enum TextOrientation
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.TextOrientation énumération. Énumération pour le mode dorientation du texte.
type: docs
weight: 4010
url: /fr/net/aspose.psd.fileformats.psd/textorientation/
---
## TextOrientation enumeration

Énumération pour le mode d'orientation du texte.

```csharp
public enum TextOrientation
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| Horizontal | `0` | L'orientation horizontale du texte. |
| Vertical | `2` | L'orientation verticale du texte. |

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

* espace de noms [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* Assemblée [Aspose.PSD](../../)


