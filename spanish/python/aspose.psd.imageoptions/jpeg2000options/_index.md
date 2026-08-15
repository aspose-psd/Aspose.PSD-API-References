---
title: "Clase Jpeg2000Options"
type: docs
weight: 50
url: /es/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Inicializa una nueva instancia de la clase [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Inicializa una nueva instancia de la clase [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | Obtiene o establece el códec JPEG2000 |
| comments | string | r/w | Obtiene o establece los marcadores de comentarios Jpeg. |
| compression_ratios | int | r/w | Obtiene o establece la matriz de relaciones de compresión.<br/>            Diferentes relaciones de compresión para capas sucesivas.<br/>            La tasa especificada para cada nivel de calidad es el factor de compresión deseado.<br/>            Se requieren relaciones decrecientes. |
| default_replacement_font | string | r/w | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema).<br/>            Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| irreversible | bool | r/w | Obtiene o establece un valor que indica si se usa el DWT irreversible 9-7 (true) o se usa compresión DWT sin pérdida 5-3 (predeterminado). |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Las opciones multipágina |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtiene o establece la paleta de colores. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtiene o establece la configuración de resolución. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Inicializa una nueva instancia de la clase [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/)

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Inicializa una nueva instancia de la clase [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/)

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | Las opciones de formato de archivo Jpeg2000 de las que copiar la configuración. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Devuelve una copia superficial de esta instancia |


