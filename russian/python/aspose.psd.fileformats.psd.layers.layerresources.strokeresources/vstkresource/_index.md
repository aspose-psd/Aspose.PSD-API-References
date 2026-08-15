---
title: "VstkResource Класс"
type: docs
weight: 40
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Инициализирует новый экземпляр класса VstkResource |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| fill_enabled | bool | r/w | Получает или задает значение, указывающее, включено ли заполнение Stroke. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Получает или задает параметры заполнения обводки. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| stroke_enabled | bool | r/w | Получает или задает значение, указывающее, включен ли эффект stroke. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Получает или задает режим наложения Stroke. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Получает или задает сущность Stroke. Свойство определяет настройки заполнения штриха. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Получает или задает выравнивание линии стиля обводки. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Получает или задает тип окончания линии стиля stroke. |
| stroke_style_line_cap_width | double | r/w | Получает или задает ширину окончания линии Stroke. |
| stroke_style_line_dash_offset | int | r/w | Получает или задает смещение stroke style line dash offset. |
| stroke_style_line_dash_set | double | r/w | Получает или задает массив штрихов линии. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Получает или задает тип соединения линий стиля Stroke. |
| stroke_style_line_width | double | r/w | Получает или задает ширину линии Stroke. |
| stroke_style_miter_limit | double | r/w | Получает или задает stroke style miter limit. |
| stroke_style_opacity | int | r/w | Получает или задает непрозрачность стиля Stroke (0-100%). |
| stroke_style_resolution | double | r/w | Получает или задает разрешение стиля обводки. |
| stroke_style_scale_lock | bool | r/w | Получает или задает блокировку масштаба стиля обводки. |
| stroke_style_stroke_adjust | bool | r/w | Получает или задает настройку обводки. |
| stroke_style_version | int | r/w | Получает или задает версию стиля обводки. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Инициализирует новый экземпляр класса VstkResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет ресурс в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

