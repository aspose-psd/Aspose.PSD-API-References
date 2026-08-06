---
title: "OuterGlowEffect"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Effet de calque de lueur externe"
type: docs
weight: 15
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Effet de calque de lueur externe
## Méthodes

| Méthode | Description |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Obtient ou définit le mode de fusion. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Calcule et obtient les limites des pixels d'effet en fonction des limites des pixels du calque d'entrée. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Obtient l'entité |
| [getEffectType()](#getEffectType--) | Obtient un type d'effet |
| [getFillColor()](#getFillColor--) | Obtient ou définit la couleur. |
| [getIntensity()](#getIntensity--) | Obtient ou définit l'angle en degrés. |
| [getJitter()](#getJitter--) | Obtient ou définit le bruit. |
| [getNoise()](#getNoise--) | Obtient ou définit le bruit. |
| [getOpacity()](#getOpacity--) | Obtient ou définit l'opacité. |
| [getRange()](#getRange--) | Obtient ou définit le bruit. |
| [getSize()](#getSize--) | Obtient la valeur du flou en pixels. |
| [getSpread()](#getSpread--) | Obtient ou définit l'intensité en pourcentage. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Obtient ou définit l'effet AntiAliasing activé |
| [isSoftBlend()](#isSoftBlend--) | Obtient ou définit une valeur indiquant si [knocks out]. |
| [isVisible()](#isVisible--) | Obtient ou définit une valeur indiquant si cette instance est visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Obtient ou définit l'effet AntiAliasing activé |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtient ou définit le mode de fusion. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Obtient ou définit la couleur. |
| [setIntensity(int value)](#setIntensity-int-) | Obtient ou définit l'angle en degrés. |
| [setJitter(int value)](#setJitter-int-) | Obtient ou définit le bruit. |
| [setNoise(int value)](#setNoise-int-) | Obtient ou définit le bruit. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtient ou définit l'opacité. |
| [setRange(int value)](#setRange-int-) | Obtient ou définit le bruit. |
| [setSize(int value)](#setSize-int-) | Obtient la valeur du flou en pixels. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Obtient ou définit une valeur indiquant si [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Obtient ou définit l'intensité en pourcentage. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtient ou définit une valeur indiquant si cette instance est visible. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Obtient ou définit la couleur.

Valeur: la couleur.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Obtient ou définit l'angle en degrés.

Valeur : l'angle.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Obtient ou définit le bruit.

**Returns:**
int
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
### getRange() {#getRange--}
```
public final int getRange()
```


Obtient ou définit le bruit.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Obtient la valeur du flou en pixels.

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


Obtient ou définit l'effet AntiAliasing activé

Valeur : La distance.

**Returns:**
booléen
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Obtient ou définit une valeur indiquant si [knocks out].

Valeur :  true  si [knocks out] ; sinon,  false .

**Returns:**
booléen
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


Obtient ou définit l'effet AntiAliasing activé

Valeur : La distance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Obtient ou définit la couleur.

Valeur: la couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Obtient ou définit l'angle en degrés.

Valeur : l'angle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Obtient ou définit le bruit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Obtient ou définit le bruit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Obtient la valeur du flou en pixels.

Valeur: la taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Obtient ou définit une valeur indiquant si [knocks out].

Valeur :  true  si [knocks out] ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

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

