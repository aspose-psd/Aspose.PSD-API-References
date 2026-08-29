---
title: "Clase TiffOptions"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.ImageOptions.TiffOptions. Las opciones del formato de archivo tiff. Tenga en cuenta que las etiquetas de ancho y alto serán sobrescritas al crear la imagen por los parámetros de ancho y alto, por lo que no es necesario especificarlas directamente. Observe que muchas opciones devuelven un valor predeterminado, pero eso no significa que esta opción esté establecida explícitamente como un valor de etiqueta. Para verificar que la etiqueta está presente, use la propiedad Tags o el método correspondiente IsTagPresent."
type: docs
weight: 5430
url: /es/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

Las opciones del formato de archivo tiff. Tenga en cuenta que las etiquetas de ancho y alto se sobrescribirán al crear la imagen mediante los parámetros de ancho y alto, por lo que no es necesario especificarlas directamente. Tenga en cuenta que muchas opciones devuelven un valor predeterminado, pero eso no significa que esta opción esté establecida explícitamente como un valor de etiqueta. Para verificar que la etiqueta está presente, use la propiedad Tags o el método correspondiente IsTagPresent.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | Inicializa una nueva instancia de la clase `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | Inicializa una nueva instancia de la clase `TiffOptions`. Por defecto se utiliza la convención little endian. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | Inicializa una nueva instancia de la clase `TiffOptions`. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Inicializa una nueva instancia de la clase `TiffOptions`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | Obtiene o establece la opción de almacenamiento alfa. Se utilizan opciones distintas de Unspecified cuando hay más de 3 [`SamplesPerPixel`](./samplesperpixel/) definidos. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | Obtiene o establece el artista. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | Obtiene los bits por píxel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | Obtiene o establece los bits por muestra. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Obtiene o establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | Obtiene o establece un valor que indica el orden de bytes del tiff. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | Obtiene o establece el mapa de colores. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | Obtiene o establece la calidad de la imagen comprimida. Se usa con la compresión Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | Obtiene o establece la compresión. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | Obtiene o establece el copyright. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | Obtiene o establece la fecha y hora. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | Obtiene o establece el límite de asignación de memoria predeterminado. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | Obtiene o establece el nombre del documento. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | Obtiene o establece el puntero al EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | Obtiene o establece las opciones fax t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | Obtiene o establece el estándar de archivo TIFF. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | Obtiene o establece el orden de relleno de bits de byte. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Obtiene o establece un valor que indica si [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | Obtiene o establece las sugerencias de semitono. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Obtiene o establece el flujo del perfil Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | Obtiene o establece la descripción de la imagen. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | Obtiene o establece la longitud de la imagen. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | Obtiene o establece el ancho de la imagen. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | Obtiene o establece los nombres de tinta. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | Obtiene un valor que indica si están presentes las muestras extra. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | Obtiene un valor que indica si la imagen está en mosaico. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | Obtiene un valor que indica si el `TiffOptions` ha sido configurado correctamente. Utilice el método Validate para encontrar la razón del error. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | Obtiene o establece el valor máximo de muestra. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | Obtiene o establece el valor mínimo de muestra. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Las opciones multipágina |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | Obtiene o establece la orientación. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | Obtiene o establece el nombre de la página. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | Obtiene o establece la etiqueta del número de página. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | Obtiene o establece la paleta de colores. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | Obtiene o establece el fotométrico. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | Obtiene o establece la configuración planar. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | Obtiene o establece el predictor para la compresión LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | Obtiene o establece un valor que indica si los componentes deben ser premultiplicados. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Obtiene o establece el controlador del evento de progreso. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | Obtiene o establece la configuración de resolución. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | Obtiene o establece la unidad de resolución. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | Obtiene o establece las filas por tira. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | Obtiene o establece el formato de muestra. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | Obtiene las muestras por píxel. Para cambiar el valor de esta propiedad use el setter de la propiedad [`BitsPerSample`](./bitspersample/). |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | Obtiene o establece el fabricante del escáner. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | Obtiene o establece el modelo del escáner. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | Obtiene o establece el valor máximo de muestra. El valor tiene un tipo de campo que mejor coincide con los datos de muestra (tipo Byte, Short o Long). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | Obtiene o establece el valor mínimo de muestra. El valor tiene un tipo de campo que mejor coincide con los datos de muestra (tipo Byte, Short o Long). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | Obtiene o establece el tipo de software. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Obtiene o establece la fuente donde crear la imagen. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | Obtiene o establece los recuentos de bytes de la tira. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | Obtiene o establece los desplazamientos de la tira. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | Obtiene o establece las etiquetas. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | Obtiene o establece la impresora de destino. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | Obtiene o establece el umbralado. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | Obtiene o establece los recuentos de bytes del mosaico. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | Obtiene o establece la longitud del mosaico. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | Obtiene o establece los desplazamientos del mosaico. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | Obtiene o establece el ancho del mosaico. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | Obtiene el total de páginas. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | Obtiene el recuento de etiquetas válidas. Este no es el recuento total de etiquetas, sino el número de etiquetas que pueden preservarse. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Obtiene o establece las opciones de rasterización vectorial. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Obtiene o establece el autor de la imagen, que es usado por Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Obtiene o establece el comentario de la imagen, que es usado por Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Obtiene o establece el tema de la imagen, que es usado por Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | Obtiene o establece la posición x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Obtiene o establece información sobre la imagen, que es utilizada por el Explorador de Windows. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Obtiene o establece información sobre la imagen, que es utilizada por el Explorador de Windows. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | Obtiene o establece la resolución x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | Obtiene o establece los coeficientes YCbCr. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | Obtiene o establece los factores de submuestreo para la fotometría YCbCr. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | Obtiene o establece la posición y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | Obtiene o establece la resolución y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | Agrega una nueva etiqueta. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | Agrega las etiquetas. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Clona esta instancia. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | Obtiene la instancia de la etiqueta por tipo. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | Determina si la etiqueta está presente en las opciones o no. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | Elimina la etiqueta. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | Valida si las opciones tienen una combinación válida de etiquetas |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | Obtiene el recuento de etiquetas válidas. |

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

Este ejemplo utiliza las clases GraphicsPath y Graphics para crear y manipular Figuras en una superficie de Imagen. El ejemplo crea una nueva Imagen y dibuja rutas con la ayuda de la clase GraphicsPath. Al final se llama al método DrawPath expuesto por la clase Graphics para renderizar las rutas en la superficie. Finalmente, la imagen se exporta al formato de archivo Tiff.

```csharp
[C#]

//Crea una instancia de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Limpia la superficie Graphics
    graphics.Clear(Color.Wheat);

    //Crea una instancia de la clase GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Crea una instancia de la clase Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Agrega formas al objeto Figure
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Agrega el objeto Figure a GraphicsPath
    graphicspath.AddFigure(figure);

    //Dibuja la ruta con el objeto Pen de color negro
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Crea una instancia de TiffOptions y establece sus diversas propiedades
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // Guarda todos los cambios.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


