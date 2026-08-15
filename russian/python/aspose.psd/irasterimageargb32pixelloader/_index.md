---
title: "Класс IRasterImageArgb32PixelLoader"
type: docs
weight: 2000
url: /ru/python-net/aspose.psd/irasterimageargb32pixelloader/
---

**Summary:** The raster image 32-bit ARGB pixel loader.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.IRasterImageArgb32PixelLoader

**Inheritance:** IRasterImageRawDataLoader

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| сырые_данные_доступны | bool | r | Получает значение, указывающее, поддерживается ли загрузка сырых данных. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Получает текущие настройки сырых данных. Примечание: при использовании этих настроек данные загружаются без конвертации. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_1) | Частично загружает 32‑битные ARGB‑пиксели (по блокам). |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2) | Загружает необработанные данные. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_1}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Частично загружает 32‑битные ARGB‑пиксели (по блокам).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Частичный загрузчик пикселей. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_2}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Загружает необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружаются необработанные данные. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено преобразование данных. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Загрузчик необработанных данных. |

