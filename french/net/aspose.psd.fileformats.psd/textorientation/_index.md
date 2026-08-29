---
title: "Énumération TextOrientation"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Énumération Aspose.PSD.FileFormats.Psd.TextOrientation. Énumération pour le mode d'orientation du texte"
type: docs
weight: 4480
url: /fr/net/aspose.psd.fileformats.psd/textorientation/
---
{{< psd/tize >}}
## TextOrientation enumeration

Énumération du mode d'orientation du texte.

```csharp
public enum TextOrientation
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Horizontal | `0` | L'orientation du texte horizontale. |
| Vertical | `2` | L'orientation du texte verticale. |

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


