---
title: "Clase GifOptions"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.ImageOptions.GifOptions. Las opciones de creación del formato de archivo gif"
type: docs
weight: 5300
url: /es/net/aspose.psd.imageoptions/gifoptions/
---
{{< psd/tize >}}
## GifOptions class

Las opciones de creación del formato de archivo gif.

```csharp
public class GifOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | Inicializa una nueva instancia de la clase `GifOptions`. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | Inicializa una nueva instancia de la clase `GifOptions`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | Obtiene o establece el índice de color de fondo del GIF. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | Obtiene o establece la resolución de color del GIF. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | Obtiene o establece un valor que indica si se aplica la corrección de paleta. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtiene o establece un valor que indica si [full frame]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | Obtiene o establece un valor que indica si el GIF tiene tráiler. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | True si la imagen debe estar entrelazada. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | Obtiene o establece un valor que indica si las entradas de la paleta están ordenadas. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | Obtiene o establece la diferencia máxima de píxeles permitida. Si es mayor que cero, se utilizará compresión con pérdida. El valor recomendado para una compresión con pérdida óptima es 80. 30 es una compresión muy ligera, 200 es pesada. Funciona mejor cuando solo se introduce poca pérdida, y debido a la limitación del algoritmo de compresión, niveles de pérdida muy altos no proporcionarán tanto beneficio. El rango de valores permitidos es [0, 1000]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Obtiene o establece la paleta de colores. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | Obtiene o establece la relación de aspecto de píxel del GIF. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtiene o establece el controlador del evento de progreso. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Obtiene o establece la configuración de resolución. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtiene o establece la fuente donde crear la imagen. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtiene o establece las opciones de rasterización vectorial. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clona esta instancia. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |

## Ejemplos

Este ejemplo muestra el uso de diferentes clases del espacio de nombres SaveOptions para propósitos de exportación. Una imagen de tipo Psd se carga en una instancia de Image y luego se exporta a varios formatos.

```csharp
[C#]

//Cargar una imagen existente en una instancia de la clase Image
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Exportar al formato de archivo BMP usando las opciones predeterminadas
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //Exportar al formato de archivo JPEG usando las opciones predeterminadas
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //Exportar al formato de archivo JPEG 2000 usando las opciones predeterminadas
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //Exportar al formato de archivo PNG usando las opciones predeterminadas
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //Exportar al formato de archivo TIFF usando las opciones predeterminadas
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


