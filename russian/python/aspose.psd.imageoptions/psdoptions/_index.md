---
title: "Класс PsdOptions"
type: docs
weight: 100
url: /ru/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Инициализирует новый экземпляр класса [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(image)](#PsdOptions_image_2) | Инициализирует новый экземпляр класса [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_3) | Инициализирует новый экземпляр класса [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Получает или задает цвет фона.<br/>            Он виден под прозрачными объектами. |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| channel_bits_count | short | r/w | Получает или задает количество бит на цветовой канал. |
| channels_count | short | r/w | Получает или задает количество цветовых каналов. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | Получает или задает режим цвета PSD. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | Получает или задает метод сжатия PSD. |
| default_replacement_font | string | r/w | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если шрифт слоя в файле PSD отсутствует в системе).<br/>            Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| full_frame | bool | r/w | Получает или задает значение, указывающее, является ли [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Опции многстраничного режима |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Получает или задает цветовую палитру. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Получает или задает версию формата файла. Это может быть PSD или PSB. |
| refresh_image_preview_data | bool | r/w | Получает или задает значение, указывающее, включено ли [refresh image preview data] - параметр, используемый для повышения совместимости с другими просмотрщиками PSD‑изображений.<br/>            Обратите внимание, что отрисовка текстовых слоёв в окончательном макете не поддерживается на платформе Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | Получает или задает значение, указывающее, следует ли - удалить глобальный ресурс текстового движка - используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда после обработки их нельзя открыть в Adobe Photoshop (в основном из‑за отсутствующих шрифтов в текстовых слоях).<br/>            После использования этой опции пользователю необходимо выполнить в открытом в Photoshop файле следующее: Меню "Text" -&gt; "Process absent fonts". После этой операции весь текст появится снова.<br/>            Обратите внимание, что эта операция может вызвать некоторые изменения окончательного макета. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Получает или задает настройки разрешения. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | Получает или задает ресурсы PSD. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Получает или задает источник, в котором создаётся изображение. |
| update_metadata | bool | r/w | Получает или задает значение, указывающее, включено ли [update metadata].<br/>            Если значение истинно, метаданные будут обновлены при сохранении изображения. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Получает или задает параметры векторной растеризации. |
| version | int | r/w | Получает или задает версию файла PSD. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Получить или задать контейнер данных XMP |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Клонирует этот экземпляр. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Инициализирует новый экземпляр класса [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Инициализирует новый экземпляр класса [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | Изображение. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Инициализирует новый экземпляр класса [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | Параметры. |

### Method: clone() {#clone__1}


```
 clone() 
```

Клонирует этот экземпляр.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Возвращает поверхностную копию этого экземпляра |


