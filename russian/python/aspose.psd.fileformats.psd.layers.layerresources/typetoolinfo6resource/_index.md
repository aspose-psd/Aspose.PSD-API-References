---
title: "Класс TypeToolInfo6Resource"
type: docs
weight: 990
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/
---

**Summary:** The type tool information. For PSD version higher or equal to the 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfo6Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [TypeToolInfo6Resource(class_id, warp_class_id)](#TypeToolInfo6Resource_class_id_warp_class_id_1) | Инициализирует новый экземпляр класса [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| bottom | int | r/w | Получает или задает нижнее расположение. |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает идентификатор класса. |
| class_name | string | r/w | Получает или задает имя класса. |
| descriptor_version | int | r/w | Получает или задает версию дескриптора. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Получает или задает элементы. |
| key | int | r | Получает ключ ресурса слоя. |
| слева | int | r/w | Получает или задает левое расположение. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| справа | int | r/w | Получает или задает правое расположение. |
| signature | int | r | Получает подпись. |
| text_version | short | r/w | Получает или задает версию текста. |
| верх | int | r/w | Получает или задает верхнее расположение. |
| transform_matrix | double | r/w | Получает или задает матрицу преобразования. |
| version | short | r/w | Получает или задает версию инструмента типа. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | r/w | Получает или задает идентификатор класса. |
| warp_class_name | string | r/w | Получает или задает имя класса warp. |
| warp_descriptor_version | int | r/w | Получает и задает версию дескриптора warp. |
| warp_items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Получает или задает элементы искажения. |
| warp_version | short | r/w | Получает или задает версию warp. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: TypeToolInfo6Resource(class_id, warp_class_id) {#TypeToolInfo6Resource_class_id_warp_class_id_1}


```
 TypeToolInfo6Resource(class_id, warp_class_id) 
```

Инициализирует новый экземпляр класса [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | Идентификатор класса. |
| warp_class_id | [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid) | ID класса warp. |

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

