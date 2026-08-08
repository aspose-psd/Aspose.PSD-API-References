---
title: "JpegOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры создания формата файла jpeg."
type: docs
weight: 15
url: /ru/java/com.aspose.psd.imageoptions/jpegoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class JpegOptions extends ImageOptionsBase
```

Параметры создания формата файла jpeg.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Инициализирует новый экземпляр класса  JpegOptions  . |
| [JpegOptions(JpegOptions jpegOptions)](#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-) | Инициализирует новый экземпляр класса  JpegOptions  . |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitsPerChannel()](#getBitsPerChannel--) | Получает количество битов на канал для без потерь jpeg-изображения. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Целевой цветовой профиль CMYK для CMYK jpeg-изображений. |
| [getColorType()](#getColorType--) | Получает тип цвета для jpeg-изображения. |
| [getComment()](#getComment--) | Получает комментарий к файлу jpeg. |
| [getCompressionType()](#getCompressionType--) | Получает тип сжатия. |
| [getDefaultMemoryAllocationLimit()](#getDefaultMemoryAllocationLimit--) | Получает предельный размер выделения памяти по умолчанию. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getExifData()](#getExifData--) | Получить или установить контейнер данных exif |
| [getFullFrame()](#getFullFrame--) | Возвращает значение, указывающее, является ли [полный кадр]. |
| [getHorizontalSampling()](#getHorizontalSampling--) | Получает горизонтальные субдискретизации для каждого компонента. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [getJfif()](#getJfif--) | Получает jfif. |
| [getJpegLsAllowedLossyError()](#getJpegLsAllowedLossyError--) | Получает границу различий JPEG-LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG-LS). |
| [getJpegLsInterleaveMode()](#getJpegLsInterleaveMode--) | Получает режим чередования JPEG-LS. |
| [getJpegLsPreset()](#getJpegLsPreset--) | Получает предустановленные параметры JPEG-LS. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Многостраничные параметры |
| [getPalette()](#getPalette--) | Получает или задает цветовую палитру. |
| [getPreblendAlphaIfPresent()](#getPreblendAlphaIfPresent--) | Получает значение, указывающее, следует ли смешивать красные, зеленые и синие компоненты с фоновым цветом, если присутствует альфа-канал. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает или задает обработчик события прогресса. |
| [getQuality()](#getQuality--) | Получает качество изображения. |
| [getRdOptSettings()](#getRdOptSettings--) | Получает настройки оптимизатора RD. |
| [getResolutionSettings()](#getResolutionSettings--) | Получает или задает настройки разрешения. |
| [getResolutionUnit()](#getResolutionUnit--) | Получает единицу измерения разрешения. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Целевой профиль RGB‑цветов для изображений jpeg в формате CMYK. |
| [getSampleRoundingMode()](#getSampleRoundingMode--) | Получает режим округления образца для приведения 8‑битного значения к n‑битному. |
| [getScaledQuality()](#getScaledQuality--) | Масштабированное качество. |
| [getSource()](#getSource--) | Получает или задает источник, в котором создаётся изображение. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Получает или задает параметры растеризации вектора. |
| [getVerticalSampling()](#getVerticalSampling--) | Получает вертикальные субдискретизации для каждого компонента. |
| [getXmpData()](#getXmpData--) | Получает контейнер метаданных XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | Устанавливает количество бит на канал для без потерь jpeg‑изображения. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Целевой цветовой профиль CMYK для CMYK jpeg-изображений. |
| [setColorType(int value)](#setColorType-int-) | Устанавливает тип цвета для jpeg‑изображения. |
| [setComment(String value)](#setComment-java.lang.String-) | Устанавливает комментарий к файлу jpeg. |
| [setCompressionType(int value)](#setCompressionType-int-) | Устанавливает тип сжатия. |
| [setDefaultMemoryAllocationLimit(int value)](#setDefaultMemoryAllocationLimit-int-) | Устанавливает предельный размер выделения памяти по умолчанию. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [setExifData(JpegExifData value)](#setExifData-com.aspose.psd.exif.JpegExifData-) | Получить или установить контейнер данных exif |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Устанавливает значение, указывающее, является ли [full frame]. |
| [setHorizontalSampling(byte[] value)](#setHorizontalSampling-byte---) | Устанавливает горизонтальные субдискретизации для каждого компонента. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-) | Устанавливает jfif. |
| [setJpegLsAllowedLossyError(int value)](#setJpegLsAllowedLossyError-int-) | Устанавливает границу различий JPEG-LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG-LS). |
| [setJpegLsInterleaveMode(int value)](#setJpegLsInterleaveMode-int-) | Устанавливает режим чередования JPEG-LS. |
| [setJpegLsPreset(JpegLsPresetCodingParameters value)](#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-) | Устанавливает предустановленные параметры JPEG-LS. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Многостраничные параметры |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Получает или задает цветовую палитру. |
| [setPreblendAlphaIfPresent(boolean value)](#setPreblendAlphaIfPresent-boolean-) | Устанавливает значение, указывающее, следует ли смешивать красные, зеленые и синие компоненты с фоновым цветом, если присутствует альфа-канал. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Получает или задает обработчик события прогресса. |
| [setQuality(int value)](#setQuality-int-) | Устанавливает качество изображения. |
| [setRdOptSettings(RdOptimizerSettings value)](#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-) | Устанавливает параметры оптимизатора RD. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Получает или задает настройки разрешения. |
| [setResolutionUnit(byte value)](#setResolutionUnit-byte-) | Устанавливает единицу измерения разрешения. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Целевой профиль RGB‑цветов для изображений jpeg в формате CMYK. |
| [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | Устанавливает режим округления образца для приведения 8-битного значения к n-битному. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Получает или задает источник, в котором создаётся изображение. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Получает или задает параметры растеризации вектора. |
| [setVerticalSampling(byte[] value)](#setVerticalSampling-byte---) | Устанавливает вертикальное субдискретизирование для каждого компонента. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Устанавливает контейнер метаданных XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Инициализирует новый экземпляр класса  JpegOptions  .

### JpegOptions(JpegOptions jpegOptions) {#JpegOptions-com.aspose.psd.imageoptions.JpegOptions-}
```
public JpegOptions(JpegOptions jpegOptions)
```


Инициализирует новый экземпляр класса  JpegOptions  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.psd.imageoptions/jpegoptions) | Параметры JPEG. |

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
### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


Получает количество бит на канал для без потерь JPEG-изображения. Сейчас поддерживается от 2 до 8 бит на канал.

**Returns:**
byte
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов.

Значение: подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


Целевой профиль цвета CMYK для CMYK JPEG-изображений. Используется при сохранении изображений. Должен использоваться вместе с RGBColorProfile для корректного преобразования цветов.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorType() {#getColorType--}
```
public int getColorType()
```


Получает тип цвета для jpeg-изображения.

**Returns:**
int
### getComment() {#getComment--}
```
public String getComment()
```


Получает комментарий к файлу jpeg.

**Returns:**
java.lang.String
### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


Получает тип сжатия.

**Returns:**
int
### getDefaultMemoryAllocationLimit() {#getDefaultMemoryAllocationLimit--}
```
public int getDefaultMemoryAllocationLimit()
```


Получает предельный размер выделения памяти по умолчанию.

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
### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Получить или установить контейнер данных exif

**Returns:**
[JpegExifData](../../com.aspose.psd.exif/jpegexifdata)
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Возвращает значение, указывающее, является ли [полный кадр].

Значение:  true  если [full frame]; иначе  false .

**Returns:**
boolean — значение, указывающее, является ли [full frame].
### getHorizontalSampling() {#getHorizontalSampling--}
```
public byte[] getHorizontalSampling()
```


Получает горизонтальные субдискретизации для каждого компонента.

**Returns:**
byte[]
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Получает или задает значение, указывающее, следует ли игнорировать событие после создания.

Значение:  true  если игнорировать после события создания; иначе  false .

**Returns:**
boolean
### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Получает jfif.

**Returns:**
[JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata)
### getJpegLsAllowedLossyError() {#getJpegLsAllowedLossyError--}
```
public int getJpegLsAllowedLossyError()
```


Получает границу различий JPEG-LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG-LS).

**Returns:**
int
### getJpegLsInterleaveMode() {#getJpegLsInterleaveMode--}
```
public int getJpegLsInterleaveMode()
```


Получает режим чередования JPEG-LS.

**Returns:**
int
### getJpegLsPreset() {#getJpegLsPreset--}
```
public JpegLsPresetCodingParameters getJpegLsPreset()
```


Получает предустановленные параметры JPEG-LS.

**Returns:**
[JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters)
### getMultiPageOptions() {#getMultiPageOptions--}
```
public final MultiPageOptions getMultiPageOptions()
```


Многостраничные параметры

**Returns:**
[MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Получает или задает цветовую палитру.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPreblendAlphaIfPresent() {#getPreblendAlphaIfPresent--}
```
public boolean getPreblendAlphaIfPresent()
```


Получает значение, указывающее, следует ли смешивать красные, зеленые и синие компоненты с фоновым цветом, если присутствует альфа-канал.

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Получает или задает обработчик события прогресса.

Значение: обработчик события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getQuality() {#getQuality--}
```
public int getQuality()
```


Получает качество изображения.

**Returns:**
int
### getRdOptSettings() {#getRdOptSettings--}
```
public RdOptimizerSettings getRdOptSettings()
```


Получает настройки оптимизатора RD.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - The RD optimizer settings.
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Получает или задает настройки разрешения.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResolutionUnit() {#getResolutionUnit--}
```
public final byte getResolutionUnit()
```


Получает единицу измерения разрешения.

**Returns:**
byte - единица измерения разрешения.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


Целевой профиль цвета RGB для CMYK JPEG-изображений. Используется при сохранении изображений. Должен использоваться вместе с CMYKColorProfile для корректного преобразования цветов.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


Получает режим округления образца для приведения 8-битного значения к n-битному.  P:JpegOptions.BitsPerChannel

**Returns:**
int
### getScaledQuality() {#getScaledQuality--}
```
public int getScaledQuality()
```


Масштабированное качество.

**Returns:**
int
### getSource() {#getSource--}
```
public final Source getSource()
```


Получает или задает источник, в котором создаётся изображение.

Значение: Источник, в котором создаётся изображение.

**Returns:**
[Source](../../com.aspose.psd/source)
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Получает или задает параметры растеризации вектора.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVerticalSampling() {#getVerticalSampling--}
```
public byte[] getVerticalSampling()
```


Получает вертикальные субдискретизации для каждого компонента.

**Returns:**
byte[]
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Получает контейнер метаданных XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP data container.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


Устанавливает количество бит на канал для без потерь JPEG-изображения. Сейчас поддерживается от 2 до 8 бит на канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

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

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


Целевой профиль цвета CMYK для CMYK JPEG-изображений. Используется при сохранении изображений. Должен использоваться вместе с RGBColorProfile для корректного преобразования цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Устанавливает тип цвета для jpeg‑изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Устанавливает комментарий к файлу jpeg.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


Устанавливает тип сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDefaultMemoryAllocationLimit(int value) {#setDefaultMemoryAllocationLimit-int-}
```
public void setDefaultMemoryAllocationLimit(int value)
```


Устанавливает предельный размер выделения памяти по умолчанию.

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

### setExifData(JpegExifData value) {#setExifData-com.aspose.psd.exif.JpegExifData-}
```
public void setExifData(JpegExifData value)
```


Получить или установить контейнер данных exif

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.psd.exif/jpegexifdata) |  |

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

### setHorizontalSampling(byte[] value) {#setHorizontalSampling-byte---}
```
public void setHorizontalSampling(byte[] value)
```


Устанавливает горизонтальные субдискретизации для каждого компонента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

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

### setJfif(JFIFData value) {#setJfif-com.aspose.psd.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Устанавливает jfif.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.psd.fileformats.jpeg/jfifdata) |  |

### setJpegLsAllowedLossyError(int value) {#setJpegLsAllowedLossyError-int-}
```
public void setJpegLsAllowedLossyError(int value)
```


Устанавливает границу различий JPEG-LS для почти без потерь кодирования (параметр NEAR из спецификации JPEG-LS).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setJpegLsInterleaveMode(int value) {#setJpegLsInterleaveMode-int-}
```
public void setJpegLsInterleaveMode(int value)
```


Устанавливает режим чередования JPEG-LS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setJpegLsPreset(JpegLsPresetCodingParameters value) {#setJpegLsPreset-com.aspose.psd.fileformats.jpeg.JpegLsPresetCodingParameters-}
```
public void setJpegLsPreset(JpegLsPresetCodingParameters value)
```


Устанавливает предустановленные параметры JPEG-LS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JpegLsPresetCodingParameters](../../com.aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters) |  |

### setMultiPageOptions(MultiPageOptions value) {#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-}
```
public final void setMultiPageOptions(MultiPageOptions value)
```


Многостраничные параметры

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [MultiPageOptions](../../com.aspose.psd.imageoptions/multipageoptions) |  |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Получает или задает цветовую палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPreblendAlphaIfPresent(boolean value) {#setPreblendAlphaIfPresent-boolean-}
```
public void setPreblendAlphaIfPresent(boolean value)
```


Устанавливает значение, указывающее, следует ли смешивать красные, зеленые и синие компоненты с фоновым цветом, если присутствует альфа-канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


Устанавливает качество изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRdOptSettings(RdOptimizerSettings value) {#setRdOptSettings-com.aspose.psd.imageoptions.RdOptimizerSettings-}
```
public void setRdOptSettings(RdOptimizerSettings value)
```


Устанавливает параметры оптимизатора RD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) | Параметры оптимизатора RD. |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Получает или задает настройки разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResolutionUnit(byte value) {#setResolutionUnit-byte-}
```
public final void setResolutionUnit(byte value)
```


Устанавливает единицу измерения разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte | единица измерения разрешения. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


Целевой профиль цвета RGB для CMYK JPEG-изображений. Используется при сохранении изображений. Должен использоваться вместе с CMYKColorProfile для корректного преобразования цветов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


Устанавливает режим округления образца для приведения 8-битного значения к n-битному.  P:JpegOptions.BitsPerChannel

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Получает или задает параметры растеризации вектора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVerticalSampling(byte[] value) {#setVerticalSampling-byte---}
```
public void setVerticalSampling(byte[] value)
```


Устанавливает вертикальное субдискретизирование для каждого компонента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Устанавливает контейнер метаданных XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Контейнер данных XMP. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

