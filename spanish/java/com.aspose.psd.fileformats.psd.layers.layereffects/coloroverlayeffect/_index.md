---
title: "ColorOverlayEffect"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Efecto de capa de superposición de color"
type: docs
weight: 11
url: /es/java/com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class ColorOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

Efecto de capa de superposición de color
## Métodos

| Método | Descripción |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Obtiene o establece el modo de fusión. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtiene o establece el color. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Obtiene la entidad |
| [getEffectType()](#getEffectType--) | Obtiene un tipo de efecto |
| [getOpacity()](#getOpacity--) | Obtiene o establece la opacidad. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Obtiene o establece un valor que indica si esta instancia es visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtiene o establece el modo de fusión. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Obtiene o establece el color. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtiene o establece la opacidad. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtiene o establece un valor que indica si esta instancia es visible. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static ColorOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[ColorOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/coloroverlayeffect)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Obtiene o establece el modo de fusión.

Valor: El modo de fusión.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Obtiene o establece el color.

Valor: El color.

**Returns:**
[Color](../../com.aspose.psd/color)
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Los límites de los píxeles de la capa. |
| globalAngle | int | El ángulo global para calcular el ángulo de luz global. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Obtiene la entidad

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Obtiene un tipo de efecto

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Obtiene o establece la opacidad.

Valor: La opacidad.

**Returns:**
byte
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


Obtiene o establece un valor que indica si esta instancia es visible.

Valor:  true  si esta instancia es visible; de lo contrario,  false .

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


Obtiene o establece el modo de fusión.

Valor: El modo de fusión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Obtiene o establece el color.

Valor: El color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Obtiene o establece la opacidad.

Valor: La opacidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Obtiene o establece un valor que indica si esta instancia es visible.

Valor:  true  si esta instancia es visible; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

