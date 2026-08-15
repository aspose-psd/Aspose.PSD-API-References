---
title: "Clase Layer"
type: docs
weight: 930
url: /es/python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Layer()](#Layer__1) | Inicializa una nueva instancia de la clase [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). Constructor para inicialización perezosa. |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | Inicializa una nueva instancia de la clase [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) a partir de matrices de bytes. |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | Inicializa una nueva instancia de la clase [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [Layer(stream)](#Layer_stream_4) | Inicializa una nueva instancia de la clase [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r | Representa la firma del modo de fusión. |
| LAYER_HEADER_SIZE [static] | int | r | El tamaño del encabezado de capa. |
| auto_adjust_palette | bool | r/w | Obtiene o establece un valor que indica si se ajusta automáticamente la paleta. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece un valor para el color de fondo. |
| bits_per_pixel | int | r | Obtiene la cantidad de bits por píxel de la imagen. |
| blend_clipped_elements | bool | r/w | Obtiene o establece la mezcla del elemento recortado. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Obtiene o establece la clave del modo de fusión. |
| blend_mode_signature | int | r | Obtiene la firma del modo de fusión. |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | Obtiene las opciones de fusión. |
| inferior | int | r/w | Obtiene o establece la posición de la capa inferior. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtiene los límites del objeto. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | Obtiene o establece la información del canal. |
| channels_count | ushort | r | Obtiene el recuento de canales de la capa. |
| recorte | byte | r/w | Obtiene o establece el recorte de la capa. 0 = base, 1 = no base. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Obtiene el contenedor de [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Obtiene el flujo de datos del objeto. |
| display_name | string | r/w | Obtiene o establece el nombre para mostrar de la capa. |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| extra_length | int | r | Obtiene la longitud de información extra de la capa en bytes. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtiene un valor del formato de archivo |
| fill_opacity | int | r/w | Obtiene o establece la opacidad de relleno. |
| filler | byte | r/w | Obtiene o establece el relleno de la capa. |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | Obtiene o establece los indicadores de la capa.<br/>            bit 0 = transparencia protegida;<br/>            bit 1 = visible;<br/>            bit 2 = obsoleto;<br/>            bit 3 = 1 para Photoshop 5.0 y posteriores, indica si el bit 4 contiene información útil;<br/>            bit 4 = datos de píxeles irrelevantes para la apariencia del documento. |
| has_alpha | bool | r | Obtiene un valor que indica si esta instancia tiene alfa. |
| has_background_color | bool | r/w | Obtiene o establece un valor que indica si la imagen tiene color de fondo. |
| has_transparent_color | bool | r/w | Obtiene un valor que indica si la imagen tiene color transparente. |
| altura | int | r | Obtiene la altura de la imagen. |
| horizontal_resolution | double | r/w | Obtiene o establece la resolución horizontal, en píxeles por pulgada, de este [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| image_opacity | float | r | Obtiene la opacidad de esta imagen. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Obtiene o establece el monitor de interrupciones. |
| is_cached | bool | r | Obtiene un valor que indica si los datos de la imagen están almacenados en caché actualmente. |
| is_raw_data_available | bool | r | Obtiene un valor que indica si se admite la carga de datos sin procesar. |
| is_visible | bool | r/w | Obtiene o establece un valor que indica si la capa es visible |
| is_visible_in_group | bool | r | Obtiene un valor que indica si esta instancia es visible en el grupo (Si la capa no está en un grupo significa que es el grupo raíz). |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | Obtiene o establece los datos de rangos de fusión de la capa. |
| layer_creation_date_time | datetime | r/w | Obtiene o establece la fecha y hora de creación de la capa. |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags | = LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | Obtiene o establece los datos de la máscara de capa. |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | Obtiene las opciones de la capa. |
| left | int | r/w | Obtiene o establece la posición izquierda de la capa. |
| longitud | int | r | Obtiene la longitud total de la capa en bytes. |
| name | string | r/w | Obtiene o establece el nombre de la capa. |
| opacity | byte | r/w | Obtiene o establece la opacidad de la capa. 0 = transparente, 255 = opaco. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtiene o establece la paleta de colores. La paleta de colores no se utiliza cuando los píxeles se representan directamente. |
| premultiply_components | bool | r/w | Obtiene o establece un valor que indica si los componentes de la imagen deben estar premultiplicados. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Obtiene o establece el convertidor de color personalizado |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Obtiene el formato de datos sin procesar. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración, los datos se cargan sin conversión. |
| raw_fallback_index | int | r/w | Obtiene o establece el índice de reserva a usar cuando el índice de la paleta está fuera de los límites |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Obtiene o establece el convertidor de color indexado |
| raw_line_size | int | r | Obtiene el tamaño de línea sin procesar en bytes. |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | Obtiene o establece los recursos de la capa. |
| right | int | r/w | Obtiene o establece la posición derecha de la capa. |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | Obtiene o establece el resaltado de color de la hoja decorativa en la lista de capas |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Obtiene el tamaño del objeto. |
| top | int | r/w | Obtiene o establece la posición superior de la capa. |
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
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | Agrega la máscara a la capa actual. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | Ajuste de brillo para la imagen. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | Contraste de imagen |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | Corrección gamma de una imagen. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | Corrección gamma de una imagen. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binarización de una imagen con umbral predefinido |
| binarize_otsu() | Binarización de una imagen con umbralizado de Otsu |
| cache_data() | Almacena en caché los datos y asegura que no se realizará una carga adicional de datos desde el [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) subyacente. |
| [can_load(file_path)](#can_load_file_path_9) | Determina si la imagen puede cargarse desde la ruta de archivo especificada. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | Determina si la imagen puede cargarse desde la ruta de archivo especificada y, opcionalmente, usando las opciones de apertura especificadas. |
| [can_load(stream)](#can_load_stream_11) | Determina si la imagen puede cargarse desde el flujo especificado. |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | Determina si la imagen puede cargarse desde el flujo especificado y, opcionalmente, usando el <paramref name="loadOptions" /> especificado. |
| [can_save(options)](#can_save_options_13) | Determina si la imagen puede guardarse en el formato de archivo especificado representado por las opciones de guardado proporcionadas. |
| [create(image_options, width, height)](#create_image_options_width_height_14) | Crea una nueva imagen usando las opciones de creación especificadas. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_15) | Recortando la imagen. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | Realiza tramado en la imagen actual. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | Realiza tramado en la imagen actual. |
| [draw_image(location, image)](#draw_image_location_image_18) | Dibuja la imagen en la capa. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | Obtiene un píxel ARGB de 32 bits de la imagen. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | Obtiene la matriz predeterminada de píxeles ARGB de 32 bits. |
| [get_default_options(args)](#get_default_options_args_21) | Obtiene las opciones predeterminadas. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | Obtiene la matriz predeterminada de datos sin procesar usando el cargador parcial de píxeles. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | Obtiene la matriz predeterminada de datos sin procesar. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | Obtiene el formato de archivo. |
| [get_file_format(stream)](#get_file_format_stream_26) | Obtiene el formato de archivo. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Obtiene el rectángulo que se ajusta a la imagen actual. |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | Obtiene la fecha y hora en que la imagen del recurso fue modificada por última vez. |
| [get_original_options()](#get_original_options__30) | Obtiene las opciones basadas en la configuración del archivo original.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) método, se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) método como segundo parámetro. |
| [get_pixel(x, y)](#get_pixel_x_y_31) | Obtiene un píxel de la imagen.<br/>            Advertencia de rendimiento: Evite usar este método para iterar sobre todos los píxeles de la imagen, ya que puede provocar problemas de rendimiento significativos.<br/>            Para una manipulación de píxeles más eficiente, use el método `LoadArgb32Pixels` para obtener todo el arreglo de píxeles simultáneamente. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | Obtiene una altura proporcional. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | Obtiene un ancho proporcional. |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | Transformación de una imagen a su representación en escala de grises |
| [load(file_path)](#load_file_path_35) | Carga una nueva imagen desde el archivo especificado. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Carga una nueva imagen desde el archivo especificado. |
| [load(stream)](#load_stream_37) | Carga una nueva imagen desde el flujo especificado. |
| [load(stream, load_options)](#load_stream_load_options_38) | Carga una nueva imagen desde el flujo especificado. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | Carga píxeles ARGB de 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | Carga píxeles ARGB de 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | Carga píxeles en formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | Carga píxeles en formato CMYK.<br/>            Este método está obsoleto. Por favor, use de manera más eficaz el método [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | Carga píxeles ARGB de 32 bits parcialmente (por bloques). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | Carga píxeles parcialmente por paquetes. |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | Carga píxeles. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | Carga datos sin procesar. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | Carga datos sin procesar. |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | Fusiona la capa con la capa especificada |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | Lee toda la línea de escaneo mediante el índice de línea de escaneo especificado. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | Redimensiona la imagen. Se utiliza el [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) predeterminado. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | Redimensiona la imagen. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | Redimensiona la imagen. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | Redimensiona la altura proporcionalmente. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | Redimensiona la altura proporcionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | Redimensiona el ancho proporcionalmente. Se utiliza el [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) predeterminado. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | Redimensiona el ancho proporcionalmente. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | Redimensiona el ancho proporcionalmente. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | Rota la imagen alrededor del centro. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | Rota, voltea o rota y voltea la imagen. |
| save() | Guarda los datos de la imagen en el flujo subyacente. |
| [save(file_path)](#save_file_path_62) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(file_path, options)](#save_file_path_options_63) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado. |
| [save(file_path, over_write)](#save_file_path_over_write_65) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| [save(stream)](#save_stream_66) | Guarda los datos del objeto en el flujo especificado. |
| [save(stream, options_base)](#save_stream_options_base_67) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | Guarda los píxeles ARGB de 32 bits. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | Guarda píxeles (método específico de formato). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | Guarda los datos sin procesar. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | Establece un píxel ARGB de 32 bits de la imagen para la posición especificada. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | Establece la paleta de la imagen. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | Establece un píxel de la imagen para la posición especificada. |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__75) | Crea una copia superficial de la capa actual.<br/>            Por favor <see href=\"https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx\" /> para la explicación. |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | Escribe la línea de escaneo completa en el índice de línea de escaneo especificado. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | Escribe la línea de escaneo completa en el índice de línea de escaneo especificado. |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

Inicializa una nueva instancia de la clase [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). Constructor para inicialización perezosa.

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

Inicializa una nueva instancia de la clase [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) a partir de matrices de bytes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Los límites de la capa. |
| red_bytes | byte | Los bytes rojos. |
| green_bytes | byte | Los bytes verdes. |
| blue_bytes | byte | Los bytes azules. |
| name | string | El nombre de la capa. |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

Inicializa una nueva instancia de la clase [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | La imagen. |
| dispose_image | bool | si se establece en <c>true</c> [descartar imagen]. |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

Inicializa una nueva instancia de la clase [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo de imagen |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

Agrega la máscara a la capa actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | La máscara de capa. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

Ajuste de brillo para la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brillo | int | Valor de brillo. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

Contraste de imagen

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| contraste | float | Valor de contraste (en rango [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

Corrección gamma de una imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gamma | float | Coeficiente gamma para los canales rojo, verde y azul |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Corrección gamma de una imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gamma_red | float | Coeficiente gamma para el canal rojo |
| gamma_green | float | Coeficiente gamma para el canal verde |
| gamma_blue | float | Coeficiente gamma para el canal azul |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brightness_difference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarización de una imagen usando el algoritmo de umbral adaptativo de Bradley mediante el umbralado de imagen integral

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| brightness_difference | double | La diferencia de brillo entre el píxel y el promedio de una ventana de s x s píxeles centrada en este píxel. |
| window_size | int | El tamaño de la ventana de s x s píxeles centrada en este píxel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binarización de una imagen con umbral predefinido

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| threshold | byte | Valor de umbral. Si el valor gris correspondiente de un píxel es mayor que el umbral, se le asignará un valor de 255, de lo contrario 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


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


### Method: can_load(stream)  [static] {#can_load_stream_11}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


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


### Method: can_save(options) {#can_save_options_13}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


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


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

Recortando la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

Realiza tramado en la imagen actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | El método de tramado. |
| bits_count | int | El recuento final de bits para el tramado. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


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

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

Dibuja la imagen en la capa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | La ubicación. |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | La imagen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


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


### Method: get_default_options(args) {#get_default_options_args_21}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtiene la matriz predeterminada de píxeles usando el cargador parcial de píxeles.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que obtener píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | El cargador parcial de píxeles. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


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


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

Obtiene las opciones basadas en la configuración del archivo original.<br/>            Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios.<br/>            Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) método, se producirá una imagen PNG de salida con 8 bits por píxel.<br/>            Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas<br/>            al [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) método como segundo parámetro.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones basadas en la configuración del archivo original. |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


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


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carga píxeles ARGB de 32 bits parcialmente (por bloques).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que cargar píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | El cargador parcial de píxeles. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carga píxeles parcialmente por paquetes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo deseado. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | El cargador de píxeles. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


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

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

Fusiona la capa con la capa especificada

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | La capa en la que fusionar. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

Redimensiona la imagen. Se utiliza el [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) predeterminado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| new_height | int | La nueva altura. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Tipo de redimensionamiento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensiona la altura proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_height | int | La nueva altura. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Los ajustes de redimensionamiento de la imagen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

Redimensiona el ancho proporcionalmente. Se utiliza el [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) predeterminado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Tipo de redimensionamiento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensiona el ancho proporcionalmente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_width | int | El nuevo ancho. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Los ajustes de redimensionamiento de la imagen. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rota la imagen alrededor del centro.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ángulo | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |
| resize_proportionally | bool | si se establece en <c>true</c> el tamaño de su imagen cambiará según las proyecciones del rectángulo girado (puntos de esquina); en otro caso, las dimensiones permanecerán sin cambios y solo se rotará el contenido interno de la imagen. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Color del fondo. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

Rota, voltea o rota y voltea la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | El tipo de volteo de rotación. |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

Guarda los datos del objeto en la ubicación de archivo especificada en el formato de archivo especificado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

Guarda los datos del objeto en la ubicación de archivo especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta del archivo donde guardar los datos del objeto. |
| over_write | bool | si se establece en <c>true</c> sobrescribirá el contenido del archivo, de lo contrario se producirá una anexión. |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

Guarda los datos del objeto en el flujo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo para guardar los datos del objeto. |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

Guarda los datos de la imagen en el flujo especificado en el formato de archivo especificado según las opciones de guardado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo para guardar los datos de la imagen. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Las opciones de guardado. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Guarda los píxeles ARGB de 32 bits.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo donde guardar los píxeles. |
| pixels | int | La matriz de píxeles ARGB de 32 bits. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

Guarda píxeles (método específico de formato).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo donde guardar los píxeles. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | La matriz de píxeles ARGB de 32 bits. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

Establece la paleta de la imagen.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La paleta a establecer. |
| update_colors | bool | si se establece en <c>true</c> los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecen sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas correspondientes en la paleta. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


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

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

Crea una copia superficial de la capa actual.<br/>            Por favor <see href=\"https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx\" /> para la explicación.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Una copia superficial de la capa actual. |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Escribe la línea de escaneo completa en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| argb_32_pixels | int | La matriz de colores ARGB de 32 bits para escribir. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

Escribe la línea de escaneo completa en el índice de línea de escaneo especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int | Índice basado en cero de la línea de escaneo. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | La matriz de colores de píxeles para escribir. |

