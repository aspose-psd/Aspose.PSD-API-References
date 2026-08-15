---
title: "AiImage Класс"
type: docs
weight: 40
url: /ru/python-net/aspose.psd.fileformats.ai/aiimage/
---

**Summary:** The Adobe Illustrator (AI)  Image.

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiImage

**Inheritance:** IObjectWithBounds, Image

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [AiImage()](#AiImage__1) | Инициализирует новый экземпляр класса AiImage |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| active_page_index | int | r/w | Получает или задает индекс активной страницы. |
| auto_adjust_palette | bool | r/w | Получает или задаёт значение, указывающее, следует ли автоматически корректировать палитру. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задаёт значение фонового цвета. |
| bits_per_pixel | int | r | Получает количество бит на пиксель изображения. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Получает границы изображения. |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Получает контейнер [Image](/psd/python-net/aspose.psd/image/). |
| data_section | [AiDataSection](/psd/python-net/aspose.psd.fileformats.ai/aidatasection) | r | Получает раздел данных. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Получает поток данных объекта. |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Получает значение формата файла. |
| finalize_section | [AiFinalizeSection](/psd/python-net/aspose.psd.fileformats.ai/aifinalizesection) | r | Получает раздел завершения. |
| имеет_цвет_фона | bool | r/w | Получает или задает значение, указывающее, имеет ли изображение фоновой цвет. |
| header | [AiHeader](/psd/python-net/aspose.psd.fileformats.ai/aiheader) | r | Получает заголовок. |
| height | int | r | Получает высоту изображения. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Получает или задает монитор прерываний. |
| закешировано | bool | r | Получает значение, указывающее, кэшированы ли данные объекта в данный момент и не требуется чтение данных. |
| layers | [AiLayerSection[]](/psd/python-net/aspose.psd.fileformats.ai/ailayersection) | r | Получает разделы слоёв. |
| page_count | int | r | Количество страниц.<br/>            Для изображений старого формата AI всегда равно 0. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| setup_section | [AiSetupSection](/psd/python-net/aspose.psd.fileformats.ai/aisetupsection) | r | Получает раздел настройки. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Получает размер изображения. |
| use_palette | bool | r | Получает значение, указывающее, используется ли палитра изображения. |
| version | [AiFormatVersion](/psd/python-net/aspose.psd.fileformats.ai/aiformatversion) | r | Получает версию формата Adobe Illustrator. |
| width | int | r | Получает ширину изображения. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r | Получает или задает XMP‑метаданные. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_layer(layer)](#add_layer_layer_1) | Добавляет раздел слоя AI. |
| cache_data() | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) не будет выполнена. |
| [can_load(file_path)](#can_load_file_path_2) | Определяет, может ли изображение быть загружено из указанного пути к файлу. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_3) | Определяет, может ли изображение быть загружено из указанного пути к файлу и, при необходимости, с использованием указанных параметров открытия. |
| [can_load(stream)](#can_load_stream_4) | Определяет, может ли изображение быть загружено из указанного потока. |
| [can_load(stream, load_options)](#can_load_stream_load_options_5) | Определяет, может ли изображение быть загружено из указанного потока и, при необходимости, с использованием указанного <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_6) | Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения. |
| [create(image_options, width, height)](#create_image_options_width_height_7) | Создаёт новое изображение с использованием указанных параметров создания. |
| [get_default_options(args)](#get_default_options_args_8) | Получает параметры по умолчанию. |
| [get_file_format(file_path)](#get_file_format_file_path_9) | Получает формат файла. |
| [get_file_format(stream)](#get_file_format_stream_10) | Получает формат файла. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_11) | Получает прямоугольник, который вписывается в текущее изображение. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_12) | Получает прямоугольник, который вписывается в текущее изображение. |
| [get_original_options()](#get_original_options__13) | Получает параметры на основе настроек исходного файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров исходного изображения без изменений.<br/>            Например, если мы загружаем черно-белое PNG‑изображение с 1 битом на пиксель, а затем сохраняем его с помощью<br/>            метода [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/), будет получено PNG‑изображение с 8 битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            методу [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) в качестве второго параметра. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_14) | Получает пропорциональную высоту. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_15) | Получает пропорциональную ширину. |
| [load(file_path)](#load_file_path_16) | Загружает новое изображение из указанного файла. |
| [load(file_path, load_options)](#load_file_path_load_options_17) | Загружает новое изображение из указанного файла. |
| [load(stream)](#load_stream_18) | Загружает новое изображение из указанного потока. |
| [load(stream, load_options)](#load_stream_load_options_19) | Загружает новое изображение из указанного потока. |
| [resize(new_width, new_height)](#resize_new_width_new_height_20) | Изменяет размер изображения. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_21) | Изменяет размер изображения. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_22) | Изменяет размер изображения. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_23) | Пропорционально изменяет высоту. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_24) | Пропорционально изменяет высоту. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_25) | Пропорционально изменяет высоту. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_26) | Пропорционально изменяет ширину. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_27) | Пропорционально изменяет ширину. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_28) | Пропорционально изменяет ширину. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_29) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| save() | Сохраняет данные изображения в базовый поток. |
| [save(file_path)](#save_file_path_30) | Сохраняет данные объекта в указанное расположение файла. |
| [save(file_path, options)](#save_file_path_options_31) | Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_32) | Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения. |
| [save(file_path, over_write)](#save_file_path_over_write_33) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_34) | Сохраняет данные объекта в указанный поток. |
| [save(stream, options_base)](#save_stream_options_base_35) | Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_36) | Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_37) | Устанавливает палитру изображения. |


### Constructor: AiImage() {#AiImage__1}


```
 AiImage() 
```

Инициализирует новый экземпляр класса AiImage

### Method: add_layer(layer) {#add_layer_layer_1}


```
 add_layer(layer) 
```

Добавляет раздел слоя AI.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [AiLayerSection](/psd/python-net/aspose.psd.fileformats.ai/ailayersection) | Раздел слоя AI. |

### Method: can_load(file_path)  [static] {#can_load_file_path_2}


```
 can_load(file_path) 
```

Определяет, может ли изображение быть загружено из указанного пути к файлу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного файла; в противном случае, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_3}


```
 can_load(file_path, load_options) 
```

Определяет, может ли изображение быть загружено из указанного пути к файлу и, при необходимости, с использованием указанных параметров открытия.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного файла; в противном случае, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_4}


```
 can_load(stream) 
```

Определяет, может ли изображение быть загружено из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного потока; в противном случае, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_5}


```
 can_load(stream, load_options) 
```

Определяет, может ли изображение быть загружено из указанного потока и, при необходимости, с использованием указанного <paramref name="loadOptions" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть загружено из указанного потока; в противном случае, <c>false</c>. |


### Method: can_save(options) {#can_save_options_6}


```
 can_save(options) 
```

Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры сохранения для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если изображение может быть сохранено в указанный формат файла, представленный переданными параметрами сохранения; в противном случае, <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

Создаёт новое изображение с использованием указанных параметров создания.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры изображения. |
| width | int | Ширина. |
| height | int | Высота. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Новое созданное изображение. |


### Method: get_default_options(args) {#get_default_options_args_8}


```
 get_default_options(args) 
```

Получает параметры по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| args | object | Аргументы. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры по умолчанию |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_9}


```
 get_file_format(file_path) 
```

Получает формат файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Определённый формат файла. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_10}


```
 get_file_format(stream) 
```

Получает формат файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Определённый формат файла. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_11}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Получает прямоугольник, который вписывается в текущее изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, для которого получить подходящий прямоугольник. |
| pixels | int | 32‑битные ARGB‑пиксели. |
| width | int | Ширина объекта. |
| height | int | Высота объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Подходящий прямоугольник или исключение, если подходящий прямоугольник не найден. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_12}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Получает прямоугольник, который вписывается в текущее изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, для которого получить подходящий прямоугольник. |
| width | int | Ширина объекта. |
| height | int | Высота объекта. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Подходящий прямоугольник или исключение, если подходящий прямоугольник не найден. |


### Method: get_original_options() {#get_original_options__13}


```
 get_original_options() 
```

Получает параметры на основе настроек исходного файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров исходного изображения без изменений.<br/>            Например, если мы загружаем черно-белое PNG‑изображение с 1 битом на пиксель, а затем сохраняем его с помощью<br/>            метода [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/), будет получено PNG‑изображение с 8 битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            методу [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) в качестве второго параметра.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры, основанные на настройках оригинального файла. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_14}


```
 get_proportional_height(width, height, new_width) 
```

Получает пропорциональную высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина. |
| height | int | Высота. |
| new_width | int | Новая ширина. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Пропорциональная высота. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_15}


```
 get_proportional_width(width, height, new_height) 
```

Получает пропорциональную ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина. |
| height | int | Высота. |
| new_height | int | Новая высота. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Пропорциональная ширина. |


### Method: load(file_path)  [static] {#load_file_path_16}


```
 load(file_path) 
```

Загружает новое изображение из указанного файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, из которого загружать изображение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Загруженное изображение. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_17}


```
 load(file_path, load_options) 
```

Загружает новое изображение из указанного файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу, из которого загружать изображение. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Загруженное изображение. |


### Method: load(stream)  [static] {#load_stream_18}


```
 load(stream) 
```

Загружает новое изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать изображение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Загруженное изображение. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_19}


```
 load(stream, load_options) 
```

Загружает новое изображение из указанного потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток, из которого загружать изображение. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры загрузки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Загруженное изображение. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_20}


```
 resize(new_width, new_height) 
```

Изменяет размер изображения. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_21}


```
 resize(new_width, new_height, resize_type) 
```

Изменяет размер изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Тип изменения размера. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_22}


```
 resize(new_width, new_height, settings) 
```

Изменяет размер изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Настройки изменения размера. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_23}


```
 resize_height_proportionally(new_height) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_24}


```
 resize_height_proportionally(new_height, resize_type) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Тип изменения размера. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_25}


```
 resize_height_proportionally(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Настройки изменения размера изображения. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_26}


```
 resize_width_proportionally(new_width) 
```

Пропорционально изменяет ширину. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_27}


```
 resize_width_proportionally(new_width, resize_type) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Тип изменения размера. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_28}


