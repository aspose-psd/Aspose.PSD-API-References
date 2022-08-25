---
title: GifOptions
second_title: Referencia de API de Aspose.PSD para .NET
description: Las opciones de creación de formato de archivo gif.
type: docs
weight: 4740
url: /es/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

Las opciones de creación de formato de archivo gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Inicializa una nueva instancia del[`GifOptions`](../gifoptions) clase. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Inicializa una nueva instancia del[`GifOptions`](../gifoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Obtiene o establece el índice de color de fondo del GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution) { get; set; } | Obtiene o establece la resolución de color del GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se usará para dibujar texto al exportar a ráster, si la fuente de capa existente en el archivo PSD no se presenta en el sistema). Para tomar el nombre correcto de la fuente predeterminada, se puede usar el siguiente fragmento de código : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familias = col.Familias; string defaultFontName = familias[0].Nombre; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer) { get; set; } | Obtiene o establece un valor que indica si el GIF tiene tráiler. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced) { get; set; } | Verdadero si la imagen debe estar entrelazada. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted) { get; set; } | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff) { get; set; } | Obtiene o establece la diferencia de píxeles máxima permitida. Si es mayor que cero, se usará compresión con pérdida. El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada. Funciona mejor cuando se introduce poca pérdida y debido a la limitación del algoritmo de compresión niveles de pérdida muy altos no darán tanta ganancia. El rango de valores permitidos es [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Obtiene o establece la proporción de aspecto de píxeles del GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Clona esta instancia. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina la instancia actual. |

### Ejemplos

Este ejemplo demuestra el uso de diferentes clases del espacio de nombres SaveOptions con fines de exportación. Una imagen de tipo Psd se carga en una instancia de Image y luego se exporta a varios formatos.

```csharp
[C#]

//Cargar una imagen existente en una instancia de la clase Imagen
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Exportar a formato de archivo BMP utilizando las opciones predeterminadas
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Exportar a formato de archivo JPEG usando las opciones predeterminadas
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Exportar a formato de archivo JPEG 2000 usando las opciones predeterminadas
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Exportar a formato de archivo PNG usando las opciones predeterminadas
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Exportar a formato de archivo TIFF usando las opciones predeterminadas
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* espacio de nombres [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
