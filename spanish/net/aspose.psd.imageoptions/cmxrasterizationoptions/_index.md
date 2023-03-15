---
title: Class CmxRasterizationOptions
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.ImageOptions.CmxRasterizationOptions clase. las opciones del exportador CMX.
type: docs
weight: 4800
url: /es/net/aspose.psd.imageoptions/cmxrasterizationoptions/
---
## CmxRasterizationOptions class

las opciones del exportador CMX.

```csharp
public class CmxRasterizationOptions : VectorRasterizationOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CmxRasterizationOptions](cmxrasterizationoptions/)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | Obtiene o establece un color de fondo. |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | Obtiene o establece el borde X. |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | Obtiene o establece el borde Y. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | Obtiene o establece un valor que indica si centrar el dibujo. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se usará para dibujar texto al exportar a ráster, si la fuente de capa existente en el archivo PSD no se presenta en el sistema). Para tomar el nombre correcto de la fuente predeterminada, se puede usar el siguiente fragmento de código : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familias = col.Familias; string defaultFontName = familias[0].Nombre; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | Obtiene o establece un color de primer plano. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Las opciones multipágina |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | Obtiene o establece la altura de la página. |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | Obtiene o establece el tamaño de la página. |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | Obtiene o establece el ancho de página. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtiene o establece la paleta de colores. |
| [Positioning](../../aspose.psd.imageoptions/cmxrasterizationoptions/positioning/) { get; set; } | Obtiene o establece el posicionamiento. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtiene o establece la configuración de resolución. |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | Obtiene o establece el modo de suavizado. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | Obtiene o establece la sugerencia de representación de texto. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clona esta instancia. |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | Copias a. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina la instancia actual. |

### Ver también

* class [VectorRasterizationOptions](../vectorrasterizationoptions/)
* espacio de nombres [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* asamblea [Aspose.PSD](../../)


