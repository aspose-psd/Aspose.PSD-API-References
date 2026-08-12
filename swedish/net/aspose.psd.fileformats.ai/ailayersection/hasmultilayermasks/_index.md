---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD för .NET API‑referens"
description: "AiLayerSection-egenskap. Hämtar eller anger ett värde som indikerar om detta objekt har multilagermasker"
type: docs
weight: 60
url: /sv/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Hämtar eller anger ett värde som indikerar om detta objekt har multilagermasker.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` om detta objekt har multilagermasker; annars `false`.

## Exempel

Följande kod demonstrerar stöd för HasMultiLayerMasks- och ColorIndex-egenskaperna i AiLayerSection.

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

### Se även

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


