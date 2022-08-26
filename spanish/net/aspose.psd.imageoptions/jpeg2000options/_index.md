---
title: Jpeg2000Options
second_title: Referencia de API de Aspose.PSD para .NET
description: Las opciones de formato de archivo JPEG2000.
type: docs
weight: 4760
url: /es/net/aspose.psd.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Las opciones de formato de archivo JPEG2000.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Jpeg2000Options](jpeg2000options#constructor)() | Inicializa una nueva instancia del[`Jpeg2000Options`](../jpeg2000options) clase. |
| [Jpeg2000Options](jpeg2000options#constructor_1)(Jpeg2000Options) | Inicializa una nueva instancia del[`Jpeg2000Options`](../jpeg2000options) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec) { get; set; } | Obtiene o establece el códec JPEG2000 |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments) { get; set; } | Obtiene o establece los marcadores de comentario Jpeg. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios) { get; set; } | Obtiene o establece la matriz de relación de compresión. Diferentes relaciones de compresión para capas sucesivas. La tasa especificada para cada nivel de calidad es el factor de compresión deseado. Relaciones decrecientes requeridas. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se usará para dibujar texto al exportar a ráster, si la fuente de capa existente en el archivo PSD no se presenta en el sistema). Para tomar el nombre correcto de la fuente predeterminada, se puede usar el siguiente fragmento de código : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familias = col.Familias; string defaultFontName = familias[0].Nombre; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible) { get; set; } | Obtiene o establece un valor que indica si se usa la compresión DWT 9-7 irreversible (verdadero) o se usa compresión DWT 5-3 sin pérdidas (predeterminado). |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

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
