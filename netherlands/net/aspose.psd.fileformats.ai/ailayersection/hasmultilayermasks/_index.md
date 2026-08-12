---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "AiLayerSection-eigenschap. Haalt of stelt een waarde in die aangeeft of deze instantie multilayer-masks heeft"
type: docs
weight: 60
url: /nl/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Haalt of stelt een waarde in die aangeeft of deze instantie multilayer-masks heeft.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` als deze instantie multilayer-masks heeft; anders `false`.

## Voorbeelden

De volgende code demonstreert de ondersteuning van HasMultiLayerMasks- en ColorIndex-eigenschappen in AiLayerSection.

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

### Zie ook

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


