---
title: "PsdOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры создания формата файла psd."
type: docs
weight: 21
url: /ru/java/com.aspose.psd.imageoptions/psdoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class PsdOptions extends ImageOptionsBase
```

Параметры создания формата файла psd.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PsdOptions()](#PsdOptions--) | Инициализирует новый экземпляр класса [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdOptions options)](#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-) | Инициализирует новый экземпляр класса [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
| [PsdOptions(PsdImage image)](#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-) | Инициализирует новый экземпляр класса [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundContents()](#getBackgroundContents--) | Получает или задаёт цвет фона. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [getChannelBitsCount()](#getChannelBitsCount--) | Получает или задает количество бит на цветовой канал. |
| [getChannelsCount()](#getChannelsCount--) | Получает или задает количество цветовых каналов. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Получает или задает цветовой режим PSD. |
| [getCompressionMethod()](#getCompressionMethod--) | Получает или задает метод сжатия PSD. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getFullFrame()](#getFullFrame--) | Возвращает значение, указывающее, является ли [полный кадр]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Многостраничные параметры |
| [getPalette()](#getPalette--) | Получает или задает цветовую палитру. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает или задает обработчик события прогресса. |
| [getPsdVersion()](#getPsdVersion--) | Получает или задает версию формата файла. |
| [getRefreshImagePreviewData()](#getRefreshImagePreviewData--) | Получает или задает значение, указывающее, следует ли [refresh image preview data] - параметр, используемый для максимальной совместимости с другими просмотрщиками PSD‑изображений. |
| [getRemoveGlobalTextEngineResource()](#getRemoveGlobalTextEngineResource--) | Получает или задает значение, указывающее, следует ли - Remove the global text engine resource - используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда они не могут быть открыты в Adobe Photoshop после обработки (в основном из‑за отсутствующих шрифтов в текстовых слоях). |
| [getResolutionSettings()](#getResolutionSettings--) | Получает или задает настройки разрешения. |
| [getResources()](#getResources--) | Получает или задает ресурсы PSD. |
| [getSource()](#getSource--) | Получает или задает источник, в котором создаётся изображение. |
| [getUpdateMetadata()](#getUpdateMetadata--) | Получает или задает значение, указывающее, следует ли [update metadata]. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Получает или задает параметры растеризации вектора. |
| [getVersion()](#getVersion--) | Получает или задает версию файла PSD. |
| [getXmpData()](#getXmpData--) | Получить или задать контейнер данных XMP |
| [hashCode()](#hashCode--) |  |
| [isColorModeSet()](#isColorModeSet--) | Показывает, было ли назначено свойство ColorMode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundContents(RawColor value)](#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Получает или задаёт цвет фона. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [setChannelBitsCount(short value)](#setChannelBitsCount-short-) | Получает или задает количество бит на цветовой канал. |
| [setChannelsCount(short value)](#setChannelsCount-short-) | Получает или задает количество цветовых каналов. |
| [setColorMode(short value)](#setColorMode-short-) | Получает или задает цветовой режим PSD. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Получает или задает метод сжатия PSD. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Устанавливает значение, указывающее, является ли [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Многостраничные параметры |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Получает или задает цветовую палитру. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Получает или задает обработчик события прогресса. |
| [setPsdVersion(byte value)](#setPsdVersion-byte-) | Получает или задает версию формата файла. |
| [setRefreshImagePreviewData(boolean value)](#setRefreshImagePreviewData-boolean-) | Получает или задает значение, указывающее, следует ли [refresh image preview data] - параметр, используемый для максимальной совместимости с другими просмотрщиками PSD‑изображений. |
| [setRemoveGlobalTextEngineResource(boolean value)](#setRemoveGlobalTextEngineResource-boolean-) | Получает или задает значение, указывающее, следует ли - Remove the global text engine resource - используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда они не могут быть открыты в Adobe Photoshop после обработки (в основном из‑за отсутствующих шрифтов в текстовых слоях). |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Получает или задает настройки разрешения. |
| [setResources(ResourceBlock[] value)](#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Получает или задает ресурсы PSD. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Получает или задает источник, в котором создаётся изображение. |
| [setUpdateMetadata(boolean value)](#setUpdateMetadata-boolean-) | Получает или задает значение, указывающее, следует ли [update metadata]. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Получает или задает параметры растеризации вектора. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает версию файла PSD. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Получить или задать контейнер данных XMP |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdOptions() {#PsdOptions--}
```
public PsdOptions()
```


Инициализирует новый экземпляр класса [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

### PsdOptions(PsdOptions options) {#PsdOptions-com.aspose.psd.imageoptions.PsdOptions-}
```
public PsdOptions(PsdOptions options)
```


Инициализирует новый экземпляр класса [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Параметры. |

### PsdOptions(PsdImage image) {#PsdOptions-com.aspose.psd.fileformats.psd.PsdImage-}
```
public PsdOptions(PsdImage image)
```


Инициализирует новый экземпляр класса [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Изображение. |

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
### getBackgroundContents() {#getBackgroundContents--}
```
public final RawColor getBackgroundContents()
```


Получает или задает цвет фона. Он виден под прозрачными объектами.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов.

Значение: подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Returns:**
int
### getChannelBitsCount() {#getChannelBitsCount--}
```
public final short getChannelBitsCount()
```


Получает или задает количество бит на цветовой канал.

Значение: количество битов на цветовой канал.

**Returns:**
short
### getChannelsCount() {#getChannelsCount--}
```
public final short getChannelsCount()
```


Получает или задает количество цветовых каналов.

Значение: количество цветовых каналов.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Получает или задает цветовой режим PSD.

Значение: Режим цвета.

**Returns:**
short
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Получает или задает метод сжатия PSD.

Значение: Метод сжатия.

**Returns:**
short
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
### getFullFrame() {#getFullFrame--}
```
public final boolean getFullFrame()
```


Возвращает значение, указывающее, является ли [полный кадр].

Значение:  true  если [full frame]; иначе  false .

**Returns:**
boolean — значение, указывающее, является ли [full frame].
### getIgnoreAfterCreate_internalized() {#getIgnoreAfterCreate-internalized--}
```
public final boolean getIgnoreAfterCreate_internalized()
```


Получает или задает значение, указывающее, следует ли игнорировать событие после создания.

Значение:  true  если игнорировать после события создания; иначе  false .

**Returns:**
boolean
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
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Получает или задает обработчик события прогресса.

Значение: обработчик события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler)
### getPsdVersion() {#getPsdVersion--}
```
public final byte getPsdVersion()
```


Получает или задает версию формата файла. Может быть PSD или PSB.

Значение: версия формата файла.

**Returns:**
byte
### getRefreshImagePreviewData() {#getRefreshImagePreviewData--}
```
public final boolean getRefreshImagePreviewData()
```


Получает или задает значение, указывающее, следует ли [refresh image preview data] - параметр, используемый для максимальной совместимости с другими просмотрщиками PSD‑изображений. Обратите внимание, что отрисовка текстовых слоёв в окончательном макете не поддерживается на платформе Compact Framework.

Значение:  true  если [refresh image preview data]; иначе  false .

**Returns:**
boolean
### getRemoveGlobalTextEngineResource() {#getRemoveGlobalTextEngineResource--}
```
public final boolean getRemoveGlobalTextEngineResource()
```


Получает или задает значение, указывающее, следует ли - Remove the global text engine resource - используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда они не могут быть открыты в Adobe Photoshop после обработки (в основном из‑за отсутствующих шрифтов в текстовых слоях). После использования этой опции пользователь должен выполнить в открытом в Photoshop файле следующее: Меню "Text" -> "Process absent fonts". После этой операции весь текст появится снова. Обратите внимание, что эта операция может вызвать некоторые изменения окончательного макета.

Значение:  true  если [remove global text engine resource]; иначе  false .

**Returns:**
boolean
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Получает или задает настройки разрешения.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
### getResources() {#getResources--}
```
public final ResourceBlock[] getResources()
```


Получает или задает ресурсы PSD. Если значение: NULL - тогда сохраняются оригинальные ImageResources (поведение по умолчанию) Not Empty - тогда сохраняются ресурсы, переданные в это свойство, + [required resources] Empty - тогда сохраняются только [required resources]. Требуемые ресурсы: ResolutionInfoResource, XmpResource

Значение: ресурсы PSD.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getSource() {#getSource--}
```
public final Source getSource()
```


Получает или задает источник, в котором создаётся изображение.

Значение: Источник, в котором создаётся изображение.

**Returns:**
[Source](../../com.aspose.psd/source)
### getUpdateMetadata() {#getUpdateMetadata--}
```
public final boolean getUpdateMetadata()
```


Получает или задает значение, указывающее, следует ли [update metadata]. Если значение истинно, метаданные будут обновлены при сохранении изображения.

Значение:  true  если [update metadata]; иначе  false .

**Returns:**
boolean
### getVectorRasterizationOptions() {#getVectorRasterizationOptions--}
```
public final VectorRasterizationOptions getVectorRasterizationOptions()
```


Получает или задает параметры растеризации вектора.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions)
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Получает или задает версию файла PSD.

Значение: версия файла PSD.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Получить или задать контейнер данных XMP

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isColorModeSet() {#isColorModeSet--}
```
public final boolean isColorModeSet()
```


Показывает, было ли назначено свойство ColorMode.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBackgroundContents(RawColor value) {#setBackgroundContents-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents(RawColor value)
```


