---
title: "Timeline 类"
type: docs
weight: 40
url: /zh/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Timeline()](#Timeline__1) | 初始化 Timeline 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_frame_index | int | r | 获取活动帧索引。 |
| af_st | int | 读/写 | 获取或设置 AFSt 值。 |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | 获取帧列表。 |
| fs_id | int | 读/写 | 获取或设置 FsID 值。 |
| loopes_count | ushort | 读/写 | 获取或设置循环计数。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | 根据保存选项，将 PsdImage 的数据和 Timeline 数据保存到指定的文件位置，使用指定的格式。 |
| [save(output_stream, options)](#save_output_stream_options_2) | 根据保存选项，将 PsdImage 的数据和 Timeline 数据保存到指定的流中，使用指定的格式。 |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | 将活动帧切换到目标帧。 |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

初始化 Timeline 类的新实例

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

根据保存选项，将 PsdImage 的数据和 Timeline 数据保存到指定的文件位置，使用指定的格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 选项。 |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

根据保存选项，将 PsdImage 的数据和 Timeline 数据保存到指定的流中，使用指定的格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | 输出流。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 选项。 |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

将活动帧切换到目标帧。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| target_active_frame_index | int | 目标帧索引。 |

