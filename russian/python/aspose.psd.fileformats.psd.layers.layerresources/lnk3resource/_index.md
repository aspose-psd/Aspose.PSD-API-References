---
title: "Класс Lnk3Resource"
type: docs
weight: 580
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/
---

**Summary:** Defines the class which contains information about an embedded file in the PSD format 32 bit per channel image.<br/>            The link resource may contain several [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) instances which can be accessed by indexer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.Lnk3Resource

**Inheritance:** Lnk2Resource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Lnk3Resource()](#Lnk3Resource__1) | Инициализирует новый экземпляр класса [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| data_source_count | int | r | Получает количество источников данных ссылок, доступных через индексатор. |
| is_empty | bool | r | Получает значение, указывающее, пустой ли этот экземпляр ресурса ссылки. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину глобального ресурса ссылки PSD в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет данные блока ресурсов. |


### Constructor: Lnk3Resource() {#Lnk3Resource__1}


```
 Lnk3Resource() 
```

Инициализирует новый экземпляр класса [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/)

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет данные блока ресурсов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

