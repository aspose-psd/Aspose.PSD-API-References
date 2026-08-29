---
title: "OuterGlowEffect"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Efecto de capa de resplandor externo"
type: docs
weight: 15
url: /es/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Efecto de capa de resplandor externo
## Métodos

| Método | Descripción |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Obtiene o establece el modo de fusión. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcula y obtiene los límites de los píxeles del efecto basándose en los límites de los píxeles de la capa de entrada. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Obtiene la entidad |
| [getEffectType()](#getEffectType--) | Obtiene un tipo de efecto |
| [getFillColor()](#getFillColor--) | Obtiene o establece el color. |
| [getIntensity()](#getIntensity--) | Obtiene o establece el ángulo en grados. |
| [getJitter()](#getJitter--) | Obtiene o establece el ruido. |
| [getNoise()](#getNoise--) | Obtiene o establece el ruido. |
| [getOpacity()](#getOpacity--) | Obtiene o establece la opacidad. |
| [getRange()](#getRange--) | Obtiene o establece el ruido. |
| [getSize()](#getSize--) | Obtiene el valor de desenfoque en píxeles. |
| [getSpread()](#getSpread--) | Obtiene o establece la intensidad como un porcentaje. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Obtiene o establece el efecto de AntiAliasing habilitado |
| [isSoftBlend()](#isSoftBlend--) | Obtiene o establece un valor que indica si [knocks out]. |
| [isVisible()](#isVisible--) | Obtiene o establece un valor que indica si esta instancia es visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Obtiene o establece el efecto de AntiAliasing habilitado |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtiene o establece el modo de fusión. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Obtiene o establece el color. |
| [setIntensity(int value)](#setIntensity-int-) | Obtiene o establece el ángulo en grados. |
| [setJitter(int value)](#setJitter-int-) | Obtiene o establece el ruido. |
| [setNoise(int value)](#setNoise-int-) | Obtiene o establece el ruido. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtiene o establece la opacidad. |
| [setRange(int value)](#setRange-int-) | Obtiene o establece el ruido. |
| [setSize(int value)](#setSize-int-) | Obtiene el valor de desenfoque en píxeles. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Obtiene o establece un valor que indica si [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Obtiene o establece la intensidad como un porcentaje. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtiene o establece un valor que indica si esta instancia es visible. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Obtiene o establece el color.

Valor: El color.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Obtiene o establece el ángulo en grados.

Valor: El ángulo.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Obtiene o establece el ruido.

**Returns:**
int
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
### getRange() {#getRange--}
```
public final int getRange()
```


Obtiene o establece el ruido.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Obtiene el valor de desenfoque en píxeles.

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


Obtiene o establece el efecto de AntiAliasing habilitado

Valor: La distancia.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Obtiene o establece un valor que indica si [knocks out].

Valor:  true  si [knocks out]; de lo contrario,  false .

**Returns:**
boolean
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


Obtiene o establece el efecto de AntiAliasing habilitado

Valor: La distancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Obtiene o establece el color.

Valor: El color.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Obtiene o establece el ángulo en grados.

Valor: El ángulo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Obtiene o establece el ruido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Obtiene o establece el ruido.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Obtiene el valor de desenfoque en píxeles.

Valor: El tamaño.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Obtiene o establece un valor que indica si [knocks out].

Valor:  true  si [knocks out]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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

