---
title: "Layer.BlendClippedElements"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad Layer. Obtiene o establece la mezcla del elemento recortado"
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Obtiene o establece la fusión del elemento recortado.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

La mezcla del elemento recortado.

## Ejemplos

El siguiente código demuestra el soporte de la propiedad BlendClippedElements.

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

### Ver también

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


