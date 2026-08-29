---
title: "DropShadowEffect"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Efecto de capa de sombra paralela"
type: docs
weight: 12
url: /es/java/com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class DropShadowEffect implements IShadowEffect, IInternalLayerEffect
```

Efecto de capa de sombra paralela
## Métodos

| Método | Descripción |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Obtiene o establece el ángulo en grados. |
| [getBlendMode()](#getBlendMode--) | Obtiene o establece el modo de fusión. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtiene o establece el color. |
| [getDistance()](#getDistance--) | Obtiene o establece la distancia en píxeles. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Obtiene la entidad |
| [getEffectType()](#getEffectType--) | Obtiene un tipo de efecto |
| [getKnocksOut()](#getKnocksOut--) | Obtiene o establece un valor que indica si [knocks out]. |
| [getNoise()](#getNoise--) | Obtiene o establece el ruido. |
| [getOpacity()](#getOpacity--) | Obtiene o establece la opacidad. |
| [getSize()](#getSize--) | Obtiene o establece el valor de desenfoque en píxeles. |
| [getSpread()](#getSpread--) | Obtiene o establece la intensidad como un porcentaje. |
| [getUseGlobalLight()](#getUseGlobalLight--) | Obtiene o establece un valor que indica si [usar este ángulo en todos los efectos de capa]. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Obtiene o establece un valor que indica si esta instancia es visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | Obtiene o establece el ángulo en grados. |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtiene o establece el modo de fusión. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Obtiene o establece el color. |
| [setDistance(int value)](#setDistance-int-) | Obtiene o establece la distancia en píxeles. |
| [setKnocksOut(boolean value)](#setKnocksOut-boolean-) | Obtiene o establece un valor que indica si [knocks out]. |
| [setNoise(int value)](#setNoise-int-) | Obtiene o establece el ruido. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtiene o establece la opacidad. |
| [setSize(int value)](#setSize-int-) | Obtiene o establece el valor de desenfoque en píxeles. |
| [setSpread(int value)](#setSpread-int-) | Obtiene o establece la intensidad como un porcentaje. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | Obtiene o establece un valor que indica si [usar este ángulo en todos los efectos de capa]. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtiene o establece un valor que indica si esta instancia es visible. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static DropShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect)
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
### getAngle() {#getAngle--}
```
public final int getAngle()
```


Obtiene o establece el ángulo en grados.

Valor: El ángulo.

**Returns:**
int
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
### getDistance() {#getDistance--}
```
public final int getDistance()
```


Obtiene o establece la distancia en píxeles.

Valor: La distancia.

**Returns:**
int
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
### getKnocksOut() {#getKnocksOut--}
```
public final boolean getKnocksOut()
```


Obtiene o establece un valor que indica si [knocks out].

Valor:  true  si [knocks out]; de lo contrario,  false .

**Returns:**
boolean
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Obtiene o establece el ruido.

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
### getSize() {#getSize--}
```
public final int getSize()
```


Obtiene o establece el valor de desenfoque en píxeles.

Valor: El tamaño.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Obtiene o establece la intensidad como un porcentaje.

Valor: La propagación.

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


Obtiene o establece un valor que indica si [usar este ángulo en todos los efectos de capa].

Valor:  verdadero  si [use global light]; de lo contrario,  falso .

**Returns:**
boolean
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




### setAngle(int value) {#setAngle-int-}
```
public final void setAngle(int value)
```


Obtiene o establece el ángulo en grados.

Valor: El ángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


Obtiene o establece la distancia en píxeles.

Valor: La distancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setKnocksOut(boolean value) {#setKnocksOut-boolean-}
```
public final void setKnocksOut(boolean value)
```


Obtiene o establece un valor que indica si [knocks out].

Valor:  true  si [knocks out]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Obtiene o establece el ruido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Obtiene o establece el valor de desenfoque en píxeles.

Valor: El tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Obtiene o establece la intensidad como un porcentaje.

Valor: La propagación.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


Obtiene o establece un valor que indica si [usar este ángulo en todos los efectos de capa].

Valor:  verdadero  si [use global light]; de lo contrario,  falso .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

