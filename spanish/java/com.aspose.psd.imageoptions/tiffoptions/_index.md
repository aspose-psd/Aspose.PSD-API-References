---
title: "TiffOptions"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Las opciones del formato de archivo tiff."
type: docs
weight: 25
url: /es/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

Las opciones del formato de archivo tiff. Tenga en cuenta que las etiquetas de ancho y alto se sobrescribirán al crear la imagen mediante los parámetros de ancho y alto, por lo que no es necesario especificarlas directamente. Observe que muchas opciones devuelven un valor predeterminado, pero eso no significa que esta opción se establezca explícitamente como valor de etiqueta. Para verificar que la etiqueta está presente, use la propiedad Tags o el método correspondiente IsTagPresent.

¡ADVERTENCIA! nunca modifique las opciones tiff durante el guardado, ya que esto puede causar efectos secundarios y errores difíciles de encontrar. La siguiente línea se dejó especialmente comentada porque provocaba una determinación incorrecta del inicio de los datos. Las opciones pasadas no contenían spp (aunque las opciones no son correctas en tal caso, este escenario aún causa errores) y la siguiente línea provocó la adición de la etiqueta +spp y la etiqueta +bpp, y cuando las opciones se escribieron después de que los datos se completaran, sobrescribieron el inicio de los datos para el códec sin comprimir!!! Vea TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Inicializa una nueva instancia de la clase  TiffOptions  . |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Inicializa una nueva instancia de la clase  TiffOptions  . |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Inicializa una nueva instancia de la clase  TiffOptions  . |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Inicializa una nueva instancia de la clase  TiffOptions  . |
## Métodos

