---
title: "TiffOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры формата файла tiff."
type: docs
weight: 25
url: /ru/java/com.aspose.psd.imageoptions/tiffoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class TiffOptions extends ImageOptionsBase
```

Параметры формата файла tiff. Обратите внимание, что теги width и height будут перезаписаны при создании изображения параметрами width и height, поэтому нет необходимости указывать их напрямую. Обратите внимание, что многие параметры возвращают значение по умолчанию, но это не означает, что данный параметр установлен явно как значение тега. Чтобы проверить наличие тега, используйте свойство Tags или соответствующий метод IsTagPresent.

ПРЕДУПРЕЖДЕНИЕ! никогда не изменяйте параметры tiff при сохранении, так как это может вызвать побочные эффекты и трудно обнаруживаемые ошибки. Следующая строка была специально оставлена закомментированной, поскольку она приводила к неправильному определению начала данных. Переданные параметры не содержали spp (хотя параметры в таком случае некорректны, но всё равно эта ситуация вызывает ошибки), и следующая строка добавляла теги +spp и +bpp, и когда параметры записывались после полного записи данных, они перезаписывали начало данных для некодированного кодека!!! См. TiffUncompressedCodec.Encode. this.Options.SamplesPerPixel = 3;
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffOptions(int expectedFormat, int byteOrder)](#TiffOptions-int-int-) | Инициализирует новый экземпляр класса  TiffOptions . |
| [TiffOptions(int expectedFormat)](#TiffOptions-int-) | Инициализирует новый экземпляр класса  TiffOptions . |
| [TiffOptions(TiffOptions options)](#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-) | Инициализирует новый экземпляр класса  TiffOptions . |
| [TiffOptions(TiffDataType[] tags)](#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---) | Инициализирует новый экземпляр класса  TiffOptions . |
## Методы

| Метод | Описание |
| --- | --- |
| [addTag(TiffDataType tagToAdd)](#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-) | Добавляет новый тег. |
| [addTags(TiffDataType[] tagsToAdd)](#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Добавляет теги. |
| [clone()](#clone--) |  |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlphaStorage()](#getAlphaStorage--) | Получает или задает параметр хранения альфа-канала. |
| [getArtist()](#getArtist--) | Получает или задаёт исполнителя. |
| [getBackgroundColor_internalized()](#getBackgroundColor-internalized--) | Получает или задает цвет фона. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество битов на пиксель. |
| [getBitsPerSample()](#getBitsPerSample--) | Получает количество бит на образец. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [getByteOrder()](#getByteOrder--) | Получает или задает значение, указывающее порядок байтов tiff. |
| [getCache_internalized(int tag)](#getCache-internalized-int-) | Получает кэш. |
| [getClass()](#getClass--) |  |
| [getColorMap()](#getColorMap--) | Получает или задает карту цветов. |
| [getCompressedQuality()](#getCompressedQuality--) | Получает качество сжатого изображения. |
| [getCompression()](#getCompression--) | Получает степень сжатия. |
| [getCopyright()](#getCopyright--) | Получает информацию об авторском праве. |
| [getDateTime()](#getDateTime--) | Получает или задает дату и время. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Получает или задает предельный размер выделения памяти по умолчанию. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getDocumentName()](#getDocumentName--) | Получает или задает имя документа. |
| [getExifIfd()](#getExifIfd--) | Получает или задает указатель на EXIF IFD. |
| [getExtraSampleCount_internalized()](#getExtraSampleCount-internalized--) | Получает количество дополнительных образцов. |
| [getExtraSamples_internalized()](#getExtraSamples-internalized--) | Получает значения дополнительных образцов. |
| [getFaxT4Options()](#getFaxT4Options--) | Получает или задает параметры fax t4. |
| [getFileStandard()](#getFileStandard--) | Получает или задает стандарт TIFF‑файла. |
| [getFillOrder()](#getFillOrder--) | Получает или задает порядок заполнения битов байта. |
| [getFullFrame()](#getFullFrame--) | Возвращает значение, указывающее, является ли [полный кадр]. |
| [getHalfToneHints()](#getHalfToneHints--) | Получает или задает подсказки полутонов. |
| [getIccProfile()](#getIccProfile--) | Получает поток ICC‑профиля. |
| [getIccProfile_internalized()](#getIccProfile-internalized--) |  |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [getImageDescription()](#getImageDescription--) | Получает или задаёт описание изображения. |
| [getImageLength()](#getImageLength--) | Получает или задаёт длину изображения. |
| [getImageWidth()](#getImageWidth--) | Получает или задаёт ширину изображения. |
| [getInkNames()](#getInkNames--) | Получает или задает названия чернил. |
| [getMaxSampleValue()](#getMaxSampleValue--) | Получает или задает максимальное значение образца. |
| [getMinSampleValue()](#getMinSampleValue--) | Получает или задает минимальное значение образца. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Многостраничные параметры |
| [getOrientation()](#getOrientation--) | Получает или задаёт ориентацию. |
| [getPageName()](#getPageName--) | Получает или задает имя страницы. |
| [getPageNumber()](#getPageNumber--) | Получает или задает тег номера страницы. |
| [getPalette()](#getPalette--) | Получает или задает цветовую палитру. |
| [getPhotometric()](#getPhotometric--) | Получает или задает фотометрический параметр. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Получает или задаёт планарную конфигурацию. |
| [getPredictor()](#getPredictor--) | Получает или задает предсказатель для LZW‑сжатия. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает или задает обработчик события прогресса. |
| [getResolutionSettings()](#getResolutionSettings--) | Получает или задает настройки разрешения. |
| [getResolutionUnit()](#getResolutionUnit--) | Получает или задаёт единицу измерения разрешения. |
| [getRowsPerStrip()](#getRowsPerStrip--) | Получает или задает количество строк в полосе. |
| [getSampleFormat()](#getSampleFormat--) | Получает или задает формат образца. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Получает количество образцов на пиксель. |
| [getScannerManufacturer()](#getScannerManufacturer--) | Получает или задает производителя сканера. |
| [getScannerModel()](#getScannerModel--) | Получает или задает модель сканера. |
| [getSmaxSampleValue()](#getSmaxSampleValue--) | Получает или задает максимальное значение образца. |
| [getSminSampleValue()](#getSminSampleValue--) | Получает или задает минимальное значение образца. |
| [getSoftwareType()](#getSoftwareType--) | Получает или задает тип программного обеспечения. |
| [getSource()](#getSource--) | Получает или задает источник, в котором создаётся изображение. |
| [getStripByteCounts()](#getStripByteCounts--) | Получает или задает количество байтов в полосе. |
| [getStripOffsets()](#getStripOffsets--) | Получает или задает смещения полос. |
| [getSubFileType()](#getSubFileType--) | Получает или задает общее указание типа данных, содержащихся в этом подфайле. |
| [getTagByType(int tagKey)](#getTagByType-int-) | Получает экземпляр тега по типу. |
| [getTags()](#getTags--) | Получает или задает теги. |
| [getTargetPrinter()](#getTargetPrinter--) | Получает или задает целевой принтер. |
| [getThreshholding()](#getThreshholding--) | Получает или задает пороговое значение. |
| [getTileByteCounts()](#getTileByteCounts--) | Получает или задает количество байтов в плитке. |
| [getTileLength()](#getTileLength--) | Получает или задает длину плитки. |
| [getTileOffsets()](#getTileOffsets--) | Получает или задает смещения плитки. |
| [getTileWidth()](#getTileWidth--) | Получает или задает ширину плитки. |
| [getTotalPages()](#getTotalPages--) | Получает общее количество страниц. |
| [getValidTagCount()](#getValidTagCount--) | Получает количество действительных тегов. |
| [getValidTagsCount(TiffDataType[] tags)](#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---) | Получает количество допустимых тегов. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Получает или задает параметры растеризации вектора. |
| [getXPAuthor()](#getXPAuthor--) | Получает автора изображения, используемого в Windows Explorer. |
| [getXPComment()](#getXPComment--) | Получает комментарий к изображению, используемый в Windows Explorer. |
| [getXPKeywords()](#getXPKeywords--) | Получает тему изображения, используемую в Windows Explorer. |
| [getXPSubject()](#getXPSubject--) | Получает информацию об изображении, используемую в Windows Explorer. |
| [getXPTitle()](#getXPTitle--) | Получает информацию об изображении, используемую в Windows Explorer. |
| [getXmpData()](#getXmpData--) | Получает или задает контейнер метаданных XMP. |
| [getXposition()](#getXposition--) | Получает или задает позицию по оси X. |
| [getXresolution()](#getXresolution--) | Получает или задаёт разрешение по оси X. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | Получает или задает коэффициенты YCbCr. |
| [getYCbCrSubsampling()](#getYCbCrSubsampling--) | Получает или задает коэффициенты субдискретизации для фотометрии YCbCr. |
| [getYposition()](#getYposition--) | Получает или задает позицию по оси Y. |
| [getYresolution()](#getYresolution--) | Получает или задаёт разрешение по оси Y. |
| [hashCode()](#hashCode--) |  |
| [isExtraSamplesPresent()](#isExtraSamplesPresent--) | Получает значение, указывающее, присутствуют ли дополнительные образцы. |
| [isTagPresent(int tag)](#isTagPresent-int-) | Определяет, присутствует ли тег в параметрах или нет. |
| [isTiled()](#isTiled--) | Получает значение, указывающее, разбита ли изображение на плитки. |
| [isValid()](#isValid--) | Получает значение, указывающее, правильно ли настроен  TiffOptions  . |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTag(int tag)](#removeTag-int-) | Удаляет тег. |
| [setAlphaStorage(int value)](#setAlphaStorage-int-) | Получает или задает параметр хранения альфа-канала. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Получает или задаёт исполнителя. |
| [setBackgroundColor_internalized(Color value)](#setBackgroundColor-internalized-com.aspose.psd.Color-) | Получает или задает цвет фона. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Устанавливает биты на образец. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [setByteOrder(int value)](#setByteOrder-int-) | Получает или задает значение, указывающее порядок байтов tiff. |
| [setColorMap(int[] value)](#setColorMap-int---) | Получает или задает карту цветов. |
| [setCompressedQuality(int value)](#setCompressedQuality-int-) | Устанавливает качество сжатого изображения. |
| [setCompression(int value)](#setCompression-int-) | Устанавливает сжатие. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Устанавливает авторские права. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Получает или задает дату и время. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Получает или задает предельный размер выделения памяти по умолчанию. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [setDocumentName(String value)](#setDocumentName-java.lang.String-) | Получает или задает имя документа. |
| [setExtraSamples_internalized(int[] value)](#setExtraSamples-internalized-int---) | Устанавливает значения дополнительных образцов. |
| [setFaxT4Options(long value)](#setFaxT4Options-long-) | Получает или задает параметры fax t4. |
| [setFileStandard(int value)](#setFileStandard-int-) | Получает или задает стандарт TIFF‑файла. |
| [setFillOrder(int value)](#setFillOrder-int-) | Получает или задает порядок заполнения битов байта. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Устанавливает значение, указывающее, является ли [full frame]. |
| [setHalfToneHints(int[] value)](#setHalfToneHints-int---) | Получает или задает подсказки полутонов. |
| [setIccProfile(byte[] value)](#setIccProfile-byte---) | Устанавливает поток ICC‑профиля. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Получает или задаёт описание изображения. |
| [setImageLength(long value)](#setImageLength-long-) | Получает или задаёт длину изображения. |
| [setImageWidth(long value)](#setImageWidth-long-) | Получает или задаёт ширину изображения. |
| [setInkNames(String value)](#setInkNames-java.lang.String-) | Получает или задает названия чернил. |
| [setMaxSampleValue(int[] value)](#setMaxSampleValue-int---) | Получает или задает максимальное значение образца. |
| [setMinSampleValue(int[] value)](#setMinSampleValue-int---) | Получает или задает минимальное значение образца. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Многостраничные параметры |
| [setOrientation(int value)](#setOrientation-int-) | Получает или задаёт ориентацию. |
| [setPageName(String value)](#setPageName-java.lang.String-) | Получает или задает имя страницы. |
| [setPageNumber(int[] value)](#setPageNumber-int---) | Получает или задает тег номера страницы. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Получает или задает цветовую палитру. |
| [setPhotometric(int value)](#setPhotometric-int-) | Получает или задает фотометрический параметр. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Получает или задаёт планарную конфигурацию. |
| [setPredictor(int value)](#setPredictor-int-) | Получает или задает предсказатель для LZW‑сжатия. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Получает или задает обработчик события прогресса. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Получает или задает настройки разрешения. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Получает или задаёт единицу измерения разрешения. |
| [setRowsPerStrip(long value)](#setRowsPerStrip-long-) | Получает или задает количество строк в полосе. |
| [setSampleFormat(int[] value)](#setSampleFormat-int---) | Получает или задает формат образца. |
| [setScannerManufacturer(String value)](#setScannerManufacturer-java.lang.String-) | Получает или задает производителя сканера. |
| [setScannerModel(String value)](#setScannerModel-java.lang.String-) | Получает или задает модель сканера. |
| [setSmaxSampleValue(long[] value)](#setSmaxSampleValue-long---) | Получает или задает максимальное значение образца. |
| [setSminSampleValue(long[] value)](#setSminSampleValue-long---) | Получает или задает минимальное значение образца. |
| [setSoftwareType(String value)](#setSoftwareType-java.lang.String-) | Получает или задает тип программного обеспечения. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Получает или задает источник, в котором создаётся изображение. |
| [setStripByteCounts(long[] value)](#setStripByteCounts-long---) | Получает или задает количество байтов в полосе. |
| [setStripOffsets(long[] value)](#setStripOffsets-long---) | Получает или задает смещения полос. |
| [setSubFileType(long value)](#setSubFileType-long-) | Получает или задает общее указание типа данных, содержащихся в этом подфайле. |
| [setTags(TiffDataType[] value)](#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---) | Получает или задает теги. |
| [setTargetPrinter(String value)](#setTargetPrinter-java.lang.String-) | Получает или задает целевой принтер. |
| [setThreshholding(int value)](#setThreshholding-int-) | Получает или задает пороговое значение. |
| [setTileByteCounts(long[] value)](#setTileByteCounts-long---) | Получает или задает количество байтов в плитке. |
| [setTileLength(long value)](#setTileLength-long-) | Получает или задает длину плитки. |
| [setTileOffsets(long[] value)](#setTileOffsets-long---) | Получает или задает смещения плитки. |
| [setTileWidth(long value)](#setTileWidth-long-) | Получает или задает ширину плитки. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Получает или задает параметры растеризации вектора. |
| [setXPAuthor(String value)](#setXPAuthor-java.lang.String-) | Устанавливает автора изображения, который используется в Windows Explorer. |
| [setXPComment(String value)](#setXPComment-java.lang.String-) | Устанавливает комментарий к изображению, который используется в Windows Explorer. |
| [setXPKeywords(String value)](#setXPKeywords-java.lang.String-) | Устанавливает тему изображения, которая используется в Windows Explorer. |
| [setXPSubject(String value)](#setXPSubject-java.lang.String-) | Устанавливает информацию об изображении, которая используется в Windows Explorer. |
| [setXPTitle(String value)](#setXPTitle-java.lang.String-) | Устанавливает информацию об изображении, которая используется в Windows Explorer. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Получает или задает контейнер метаданных XMP. |
| [setXposition(TiffRational value)](#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает позицию по оси X. |
| [setXresolution(TiffRational value)](#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задаёт разрешение по оси X. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---) | Получает или задает коэффициенты YCbCr. |
| [setYCbCrSubsampling(int[] value)](#setYCbCrSubsampling-int---) | Получает или задает коэффициенты субдискретизации для фотометрии YCbCr. |
| [setYposition(TiffRational value)](#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задает позицию по оси Y. |
| [setYresolution(TiffRational value)](#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-) | Получает или задаёт разрешение по оси Y. |
| [toString()](#toString--) |  |
| [validate()](#validate--) | Проверяет, имеет ли набор параметров допустимую комбинацию тегов |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffOptions(int expectedFormat, int byteOrder) {#TiffOptions-int-int-}
```
public TiffOptions(int expectedFormat, int byteOrder)
```


Инициализирует новый экземпляр класса  TiffOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| expectedFormat | int | Ожидаемый формат файла tiff. |
| byteOrder | int | Порядок байтов формата файла TIFF, который следует использовать. |

### TiffOptions(int expectedFormat) {#TiffOptions-int-}
```
public TiffOptions(int expectedFormat)
```


Инициализирует новый экземпляр класса  TiffOptions . По умолчанию используется порядок little endian.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| expectedFormat | int | Ожидаемый формат файла tiff. |

### TiffOptions(TiffOptions options) {#TiffOptions-com.aspose.psd.imageoptions.TiffOptions-}
```
public TiffOptions(TiffOptions options)
```


Инициализирует новый экземпляр класса  TiffOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.psd.imageoptions/tiffoptions) | Параметры, из которых копировать. |

### TiffOptions(TiffDataType[] tags) {#TiffOptions-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public TiffOptions(TiffDataType[] tags)
```


