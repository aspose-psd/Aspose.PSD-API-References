---
title: "TransparencyIndexResource 类"
type: docs
weight: 260
url: /zh/python-net/aspose.psd.fileformats.psd.resources/transparencyindexresource/
---

**Summary:** The transparency index resource block.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.TransparencyIndexResource

**Inheritance:** ResourceBlock

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TransparencyIndexResource()](#TransparencyIndexResource__1) | 初始化 TransparencyIndexResource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady 的资源签名。 |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 常规 Photoshop 资源签名。 |
| data_size | int | r | 获取资源数据大小（字节）。 |
| id | short | 读/写 | 获取或设置资源的唯一标识符。 |
| minimal_version | int | r | 获取最小所需的 psd 版本。 |
| name | 字符串 | 读/写 | 获取或设置资源名称。Pascal 字符串，填充至大小为偶数（空名称由两个字节的 0 组成）。 |
| signature | int | r | 获取资源签名。应始终为 '8BIM'。 |
| 大小 | int | r | 获取资源块的大小（字节），包括其数据。 |
| transparency_index | short | 读/写 | 获取或设置透明颜色索引。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | 将资源块保存到指定的流。 |
| validate_values() | 验证资源值。 |


### Constructor: TransparencyIndexResource() {#TransparencyIndexResource__1}


```
 TransparencyIndexResource() 
```

初始化 TransparencyIndexResource 类的新实例

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

将资源块保存到指定的流。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 用于保存资源块的流。 |

