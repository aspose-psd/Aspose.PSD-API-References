---
title: "Clase PsdOptions"
type: docs
weight: 100
url: /es/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Inicializa una nueva instancia de la clase [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(image)](#PsdOptions_image_2) | Inicializa una nueva instancia de la clase [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_3) | Inicializa una nueva instancia de la clase [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Obtiene o establece el color de fondo.<br/>            Puede verse bajo objetos transparentes. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| channel_bits_count | short | r/w | Obtiene o establece el recuento de bits por canal de color. |
| channels_count | short | r/w | Obtiene o establece el recuento de canales de color. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | Obtiene o establece el modo de color PSD. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | Obtiene o establece el método de compresión PSD. |
| default_replacement_font | string | r/w | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema).<br/>            Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtiene o establece la paleta de colores. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Obtiene o establece la versión del formato de archivo. Puede ser PSD o PSB. |
| refresh_image_preview_data | bool | r/w | Obtiene o establece un valor que indica si [refresh image preview data] - opción utilizada para maximizar la compatibilidad con otros visores de imágenes PSD.<br/>            Tenga en cuenta que el dibujo de capas de texto en el diseño final no es compatible con la plataforma Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | Obtiene o establece un valor que indica si - Eliminar el recurso global del motor de texto - Utilizado para algunos archivos PSD con capas de texto, en el único caso en que no pueden abrirse en Adobe Photoshop después del procesamiento (principalmente relacionado con capas de texto con fuentes ausentes).<br/>            Después de usar esta opción, el usuario debe realizar lo siguiente en el archivo abierto en Photoshop: Menú \"Text\" -&gt; \"Process absent fonts\". Después de esa operación todo el texto volverá a aparecer.<br/>            Tenga en cuenta que esta operación puede causar algunos cambios en el diseño final. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtiene o establece la configuración de resolución. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | Obtiene o establece los recursos PSD. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| update_metadata | bool | r/w | Obtiene o establece un valor que indica si [update metadata].<br/>            Si el valor es verdadero, los metadatos se actualizarán al guardar una imagen. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| version | int | r/w | Obtiene o establece la versión del archivo PSD. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtener o establecer el contenedor de datos XMP |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Inicializa una nueva instancia de la clase [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Inicializa una nueva instancia de la clase [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | La imagen. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Inicializa una nueva instancia de la clase [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | Las opciones. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Devuelve una copia superficial de esta instancia |


