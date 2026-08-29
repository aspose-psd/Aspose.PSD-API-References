---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Layer-Eigenschaft. Ruft das Blending des beschnittenen Elements ab oder legt es fest"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Liest oder setzt das Blending des beschnittenen Elements.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

Das Blending des beschnittenen Elements.

## Beispiele

Der folgende Code demonstriert die Unterstützung der BlendClippedElements-Eigenschaft.

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

### Siehe auch

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


