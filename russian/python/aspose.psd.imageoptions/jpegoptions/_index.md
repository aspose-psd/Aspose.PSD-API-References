---
title: "Класс JpegOptions"
type: docs
weight: 60
url: /ru/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Инициализирует новый экземпляр класса [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Инициализирует новый экземпляр класса [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| bits_per_channel | байт | r/w | Получает или задает количество бит на канал для без потерь jpeg‑изображения. Сейчас поддерживается от 2 до 8 бит на канал. |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Целевой профиль цвета CMYK для изображений CMYK jpeg. Используется для сохранения изображений. Должен использоваться вместе с RGBColorProfile для корректного преобразования цветов. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Получает или задает тип цвета для изображения jpeg. |
| комментарий | string | r/w | Получает или задает комментарий файла jpeg. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | Получает или задает тип сжатия. |
| default_memory_allocation_limit | int | r/w | Получает или задает предельный объём выделяемой памяти по умолчанию. |
| default_replacement_font | string | r/w | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если шрифт слоя в файле PSD отсутствует в системе).<br/>            Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | Получить или задать контейнер данных exif |
| full_frame | bool | r/w | Получает или задает значение, указывающее, является ли [full frame]. |
| horizontal_sampling | байт | r/w | Получает или задает горизонтальные субдискретизации для каждого компонента. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | Получает или задает jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Получает или задает границу различий JPEG-LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Получает или задает режим чередования JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Получает или задает предустановленные параметры JPEG-LS. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Опции многстраничного режима |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Получает или задает цветовую палитру. |
| preblend_alpha_if_present | bool | r/w | Получает или задает значение, указывающее, следует ли смешивать компоненты красного, зелёного и синего с цветом фона, если присутствует альфа‑канал. |
| quality | int | r/w | Получает или задает качество изображения. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | Получает или задает параметры оптимизатора RD. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Получает или задает настройки разрешения. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | Получает или задает единицу измерения разрешения. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Целевой профиль цвета RGB для изображений CMYK jpeg. Используется для сохранения изображений. Должен использоваться вместе с CMYKColorProfile для корректного преобразования цветов. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | Получает или задает режим округления образца для приведения 8‑битного значения к n‑битному. <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | Масштабированное качество. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Получает или задает источник, в котором создаётся изображение. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Получает или задает параметры векторной растеризации. |
| vertical_sampling | байт | r/w | Получает или задает вертикальные субдискретизации для каждого компонента. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Получает или задает контейнер метаданных XMP. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Клонирует этот экземпляр. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Инициализирует новый экземпляр класса [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Инициализирует новый экземпляр класса [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | Параметры JPEG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Клонирует этот экземпляр.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Возвращает поверхностную копию этого экземпляра |


