---
title: "Класс SmartObjectResource"
type: docs
weight: 900
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---

**Summary:** Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file.<br/>            Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartObjectResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| anti_alias_policy | int | r/w | Получает или задает политику сглаживания данных слоя смарт-объекта в изображении PSD. |
| bottom | double | r/w | Получает или задает положение нижней границы размещённого слоя в изображении PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Получает или задает границы размещённого слоя в файле PSD. |
| comp | int | r/w | Получает или задает значение comp данных слоя смарт-объекта в файле PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Слойные компоновки в смарт-объектах</see> |
| comp_id | int | r/w | Получает или задает идентификатор текущего выбранного comp для дочернего документа, который будет -1, если ничего не выбрано.<br/>            Comp'ы — это композиции макета страницы, которые могут создавать дизайнеры. С помощью слойных компоновок вы можете создавать, управлять и просматривать несколько версий<br/>            макета в одном файле Adobe® Photoshop® file. Слойная компоновка — это снимок состояния панели Layers. Слойные компоновки сохраняют три типа параметров слоев, но<br/>            это свойство получает идентификатор выбранной слойной компоновки для слоя смарт-объекта в файле PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Слойные компоновки в смарт-объектах</see> |
| crop | int | r/w | Получает или задает обрезку данных слоя смарт-объекта в изображении PSD. |
| duration_denominator | int | r/w | Получает или задает знаменатель длительности. |
| duration_numerator | int | r/w | Получает или задает числитель длительности. |
| frame_count | int | r/w | Получает или задает количество кадров данных слоя смарт‑объекта в файле PSD. |
| frame_step_denominator | int | r/w | Получает или задает знаменатель шага кадра. |
| frame_step_numerator | int | r/w | Получает или задает числитель шага кадра. |
| height | double | r/w | Получает или задает высоту. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Получает или задает единицу измерения горизонтальных точек сетки. |
| horizontal_mesh_points | double | r/w | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| is_custom | bool | r/w | Получает или задает значение, указывающее, является ли стиль искажения этого экземпляра пользовательским.<br/>            Если true, он содержит точки сетки. Если установить false, он удаляет точки сетки. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Получает или задает элементы дескриптора данных слоя смарт‑объекта в файле PSD. |
| key | int | r | Получает ключ ресурса слоя. |
| слева | double | r/w | Получает или задает левое положение размещённого слоя в файле PSD. |
| длина | int | r | Получает длину ресурса смарт‑объекта в байтах. |
| non_affine_transform_matrix | double | r/w | Получает или задает неаффинную матрицу преобразования данных слоя смарт‑объекта в файле PSD. |
| original_comp_id | int | r | Получает оригинальный идентификатор текущего выбранного Comp для дочернего документа, который будет -1, если ничего не выбрано.<br/>            Это свойство получает оригинальный идентификатор выбора слоя Comp для смарт‑объекта в файле PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Слой‑компоновки в смарт‑объектах</see> |
| page_number | int | r/w | Получает или задает номер страницы данных слоя смарт‑объекта в файле PSD. |
| perspective | double | r/w | Получает или задает значение перспективы размещённого слоя в файле PSD. |
| perspective_other | double | r/w | Получает или задает другое значение перспективы размещённого слоя в файле PSD. |
| placed_id | Guid | r/w | Получает или задает уникальный идентификатор этих данных слоя смарт‑объекта в изображении PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Получает или задает тип данных слоя смарт‑объекта в файле PSD. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| resolution | double | r/w | Получает или задает разрешение данных слоя смарт‑объекта в файле PSD. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Получает или задает единицу измерения разрешения данных слоя смарт‑объекта в файле PSD. |
| справа | double | r/w | Получает или задает правое положение размещённого слоя в файле PSD. |
| signature | int | r | Получает подпись. |
| верх | double | r/w | Получает или задает верхнее положение размещённого слоя в изображении PSD. |
| total_pages | int | r/w | Получает или задает общее количество страниц данных слоя смарт‑объекта в файле PSD. |
| transform_matrix | double | r/w | Получает или задает матрицу преобразования данных слоя смарт‑объекта в файле PSD. |
| u_order | int | r/w | Получает или задает значение порядка U размещённого слоя в файле PSD. |
| unique_id | Guid | r/w | Получает или задает глобальный уникальный идентификатор данных слоя смарт‑объекта [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) в изображении PSD. |
| v_order | int | r/w | Получает или задает значение порядка V размещённого слоя в файле PSD. |
| значение | double | r/w | Получает или задает значение искажения размещённого слоя в изображении PSD. |
| version | int | r | Получает версию размещённого слоя в файле PSD, обычно 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Получает или задает единицу измерения вертикальных точек сетки. |
| vertical_mesh_points | double | r/w | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| width | double | r/w | Получает или задает ширину. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс смарт-объекта в указанный потоковый контейнер. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет ресурс смарт-объекта в указанный потоковый контейнер.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

