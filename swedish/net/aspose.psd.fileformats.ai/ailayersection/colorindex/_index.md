---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD för .NET API‑referens"
description: "AiLayerSection egenskap. Hämtar eller anger färgindexet. Detta argument kan ha värden mellan 1 och 26. Varje heltal representerar en färg som kan tilldelas lagret för användaridentifieringsändamål"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Hämtar eller anger färgindexet. Detta argument kan ha värden mellan –1 och 26. Varje heltal representerar en färg som kan tilldelas lagret för användaridentifieringsändamål.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

Färgindexet.

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


