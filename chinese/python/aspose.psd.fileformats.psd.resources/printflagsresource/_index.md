---
title: "PrintFlagsResource 类"
type: docs
weight: 200
url: /zh/python-net/aspose.psd.fileformats.psd.resources/printflagsresource/
---

**Summary:** Print flags resource

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.PrintFlagsResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PrintFlagsResource()](#PrintFlagsResource__1) | 初始化 PrintFlagsResource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady 的资源签名。 |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 常规 Photoshop 资源签名。 |
| bleed_scale | short | 读/写 | 获取或设置出血比例。 |
| bleed_width | int | 读/写 | 获取或设置出血宽度。 |
| center_crop_mark | byte | 读/写 | 获取或设置中心裁剪标记。 |
| data_size | int | r | 获取资源数据大小（字节）。 |
| id | short | 读/写 | 获取或设置资源的唯一标识符。 |
| minimal_version | int | r | 获取所需的最低 PSD 版本。 |
| name | 字符串 | 读/写 | 获取或设置资源名称。Pascal 字符串，填充至大小为偶数（空名称由两个字节的 0 组成）。 |
| signature | int | r | 获取资源签名。应始终为 '8BIM'。 |
| 大小 | int | r | 获取资源块的大小（字节），包括其数据。 |
| version | short | 读/写 | 获取或设置版本。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | 将资源块保存到指定的流。 |
| validate_values() | 验证资源值。 |


### Constructor: PrintFlagsResource() {#PrintFlagsResource__1}


```
 PrintFlagsResource() 
```

初始化 PrintFlagsResource 类的新实例

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

将资源块保存到指定的流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 用于保存资源块的流。 |

