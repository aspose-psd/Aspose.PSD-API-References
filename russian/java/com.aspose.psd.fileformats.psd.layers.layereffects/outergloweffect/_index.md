---
title: "OuterGlowEffect"
second_title: "Aspose.PSD for Java API Справочник"
description: "Эффект внешнего свечения слоя"
type: docs
weight: 15
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Эффект внешнего свечения слоя
## Методы

| Метод | Описание |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Получает или задает режим смешивания. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Вычисляет и получает границы пикселей эффекта на основе границ пикселей входного слоя. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Получает сущность. |
| [getEffectType()](#getEffectType--) | Получает тип эффекта |
| [getFillColor()](#getFillColor--) | Получает или задаёт цвет. |
| [getIntensity()](#getIntensity--) | Получает или задаёт угол в градусах. |
| [getJitter()](#getJitter--) | Получает или задаёт шум. |
| [getNoise()](#getNoise--) | Получает или задаёт шум. |
| [getOpacity()](#getOpacity--) | Получает или задает непрозрачность. |
| [getRange()](#getRange--) | Получает или задаёт шум. |
| [getSize()](#getSize--) | Получает значение размытия в пикселях. |
| [getSpread()](#getSpread--) | Получает или задаёт интенсивность в процентах. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Получает или задает включенный эффект AntiAliasing |
| [isSoftBlend()](#isSoftBlend--) | Получает или задаёт значение, указывающее, включено ли [knocks out]. |
| [isVisible()](#isVisible--) | Получает или задает значение, указывающее, видим ли этот экземпляр. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Получает или задает включенный эффект AntiAliasing |
| [setBlendMode(long value)](#setBlendMode-long-) | Получает или задает режим смешивания. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Получает или задаёт цвет. |
| [setIntensity(int value)](#setIntensity-int-) | Получает или задаёт угол в градусах. |
| [setJitter(int value)](#setJitter-int-) | Получает или задаёт шум. |
| [setNoise(int value)](#setNoise-int-) | Получает или задаёт шум. |
| [setOpacity(byte value)](#setOpacity-byte-) | Получает или задает непрозрачность. |
| [setRange(int value)](#setRange-int-) | Получает или задаёт шум. |
| [setSize(int value)](#setSize-int-) | Получает значение размытия в пикселях. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Получает или задаёт значение, указывающее, включено ли [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Получает или задаёт интенсивность в процентах. |
| [setVisible(boolean value)](#setVisible-boolean-) | Получает или задает значение, указывающее, видим ли этот экземпляр. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Получает или задает режим смешивания.

Значение: режим смешивания.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Вычисляет и получает границы пикселей эффекта на основе границ пикселей входного слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы пикселей слоя. |
| globalAngle | int | Глобальный угол для вычисления угла глобального света. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Получает сущность.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Получает тип эффекта

**Returns:**
int
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Получает или задаёт цвет.

Значение: Цвет.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Получает или задаёт угол в градусах.

Значение: Угол.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Получает или задаёт шум.

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Получает или задаёт шум.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Получает или задает непрозрачность.

Значение: непрозрачность.

**Returns:**
byte
### getRange() {#getRange--}
```
public final int getRange()
```


Получает или задаёт шум.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Получает значение размытия в пикселях.

Значение: Размер.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Получает или задаёт интенсивность в процентах.

Значение: растушевка.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAntiAliasing() {#isAntiAliasing--}
```
public final boolean isAntiAliasing()
```


Получает или задает включенный эффект AntiAliasing

Значение: Расстояние.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Получает или задаёт значение, указывающее, включено ли [knocks out].

Значение:  true  если [knocks out]; иначе,  false .

**Returns:**
boolean
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Получает или задает значение, указывающее, видим ли этот экземпляр.

Значение:  true  если этот экземпляр видим; иначе,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


Получает или задает включенный эффект AntiAliasing

Значение: Расстояние.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Получает или задает режим смешивания.

Значение: режим смешивания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Получает или задаёт цвет.

Значение: Цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Получает или задаёт угол в градусах.

Значение: Угол.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Получает или задаёт шум.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Получает или задаёт шум.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Получает или задает непрозрачность.

Значение: непрозрачность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Получает или задаёт шум.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Получает значение размытия в пикселях.

Значение: Размер.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Получает или задаёт значение, указывающее, включено ли [knocks out].

Значение:  true  если [knocks out]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Получает или задаёт интенсивность в процентах.

Значение: растушевка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Получает или задает значение, указывающее, видим ли этот экземпляр.

Значение:  true  если этот экземпляр видим; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

