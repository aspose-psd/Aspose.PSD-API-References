---
title: "StrokeEffect"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "L'effet de contour Adobe Photoshop pour le calque PSD."
type: docs
weight: 17
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

L'effet de contour Adobe® Photoshop® pour le calque PSD.
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
| [getFillSettings()](#getFillSettings--) | Obtient ou définit les paramètres de remplissage. |
| [getOpacity()](#getOpacity--) | Obtient ou définit l'opacité. |
| [getOverprint()](#getOverprint--) | Obtient ou définit une valeur indiquant si ce [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) mélangera le contour avec le contenu du calque actuel. |
| [getPosition()](#getPosition--) | Obtient ou définit la position de l'effet de contour pour contrôler l'alignement de votre contour par rapport au contenu du calque PSD. |
| [getSize()](#getSize--) | Obtient ou définit la largeur de l'effet de contour. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Obtient ou définit une valeur indiquant si cette instance est visible. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Obtient ou définit le mode de fusion. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Obtient ou définit les paramètres de remplissage. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtient ou définit l'opacité. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Obtient ou définit une valeur indiquant si ce [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) mélangera le contour avec le contenu du calque actuel. |
| [setPosition(short value)](#setPosition-short-) | Obtient ou définit la position de l'effet de contour pour contrôler l'alignement de votre contour par rapport au contenu du calque PSD. |
| [setSize(int value)](#setSize-int-) | Obtient ou définit la largeur de l'effet de contour. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtient ou définit une valeur indiquant si cette instance est visible. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Obtient ou définit les paramètres de remplissage.

Valeur : les paramètres de remplissage.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Obtient ou définit l'opacité.

Valeur : l'opacité.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Obtient ou définit une valeur indiquant si ce [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) mélangera le contour avec le contenu du calque actuel.

Valeur :  true  si le contour doit être mélangé avec le contenu du calque actuel ; sinon,  false .

**Returns:**
booléen
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Obtient ou définit la position de l'effet de contour pour contrôler l'alignement de votre contour par rapport au contenu du calque PSD. La valeur peut être [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) pour dessiner le contour à l'intérieur du contenu du calque PSD, ou [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) pour dessiner le contour autour du contenu du calque PSD, et [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) pour dessiner le contour à la fois à l'intérieur et à l'extérieur.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Obtient ou définit la largeur de l'effet de contour.

Valeur : la largeur de l'effet de contour.

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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Obtient ou définit les paramètres de remplissage.

Valeur : les paramètres de remplissage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Obtient ou définit une valeur indiquant si ce [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) mélangera le contour avec le contenu du calque actuel.

Valeur :  true  si le contour doit être mélangé avec le contenu du calque actuel ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Obtient ou définit la position de l'effet de contour pour contrôler l'alignement de votre contour par rapport au contenu du calque PSD. La valeur peut être [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) pour dessiner le contour à l'intérieur du contenu du calque PSD, ou [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) pour dessiner le contour autour du contenu du calque PSD, et [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) pour dessiner le contour à la fois à l'intérieur et à l'extérieur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Obtient ou définit la largeur de l'effet de contour.

Valeur : la largeur de l'effet de contour.

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

