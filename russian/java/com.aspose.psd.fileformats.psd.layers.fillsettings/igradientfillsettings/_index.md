---
title: "IGradientFillSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Базовый интерфейс для настроек градиентной заливки."
type: docs
weight: 23
url: /ru/java/com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
```
public interface IGradientFillSettings extends IFillSettings
```

Базовый интерфейс для настроек градиентной заливки.
## Методы

| Метод | Описание |
| --- | --- |
| [getAlignWithLayer()](#getAlignWithLayer--) | Получает или задает значение, указывающее, [align with layer]. |
| [getAngle()](#getAngle--) | Получает или задает угол. |
| [getDither()](#getDither--) | Получает или задает значение, указывающее, является ли этот [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) дезерированным. |
| [getGradient()](#getGradient--) | Получает или задает конкретный экземпляр определения градиента (Solid/Noise). |
| [getGradientType()](#getGradientType--) | Получает или задает тип градиента. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Получает или задает горизонтальное смещение. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Получает или задает метод интерполяции для градиента. |
| [getReverse()](#getReverse--) | Получает или задает значение, указывающее, является ли этот [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) обратным. |
| [getScale()](#getScale--) | Получает или задает  **normalized**  масштаб градиента (в процентах). |
| [getVerticalOffset()](#getVerticalOffset--) | Получает или задает вертикальное смещение. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Получает или задает значение, указывающее, [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Получает или задает угол. |
| [setDither(boolean value)](#setDither-boolean-) | Получает или задает значение, указывающее, является ли этот [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) дезерированным. |
| [setGradient(BaseGradient value)](#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-) | Получает или задает конкретный экземпляр определения градиента (Solid/Noise). |
| [setGradientType(int value)](#setGradientType-int-) | Получает или задает тип градиента. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Получает или задает горизонтальное смещение. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Получает или задает метод интерполяции для градиента. |
| [setReverse(boolean value)](#setReverse-boolean-) | Получает или задает значение, указывающее, является ли этот [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) обратным. |
| [setScale(int value)](#setScale-int-) | Получает или задает  **normalized**  масштаб градиента (в процентах). |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Получает или задает вертикальное смещение. |
### getAlignWithLayer() {#getAlignWithLayer--}
```
public abstract boolean getAlignWithLayer()
```


Получает или задает значение, указывающее, [align with layer].

Значение:  true  если [align with layer]; иначе,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public abstract double getAngle()
```


Получает или задает угол.

Значение: Угол.

**Returns:**
double
### getDither() {#getDither--}
```
public abstract boolean getDither()
```


Получает или задает значение, указывающее, является ли этот [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) дезерированным.

Значение:  true  если включён дизеринг; иначе  false .

**Returns:**
boolean
### getGradient() {#getGradient--}
```
public abstract BaseGradient getGradient()
```


Получает или задает конкретный экземпляр определения градиента (Solid/Noise).

**Returns:**
[BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
### getGradientType() {#getGradientType--}
```
public abstract int getGradientType()
```


Получает или задает тип градиента.

Значение: тип градиента.

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public abstract double getHorizontalOffset()
```


Получает или задает горизонтальное смещение.

Значение: Горизонтальное смещение.

**Returns:**
double
### getInterpolationMethod() {#getInterpolationMethod--}
```
public abstract long getInterpolationMethod()
```


Получает или задает метод интерполяции для градиента.

**Returns:**
long
### getReverse() {#getReverse--}
```
public abstract boolean getReverse()
```


Получает или задает значение, указывающее, является ли этот [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) обратным.

Значение:  true  если обратный; иначе  false .

**Returns:**
boolean
### getScale() {#getScale--}
```
public abstract int getScale()
```


Получает или задает  **normalized**  масштаб градиента (в процентах).

Значение: Масштаб.

**Returns:**
int
### getVerticalOffset() {#getVerticalOffset--}
```
public abstract double getVerticalOffset()
```


Получает или задает вертикальное смещение.

Значение: Вертикальное смещение.

**Returns:**
double
### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public abstract void setAlignWithLayer(boolean value)
```


Получает или задает значение, указывающее, [align with layer].

Значение:  true  если [align with layer]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public abstract void setAngle(double value)
```


Получает или задает угол.

Значение: Угол.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setDither(boolean value) {#setDither-boolean-}
```
public abstract void setDither(boolean value)
```


Получает или задает значение, указывающее, является ли этот [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) дезерированным.

Значение:  true  если включён дизеринг; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setGradient(BaseGradient value) {#setGradient-com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient-}
```
public abstract void setGradient(BaseGradient value)
```


Получает или задает конкретный экземпляр определения градиента (Solid/Noise).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient) |  |

### setGradientType(int value) {#setGradientType-int-}
```
public abstract void setGradientType(int value)
```


Получает или задает тип градиента.

Значение: тип градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public abstract void setHorizontalOffset(double value)
```


Получает или задает горизонтальное смещение.

Значение: Горизонтальное смещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public abstract void setInterpolationMethod(long value)
```


Получает или задает метод интерполяции для градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public abstract void setReverse(boolean value)
```


Получает или задает значение, указывающее, является ли этот [IGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings) обратным.

Значение:  true  если обратный; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


Получает или задает  **normalized**  масштаб градиента (в процентах).

Значение: Масштаб.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public abstract void setVerticalOffset(double value)
```


Получает или задает вертикальное смещение.

Значение: Вертикальное смещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

