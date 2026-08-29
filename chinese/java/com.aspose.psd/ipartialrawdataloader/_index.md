---
title: "IPartialRawDataLoader"
second_title: "Aspose.PSD 的 Java API 参考"
description: "部分数据加载器。"
type: docs
weight: 133
url: /zh/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

部分数据加载器。
## Methods

| Method | 描述 |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | 处理已加载的数据。 |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | 处理已加载的数据。 |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


处理已加载的数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 数据矩形。 |
| data | byte[] | 原始数据。 |
| start | [Point](../../com.aspose.psd/point) | 起始数据点。如果不等于 (left,top)，则表示我们拥有的不是完整的矩形。 |
| end | [Point](../../com.aspose.psd/point) | 结束数据点。如果不等于 (right,bottom)，则表示我们拥有的不是完整的矩形。 |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


处理已加载的数据。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | 数据矩形。 |
| data | byte[] | 原始数据。 |
| start | [Point](../../com.aspose.psd/point) | 起始数据点。如果不等于 (left,top)，则表示我们拥有的不是完整的矩形。 |
| end | [Point](../../com.aspose.psd/point) | 结束数据点。如果不等于 (right,bottom)，则表示我们拥有的不是完整的矩形。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 加载选项。 |

