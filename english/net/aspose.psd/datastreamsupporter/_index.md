---
title: Class DataStreamSupporter
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.DataStreamSupporter class. The data stream container
type: docs
weight: 740
url: /net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

The data stream container.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Properties

| Name | Description |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Gets the object's data stream. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Gets a value indicating whether this instance is disposed. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Gets a value indicating whether object's data is cached currently and no data reading is required. |

## Methods

| Name | Description |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Caches the data and ensures no additional data loading will be performed from the underlying [`DataStreamContainer`](./datastreamcontainer/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Disposes the current instance. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Saves the object's data to the current `DataStreamSupporter`. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Saves the object's data to the specified stream. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Saves the object's data to the specified file location. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Saves the object's data to the specified file location. |

### See Also

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


