---
title: "IPartialRawDataLoader 类"
type: docs
weight: 1940
url: /zh/python-net/aspose.psd/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | 处理已加载的数据。 |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | 处理已加载的数据。 |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

处理已加载的数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 数据矩形。 |
| 数据 | byte | 原始数据。 |
| start | [Point](/psd/python-net/aspose.psd/point) | 起始数据点。如果不等于 (left,top)，则表示它不是完整的矩形。 |
| end | [Point](/psd/python-net/aspose.psd/point) | 结束数据点。如果不等于 (right,bottom)，则表示它不是完整的矩形。 |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

处理已加载的数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 数据矩形。 |
| 数据 | byte | 原始数据。 |
| start | [Point](/psd/python-net/aspose.psd/point) | 起始数据点。如果不等于 (left,top)，则表示它不是完整的矩形。 |
| end | [Point](/psd/python-net/aspose.psd/point) | 结束数据点。如果不等于 (right,bottom)，则表示它不是完整的矩形。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