Инициализирует новый экземпляр класса  TiffOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Теги, с помощью которых инициализировать параметры. |

### addTag(TiffDataType tagToAdd) {#addTag-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public void addTag(TiffDataType tagToAdd)
```


Добавляет новый тег.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagToAdd | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Тег для добавления. |

### addTags(TiffDataType[] tagsToAdd) {#addTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void addTags(TiffDataType[] tagsToAdd)
```


Добавляет теги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagsToAdd | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Теги для добавления. |

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


Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. Этот метод просто вызывает метод dispose.

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Клонирует этот экземпляр.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### deepClone_internalized() {#deepClone-internalized--}
```
public ImageOptionsBase deepClone_internalized()
```


Клонирует этот экземпляр.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Returns shallow copy of this instance
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает текущий экземпляр.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAlphaStorage() {#getAlphaStorage--}
```
public int getAlphaStorage()
```


Получает или задает параметр хранения альфа‑канала. Параметры, отличные от  TiffAlphaStorage.Unspecified  используются, когда определено более 3  SamplesPerPixel  .

**Returns:**
int — параметр хранения альфа‑канала.
### getArtist() {#getArtist--}
```
public String getArtist()
```


Получает или задаёт исполнителя.

**Returns:**
java.lang.String - Художник.
### getBackgroundColor_internalized() {#getBackgroundColor-internalized--}
```
public Color getBackgroundColor_internalized()
```


Получает или задает цвет фона. Используется в внутренних целях для хранения цвета фона изображения.

**Returns:**
[Color](../../com.aspose.psd/color) - The color of the background.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество битов на пиксель.

**Returns:**
int - количество бит на пиксель.
### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Получает количество бит на образец.

**Returns:**
int[] - Значение битов на образец.

При установке этого значения имейте в виду, что также будет установлено значение SamplesPerPixel равным длине массива. Эти два свойства очень тесно связаны, поэтому могут устанавливаться только вместе.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов.

Значение: подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Returns:**
int
### getByteOrder() {#getByteOrder--}
```
public int getByteOrder()
```


Получает или задает значение, указывающее порядок байтов tiff.

**Returns:**
int
### getCache_internalized(int tag) {#getCache-internalized-int-}
```
public long[] getCache_internalized(int tag)
```


Получает кэш.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тег | int | Тег (который является массивом). |

**Returns:**
long[] - Значение тега.
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


Получает или задает карту цветов.

**Returns:**
int[] - Цветовая карта.
### getCompressedQuality() {#getCompressedQuality--}
```
public final int getCompressedQuality()
```


Получает качество сжатого изображения. Используется с JPEG‑сжатием.

**Returns:**
int - качество сжатого изображения.
### getCompression() {#getCompression--}
```
public int getCompression()
```


Получает степень сжатия.

**Returns:**
int - Сжатие.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Получает информацию об авторском праве.

**Returns:**
java.lang.String - Авторские права.
### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Получает или задает дату и время.

**Returns:**
java.lang.String - Дата и время.
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Получает или задает предельный размер выделения памяти по умолчанию.

**Returns:**
int - Значение ограничения выделения памяти по умолчанию.
### getDefaultReplacementFont() {#getDefaultReplacementFont--}
```
public String getDefaultReplacementFont()
```


Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если шрифт существующего слоя в файле PSD не представлен в системе). Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Значение: Шрифт замены по умолчанию.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Получает значение, указывающее, освобожден ли этот экземпляр.

