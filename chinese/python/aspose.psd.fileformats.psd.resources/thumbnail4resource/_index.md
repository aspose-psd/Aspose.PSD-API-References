---
title: "Thumbnail4Resource 类"
type: docs
weight: 240
url: /zh/python-net/aspose.psd.fileformats.psd.resources/thumbnail4resource/
---

**Summary:** Represents the thumbnail resource for psd 4.0.

**Module:** [aspose.psd.fileformats.psd.resources](/psd/python-net/aspose.psd.fileformats.psd.resources/)

**Full Name:** aspose.psd.fileformats.psd.resources.Thumbnail4Resource

**Inheritance:** ThumbnailResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Thumbnail4Resource()](#Thumbnail4Resource__1) | 初始化 Thumbnail4Resource 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| RESOUCE_BLOCK_ME_SA_SIGNATURE [static] | int | r | ImageReady 的资源签名。 |
| RESOUCE_BLOCK_SIGNATURE [static] | int | r | 常规 Photoshop 资源签名。 |
| bits_pixel | short | 读/写 | 获取或设置位像素。 |
| data_size | int | r | 获取资源数据大小（字节）。 |
| format | [ThumbnailFormat](/psd/python-net/aspose.psd.fileformats.psd.resources/thumbnailformat) | r/w | 获取或设置缩略图数据格式。 |
| height | int | 读/写 | 获取或设置缩略图的高度（像素）。 |
| id | short | 读/写 | 获取或设置资源的唯一标识符。 |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) | r/w | 获取或设置 JPEG 选项。仅在缩略图资源保存为 JPEG 文件格式时适用。当定义为 RAW 格式时，此选项无效。 |
| minimal_version | int | r | 获取最小所需的 psd 版本。 |
| name | 字符串 | 读/写 | 获取或设置资源名称。Pascal 字符串，填充至大小为偶数（空名称由两个字节的 0 组成）。 |
| planes_count | short | 读/写 | 获取或设置平面计数。 |
| signature | int | r | 获取资源签名。应始终为 '8BIM'。 |
| 大小 | int | r | 获取资源块的大小（字节），包括其数据。 |
| size_after_compression | int | r | 获取或设置压缩后的大小。用于一致性检查。 |
| thumbnail_argb_32_data | int | 读/写 | 获取或设置 32 位 ARGB 缩略图数据。 |
| thumbnail_data | [Color[]](/psd/python-net/aspose.psd/color) | r/w | 获取或设置缩略图数据。 |
| total_size | int | r | 获取总数据大小。 |
| width | int | 读/写 | 获取或设置缩略图的宽度（像素）。 |
| width_bytes | int | r | 获取行宽（字节）。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(stream)](#save_stream_1) | 保存资源块数据。 |
| validate_values() | 验证资源值。 |


### Constructor: Thumbnail4Resource() {#Thumbnail4Resource__1}


```
 Thumbnail4Resource() 
```

初始化 Thumbnail4Resource 类的新实例

### Method: save(stream) {#save_stream_1}


```
 save(stream) 
```

保存资源块数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) |  |

