---
title: "Clase GifOptions"
type: docs
weight: 30
url: /es/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Inicializa una nueva instancia de la clase [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Inicializa una nueva instancia de la clase [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | Obtiene o establece el índice de color de fondo del GIF. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| color_resolution | byte | r/w | Obtiene o establece la resolución de color del GIF. |
| default_replacement_font | string | r/w | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema).<br/>            Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| do_palette_correction | bool | r/w | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| has_trailer | bool | r/w | Obtiene o establece un valor que indica si el GIF tiene trailer. |
| interlaced | bool | r/w | Verdadero si la imagen debe estar entrelazada. |
| is_palette_sorted | bool | r/w | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| max_diff | int | r/w | Obtiene o establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida.<br/>            El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada.<br/>            Funciona mejor cuando solo se introduce poca pérdida, y debido a la limitación del algoritmo de compresión, niveles de pérdida muy altos no proporcionarán tanto beneficio.<br/>            El rango de valores permitidos es [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtiene o establece la paleta de colores. |
| pixel_aspect_ratio | byte | r/w | Obtiene o establece la relación de aspecto de píxel del GIF. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtiene o establece la configuración de resolución. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Inicializa una nueva instancia de la clase [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Inicializa una nueva instancia de la clase [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | Las opciones del GIF. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Devuelve una copia superficial de esta instancia |


