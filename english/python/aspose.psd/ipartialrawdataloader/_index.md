---
title: IPartialRawDataLoader Class
type: docs
weight: 1880
url: /python-net/aspose.psd/ipartialrawdataloader/
---

**Summary:** The partial data loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IPartialRawDataLoader

**Aspose.PSD Version:** 24.5.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(rectangle, data, start, end)](#process_rectangle_data_start_end_1) | Processes the loaded data. |
| [process(rectangle, data, start, end, load_options)](#process_rectangle_data_start_end_load_options_2) | Processes the loaded data. |


### Method: process(rectangle, data, start, end) {#process_rectangle_data_start_end_1}


```
 process(rectangle, data, start, end) 
```

Processes the loaded data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The data rectangle. |
| data | byte | The raw data. |
| start | [Point](/psd/python-net/aspose.psd/point) | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](/psd/python-net/aspose.psd/point) | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |

### Method: process(rectangle, data, start, end, load_options) {#process_rectangle_data_start_end_load_options_2}


```
 process(rectangle, data, start, end, load_options) 
```

Processes the loaded data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | The data rectangle. |
| data | byte | The raw data. |
| start | [Point](/psd/python-net/aspose.psd/point) | The start data point. If not equal to (left,top) meaning that it is not full rectangle we have. |
| end | [Point](/psd/python-net/aspose.psd/point) | The end data point. If not equal to (right,bottom) meaning that it is not full rectangle we have. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | The load options. |

