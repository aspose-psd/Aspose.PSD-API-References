---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "AiLayerSection Eigenschaft. Gibt den Index der Farbe zurück oder legt ihn fest. Dieses Argument kann Werte zwischen 1 und 26 annehmen. Jeder Integer stellt eine Farbe dar, die der Ebene zu Identifikationszwecken zugewiesen werden kann."
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Liest oder setzt den Index der Farbe. Dieses Argument kann Werte zwischen –1 und 26 annehmen. Jeder Integer stellt eine Farbe dar, die der Ebene zur Benutzeridentifikation zugewiesen werden kann.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

Der Index der Farbe.

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


