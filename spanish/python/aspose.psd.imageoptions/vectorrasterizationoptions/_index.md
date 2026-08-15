---
title: "Clase VectorRasterizationOptions"
type: docs
weight: 150
url: /es/python-net/aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.VectorRasterizationOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece un color de fondo. |
| border_x | float | r/w | Obtiene o establece el borde X. |
| border_y | float | r/w | Obtiene o establece el borde Y. |
| buffer_size_hint | int | r/w | Obtiene o establece la sugerencia de tamaño del búfer, que se define como el tamaño máximo permitido para todos los búferes internos. |
| center_drawing | bool | r/w | Obtiene o establece un valor que indica si se centra el dibujo. |
| default_replacement_font | string | r/w | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema).<br/>            Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Obtiene un valor que indica si esta instancia está descartada. |
| draw_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtiene o establece un color de primer plano. |
| full_frame | bool | r/w | Obtiene o establece un valor que indica si [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Las opciones multipágina |
| page_height | float | r/w | Obtiene o establece la altura de la página. |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Obtiene o establece el tamaño de la página. |
| page_width | float | r/w | Obtiene o establece el ancho de la página. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtiene o establece la paleta de colores. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtiene o establece la configuración de resolución. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Obtiene o establece el modo de suavizado. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtiene o establece la fuente en la que crear la imagen. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Obtiene o establece la sugerencia de renderizado de texto. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtiene o establece las opciones de rasterización vectorial. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtiene o establece el contenedor de metadatos XMP. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copia a. |


### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Devuelve una copia superficial de esta instancia |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copia a.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | Las opciones de rasterización vectorial. |

