---
title: "InnerShadowEffect"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Binnenste schaduwlaag-effect"
type: docs
weight: 14
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.IShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ishadoweffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class InnerShadowEffect implements IShadowEffect, IInternalLayerEffect
```

Binnenste schaduwlaag-effect
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAngle()](#getAngle--) | Haalt de hoek op of stelt deze in graden. |
| [getBlendMode()](#getBlendMode--) | Haalt op of stelt de mengmodus in. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Haalt de kleur op of stelt deze in. |
| [getDistance()](#getDistance--) | Haalt de afstand op of stelt deze in pixels. |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Bereken en haal de grenzen van effectpixels op op basis van de grenzen van invoerlaagpixels. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Haalt de entiteit op |
| [getEffectType()](#getEffectType--) | Haalt een type effect op |
| [getNoise()](#getNoise--) | Haalt de ruis op of stelt deze in. |
| [getOpacity()](#getOpacity--) | Haalt op of stelt de dekking in. |
| [getSize()](#getSize--) | Haalt de onscherptewaarde op of stelt deze in pixels. |
| [getSpread()](#getSpread--) | Haalt op of stelt de spreiding (afsnijding) in als percentage. |
| [getUseGlobalLight()](#getUseGlobalLight--) | Haalt een waarde op of stelt deze in die aangeeft of [use this angle in all of the layer effects]. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAngle(int value)](#setAngle-int-) | Haalt de hoek op of stelt deze in graden. |
| [setBlendMode(long value)](#setBlendMode-long-) | Haalt op of stelt de mengmodus in. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Haalt de kleur op of stelt deze in. |
| [setDistance(int value)](#setDistance-int-) | Haalt de afstand op of stelt deze in pixels. |
| [setNoise(int value)](#setNoise-int-) | Haalt de ruis op of stelt deze in. |
| [setOpacity(byte value)](#setOpacity-byte-) | Haalt op of stelt de dekking in. |
| [setSize(int value)](#setSize-int-) | Haalt de onscherptewaarde op of stelt deze in pixels. |
| [setSpread(int value)](#setSpread-int-) | Haalt op of stelt de spreiding (afsnijding) in als percentage. |
| [setUseGlobalLight(boolean value)](#setUseGlobalLight-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of [use this angle in all of the layer effects]. |
| [setVisible(boolean value)](#setVisible-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static InnerShadowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[InnerShadowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/innershadoweffect)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final int getAngle()
```


Haalt de hoek op of stelt deze in graden.

Waarde: De hoek.

**Returns:**
int
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Haalt op of stelt de mengmodus in.

Waarde: De mengmodus.

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


Haalt de kleur op of stelt deze in.

Waarde: De kleur.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDistance() {#getDistance--}
```
public final int getDistance()
```


Haalt de afstand op of stelt deze in pixels.

Waarde: De afstand.

**Returns:**
int
### getEffectBounds(Rectangle layerBounds, int globalAngle) {#getEffectBounds-com.aspose.psd.Rectangle-int-}
```
public final Rectangle getEffectBounds(Rectangle layerBounds, int globalAngle)
```


Bereken en haal de grenzen van effectpixels op op basis van de grenzen van invoerlaagpixels.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | De pixelgrenzen van de laag. |
| globalAngle | int | De globale hoek om de globale lichthoek te berekenen. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The bounds of effect pixels based on input layer pixels bounds.
### getEffectEntity_internalized() {#getEffectEntity-internalized--}
```
public final IEffectEntity getEffectEntity_internalized()
```


Haalt de entiteit op

**Returns:**
com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity
### getEffectType() {#getEffectType--}
```
public final int getEffectType()
```


Haalt een type effect op

**Returns:**
int
### getNoise() {#getNoise--}
```
public final int getNoise()
```


Haalt de ruis op of stelt deze in.

**Returns:**
int
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Haalt op of stelt de dekking in.

Waarde: De dekking.

**Returns:**
byte
### getSize() {#getSize--}
```
public final int getSize()
```


Haalt de onscherptewaarde op of stelt deze in pixels.

Waarde: De grootte.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Haalt op of stelt de spreiding (afsnijding) in als percentage.

Waarde: De spreiding.

**Returns:**
int
### getUseGlobalLight() {#getUseGlobalLight--}
```
public final boolean getUseGlobalLight()
```


Haalt een waarde op of stelt deze in die aangeeft of [use this angle in all of the layer effects].

Waarde:  true  als [use global light]; anders,  false .

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


Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is.

Waarde:  true  als deze instantie zichtbaar is; anders,  false .

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


Haalt de hoek op of stelt deze in graden.

Waarde: De hoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Haalt op of stelt de mengmodus in.

Waarde: De mengmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Haalt de kleur op of stelt deze in.

Waarde: De kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDistance(int value) {#setDistance-int-}
```
public final void setDistance(int value)
```


Haalt de afstand op of stelt deze in pixels.

Waarde: De afstand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setNoise(int value) {#setNoise-int-}
```
public final void setNoise(int value)
```


Haalt de ruis op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Haalt op of stelt de dekking in.

Waarde: De dekking.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Haalt de onscherptewaarde op of stelt deze in pixels.

Waarde: De grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Haalt op of stelt de spreiding (afsnijding) in als percentage.

Waarde: De spreiding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setUseGlobalLight(boolean value) {#setUseGlobalLight-boolean-}
```
public final void setUseGlobalLight(boolean value)
```


Haalt een waarde op of stelt deze in die aangeeft of [use this angle in all of the layer effects].

Waarde:  true  als [use global light]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is.

Waarde:  true  als deze instantie zichtbaar is; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

