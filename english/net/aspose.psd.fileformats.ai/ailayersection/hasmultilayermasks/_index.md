---
title: AiLayerSection.HasMultiLayerMasks
second_title: Aspose.PSD for .NET API Reference
description: AiLayerSection property. Gets or sets a value indicating whether this instance has multilayer masks
type: docs
weight: 60
url: /net/aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/
---
{{< psd/tize >}}
## AiLayerSection.HasMultiLayerMasks property

Gets or sets a value indicating whether this instance has multilayer masks.

```csharp
public bool HasMultiLayerMasks { get; set; }
```

### Property Value

`true` if this instance has multilayer masks; otherwise, `false`.

## Examples

The following code demonstrates support of HasMultiLayerMasks and ColorIndex properties in AiLayerSection.

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

### See Also

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


