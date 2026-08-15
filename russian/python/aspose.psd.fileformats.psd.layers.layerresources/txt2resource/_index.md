---
title: "Класс Txt2Resource"
type: docs
weight: 970
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Summary:** Txt2 resource class

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Txt2Resource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Txt2Resource()](#Txt2Resource__1) | Инициализирует новый экземпляр класса Txt2Resource |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| данные | байт | r/w | Получает или задает данные. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_text_record(text, bounds)](#add_text_record_text_bounds_1) | Добавляет текстовую запись в Resource и возвращает идентификатор текстовой записи. |
| [get_text_data()](#get_text_data__2) | Получает текстовую запись из данных ресурса. |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_3) | Сохраняет указанный контейнер потока. |


### Constructor: Txt2Resource() {#Txt2Resource__1}


```
 Txt2Resource() 
```

Инициализирует новый экземпляр класса Txt2Resource

### Method: add_text_record(text, bounds) {#add_text_record_text_bounds_1}


```
 add_text_record(text, bounds) 
```

Добавляет текстовую запись в Resource и возвращает идентификатор текстовой записи.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Текст записи. |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Границы. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Возвращает идентификатор текстовой записи для ресурса |


### Method: get_text_data() {#get_text_data__2}


```
 get_text_data() 
```

Получает текстовую запись из данных ресурса.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Массив текстовых записей |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_3}


```
 save(stream_container, psd_version) 
```

Сохраняет указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |
| psd_version | int | Версия PSD. |