**Returns:**
boolean -  true  если освобождено; иначе,  false .
### getDocumentName() {#getDocumentName--}
```
public String getDocumentName()
```


Получает или задает имя документа.

**Returns:**
java.lang.String - Название документа.
### getExifIfd() {#getExifIfd--}
```
public TiffExifIfd getExifIfd()
```


Получает или задает указатель на EXIF IFD.

**Returns:**
[TiffExifIfd](../../com.aspose.psd.fileformats.tiff/tiffexififd) - The pointer to EXIF IFD.
### getExtraSampleCount_internalized() {#getExtraSampleCount-internalized--}
```
public final long getExtraSampleCount_internalized()
```


Получает количество дополнительных образцов.

Значение: количество дополнительных образцов.

**Returns:**
long - количество дополнительных образцов.
### getExtraSamples_internalized() {#getExtraSamples-internalized--}
```
public final int[] getExtraSamples_internalized()
```


Получает значения дополнительных образцов.

Значение: значение дополнительных образцов.

**Returns:**
int[] - значения дополнительных образцов.
### getFaxT4Options() {#getFaxT4Options--}
```
public long getFaxT4Options()
```


Получает или задает параметры fax t4.

**Returns:**
long - Параметры факса t4.
### getFileStandard() {#getFileStandard--}
```
public int getFileStandard()
```


