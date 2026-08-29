---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà AiLayerSection. Ottiene o imposta un valore che indica se questa istanza ha maschere multilivello"
type: docs
weight: 60
url: /it/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Ottiene o imposta un valore che indica se questa istanza ha maschere multilivello.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` se questa istanza ha maschere multilivello; altrimenti, `false`.

## Esempi

Il codice seguente dimostra il supporto delle proprietà HasMultiLayerMasks e ColorIndex in AiLayerSection.

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

### Vedi anche

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


