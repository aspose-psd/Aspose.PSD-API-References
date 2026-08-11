---
title: "AiLayerSection.ColorIndex"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà AiLayerSection. Ottiene o imposta l'indice del colore. Questo argomento può assumere valori compresi tra 1 e 26. Ogni intero rappresenta un colore che può essere assegnato al livello per scopi di identificazione dell'utente."
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Ottiene o imposta l'indice del colore. Questo argomento può assumere valori compresi tra –1 e 26. Ogni intero rappresenta un colore che può essere assegnato al livello per scopi di identificazione dell'utente.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

L'indice del colore.

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