Получает или задает стандарт TIFF‑файла.

**Returns:**
int - Стандарт TIFF‑файла.
### getFillOrder() {#getFillOrder--}
```
public int getFillOrder()
```


Получает или задает порядок заполнения битов байта.

**Returns:**
int - Порядок заполнения битов байта.
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Возвращает значение, указывающее, является ли [полный кадр].

Значение:  true  если [full frame]; иначе  false .

**Returns:**
boolean — значение, указывающее, является ли [full frame].
### getHalfToneHints() {#getHalfToneHints--}
```
public int[] getHalfToneHints()
```


Получает или задает подсказки полутонов.

**Returns:**
int[] - Подсказки полутонов.
### getIccProfile() {#getIccProfile--}
```
public byte[] getIccProfile()
```


Получает поток ICC‑профиля.

**Returns:**
byte[] - Профиль ICC.
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


Получает или задает значение, указывающее, следует ли игнорировать событие после создания.

Значение:  true  если игнорировать после события создания; иначе  false .

**Returns:**
boolean
### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Получает или задаёт описание изображения.

**Returns:**
java.lang.String - Описание изображения.
### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Получает или задаёт длину изображения.

**Returns:**
long - Длина изображения.
### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Получает или задаёт ширину изображения.

**Returns:**
long - Ширина изображения.
### getInkNames() {#getInkNames--}
```
public String getInkNames()
```


