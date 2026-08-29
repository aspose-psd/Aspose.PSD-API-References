---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα AiLayerSection. Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει πολυστρωματικές μάσκες."
type: docs
weight: 60
url: /el/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει μάσκες πολλαπλών στρωμάτων.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` εάν αυτή η παρουσία έχει πολυστρωματικές μάσκες· διαφορετικά, `false`.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη των ιδιοτήτων HasMultiLayerMasks και ColorIndex στην AiLayerSection.

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

### Δείτε επίσης

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


