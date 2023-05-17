---
title: SmartObjectProvider.ConvertToSmartObject
second_title: Aspose.PSD for .NET API Reference
description: SmartObjectProvider method. Converts layers to an embedded smart object
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd/smartobjectprovider/converttosmartobject/
---
{{< psd/tize >}}
## ConvertToSmartObject(params int[]) {#converttosmartobject_1}

Converts layers to an embedded smart object.

```csharp
public SmartObjectLayer ConvertToSmartObject(params int[] layerNumbers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| layerNumbers | Int32[] | The layer numbers. |

### Return Value

The created [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instance.

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | No layers to convert. or Layer number is out of range. |

### See Also

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../smartobjectprovider/)
* assembly [Aspose.PSD](../../../)

---

## ConvertToSmartObject(Layer[]) {#converttosmartobject}

Converts layers to an embedded smart object.

```csharp
public SmartObjectLayer ConvertToSmartObject(Layer[] layers)
```

| Parameter | Type | Description |
| --- | --- | --- |
| layers | Layer[] | The layers. |

### Return Value

The created [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) instance.

### Exceptions

| exception | condition |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | No layers to convert. |

### See Also

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../smartobjectprovider/)
* assembly [Aspose.PSD](../../../)


