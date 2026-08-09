---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "AiLayerSection propriété. Obtient ou définit une valeur indiquant si cette instance possède des masques multicouches"
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Obtient ou définit une valeur indiquant si cette instance possède des masques multicouches.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` si cette instance possède des masques multicouches ; sinon, `false`.

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


