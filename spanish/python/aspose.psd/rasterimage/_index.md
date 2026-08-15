---
title: "Clase RasterImage"
type: docs
weight: 3740
url: /es/python-net/aspose.psd/rasterimage/
---

**Summary:** Represents a raster image supporting raster graphics operations.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RasterImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Image

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtiene o establece un valor que indica si se ajusta automáticamente la paleta. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece un valor para el color de fondo. |
| bits_per_pixel | int | r | Obtiene la cantidad de bits por píxel de la imagen. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtiene los límites de la imagen. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Obtiene el contenedor de [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Obtiene el flujo de datos del objeto. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtiene un valor del formato de archivo |
| has_alpha | bool | r | Obtiene un valor que indica si esta instancia tiene alfa. |
| has_background_color | bool | r/w | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| has_transparent_color | bool | r/w | Obtiene un valor que indica si la imagen tiene color transparente. |
| altura | int | r | Obtiene la altura de la imagen. |
| horizontal_resolution | double | r/w | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| image_opacity | float | r | Obtiene la opacidad de esta imagen. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Obtiene o establece el monitor de interrupciones. |
| is_cached | bool | r | Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos. |
| is_raw_data_available | bool | r | Obtiene un valor que indica si la carga de datos sin procesar está disponible. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| premultiply_components | bool | r/w | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Obtiene o establece el convertidor de color personalizado |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Obtiene el formato de datos sin procesar. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración, los datos se cargan sin conversión. |
| raw_fallback_index | int | r/w | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Obtiene o establece el convertidor de color indexado |
| raw_line_size | int | r | Obtiene el tamaño de línea sin procesar en bytes. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Obtiene el tamaño de la imagen. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene el color transparente de la imagen. |
| update_xmp_data | bool | r/w | Obtiene o establece un valor que indica si se debe actualizar los metadatos XMP. |
| use_palette | bool | r | Obtiene un valor que indica si se utiliza la paleta de la imagen. |
| use_raw_data | bool | r/w | Obtiene o establece un valor que indica si se debe usar la carga de datos sin procesar cuando la carga de datos sin procesar está disponible. |
| vertical_resolution | double | r/w | Obtiene o establece la resolución vertical, en píxeles por pulgada, de este [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| width | int | r | Obtiene el ancho de la imagen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtiene o establece los metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| adjust_brightness(brightness) |  |
| adjust_contrast(contrast) |  |
| adjust_gamma(gamma) |  |
| adjust_gamma(gamma_red, gamma_green, gamma_blue) |  |
| binarize_bradley(brightness_difference) |  |
| binarize_bradley(brightness_difference, window_size) |  |
| binarize_fixed(threshold) |  |
| binarize_otsu() |  |
| cache_data() | Almacena en caché los datos y asegura que no se realizará una carga adicional de datos desde el [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) subyacente. |
| [can_load(file_path)](#can_load_file_path_1) | Determina si la imagen puede cargarse desde la ruta de archivo especificada. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| [can_load(stream)](#can_load_stream_3) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando el <paramref name="loadOptions" /> especificado. |
| [can_save(options)](#can_save_options_5) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | Crea una nueva imagen usando las opciones de creación especificadas. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_7) | Realiza tramado en la imagen actual. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_8) | Realiza tramado en la imagen actual. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_9) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_10) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| [get_default_options(args)](#get_default_options_args_11) | Obtiene las opciones predeterminadas. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_12) | Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13) | Obtiene la matriz predeterminada de datos sin procesar usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_14) | Obtiene la matriz predeterminada de datos sin procesar. |
| [get_file_format(file_path)](#get_file_format_file_path_15) | Obtiene el formato de archivo. |
| [get_file_format(stream)](#get_file_format_stream_16) | Obtiene el formato de archivo. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_17) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_18) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_modify_date(use_default)](#get_modify_date_use_default_19) | Obtiene la fecha y hora en que la imagen del recurso fue modificada por última vez. |
| [get_original_options()](#get_original_options__20) | Obtiene las opciones basadas en la configuración del archivo original.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) método, se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) método como segundo parámetro. |
| [get_pixel(x, y)](#get_pixel_x_y_21) | Obtiene un píxel de la imagen.<br/>            Advertencia de rendimiento: Evite usar este método para iterar sobre todos los píxeles de la imagen, ya que puede provocar problemas de rendimiento significativos.<br/>            Para una manipulación de píxeles más eficiente, use el método `LoadArgb32Pixels` para obtener todo el arreglo de píxeles simultáneamente. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_22) | Obtiene una altura proporcional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_23) | Obtiene un ancho proporcional. |
| [get_skew_angle()](#get_skew_angle__24) |    |
| grayscale() |  |
| [load(file_path)](#load_file_path_25) | Carga una nueva imagen desde el archivo especificado. |
| [load(file_path, load_options)](#load_file_path_load_options_26) | Carga una nueva imagen desde el archivo especificado. |
| [load(stream)](#load_stream_27) | Carga una nueva imagen desde el flujo especificado. |
| [load(stream, load_options)](#load_stream_load_options_28) | Carga una nueva imagen desde el flujo especificado. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_29) | Carga píxeles ARGB de 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_30) | Carga píxeles ARGB de 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_31) | Carga píxeles en formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_32) | Carga píxeles en formato CMYK.<br/>            Este método está obsoleto. Por favor, use de manera más eficaz el método [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | Carga píxeles ARGB de 32 bits parcialmente por paquetes. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_34) | Carga píxeles parcialmente por paquetes. |
| [load_pixels(rectangle)](#load_pixels_rectangle_35) | Carga píxeles. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36) | Carga datos sin procesar. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37) | Carga datos sin procesar. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_38) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_39) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_40) | Redimensiona la imagen. Se utiliza el [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) predeterminado. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_41) | Redimensiona la imagen. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_42) | Redimensiona la imagen. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_43) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_44) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_45) | Redimensiona la altura proporcionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_46) | Redimensiona el ancho proporcionalmente. Se utiliza el [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) predeterminado. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_47) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_48) | Redimensiona el ancho proporcionalmente. |
| rotate(angle) |  |
| rotate(angle, resize_proportionally, background_color) |  |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_49) | Rota, voltea o rota y voltea la imagen. |
| save() | Guarda los datos de la imagen en el flujo subyacente. |
| [save(file_path)](#save_file_path_50) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(file_path, options)](#save_file_path_options_51) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_52) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [save(file_path, over_write)](#save_file_path_over_write_53) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(stream)](#save_stream_54) | Guarda los datos del objeto en el flujo especificado. |
| [save(stream, options_base)](#save_stream_options_base_55) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_56) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_57) | Guarda los píxeles ARGB de 32 bits. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_58) | Guarda los píxeles. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_59) | Guarda los datos sin procesar. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_60) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_61) | Establece la paleta de la imagen. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_62) | Establece un píxel de la imagen para la posición especificada. |
| set_resolution(dpi_x, dpi_y) |  |
| [to_bitmap()](#to_bitmap__63) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64) | Escribe la línea de escaneo completa en el índice de línea de escaneo especificado. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_65) | Escribe la línea de escaneo completa en el índice de línea de escaneo especificado. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

Determina si la imagen puede cargarse desde la ruta de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el archivo especificado; de lo contrario, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el archivo especificado; de lo contrario, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

Determina si la imagen puede cargarse desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el flujo especificado; de lo contrario, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando el <paramref name="loadOptions" /> especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde el cual cargar. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede cargarse desde el flujo especificado; de lo contrario, <c>false</c>. |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones de guardado a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas; de lo contrario, <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

Crea una nueva imagen usando las opciones de creación especificadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones de imagen. |
| width | int | El ancho. |
| altura | int | La altura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | La imagen recién creada. |


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_7}


```
 dither(dithering_method, bits_count) 
```

Realiza tramado en la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | El método de tramado. |
| bits_count | int | El recuento final de bits para el tramado. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_8}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Realiza tramado en la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | El método de tramado. |
| bits_count | int | El recuento final de bits para el tramado. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta personalizada para el tramado. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_9}


```
 get_argb_32_pixel(x, y) 
```

Obtiene un píxel ARGB de 32 bits de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El píxel ARGB de 32 bits para la ubicación especificada. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_10}


```
 get_default_argb_32_pixels(rectangle) 
```

Obtiene la matriz predeterminada de píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que obtener píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La matriz de píxeles predeterminada. |


### Method: get_default_options(args) {#get_default_options_args_11}


```
 get_default_options(args) 
```

Obtiene las opciones predeterminadas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| args | object | Los argumentos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Opciones predeterminadas |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_12}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que obtener píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | El cargador parcial de píxeles. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Obtiene la matriz predeterminada de datos sin procesar usando el cargador parcial de píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que obtener píxeles. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | El cargador parcial de datos sin procesar. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | La configuración de datos sin procesar. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_14}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Obtiene la matriz predeterminada de datos sin procesar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que obtener datos sin procesar. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | La configuración de datos sin procesar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | La matriz de datos sin procesar predeterminada. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_15}


```
 get_file_format(file_path) 
```

Obtiene el formato de archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | El formato de archivo determinado. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_16}


```
 get_file_format(stream) 
```

Obtiene el formato de archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | El formato de archivo determinado. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_17}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Obtiene el rectángulo que se ajusta a la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que obtener el rectángulo de ajuste. |
| pixels | int | Los píxeles ARGB de 32 bits. |
| width | int | El ancho del objeto. |
| altura | int | La altura del objeto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de ajuste o excepción si no se puede encontrar un rectángulo de ajuste. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_18}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Obtiene el rectángulo que se ajusta a la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que obtener el rectángulo de ajuste. |
| width | int | El ancho del objeto. |
| altura | int | La altura del objeto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de ajuste o excepción si no se puede encontrar un rectángulo de ajuste. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_19}


```
 get_modify_date(use_default) 
```

Obtiene la fecha y hora en que la imagen del recurso fue modificada por última vez.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| use_default | bool | si se establece en <c>true</c> utiliza la información de FileInfo como valor predeterminado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| datetime | La fecha y hora en que la imagen del recurso fue modificada por última vez. |


### Method: get_original_options() {#get_original_options__20}


```
 get_original_options() 
```

Obtiene las opciones basadas en la configuración del archivo original.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) método, se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) método como segundo parámetro.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones basadas en la configuración del archivo original. |


### Method: get_pixel(x, y) {#get_pixel_x_y_21}


```
 get_pixel(x, y) 
```

Obtiene un píxel de la imagen.<br/>            Advertencia de rendimiento: Evite usar este método para iterar sobre todos los píxeles de la imagen, ya que puede provocar problemas de rendimiento significativos.<br/>            Para una manipulación de píxeles más eficiente, use el método `LoadArgb32Pixels` para obtener todo el arreglo de píxeles simultáneamente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | El color del píxel para la ubicación especificada. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_22}


```
 get_proportional_height(width, height, new_width) 
```

Obtiene una altura proporcional.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho. |
| altura | int | La altura. |
| new_width | int | El nuevo ancho. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La altura proporcional. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_23}


```
 get_proportional_width(width, height, new_height) 
```

Obtiene un ancho proporcional.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho. |
| altura | int | La altura. |
| new_height | int | La nueva altura. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El ancho proporcional. |


### Method: get_skew_angle() {#get_skew_angle__24}


```
 get_skew_angle() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_25}


```
 load(file_path) 
```

Carga una nueva imagen desde el archivo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo desde donde cargar la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | La imagen cargada. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_26}


```
 load(file_path, load_options) 
```

Carga una nueva imagen desde el archivo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo desde donde cargar la imagen. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | La imagen cargada. |


### Method: load(stream)  [static] {#load_stream_27}


```
 load(stream) 
```

Carga una nueva imagen desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde donde cargar la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | La imagen cargada. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_28}


```
 load(stream, load_options) 
```

Carga una nueva imagen desde el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo desde donde cargar la imagen. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Las opciones de carga. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | La imagen cargada. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_29}


```
 load_argb_32_pixels(rectangle) 
```

Carga píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que cargar píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La matriz de píxeles ARGB de 32 bits cargada. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_30}


```
 load_argb_64_pixels(rectangle) 
```

Carga píxeles ARGB de 64 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que cargar píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| long | La matriz de píxeles ARGB de 64 bits cargada. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_31}


```
 load_cmyk_32_pixels(rectangle) 
```

Carga píxeles en formato CMYK.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que cargar píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Los píxeles CMYK cargados presentados como valores enteros de 32 bits. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_32}


```
 load_cmyk_pixels(rectangle) 
```

Carga píxeles en formato CMYK.<br/>            Este método está obsoleto. Por favor, use de manera más eficaz el método [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que cargar píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | La matriz de píxeles CMYK cargada. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carga píxeles ARGB de 32 bits parcialmente por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo deseado. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | El cargador de píxeles ARGB de 32 bits. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_34}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carga píxeles parcialmente por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo deseado. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | El cargador de píxeles. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_35}


```
 load_pixels(rectangle) 
```

Carga píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que cargar píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | La matriz de píxeles cargada. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Carga datos sin procesar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo desde el cual cargar los datos sin procesar. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Los límites de la imagen de destino. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Los ajustes de datos sin procesar a usar para los datos cargados. Nota: si los datos no están en el formato especificado, se realizará la conversión de datos. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | El cargador de datos sin procesar. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Carga datos sin procesar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo desde el cual cargar los datos sin procesar. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Los ajustes de datos sin procesar a usar para los datos cargados. Nota: si los datos no están en el formato especificado, se realizará la conversión de datos. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | El cargador de datos sin procesar. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_38}


```
 read_argb_32_scan_line(scan_line_index) 
```

Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | La matriz de valores de color ARGB de 32 bits de la línea de escaneo. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_39}


```
 read_scan_line(scan_line_index) 
```

Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | La matriz de valores de color de píxel de la línea de escaneo. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_40}


```
 resize(new_width, new_height) 
```

Redimensiona la imagen. Se utiliza el [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) predeterminado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_41}


```
 resize(new_width, new_height, resize_type) 
```

Redimensiona la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | El tipo de redimensionado. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_42}


```
 resize(new_width, new_height, settings) 
```

Redimensiona la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Los ajustes de redimensionado. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_43}


```
 resize_height_proportionally(new_height) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_44}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Tipo de redimensionamiento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_45}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_46}


