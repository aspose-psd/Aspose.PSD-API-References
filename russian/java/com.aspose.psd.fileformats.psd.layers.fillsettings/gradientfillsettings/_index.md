---
title: "GradientFillSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Настройки эффекта заливки градиентом."
type: docs
weight: 14
url: /ru/java/com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings)
```
public class GradientFillSettings extends BaseFillSettings implements IGradientFillSettings
```

Настройки эффекта заливки градиентом.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GradientFillSettings()](#GradientFillSettings--) | Инициализирует новый экземпляр класса [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
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
| [getContainerBounds_internalized()](#getContainerBounds-internalized--) | Получает или задает границы контейнера слоя для корректного вычисления позиции градиента. |
| [getDenormalizedScale_internalized(Size fillArea)](#getDenormalizedScale-internalized-com.aspose.psd.Size-) | Вычисляет и возвращает  **denormalized**  масштаб градиента (UI Scale), соответствующий текущему значению  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [getDither()](#getDither--) | Получает или задает значение, указывающее, применяется ли дизеринг к этому [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
| [getFillType()](#getFillType--) | Тип заливки. |
| [getGradient()](#getGradient--) | Получает или задает конкретный экземпляр определения градиента (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Получает или задает тип градиента. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Получает или задает горизонтальное смещение в процентах. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Получает или задает метод интерполяции для градиента. |
| [getReverse()](#getReverse--) | Получает или задает значение, указывающее, является ли этот [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) обратным. |
| [getScale()](#getScale--) | Получает или задает  **normalized**  масштаб градиента (в процентах) |
| [getVerticalOffset()](#getVerticalOffset--) | Получает или задает вертикальное смещение в процентах. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Вызывает событие изменения значения. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Получает или задает значение, указывающее, [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Получает или задает угол. |
| [setContainerBounds_internalized(Rectangle value)](#setContainerBounds-internalized-com.aspose.psd.Rectangle-) | Получает или задает границы контейнера слоя для корректного вычисления позиции градиента. |
| [setDenormalizedScale_internalized(int value, Size fillArea)](#setDenormalizedScale-internalized-int-com.aspose.psd.Size-) | Преобразует указанное денормализованное значение масштаба (UI) в его  **normalized**  эквивалент и назначает его свойству  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). |
| [setDither(boolean value)](#setDither-boolean-) | Получает или задает значение, указывающее, применяется ли дизеринг к этому [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings). |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Получает или задает конкретный экземпляр определения градиента (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Получает или задает тип градиента. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Получает или задает горизонтальное смещение в процентах. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Получает или задает метод интерполяции для градиента. |
| [setReverse(boolean value)](#setReverse-boolean-) | Получает или задает значение, указывающее, является ли этот [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) обратным. |
| [setScale(int value)](#setScale-int-) | Получает или задает  **normalized**  масштаб градиента (в процентах) |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Получает или задает вертикальное смещение в процентах. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GradientFillSettings() {#GradientFillSettings--}
```
public GradientFillSettings()
```


Инициализирует новый экземпляр класса [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

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
### getContainerBounds_internalized() {#getContainerBounds-internalized--}
```
public final Rectangle getContainerBounds_internalized()
```


Получает или задает границы контейнера слоя для корректного вычисления позиции градиента.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getDenormalizedScale_internalized(Size fillArea) {#getDenormalizedScale-internalized-com.aspose.psd.Size-}
```
public final int getDenormalizedScale_internalized(Size fillArea)
```


Вычисляет и возвращает  **denormalized**  масштаб градиента (UI Scale), соответствующий текущему значению  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillArea | [Size](../../com.aspose.psd/size) | Границы градиента. |

**Returns:**
int — Денормализованный (UI) масштаб в процентах, отображаемый в Photoshop.
### getDither() {#getDither--}
```
public final boolean getDither()
```


Получает или задает значение, указывающее, применяется ли дизеринг к этому [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

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
### getGradient() {#getGradient--}
```
public final BaseGradient getGradient()
```


Получает или задает конкретный экземпляр определения градиента (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
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
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Получает или задает метод интерполяции для градиента.

**Returns:**
long
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Получает или задает значение, указывающее, является ли этот [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) обратным.

Значение:  true  если обратный; иначе  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public final int getScale()
```


Получает или задает  **normalized**  масштаб градиента (в процентах)

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

### setContainerBounds_internalized(Rectangle value) {#setContainerBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setContainerBounds_internalized(Rectangle value)
```


Получает или задает границы контейнера слоя для корректного вычисления позиции градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setDenormalizedScale_internalized(int value, Size fillArea) {#setDenormalizedScale-internalized-int-com.aspose.psd.Size-}
```
public final void setDenormalizedScale_internalized(int value, Size fillArea)
```


Преобразует указанное денормализованное значение масштаба (UI) в его  **normalized**  эквивалент и назначает его свойству  Scale ([.getScale](../../null/\#getScale)/[.setScale(int)](../../null/\#setScale-int-)). Преобразование применяет текущий угол градиента ([.getAngle](../../null/\#getAngle)/[.setAngle(double)](../../null/\#setAngle-double-)) и предоставленную  fillArea  для вычисления коэффициента нормализации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Денормализованный масштаб, UI‑масштаб в процентах, отображаемый в Photoshop; |
| fillArea | [Size](../../com.aspose.psd/size) | Границы градиента. |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Получает или задает значение, указывающее, применяется ли дизеринг к этому [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings).

Значение:  true  если включён дизеринг; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public final void setGradient(BaseGradient value)
```


Получает или задает конкретный экземпляр определения градиента (Solid/Noise).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

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

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Получает или задает метод интерполяции для градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Получает или задает значение, указывающее, является ли этот [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) обратным.

Значение:  true  если обратный; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Получает или задает  **normalized**  масштаб градиента (в процентах)

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

