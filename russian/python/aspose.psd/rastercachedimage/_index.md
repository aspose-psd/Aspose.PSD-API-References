---
title: "RasterCachedImage Класс"
type: docs
weight: 3730
url: /ru/python-net/aspose.psd/rastercachedimage/
---

**Summary:** Represents a raster image supporting raster graphics operations. This image caches pixel data when required.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RasterCachedImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterImage

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Получает или задаёт значение, указывающее, следует ли автоматически корректировать палитру. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает или задаёт значение фонового цвета. |
| bits_per_pixel | int | r | Получает количество бит на пиксель изображения. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Получает границы объекта. |
| buffer_size_hint | int | r/w | Получает или задаёт подсказку размера буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Получает контейнер [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Получает поток данных объекта. |
| освобождено | bool | r | Получает значение, указывающее, освобожден ли данный экземпляр. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Получает значение формата файла |
| имеет_alpha | bool | r | Получает значение, указывающее, имеет ли этот экземпляр альфа-канал. |
| имеет_цвет_фона | bool | r/w | Получает или задает значение, указывающее, имеет ли изображение фоновой цвет. |
| имеет_прозрачный_цвет | bool | r/w | Получает значение, указывающее, имеет ли изображение прозрачный цвет. |
| height | int | r | Получает высоту объекта. |
| horizontal_resolution | double | r/w | Получает или задает горизонтальное разрешение в пикселях на дюйм для этого [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| непрозрачность_изображения | float | r | Получает непрозрачность этого изображения. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Получает или задает монитор прерываний. |
| закешировано | bool | r | Получает значение, указывающее, кэшируются ли данные изображения в данный момент. |
| сырые_данные_доступны | bool | r | Получает значение, указывающее, доступна ли загрузка необработанных данных. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Получает или задает цветовую палитру. Цветовая палитра не используется, когда пиксели представлены напрямую. |
| предумножить_компоненты | bool | r/w | Получает или задает значение, указывающее, должны ли компоненты изображения быть предварительно умноженными. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Получает или задает пользовательский конвертер цветов |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Получает формат необработанных данных. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Получает текущие настройки сырых данных. Примечание: при использовании этих настроек данные загружаются без конвертации. |
| индекс_резервного_варианта | int | r/w | Получает или задает запасной индекс, используемый, когда индекс палитры выходит за пределы |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Получает или задает индексированный конвертер цветов |
| размер_строки_сырых | int | r | Получает размер необработанной строки в байтах. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Получает размер объекта. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Получает прозрачный цвет изображения. |
| update_xmp_data | bool | r/w | Получает или задает значение, указывающее, следует ли обновлять метаданные XMP. |
| use_palette | bool | r | Получает значение, указывающее, используется ли палитра изображения. |
| use_raw_data | bool | r/w | Получает или задает значение, указывающее, следует ли использовать загрузку необработанных данных, когда такая загрузка доступна. |
| vertical_resolution | double | r/w | Получает или задает вертикальное разрешение в пикселях на дюйм для этого [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| width | int | r | Получает ширину объекта. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Получает или задает XMP‑метаданные. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Регулировка яркости изображения. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Контрастирование изображения |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Гамма‑коррекция изображения. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Гамма‑коррекция изображения. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_5) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_6) | Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_7) | Бинаризация изображения с предопределённым порогом. |
| binarize_otsu() | Бинаризация изображения с порогом Оцу. |
| cache_data() | Кеширует данные и гарантирует, что дополнительная загрузка данных из базового [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) не будет выполнена. |
| [can_load(file_path)](#can_load_file_path_8) | Определяет, может ли изображение быть загружено из указанного пути к файлу. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_9) | Определяет, может ли изображение быть загружено из указанного пути к файлу и, при необходимости, с использованием указанных параметров открытия. |
| [can_load(stream)](#can_load_stream_10) | Определяет, может ли изображение быть загружено из указанного потока. |
| [can_load(stream, load_options)](#can_load_stream_load_options_11) | Определяет, может ли изображение быть загружено из указанного потока и, при необходимости, с использованием указанного <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_12) | Определяет, может ли изображение быть сохранено в указанный формат файла, представленный переданными параметрами сохранения. |
| [create(image_options, width, height)](#create_image_options_width_height_13) | Создаёт новое изображение с использованием указанных параметров создания. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_14) | Обрезка изображения. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_15) | Выполняет дизеринг текущего изображения. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_16) | Выполняет дизеринг текущего изображения. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_17) | Получает 32‑битный ARGB‑пиксель изображения. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_18) | Получает массив пикселей по умолчанию в формате 32‑бит ARGB. |
| [get_default_options(args)](#get_default_options_args_19) | Получает параметры по умолчанию. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_20) | Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_21) | Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_22) | Получает массив необработанных данных по умолчанию. |
| [get_file_format(file_path)](#get_file_format_file_path_23) | Получает формат файла. |
| [get_file_format(stream)](#get_file_format_stream_24) | Получает формат файла. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_25) | Получает прямоугольник, который вписывается в текущее изображение. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_26) | Получает прямоугольник, который вписывается в текущее изображение. |
| [get_modify_date(use_default)](#get_modify_date_use_default_27) | Получает дату и время последнего изменения ресурсного изображения. |
| [get_original_options()](#get_original_options__28) | Получает параметры на основе настроек исходного файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров исходного изображения без изменений.<br/>            Например, если мы загружаем черно-белое PNG‑изображение с 1 битом на пиксель, а затем сохраняем его с помощью<br/>            метода [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/), будет получено PNG‑изображение с 8 битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            методу [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) в качестве второго параметра. |
| [get_pixel(x, y)](#get_pixel_x_y_29) | Получает пиксель изображения.<br/>            Предупреждение о производительности: избегайте использования этого метода для обхода всех пикселей изображения, так как это может привести к значительным проблемам с производительностью.<br/>            Для более эффективного управления пикселями используйте метод `LoadArgb32Pixels` для одновременного получения всего массива пикселей. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_30) | Получает пропорциональную высоту. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_31) | Получает пропорциональную ширину. |
| [get_skew_angle()](#get_skew_angle__32) |    |
| grayscale() | Преобразование изображения в его градации серого |
| [load(file_path)](#load_file_path_33) | Загружает новое изображение из указанного файла. |
| [load(file_path, load_options)](#load_file_path_load_options_34) | Загружает новое изображение из указанного файла. |
| [load(stream)](#load_stream_35) | Загружает новое изображение из указанного потока. |
| [load(stream, load_options)](#load_stream_load_options_36) | Загружает новое изображение из указанного потока. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_37) | Загружает 32‑битные ARGB‑пиксели. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_38) | Загружает 64‑битные ARGB‑пиксели. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_39) | Загружает пиксели в формате CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_40) | Загружает пиксели в формате CMYK.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_41) | Загружает 32-битные ARGB пиксели частично пакетами. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_42) | Частично загружает пиксели пакетами. |
| [load_pixels(rectangle)](#load_pixels_rectangle_43) | Загружает пиксели. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_44) | Загружает необработанные данные. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_45) | Загружает необработанные данные. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_46) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_47) | Читает всю строку сканирования по указанному индексу строки сканирования. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_48) | Изменяет размер изображения. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_49) | Изменяет размер изображения. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_50) | Изменяет размер изображения. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_51) | Пропорционально изменяет высоту. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_52) | Пропорционально изменяет высоту. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_53) | Пропорционально изменяет высоту. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_54) | Пропорционально изменяет ширину. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_55) | Пропорционально изменяет ширину. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_56) | Пропорционально изменяет ширину. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_57) | Поворачивает изображение вокруг центра. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_58) | Поворачивает, отражает или одновременно поворачивает и отражает изображение. |
| save() | Сохраняет данные изображения в базовый поток. |
| [save(file_path)](#save_file_path_59) | Сохраняет данные объекта в указанное расположение файла. |
| [save(file_path, options)](#save_file_path_options_60) | Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_61) | Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения. |
| [save(file_path, over_write)](#save_file_path_over_write_62) | Сохраняет данные объекта в указанное расположение файла. |
| [save(stream)](#save_stream_63) | Сохраняет данные объекта в указанный поток. |
| [save(stream, options_base)](#save_stream_options_base_64) | Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_65) | Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_66) | Сохраняет 32‑битные ARGB‑пиксели. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_67) | Сохраняет пиксели (метод, специфичный для формата). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_68) | Сохраняет необработанные данные. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_69) | Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_70) | Устанавливает палитру изображения. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_71) | Устанавливает пиксель изображения для указанной позиции. |
| set_resolution(dpi_x, dpi_y) |  |
| [to_bitmap()](#to_bitmap__72) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_73) | Записывает всю строку сканирования в указанный индекс строки сканирования. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_74) | Записывает всю строку сканирования в указанный индекс строки сканирования. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Регулировка яркости изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| яркость | int | Значение яркости. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Контрастирование изображения

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| контраст | float | Значение контраста (в диапазоне [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Гамма‑коррекция изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| гамма | float | Коэффициент гаммы для красного, зелёного и синего каналов |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Гамма‑коррекция изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| gamma_red | float | Коэффициент гаммы для красного канала |
| gamma_green | float | Коэффициент гаммы для зелёного канала |
| gamma_blue | float | Коэффициент гаммы для синего канала |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_5}


```
 binarize_bradley(brightness_difference) 
```

Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | double | Разница яркости между пикселем и средним значением окна s x s пикселей, центрированного вокруг этого пикселя |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_6}


```
 binarize_bradley(brightness_difference, window_size) 
```

Бинаризация изображения с использованием адаптивного порогового алгоритма Брэдли, основанного на интегральном изображении

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| brightness_difference | double | Разница яркости между пикселем и средним значением окна s x s пикселей, центрированного вокруг этого пикселя |
| window_size | int | Размер окна s x s пикселей, центрированного вокруг этого пикселя |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_7}


```
 binarize_fixed(threshold) 
```

Бинаризация изображения с предопределённым порогом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| порог | байт | Значение порога. Если соответствующее серое значение пикселя больше порога, ему будет присвоено значение 255, иначе 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_8}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_9}


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


### Method: can_load(stream)  [static] {#can_load_stream_10}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_11}


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


### Method: can_save(options) {#can_save_options_12}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_13}


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


### Method: crop(rectangle) {#crop_rectangle_14}


```
 crop(rectangle) 
```

Обрезка изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_15}


```
 dither(dithering_method, bits_count) 
```

Выполняет дизеринг текущего изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Метод дизеринга. |
| bits_count | int | Окончательное количество бит для дизеринга. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_16}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Выполняет дизеринг текущего изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Метод дизеринга. |
| bits_count | int | Окончательное количество бит для дизеринга. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Пользовательская палитра для дизеринга. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_17}


```
 get_argb_32_pixel(x, y) 
```

Получает 32‑битный ARGB‑пиксель изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | 32‑битный ARGB‑пиксель для указанного расположения. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_18}


```
 get_default_argb_32_pixels(rectangle) 
```

Получает массив пикселей по умолчанию в формате 32‑бит ARGB.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого получать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Массив пикселей по умолчанию. |


### Method: get_default_options(args) {#get_default_options_args_19}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_20}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Получает массив пикселей по умолчанию с использованием частичного загрузчика пикселей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого получать пиксели. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Частичный загрузчик пикселей. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_21}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Получает массив необработанных данных по умолчанию с использованием частичного загрузчика пикселей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого получать пиксели. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Частичный загрузчик необработанных данных. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки необработанных данных. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_22}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Получает массив необработанных данных по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого получать необработанные данные. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки необработанных данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| байт | Массив необработанных данных по умолчанию. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_23}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_24}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_25}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_26}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_27}


```
 get_modify_date(use_default) 
```

Получает дату и время последнего изменения ресурсного изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| use_default | bool | если установлено в <c>true</c>, использует информацию из FileInfo в качестве значения по умолчанию. |

**Returns**

| Тип | Описание |
| :- | :- |
| datetime | Дата и время последнего изменения изображения ресурса. |


### Method: get_original_options() {#get_original_options__28}


```
 get_original_options() 
```

Получает параметры на основе настроек исходного файла.<br/>            Это может быть полезно для сохранения глубины цвета и других параметров исходного изображения без изменений.<br/>            Например, если мы загружаем черно-белое PNG‑изображение с 1 битом на пиксель, а затем сохраняем его с помощью<br/>            метода [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/), будет получено PNG‑изображение с 8 битами на пиксель.<br/>            Чтобы избежать этого и сохранить PNG‑изображение с 1 битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их<br/>            методу [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) в качестве второго параметра.

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры, основанные на настройках оригинального файла. |


### Method: get_pixel(x, y) {#get_pixel_x_y_29}


```
 get_pixel(x, y) 
```

Получает пиксель изображения.<br/>            Предупреждение о производительности: избегайте использования этого метода для обхода всех пикселей изображения, так как это может привести к значительным проблемам с производительностью.<br/>            Для более эффективного управления пикселями используйте метод `LoadArgb32Pixels` для одновременного получения всего массива пикселей.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Цвет пикселя для указанного положения. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_30}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_31}


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


### Method: get_skew_angle() {#get_skew_angle__32}


```
 get_skew_angle() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_33}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_34}


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


### Method: load(stream)  [static] {#load_stream_35}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_36}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_37}


```
 load_argb_32_pixels(rectangle) 
```

Загружает 32‑битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Загруженный массив 32‑битных ARGB пикселей. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_38}


```
 load_argb_64_pixels(rectangle) 
```

Загружает 64‑битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| long | Загруженный массив 64‑битных ARGB пикселей. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_39}


```
 load_cmyk_32_pixels(rectangle) 
```

Загружает пиксели в формате CMYK.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Загруженные CMYK пиксели, представленные как 32‑битные целочисленные значения. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_40}


```
 load_cmyk_pixels(rectangle) 
```

Загружает пиксели в формате CMYK.<br/>            Этот метод устарел. Пожалуйста, используйте более эффективный метод [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Загруженный массив CMYK пикселей. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_41}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Загружает 32-битные ARGB пиксели частично пакетами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Желаемый прямоугольник. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Загрузчик 32-битных ARGB пикселей. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_42}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Частично загружает пиксели пакетами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Желаемый прямоугольник. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Загрузчик пикселей. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_43}


```
 load_pixels(rectangle) 
```

Загружает пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружать пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Загруженный массив пикселей. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_44}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Загружает необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник, из которого загружаются необработанные данные. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Границы целевого изображения. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки необработанных данных, используемые для загруженных данных. Обратите внимание, что если данные не в указанном формате, будет выполнено преобразование данных. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Загрузчик необработанных данных. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_45}


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

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_46}


```
 read_argb_32_scan_line(scan_line_index) 
```

Читает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Нулевой индекс строки сканирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Массив 32‑битных ARGB значений цвета строки сканирования. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_47}


```
 read_scan_line(scan_line_index) 
```

Читает всю строку сканирования по указанному индексу строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Нулевой индекс строки сканирования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Массив значений цвета пикселей строки сканирования. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_48}


```
 resize(new_width, new_height) 
```

Изменяет размер изображения. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| new_height | int | Новая высота. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_49}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_50}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_51}


```
 resize_height_proportionally(new_height) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_52}


```
 resize_height_proportionally(new_height, resize_type) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Тип изменения размера. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_53}


```
 resize_height_proportionally(new_height, settings) 
```

Пропорционально изменяет высоту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_height | int | Новая высота. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Настройки изменения размера изображения. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_54}


```
 resize_width_proportionally(new_width) 
```

Пропорционально изменяет ширину. Используется значение по умолчанию [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_55}


```
 resize_width_proportionally(new_width, resize_type) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Тип изменения размера. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_56}


```
 resize_width_proportionally(new_width, settings) 
```

Пропорционально изменяет ширину.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_width | int | Новая ширина. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Настройки изменения размера изображения. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_57}


```
 rotate(angle, resize_proportionally, background_color) 
```

Поворачивает изображение вокруг центра.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| угол | float | Угол вращения в градусах. Положительные значения вращают по часовой стрелке. |
| resize_proportionally | bool | если установить в <c>true</c>, размер изображения будет изменён в соответствии с проекциями повернутого прямоугольника (угловых точек); в противном случае размеры останутся неизменными, и будет вращено только внутреннее содержимое изображения. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Цвет фона. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_58}


```
 rotate_flip(rotate_flip_type) 
```

Поворачивает, отражает или одновременно поворачивает и отражает изображение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Тип вращения и отражения. |

### Method: save(file_path) {#save_file_path_59}


```
 save(file_path) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для сохранения данных объекта. |

### Method: save(file_path, options) {#save_file_path_options_60}


```
 save(file_path, options) 
```

Сохраняет данные объекта в указанное расположение файла в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_61}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_62}


```
 save(file_path, over_write) 
```

Сохраняет данные объекта в указанное расположение файла.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_path | string | Путь к файлу для сохранения данных объекта. |
| over_write | bool | если установить в <c>true</c>, содержимое файла будет перезаписано, иначе будет выполнено добавление. |

### Method: save(stream) {#save_stream_63}


```
 save(stream) 
```

Сохраняет данные объекта в указанный поток.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для сохранения данных объекта. |

### Method: save(stream, options_base) {#save_stream_options_base_64}


```
 save(stream, options_base) 
```

Сохраняет данные изображения в указанный поток в указанном формате файла согласно параметрам сохранения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| поток | _io.BufferedRandom | Поток для сохранения данных изображения. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Параметры сохранения. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_65}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_66}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Сохраняет 32‑битные ARGB‑пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник для сохранения пикселей. |
| pixels | int | Массив 32‑битных ARGB‑пикселей. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_67}


```
 save_pixels(rectangle, pixels) 
```

Сохраняет пиксели (метод, специфичный для формата).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник для сохранения пикселей. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Массив 32‑битных ARGB‑пикселей. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_68}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Сохраняет необработанные данные.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| данные | байт | Необработанные данные. |
| data_offset | int | Начальное смещение необработанных данных. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Прямоугольник необработанных данных. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Настройки формата необработанных данных. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_69}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Устанавливает 32‑битный ARGB‑пиксель изображения для указанной позиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| argb_32_color | int | 32‑битный ARGB‑пиксель для указанной позиции. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_70}


```
 set_palette(palette, update_colors) 
```

Устанавливает палитру изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Палитра для установки. |
| update_colors | bool | если установить значение <c>true</c>, цвета будут обновлены в соответствии с новой палитрой; в противном случае индексы цветов останутся без изменений. Обратите внимание, что неизменённые индексы могут вызвать сбой изображения при загрузке, если у некоторых индексов нет соответствующих записей в палитре. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_71}


```
 set_pixel(x, y, color) 
```

Устанавливает пиксель изображения для указанной позиции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |
| color | [Color](/psd/python-net/aspose.psd/color) | Цвет пикселя для указанной позиции. |

### Method: to_bitmap() {#to_bitmap__72}


```
 to_bitmap() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_73}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Нулевой индекс строки сканирования. |
| argb_32_pixels | int | Массив 32‑битных ARGB‑цветов для записи. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_74}


```
 write_scan_line(scan_line_index, pixels) 
```

Записывает всю строку сканирования в указанный индекс строки сканирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| scan_line_index | int | Нулевой индекс строки сканирования. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Массив цветов пикселей для записи. |