Получает или задает названия чернил.

**Returns:**
java.lang.String - Названия чернил.
### getMaxSampleValue() {#getMaxSampleValue--}
```
public int[] getMaxSampleValue()
```


Получает или задает максимальное значение образца.

**Returns:**
int[] - Максимальное значение образца.
### getMinSampleValue() {#getMinSampleValue--}
```
public int[] getMinSampleValue()
```


Получает или задает минимальное значение образца.

**Returns:**
int[] - Минимальное значение образца.
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Многостраничные параметры

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Получает или задаёт ориентацию.

**Returns:**
int - Ориентация.
### getPageName() {#getPageName--}
```
public String getPageName()
```


Получает или задает имя страницы.

**Returns:**
java.lang.String - Имя страницы.
### getPageNumber() {#getPageNumber--}
```
public int[] getPageNumber()
```


Получает или задает тег номера страницы.

**Returns:**
int[] - Тег номера страницы.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Получает или задает цветовую палитру.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPhotometric() {#getPhotometric--}
```
public int getPhotometric()
```


Получает или задает фотометрический параметр.

**Returns:**
int - Фотометрический параметр.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Получает или задаёт планарную конфигурацию.

**Returns:**
int - Планарная конфигурация.
### getPredictor() {#getPredictor--}
```
public int getPredictor()
```


Получает или задает предсказатель для LZW‑сжатия.

**Returns:**
int - Тип предиктора.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены.

**Returns:**
boolean -  true  если компоненты должны быть предварительно умножены; иначе,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Получает или задает обработчик события прогресса.

Значение: обработчик события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Получает или задает настройки разрешения.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Получает или задаёт единицу измерения разрешения.

**Returns:**
int - Единица измерения разрешения.
### getRowsPerStrip() {#getRowsPerStrip--}
```
public long getRowsPerStrip()
```


Получает или задает количество строк в полосе.

**Returns:**
long - Строк в полосе.
### getSampleFormat() {#getSampleFormat--}
```
public int[] getSampleFormat()
```


Получает или задает формат образца.

**Returns:**
int[] - Формат образца.
### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Получает количество образцов на пиксель. Чтобы изменить значение этого свойства, используйте сеттер свойства  BitsPerSample  .

**Returns:**
int - Количество образцов на пиксель.
### getScannerManufacturer() {#getScannerManufacturer--}
```
public String getScannerManufacturer()
```


Получает или задает производителя сканера.

**Returns:**
java.lang.String - Производитель сканера.
### getScannerModel() {#getScannerModel--}
```
public String getScannerModel()
```


Получает или задает модель сканера.

**Returns:**
java.lang.String - Модель сканера.
### getSmaxSampleValue() {#getSmaxSampleValue--}
```
public long[] getSmaxSampleValue()
```


Получает или задает максимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long).

**Returns:**
long[] - Максимальное значение образца.
### getSminSampleValue() {#getSminSampleValue--}
```
public long[] getSminSampleValue()
```


Получает или задает минимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long).

**Returns:**
long[] - Минимальное значение образца.
### getSoftwareType() {#getSoftwareType--}
```
public String getSoftwareType()
```


Получает или задает тип программного обеспечения.

**Returns:**
java.lang.String - Тип программного обеспечения.
### getSource() {#getSource--}
```
public final Source getSource()
```


Получает или задает источник, в котором создаётся изображение.

Значение: Источник, в котором создаётся изображение.

**Returns:**
[Source](../../com.aspose.psd/source)
### getStripByteCounts() {#getStripByteCounts--}
```
public long[] getStripByteCounts()
```


Получает или задает количество байтов в полосе.

**Returns:**
long[] - Количество байтов в полосе.
### getStripOffsets() {#getStripOffsets--}
```
public long[] getStripOffsets()
```


Получает или задает смещения полос.

**Returns:**
long[] - Смещения полос.
### getSubFileType() {#getSubFileType--}
```
public long getSubFileType()
```


Получает или задает общее указание типа данных, содержащихся в этом подфайле.

**Returns:**
long - Общее указание типа данных, содержащихся в этом подпфайле.
### getTagByType(int tagKey) {#getTagByType-int-}
```
public TiffDataType getTagByType(int tagKey)
```


Получает экземпляр тега по типу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tagKey | int | Ключ тега. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - Instance of the tag if exists or null otherwise.
### getTags() {#getTags--}
```
public TiffDataType[] getTags()
```


Получает или задает теги.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffDataType[] - Теги.
### getTargetPrinter() {#getTargetPrinter--}
```
public String getTargetPrinter()
```


Получает или задает целевой принтер.

**Returns:**
java.lang.String - Целевой принтер.
### getThreshholding() {#getThreshholding--}
```
public int getThreshholding()
```


Получает или задает пороговое значение.

**Returns:**
int - Пороговое значение.
### getTileByteCounts() {#getTileByteCounts--}
```
public long[] getTileByteCounts()
```


Получает или задает количество байтов в плитке.

**Returns:**
long[]
### getTileLength() {#getTileLength--}
```
public long getTileLength()
```


Получает или задает длину плитки.

**Returns:**
long
### getTileOffsets() {#getTileOffsets--}
```
public long[] getTileOffsets()
```


Получает или задает смещения плитки.

**Returns:**
long[]
### getTileWidth() {#getTileWidth--}
```
public long getTileWidth()
```


