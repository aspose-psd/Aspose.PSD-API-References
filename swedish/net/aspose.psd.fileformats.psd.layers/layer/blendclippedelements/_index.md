---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Layer egenskap. Hämtar eller anger blandningen av avklippta elementet"
type: docs
weight: 30
url: /sv/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Hämtar eller anger blandningen av det beskurna elementet.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

Blandningen av avklippta elementet.

## Exempel

Följande kod demonstrerar stöd för BlendClippedElements egenskapen.

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

### Se även

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


