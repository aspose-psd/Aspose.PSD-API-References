---
title: "Класс Jpeg2000Options"
type: docs
weight: 50
url: /ru/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Инициализирует новый экземпляр класса [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Инициализирует новый экземпляр класса [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | Получает или задает кодек JPEG2000 |
| comments | string | r/w | Получает или задает маркеры комментариев Jpeg. |
| compression_ratios | int | r/w | Получает или задает массив коэффициентов сжатия.<br/>            Разные коэффициенты сжатия для последовательных слоёв.<br/>            Указанная для каждого уровня качества ставка является желаемым<br/>            коэффициентом сжатия.<br/>            Требуются уменьшающиеся коэффициенты. |
| default_replacement_font | string | r/w | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если шрифт слоя в файле PSD отсутствует в системе).<br/>            Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, является ли [full frame]. |
| irreversible | bool | r/w | Получает или задает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или использовать без потерь DWT 5-3 сжатие (по умолчанию). |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Опции многстраничного режима |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Получает или задает цветовую палитру. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Получает или задает настройки разрешения. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Получает или задает источник, в котором создаётся изображение. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Получает или задает параметры векторной растеризации. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Получает или задает контейнер метаданных XMP. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Клонирует этот экземпляр. |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Инициализирует новый экземпляр класса [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Инициализирует новый экземпляр класса [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | Параметры формата файла Jpeg2000, из которых копировать настройки. |

### Method: clone() {#clone__1}


```
 clone() 
```

Клонирует этот экземпляр.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Возвращает поверхностную копию этого экземпляра |


