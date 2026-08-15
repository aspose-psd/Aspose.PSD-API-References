---
title: "Clase JpegOptions"
type: docs
weight: 60
url: /es/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Inicializa una nueva instancia de la clase [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Inicializa una nueva instancia de la clase [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | Obtiene o establece bits por canal para imagen jpeg sin pérdida. Ahora soportamos de 2 a 8 bits por canal. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | El perfil de color CMYK de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar emparejado con RGBColorProfile para una conversión de color correcta. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Obtiene o establece el tipo de color para la imagen jpeg. |
| comment | string | r/w | Obtiene o establece el comentario del archivo jpeg. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | Obtiene o establece el tipo de compresión. |
| default_memory_allocation_limit | int | r/w | Obtiene o establece el límite de asignación de memoria predeterminado. |
| default_replacement_font | string | r/w | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema).<br/>            Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | Obtenga o establezca el contenedor de datos exif |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| horizontal_sampling | byte | r/w | Obtiene o establece los submuestreos horizontales para cada componente. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | Obtiene o establece el jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Obtiene o establece el límite de diferencia JPEG-LS para codificación casi sin pérdida (parámetro NEAR de la especificación JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Obtiene o establece el modo de entrelazado JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Obtiene o establece los parámetros predefinidos JPEG-LS. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtiene o establece la paleta de colores. |
| preblend_alpha_if_present | bool | r/w | Obtiene o establece un valor que indica si los componentes rojo, verde y azul deben mezclarse con un color de fondo, si el canal alfa está presente. |
| quality | int | r/w | Obtiene o establece la calidad de la imagen. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | Obtiene o establece la configuración del optimizador RD. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtiene o establece la configuración de resolución. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | Obtiene o establece la unidad de resolución. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | El perfil de color RGB de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar emparejado con CMYKColorProfile para una conversión de color correcta. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | Obtiene o establece el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits. <see cref="P:JpegOptions.BitsPerChannel" /> |
| scaled_quality | int | r | La calidad escalada. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| vertical_sampling | byte | r/w | Obtiene o establece los submuestreos verticales para cada componente. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Inicializa una nueva instancia de la clase [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Inicializa una nueva instancia de la clase [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | Las opciones JPEG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Devuelve una copia superficial de esta instancia |


