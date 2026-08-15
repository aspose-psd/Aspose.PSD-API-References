---
title: "Класс Timeline"
type: docs
weight: 40
url: /ru/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/
---

**Summary:** The time line options model.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.Timeline

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Timeline()](#Timeline__1) | Инициализирует новый экземпляр класса Timeline |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| active_frame_index | int | r | Получает индекс активного кадра. |
| af_st | int | r/w | Получает или задает значение AFSt. |
| frames | [Frame[]](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/frame) | r/w | Получает список кадров. |
| fs_id | int | r/w | Получает или задает значение FsID. |
| loopes_count | ushort | r/w | Получает или задает количество циклов. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(file_path, options)](#save_file_path_options_1) | Сохраняет данные PsdImage и Timeline в указанное файловое расположение в указанном формате согласно параметрам сохранения. |
| [save(output_stream, options)](#save_output_stream_options_2) | Сохраняет данные PsdImage и Timeline в указанный поток в указанном формате согласно параметрам сохранения. |
| [switch_active_frame(target_active_frame_index)](#switch_active_frame_target_active_frame_index_3) | Переключает активный кадр на целевой. |


### Constructor: Timeline() {#Timeline__1}


```
 Timeline() 
```

Инициализирует новый экземпляр класса Timeline

### Method: save(file_path, options) {#save_file_path_options_1}


```
 save(file_path, options) 
```

Сохраняет данные PsdImage и Timeline в указанное файловое расположение в указанном формате согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры. |

### Method: save(output_stream, options) {#save_output_stream_options_2}


```
 save(output_stream, options) 
```

Сохраняет данные PsdImage и Timeline в указанный поток в указанном формате согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| output_stream | _io.BufferedRandom | Выходной поток. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры. |

### Method: switch_active_frame(target_active_frame_index) {#switch_active_frame_target_active_frame_index_3}


```
 switch_active_frame(target_active_frame_index) 
```

Переключает активный кадр на целевой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| target_active_frame_index | int | Индекс целевого кадра. |