Получает или задает цвет фона. Он виден под прозрачными объектами.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setChannelBitsCount(short value) {#setChannelBitsCount-short-}
```
public final void setChannelBitsCount(short value)
```


Получает или задает количество бит на цветовой канал.

Значение: количество битов на цветовой канал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setChannelsCount(short value) {#setChannelsCount-short-}
```
public final void setChannelsCount(short value)
```


Получает или задает количество цветовых каналов.

Значение: количество цветовых каналов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Получает или задает цветовой режим PSD.

Значение: Режим цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Получает или задает метод сжатия PSD.

Значение: Метод сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

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

### setPsdVersion(byte value) {#setPsdVersion-byte-}
```
public final void setPsdVersion(byte value)
```


Получает или задает версию формата файла. Может быть PSD или PSB.

Значение: версия формата файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setRefreshImagePreviewData(boolean value) {#setRefreshImagePreviewData-boolean-}
```
public final void setRefreshImagePreviewData(boolean value)
```


Получает или задает значение, указывающее, следует ли [refresh image preview data] - параметр, используемый для максимальной совместимости с другими просмотрщиками PSD‑изображений. Обратите внимание, что отрисовка текстовых слоёв в окончательном макете не поддерживается на платформе Compact Framework.

Значение:  true  если [refresh image preview data]; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setRemoveGlobalTextEngineResource(boolean value) {#setRemoveGlobalTextEngineResource-boolean-}
```
public final void setRemoveGlobalTextEngineResource(boolean value)
```


Получает или задает значение, указывающее, следует ли - Remove the global text engine resource - используется для некоторых PSD‑файлов с текстовыми слоями, только в случае, когда они не могут быть открыты в Adobe Photoshop после обработки (в основном из‑за отсутствующих шрифтов в текстовых слоях). После использования этой опции пользователь должен выполнить в открытом в Photoshop файле следующее: Меню "Text" -> "Process absent fonts". После этой операции весь текст появится снова. Обратите внимание, что эта операция может вызвать некоторые изменения окончательного макета.

Значение:  true  если [remove global text engine resource]; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Получает или задает настройки разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

### setResources(ResourceBlock[] value) {#setResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setResources(ResourceBlock[] value)
```


Получает или задает ресурсы PSD. Если значение: NULL - тогда сохраняются оригинальные ImageResources (поведение по умолчанию) Not Empty - тогда сохраняются ресурсы, переданные в это свойство, + [required resources] Empty - тогда сохраняются только [required resources]. Требуемые ресурсы: ResolutionInfoResource, XmpResource

Значение: ресурсы PSD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

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

### setUpdateMetadata(boolean value) {#setUpdateMetadata-boolean-}
```
public final void setUpdateMetadata(boolean value)
```


Получает или задает значение, указывающее, следует ли [update metadata]. Если значение истинно, метаданные будут обновлены при сохранении изображения.

Значение:  true  если [update metadata]; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setVectorRasterizationOptions(VectorRasterizationOptions value) {#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void setVectorRasterizationOptions(VectorRasterizationOptions value)
```


Получает или задает параметры растеризации вектора.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Получает или задает версию файла PSD.

Значение: версия файла PSD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Получить или задать контейнер данных XMP

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

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

