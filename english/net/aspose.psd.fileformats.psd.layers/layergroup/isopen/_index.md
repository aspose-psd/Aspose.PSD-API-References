---
title: LayerGroup.IsOpen
second_title: Aspose.PSD for .NET API Reference
description: LayerGroup property. Gets or sets is folder opened if set to true than group will be in open state on start up otherwise in minimized state
type: docs
weight: 30
url: /net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

Gets or sets is folder opened if set to `true` than group will be in open state on start up, otherwise in minimized state.

```csharp
public bool IsOpen { get; set; }
```

## Examples

The following code shows how to open and close LayerGroup (Folder) using the IsOpen property.

```csharp
[C#]

// Example of reading and writing IsOpen property at runtime.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### See Also

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* assembly [Aspose.PSD](../../../)


