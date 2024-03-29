---
title: LinkedLayersManager.UnlinkLayer
second_title: Aspose.PSD for .NET API Reference
description: LinkedLayersManager method. Unlinks the layer
type: docs
weight: 40
url: /net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/
---
{{< psd/tize >}}
## LinkedLayersManager.UnlinkLayer method

Unlinks the layer..

```csharp
public void UnlinkLayer(Layer layer)
```

| Parameter | Type | Description |
| --- | --- | --- |
| layer | Layer | The layer. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The layer is null. |
| ArgumentException | The container of the layer should be the same as the current PsdImage. |

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


