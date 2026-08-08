---
title: "ResolutionSetting"
second_title: "Aspose.PSD for Java API Справочник"
description: "Настройка разрешения для параметров сохранения изображения."
type: docs
weight: 92
url: /ru/java/com.aspose.psd/resolutionsetting/
---

**Inheritance:**
java.lang.Object
```
public class ResolutionSetting
```

Настройка разрешения для параметров сохранения изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ResolutionSetting()](#ResolutionSetting--) | Инициализирует новый экземпляр класса  ResolutionSetting . |
| [ResolutionSetting(double horizontalResolution, double verticalResolution)](#ResolutionSetting-double-double-) | Инициализирует новый экземпляр класса  ResolutionSetting . |
## Методы

| Метод | Описание |
| --- | --- |
| [adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)](#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-) | Определяет размер страницы PDF в зависимости от разрешения DPI, полученного из PdfOptions.ResolutionSettings или, если он имеет значения по умолчанию, из самого изображения. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHorizontalResolution()](#getHorizontalResolution--) | Получает или задает горизонтальное разрешение. |
| [getVerticalResolution()](#getVerticalResolution--) | Получает или задает вертикальное разрешение. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Получает или задает горизонтальное разрешение. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Получает или задает вертикальное разрешение. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResolutionSetting() {#ResolutionSetting--}
```
public ResolutionSetting()
```


Инициализирует новый экземпляр класса  ResolutionSetting .

### ResolutionSetting(double horizontalResolution, double verticalResolution) {#ResolutionSetting-double-double-}
```
public ResolutionSetting(double horizontalResolution, double verticalResolution)
```


Инициализирует новый экземпляр класса  ResolutionSetting .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| horizontalResolution | double | Горизонтальное разрешение. |
| verticalResolution | double | Вертикальное разрешение. |

### adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution) {#adjustSizeToDefaultDPI-internalized-com.aspose.psd.SizeF-com.aspose.psd.ResolutionSetting-com.aspose.psd.ResolutionSetting-}
```
public static SizeF adjustSizeToDefaultDPI_internalized(SizeF size, ResolutionSetting originalResolution, ResolutionSetting newResolution)
```


Определяет размер страницы PDF в зависимости от разрешения DPI, полученного из PdfOptions.ResolutionSettings или, если он имеет значения по умолчанию, из самого изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.psd/sizef) | Размер изображения. |
| originalResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Исходное разрешение. |
| newResolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Новое разрешение. |

**Returns:**
[SizeF](../../com.aspose.psd/sizef)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Получает или задает горизонтальное разрешение.

**Returns:**
double
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Получает или задает вертикальное разрешение.

**Returns:**
double
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




### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Получает или задает горизонтальное разрешение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Получает или задает вертикальное разрешение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

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

