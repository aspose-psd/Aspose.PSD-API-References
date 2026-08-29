---
title: "AiLayerSection.HasMultiLayerMasks"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "AiLayerSection-Eigenschaft. Gibt einen Wert zurück oder legt ihn fest, der angibt, ob diese Instanz Multilayer‑Masken hat."
type: docs
weight: 60
url: /de/net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Liest oder setzt einen Wert, der angibt, ob diese Instanz Mehrschichtmasken hat.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true`, wenn diese Instanz Multilayer‑Masken hat; andernfalls `false`.

## Beispiele

Der folgende Code demonstriert die Unterstützung der Eigenschaften HasMultiLayerMasks und ColorIndex in AiLayerSection.

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

### Siehe auch

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


