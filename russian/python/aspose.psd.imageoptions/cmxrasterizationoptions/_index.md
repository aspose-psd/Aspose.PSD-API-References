---
title: "Класс CmxRasterizationOptions"
type: docs
weight: 20
url: /ru/python-net/aspose.psd.imageoptions/cmxrasterizationoptions/
---

**Summary:** the CMX exporter options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.CmxRasterizationOptions

**Inheritance:** VectorRasterizationOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CmxRasterizationOptions()](#CmxRasterizationOptions__1) | Инициализирует новый экземпляр класса CmxRasterizationOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает цвет фона. |
| border_x | float | r/w | Получает или задает границу X. |
| border_y | float | r/w | Получает или задает границу Y. |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| center_drawing | bool | r/w | Получает или задает значение, указывающее, следует ли центрировать рисунок. |
| default_replacement_font | string | r/w | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если шрифт слоя в файле PSD отсутствует в системе).<br/>            Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| draw_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задает цвет переднего плана. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, является ли [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Опции многстраничного режима |
| page_height | float | r/w | Получает или задает высоту страницы. |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Получает или задает размер страницы. |
| page_width | float | r/w | Получает или задает ширину страницы. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Получает или задает цветовую палитру. |
| positioning | [PositioningTypes](/psd/python-net/aspose.psd.imageoptions/positioningtypes) | r/w | Получает или задает позиционирование. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Получает или задает настройки разрешения. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Получает или задает режим сглаживания. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Получает или задает источник, в котором создаётся изображение. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Получает или задает подсказку рендеринга текста. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Получает или задает параметры векторной растеризации. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Получает или задает контейнер метаданных XMP. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Клонирует этот экземпляр. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Копирует в. |


### Constructor: CmxRasterizationOptions() {#CmxRasterizationOptions__1}


```
 CmxRasterizationOptions() 
```

Инициализирует новый экземпляр класса CmxRasterizationOptions

### Method: clone() {#clone__1}


```
 clone() 
```

Клонирует этот экземпляр.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Возвращает поверхностную копию этого экземпляра |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Копирует в.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | Параметры векторного растеризования. |