Получает или задает ширину плитки.

**Returns:**
long
### getTotalPages() {#getTotalPages--}
```
public int getTotalPages()
```


Получает общее количество страниц.

**Returns:**
int - Общее количество страниц.
### getValidTagCount() {#getValidTagCount--}
```
public int getValidTagCount()
```


Получает количество действительных тегов. Это не общее количество тегов, а число тегов, которые могут быть сохранены.

**Returns:**
int - Количество действительных тегов.
### getValidTagsCount(TiffDataType[] tags) {#getValidTagsCount-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public static int getValidTagsCount(TiffDataType[] tags)
```


Получает количество допустимых тегов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Теги для проверки. |

**Returns:**
int - Количество допустимых тегов.
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Получает или задает параметры растеризации вектора.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getXPAuthor() {#getXPAuthor--}
```
public final String getXPAuthor()
```


Получает автора изображения, используемого в Windows Explorer.

Значение: Автор изображения, используется Windows Explorer. XPAuthor ( \#getXPAuthor /[.setXPAuthor(String)](../../null/\#setXPAuthor-String-)) игнорируется Windows Explorer, если существует тег Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)).

**Returns:**
java.lang.String - автор изображения, используемый Windows Explorer.
### getXPComment() {#getXPComment--}
```
public final String getXPComment()
```


Получает комментарий к изображению, используемый в Windows Explorer.

Значение: Комментарий к изображению, используется Windows Explorer.

**Returns:**
java.lang.String - комментарий к изображению, используемый Windows Explorer.
### getXPKeywords() {#getXPKeywords--}
```
public final String getXPKeywords()
```


Получает тему изображения, используемую в Windows Explorer.

Значение: Тема изображения, используется Windows Explorer.

**Returns:**
java.lang.String - тема изображения, используемая Windows Explorer.
### getXPSubject() {#getXPSubject--}
```
public final String getXPSubject()
```


Получает информацию об изображении, используемую в Windows Explorer.

Значение: Информация об изображении, используется Windows Explorer.

**Returns:**
java.lang.String - информация об изображении, используемая Windows Explorer.
### getXPTitle() {#getXPTitle--}
```
public final String getXPTitle()
```


Получает информацию об изображении, используемую в Windows Explorer.

Значение: Информация об изображении, используется Windows Explorer. XPTitle ( \#getXPTitle /[.setXPTitle(String)](../../null/\#setXPTitle-String-)) игнорируется Windows Explorer, если существует тег ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)).

**Returns:**
java.lang.String - информация об изображении, используемая Windows Explorer.
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Получает или задает контейнер метаданных XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### getXposition() {#getXposition--}
```
public TiffRational getXposition()
```


Получает или задает позицию по оси X.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x position.
### getXresolution() {#getXresolution--}
```
public TiffRational getXresolution()
```


Получает или задаёт разрешение по оси X.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The x resolution.
### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


Получает или задает коэффициенты YCbCr.

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Коэффициенты YCbCr.
### getYCbCrSubsampling() {#getYCbCrSubsampling--}
```
public int[] getYCbCrSubsampling()
```


Получает или задает коэффициенты субдискретизации для фотометрии YCbCr.

**Returns:**
int[] - Факторы субдискретизации для фотометрии YCbCr.
### getYposition() {#getYposition--}
```
public TiffRational getYposition()
```


Получает или задает позицию по оси Y.

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The y position.
### getYresolution() {#getYresolution--}
```
public TiffRational getYresolution()
```


Получает или задаёт разрешение по оси Y.

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


Получает значение, указывающее, присутствуют ли дополнительные образцы.

**Returns:**
boolean -  true  если присутствуют дополнительные образцы; иначе,  false .
### isTagPresent(int tag) {#isTagPresent-int-}
```
public boolean isTagPresent(int tag)
```


Определяет, присутствует ли тег в параметрах или нет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тег | int | Идентификатор тега для проверки. |

**Returns:**
boolean -  true  если тег присутствует; иначе,  false .
### isTiled() {#isTiled--}
```
public boolean isTiled()
```


Получает значение, указывающее, разбита ли изображение на плитки.

**Returns:**
boolean -  true  если изображение разбито на плитки; иначе,  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Получает значение, указывающее, правильно ли настроены  TiffOptions. Используйте метод Validate, чтобы найти причину ошибки.

**Returns:**
boolean -  true  если TiffOptions правильно настроены; иначе,  false .
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


Удаляет тег.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тег | int | Тег для удаления. |

**Returns:**
boolean - true если успешно удалено
### setAlphaStorage(int value) {#setAlphaStorage-int-}
```
public void setAlphaStorage(int value)
```


Получает или задает параметр хранения альфа‑канала. Параметры, отличные от  TiffAlphaStorage.Unspecified  используются, когда определено более 3  SamplesPerPixel  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Опция хранения альфа-канала. |

### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Получает или задаёт исполнителя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Автор. |

### setBackgroundColor_internalized(Color value) {#setBackgroundColor-internalized-com.aspose.psd.Color-}
```
public void setBackgroundColor_internalized(Color value)
```


Получает или задает цвет фона. Используется в внутренних целях для хранения цвета фона изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | Цвет фона. |

### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Устанавливает биты на образец.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | значение | int[] | Значение бит на образец. |

При установке этого значения имейте в виду, что оно также задаст значение SamplesPerPixel равным длине массива. Эти 2 свойства очень тесно связаны, поэтому могут устанавливаться только вместе. |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов.

Значение: подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setByteOrder(int value) {#setByteOrder-int-}
```
public void setByteOrder(int value)
```


Получает или задает значение, указывающее порядок байтов tiff.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColorMap(int[] value) {#setColorMap-int---}
```
public void setColorMap(int[] value)
```


Получает или задает карту цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] | Карта цветов. |

### setCompressedQuality(int value) {#setCompressedQuality-int-}
```
public final void setCompressedQuality(int value)
```


Устанавливает качество сжатого изображения. Используется с компрессией Jpeg.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Качество сжатого изображения. |

### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Устанавливает сжатие.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Сжатие. |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Устанавливает авторские права.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Авторские права. |

### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Получает или задает дату и время.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Дата и время. |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Получает или задает предельный размер выделения памяти по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Ограничение выделения памяти по умолчанию. |

### setDefaultReplacementFont(String value) {#setDefaultReplacementFont-java.lang.String-}
```
public void setDefaultReplacementFont(String value)
```


Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растр, если шрифт существующего слоя в файле PSD не представлен в системе). Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() \{ DefaultReplacementFont = defaultFontName \});

Значение: Шрифт замены по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setDocumentName(String value) {#setDocumentName-java.lang.String-}
```
public void setDocumentName(String value)
```


Получает или задает имя документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Имя документа. |

### setExtraSamples_internalized(int[] value) {#setExtraSamples-internalized-int---}
```
public void setExtraSamples_internalized(int[] value)
```


Устанавливает значения дополнительных образцов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] | Значение дополнительных образцов. |

### setFaxT4Options(long value) {#setFaxT4Options-long-}
```
public void setFaxT4Options(long value)
```


Получает или задает параметры fax t4.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long | Опции fax t4. |

### setFileStandard(int value) {#setFileStandard-int-}
```
public void setFileStandard(int value)
```


Получает или задает стандарт TIFF‑файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Стандарт файла TIFF. |

### setFillOrder(int value) {#setFillOrder-int-}
```
public void setFillOrder(int value)
```


Получает или задает порядок заполнения битов байта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Порядок заполнения байтовых бит. |

### setFullFrame(boolean value) {#setFullFrame-boolean-}
```
public final void setFullFrame(boolean value)
```


Устанавливает значение, указывающее, является ли [full frame].

Значение:  true  если [full frame]; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, является ли [full frame]. |

### setHalfToneHints(int[] value) {#setHalfToneHints-int---}
```
public void setHalfToneHints(int[] value)
```


Получает или задает подсказки полутонов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] | Подсказки полутонов. |

### setIccProfile(byte[] value) {#setIccProfile-byte---}
```
public void setIccProfile(byte[] value)
```


Устанавливает поток ICC‑профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] | icc профиль. |

### setIgnoreAfterCreate_internalized(boolean value) {#setIgnoreAfterCreate-internalized-boolean-}
```
public final void setIgnoreAfterCreate_internalized(boolean value)
```


Получает или задает значение, указывающее, следует ли игнорировать событие после создания.

Значение:  true  если игнорировать после события создания; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Получает или задаёт описание изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Описание изображения. |

### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Получает или задаёт длину изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long | Длина изображения. |

### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Получает или задаёт ширину изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long | Ширина изображения. |

### setInkNames(String value) {#setInkNames-java.lang.String-}
```
public void setInkNames(String value)
```


Получает или задает названия чернил.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Названия чернил. |

### setMaxSampleValue(int[] value) {#setMaxSampleValue-int---}
```
public void setMaxSampleValue(int[] value)
```


Получает или задает максимальное значение образца.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] | Максимальное значение образца. |

### setMinSampleValue(int[] value) {#setMinSampleValue-int---}
```
public void setMinSampleValue(int[] value)
```


Получает или задает минимальное значение образца.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] | Минимальное значение образца. |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Многостраничные параметры

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Получает или задаёт ориентацию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Ориентация. |

### setPageName(String value) {#setPageName-java.lang.String-}
```
public void setPageName(String value)
```


Получает или задает имя страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Имя страницы. |

### setPageNumber(int[] value) {#setPageNumber-int---}
```
public void setPageNumber(int[] value)
```


Получает или задает тег номера страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] | Тег номера страницы. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Получает или задает цветовую палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | Цветовая палитра. |

### setPhotometric(int value) {#setPhotometric-int-}
```
public void setPhotometric(int value)
```


Получает или задает фотометрический параметр.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Фотометрический. |

### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Получает или задаёт планарную конфигурацию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Плоская конфигурация. |

### setPredictor(int value) {#setPredictor-int-}
```
public void setPredictor(int value)
```


Получает или задает предсказатель для LZW‑сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Тип предиктора. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Получает или задает значение, указывающее, должны ли компоненты быть предварительно умножены.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true, если компоненты должны быть предварительно умножены; иначе false. |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setProgressEventHandler(ProgressEventHandler value)
```


