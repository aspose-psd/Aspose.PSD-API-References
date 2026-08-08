---
title: "StrokeEffect"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El efecto de trazo de Adobe Photoshop para la capa PSD."
type: docs
weight: 17
url: /es/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

El efecto de trazo de Adobe® Photoshop® para la capa PSD.
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
| [getFillSettings()](#getFillSettings--) | Obtiene o establece la configuración de relleno. |
| [getOpacity()](#getOpacity--) | Obtiene o establece la opacidad. |
| [getOverprint()](#getOverprint--) | Obtiene o establece un valor que indica si este [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) combinará el trazo con el contenido de la capa actual. |
| [getPosition()](#getPosition--) | Obtiene o establece la posición del efecto de trazo para controlar la alineación de su trazo con el contenido de la capa PSD. |
| [getSize()](#getSize--) | Obtiene o establece el ancho del efecto de trazo. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Obtiene o establece un valor que indica si esta instancia es visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtiene o establece el modo de fusión. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Obtiene o establece la configuración de relleno. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtiene o establece la opacidad. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Obtiene o establece un valor que indica si este [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) combinará el trazo con el contenido de la capa actual. |
| [setPosition(short value)](#setPosition-short-) | Obtiene o establece la posición del efecto de trazo para controlar la alineación de su trazo con el contenido de la capa PSD. |
| [setSize(int value)](#setSize-int-) | Obtiene o establece el ancho del efecto de trazo. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtiene o establece un valor que indica si esta instancia es visible. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Obtiene o establece la configuración de relleno.

Valor: La configuración de relleno.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Obtiene o establece la opacidad.

Valor: La opacidad.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Obtiene o establece un valor que indica si este [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) combinará el trazo con el contenido de la capa actual.

Valor:  true  si debe combinar el trazo con el contenido de la capa actual; de lo contrario,  false .

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Obtiene o establece la posición del efecto de trazo para controlar la alineación de su trazo con el contenido de la capa PSD. El valor puede ser [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) para dibujar el trazo dentro del contenido de la capa PSD, o [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) para dibujar el trazo alrededor del contenido de la capa PSD, y [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) para dibujar el trazo tanto dentro como fuera.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Obtiene o establece el ancho del efecto de trazo.

Valor: El ancho del efecto de trazo.

**Returns:**
int
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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Obtiene o establece la configuración de relleno.

Valor: La configuración de relleno.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Obtiene o establece un valor que indica si este [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) combinará el trazo con el contenido de la capa actual.

Valor:  true  si debe combinar el trazo con el contenido de la capa actual; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Obtiene o establece la posición del efecto de trazo para controlar la alineación de su trazo con el contenido de la capa PSD. El valor puede ser [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) para dibujar el trazo dentro del contenido de la capa PSD, o [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) para dibujar el trazo alrededor del contenido de la capa PSD, y [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) para dibujar el trazo tanto dentro como fuera.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Obtiene o establece el ancho del efecto de trazo.

Valor: El ancho del efecto de trazo.

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

