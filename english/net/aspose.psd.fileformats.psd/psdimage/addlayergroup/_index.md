---
title: PsdImage.AddLayerGroup
second_title: Aspose.PSD for .NET API Reference
description: PsdImage method. Adds the layer group
type: docs
weight: 400
url: /net/aspose.psd.fileformats.psd/psdimage/addlayergroup/
---
{{< psd/tize >}}
## PsdImage.AddLayerGroup method

Adds the layer group.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index, bool startBehaviour)
```

| Parameter | Type | Description |
| --- | --- | --- |
| groupName | String | Name of the group. |
| index | Int32 | The index of the layer to insert after. |
| startBehaviour | Boolean | if set to `true` [start behaviour] than group will be in open state on start up, otherwise in minimized state. |

### Return Value

Opening group layer

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Index must be in bounds of Layers count |

### See Also

* class [LayerGroup](../../../aspose.psd.fileformats.psd.layers/layergroup/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