```
 resize_width_proportionally(new_width) 
```

Redimensiona el ancho proporcionalmente. Se utiliza el [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) predeterminado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_47}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Tipo de redimensionamiento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_48}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Los ajustes de redimensionamiento de la imagen. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_49}


```
 rotate_flip(rotate_flip_type) 
```

Rota, voltea o rota y voltea la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Tipo de rotación e inversión. |

### Method: save(file_path) {#save_file_path_50}


```
 save(file_path) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |

### Method: save(file_path, options) {#save_file_path_options_51}


```
 save(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_52}


```
 save(file_path, options, bounds_rectangle) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### Method: save(file_path, over_write) {#save_file_path_over_write_53}


```
 save(file_path, over_write) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |
| over_write | bool | si se establece en <c>true</c> sobrescribirá el contenido del archivo, de lo contrario se producirá una anexión. |

### Method: save(stream) {#save_stream_54}


```
 save(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo para guardar los datos del objeto. |

### Method: save(stream, options_base) {#save_stream_options_base_55}


```
 save(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo para guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones de guardado. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_56}


```
 save(stream, options_base, bounds_rectangle) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo para guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones de guardado. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de límites de la imagen de destino. Establezca el rectángulo vacío para usar los límites de origen. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_57}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Guarda los píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo donde guardar los píxeles. |
| pixels | int | La matriz de píxeles ARGB de 32 bits. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_58}


```
 save_pixels(rectangle, pixels) 
