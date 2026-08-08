---
title: "ColorRangeHsl"
second_title: "Aspose.PSD for Java API Справочник"
description: "Содержит 6 цветовых диапазонов, в которых можно изменить параметры HSV."
type: docs
weight: 22
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | Инициализирует новый экземпляр класса [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl). |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | Инициализирует новый экземпляр класса [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl). |
## Методы

| Метод | Описание |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | Получает или задает оттенок. |
| [getLeftBorder()](#getLeftBorder--) | Получает или задает левую границу. |
| [getLightness()](#getLightness--) | Получает или задает яркость. |
| [getMostLeftBorder()](#getMostLeftBorder--) | Получает или задает самую левую границу. |
| [getMostRightBorder()](#getMostRightBorder--) | Получает или задает самую правую границу. |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | Получает коэффициент диапазона. |
| [getRightBorder()](#getRightBorder--) | Получает или задает правую границу. |
| [getSaturation()](#getSaturation--) | Получает или задает насыщенность. |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | Определяет, находится ли оттенок в большом диапазоне. |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | Определяет, находится ли оттенок в небольшом диапазоне. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Сохраняет данные в указанный контейнер потока. |
| [setHue(short value)](#setHue-short-) | Получает или задает оттенок. |
| [setLeftBorder(short value)](#setLeftBorder-short-) | Получает или задает левую границу. |
| [setLightness(short value)](#setLightness-short-) | Получает или задает яркость. |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | Получает или задает самую левую границу. |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | Получает или задает самую правую границу. |
| [setRightBorder(short value)](#setRightBorder-short-) | Получает или задает правую границу. |
| [setSaturation(short value)](#setSaturation-short-) | Получает или задает насыщенность. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


Инициализирует новый экземпляр класса [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl).

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


Инициализирует новый экземпляр класса [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные цветового диапазона. |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mostLeft | short |  |
| left | short |  |
| right | short |  |
| mostRight | short |  |

**Returns:**
[ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl)
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
### getHue() {#getHue--}
```
public final short getHue()
```


Получает или задает оттенок.

Значение: Оттенок.

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


Получает или задает левую границу.

Значение: Левая граница.

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Получает или задает яркость.

Значение: Светлота.

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


Получает или задает самую левую границу.

Значение: Самая левая граница.

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


Получает или задает самую правую границу.

Значение: Самая правая граница.

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


Получает коэффициент диапазона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | double | Значение тона. |

**Returns:**
double - коэффициент диапазона насыщенности.
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


Получает или задает правую границу.

Значение: правый предел.

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Получает или задает насыщенность.

Значение: Насыщенность.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isHueInBigRange(double hue) {#isHueInBigRange-double-}
```
public final boolean isHueInBigRange(double hue)
```


Определяет, находится ли оттенок в большом диапазоне.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | double | Значение тона. |

**Returns:**
boolean -  true  если тон находится в большом диапазоне; иначе,  false .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


Определяет, находится ли оттенок в небольшом диапазоне.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hue | double | Значение тона. |

**Returns:**
boolean -  true  если тон находится в небольшом диапазоне; иначе,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Сохраняет данные в указанный контейнер потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Получает или задает оттенок.

Значение: Оттенок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


Получает или задает левую границу.

Значение: Левая граница.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Получает или задает яркость.

Значение: Светлота.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


Получает или задает самую левую границу.

Значение: Самая левая граница.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


Получает или задает самую правую границу.

Значение: Самая правая граница.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


Получает или задает правую границу.

Значение: правый предел.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Получает или задает насыщенность.

Значение: Насыщенность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

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

