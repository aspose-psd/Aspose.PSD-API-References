---
title: "ILayerEffect"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Interfaz para efectos de capa"
type: docs
weight: 20
url: /es/java/com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect/
---
```
public interface ILayerEffect
```

Interfaz para efectos de capa
## Métodos

| Método | Descripción |
| --- | --- |
| [getBlendMode()](#getBlendMode--) | Obtiene o establece el modo de fusión. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada. |
| [getEffectType()](#getEffectType--) | Obtiene un tipo de efecto |
| [getOpacity()](#getOpacity--) | Obtiene o establece la opacidad donde 255 = 100% |
| [isVisible()](#isVisible--) | Obtiene o establece un valor que indica si esta instancia es visible. |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtiene o establece el modo de fusión. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtiene o establece la opacidad donde 255 = 100% |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtiene o establece un valor que indica si esta instancia es visible. |
### getBlendMode() {#getBlendMode--}
```
public abstract long getBlendMode()
```


Obtiene o establece el modo de fusión.

Valor: El modo de fusión.

**Returns:**
long
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public abstract Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de los píxeles de la capa. |
| globalAngle | int | El ángulo global para calcular el ángulo de luz global. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectType() {#getEffectType--}
```
public abstract int getEffectType()
```


Obtiene un tipo de efecto

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public abstract byte getOpacity()
```


Obtiene o establece la opacidad donde 255 = 100%

Valor: La opacidad.

**Returns:**
byte
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Obtiene o establece un valor que indica si esta instancia es visible.

Valor:  true  si esta instancia es visible; de lo contrario,  false .

**Returns:**
boolean
### setBlendMode(long value) {#setBlendMode-long-}
```
public abstract void setBlendMode(long value)
```


Obtiene o establece el modo de fusión.

Valor: El modo de fusión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public abstract void setOpacity(byte value)
```


Obtiene o establece la opacidad donde 255 = 100%

Valor: La opacidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```


Obtiene o establece un valor que indica si esta instancia es visible.

Valor:  true  si esta instancia es visible; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

