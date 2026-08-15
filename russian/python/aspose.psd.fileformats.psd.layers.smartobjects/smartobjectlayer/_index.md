---
title: "Класс SmartObjectLayer"
type: docs
weight: 10
url: /ru/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---

**Summary:** Defines the SmartObjectLayer class that contains embedded in the PSD file or linked smart object in the external file.<br/>            With Smart Objects, you can:<br/>            Perform nondestructive transforms. You can scale, rotate, skew, distort, perspective transform, or warp a layer<br/>            without losing original image data or quality because the transforms don�t affect the original data.<br/>            Work with vector data, such as vector artwork from Illustrator, that otherwise would be rasterized.<br/>            Perform nondestructive filtering. You can edit filters applied to Smart Objects at any time.<br/>            Edit one Smart Object and automatically update all its linked instances.<br/>            Apply a layer mask that�s either linked or unlinked to the Smart Object layer.<br/>            Try various designs with low-resolution placeholder images that you later replace with final versions.<br/>            In Adobe� Photoshop�, you can embed the contents of an image into a PSD document.<br/>            More information is here: <see href="https://helpx.adobe.com/photoshop/using/create-smart-objects.html" /><br/>            A layer with an embedded smart object contains placed (PlLd) and SoLd resources with smart object properties.<br/>            The PlLd resource can be alone for PSD versions older then 10.<br/>            These resources contain UniqueId of the LiFdDataSource in the global Lnk2Resource with the embedded filename<br/>            and other parameters, including the embedded file contents in the original format as a byte array.

