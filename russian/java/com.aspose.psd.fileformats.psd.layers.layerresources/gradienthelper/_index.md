---
title: "GradientHelper"
second_title: "Aspose.PSD for Java API Справочник"
description: "Вспомогательный класс, реализующий преобразование данных для свойств градиента."
type: docs
weight: 34
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/gradienthelper/
---

**Inheritance:**
java.lang.Object
```
public final class GradientHelper
```

Вспомогательный класс, реализующий преобразование данных для свойств градиента.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GradientHelper()](#GradientHelper--) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [IntModelHSB](#IntModelHSB) | Целочисленная константа модели цвета HSBL для градиента шума. |
| [IntModelLAB](#IntModelLAB) | Целочисленная константа модели цвета LBCL для градиента шума. |
| [IntModelRGB](#IntModelRGB) | Целочисленная константа модели цвета RGBC для градиента шума. |
| [StrGradientNoise](#StrGradientNoise) | Константа строки градиента шума. |
| [StrGradientSolid](#StrGradientSolid) | Константа строки сплошного градиента. |
| [StrModelHSB](#StrModelHSB) | Константа строки цветовой модели HSBL для градиента шума. |
| [StrModelLAB](#StrModelLAB) | Константа строки цветовой модели LBCL для градиента шума. |
| [StrModelRGB](#StrModelRGB) | Константа строки цветовой модели RGBC для градиента шума. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [gradientKindToStr(int gradientKind)](#gradientKindToStr-int-) | Преобразовать значение GradientKind в строку. |
| [hashCode()](#hashCode--) |  |
| [intToNoiseColorModel(short colorModel)](#intToNoiseColorModel-short-) | Преобразует целочисленное значение модели цвета шума в NoiseColorModel. |
| [noiseColorModelToInt(short colorModel)](#noiseColorModelToInt-short-) | Преобразует экземпляр NoiseColorModel в целочисленное значение модели цвета шума. |
| [noiseColorModelToStr(short colorModel)](#noiseColorModelToStr-short-) | Преобразовать значение NoiseColorModel в строку. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [strToGradientKind(String str)](#strToGradientKind-java.lang.String-) | Преобразовать строковое значение в GradientKind. |
| [strToNoiseColorModel(String colorModel)](#strToNoiseColorModel-java.lang.String-) | Преобразовать строковое значение в NoiseColorModel. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientHelper() {#GradientHelper--}
```
public GradientHelper()
```


### IntModelHSB {#IntModelHSB}
```
public static final short IntModelHSB
```


Целочисленная константа модели цвета HSBL для градиента шума.

### IntModelLAB {#IntModelLAB}
```
public static final short IntModelLAB
```


Целочисленная константа модели цвета LBCL для градиента шума.

### IntModelRGB {#IntModelRGB}
```
public static final short IntModelRGB
```


Целочисленная константа модели цвета RGBC для градиента шума.

### StrGradientNoise {#StrGradientNoise}
```
public static final String StrGradientNoise
```


Константа строки градиента шума.

### StrGradientSolid {#StrGradientSolid}
```
public static final String StrGradientSolid
```


Константа строки сплошного градиента.

### StrModelHSB {#StrModelHSB}
```
public static final String StrModelHSB
```


Константа строки цветовой модели HSBL для градиента шума.

### StrModelLAB {#StrModelLAB}
```
public static final String StrModelLAB
```


Константа строки цветовой модели LBCL для градиента шума.

### StrModelRGB {#StrModelRGB}
```
public static final String StrModelRGB
```


Константа строки цветовой модели RGBC для градиента шума.

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
### gradientKindToStr(int gradientKind) {#gradientKindToStr-int-}
```
public static String gradientKindToStr(int gradientKind)
```


Преобразовать значение GradientKind в строку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| gradientKind | int | Значение GradientKind. |

**Returns:**
java.lang.String - строковое значение.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### intToNoiseColorModel(short colorModel) {#intToNoiseColorModel-short-}
```
public static short intToNoiseColorModel(short colorModel)
```


Преобразует целочисленное значение модели цвета шума в NoiseColorModel.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorModel | short | Целочисленное значение модели цвета шума. |

**Returns:**
short - экземпляр NoiseColorModel.
### noiseColorModelToInt(short colorModel) {#noiseColorModelToInt-short-}
```
public static short noiseColorModelToInt(short colorModel)
```


Преобразует экземпляр NoiseColorModel в целочисленное значение модели цвета шума.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorModel | short | Экземпляр NoiseColorModel. |

**Returns:**
short - целочисленное значение модели цвета градиента шума.
### noiseColorModelToStr(short colorModel) {#noiseColorModelToStr-short-}
```
public static String noiseColorModelToStr(short colorModel)
```


Преобразовать значение NoiseColorModel в строку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorModel | short | Значение NoiseColorModel. |

**Returns:**
java.lang.String - строковое значение модели цвета.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### strToGradientKind(String str) {#strToGradientKind-java.lang.String-}
```
public static int strToGradientKind(String str)
```


Преобразовать строковое значение в GradientKind.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| str | java.lang.String | строковое значение. |

**Returns:**
int - значение GradientKind.
### strToNoiseColorModel(String colorModel) {#strToNoiseColorModel-java.lang.String-}
```
public static short strToNoiseColorModel(String colorModel)
```


Преобразовать строковое значение в NoiseColorModel.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorModel | java.lang.String | строковое значение. |

**Returns:**
short - значение NoiseColorModel.
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

