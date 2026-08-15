---
title: "Класс GdFlResource"
type: docs
weight: 330
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Инициализирует новый экземпляр класса GdFlResource |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента. |
| align_with_layer | bool | r/w | Получает или задает значение, указывающее, следует ли [align with layer]. |
| угол | double | r/w | Получает или задает угол. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает цвет RGB. |
| color_model | string | r/w | Модель цвета - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Получает точки цвета. |
| dither | bool | r/w | Получает или задает значение, указывающее, является ли этот [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) dither. |
| gradient_interval | double | r/w | Получает или задает интервал градиента. |
| gradient_mode | string | r/w | Режим для этого градиента.<br/>            Определяет 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs". |
| gradient_name | string | r/w | Получает или задает имя градиента. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Получает или задает тип градиента. |
| horizontal_offset | double | r/w | Получает или задает горизонтальное смещение. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Максимальный цвет PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Минимальный цвет PixelDataFormat. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| reverse | bool | r/w | Получает или задает значение, указывающее, является ли этот [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) reverse. |
| rnd_number_seed | int | r/w | Сид случайного числа, используемый для генерации цветов шумового градиента. |
| roughness | int | r/w | Коэффициент шероховатости. |
| scale | int | r/w | Получает или задает масштаб. |
| show_transparency | bool | r/w | Флаг для отображения прозрачности. |
| signature | int | r | Получает подпись. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Получает точки прозрачности. |
| use_vector_color | bool | r/w | Флаг для использования векторного цвета. |
| vertical_offset | double | r/w | Получает или задает вертикальное смещение. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Инициализирует новый экземпляр класса GdFlResource

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