| Método | Descripción |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Agrega una nueva etiqueta. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Agrega las etiquetas. |
| [clone()](#clone--) |  |
| [close()](#close--) | Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. |
| [deepClone()](#deepClone--) | Clona esta instancia. |
| [deepClone_internalized()](#deepClone-internalized--) | Clona esta instancia. |
| [dispose()](#dispose--) | Descarta la instancia actual. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Obtiene o establece la opción de almacenamiento alfa. |
| [getArtist()](#getArtist--) | Obtiene o establece el artista. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Obtiene o establece el color del fondo. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene los bits por píxel. |
| [getBitsPerSample()](#getBitsPerSample--) | Obtiene los bits por muestra. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [getByteOrder()](#getByteOrder--) | Obtiene o establece un valor que indica el orden de bytes tiff. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Obtiene la caché. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Obtiene o establece el mapa de colores. |
| [getCompressedQuality()](#getCompressedQuality--) | Obtiene la calidad de la imagen comprimida. |
| [getCompression()](#getCompression--) | Obtiene la compresión. |
| [getCopyright()](#getCopyright--) | Obtiene el copyright. |
| [getDateTime()](#getDateTime--) | Obtiene o establece la fecha y hora. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Obtiene o establece el límite predeterminado de asignación de memoria. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [getDisposed()](#getDisposed--) | Obtiene un valor que indica si esta instancia está eliminada. |
| [getDocumentName()](#getDocumentName--) | Obtiene o establece el nombre del documento. |
| [getExifIfd()](#getExifIfd--) | Obtiene o establece el puntero al EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Obtiene el recuento de muestras extra. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Obtiene los valores de las muestras extra. |
| [getFaxT4Options()](#getFaxT4Options--) | Obtiene o establece las opciones de fax t4. |
| [getFileStandard()](#getFileStandard--) | Obtiene o establece el estándar de archivo TIFF. |
| [getFillOrder()](#getFillOrder--) | Obtiene o establece el orden de relleno de bits de byte. |
| [getFullFrame()](#getFullFrame--) | Obtiene un valor que indica si [full frame]. |
| [getHalfToneHints()](#getHalfToneHints--) | Obtiene o establece las sugerencias de semitono. |
| [getIccProfile()](#getIccProfile--) | Obtiene el flujo del perfil icc. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [getImageDescription()](#getImageDescription--) | Obtiene o establece la descripción de la imagen. |
| [getImageLength()](#getImageLength--) | Obtiene o establece la longitud de la imagen. |
| [getImageWidth()](#getImageWidth--) | Obtiene o establece el ancho de la imagen. |
| [getInkNames()](#getInkNames--) | Obtiene o establece los nombres de tinta. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Obtiene o establece el valor máximo de muestra. |
| [getMinSampleValue()](#getMinSampleValue--) | Obtiene o establece el valor mínimo de muestra. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Las opciones multipágina |
| [getOrientation()](#getOrientation--) | Obtiene o establece la orientación. |
| [getPageName()](#getPageName--) | Obtiene o establece el nombre de la página. |
| [getPageNumber()](#getPageNumber--) | Obtiene o establece la etiqueta de número de página. |
| [getPalette()](#getPalette--) | Obtiene o establece la paleta de colores. |
| [getPhotometric()](#getPhotometric--) | Obtiene o establece el fotométrico. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Obtiene o establece la configuración planar. |
| [getPredictor()](#getPredictor--) | Obtiene o establece el predictor para la compresión LZW. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Obtiene o establece un valor que indica si los componentes deben ser premultiplicados. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtiene o establece el controlador del evento de progreso. |
| [getResolutionSettings()](#getResolutionSettings--) | Obtiene o establece la configuración de resolución. |
| [getResolutionUnit()](#getResolutionUnit--) | Obtiene o establece la unidad de resolución. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Obtiene o establece las filas por tira. |
| [getSampleFormat()](#getSampleFormat--) | Obtiene o establece el formato de muestra. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Obtiene las muestras por píxel. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Obtiene o establece el fabricante del escáner. |
| [getScannerModel()](#getScannerModel--) | Obtiene o establece el modelo del escáner. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Obtiene o establece el valor máximo de muestra. |
| [getSminSampleValue()](#getSminSampleValue--) | Obtiene o establece el valor mínimo de muestra. |
| [getSoftwareType()](#getSoftwareType--) | Obtiene o establece el tipo de software. |
| [getSource()](#getSource--) | Obtiene o establece la fuente en la que crear la imagen. |
| [getStripByteCounts()](#getStripByteCounts--) | Obtiene o establece los recuentos de bytes de la tira. |
| [getStripOffsets()](#getStripOffsets--) | Obtiene o establece los desplazamientos de la tira. |
| [getSubFileType()](#getSubFileType--) | Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Obtiene la instancia de la etiqueta por tipo. |
| [getTags()](#getTags--) | Obtiene o establece las etiquetas. |
| [getTargetPrinter()](#getTargetPrinter--) | Obtiene o establece la impresora objetivo. |
| [getThreshholding()](#getThreshholding--) | Obtiene o establece el umbral. |
| [getTileByteCounts()](#getTileByteCounts--) | Obtiene o establece los recuentos de bytes del mosaico. |
| [getTileLength()](#getTileLength--) | Obtiene ot establece la longitud del mosaico. |
| [getTileOffsets()](#getTileOffsets--) | Obtiene o establece los desplazamientos del mosaico. |
| [getTileWidth()](#getTileWidth--) | Obtiene ot establece el ancho del mosaico. |
| [getTotalPages()](#getTotalPages--) | Obtiene el total de páginas. |
| [getValidTagCount()](#getValidTagCount--) | Obtiene el recuento válido de etiquetas. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtiene la cantidad de etiquetas válidas. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Obtiene o establece las opciones de rasterización vectorial. |
| [getXPAuthor()](#getXPAuthor--) | Obtiene el autor de la imagen, que es usado por el Explorador de Windows. |
| [getXPComment()](#getXPComment--) | Obtiene el comentario de la imagen, que es usado por el Explorador de Windows. |
| [getXPKeywords()](#getXPKeywords--) | Obtiene la imagen del asunto, que es usada por el Explorador de Windows. |
| [getXPSubject()](#getXPSubject--) | Obtiene información sobre la imagen, que es usada por el Explorador de Windows. |
| [getXPTitle()](#getXPTitle--) | Obtiene información sobre la imagen, que es usada por el Explorador de Windows. |
| [getXmpData()](#getXmpData--) | Obtiene o establece el contenedor de metadatos XMP. |
| [getXposition()](#getXposition--) | Obtiene o establece la posición x. |
| [getXresolution()](#getXresolution--) | Obtiene o establece la resolución X. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Obtiene o establece los YCbCrCoefficients. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Obtiene o establece los factores de submuestreo para la fotométrica YCbCr. |
| [getYposition()](#getYposition--) | Obtiene o establece la posición y. |
| [getYresolution()](#getYresolution--) | Obtiene o establece la resolución y. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Obtiene un valor que indica si los extra samples están presentes. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Determina si la etiqueta está presente en las opciones o no. |
| [isTiled()](#isTiled--) | Obtiene un valor que indica si la imagen está en mosaico. |
| [isValid()](#isValid--) | Obtiene un valor que indica si TiffOptions ha sido configurado correctamente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Elimina la etiqueta. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Obtiene o establece la opción de almacenamiento alfa. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Obtiene o establece el artista. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Obtiene o establece el color del fondo. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Establece los bits por muestra. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setByteOrder(int value)](#setByteOrder-int-) | Obtiene o establece un valor que indica el orden de bytes tiff. |
| [setColorMap(int[] value)](#setColorMap-int---) | Obtiene o establece el mapa de colores. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Establece la calidad de la imagen comprimida. |
| [setCompression(int value)](#setCompression-int-) | Establece la compresión. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Establece el copyright. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Obtiene o establece la fecha y hora. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Obtiene o establece el límite predeterminado de asignación de memoria. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de la capa existente en el archivo PSD no está presente en el sistema). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Obtiene o establece el nombre del documento. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Establece los valores de extra samples. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Obtiene o establece las opciones de fax t4. |
| [setFileStandard(int value)](#setFileStandard-int-) | Obtiene o establece el estándar de archivo TIFF. |
| [setFillOrder(int value)](#setFillOrder-int-) | Obtiene o establece el orden de relleno de bits de byte. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Establece un valor que indica si [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Obtiene o establece las sugerencias de semitono. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Establece el flujo del perfil icc. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Obtiene o establece un valor que indica si se ignora después del evento de creación. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Obtiene o establece la descripción de la imagen. |
| [setImageLength(long value)](#setImageLength-long-) | Obtiene o establece la longitud de la imagen. |
| [setImageWidth(long value)](#setImageWidth-long-) | Obtiene o establece el ancho de la imagen. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Obtiene o establece los nombres de tinta. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Obtiene o establece el valor máximo de muestra. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Obtiene o establece el valor mínimo de muestra. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Las opciones multipágina |
| [setOrientation(int value)](#setOrientation-int-) | Obtiene o establece la orientación. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Obtiene o establece el nombre de la página. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Obtiene o establece la etiqueta de número de página. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Obtiene o establece la paleta de colores. |
| [setPhotometric(int value)](#setPhotometric-int-) | Obtiene o establece el fotométrico. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Obtiene o establece la configuración planar. |
| [setPredictor(int value)](#setPredictor-int-) | Obtiene o establece el predictor para la compresión LZW. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtiene o establece un valor que indica si los componentes deben ser premultiplicados. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Obtiene o establece el controlador del evento de progreso. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Obtiene o establece la configuración de resolución. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Obtiene o establece la unidad de resolución. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Obtiene o establece las filas por tira. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Obtiene o establece el formato de muestra. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Obtiene o establece el fabricante del escáner. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Obtiene o establece el modelo del escáner. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Obtiene o establece el valor máximo de muestra. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Obtiene o establece el valor mínimo de muestra. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Obtiene o establece el tipo de software. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Obtiene o establece la fuente en la que crear la imagen. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Obtiene o establece los recuentos de bytes de la tira. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Obtiene o establece los desplazamientos de la tira. |
| [setSubFileType(long value)](#setSubFileType-long-) | Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Obtiene o establece las etiquetas. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Obtiene o establece la impresora objetivo. |
| [setThreshholding(int value)](#setThreshholding-int-) | Obtiene o establece el umbral. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Obtiene o establece los recuentos de bytes del mosaico. |
| [setTileLength(long value)](#setTileLength-long-) | Obtiene ot establece la longitud del mosaico. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Obtiene o establece los desplazamientos del mosaico. |
| [setTileWidth(long value)](#setTileWidth-long-) | Obtiene ot establece el ancho del mosaico. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Obtiene o establece las opciones de rasterización vectorial. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Establece el autor de la imagen, que es usado por Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Establece el comentario de la imagen, que es usado por Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Establece el asunto de la imagen, que es usado por Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Establece información sobre la imagen, que es usado por Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Establece información sobre la imagen, que es usado por Windows Explorer. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtiene o establece el contenedor de metadatos XMP. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la posición x. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución X. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Obtiene o establece los YCbCrCoefficients. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Obtiene o establece los factores de submuestreo para la fotométrica YCbCr. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la posición y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Obtiene o establece la resolución y. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Valida si las opciones tienen una combinación válida de etiquetas |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Inicializa una nueva instancia de la clase  TiffOptions  .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expectedFormat | int | El formato de archivo tiff esperado. |
| byteOrder | int | El orden de bytes del formato de archivo tiff a usar. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Inicializa una nueva instancia de la clase TiffOptions. Por defecto se usa la convención little endian.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expectedFormat | int | El formato de archivo tiff esperado. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Inicializa una nueva instancia de la clase  TiffOptions  .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | Las opciones de las que copiar. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Inicializa una nueva instancia de la clase  TiffOptions  .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Las etiquetas con las que inicializar las opciones. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Agrega una nueva etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | La etiqueta a añadir. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Agrega las etiquetas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Las etiquetas a añadir. |

### clone() {#clone--}
```
public ImageOptionsBase clone()
```




**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
### close() {#close--}
```
public void close()
```


Implementa la interfaz Closable y puede usarse en la sentencia try-with-resources desde JDK 1.7. Este método simplemente llama al método dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clona esta instancia.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Clona esta instancia.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Descarta la instancia actual.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Obtiene o establece la opción de almacenamiento alfa. Las opciones distintas de TiffAlphaStorage.Unspecified se usan cuando hay más de 3 SamplesPerPixel definidos.

**Returns:**
int - La opción de almacenamiento alfa.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Obtiene o establece el artista.

**Returns:**
java.lang.String - El artista.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Obtiene o establece el color del fondo. Se usa con fines internos para almacenar el color de fondo de la imagen.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene los bits por píxel.

**Returns:**
int - Los bits por píxel.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Obtiene los bits por muestra.

**Returns:**
int[] - El valor de bits por muestra.

Al establecer este valor, tenga en cuenta que también establecerá el valor de SamplesPerPixel a la longitud del arreglo. Estas 2 propiedades están muy estrechamente acopladas, por lo que solo pueden establecerse juntas.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Obtiene o establece un valor que indica el orden de bytes tiff.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Obtiene la caché.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etiqueta | int | La etiqueta (que es un tipo de arreglo). |

**Returns:**
long[] - El valor de la etiqueta.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMap() {#getColorMap--}
```
public int[] getColorMap()
```


Obtiene o establece el mapa de colores.

**Returns:**
int[] - El mapa de colores.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Obtiene la calidad de la imagen comprimida. Se usa con la compresión JPEG.

**Returns:**
int - calidad de imagen comprimida.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Obtiene la compresión.

**Returns:**
int - La compresión.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Obtiene el copyright.

**Returns:**
java.lang.String - El copyright.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Obtiene o establece la fecha y hora.

**Returns:**
java.lang.String - La fecha y hora.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Obtiene o establece el límite predeterminado de asignación de memoria.

**Returns:**
int - El límite predeterminado de asignación de memoria.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema). Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valor: La fuente de reemplazo predeterminada.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtiene un valor que indica si esta instancia está eliminada.

**Returns:**
boolean -  true  si está eliminado; de lo contrario,  false .
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Obtiene o establece el nombre del documento.

**Returns:**
java.lang.String - El nombre del documento.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Obtiene o establece el puntero al EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Obtiene el recuento de muestras extra.

Valor: El recuento de muestras extra.

**Returns:**
long - el recuento de muestras extra.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Obtiene los valores de las muestras extra.

Valor: El valor de las muestras extra.

**Returns:**
int[] - los valores de las muestras extra.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Obtiene o establece las opciones de fax t4.

**Returns:**
long - Las opciones de fax t4.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Obtiene o establece el estándar de archivo TIFF.

**Returns:**
int - El estándar de archivo TIFF.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Obtiene o establece el orden de relleno de bits de byte.

**Returns:**
int - El orden de relleno de bits de byte.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Obtiene un valor que indica si [full frame].

Valor:  true  si [full frame]; de lo contrario,  false .

**Returns:**
boolean - un valor que indica si [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Obtiene o establece las sugerencias de semitono.

**Returns:**
int[] - Las sugerencias de semitono.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Obtiene el flujo del perfil icc.

**Returns:**
byte[] - El perfil ICC.
### getIccProfile_internalized() {#getIccProfile-internalized--}
```
public System.IO.MemoryStream getIccProfile_internalized()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Obtiene o establece un valor que indica si se ignora después del evento de creación.

Valor:  true  si se ignora después del evento de creación; de lo contrario,  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Obtiene o establece la descripción de la imagen.

**Returns:**
java.lang.String - La descripción de la imagen.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Obtiene o establece la longitud de la imagen.

**Returns:**
long - La longitud de la imagen.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Obtiene o establece el ancho de la imagen.

**Returns:**
long - El ancho de la imagen.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Obtiene o establece los nombres de tinta.

**Returns:**
java.lang.String - Los nombres de tinta.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Obtiene o establece el valor máximo de muestra.

**Returns:**
int[] - El valor máximo de la muestra.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Obtiene o establece el valor mínimo de muestra.

**Returns:**
int[] - El valor mínimo de la muestra.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Las opciones multipágina

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Obtiene o establece la orientación.

**Returns:**
int - La orientación.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Obtiene o establece el nombre de la página.

**Returns:**
java.lang.String - El nombre de la página.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Obtiene o establece la etiqueta de número de página.

**Returns:**
int[] - La etiqueta de número de página.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtiene o establece la paleta de colores.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Obtiene o establece el fotométrico.

**Returns:**
int - El fotométrico.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Obtiene o establece la configuración planar.

**Returns:**
int - La configuración planar.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Obtiene o establece el predictor para la compresión LZW.

**Returns:**
int - El tipo de predictor.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Obtiene o establece un valor que indica si los componentes deben ser premultiplicados.

**Returns:**
boolean -  true  si los componentes deben estar premultiplicados; de lo contrario,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Obtiene o establece el controlador del evento de progreso.

Valor: El controlador del evento de progreso.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Obtiene o establece la configuración de resolución.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Obtiene o establece la unidad de resolución.

**Returns:**
int - La unidad de resolución.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Obtiene o establece las filas por tira.

**Returns:**
long - Las filas por tira.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Obtiene o establece el formato de muestra.

**Returns:**
int[] - El formato de muestra.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Obtiene las muestras por píxel. Para cambiar el valor de esta propiedad use el configurador de la propiedad  BitsPerSample  .

**Returns:**
int - Las muestras por píxel.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Obtiene o establece el fabricante del escáner.

**Returns:**
java.lang.String - El fabricante del escáner.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Obtiene o establece el modelo del escáner.

**Returns:**
java.lang.String - El modelo del escáner.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Obtiene o establece el valor máximo de la muestra. El valor tiene un tipo de campo que mejor coincide con los datos de la muestra (Byte, Short o Long tipo).

**Returns:**
long[] - El valor máximo de la muestra.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Obtiene o establece el valor mínimo de la muestra. El valor tiene un tipo de campo que mejor coincide con los datos de la muestra (Byte, Short o Long tipo).

**Returns:**
long[] - El valor mínimo de la muestra.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Obtiene o establece el tipo de software.

**Returns:**
java.lang.String - El tipo de software.
### getSource() {#getSource--}
```
public final Source getSource()
```


Obtiene o establece la fuente en la que crear la imagen.

Valor: La fuente en la que crear la imagen.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Obtiene o establece los recuentos de bytes de la tira.

**Returns:**
long[] - Los recuentos de bytes de la tira.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Obtiene o establece los desplazamientos de la tira.

**Returns:**
long[] - Los desplazamientos de tira.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo.

**Returns:**
long - La indicación general del tipo de datos contenidos en este subarchivo.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Obtiene la instancia de la etiqueta por tipo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tagKey | int | La clave de etiqueta. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Obtiene o establece las etiquetas.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - Las etiquetas.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Obtiene o establece la impresora objetivo.

**Returns:**
java.lang.String - La impresora objetivo.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Obtiene o establece el umbral.

**Returns:**
int - El umbral.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Obtiene o establece los recuentos de bytes del mosaico.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Obtiene ot establece la longitud del mosaico.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Obtiene o establece los desplazamientos del mosaico.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Obtiene ot establece el ancho del mosaico.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Obtiene el total de páginas.

**Returns:**
int - El total de páginas.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Obtiene el recuento de etiquetas válidas. No es el recuento total de etiquetas, sino el número de etiquetas que pueden preservarse.

**Returns:**
int - El recuento de etiquetas válidas.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Obtiene la cantidad de etiquetas válidas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Las etiquetas a validar. |

**Returns:**
int - La cantidad de etiquetas válidas.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Obtiene o establece las opciones de rasterización vectorial.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Obtiene el autor de la imagen, que es usado por el Explorador de Windows.

Valor: Autor de la imagen, usado por Windows Explorer. El  XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) es ignorado por Windows Explorer si la etiqueta Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) existe.

**Returns:**
java.lang.String - autor de la imagen, que es usado por Windows Explorer.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Obtiene el comentario de la imagen, que es usado por el Explorador de Windows.

Valor: Comentario de la imagen, usado por Windows Explorer.

**Returns:**
java.lang.String - comentario de la imagen, que es usado por Windows Explorer.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Obtiene la imagen del asunto, que es usada por el Explorador de Windows.

Valor: Asunto de la imagen, usado por Windows Explorer.

**Returns:**
java.lang.String - asunto de la imagen, que es usado por Windows Explorer.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Obtiene información sobre la imagen, que es usada por el Explorador de Windows.

Valor: Información sobre la imagen, usado por Windows Explorer.

**Returns:**
java.lang.String - información sobre la imagen, que es usado por Windows Explorer.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Obtiene información sobre la imagen, que es usada por el Explorador de Windows.

Valor: Información sobre la imagen, usado por Windows Explorer. El  XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) es ignorado por Windows Explorer si la etiqueta ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) existe.

**Returns:**
java.lang.String - información sobre la imagen, que es usado por Windows Explorer.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtiene o establece el contenedor de metadatos XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Obtiene o establece la posición x.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Obtiene o establece la resolución X.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Obtiene o establece los YCbCrCoefficients.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Los coeficientes YCbCr.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Obtiene o establece los factores de submuestreo para la fotométrica YCbCr.

**Returns:**
int[] - Los factores de submuestreo para la fotométrica YCbCr.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Obtiene o establece la posición y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Obtiene o establece la resolución y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y resolution.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isExtraSamplesPresent() {#isExtraSamplesPresent--}
```
public boolean isExtraSamplesPresent()
```


Obtiene un valor que indica si los extra samples están presentes.

**Returns:**
boolean -  true  si las muestras extra están presentes; de lo contrario,  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Determina si la etiqueta está presente en las opciones o no.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etiqueta | int | El id de etiqueta a comprobar. |

**Returns:**
boolean -  true  si la etiqueta está presente; de lo contrario,  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Obtiene un valor que indica si la imagen está en mosaico.

**Returns:**
boolean -  true  si la imagen está en mosaico; de lo contrario,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Obtiene un valor que indica si las TiffOptions se han configurado correctamente. Use el método Validate para encontrar la razón del error.

**Returns:**
boolean -  true  si las TiffOptions están configuradas correctamente; de lo contrario,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeTag(int tag) {#removeTag-int-}
```
public boolean removeTag(int tag)
```


Elimina la etiqueta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| etiqueta | int | La etiqueta a eliminar. |

**Returns:**
boolean - true si se eliminó correctamente
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Obtiene o establece la opción de almacenamiento alfa. Las opciones distintas de TiffAlphaStorage.Unspecified se usan cuando hay más de 3 SamplesPerPixel definidos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La opción de almacenamiento alfa. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Obtiene o establece el artista.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El artista. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Obtiene o establece el color del fondo. Se usa con fines internos para almacenar el color de fondo de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | El color del fondo. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Establece los bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int[] | El valor de bits por muestra. |

Al establecer este valor, tenga en cuenta que también establecerá el valor de SamplesPerPixel a la longitud del arreglo. Estas 2 propiedades están muy estrechamente acopladas, por lo que solo pueden establecerse juntas. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Obtiene o establece la sugerencia de tamaño de búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Obtiene o establece un valor que indica el orden de bytes tiff.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Obtiene o establece el mapa de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El mapa de colores. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Establece la calidad de la imagen comprimida. Se usa con la compresión Jpeg.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | calidad de la imagen comprimida. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Establece la compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La compresión. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Establece el copyright.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El copyright. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Obtiene o establece la fecha y hora.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La fecha y hora. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Obtiene o establece el límite predeterminado de asignación de memoria.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El límite predeterminado de asignación de memoria. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Obtiene o establece la fuente de reemplazo predeterminada (fuente que se utilizará para dibujar texto al exportar a raster, si la fuente de capa existente en el archivo PSD no está presente en el sistema). Para obtener el nombre correcto de la fuente predeterminada se puede usar el siguiente fragmento de código: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Valor: La fuente de reemplazo predeterminada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Obtiene o establece el nombre del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El nombre del documento. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Establece los valores de extra samples.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El valor de muestras extra. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Obtiene o establece las opciones de fax t4.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | Las opciones fax t4. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Obtiene o establece el estándar de archivo TIFF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El estándar de archivo TIFF. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Obtiene o establece el orden de relleno de bits de byte.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El orden de relleno de bits de byte. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Establece un valor que indica si [full frame].

Valor:  true  si [full frame]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [full frame]. |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Obtiene o establece las sugerencias de semitono.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | Las sugerencias de semitono. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Establece el flujo del perfil icc.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] | El perfil icc. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Obtiene o establece un valor que indica si se ignora después del evento de creación.

Valor:  true  si se ignora después del evento de creación; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Obtiene o establece la descripción de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La descripción de la imagen. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Obtiene o establece la longitud de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | La longitud de la imagen. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Obtiene o establece el ancho de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | El ancho de la imagen. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Obtiene o establece los nombres de tinta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Los nombres de tinta. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Obtiene o establece el valor máximo de muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El valor máximo de muestra. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Obtiene o establece el valor mínimo de muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El valor mínimo de muestra. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Las opciones multipágina

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Obtiene o establece la orientación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La orientación. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Obtiene o establece el nombre de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El nombre de la página. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Obtiene o establece la etiqueta de número de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | La etiqueta de número de página. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Obtiene o establece la paleta de colores.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | La paleta de colores. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Obtiene o establece el fotométrico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El fotométrico. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Obtiene o establece la configuración planar.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La configuración planar. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Obtiene o establece el predictor para la compresión LZW.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El tipo de predictor. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Obtiene o establece un valor que indica si los componentes deben ser premultiplicados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | true si los componentes deben estar premultiplicados; de lo contrario, false. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Obtiene o establece el controlador del evento de progreso.

Valor: El controlador del evento de progreso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Obtiene o establece la configuración de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Obtiene o establece la unidad de resolución.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | La unidad de resolución. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Obtiene o establece las filas por tira.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | Las filas por tira. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Obtiene o establece el formato de muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | El formato de muestra. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Obtiene o establece el fabricante del escáner.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El fabricante del escáner. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Obtiene o establece el modelo del escáner.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El modelo del escáner. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Obtiene o establece el valor máximo de la muestra. El valor tiene un tipo de campo que mejor coincide con los datos de la muestra (Byte, Short o Long tipo).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] | El valor máximo de muestra. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Obtiene o establece el valor mínimo de la muestra. El valor tiene un tipo de campo que mejor coincide con los datos de la muestra (Byte, Short o Long tipo).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] | El valor mínimo de muestra. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Obtiene o establece el tipo de software.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | El tipo de software. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Obtiene o establece la fuente en la que crear la imagen.

Valor: La fuente en la que crear la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Obtiene o establece los recuentos de bytes de la tira.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] | Los recuentos de bytes de la tira. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Obtiene o establece los desplazamientos de la tira.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] | Los desplazamientos de la tira. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Obtiene o establece una indicación general del tipo de datos contenidos en este subarchivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | La indicación general del tipo de datos contenidos en este subarchivo. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Obtiene o establece las etiquetas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Las etiquetas. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Obtiene o establece la impresora objetivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | La impresora objetivo. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Obtiene o establece el umbral.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | El umbralado. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Obtiene o establece los recuentos de bytes del mosaico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Obtiene ot establece la longitud del mosaico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Obtiene o establece los desplazamientos del mosaico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Obtiene ot establece el ancho del mosaico.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Obtiene o establece las opciones de rasterización vectorial.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Establece el autor de la imagen, que es usado por Windows Explorer.

Valor: Autor de la Imagen, usado por Windows Explorer. El  XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) es ignorado por Windows Explorer si la etiqueta Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) existe.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | autor de la imagen, que es usado por Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Establece el comentario de la imagen, que es usado por Windows Explorer.

Valor: Comentario de la imagen, usado por Windows Explorer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | comentario de la imagen, que es usado por Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Establece el asunto de la imagen, que es usado por Windows Explorer.

Valor: Asunto de la imagen, usado por Windows Explorer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | imagen del asunto, que es usada por Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Establece información sobre la imagen, que es usado por Windows Explorer.

Valor: Información sobre la imagen, usado por Windows Explorer.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | información sobre la imagen, que es usada por Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Establece información sobre la imagen, que es usado por Windows Explorer.

Valor: Información sobre la imagen, usada por Windows Explorer. El  XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) es ignorado por Windows Explorer si la etiqueta ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) existe.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | información sobre la imagen, que es usada por Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtiene o establece el contenedor de metadatos XMP.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | El contenedor de datos XMP. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Obtiene o establece la posición x.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La posición x. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Obtiene o establece la resolución X.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La resolución x. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Obtiene o establece los YCbCrCoefficients.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Los coeficientes YCbCr. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Obtiene o establece los factores de submuestreo para la fotométrica YCbCr.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] | Los factores de submuestreo para la fotometría YCbCr. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Obtiene o establece la posición y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La posición y. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Obtiene o establece la resolución y.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | La resolución y. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validate() {#validate--}
```
public void validate()
```


Valida si las opciones tienen una combinación válida de etiquetas

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

