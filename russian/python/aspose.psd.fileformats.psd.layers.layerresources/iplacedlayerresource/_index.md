---
title: "Класс IPlacedLayerResource"
type: docs
weight: 390
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/
---

**Summary:** Defines the IPlacedLayerResource interface that contains information about a placed layer in the PSD file.<br/>            Is is a markup interface used to designate PlLd, Sold and Sole resources in the Adobe® Photoshop® images.<br/>            Is is used to support smart object layers in the Adobe® Photoshop® images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.IPlacedLayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| anti_alias_policy | int | r/w | Получает или задает политику сглаживания размещённого слоя в изображении PSD. |
| bottom | double | r/w | Получает или задает положение нижней границы размещённого слоя в изображении PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Получает или задает границы размещённого слоя в файле PSD. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Получает или задает единицу измерения горизонтальных точек сетки. |
| horizontal_mesh_points | double | r/w | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| is_custom | bool | r/w | Получает или задает значение, указывающее, является ли стиль искажения этого экземпляра пользовательским.<br/>            Если true, он содержит точки сетки. Если установить false, он удаляет точки сетки. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Получает или задает элементы искажения. |
| слева | double | r/w | Получает или задает левое положение размещённого слоя в файле PSD. |
| page_number | int | r/w | Получает или задает номер страницы размещённого слоя в файле PSD. |
| perspective | double | r/w | Получает или задает значение перспективы размещённого слоя в файле PSD. |
| perspective_other | double | r/w | Получает или задает другое значение перспективы размещённого слоя в файле PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Получает или задает тип размещённого слоя в файле PSD. |
| справа | double | r/w | Получает или задает правое положение размещённого слоя в файле PSD. |
| верх | double | r/w | Получает или задает верхнее положение размещённого слоя в изображении PSD. |
| total_pages | int | r/w | Получает или задает общее количество страниц размещённого слоя в файле PSD. |
| transform_matrix | double | r/w | Получает или задает матрицу преобразования размещённого слоя в файле PSD. |
| u_order | int | r/w | Получает или задает значение порядка U размещённого слоя в файле PSD. |
| unique_id | Guid | r/w | Получает или задает глобальный уникальный идентификатор размещённого слоя или смарт‑объекта в изображении PSD. |
| v_order | int | r/w | Получает или задает значение порядка V размещённого слоя в файле PSD. |
| значение | double | r/w | Получает или задает значение искажения размещённого слоя в изображении PSD. |
| version | int | r | Возвращает версию размещённого слоя в файле PSD, обычно 3-5. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Получает или задает единицу измерения вертикальных точек сетки. |
| vertical_mesh_points | double | r/w | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |


