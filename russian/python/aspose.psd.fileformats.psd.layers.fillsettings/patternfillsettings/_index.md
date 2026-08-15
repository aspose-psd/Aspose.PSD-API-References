---
title: "Класс PatternFillSettings"
type: docs
weight: 130
url: /ru/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Summary:** Pattern fill effect settings

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings

**Inheritance:** IFillSettings, IPatternFillSettings, BaseFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PatternFillSettings()](#PatternFillSettings__1) | Создает новый экземпляр класса PatternFillSettings |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Получает или задает значение, указывающее, связан ли [link with layer]. |
| угол | double | r/w | Получает или задает угол. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает цвет. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Тип заливки |
| horizontal_offset | int | r/w | Получает или задает горизонтальное смещение. |
| linked | bool | r/w | Получает или задает значение, указывающее, связан ли этот [PatternFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/). |
| pattern_data | int | r/w | Получает или задает данные шаблона. |
| pattern_height | int | r/w | Получает или задает высоту шаблона. |
| pattern_id | string | r/w | Получает или задает идентификатор шаблона. |
| pattern_name | string | r/w | Получает или задает имя шаблона. |
| pattern_width | int | r/w | Получает или задает ширину шаблона. |
| point_type | string | r/w | Получает или задает тип точки. |
| scale | double | r/w | Получает или задает масштаб. |
| vertical_offset | int | r/w | Получает или задает вертикальное смещение. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)](#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1) | Генерирует узлы ресурсов LFX2. |


### Constructor: PatternFillSettings() {#PatternFillSettings__1}


```
 PatternFillSettings() 
```

Создает новый экземпляр класса PatternFillSettings

### Method: generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset)  [static] {#generate_lfx_2_resource_nodes_point_type_color_pattern_name_identifier_scale_linked_offset_1}


```
 generate_lfx_2_resource_nodes(point_type, color, pattern_name, identifier, scale, linked, offset) 
```

Генерирует узлы ресурсов LFX2.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point_type | string | Тип точки. |
| color | [Color](/psd/python-net/aspose.psd/color) | Цвет. |
| pattern_name | string | Имя шаблона. |
| идентификатор | string | Идентификатор. |
| scale | double | Масштаб. |
| linked | bool | если установлено в <c>true</c> [linked]. |
| offset | [PointF](/psd/python-net/aspose.psd/pointf) | Смещение. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Список [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


