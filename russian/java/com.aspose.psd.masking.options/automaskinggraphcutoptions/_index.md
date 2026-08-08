---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры автоматического маскирования GraphCut."
type: docs
weight: 12
url: /ru/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

Параметры автоматического маскирования GraphCut.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Инициализирует новый экземпляр класса [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions). |
## Поля

| Поле | Описание |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Номер фонового объекта |
## Методы

| Метод | Описание |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | Добавить аргументы автомаскирования. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | Заполнить внутренние стандартные штрихи. |
| [getArgs()](#getArgs--) | Получает аргументы алгоритма сегментации. |
| [getAssumedObjects()](#getAssumedObjects--) | Получает предполагаемые объекты. |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Получает цвет замены фона. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Получает значение, указывающее, следует ли вычислять стандартные штрихи. |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | Получает прямоугольник объединённых объектов. |
| [getDecompose()](#getDecompose--) | Получает значение, указывающее, необходимо ли разделять каждую Shape из маски как отдельный объект или как объединённый объект из маски, отделённый от фона. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Получает стандартные фоновые штрихи. |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Получает предварительно вычисленные стандартные штрихи переднего плана. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Получает стандартные прямоугольники объектов. |
| [getExportOptions()](#getExportOptions--) | Получает параметры экспорта изображения. |
| [getFeatheringRadius()](#getFeatheringRadius--) | Получает радиус растушевки. |
| [getMaskingArea()](#getMaskingArea--) | Получает область маски. |
| [getMethod()](#getMethod--) | Получает метод сегментации. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Получает обработчик события прогресса процесса предварительного расчёта стандартных точек. |
| [hasHumans_internalized()](#hasHumans-internalized--) | Получает значение, указывающее, содержит ли коллекция предполагаемых объектов человеческие объекты. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Устанавливает аргументы алгоритма сегментации. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | Устанавливает предполагаемые объекты. |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Устанавливает цвет замены фона. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Устанавливает значение, указывающее, следует ли вычислять стандартные штрихи. |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | Объединённый прямоугольник объектов. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Устанавливает значение, указывающее, необходимо ли разделять каждую Shape из маски как отдельный объект или как объединённый объект из маски, отделённый от фона. |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | Стандартные фоновые штрихи. |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | Предвычисленные стандартные передние штрихи. |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | Стандартные прямоугольники объектов. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Устанавливает параметры экспорта изображения. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | Устанавливает радиус размытия. |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | Значение, указывающее, содержит ли предполагаемая коллекция объектов человеческие объекты. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Устанавливает область маски. |
| [setMethod(int value)](#setMethod-int-) | Устанавливает метод сегментации. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Устанавливает обработчик события прогресса процесса предварительного расчёта стандартных точек. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Инициализирует новый экземпляр класса [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions).

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Номер фонового объекта

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


Добавить аргументы автомаскирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Изображение. |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


Заполнить внутренние стандартные штрихи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | Изображение. |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Получает аргументы алгоритма сегментации.

Значение: аргументы алгоритма сегментации.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Получает предполагаемые объекты.

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - предполагаемые объекты.
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Получает цвет замены фона.

Значение: цвет замены фона. Этот цвет будет использоваться в качестве фонового цвета в получаемых изображениях.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Получает значение, указывающее, следует ли вычислять стандартные штрихи.

**Returns:**
boolean - значение, указывающее, следует ли рассчитывать стандартные штрихи.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


Получает прямоугольник объединённых объектов.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Получает значение, указывающее, необходимо ли разделять каждую Shape из маски как отдельный объект или как объединённый объект из маски, отделённый от фона.

Значение:  true  если разложить; иначе,  false .

**Returns:**
boolean - значение, указывающее, необходимо ли разделять каждую Shape из маски как отдельный объект или как объединённый объект из маски, отделённый от фона.
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Получает стандартные фоновые штрихи.

**Returns:**
com.aspose.psd.Point[] - стандартные фоновые штрихи.
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Получает предварительно вычисленные стандартные штрихи переднего плана.

**Returns:**
com.aspose.psd.Point[] - предвычисленные стандартные передние штрихи.
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Получает стандартные прямоугольники объектов.

**Returns:**
com.aspose.psd.Rectangle[] - стандартные прямоугольники объектов.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Получает параметры экспорта изображения.

Значение: параметры экспорта изображения, которые будут использованы для создания получаемых изображений.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


Получает радиус растушевки.

**Returns:**
int - радиус размытия.
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Получает область маски.

Значение: область маски, которая является частичной областью исходного изображения. Значение Rectangle.Empty означает полную область исходного изображения.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


Получает метод сегментации.

Значение: метод сегментации.

**Returns:**
int - метод сегментации.
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Получает обработчик события прогресса процесса предварительного расчёта стандартных точек.

Значение: обработчик события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


Получает значение, указывающее, содержит ли коллекция предполагаемых объектов человеческие объекты.

**Returns:**
boolean - значение, указывающее, содержит ли предполагаемая коллекция объектов человеческие объекты.
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Устанавливает аргументы алгоритма сегментации.

Значение: аргументы алгоритма сегментации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | аргументы для алгоритма сегментации. |

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Устанавливает предполагаемые объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | предполагаемые объекты. |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Устанавливает цвет замены фона.

Значение: цвет замены фона. Этот цвет будет использоваться в качестве фонового цвета в получаемых изображениях.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | цвет замены фона. |

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Устанавливает значение, указывающее, следует ли вычислять стандартные штрихи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, следует ли рассчитывать стандартные штрихи. |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


Объединённый прямоугольник объектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | объединённый прямоугольник объектов. |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Устанавливает значение, указывающее, необходимо ли разделять каждую Shape из маски как отдельный объект или как объединённый объект из маски, отделённый от фона.

Значение:  true  если разложить; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, нужно ли разделять каждую Shape от маски как отдельный объект или как объединённый объект от маски, отделённый от фона. |

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


Стандартные фоновые штрихи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | стандартные фоновые штрихи. |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


Предвычисленные стандартные передние штрихи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | предвычисленные стандартные передние штрихи. |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


Стандартные прямоугольники объектов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | стандартные прямоугольники объектов. |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Устанавливает параметры экспорта изображения.

Значение: параметры экспорта изображения, которые будут использованы для создания получаемых изображений.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | параметры экспорта изображения. |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


Устанавливает радиус размытия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | радиус размытия. |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


Значение, указывающее, содержит ли предполагаемая коллекция объектов человеческие объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, содержит ли предполагаемая коллекция объектов человеческие объекты. |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Устанавливает область маски.

Значение: область маски, которая является частичной областью исходного изображения. Значение Rectangle.Empty означает полную область исходного изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | область маскирования. |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Устанавливает метод сегментации.

Значение: метод сегментации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | метод сегментации. |

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Устанавливает обработчик события прогресса процесса предварительного расчёта стандартных точек.

Значение: обработчик события прогресса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | обработчик события прогресса процесса предварительного расчёта стандартных точек. |

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

