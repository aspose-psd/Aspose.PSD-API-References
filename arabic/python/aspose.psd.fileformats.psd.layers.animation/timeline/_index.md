---
title: "فئة Timeline"
type: docs
weight: 40
url: /ar/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Timeline()](#Timeline__1) | يُنشئ مثيلًا جديدًا لفئة Timeline |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| active_frame_index | int | r | يحصل على فهرس الإطار النشط. |
| af_st | int | r/w | يحصل أو يضبط قيمة AFSt. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | يحصل على قائمة الإطارات. |
| fs_id | int | r/w | يحصل أو يضبط قيمة FsID. |
| loopes_count | ushort | r/w | يحصل أو يضبط عدد الحلقات. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | يحفظ بيانات PsdImage و Timeline إلى موقع الملف المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ. |
| [save(output_stream, options)](#save_output_stream_options_2) | يحفظ بيانات PsdImage و Timeline إلى الدفق المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | يبدل الإطار النشط إلى المستهدف. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

يُنشئ مثيلًا جديدًا لفئة Timeline

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

يحفظ بيانات PsdImage و Timeline إلى موقع الملف المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

يحفظ بيانات PsdImage و Timeline إلى الدفق المحدد بالتنسيق المحدد وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | دفق الإخراج. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

يبدل الإطار النشط إلى المستهدف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| target_active_frame_index | int | فهرس الإطار المستهدف. |

