---
title: "MaskingOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет общие параметры маскирования изображения."
type: docs
weight: 16
url: /ru/java/com.aspose.psd.masking.options/maskingoptions/
---

**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Представляет общие параметры маскирования изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Номер фонового объекта |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgs()](#getArgs--) | Получает аргументы алгоритма сегментации. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Получает цвет замены фона. |
| [getClass()](#getClass--) |  |
| [getDecompose()](#getDecompose--) | Получает значение, указывающее, необходимо ли разделять каждую Shape из маски как отдельный объект или как объединённый объект из маски, отделённый от фона. |
| [getExportOptions()](#getExportOptions--) | Получает параметры экспорта изображения. |
| [getMaskingArea()](#getMaskingArea--) | Получает область маски. |
| [getMethod()](#getMethod--) | Получает метод сегментации. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | Устанавливает аргументы алгоритма сегментации. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | Устанавливает цвет замены фона. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Устанавливает значение, указывающее, необходимо ли разделять каждую Shape из маски как отдельный объект или как объединённый объект из маски, отделённый от фона. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | Устанавливает параметры экспорта изображения. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | Устанавливает область маски. |
| [setMethod(int value)](#setMethod-int-) | Устанавливает метод сегментации. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Номер фонового объекта

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
### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Получает аргументы алгоритма сегментации.

Значение: аргументы алгоритма сегментации.

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Получает цвет замены фона.

Значение: цвет замены фона. Этот цвет будет использоваться в качестве фонового цвета в получаемых изображениях.

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Получает значение, указывающее, необходимо ли разделять каждую Shape из маски как отдельный объект или как объединённый объект из маски, отделённый от фона.

Значение:  true  если разложить; иначе,  false .

**Returns:**
boolean - значение, указывающее, необходимо ли разделять каждую Shape из маски как отдельный объект или как объединённый объект из маски, отделённый от фона.
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Получает параметры экспорта изображения.

Значение: параметры экспорта изображения, которые будут использованы для создания получаемых изображений.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
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

