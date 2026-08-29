---
title: "SmartObjectProvider.ConvertToSmartObject"
second_title: "Aspose.PSD for .NET API 参考"
description: "SmartObjectProvider 方法。将图层转换为嵌入式智能对象"
type: docs
weight: 10
url: /zh/net/aspose.psd.fileformats.psd/smartobjectprovider/converttosmartobject/
---
{{< psd/tize >}}
## ConvertToSmartObject(params int[]) {#converttosmartobject_1}

将图层转换为嵌入式智能对象。

```csharp
public SmartObjectLayer ConvertToSmartObject(params int[] layerNumbers)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layerNumbers | Int32[] | 图层编号。 |

### 返回值

已创建的 [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 没有可转换的图层。或图层编号超出范围。 |

### 另请参阅

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## ConvertToSmartObject(Layer[]) {#converttosmartobject}

将图层转换为嵌入式智能对象。

```csharp
public SmartObjectLayer ConvertToSmartObject(Layer[] layers)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layers | Layer[] | 图层。 |

### 返回值

已创建的 [`SmartObjectLayer`](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | 没有可转换的图层。 |

### 另请参阅

* class [SmartObjectLayer](../../../aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/)
* class [Layer](../../../aspose.psd.fileformats.psd.layers/layer/)
* class [SmartObjectProvider](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