Получает или задает обработчик события прогресса.

Значение: обработчик события прогресса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Получает или задает настройки разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Получает или задаёт единицу измерения разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Единица разрешения. |

### setRowsPerStrip(long value) {#setRowsPerStrip-long-}
```
public void setRowsPerStrip(long value)
```


Получает или задает количество строк в полосе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long | Строки на полосу. |

### setSampleFormat(int[] value) {#setSampleFormat-int---}
```
public void setSampleFormat(int[] value)
```


Получает или задает формат образца.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] | Формат образца. |

### setScannerManufacturer(String value) {#setScannerManufacturer-java.lang.String-}
```
public void setScannerManufacturer(String value)
```


Получает или задает производителя сканера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Производитель сканера. |

### setScannerModel(String value) {#setScannerModel-java.lang.String-}
```
public void setScannerModel(String value)
```


Получает или задает модель сканера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Модель сканера. |

### setSmaxSampleValue(long[] value) {#setSmaxSampleValue-long---}
```
public void setSmaxSampleValue(long[] value)
```


Получает или задает максимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long[] | Максимальное значение образца. |

### setSminSampleValue(long[] value) {#setSminSampleValue-long---}
```
public void setSminSampleValue(long[] value)
```


Получает или задает минимальное значение образца. Значение имеет тип поля, который лучше всего соответствует данным образца (тип Byte, Short или Long).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long[] | Минимальное значение образца. |

