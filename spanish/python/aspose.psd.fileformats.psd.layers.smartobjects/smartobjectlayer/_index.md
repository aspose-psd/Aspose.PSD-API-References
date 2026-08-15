---
title: "Clase SmartObjectLayer"
type: docs
weight: 10
url: /es/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---

**Summary:** Defines the SmartObjectLayer class that contains embedded in the PSD file or linked smart object in the external file.<br/>            With Smart Objects, you can:<br/>            Perform nondestructive transforms. You can scale, rotate, skew, distort, perspective transform, or warp a layer<br/>            without losing original image data or quality because the transforms don�t affect the original data.<br/>            Work with vector data, such as vector artwork from Illustrator, that otherwise would be rasterized.<br/>            Perform nondestructive filtering. You can edit filters applied to Smart Objects at any time.<br/>            Edit one Smart Object and automatically update all its linked instances.<br/>            Apply a layer mask that�s either linked or unlinked to the Smart Object layer.<br/>            Try various designs with low-resolution placeholder images that you later replace with final versions.<br/>            In Adobe� Photoshop�, you can embed the contents of an image into a PSD document.<br/>            More information is here: <see href="https://helpx.adobe.com/photoshop/using/create-smart-objects.html" /><br/>            A layer with an embedded smart object contains placed (PlLd) and SoLd resources with smart object properties.<br/>            The PlLd resource can be alone for PSD versions older then 10.<br/>            These resources contain UniqueId of the LiFdDataSource in the global Lnk2Resource with the embedded filename<br/>            and other parameters, including the embedded file contents in the original format as a byte array.

