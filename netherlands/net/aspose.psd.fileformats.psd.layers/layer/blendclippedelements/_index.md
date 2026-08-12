---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "Layer eigenschap. Krijgt of stelt de menging van het bijgesneden element in"
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Haalt of stelt de mengmodus van het bijgesneden element in.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

De menging van het bijgesneden element.

## Voorbeelden

De volgende code toont de ondersteuning van de BlendClippedElements-eigenschap.

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

### Zie ook

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


