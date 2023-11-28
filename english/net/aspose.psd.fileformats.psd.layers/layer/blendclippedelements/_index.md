---
title: Layer.BlendClippedElements
second_title: Aspose.PSD for .NET API Reference
description: Layer property. Gets or sets the blending of clipped element
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Gets or sets the blending of clipped element.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

The blending of clipped element.

## Examples

The following code demonstrates support of BlendClippedElements property.

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

### See Also

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


