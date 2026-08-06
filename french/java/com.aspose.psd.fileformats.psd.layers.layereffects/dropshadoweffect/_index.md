---
title: "DropShadowEffect"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Effet de calque d'ombre portée"
type: docs
weight: 12
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class DropShadowEffect implements IShadowEffect, IInternalLayerEffect
```

Effet de calque d'ombre portée
## Méthodes

| Méthode | Description |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Obtient ou définit l'angle en degrés. |
| [getBlendMode()](#getBlendMode--) | Obtient ou définit le mode de fusion. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Obtient ou définit la couleur. |
| [getDistance()](#getDistance--) | Obtient ou définit la distance en pixels. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcule et obtient les limites des pixels d'effet en fonction des limites des pixels du calque d'entrée. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Obtient l'entité |
| [getEffectType()](#getEffectType--) | Obtient un type d'effet |
| [getKnocksOut()](#getKnocksOut--) | Obtient ou définit une valeur indiquant si [knocks out]. |
| [getNoise()](#getNoise--) | Obtient ou définit le bruit. |
| [getOpacity()](#getOpacity--) | Obtient ou définit l'opacité. |
| [getSize()](#getSize--) | Obtient ou définit la valeur de flou en pixels. |
| [getSpread()](#getSpread--) | Obtient ou définit l'intensité en pourcentage. |
| [getUseGlobalLight()](#getUseGlobalLight--) | Obtient ou définit une valeur indiquant si [use this angle in all of the layer effects]. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Obtient ou définit une valeur indiquant si cette instance est visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | Obtient ou définit l'angle en degrés. |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtient ou définit le mode de fusion. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Obtient ou définit la couleur. |
| [setDistance(int value)](#setDistance-int-) | Obtient ou définit la distance en pixels. |
| [setKnocksOut(boolean value)](#setKnocksOut-boolean-) | Obtient ou définit une valeur indiquant si [knocks out]. |
| [setNoise(int value)](#setNoise-int-) | Obtient ou définit le bruit. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtient ou définit l'opacité. |
| [setSize(int value)](#setSize-int-) | Obtient ou définit la valeur de flou en pixels. |
| [setSpread(int value)](#setSpread-int-) | Obtient ou définit l'intensité en pourcentage. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | Obtient ou définit une valeur indiquant si [use this angle in all of the layer effects]. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtient ou définit une valeur indiquant si cette instance est visible. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static DropShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[DropShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/dropshadoweffect)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### getAngle() {#getAngle--}
```
public final int getAngle()
```


Obtient ou définit l'angle en degrés.

Valeur : l'angle.

**Returns:**
int
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Obtient ou définit le mode de fusion.

Valeur : le mode de fusion.

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


Obtient ou définit la couleur.

Valeur: la couleur.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public final int getDistance()
```


Obtient ou définit la distance en pixels.

Valeur : La distance.

**Returns:**
int
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Calcule et obtient les limites des pixels d'effet en fonction des limites des pixels du calque d'entrée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites des pixels du calque. |
| globalAngle | int | L'angle global pour calculer l'angle de lumière global. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Obtient l'entité

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Obtient un type d'effet

**Returns:**
int
### getKnocksOut() {#getKnocksOut--}
```
public final boolean getKnocksOut()
```


Obtient ou définit une valeur indiquant si [knocks out].

Valeur :  true  si [knocks out] ; sinon,  false .

**Returns:**
booléen
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Obtient ou définit le bruit.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Obtient ou définit l'opacité.

Valeur : l'opacité.

**Returns:**
byte
### getSize() {#getSize--}
```
public final int getSize()
```


Obtient ou définit la valeur de flou en pixels.

Valeur: la taille.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Obtient ou définit l'intensité en pourcentage.

Valeur : L'étalement.

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


Obtient ou définit une valeur indiquant si [use this angle in all of the layer effects].

Valeur : true si [use global light] ; sinon, false.

**Returns:**
booléen
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


Obtient ou définit une valeur indiquant si cette instance est visible.

Valeur:  true  si cette instance est visible ; sinon,  false .

**Returns:**
booléen
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


Obtient ou définit l'angle en degrés.

Valeur : l'angle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Obtient ou définit le mode de fusion.

Valeur : le mode de fusion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Obtient ou définit la couleur.

Valeur: la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


Obtient ou définit la distance en pixels.

Valeur : La distance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setKnocksOut(boolean value) {#setKnocksOut-boolean-}
```
public final void setKnocksOut(boolean value)
```


Obtient ou définit une valeur indiquant si [knocks out].

Valeur :  true  si [knocks out] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Obtient ou définit le bruit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Obtient ou définit l'opacité.

Valeur : l'opacité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Obtient ou définit la valeur de flou en pixels.

Valeur: la taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Obtient ou définit l'intensité en pourcentage.

Valeur : L'étalement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


Obtient ou définit une valeur indiquant si [use this angle in all of the layer effects].

Valeur : true si [use global light] ; sinon, false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance est visible.

Valeur:  true  si cette instance est visible ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

