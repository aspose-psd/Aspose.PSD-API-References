---
title: Layer.IsVisible
second_title: Aspose.PSD for .NET API Reference
description: Layer property. Gets or sets a value indicating whether the layer is visible
type: docs
weight: 170
url: /net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

Gets or sets a value indicating whether the layer is visible

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` if this instance is visible; otherwise, `false`.

## Examples

The following example demonstrates how you can change LayerGroup visibility in Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// make changes in layer names and save it
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Turn off everything inside a group
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### See Also

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


