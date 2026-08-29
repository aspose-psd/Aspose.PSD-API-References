---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété AiLayerSection. Obtient ou définit l'index de la couleur. Cet argument peut prendre des valeurs entre 1 et 26. Chaque entier représente une couleur pouvant être assignée à la couche à des fins d'identification par l'utilisateur."
type: docs
weight: 20
url: /fr/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Obtient ou définit l'index de la couleur. Cet argument peut prendre des valeurs entre –1 et 26. Chaque entier représente une couleur qui peut être attribuée au calque à des fins d'identification par l'utilisateur.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

L'index de la couleur.

## Exemples

Le code suivant montre la prise en charge des propriétés HasMultiLayerMasks et ColorIndex dans AiLayerSection.

```csharp
[C#]

string sourceFile = "example.ai";
string outputFilePath = "example.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.Layers.Length, 2);
    AssertAreEqual(image.Layers[0].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[0].ColorIndex, -1);
    AssertAreEqual(image.Layers[1].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[1].ColorIndex, -1);

    image.Save(outputFilePath, new PngOptions());
}
```

### Voir aussi

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


