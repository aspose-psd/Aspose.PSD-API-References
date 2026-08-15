---
title: "Clase PngOptions"
type: docs
weight: 90
url: /es/python-net/aspose.psd.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Inicializa una nueva instancia de la clase [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/). |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Inicializa una nueva instancia de la clase [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | El nivel de compresión predeterminado. |
| bit_depth | byte | r/w | La profundidad de bits. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| color_type | [PngColorType](/psd/python-net/aspose.psd.fileformats.png/pngcolortype/) | r/w | Obtiene o establece el tipo de color. |
| compression_level | int | r/w | El nivel de compresión de la imagen png en el rango 0-9, donde 9 es la compresión máxima y 0 es modo de almacenamiento. |
| default_replacement_font | string | r/w | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema).<br/>            Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| filter_type | [PngFilterType](/psd/python-net/aspose.psd.fileformats.png/pngfiltertype/) | r/w | Obtiene o establece el tipo de filtro utilizado durante el proceso de guardado del archivo png. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtiene o establece la paleta de colores. |
| progressive | bool | r/w | Obtiene o establece un valor que indica si este [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) es progresivo. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtiene o establece la configuración de resolución. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Inicializa una nueva instancia de la clase [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/).

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Inicializa una nueva instancia de la clase [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| png_options | [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions) | Las opciones PNG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Devuelve una copia superficial de esta instancia |


