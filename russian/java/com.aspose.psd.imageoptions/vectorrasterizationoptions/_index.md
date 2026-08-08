---
title: "VectorRasterizationOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры векторной растеризации."
type: docs
weight: 29
url: /ru/java/com.aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.ImageOptionsBase](../../com.aspose.psd/imageoptionsbase)
```
public class VectorRasterizationOptions extends ImageOptionsBase
```

Параметры векторной растеризации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [clone()](#clone--) |  |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Копирует в. |
| [deepClone()](#deepClone--) | Клонирует этот экземпляр. |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона. |
| [getBorderX()](#getBorderX--) | Получает или задает границу X. |
| [getBorderY()](#getBorderY--) | Получает или задает границу Y. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [getCenterDrawing()](#getCenterDrawing--) | Получает значение, указывающее, выполняется ли центрирование рисования. |
| [getClass()](#getClass--) |  |
| [getDefaultReplacementFont()](#getDefaultReplacementFont--) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getDrawColor()](#getDrawColor--) | Получает цвет переднего плана. |
| [getFullFrame()](#getFullFrame--) | Возвращает значение, указывающее, является ли [полный кадр]. |
| [getIgnoreAfterCreate_internalized()](#getIgnoreAfterCreate-internalized--) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [getMultiPageOptions()](#getMultiPageOptions--) | Многостраничные параметры |
| [getPageHeight()](#getPageHeight--) | Получает высоту страницы. |
| [getPageSize()](#getPageSize--) | Получает размер страницы. |
| [getPageWidth()](#getPageWidth--) | Получает ширину страницы. |
| [getPalette()](#getPalette--) | Получает или задает цветовую палитру. |
| [getPositioning()](#getPositioning--) | Получает позиционирование. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает или задает обработчик события прогресса. |
| [getResolutionSettings()](#getResolutionSettings--) | Получает или задает настройки разрешения. |
| [getSmoothingMode()](#getSmoothingMode--) | Получает режим сглаживания. |
| [getSource()](#getSource--) | Получает или задает источник, в котором создаётся изображение. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Получает подсказку рендеринга текста. |
| [getVectorRasterizationOptions()](#getVectorRasterizationOptions--) | Получает или задает параметры растеризации вектора. |
| [getXmpData()](#getXmpData--) | Получает или задает контейнер метаданных XMP. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Устанавливает цвет фона. |
| [setBorderX(float value)](#setBorderX-float-) | Получает или задает границу X. |
| [setBorderY(float value)](#setBorderY-float-) | Получает или задает границу Y. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Устанавливает значение, указывающее, выполняется ли центрирование рисования. |
| [setDefaultReplacementFont(String value)](#setDefaultReplacementFont-java.lang.String-) | Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.psd.Color-) | Устанавливает цвет переднего плана. |
| [setFullFrame(boolean value)](#setFullFrame-boolean-) | Устанавливает значение, указывающее, является ли [full frame]. |
| [setIgnoreAfterCreate_internalized(boolean value)](#setIgnoreAfterCreate-internalized-boolean-) | Получает или задает значение, указывающее, следует ли игнорировать событие после создания. |
| [setMultiPageOptions(MultiPageOptions value)](#setMultiPageOptions-com.aspose.psd.imageoptions.MultiPageOptions-) | Многостраничные параметры |
| [setPageHeight(float value)](#setPageHeight-float-) | Устанавливает высоту страницы. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.psd.SizeF-) | Устанавливает размер страницы. |
| [setPageWidth(float value)](#setPageWidth-float-) | Устанавливает ширину страницы. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Получает или задает цветовую палитру. |
| [setPositioning(int value)](#setPositioning-int-) | Устанавливает позиционирование. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Получает или задает обработчик события прогресса. |
| [setResolutionSettings(ResolutionSetting value)](#setResolutionSettings-com.aspose.psd.ResolutionSetting-) | Получает или задает настройки разрешения. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Устанавливает режим сглаживания. |
| [setSource(Source value)](#setSource-com.aspose.psd.Source-) | Получает или задает источник, в котором создаётся изображение. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Устанавливает подсказку рендеринга текста. |
| [setVectorRasterizationOptions(VectorRasterizationOptions value)](#setVectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-) | Получает или задает параметры растеризации вектора. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Получает или задает контейнер метаданных XMP. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) |  |

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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.psd.imageoptions.VectorRasterizationOptions-}
```
public final void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Копирует в.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | Параметры векторной растеризации. |

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
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает цвет фона.

**Returns:**
[Color](../../com.aspose.psd/color) - a background color.
### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Получает или задает границу X.

**Returns:**
float - Граница X.
### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Получает или задает границу Y.

**Returns:**
float - Граница Y.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Получает или задает подсказку о размере буфера, определяющую максимальный разрешённый размер для всех внутренних буферов.

Значение: подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Returns:**
int
### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Получает значение, указывающее, выполняется ли центрирование рисования.

**Returns:**
boolean - значение, указывающее, выполняется ли центрирование рисования.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Получает цвет переднего плана.

**Returns:**
[Color](../../com.aspose.psd/color) - a foreground color.
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
### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Получает высоту страницы.

**Returns:**
float - высота страницы.
### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Получает размер страницы.

**Returns:**
[SizeF](../../com.aspose.psd/sizef) - the page size.
### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Получает ширину страницы.

**Returns:**
float - ширина страницы.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Получает или задает цветовую палитру.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Получает позиционирование.

Значение: позиционирование.

**Returns:**
int - позиционирование.
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
### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Получает режим сглаживания.

**Returns:**
int - режим сглаживания.
### getSource() {#getSource--}
```
public final Source getSource()
```


Получает или задает источник, в котором создаётся изображение.

Значение: Источник, в котором создаётся изображение.

**Returns:**
[Source](../../com.aspose.psd/source)
### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Получает подсказку рендеринга текста.

Значение: Подсказка по отрисовке текста.

**Returns:**
int - подсказка по отрисовке текста.
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

Значение: Контейнер данных XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
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




### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Устанавливает цвет фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | цвет фона. |

### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Получает или задает границу X.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Граница X. |

### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Получает или задает границу Y.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Граница Y. |

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

### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Устанавливает значение, указывающее, выполняется ли центрирование рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, следует ли центрировать отрисовку. |

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

### setDrawColor(Color value) {#setDrawColor-com.aspose.psd.Color-}
```
public void setDrawColor(Color value)
```


Устанавливает цвет переднего плана.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | цвет переднего плана. |

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

### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Устанавливает высоту страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | высота страницы. |

### setPageSize(SizeF value) {#setPageSize-com.aspose.psd.SizeF-}
```
public void setPageSize(SizeF value)
```


Устанавливает размер страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.psd/sizef) | размер страницы. |

### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Устанавливает ширину страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | ширина страницы. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Получает или задает цветовую палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Устанавливает позиционирование.

Значение: позиционирование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | позиционирование. |

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

### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Устанавливает режим сглаживания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | режим сглаживания. |

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

### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Устанавливает подсказку рендеринга текста.

Значение: Подсказка по отрисовке текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | подсказка по отрисовке текста. |

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

Значение: Контейнер данных XMP.

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

