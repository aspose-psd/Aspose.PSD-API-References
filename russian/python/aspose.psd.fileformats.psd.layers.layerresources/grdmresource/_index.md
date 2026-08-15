---
title: "Класс GrdmResource"
type: docs
weight: 340
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Инициализирует новый экземпляр класса [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| color_model | short | r/w | Цветовая модель.<br/>            Когда 'Gradient type' = 'Noise', мы можем установить 'Color Model' в RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Получает или задает цветовые точки. |
| dither | bool | r/w | Градиент дизерован. |
| expansion_count | short | r/w | Количество расширений ( = 2 для Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Режим для этого градиента<br/>            Определяет 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Имя градиента: строка Unicode, с заполнением. |
| интерполяция | short | r/w | Интерполяция. Определяет плавность, когда 'Gradient Type' = 'Solid' (GradientMode = 0). |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Максимальный цвет формата PixelDataFormat.Rgba64Bpp.<br/>            Цвет имеет каналы ARGB, каждый канал 16 бит. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Минимальный цвет формата PixelDataFormat.Rgba64Bpp.<br/>            Цвет имеет каналы ARGB, каждый канал 16 бит. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| reverse | bool | r/w | Градиент инвертирован. |
| rnd_number_seed | int | r/w | Сид случайного числа, используемый для генерации цветов шумового градиента. |
| roughness | int | r/w | Коэффициент шероховатости<br/>            Когда 'Gradient type' = 'Noise', мы можем установить 'Roughness' (0 - 2048). |
| show_transparency | short | r/w | Флаг отображения прозрачности<br/>            Когда 'Gradient type' = 'Noise', мы можем установить 'Add transparency' в true. |
| signature | int | r | Получает подпись. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Получает или задает точки прозрачности. |
| use_vector_color | short | r/w | Флаг для использования векторного цвета. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет данные ресурса в указанный контейнер потока. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Инициализирует новый экземпляр класса [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| psd_version | int | Версия ресурса в формате psd. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет данные ресурса в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |
| psd_version | int | Версия PSD. |

