---
title: TiffOptions
second_title: Referencia de API de Aspose.PSD para .NET
description: Las opciones de formato de archivo tiff. Tenga en cuenta que las etiquetas de ancho y alto se sobrescribirán en la creación de la imagen por los parámetros de ancho y alto por lo que no es necesario especificarlas directamente. Tenga en cuenta que muchas opciones devuelven un valor predeterminado pero eso no significa que esta opción se establece explícitamente como un valor de etiqueta. Para verificar que la etiqueta está presente use la propiedad Tags o el método IsTagPresent correspondiente.
type: docs
weight: 4870
url: /es/net/aspose.psd.imageoptions/tiffoptions/
---
## TiffOptions class

Las opciones de formato de archivo tiff. Tenga en cuenta que las etiquetas de ancho y alto se sobrescribirán en la creación de la imagen por los parámetros de ancho y alto, por lo que no es necesario especificarlas directamente. Tenga en cuenta que muchas opciones devuelven un valor predeterminado, pero eso no significa que esta opción se establece explícitamente como un valor de etiqueta. Para verificar que la etiqueta está presente, use la propiedad Tags o el método IsTagPresent correspondiente.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Inicializa una nueva instancia del[`TiffOptions`](../tiffoptions) clase. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Inicializa una nueva instancia del[`TiffOptions`](../tiffoptions) clase. Por defecto se usa la convención little endian. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Inicializa una nueva instancia del[`TiffOptions`](../tiffoptions) clase. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Inicializa una nueva instancia del[`TiffOptions`](../tiffoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage) { get; set; } | Obtiene o establece la opción de almacenamiento alfa. Opciones distintas aUnspecified se utilizan cuando hay más de 3[`SamplesPerPixel`](./samplesperpixel) definido. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist) { get; set; } | Obtiene o establece el artista. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel) { get; } | Obtiene los bits por píxel. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample) { get; set; } | Obtiene o establece los bits por muestra. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Obtiene o establece la sugerencia de tamaño de búfer que se define como el tamaño máximo permitido para todos los búferes internos. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder) { get; set; } | Obtiene o establece un valor que indica el orden de bytes tiff. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap) { get; set; } | Obtiene o establece el mapa de colores. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality) { get; set; } | Obtiene o establece la calidad de la imagen comprimida. Se utiliza con la compresión Jpeg. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression) { get; set; } | Obtiene o establece la compresión. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright) { get; set; } | Obtiene o establece el copyright. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime) { get; set; } | Obtiene o establece la fecha y la hora. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se usará para dibujar texto al exportar a ráster, si la fuente de capa existente en el archivo PSD no se presenta en el sistema). Para tomar el nombre correcto de la fuente predeterminada, se puede usar el siguiente fragmento de código : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familias = col.Familias; string defaultFontName = familias[0].Nombre; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname) { get; set; } | Obtiene o establece el nombre del documento. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd) { get; } | Obtiene o establece el puntero a EXIF IFD. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options) { get; set; } | Obtiene o establece las opciones de fax t4. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard) { get; set; } | Obtiene o establece el archivo TIFF estándar. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder) { get; set; } | Obtiene o establece el orden de llenado de bits de byte. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Obtiene o establece un valor que indica si [fotograma completo]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints) { get; set; } | Obtiene o establece las sugerencias de medios tonos. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile) { get; set; } | Obtiene o establece el flujo de perfil Icc. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription) { get; set; } | Obtiene o establece la descripción de la imagen. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength) { get; set; } | Obtiene o establece la longitud de la imagen. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth) { get; set; } | Obtiene o establece el ancho de la imagen. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames) { get; set; } | Obtiene o establece los nombres de las tintas. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Obtiene un valor que indica si las muestras adicionales están presentes. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled) { get; } | Obtiene un valor que indica si la imagen está en mosaico. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid) { get; } | Obtiene un valor que indica si el[`TiffOptions`](../tiffoptions) han sido configurados correctamente. Utilice el método Validate para encontrar el motivo del error. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Obtiene o establece el valor de muestra máximo. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Obtiene o establece el valor de muestra mínimo. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Las opciones multipágina |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation) { get; set; } | Obtiene o establece la orientación. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename) { get; set; } | Obtiene o establece el nombre de la página. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber) { get; set; } | Obtiene o establece la etiqueta del número de página. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette) { get; set; } | Obtiene o establece la paleta de colores. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric) { get; set; } | Obtiene o establece la fotométrica. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Obtiene o establece la configuración planar. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor) { get; set; } | Obtiene o establece el predictor para la compresión LZW. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Obtiene o establece un valor que indica si los componentes se deben premultiplicar. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Obtiene o establece el controlador de eventos de progreso. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Obtiene o establece la configuración de resolución. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit) { get; set; } | Obtiene o establece la unidad de resolución. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Obtiene o establece las filas por tira. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat) { get; set; } | Obtiene o establece el formato de muestra. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel) { get; } | Obtiene las muestras por píxel. Para cambiar el valor de esta propiedad utilice el[`BitsPerSample`](./bitspersample) establecedor de propiedades. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Obtiene o establece el fabricante del escáner. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel) { get; set; } | Obtiene o establece el modelo de escáner. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Obtiene o establece el valor de muestra máximo. El valor tiene un tipo de campo que coincide mejor con los datos de muestra (tipo Byte, Corto o Largo). |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Obtiene o establece el valor de muestra mínimo. El valor tiene un tipo de campo que coincide mejor con los datos de muestra (tipo Byte, Corto o Largo). |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype) { get; set; } | Obtiene o establece el tipo de software. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Obtiene o establece la fuente para crear la imagen en. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Obtiene o establece los recuentos de bytes de tira. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets) { get; set; } | Obtiene o establece los desplazamientos de la tira. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype) { get; set; } | Obtiene o establece una indicación general del tipo de datos contenidos en este subfile. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags) { get; set; } | Obtiene o establece las etiquetas. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter) { get; set; } | Obtiene o establece la impresora de destino. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding) { get; set; } | Obtiene o establece el umbral. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Obtiene o establece los recuentos de bytes de mosaico. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength) { get; set; } | Obtiene ot establece la longitud del mosaico. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets) { get; set; } | Obtiene o establece los desplazamientos de mosaico. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth) { get; set; } | Obtiene ot establece el ancho del mosaico. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages) { get; } | Obtiene el total de páginas. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount) { get; } | Obtiene el recuento de etiquetas válidas. Este no es el recuento total de etiquetas, sino el número de etiquetas que se pueden conservar. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Obtiene o establece las opciones de rasterización de vectores. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata) { get; set; } | Obtiene o establece el contenedor de metadatos XMP. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor) { get; set; } | Obtiene o establece el autor de la imagen, que utiliza Windows Explorer. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment) { get; set; } | Obtiene o establece un comentario en la imagen, que utiliza Windows Explorer. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords) { get; set; } | Obtiene o establece la imagen del sujeto, que utiliza Windows Explorer. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition) { get; set; } | Obtiene o establece la posición x. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject) { get; set; } | Obtiene o establece información sobre la imagen, que utiliza Windows Explorer. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle) { get; set; } | Obtiene o establece información sobre la imagen, que utiliza Windows Explorer. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution) { get; set; } | Obtiene o establece la resolución x. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Obtiene o establece los Coeficientes YCbCr. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Obtiene o establece los factores de submuestreo para el fotométrico YCbCr. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition) { get; set; } | Obtiene o establece la posición y. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution) { get; set; } | Obtiene o establece la resolución y. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag)(TiffDataType) | Agrega una nueva etiqueta. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Agrega las etiquetas. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Clona esta instancia. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina la instancia actual. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Obtiene la instancia de la etiqueta por tipo. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent)(TiffTags) | Determina si la etiqueta está presente en las opciones o no. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag)(TiffTags) | Elimina la etiqueta. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate)() | Valida si las opciones tienen una combinación válida de etiquetas |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Obtiene el recuento de etiquetas válidas. |

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

Estos ejemplos hacen uso de las clases GraphicsPath y Graphics para crear y manipular figuras en una superficie de imagen. El ejemplo crea una nueva imagen y dibuja rutas con la ayuda de la clase GraphicsPath. Al final, se llama al método DrawPath expuesto por la clase Graphics para representar las rutas en la superficie. Finalmente, la imagen se exporta a formato de archivo Tiff.

```csharp
[C#]

//Crear una instancia de Imagen 
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crear e inicializar una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Borrar superficie gráfica
    graphics.Clear(Color.Wheat);

    //Crear una instancia de la clase GraphicsPath
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Crear una instancia de la clase Figure
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Agregar formas al objeto Figura
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Agregar objeto Figura a GraphicsPath
    graphicspath.AddFigure(figure);

    //Dibujar ruta con objeto Pluma de color Negro
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //Crear una instancia de TiffOptions y establecer sus diversas propiedades
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // guarda todos los cambios.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### Ver también

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* espacio de nombres [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
