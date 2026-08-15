---
title: "PlLdResource Класс"
type: docs
weight: 820
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/
---

**Summary:** Defines the PlLdResource class that contains information about a placed layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.<br/>            It was replaced by SoLdResource in the Adobe� Photoshop� CS3

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlLdResource

**Inheritance:** IPlacedLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| anti_alias_policy | int | r/w | Получает или задает политику сглаживания размещённого слоя в изображении PSD. |
| bottom | double | r/w | Получает или задает положение нижней границы размещённого слоя в изображении PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Получает или задает границы размещённого слоя в файле PSD. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Получает или задает единицу измерения горизонтальных точек сетки. |
| horizontal_mesh_points | double | r/w | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| is_custom | bool | r/w | Получает или задает значение, указывающее, является ли стиль искажения этого экземпляра пользовательским.<br/>            Если true, он содержит точки сетки. Если установить false, он удаляет точки сетки. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Получает или задает элементы искажения. |
| key | int | r | Получает ключ ресурса слоя. |
| слева | double | r/w | Получает или задает левое положение размещённого слоя в файле PSD. |
| длина | int | r | Получает длину ресурса PlLd в байтах. |
| page_number | int | r/w | Получает или задает номер страницы размещённого слоя в файле PSD. |
| perspective | double | r/w | Получает или задает значение перспективы размещённого слоя в файле PSD. |
| perspective_other | double | r/w | Получает или задает другое значение перспективы размещённого слоя в файле PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Получает или задает тип размещённого слоя в файле PSD. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| справа | double | r/w | Получает или задает правое положение размещённого слоя в файле PSD. |
| signature | int | r | Получает подпись. |
| верх | double | r/w | Получает или задает верхнее положение размещённого слоя в изображении PSD. |
| total_pages | int | r/w | Получает или задает общее количество страниц размещённого слоя в файле PSD. |
| transform_matrix | double | r/w | Получает или задает матрицу преобразования размещённого слоя в файле PSD. |
| u_order | int | r/w | Получает или задает значение порядка U размещённого слоя в файле PSD. |
| unique_id | Guid | r/w | Получает или задает глобальный уникальный идентификатор размещённого слоя в изображении PSD. |
| v_order | int | r/w | Получает или задает значение порядка V размещённого слоя в файле PSD. |
| значение | double | r/w | Получает или задает значение искажения размещённого слоя в изображении PSD. |
| version | int | r | Получает версию размещённого слоя в файле PSD, обычно 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Получает или задает единицу измерения вертикальных точек сетки. |
| vertical_mesh_points | double | r/w | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс PlLD в указанный потоковый контейнер. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет ресурс PlLD в указанный потоковый контейнер.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

