---
title: "TiffOptions Класс"
type: docs
weight: 130
url: /ru/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Инициализирует новый экземпляр класса [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). По умолчанию используется порядок байтов little endian. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Инициализирует новый экземпляр класса [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Инициализирует новый экземпляр класса [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Инициализирует новый экземпляр класса [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Получает или задает параметр хранения альфа-канала. Параметры, отличные от [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            используются, когда определено более 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| artist | string | r/w | Получает или задает значение свойства artist. |
| bits_per_pixel | int | r | Получает количество бит на пиксель. |
| bits_per_sample | ushort | r/w | Получает или задает значение свойства bits_per_sample. |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Получает или задает значение, указывающее порядок байтов tiff. |
| color_map | ushort | r/w | Получает или задает карту цветов. |
| compressed_quality | int | r/w | Получает или задает качество сжатого изображения.<br/>            Используется с сжатием Jpeg. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Получает или задает сжатие. |
| copyright | string | r/w | Получает или задает авторские права. |
| date_time | string | r/w | Получает или задает дату и время. |
| default_memory_allocation_limit | int | r/w | Получает или задает предельный объём выделяемой памяти по умолчанию. |
| default_replacement_font | string | r/w | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если шрифт слоя в файле PSD отсутствует в системе).<br/>            Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| document_name | string | r/w | Получает или задает имя документа. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Получает или задает указатель на EXIF IFD. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Получает или задает параметры fax t4. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Получает или задает стандарт файла TIFF. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Получает или задает порядок заполнения битов байта. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, является ли [full frame]. |
| half_tone_hints | ushort | r/w | Получает или задает подсказки полутонов. |
| image_description | string | r/w | Получает или задает описание изображения. |
| image_length | uint | r/w | Получает или задает длину изображения. |
| image_width | uint | r/w | Получает или задает ширину изображения. |
| ink_names | string | r/w | Получает или задает названия чернил. |
| is_extra_samples_present | bool | r | Возвращает значение, указывающее, присутствуют ли дополнительные образцы. |
| is_tiled | bool | r | Возвращает значение, указывающее, разложено ли изображение плитками. |
| is_valid | bool | r | Возвращает значение, указывающее, правильно ли настроены [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Используйте метод Validate, чтобы найти причину сбоя. |
| max_sample_value | ushort | r/w | Получает или задает максимальное значение образца. |
| min_sample_value | ushort | r/w | Получает или задает минимальное значение образца. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Опции многстраничного режима |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Получает или задает ориентацию. |
| page_name | string | r/w | Получает или задает имя страницы. |
| page_number | ushort | r/w | Получает или задает тег номера страницы. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Получает или задает цветовую палитру. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Получает или задает фотометрический параметр. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Получает или задает планарную конфигурацию. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Получает или задает предсказатель для сжатия LZW. |
| предумножить_компоненты | bool | r/w | Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Получает или задает настройки разрешения. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Получает или задает единицу измерения разрешения. |
| rows_per_strip | uint | r/w | Получает или задает количество строк в полосе. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Получает или задает формат образца. |
| samples_per_pixel | ushort | r | Получает количество образцов на пиксель. Чтобы изменить значение этого свойства, используйте сеттер свойства [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Получает или задает производителя сканера. |
| scanner_model | string | r/w | Получает или задает модель сканера. |
| smax_sample_value | uint | r/w | Получает или задает максимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long). |
| smin_sample_value | uint | r/w | Получает или задает минимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (Byte, Short или Long). |
| software_type | string | r/w | Получает или задает тип программного обеспечения. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Получает или задает источник, в котором создаётся изображение. |
| strip_byte_counts | uint | r/w | Получает или задает количество байтов полосы. |
| strip_offsets | uint | r/w | Получает или задает смещения полосы. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Получает или задает общее указание типа данных, содержащихся в этом подфайле. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Получает или задает теги. |
| target_printer | string | r/w | Получает или задает целевой принтер. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Получает или задает пороговое значение. |
| tile_byte_counts | uint | r/w | Получает или задает количество байтов плитки. |
| tile_length | uint | r/w | Получает ot задает длину плитки. |
| tile_offsets | uint | r/w | Получает или задает смещения плитки. |
| tile_width | uint | r/w | Получает ot задает ширину плитки. |
| total_pages | ushort | r | Получает общее количество страниц. |
| valid_tag_count | int | r | Получает количество действительных тегов. Это не общее количество тегов, а число тегов, которые могут быть сохранены. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Получает или задает параметры векторной растеризации. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Получает или задает контейнер метаданных XMP. |
| xp_author | string | r/w | Получает или задает автора изображения, который используется Проводником Windows. |
| xp_comment | string | r/w | Получает или задает комментарий к изображению, который используется Проводником Windows. |
| xp_keywords | string | r/w | Получает или задает тему изображения, который используется Проводником Windows. |
| xp_subject | string | r/w | Получает или задает информацию об изображении, которая используется Проводником Windows. |
| xp_title | string | r/w | Получает или задает информацию об изображении, которая используется Проводником Windows. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает позицию по оси X. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси X. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает коэффициенты YCbCr. |
| y_cb_cr_subsampling | ushort | r/w | Получает или задает коэффициенты субдискретизации для фотометрии YCbCr. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает позицию по оси Y. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Получает или задает разрешение по оси Y. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Добавляет новый тег. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Добавляет теги. |
| [clone()](#clone__3) | Клонирует этот экземпляр. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Получает экземпляр тега по типу. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Получает количество действительных тегов. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Определяет, присутствует ли тег в параметрах или нет. |
| [remove_tag(tag)](#remove_tag_tag_7) | Удаляет тег. |
| validate() | Проверяет, имеет ли набор параметров допустимую комбинацию тегов. |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Инициализирует новый экземпляр класса [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). По умолчанию используется порядок байтов little endian.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Ожидаемый формат TIFF‑файла. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Инициализирует новый экземпляр класса [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Ожидаемый формат TIFF‑файла. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | Порядок байтов формата файла TIFF, который следует использовать. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Инициализирует новый экземпляр класса [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | Параметры, из которых копировать. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Инициализирует новый экземпляр класса [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Теги для инициализации параметров. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Добавляет новый тег.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Тег для добавления. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Добавляет теги.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Теги для добавления. |

### Method: clone() {#clone__3}


```
 clone() 
```

Клонирует этот экземпляр.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Возвращает поверхностную копию этого экземпляра |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Получает экземпляр тега по типу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Ключ тега. |

**Returns**

| Тип | Описание |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Экземпляр тега, если он существует, иначе null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Получает количество действительных тегов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Теги для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Количество действительных тегов. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Определяет, присутствует ли тег в параметрах или нет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Идентификатор тега для проверки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если тег присутствует; иначе <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Удаляет тег.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Тег для удаления. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | true, если успешно удалён |


