---
title: "BaseGradientFillSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Базовый класс определения градиента."
type: docs
weight: 11
url: /ru/java/com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public abstract class BaseGradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Класс определения базового градиента. Содержит общие свойства для обоих типов градиента (Solid и Noise).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [BaseGradientFillSettings()](#BaseGradientFillSettings--) | Инициализирует новый экземпляр класса [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings). |
## Поля

| Поле | Описание |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignWithLayer()](#getAlignWithLayer--) | Получает или задает значение, указывающее, [align with layer]. |
| [getAngle()](#getAngle--) | Получает или задает угол. |
| [getClass()](#getClass--) |  |
| [getDither()](#getDither--) | Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) дезерированным. |
| [getFillType()](#getFillType--) | Тип заливки. |
| [getGradientMode()](#getGradientMode--) | Получает режим для этого градиента. |
| [getGradientName()](#getGradientName--) | Получает или задаёт имя градиента. |
| [getGradientType()](#getGradientType--) | Получает или задает тип градиента. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Получает или задает горизонтальное смещение в процентах. |
| [getReverse()](#getReverse--) | Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) обратным. |
| [getScale()](#getScale--) | Получает или задает масштаб. |
| [getVerticalOffset()](#getVerticalOffset--) | Получает или задает вертикальное смещение в процентах. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Вызывает событие изменения значения. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Получает или задает значение, указывающее, [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Получает или задает угол. |
| [setDither(boolean value)](#setDither-boolean-) | Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) дезерированным. |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Получает режим для этого градиента. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Получает или задаёт имя градиента. |
| [setGradientType(int value)](#setGradientType-int-) | Получает или задает тип градиента. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Получает или задает горизонтальное смещение в процентах. |
| [setReverse(boolean value)](#setReverse-boolean-) | Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) обратным. |
| [setScale(int value)](#setScale-int-) | Получает или задает масштаб. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Получает или задает вертикальное смещение в процентах. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BaseGradientFillSettings() {#BaseGradientFillSettings--}
```
public BaseGradientFillSettings()
```


Инициализирует новый экземпляр класса [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Получает или задает значение, указывающее, [align with layer].

Значение:  true  если [align with layer]; иначе,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Получает или задает угол.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDither() {#getDither--}
```
public final boolean getDither()
```


Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) дезерированным.

Значение:  true  если включён дизеринг; иначе  false .

**Returns:**
boolean
### getFillType() {#getFillType--}
```
public int getFillType()
```


Тип заливки.

**Returns:**
int
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Получает режим для этого градиента. Определяет 'Тип градиента' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Получает или задаёт имя градиента.

Значение: Имя градиента.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public final int getGradientType()
```


Получает или задает тип градиента.

Значение: тип градиента.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final double getHorizontalOffset()
```


Получает или задает горизонтальное смещение в процентах.

Значение: Горизонтальное смещение.

**Returns:**
double
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) обратным.

Значение:  true  если обратный; иначе  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Получает или задает масштаб.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public final double getVerticalOffset()
```


Получает или задает вертикальное смещение в процентах.

Значение: Вертикальное смещение.

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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Вызывает событие изменения значения.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Получает или задает значение, указывающее, [align with layer].

Значение:  true  если [align with layer]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Получает или задает угол.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) дезерированным.

Значение:  true  если включён дизеринг; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setGradientMode_internalized(int value) {#setGradientMode-internalized-int-}
```
public final void setGradientMode_internalized(int value)
```


Получает режим для этого градиента. Определяет 'Тип градиента' = 'Solid/Noise' (0/1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Получает или задаёт имя градиента.

Значение: Имя градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public final void setGradientType(int value)
```


Получает или задает тип градиента.

Значение: тип градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public final void setHorizontalOffset(double value)
```


Получает или задает горизонтальное смещение в процентах.

Значение: Горизонтальное смещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) обратным.

Значение:  true  если обратный; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Получает или задает масштаб.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public final void setVerticalOffset(double value)
```


Получает или задает вертикальное смещение в процентах.

Значение: Вертикальное смещение.

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

