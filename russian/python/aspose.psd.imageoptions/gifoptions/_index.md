---
title: "Класс GifOptions"
type: docs
weight: 30
url: /ru/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Инициализирует новый экземпляр класса [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Инициализирует новый экземпляр класса [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| background_color_index | байт | r/w | Получает или задает индекс фонового цвета GIF. |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| color_resolution | байт | r/w | Получает или задает разрешение цвета GIF. |
| default_replacement_font | string | r/w | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если шрифт слоя в файле PSD отсутствует в системе).<br/>            Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| do_palette_correction | bool | r/w | Получает или задает значение, указывающее, применяется ли коррекция палитры. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, является ли [full frame]. |
| has_trailer | bool | r/w | Получает или задает значение, указывающее, имеет ли GIF трейлер. |
| interlaced | bool | r/w | True, если изображение должно быть чересстрочным. |
| is_palette_sorted | bool | r/w | Получает или задает значение, указывающее, отсортированы ли элементы палитры. |
| max_diff | int | r/w | Получает или задает максимальное допустимое различие пикселей. Если значение больше нуля, будет использовано сжатие с потерями.<br/>            Рекомендуемое значение для оптимального сжатия с потерями — 80. 30 означает очень легкое сжатие, 200 — сильное.<br/>            Оно работает лучше всего, когда вводится небольшая потеря, и из‑за ограничений алгоритма сжатия очень высокие уровни потерь не дают значительного выигрыша.<br/>            Диапазон допустимых значений: [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Опции многстраничного режима |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Получает или задает цветовую палитру. |
| pixel_aspect_ratio | байт | r/w | Получает или задает соотношение сторон пикселей GIF. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Получает или задает настройки разрешения. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Получает или задает источник, в котором создаётся изображение. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Получает или задает параметры векторной растеризации. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Получает или задает контейнер метаданных XMP. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Клонирует этот экземпляр. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Инициализирует новый экземпляр класса [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Инициализирует новый экземпляр класса [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | Параметры GIF. |

### Method: clone() {#clone__1}


```
 clone() 
```

Клонирует этот экземпляр.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Возвращает поверхностную копию этого экземпляра |


