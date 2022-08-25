---
title: JpegOptions
second_title: Referencia de API de Aspose.PSD para .NET
description: Las opciones de creación de formato de archivo jpeg.
type: docs
weight: 4770
url: /es/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

Las opciones de creación de formato de archivo jpeg.

```csharp
public class JpegOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [JpegOptions](jpegoptions#constructor)() | Inicializa una nueva instancia del[`JpegOptions`](../jpegoptions) clase. |
| [JpegOptions](jpegoptions#constructor_1)(JpegOptions) | Inicializa una nueva instancia del[`JpegOptions`](../jpegoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel) { get; set; } | Obtiene o establece bits por canal para una imagen jpeg sin pérdidas. Ahora admitimos de 2 a 8 bits por canal. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile) { get; set; } | El perfil de color CMYK de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar en pareja con RGBColorProfile para una conversión de color correcta. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype) { get; set; } | Obtiene o establece el tipo de color para la imagen jpeg. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment) { get; set; } | Obtiene o establece el comentario del archivo jpeg. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype) { get; set; } | Obtiene o establece el tipo de compresión. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se usará para dibujar texto al exportar a ráster, si la fuente de capa existente en el archivo PSD no se presenta en el sistema). Para tomar el nombre correcto de la fuente predeterminada, se puede usar el siguiente fragmento de código : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familias = col.Familias; string defaultFontName = familias[0].Nombre; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata) { get; set; } | Obtener o configurar el contenedor de datos exif |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling) { get; set; } | Obtiene o establece los submuestreos horizontales para cada componente. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif) { get; set; } | Obtiene o establece el jfif. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror) { get; set; } | Obtiene o establece el límite de diferencia de JPEG-LS para la codificación casi sin pérdidas (parámetro NEAR de la especificación JPEG-LS). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode) { get; set; } | Obtiene o establece el modo de intercalado JPEG-LS. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset) { get; set; } | Obtiene o establece los parámetros predeterminados de JPEG-LS. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent) { get; set; } | Obtiene o establece un valor que indica si los componentes rojo, verde y azul se deben mezclar con un color de fondo, si el canal alfa está presente. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality) { get; set; } | Obtiene o establece la calidad de la imagen. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings) { get; set; } | Obtiene o establece la configuración del optimizador de Escritorio remoto. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit) { get; set; } | Obtiene o establece la unidad de resolución. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile) { get; set; } | El perfil de color RGB de destino para imágenes jpeg CMYK. Úselo para guardar imágenes. Debe estar en pareja con CMYKColorProfile para una conversión de color correcta. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode) { get; set; } | Obtiene o establece el modo de redondeo de muestra para ajustar un valor de 8 bits a un valor de n bits.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality) { get; } | La calidad escalada. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling) { get; set; } | Obtiene o establece los submuestreos verticales para cada componente. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Clona esta instancia. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina la instancia actual. |

### Ejemplos

Este ejemplo demuestra el uso de Aspose.PSD para .Net API para convertir imágenes a formato Jpeg. Para lograr este objetivo, este ejemplo carga una imagen existente y luego la convierte al formato de archivo Jpeg.

```csharp
[C#]

//Crea una instancia de la clase de imagen y la inicializa con un archivo existente a través de la ruta del archivo
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Crear una instancia de la clase PsdOptions
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //Establezca la calidad al 50% para reducir el tamaño de la imagen de salida.
    jpegOptions.Quality = 50;

    //Establecer los comentarios exif.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //Guarde la imagen en la ubicación del disco con la configuración de JpegOptions suministrada
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

Este ejemplo demuestra el uso de System.IO.Stream para crear un nuevo archivo de imagen

```csharp
[C#]

//Crea una instancia de PsdOptions y establece sus diversas propiedades
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crear una instancia de System.IO.Stream
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//Definir la propiedad de origen para la instancia de PsdOptions
//El segundo parámetro booleano determina si el Stream se elimina una vez que sale del alcance
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Crea una instancia de Image y llama al método Create con PsdOptions como parámetro para inicializar el objeto Image   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //hacer un poco de procesamiento de imagen
}
```

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
