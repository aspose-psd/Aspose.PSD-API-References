---
title: "Clase TiffOptions"
type: docs
weight: 130
url: /es/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Inicializa una nueva instancia de la clase [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Por defecto se usa la convención de little endian. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Inicializa una nueva instancia de la clase [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Inicializa una nueva instancia de la clase [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Inicializa una nueva instancia de la clase [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Obtiene o establece la opción de almacenamiento alfa. Las opciones distintas de [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            se usan cuando hay más de 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) definidos. |
| artist | string | r/w | Obtiene o establece el artista. |
| bits_per_pixel | int | r | Obtiene los bits por píxel. |
| bits_per_sample | ushort | r/w | Obtiene o establece los bits por muestra. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Obtiene o establece un valor que indica el orden de bytes del tiff. |
| color_map | ushort | r/w | Obtiene o establece el mapa de colores. |
| compressed_quality | int | r/w | Obtiene o establece la calidad de la imagen comprimida.<br/>            Se usa con la compresión Jpeg. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Obtiene o establece la compresión. |
| copyright | string | r/w | Obtiene o establece el copyright. |
| date_time | string | r/w | Obtiene o establece la fecha y hora. |
| default_memory_allocation_limit | int | r/w | Obtiene o establece el límite de asignación de memoria predeterminado. |
| default_replacement_font | string | r/w | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema).<br/>            Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| document_name | string | r/w | Obtiene o establece el nombre del documento. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Obtiene o establece el puntero al EXIF IFD. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Obtiene o establece las opciones fax t4. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Obtiene o establece el estándar de archivo TIFF. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Obtiene o establece el orden de relleno de bits de byte. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| half_tone_hints | ushort | r/w | Obtiene o establece las sugerencias de semitono. |
| image_description | string | r/w | Obtiene o establece la descripción de la imagen. |
| image_length | uint | r/w | Obtiene o establece la longitud de la imagen. |
| image_width | uint | r/w | Obtiene o establece el ancho de la imagen. |
| ink_names | string | r/w | Obtiene o establece los nombres de tinta. |
| is_extra_samples_present | bool | r | Obtiene un valor que indica si las muestras extra están presentes. |
| is_tiled | bool | r | Obtiene un valor que indica si la imagen está en mosaico. |
| is_valid | bool | r | Obtiene un valor que indica si las [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) han sido configuradas correctamente. Utilice el método Validate para encontrar la razón del error. |
| max_sample_value | ushort | r/w | Obtiene o establece el valor máximo de muestra. |
| min_sample_value | ushort | r/w | Obtiene o establece el valor mínimo de muestra. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Las opciones multipágina |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Obtiene o establece la orientación. |
| page_name | string | r/w | Obtiene o establece el nombre de página. |
| page_number | ushort | r/w | Obtiene o establece la etiqueta del número de página. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtiene o establece la paleta de colores. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Obtiene o establece el fotométrico. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Obtiene o establece la configuración planar. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Obtiene o establece el predictor para la compresión LZW. |
| premultiply_components | bool | r/w | Obtiene o establece un valor que indica si los componentes deben estar premultiplicados. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtiene o establece la configuración de resolución. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Obtiene o establece la unidad de resolución. |
| rows_per_strip | uint | r/w | Obtiene o establece las filas por tira. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Obtiene o establece el formato de muestra. |
| samples_per_pixel | ushort | r | Obtiene las muestras por píxel. Para cambiar el valor de esta propiedad, utilice el setter de la propiedad [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Obtiene o establece el fabricante del escáner. |
| scanner_model | string | r/w | Obtiene o establece el modelo del escáner. |
| smax_sample_value | uint | r/w | Obtiene o establece el valor máximo de muestra. El valor tiene un tipo de campo que coincide mejor con los datos de muestra (tipo Byte, Short o Long). |
| smin_sample_value | uint | r/w | Obtiene o establece el valor mínimo de muestra. El valor tiene un tipo de campo que mejor coincide con los datos de muestra (Byte, Short o Long). |
| software_type | string | r/w | Obtiene o establece el tipo de software. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| strip_byte_counts | uint | r/w | Obtiene o establece los recuentos de bytes de la tira. |
| strip_offsets | uint | r/w | Obtiene o establece los desplazamientos de la tira. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtiene o establece las etiquetas. |
| target_printer | string | r/w | Obtiene o establece la impresora objetivo. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Obtiene o establece el umbralado. |
| tile_byte_counts | uint | r/w | Obtiene o establece los recuentos de bytes de los mosaicos. |
| tile_length | uint | r/w | Obtiene ot establece la longitud del mosaico. |
| tile_offsets | uint | r/w | Obtiene o establece los desplazamientos del mosaico. |
| tile_width | uint | r/w | Obtiene ot establece el ancho del mosaico. |
| total_pages | ushort | r | Obtiene el total de páginas. |
| valid_tag_count | int | r | Obtiene el recuento de etiquetas válidas. Esto no es el recuento total de etiquetas, sino el número de etiquetas que pueden preservarse. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
| xp_author | string | r/w | Obtiene o establece el autor de la imagen, que es usado por el Explorador de Windows. |
| xp_comment | string | r/w | Obtiene o establece el comentario de la imagen, que es usado por el Explorador de Windows. |
| xp_keywords | string | r/w | Obtiene o establece el asunto de la imagen, que es usado por el Explorador de Windows. |
| xp_subject | string | r/w | Obtiene o establece información sobre la imagen, que es usado por el Explorador de Windows. |
| xp_title | string | r/w | Obtiene o establece información sobre la imagen, que es usado por el Explorador de Windows. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la posición x. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece los coeficientes YCbCr. |
| y_cb_cr_subsampling | ushort | r/w | Obtiene o establece los factores de submuestreo para la fotométrica YCbCr. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la posición y. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtiene o establece la resolución y. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Añade una nueva etiqueta. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Añade las etiquetas. |
| [clone()](#clone__3) | Clona esta instancia. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Obtiene la instancia de la etiqueta por tipo. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Obtiene el recuento de etiquetas válidas. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Determina si la etiqueta está presente en las opciones o no. |
| [remove_tag(tag)](#remove_tag_tag_7) | Elimina la etiqueta. |
| validate() | Valida si las opciones tienen una combinación válida de etiquetas. |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Por defecto se usa la convención de little endian.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | El formato de archivo TIFF esperado. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | El formato de archivo TIFF esperado. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | El orden de bytes del formato de archivo TIFF a usar. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | Las opciones de las que copiar. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Inicializa una nueva instancia de la clase [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Las etiquetas con las que inicializar opciones. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Añade una nueva etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | La etiqueta para agregar. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Añade las etiquetas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Las etiquetas para agregar. |

### Method: clone() {#clone__3}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Devuelve una copia superficial de esta instancia |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Obtiene la instancia de la etiqueta por tipo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | La clave de la etiqueta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Instancia de la etiqueta si existe o null de lo contrario. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Obtiene el recuento de etiquetas válidas.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Las etiquetas a validar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El recuento de etiquetas válidas. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Determina si la etiqueta está presente en las opciones o no.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | El id de la etiqueta a comprobar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si la etiqueta está presente; de lo contrario, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Elimina la etiqueta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | La etiqueta a eliminar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | true si se eliminó correctamente |


