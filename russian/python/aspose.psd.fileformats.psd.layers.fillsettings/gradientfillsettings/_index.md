---
title: "Класс GradientFillSettings"
type: docs
weight: 50
url: /ru/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Инициализирует новый экземпляр класса [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/) |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Получает или задает значение, указывающее, следует ли [align with layer]. |
| угол | double | r/w | Получает или задает угол. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает цвет. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Получает или задает цветовые точки. |
| dither | bool | r/w | Получает или задает значение, указывающее, применяется ли дизеринг к этому [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/). |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Тип заливки. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Получает режим для этого градиента.<br/>            Определяет 'Тип градиента' = 'Сплошной/Шум' (0/1). |
| gradient_name | string | r/w | Получает или задает имя градиента. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Получает или задает тип градиента. |
| horizontal_offset | double | r/w | Получает или задает горизонтальное смещение в процентах. |
| интерполяция | short | r/w | Интерполяция. Определяет плавность, когда 'Gradient Type' = 'Solid'. Диапазон значений: 0-4096. |
| reverse | bool | r/w | Получает или задает значение, указывающее, является ли этот [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) обратным. |
| scale | int | r/w | Получает или задает масштаб. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Получает или задает точки прозрачности. |
| vertical_offset | double | r/w | Получает или задает вертикальное смещение в процентах. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Добавляет точку цвета. |
| [add_transparency_point()](#add_transparency_point__2) | Добавляет точку цвета. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Генерирует узлы ресурсов LFX2. |
| [remove_color_point(point)](#remove_color_point_point_4) | Удаляет точку цвета. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Удаляет точку прозрачности. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Инициализирует новый экземпляр класса [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/)

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Добавляет точку цвета.

**Returns**

| Тип | Описание |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Создана точка цвета |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Добавляет точку цвета.

**Returns**

| Тип | Описание |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Создана точка прозрачности |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Генерирует узлы ресурсов LFX2.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Сгенерированный список [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Удаляет точку цвета.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Точка. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Удаляет точку прозрачности.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Точка. |

