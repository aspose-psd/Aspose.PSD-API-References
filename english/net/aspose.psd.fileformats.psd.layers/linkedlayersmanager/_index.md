---
title: Class LinkedLayersManager
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager class. Linked layers manager class
type: docs
weight: 3760
url: /net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
{{< psd/tize >}}
## LinkedLayersManager class

Linked layers manager class.

```csharp
public sealed class LinkedLayersManager
```

## Methods

| Name | Description |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | Gets layers by link group id. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | Gets the link group ID associated with the layer. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | Links the input layers and return LingGroupId. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | Unlinks the layer.. |

## Examples

The following example demonstrates how you can manipulate Linked Layers in Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Load an existing image into an instance of PsdImage class
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // link all layers in one linked group
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // gets id for one layer
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // gets all linked layers by link group id.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // unlink each layer from group
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // retrieves NULL for a link group ID that has no layers in the group.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


