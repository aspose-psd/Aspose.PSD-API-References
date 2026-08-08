---
title: "NoiseGradientFillSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс определения шумового градиента."
type: docs
weight: 18
url: /ru/java/com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings), [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings)
```
public class NoiseGradientFillSettings extends BaseGradientFillSettings
```

Класс определения шумового градиента.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [NoiseGradientFillSettings()](#NoiseGradientFillSettings--) | Инициализирует новый экземпляр класса [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) . |
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
| [getColorModel()](#getColorModel--) | Получает или задает модель цвета — RGB/HSB/LAB (3/4/6). |
| [getDither()](#getDither--) | Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) дезерированным. |
| [getExpansionCount()](#getExpansionCount--) | Получает или задает количество расширения ( = 2 для Photoshop 6.0). |
| [getFillType()](#getFillType--) | Тип заливки. |
| [getGradientMode()](#getGradientMode--) | Получает режим для этого градиента. |
| [getGradientName()](#getGradientName--) | Получает или задаёт имя градиента. |
| [getGradientType()](#getGradientType--) | Получает или задает тип градиента. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Получает или задает горизонтальное смещение в процентах. |
| [getMaximumColor()](#getMaximumColor--) | Получает или задает максимальный цвет PixelDataFormat. |
| [getMinimumColor()](#getMinimumColor--) | Получает или задает минимальный цвет PixelDataFormat. |
| [getReverse()](#getReverse--) | Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) обратным. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Получает или задает seed случайного числа, используемый для генерации цветов для Noise gradient |
| [getRoughness()](#getRoughness--) | Получает или задает коэффициент шероховатости. |
| [getScale()](#getScale--) | Получает или задает масштаб. |
| [getShowTransparency()](#getShowTransparency--) | Получает или задает флаг отображения прозрачности. |
| [getUseVectorColor()](#getUseVectorColor--) | Получает или задает флаг использования векторного цвета. |
| [getVerticalOffset()](#getVerticalOffset--) | Получает или задает вертикальное смещение в процентах. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Вызывает событие изменения значения. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Получает или задает значение, указывающее, [align with layer]. |
| [setAngle(double value)](#setAngle-double-) | Получает или задает угол. |
| [setColorModel(short value)](#setColorModel-short-) | Получает или задает модель цвета — RGB/HSB/LAB (3/4/6). |
| [setDither(boolean value)](#setDither-boolean-) | Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) дезерированным. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Получает или задает количество расширения ( = 2 для Photoshop 6.0). |
| [setGradientMode_internalized(int value)](#setGradientMode-internalized-int-) | Получает режим для этого градиента. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Получает или задаёт имя градиента. |
| [setGradientType(int value)](#setGradientType-int-) | Получает или задает тип градиента. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) | Получает или задает горизонтальное смещение в процентах. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Получает или задает максимальный цвет PixelDataFormat. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Получает или задает минимальный цвет PixelDataFormat. |
| [setReverse(boolean value)](#setReverse-boolean-) | Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) обратным. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Получает или задает seed случайного числа, используемый для генерации цветов для Noise gradient |
| [setRoughness(int value)](#setRoughness-int-) | Получает или задает коэффициент шероховатости. |
| [setScale(int value)](#setScale-int-) | Получает или задает масштаб. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Получает или задает флаг отображения прозрачности. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Получает или задает флаг использования векторного цвета. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) | Получает или задает вертикальное смещение в процентах. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NoiseGradientFillSettings() {#NoiseGradientFillSettings--}
```
public NoiseGradientFillSettings()
```


Инициализирует новый экземпляр класса [NoiseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/noisegradientfillsettings) .

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Получает или задает модель цвета — RGB/HSB/LAB (3/4/6).

**Returns:**
short
### getDither() {#getDither--}
```
public final boolean getDither()
```


Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) дезерированным.

Значение:  true  если включён дизеринг; иначе  false .

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Получает или задает количество расширения ( = 2 для Photoshop 6.0).

**Returns:**
short
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


Получает или задает максимальный цвет PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


Получает или задает минимальный цвет PixelDataFormat.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Получает или задает значение, указывающее, является ли данный [BaseGradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings) обратным.

Значение:  true  если обратный; иначе  false .

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Получает или задает seed случайного числа, используемый для генерации цветов для Noise gradient

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Получает или задает коэффициент шероховатости.

**Returns:**
int
### getScale() {#getScale--}
```
public final int getScale()
```


Получает или задает масштаб.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Получает или задает флаг отображения прозрачности.

**Returns:**
boolean
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Получает или задает флаг использования векторного цвета.

**Returns:**
boolean
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Получает или задает модель цвета — RGB/HSB/LAB (3/4/6).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

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

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Получает или задает количество расширения ( = 2 для Photoshop 6.0).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

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

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


Получает или задает максимальный цвет PixelDataFormat.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


Получает или задает минимальный цвет PixelDataFormat.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

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

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Получает или задает seed случайного числа, используемый для генерации цветов для Noise gradient

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Получает или задает коэффициент шероховатости.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```


Получает или задает масштаб.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Получает или задает флаг отображения прозрачности.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Получает или задает флаг использования векторного цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

