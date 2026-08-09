---
title: "IPartialRawDataLoader.Process"
second_title: "Aspose.PSD for .NET API 参考"
description: "IPartialRawDataLoader 方法。处理已加载的数据"
type: docs
weight: 10
url: /zh/net/aspose.psd/ipartialrawdataloader/process/
---
{{< psd/tize >}}
## Process(Rectangle, byte[], Point, Point) {#process}

处理已加载的数据。

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 数据矩形。 |
| 数据 | Byte[] | 原始数据。 |
| start | Point | 起始数据点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| 结束 | Point | 结束数据点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |

### 另请参阅

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

处理已加载的数据。

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 数据矩形。 |
| 数据 | Byte[] | 原始数据。 |
| start | Point | 起始数据点。如果不等于 (left,top)，则表示我们拥有的不是完整矩形。 |
| 结束 | Point | 结束数据点。如果不等于 (right,bottom)，则表示我们拥有的不是完整矩形。 |
| loadOptions | LoadOptions | 加载选项。 |

### 另请参阅

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