```
 resize_width_proportionally(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Настройки изменения размера изображения. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_29}


```
 rotate_flip(rotate_flip_type) 
```

Поворачивает, отражает или одновременно поворачивает и отражает изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Тип вращения и отражения. |

### Method: save(file_path) {#save_file_path_30}


```
 save(file_path) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для сохранения данных объекта. |

### Method: save(file_path, options) {#save_file_path_options_31}


```
 save(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_32}


```
 save(file_path, options, bounds_rectangle) 
```

Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### Method: save(file_path, over_write) {#save_file_path_over_write_33}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для сохранения данных объекта. |
| over_write | bool | если установить в <c>true</c>, содержимое файла будет перезаписано, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_34}


```
 save(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для сохранения данных объекта. |

### Method: save(stream, options_base) {#save_stream_options_base_35}


```
 save(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для сохранения данных изображения. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры сохранения. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_36}


```
 save(stream, options_base, bounds_rectangle) 
```

Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для сохранения данных изображения. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры сохранения. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_37}


```
 set_palette(palette, update_colors) 
```

Устанавливает палитру изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Палитра для установки. |
| update_colors | bool | если установить значение <c>true</c>, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся без изменений. Обратите внимание, что неизменённые индексы могут вызвать сбой изображения при загрузке, если у некоторых индексов нет соответствующих записей в палитре. |