**Module:** [aspose.psd.fileformats.psd.layers.smartobjects](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Layer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SmartObjectLayer(stream)](#SmartObjectLayer_stream_1) | Inicializa una nueva instancia de la clase [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
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
| inferior | int | r/w |  |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtiene los límites del objeto. |
| buffer_size_hint | int | r/w |  |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w |    |
| channels_count | ushort | r |  |
| recorte | byte | r/w |  |
| container | [Image](/psd/python-net/aspose.psd/image) | r |    |
| content_type | [SmartObjectType](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjecttype) | r | Obtiene el tipo del contenido de la capa de objeto inteligente.<br/>            El contenido incrustado del objeto inteligente es el archivo de imagen sin procesar incrustado: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).<br/>            El contenido enlazado del objeto inteligente es el contenido sin procesar del archivo de imagen enlazado si está disponible: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            No admitimos la carga desde la Adobe� Photoshop� �� Graphics Library cuando [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) es verdadero.<br/>            Para archivos enlazados normales, primero usamos [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) para buscar el archivo de forma relativa<br/>            a la ruta de la imagen fuente [None](/psd/python-net/aspose.psd/datastreamsupporter/),<br/>            si no está disponible buscamos en [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/),<br/>            si tampoco, buscamos el archivo enlazado en el mismo directorio donde está nuestra imagen: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents | byte | r/w | Obtiene o establece el contenido de la capa de objeto inteligente.<br/>            El contenido incrustado del objeto inteligente es el archivo de imagen sin procesar incrustado: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) y sus propiedades.<br/>            El contenido enlazado del objeto inteligente es el contenido sin procesar del archivo de imagen enlazado si está disponible y sus propiedades: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            No admitimos la carga desde la Adobe� Photoshop� �� Graphics Library cuando [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) es verdadero.<br/>            Para archivos enlazados normales, primero usamos [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) para buscar el archivo de forma relativa<br/>            a la ruta de la imagen fuente [None](/psd/python-net/aspose.psd/datastreamsupporter/),<br/>            si no está disponible buscamos en [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/),<br/>            si tampoco, buscamos el archivo enlazado en el mismo directorio donde está nuestra imagen: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Obtiene o establece los límites del contenido del objeto inteligente. |
| contents_source | [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | r/w | Obtiene o establece la fuente del contenido del objeto inteligente. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r |    |
| display_name | string | r/w |  |
| disposed | bool | r |  |
| extra_length | int | r |  |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r |    |
| fill_opacity | int | r/w |  |
| filler | byte | r/w |  |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w |    |
| has_alpha | bool | r |  |
| has_background_color | bool | r/w |  |
| has_transparent_color | bool | r/w |  |
| altura | int | r | Obtiene la altura del objeto. |
| horizontal_resolution | double | r/w |  |
| image_opacity | float | r |  |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w |    |
| is_cached | bool | r |  |
| is_raw_data_available | bool | r | Obtiene un valor que indica si se admite la carga de datos sin procesar. |
| is_visible | bool | r/w |  |
| is_visible_in_group | bool | r |  |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w |    |
| layer_creation_date_time | datetime | r/w |  |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w |    |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w |    |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r |    |
| left | int | r/w |  |
| longitud | int | r |  |
| name | string | r/w | Obtiene o establece el nombre de la capa de texto. |
| opacity | byte | r/w |  |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w |    |
| premultiply_components | bool | r/w |  |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w |    |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r |    |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Obtiene la configuración actual de datos sin procesar. Nota: al usar esta configuración, los datos se cargan sin conversión. |
| raw_fallback_index | int | r/w |  |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w |    |
| raw_line_size | int | r |  |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w |    |
| right | int | r/w |  |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w |    |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Obtiene el tamaño del objeto. |
| smart_filters | [SmartFilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilters/) | r | Obtiene los filtros inteligentes. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Obtiene el proveedor de objetos inteligentes. |
| top | int | r/w |  |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| update_xmp_data | bool | r/w |  |
| use_palette | bool | r |  |
| use_raw_data | bool | r/w |  |
| vertical_resolution | double | r/w |  |
| warp_settings | [WarpSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.warp/warpsettings/) | r/w | Obtiene o establece los parámetros de Warp que se establecieron u obtuvieron del recurso (por defecto) |
| width | int | r | Obtiene el ancho del objeto. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w |    |
## **Methods**
| **Name** | **Descripción** |
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
| [convert_to_linked(linked_path)](#convert_to_linked_linked_path_6) | Convierte este objeto inteligente incrustado en un objeto inteligente vinculado. |
| [create(image_options, width, height)](#create_image_options_width_height_7) |    |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| dither(dithering_method, bits_count) |  |
| dither(dithering_method, bits_count, custom_palette) |  |
| draw_image(location, image) |  |
| [duplicate_layer()](#duplicate_layer__8) | Crea una nueva capa de objeto inteligente copiando esta.<br/>            Observe que para los objetos inteligentes incrustados la imagen incrustada se comparte.<br/>            Si desea copiar la imagen incrustada, use el método [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |
| embed_linked() | Incrusta el objeto inteligente vinculado en esta capa. |
| [export_contents(file_path)](#export_contents_file_path_9) | Exporta el contenido incrustado o vinculado a un archivo. |
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
| [load_contents(options)](#load_contents_options_32) | Obtiene el contenido de imagen incrustado o vinculado de la capa de objeto inteligente. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | Carga píxeles ARGB de 32 bits parcialmente (por bloques). |
| load_partial_pixels(desired_rectangle, pixel_loader) |  |
| [load_pixels(rectangle)](#load_pixels_rectangle_34) |    |
| load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) |  |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35) | Carga datos sin procesar. |
| merge_layer_to(layer_to_merge_into) |  |
| [new_smart_object_via_copy()](#new_smart_object_via_copy__36) | Crea una nueva capa de objeto inteligente copiando esta.<br/>            Reproduce la funcionalidad `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` de Adobe Photoshop.<br/>            Observe que solo está habilitada para objetos inteligentes incrustados porque la imagen incrustada también se copia.<br/>            Si desea compartir la imagen incrustada, use el método [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_37) |    |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_38) |    |
| [relink_to_file(linked_path)](#relink_to_file_linked_path_39) | Vuelve a vincular el objeto inteligente vinculado a un nuevo archivo.<br/>            No es necesario llamar al método UpdateModifiedContent después. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| [replace_contents(image)](#replace_contents_image_40) | Reemplaza el contenido del objeto inteligente incrustado en la capa de objeto inteligente. |
| [replace_contents(image, resolution)](#replace_contents_image_resolution_41) | Reemplaza el contenido del objeto inteligente incrustado en la capa de objeto inteligente. |
| [replace_contents(linked_path)](#replace_contents_linked_path_42) | Reemplaza el contenido con un archivo.<br/>            No es necesario llamar al método UpdateModifiedContent después. |
| [replace_contents(linked_path, resolution)](#replace_contents_linked_path_resolution_43) | Reemplaza el contenido con un archivo.<br/>            No es necesario llamar al método UpdateModifiedContent después. |
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
| update_modified_content() | Actualiza la caché de imágenes de la capa de objeto inteligente con el contenido modificado. |
| write_argb_32_scan_line(scan_line_index, argb_32_pixels) |  |
| write_scan_line(scan_line_index, pixels) |  |


### Constructor: SmartObjectLayer(stream) {#SmartObjectLayer_stream_1}


```
 SmartObjectLayer(stream) 
```

Inicializa una nueva instancia de la clase [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | El flujo de elementos |

### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool |  |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool |  |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool |  |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool |  |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool |  |


### Method: convert_to_linked(linked_path) {#convert_to_linked_linked_path_6}


```
 convert_to_linked(linked_path) 
```

Convierte este objeto inteligente incrustado en un objeto inteligente vinculado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| linked_path | string | La ruta vinculada. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |
| width | int |  |
| altura | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: duplicate_layer() {#duplicate_layer__8}


```
 duplicate_layer() 
```

Crea una nueva capa de objeto inteligente copiando esta.<br/>            Observe que para los objetos inteligentes incrustados la imagen incrustada se comparte.<br/>            Si desea copiar la imagen incrustada, use el método [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | La instancia clonada de [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: export_contents(file_path) {#export_contents_file_path_9}


```
 export_contents(file_path) 
```

Exporta el contenido incrustado o vinculado a un archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string | La ruta de archivo de exportación. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_10}


```
 get_argb_32_pixel(x, y) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int |  |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_11}


```
 get_default_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int |  |


### Method: get_default_options(args) {#get_default_options_args_12}


```
 get_default_options(args) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| args | object |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_13}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte |  |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_14}


```
 get_file_format(file_path) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_15}


```
 get_file_format(stream) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_16}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| pixels | int |  |
| width | int |  |
| altura | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_17}


```
 get_fitting_rectangle(rectangle, width, height) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| width | int |  |
| altura | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_18}


```
 get_modify_date(use_default) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| use_default | bool |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| datetime |  |


### Method: get_original_options() {#get_original_options__19}


```
 get_original_options() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_pixel(x, y) {#get_pixel_x_y_20}


```
 get_pixel(x, y) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) |  |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_21}


```
 get_proportional_height(width, height, new_width) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int |  |
| altura | int |  |
| new_width | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int |  |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_22}


```
 get_proportional_width(width, height, new_height) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int |  |
| altura | int |  |
| new_height | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int |  |


### Method: get_skew_angle() {#get_skew_angle__23}


```
 get_skew_angle() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_24}


```
 load(file_path) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_25}


```
 load(file_path, load_options) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream)  [static] {#load_stream_26}


```
 load(stream) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_27}


```
 load(stream, load_options) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_28}


```
 load_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int |  |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_29}


```
 load_argb_64_pixels(rectangle) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| long |  |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_30}


```
 load_cmyk_32_pixels(rectangle) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int |  |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_31}


```
 load_cmyk_pixels(rectangle) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) |  |


### Method: load_contents(options) {#load_contents_options_32}


```
 load_contents(options) 
```

Obtiene el contenido de imagen incrustado o vinculado de la capa de objeto inteligente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Las opciones. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | La instancia de objeto inteligente [Image](/psd/python-net/aspose.psd/image/) cargada. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carga píxeles ARGB de 32 bits parcialmente (por bloques).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | El rectángulo del que cargar píxeles. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | El cargador parcial de píxeles. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_34}


```
 load_pixels(rectangle) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35}


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

### Method: new_smart_object_via_copy() {#new_smart_object_via_copy__36}


```
 new_smart_object_via_copy() 
```

Crea una nueva capa de objeto inteligente copiando esta.<br/>            Reproduce la funcionalidad `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` de Adobe Photoshop.<br/>            Observe que solo está habilitada para objetos inteligentes incrustados porque la imagen incrustada también se copia.<br/>            Si desea compartir la imagen incrustada, use el método [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | La instancia clonada de [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_37}


```
 read_argb_32_scan_line(scan_line_index) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int |  |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_38}


```
 read_scan_line(scan_line_index) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: relink_to_file(linked_path) {#relink_to_file_linked_path_39}


```
 relink_to_file(linked_path) 
```

Vuelve a vincular el objeto inteligente vinculado a un nuevo archivo.<br/>            No es necesario llamar al método UpdateModifiedContent después.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| linked_path | string | La ruta vinculada. |

### Method: replace_contents(image) {#replace_contents_image_40}


```
 replace_contents(image) 
```

Reemplaza el contenido del objeto inteligente incrustado en la capa de objeto inteligente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen. |

### Method: replace_contents(image, resolution) {#replace_contents_image_resolution_41}


```
 replace_contents(image, resolution) 
```

Reemplaza el contenido del objeto inteligente incrustado en la capa de objeto inteligente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | La imagen. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | Los ajustes de resolución. Si es nulo, se usará la resolución de la imagen. |

### Method: replace_contents(linked_path) {#replace_contents_linked_path_42}


```
 replace_contents(linked_path) 
```

Reemplaza el contenido con un archivo.<br/>            No es necesario llamar al método UpdateModifiedContent después.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| linked_path | string | La ruta vinculada. |

### Method: replace_contents(linked_path, resolution) {#replace_contents_linked_path_resolution_43}


```
 replace_contents(linked_path, resolution) 
```

Reemplaza el contenido con un archivo.<br/>            No es necesario llamar al método UpdateModifiedContent después.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| linked_path | string | La ruta vinculada. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | Los ajustes de resolución. Si es nulo, se usará la resolución de la imagen. |

### Method: shallow_copy() {#shallow_copy__44}


```
 shallow_copy() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) |  |


### Method: to_bitmap() {#to_bitmap__45}


```
 to_bitmap() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