### setSoftwareType(String value) {#setSoftwareType-java.lang.String-}
```
public void setSoftwareType(String value)
```


Получает или задает тип программного обеспечения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Тип программного обеспечения. |

### setSource(Source value) {#setSource-com.aspose.psd.Source-}
```
public final void setSource(Source value)
```


Получает или задает источник, в котором создаётся изображение.

Значение: Источник, в котором создаётся изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Source](../../com.aspose.psd/source) |  |

### setStripByteCounts(long[] value) {#setStripByteCounts-long---}
```
public void setStripByteCounts(long[] value)
```


Получает или задает количество байтов в полосе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long[] | Количество байтов в полосе. |

### setStripOffsets(long[] value) {#setStripOffsets-long---}
```
public void setStripOffsets(long[] value)
```


Получает или задает смещения полос.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long[] | Смещения полос. |

### setSubFileType(long value) {#setSubFileType-long-}
```
public void setSubFileType(long value)
```


Получает или задает общее указание типа данных, содержащихся в этом подфайле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long | Общее указание типа данных, содержащихся в этом подфайле. |

### setTags(TiffDataType[] value) {#setTags-com.aspose.psd.fileformats.tiff.TiffDataType---}
```
public void setTags(TiffDataType[] value)
```


Получает или задает теги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Теги. |

### setTargetPrinter(String value) {#setTargetPrinter-java.lang.String-}
```
public void setTargetPrinter(String value)
```


Получает или задает целевой принтер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Целевой принтер. |

### setThreshholding(int value) {#setThreshholding-int-}
```
public void setThreshholding(int value)
```


Получает или задает пороговое значение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Пороговое значение. |

### setTileByteCounts(long[] value) {#setTileByteCounts-long---}
```
public void setTileByteCounts(long[] value)
```


Получает или задает количество байтов в плитке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long[] |  |

### setTileLength(long value) {#setTileLength-long-}
```
public void setTileLength(long value)
```


Получает или задает длину плитки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setTileOffsets(long[] value) {#setTileOffsets-long---}
```
public void setTileOffsets(long[] value)
```


Получает или задает смещения плитки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long[] |  |

### setTileWidth(long value) {#setTileWidth-long-}
```
public void setTileWidth(long value)
```


Получает или задает ширину плитки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Получает или задает параметры растеризации вектора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setXPAuthor(String value) {#setXPAuthor-java.lang.String-}
```
public final void setXPAuthor(String value)
```


Устанавливает автора изображения, который используется в Windows Explorer.

Значение: Image Author, используется Windows Explorer. XPAuthor ([.getXPAuthor](../../null/\#getXPAuthor)/ \#setXPAuthor(String) ) игнорируется Windows Explorer, если тег Artist ([.getArtist](../../null/\#getArtist)/[.setArtist(String)](../../null/\#setArtist-String-)) существует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Автор изображения, используется Windows Explorer. |

### setXPComment(String value) {#setXPComment-java.lang.String-}
```
public final void setXPComment(String value)
```


Устанавливает комментарий к изображению, который используется в Windows Explorer.

Значение: Комментарий к изображению, используется Windows Explorer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Комментарий к изображению, используется Windows Explorer. |

### setXPKeywords(String value) {#setXPKeywords-java.lang.String-}
```
public final void setXPKeywords(String value)
```


Устанавливает тему изображения, которая используется в Windows Explorer.

Значение: Тема изображения, используется Windows Explorer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Тема изображения, используется Windows Explorer. |

### setXPSubject(String value) {#setXPSubject-java.lang.String-}
```
public final void setXPSubject(String value)
```


Устанавливает информацию об изображении, которая используется в Windows Explorer.

Значение: Информация об изображении, используется Windows Explorer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Информация об изображении, используется Windows Explorer. |

### setXPTitle(String value) {#setXPTitle-java.lang.String-}
```
public final void setXPTitle(String value)
```


Устанавливает информацию об изображении, которая используется в Windows Explorer.

Значение: Information about image, используется Windows Explorer. XPTitle ([.getXPTitle](../../null/\#getXPTitle)/ \#setXPTitle(String) ) игнорируется Windows Explorer, если тег ImageDescription ([.getImageDescription](../../null/\#getImageDescription)/[.setImageDescription(String)](../../null/\#setImageDescription-String-)) существует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String | Информация об изображении, используется Windows Explorer. |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Получает или задает контейнер метаданных XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Контейнер данных XMP. |

### setXposition(TiffRational value) {#setXposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXposition(TiffRational value)
```


Получает или задает позицию по оси X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Позиция x. |

### setXresolution(TiffRational value) {#setXresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setXresolution(TiffRational value)
```


Получает или задаёт разрешение по оси X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Разрешение по оси x. |

### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


Получает или задает коэффициенты YCbCr.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Коэффициенты YCbCr. |

### setYCbCrSubsampling(int[] value) {#setYCbCrSubsampling-int---}
```
public void setYCbCrSubsampling(int[] value)
```


Получает или задает коэффициенты субдискретизации для фотометрии YCbCr.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] | Коэффициенты субдискретизации для фотометрии YCbCr. |

### setYposition(TiffRational value) {#setYposition-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYposition(TiffRational value)
```


Получает или задает позицию по оси Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Позиция по оси y. |

### setYresolution(TiffRational value) {#setYresolution-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void setYresolution(TiffRational value)
```


Получает или задаёт разрешение по оси Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Разрешение по оси y. |

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


Проверяет, имеет ли набор параметров допустимую комбинацию тегов

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

