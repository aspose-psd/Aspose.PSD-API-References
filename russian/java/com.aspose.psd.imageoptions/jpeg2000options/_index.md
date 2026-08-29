---
title: "Jpeg2000Options"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры формата файла Jpeg2000."
type: docs
weight: 14
url: /ru/java/com.aspose.psd.imageoptions/jpeg2000options/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class Jpeg2000Options extends ImageOptionsBase
```

Параметры формата файла Jpeg2000.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Jpeg2000Options()](#Jpeg2000Options--) | Инициализирует новый экземпляр класса Jpeg2000Options. |
| [Jpeg2000Options(Jpeg2000Options jpeg2000Options)](#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-) | Инициализирует новый экземпляр класса Jpeg2000Options. |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [getClass()](#getClass--) |  |
| [getCodec()](#getCodec--) | Получает или задает кодек JPEG2000 |
| [getComments()](#getComments--) | Получает или задает маркеры комментариев Jpeg. |
| [getCompressionRatios()](#getCompressionRatios--) | Получает или задает массив коэффициентов сжатия. |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getFullFrame()](#getFullFrame--) | Возвращает значение, указывающее, является ли [полный кадр]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [getIrreversible()](#getIrreversible--) | Получает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 (по умолчанию). |
| [getMultiPageOptions()](#getMultiPageOptions--) | Многостраничные параметры |
| [getPalette()](#getPalette--) | Получает или задает цветовую палитру. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает или задает обработчик события прогресса. |
| [getResolutionSettings()](#getResolutionSettings--) | Получает или задает настройки разрешения. |
| [getSource()](#getSource--) | Получает или задает источник, в котором создаётся изображение. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Получает или задает параметры растеризации вектора. |
| [getXmpData()](#getXmpData--) | Получает или задает контейнер метаданных XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [setCodec(int value)](#setCodec-int-) | Получает или задает кодек JPEG2000 |
| [setComments(String[] value)](#setComments-java.lang.String---) | Получает или задает маркеры комментариев Jpeg. |
| [setCompressionRatios(int[] value)](#setCompressionRatios-int---) | Получает или задает массив коэффициентов сжатия. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Устанавливает значение, указывающее, является ли [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [setIrreversible(boolean value)](#setIrreversible-boolean-) | Задает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 (по умолчанию). |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Многостраничные параметры |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Получает или задает цветовую палитру. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Получает или задает обработчик события прогресса. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Получает или задает настройки разрешения. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Получает или задает источник, в котором создаётся изображение. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Получает или задает параметры растеризации вектора. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Получает или задает контейнер метаданных XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000Options() {#Jpeg2000Options--}
```
public Jpeg2000Options()
```


Инициализирует новый экземпляр класса Jpeg2000Options.

### Jpeg2000Options(Jpeg2000Options jpeg2000Options) {#Jpeg2000Options-com.aspose.psd.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Options(Jpeg2000Options jpeg2000Options)
```


Инициализирует новый экземпляр класса Jpeg2000Options.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| jpeg2000Options | [Jpeg2000Options](../../com.aspose.psd.imageoptions/jpeg2000options) | Параметры формата файла Jpeg2000, из которых копировать настройки. |

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
### getCodec() {#getCodec--}
```
public int getCodec()
```


Получает или задает кодек JPEG2000

**Returns:**
int — кодек JPEG2000
### getComments() {#getComments--}
```
public String[] getComments()
```


Получает или задает маркеры комментариев Jpeg.

**Returns:**
java.lang.String[] — маркеры комментариев Jpeg.
### getCompressionRatios() {#getCompressionRatios--}
```
public int[] getCompressionRatios()
```


Получает или задает массив коэффициентов сжатия. Различные коэффициенты сжатия для последовательных слоёв. Указанный коэффициент для каждого уровня качества является требуемым фактором сжатия. Требуются уменьшающиеся коэффициенты.

**Returns:**
int[] — коэффициенты сжатия.
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
### getIrreversible() {#getIrreversible--}
```
public boolean getIrreversible()
```


Получает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 (по умолчанию).

**Returns:**
boolean — значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3.
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
### getResolutionSettings() {#getResolutionSettings--}
```
public ResolutionSetting getResolutionSettings()
```


Получает или задает настройки разрешения.

**Returns:**
[ResolutionSetting](../../com.aspose.psd/resolutionsetting)
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
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Получает или задает контейнер метаданных XMP.

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

### setCodec(int value) {#setCodec-int-}
```
public void setCodec(int value)
```


Получает или задает кодек JPEG2000

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Кодек JPEG2000 |

### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Получает или задает маркеры комментариев Jpeg.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String[] | Маркеры комментариев Jpeg. |

### setCompressionRatios(int[] value) {#setCompressionRatios-int---}
```
public void setCompressionRatios(int[] value)
```


Получает или задает массив коэффициентов сжатия. Различные коэффициенты сжатия для последовательных слоёв. Указанный коэффициент для каждого уровня качества является требуемым фактором сжатия. Требуются уменьшающиеся коэффициенты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] | Коэффициенты сжатия. |

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

### setIrreversible(boolean value) {#setIrreversible-boolean-}
```
public void setIrreversible(boolean value)
```


Задает значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3 (по умолчанию).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, использовать ли необратимый DWT 9-7 (true) или без потерь DWT 5-3. |

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

### setResolutionSettings(ResolutionSetting value) {#setResolutionSettings-com.aspose.psd.ResolutionSetting-}
```
public void setResolutionSettings(ResolutionSetting value)
```


Получает или задает настройки разрешения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) |  |

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

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Получает или задает контейнер метаданных XMP.

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

