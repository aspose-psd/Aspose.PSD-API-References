---
title: "ILayerEffect"
second_title: "Aspose.PSD for Java API Справочник"
description: "Интерфейс для эффектов слоёв"
type: docs
weight: 20
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

Интерфейс для эффектов слоёв
## Методы

| Метод | Описание |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Получает или задает режим смешивания. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Вычисляет и получает границы пикселей эффекта на основе границ пикселей входного слоя. |
| [getEffectType()](#getEffectType--) | Получает тип эффекта |
| [getOpacity()](#getOpacity--) | Получает или задает непрозрачность, где 255 = 100% |
| [isVisible()](#isVisible--) | Получает или задает значение, указывающее, видим ли этот экземпляр. |
| [setBlendMode(long value)](#setBlendMode-long-) | Получает или задает режим смешивания. |
| [setOpacity(byte value)](#setOpacity-byte-) | Получает или задает непрозрачность, где 255 = 100% |
| [setVisible(boolean value)](#setVisible-boolean-) | Получает или задает значение, указывающее, видим ли этот экземпляр. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


Получает или задает режим смешивания.

Значение: режим смешивания.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Вычисляет и получает границы пикселей эффекта на основе границ пикселей входного слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы пикселей слоя. |
| globalAngle | int | Глобальный угол для вычисления угла глобального света. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


Получает тип эффекта

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


Получает или задает непрозрачность, где 255 = 100%

Значение: непрозрачность.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Получает или задает значение, указывающее, видим ли этот экземпляр.

Значение:  true  если этот экземпляр видим; иначе,  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


Получает или задает режим смешивания.

Значение: режим смешивания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


Получает или задает непрозрачность, где 255 = 100%

Значение: непрозрачность.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Получает или задает значение, указывающее, видим ли этот экземпляр.

Значение:  true  если этот экземпляр видим; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