**Module:** [aspose.psd.fileformats.psd.layers.smartobjects](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Layer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [SmartObjectLayer(stream)](#SmartObjectLayer_stream_1) | Инициализирует новый экземпляр класса [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r |  |
| LAYER_HEADER_SIZE [static] | int | r |  |
| auto_adjust_palette | bool | r/w |  |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| bits_per_pixel | int | r |  |
| blend_clipped_elements | bool | r/w |  |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w |    |
| blend_mode_signature | int | r |  |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r |    |
| bottom | int | r/w |  |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Получает границы объекта. |
| buffer_size_hint | int | r/w |  |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w |    |
| channels_count | ushort | r |  |
| clipping | байт | r/w |  |
| container | [Image](/psd/python-net/aspose.psd/image) | r |    |
| content_type | [SmartObjectType](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjecttype) | r | Получает тип содержимого слоя умного объекта.<br/>            Встроенное содержимое умного объекта представляет собой встроенный необработанный файл изображения: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifdddatasource/).<br/>            Связанное содержимое умного объекта представляет собой необработанное содержимое связанного файла изображения, если оно доступно: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            Мы не поддерживаем загрузку из Adobe� Photoshop� �� Graphics Library, когда [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) равно true.<br/>            Для обычных файлов‑ссылок сначала используется [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) для поиска файла относительно<br/>            пути исходного изображения [None](/psd/python-net/aspose.psd/datastreamsupporter/),<br/>            если он недоступен, проверяется [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/),<br/>            если и это не удалось, ищется файл‑ссылка в том же каталоге, где находится наше изображение: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents | byte | r/w | Получает или задает содержимое слоя умного объекта.<br/>            Встроенное содержимое умного объекта представляет собой встроенный необработанный файл изображения: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifdddatasource/) и его свойства.<br/>            Связанное содержимое умного объекта представляет собой необработанное содержимое связанного файла изображения, если оно доступно, и его свойства: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            Мы не поддерживаем загрузку из Adobe� Photoshop� �� Graphics Library, когда [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) равно true.<br/>            Для обычных файлов‑ссылок сначала используется [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) для поиска файла относительно<br/>            пути исходного изображения [None](/psd/python-net/aspose.psd/datastreamsupporter/),<br/>            если он недоступен, проверяется [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/),<br/>            если и это не удалось, ищется файл‑ссылка в том же каталоге, где находится наше изображение: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Получает или задает границы содержимого умного объекта. |
| contents_source | [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | r/w | Получает или задает источник содержимого умного объекта. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r |    |
| display_name | string | r/w |  |
| освобождено | bool | r |  |
| дополнительная_длина | int | r |  |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r |    |
| непрозрачность_заполнения | int | r/w |  |
| заполнитель | байт | r/w |  |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w |    |
| имеет_alpha | bool | r |  |
| имеет_цвет_фона | bool | r/w |  |
| имеет_прозрачный_цвет | bool | r/w |  |
| height | int | r | Получает высоту объекта. |
| горизонтальное_разрешение | double | r/w |  |
| непрозрачность_изображения | float | r |  |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w |    |
| закешировано | bool | r |  |
| сырые_данные_доступны | bool | r | Получает значение, указывающее, поддерживается ли загрузка сырых данных. |
| видим | bool | r/w |  |
| видим_в_группе | bool | r |  |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w |    |
| дата_и_время_создания_слоя | datetime | r/w |  |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w |    |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w |    |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r |    |
| слева | int | r/w |  |
| длина | int | r |  |
| name | string | r/w | Получает или задает имя текстового слоя. |
| opacity | байт | r/w |  |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w |    |
| предумножить_компоненты | bool | r/w |  |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w |    |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r |    |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Получает текущие настройки сырых данных. Примечание: при использовании этих настроек данные загружаются без конвертации. |
| индекс_резервного_варианта | int | r/w |  |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w |    |
| размер_строки_сырых | int | r |  |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w |    |
| справа | int | r/w |  |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w |    |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Получает размер объекта. |
| smart_filters | [SmartFilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilters/) | r | Получает умные фильтры. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Получает поставщика смарт‑объекта. |
| верх | int | r/w |  |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| update_xmp_data | bool | r/w |  |
| use_palette | bool | r |  |
| use_raw_data | bool | r/w |  |
| vertical_resolution | double | r/w |  |
| warp_settings | [WarpSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.warp/warpsettings/) | r/w | Получает или задаёт параметры Warp, которые были установлены или получены из ресурса (по умолчанию) |
| width | int | r | Получает ширину объекта. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w |    |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| add_layer_mask(layer_mask) |  |
| adjust_brightness(brightness) |  |
| adjust_contrast(contrast) |  |
| adjust_gamma(gamma) |  |
| adjust_gamma(gamma_red, gamma_green, gamma_blue) |  |
| binarize_bradley(brightness_difference) |  |
| binarize_bradley(brightness_difference, window_size) |  |
| binarize_fixed(threshold) |  |
| binarize_otsu() |  |
| cache_data() |  |
| [can_load(file_path)](#can_load_file_path_1) |    |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) |    |
| [can_load(stream)](#can_load_stream_3) |    |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) |    |
| [can_save(options)](#can_save_options_5) |    |
| [convert_to_linked(linked_path)](#convert_to_linked_linked_path_6) | Преобразует этот встроенный смарт‑объект в связанный смарт‑объект. |
| [create(image_options, width, height)](#create_image_options_width_height_7) |    |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| dither(dithering_method, bits_count) |  |
| dither(dithering_method, bits_count, custom_palette) |  |
| draw_image(location, image) |  |
| [duplicate_layer()](#duplicate_layer__8) | Создаёт новый слой смарт‑объекта, копируя этот.<br/>            Обратите внимание, что для встроенных смарт‑объектов встроенное изображение является общим.<br/>            Если вы хотите скопировать встроенное изображение, используйте метод [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |
| embed_linked() | Встраивает связанный смарт‑объект в этот слой. |
| [export_contents(file_path)](#export_contents_file_path_9) | Экспортирует встроенное или связанное содержимое в файл. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_10) |    |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_11) |    |
| [get_default_options(args)](#get_default_options_args_12) |    |
| get_default_pixels(rectangle, partial_pixel_loader) |  |
| get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) |  |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_13) |    |
| [get_file_format(file_path)](#get_file_format_file_path_14) |    |
| [get_file_format(stream)](#get_file_format_stream_15) |    |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_16) |    |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_17) |    |
| [get_modify_date(use_default)](#get_modify_date_use_default_18) |    |
| [get_original_options()](#get_original_options__19) |    |
| [get_pixel(x, y)](#get_pixel_x_y_20) |    |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_21) |    |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_22) |    |
| [get_skew_angle()](#get_skew_angle__23) |    |
| grayscale() |  |
| [load(file_path)](#load_file_path_24) |    |
| [load(file_path, load_options)](#load_file_path_load_options_25) |    |
| [load(stream)](#load_stream_26) |    |
| [load(stream, load_options)](#load_stream_load_options_27) |    |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_28) |    |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_29) |    |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_30) |    |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_31) |    |
| [load_contents(options)](#load_contents_options_32) | Получает встроенное или связанное изображение слоя смарт‑объекта. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | Частично загружает 32‑битные ARGB‑пиксели (по блокам). |
| load_partial_pixels(desired_rectangle, pixel_loader) |  |
| [load_pixels(rectangle)](#load_pixels_rectangle_34) |    |
| load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) |  |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35) | Загружает необработанные данные. |
| merge_layer_to(layer_to_merge_into) |  |
| [new_smart_object_via_copy()](#new_smart_object_via_copy__36) | Создает новый слой смарт‑объекта, копируя текущий.<br/>            Воспроизводит функциональность `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` в Adobe Photoshop.<br/>            Обратите внимание, что она доступна только для встроенных смарт‑объектов, поскольку встроенное изображение также копируется.<br/>            Если вы хотите поделиться встроенным изображением, используйте метод [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_37) |    |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_38) |    |
| [relink_to_file(linked_path)](#relink_to_file_linked_path_39) | Перепривязывает связанный смарт‑объект к новому файлу.<br/>            Нет необходимости вызывать метод UpdateModifiedContent после этого. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| [replace_contents(image)](#replace_contents_image_40) | Заменяет содержимое смарт‑объекта, встроенное в слой смарт‑объекта. |
| [replace_contents(image, resolution)](#replace_contents_image_resolution_41) | Заменяет содержимое смарт‑объекта, встроенное в слой смарт‑объекта. |
| [replace_contents(linked_path)](#replace_contents_linked_path_42) | Заменяет содержимое файлом.<br/>            Нет необходимости вызывать метод UpdateModifiedContent после этого. |
| [replace_contents(linked_path, resolution)](#replace_contents_linked_path_resolution_43) | Заменяет содержимое файлом.<br/>            Нет необходимости вызывать метод UpdateModifiedContent после этого. |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| resize(new_width, new_height) |  |
| resize(new_width, new_height, resize_type) |  |
| resize(new_width, new_height, settings) |  |
| resize_height_proportionally(new_height) |  |
| resize_height_proportionally(new_height, resize_type) |  |
| resize_height_proportionally(new_height, settings) |  |
| resize_width_proportionally(new_width) |  |
| resize_width_proportionally(new_width, resize_type) |  |
| resize_width_proportionally(new_width, settings) |  |
| rotate(angle) |  |
| rotate(angle, resize_proportionally, background_color) |  |
| rotate_flip(rotate_flip_type) |  |
| save() |  |
| save(file_path) |  |
| save(file_path, options) |  |
| save(file_path, options, bounds_rectangle) |  |
| save(file_path, over_write) |  |
| save(stream) |  |
| save(stream, options_base) |  |
| save(stream, options_base, bounds_rectangle) |  |
| save_argb_32_pixels(rectangle, pixels) |  |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| save_pixels(rectangle, pixels) |  |
| save_raw_data(data, data_offset, rectangle, raw_data_settings) |  |
| set_argb_32_pixel(x, y, argb_32_color) |  |
| set_palette(palette, update_colors) |  |
| set_pixel(x, y, color) |  |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__44) |    |
| [to_bitmap()](#to_bitmap__45) |    |
| update_modified_content() | Обновляет кэш изображений слоя смарт‑объекта с изменённым содержимым. |
| write_argb_32_scan_line(scan_line_index, argb_32_pixels) |  |
| write_scan_line(scan_line_index, pixels) |  |


### Constructor: SmartObjectLayer(stream) {#SmartObjectLayer_stream_1}


```
 SmartObjectLayer(stream) 
```

Инициализирует новый экземпляр класса [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток элементов |

### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: convert_to_linked(linked_path) {#convert_to_linked_linked_path_6}


```
 convert_to_linked(linked_path) 
```

Преобразует этот встроенный смарт‑объект в связанный смарт‑объект.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| linked_path | string | Связанный путь. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |
| width | int |  |
| height | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: duplicate_layer() {#duplicate_layer__8}


```
 duplicate_layer() 
```

Создаёт новый слой смарт‑объекта, копируя этот.<br/>            Обратите внимание, что для встроенных смарт‑объектов встроенное изображение является общим.<br/>            Если вы хотите скопировать встроенное изображение, используйте метод [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/).

**Returns**

| Тип | Описание |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Клонированный экземпляр [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: export_contents(file_path) {#export_contents_file_path_9}


```
 export_contents(file_path) 
```

Экспортирует встроенное или связанное содержимое в файл.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к экспортируемому файлу. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_10}


```
 get_argb_32_pixel(x, y) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_11}


```
 get_default_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: get_default_options(args) {#get_default_options_args_12}


```
 get_default_options(args) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| args | object |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_13}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| байт |  |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_14}


```
 get_file_format(file_path) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_15}


```
 get_file_format(stream) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_16}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| pixels | int |  |
| width | int |  |
| height | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_17}


```
 get_fitting_rectangle(rectangle, width, height) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| width | int |  |
| height | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_18}


```
 get_modify_date(use_default) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| use_default | bool |  |

**Returns**

| Тип | Описание |
| :- | :- |
| datetime |  |


### Method: get_original_options() {#get_original_options__19}


```
 get_original_options() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_pixel(x, y) {#get_pixel_x_y_20}


```
 get_pixel(x, y) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) |  |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_21}


```
 get_proportional_height(width, height, new_width) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_width | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_22}


```
 get_proportional_width(width, height, new_height) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_height | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: get_skew_angle() {#get_skew_angle__23}


```
 get_skew_angle() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_24}


```
 load(file_path) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_25}


```
 load(file_path, load_options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream)  [static] {#load_stream_26}


```
 load(stream) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_27}


```
 load(stream, load_options) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_28}


```
 load_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_29}


```
 load_argb_64_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| long |  |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_30}


```
 load_cmyk_32_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_31}


```
 load_cmyk_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) |  |


### Method: load_contents(options) {#load_contents_options_32}


```
 load_contents(options) 
```

Получает встроенное или связанное изображение слоя смарт‑объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Параметры. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Загруженный экземпляр смарт‑объекта [Image](/psd/python-net/aspose.psd/image/). |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Частично загружает 32‑битные ARGB‑пиксели (по блокам).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Частичный загрузчик пикселей. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_34}


```
 load_pixels(rectangle) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Загружает необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружаются необработанные данные. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено преобразование данных. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Загрузчик необработанных данных. |

### Method: new_smart_object_via_copy() {#new_smart_object_via_copy__36}


```
 new_smart_object_via_copy() 
```

Создает новый слой смарт‑объекта, копируя текущий.<br/>            Воспроизводит функциональность `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` в Adobe Photoshop.<br/>            Обратите внимание, что она доступна только для встроенных смарт‑объектов, поскольку встроенное изображение также копируется.<br/>            Если вы хотите поделиться встроенным изображением, используйте метод [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/).

**Returns**

| Тип | Описание |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Клонированный экземпляр [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_37}


```
 read_argb_32_scan_line(scan_line_index) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_38}


```
 read_scan_line(scan_line_index) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: relink_to_file(linked_path) {#relink_to_file_linked_path_39}


```
 relink_to_file(linked_path) 
```

Перепривязывает связанный смарт‑объект к новому файлу.<br/>            Нет необходимости вызывать метод UpdateModifiedContent после этого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| linked_path | string | Связанный путь. |

### Method: replace_contents(image) {#replace_contents_image_40}


```
 replace_contents(image) 
```

Заменяет содержимое смарт‑объекта, встроенное в слой смарт‑объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение. |

### Method: replace_contents(image, resolution) {#replace_contents_image_resolution_41}


```
 replace_contents(image, resolution) 
```

Заменяет содержимое смарт‑объекта, встроенное в слой смарт‑объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Изображение. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | Настройки разрешения. Если null, будет использовано разрешение изображения. |

### Method: replace_contents(linked_path) {#replace_contents_linked_path_42}


```
 replace_contents(linked_path) 
```

Заменяет содержимое файлом.<br/>            Нет необходимости вызывать метод UpdateModifiedContent после этого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| linked_path | string | Связанный путь. |

### Method: replace_contents(linked_path, resolution) {#replace_contents_linked_path_resolution_43}


```
 replace_contents(linked_path, resolution) 
```

Заменяет содержимое файлом.<br/>            Нет необходимости вызывать метод UpdateModifiedContent после этого.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| linked_path | string | Связанный путь. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | Настройки разрешения. Если null, будет использовано разрешение изображения. |

### Method: shallow_copy() {#shallow_copy__44}


```
 shallow_copy() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) |  |


### Method: to_bitmap() {#to_bitmap__45}


```
 to_bitmap() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


