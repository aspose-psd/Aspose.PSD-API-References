---
title: "Layer.BlendClippedElements"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà Layer. Ottiene o imposta la fusione dell'elemento ritagliato"
type: docs
weight: 30
url: /it/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Ottiene o imposta la fusione dell'elemento ritagliato.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

La fusione dell'elemento ritagliato.

## Esempi

Il codice seguente dimostra il supporto della proprietà BlendClippedElements.

```csharp
[C#]

string sourceFile = "example_source.psd";
string outputPsd = "example_output.psd";
string outputPng = "example_output.png";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    image.Layers[1].BlendClippedElements = false;
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Vedi anche

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