```

Guarda los píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo donde guardar los píxeles. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | La matriz de píxeles. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_59}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Guarda los datos sin procesar.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| datos | byte | Los datos sin procesar. |
| data_offset | int | El desplazamiento inicial de los datos sin procesar. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo de datos sin procesar. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Los ajustes de datos sin procesar en los que se encuentran los datos. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_60}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Establece un píxel ARGB de 32 bits de la imagen para la posición especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |
| argb_32_color | int | El píxel ARGB de 32 bits para la posición especificada. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_61}


```
 set_palette(palette, update_colors) 
```

Establece la paleta de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta a establecer. |
| update_colors | bool | si se establece en <c>true</c> los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecen sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas correspondientes en la paleta. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_62}


```
 set_pixel(x, y, color) 
```

Establece un píxel de la imagen para la posición especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int | La ubicación x del píxel. |
| y | int | La ubicación y del píxel. |
| color | [Color](/psd/python-net/aspose.psd/color) | El color del píxel para la posición especificada. |

### Method: to_bitmap() {#to_bitmap__63}


```
 to_bitmap() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Escribe la línea de escaneo completa en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| argb_32_pixels | int | La matriz de colores ARGB de 32 bits para escribir. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_65}


```
 write_scan_line(scan_line_index, pixels) 
```

Escribe la línea de escaneo completa en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | La matriz de colores de píxeles para escribir. |

