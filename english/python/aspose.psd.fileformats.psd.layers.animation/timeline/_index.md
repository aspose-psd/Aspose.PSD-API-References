---
title: Timeline Class
type: docs
weight: 40
url: /python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.4.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Timeline()](#Timeline__1) | Initializes a new instance of the Timeline class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Gets the active frame index. |
| af_st | int | r/w | Gets or sets the AFSt value. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Gets the list of frames. |
| fs_id | int | r/w | Gets or sets the FsID value. |
| loopes_count | ushort | r/w | Gets or sets the count of loops. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Saves the PsdImage's and Timeline data to the specified file location in the specified format according to save options. |
| [save(output_stream, options)](#save_output_stream_options_2) | Saves the PsdImage's and Timeline data to the specified stream in the specified format according to save options. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Switches the active frame to targeted. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Initializes a new instance of the Timeline class

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Saves the PsdImage's and Timeline data to the specified file location in the specified format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The options. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Saves the PsdImage's and Timeline data to the specified stream in the specified format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | The output stream. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | The options. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Switches the active frame to targeted.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| target_active_frame_index | int | The target frame index. |

