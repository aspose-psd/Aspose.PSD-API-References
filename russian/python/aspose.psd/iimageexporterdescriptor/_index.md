---
title: "Класс IImageExporterDescriptor"
type: docs
weight: 1800
url: /ru/python-net/aspose.psd/iimageexporterdescriptor/
---

**Summary:** Represents the image exporter descriptor. The exporter descriptor is used to overcome the necessity to contain each exporter instance<br/>            in memory and multithreading issues.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IImageExporterDescriptor

**Inheritance:** IImageDescriptor

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| supported_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Получает поддерживаемый формат. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [can_export(image, options_base)](#can_export_image_options_base_1) | Определяет, может ли экспортёр изображений экспортировать указанное изображение в заданный формат изображения, указанный в параметрах сохранения. |
| [create_instance()](#create_instance__2) | Создаёт новый экземпляр экспортёра. |


### Method: can_export(image, options_base) {#can_export_image_options_base_1}


```
 can_export(image, options_base) 
```

Определяет, может ли экспортёр изображений экспортировать указанное изображение в заданный формат изображения, указанный в параметрах сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение для экспорта. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | База параметров. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>True</c> если экспортёр, созданный этим дескриптором, может экспортировать указанное изображение в указанный формат файла; иначе <c>false</c>. |


### Method: create_instance() {#create_instance__2}


```
 create_instance() 
```

Создаёт новый экземпляр экспортёра.

**Returns**

| Тип | Описание |
| :- | :- |
| [IImageExporter](/psd/python-net/aspose.psd/iimageexporter) | Новый экземпляр экспортера. |


