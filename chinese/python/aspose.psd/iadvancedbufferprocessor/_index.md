---
title: "IAdvancedBufferProcessor 类"
type: docs
weight: 1650
url: /zh/python-net/aspose.psd/iadvancedbufferprocessor/
---

**Summary:** The advanced buffer processor.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IAdvancedBufferProcessor

**Inheritance:** IBufferProcessor

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| finish_row() | 完成该行。 |
| [finish_rows(rows_count)](#finish_rows_rows_count_1) | 完成这些行。 |
| [process_buffer(buffer, buffer_length)](#process_buffer_buffer_buffer_length_2) | 处理缓冲区。 |


### Method: finish_rows(rows_count) {#finish_rows_rows_count_1}


```
 finish_rows(rows_count) 
```

完成这些行。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rows_count | int | 行数。 |

### Method: process_buffer(buffer, buffer_length) {#process_buffer_buffer_buffer_length_2}


```
 process_buffer(buffer, buffer_length) 
```

处理缓冲区。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 缓冲区 | byte | 要处理的缓冲区。 |
| buffer_length | int | 要处理的缓冲区长度。 |

