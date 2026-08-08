---
title: "PatternOverlayEffect"
second_title: "Aspose.PSD for Java API Справочник"
description: "Эффект узора слоя"
type: docs
weight: 16
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class PatternOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

Эффект узора слоя
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
| [getOpacity()](#getOpacity--) | Получает или задает непрозрачность. |
| [getSettings()](#getSettings--) | Получает или задает настройки. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Получает или задает значение, указывающее, видим ли этот экземпляр. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Получает или задает режим смешивания. |
| [setOpacity(byte value)](#setOpacity-byte-) | Получает или задает непрозрачность. |
| [setSettings(PatternFillSettings value)](#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Получает или задает настройки. |
| [setVisible(boolean value)](#setVisible-boolean-) | Получает или задает значение, указывающее, видим ли этот экземпляр. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static PatternOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[PatternOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect)
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
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Получает или задает непрозрачность.

Значение: непрозрачность.

**Returns:**
byte
### getSettings() {#getSettings--}
```
public final PatternFillSettings getSettings()
```


Получает или задает настройки.

Значение: Настройки.

**Returns:**
[PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### setSettings(PatternFillSettings value) {#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public final void setSettings(PatternFillSettings value)
```


Получает или задает настройки.

Значение: Настройки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) |  |

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

