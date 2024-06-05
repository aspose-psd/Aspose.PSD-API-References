---
title: AiLayerSection.ColorIndex
second_title: Aspose.PSD for .NET API Reference
description: AiLayerSection property. Gets or sets the index of the color. This argument can take on values between 1 and 26. Each integer represents a color that can be assigned to the layer for user identification purposes
type: docs
weight: 20
url: /net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Gets or sets the index of the color. This argument can take on values between –1 and 26. Each integer represents a color that can be assigned to the layer for user identification purposes.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

The index of the color.

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


