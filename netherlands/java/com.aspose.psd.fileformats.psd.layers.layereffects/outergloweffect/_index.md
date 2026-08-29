---
title: "OuterGlowEffect"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Buitenste gloedlaag-effect"
type: docs
weight: 15
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class OuterGlowEffect implements ILayerEffect, IInternalLayerEffect
```

Buitenste gloedlaag-effect
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [create_internalized(IEffectEntity entity)](#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Haalt op of stelt de mengmodus in. |
| [getClass()](#getClass--) |  |
| [getEffectBounds(Rectangle layerBounds, int globalAngle)](#getEffectBounds-com.aspose.psd.Rectangle-int-) | Bereken en haal de grenzen van effectpixels op op basis van de grenzen van invoerlaagpixels. |
| [getEffectEntity_internalized()](#getEffectEntity-internalized--) | Haalt de entiteit op |
| [getEffectType()](#getEffectType--) | Haalt een type effect op |
| [getFillColor()](#getFillColor--) | Haalt de kleur op of stelt deze in. |
| [getIntensity()](#getIntensity--) | Haalt de hoek op of stelt deze in graden. |
| [getJitter()](#getJitter--) | Haalt de ruis op of stelt deze in. |
| [getNoise()](#getNoise--) | Haalt de ruis op of stelt deze in. |
| [getOpacity()](#getOpacity--) | Haalt op of stelt de dekking in. |
| [getRange()](#getRange--) | Haalt de ruis op of stelt deze in. |
| [getSize()](#getSize--) | Haalt de vervagingswaarde op in pixels. |
| [getSpread()](#getSpread--) | Haalt de intensiteit op of stelt deze in als een percentage. |
| [hashCode()](#hashCode--) |  |
| [isAntiAliasing()](#isAntiAliasing--) | Haalt het ingeschakelde AntiAliasing-effect op of stelt het in |
| [isSoftBlend()](#isSoftBlend--) | Haalt op of stelt een waarde in die aangeeft of [knocks out]. |
| [isVisible()](#isVisible--) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Haalt het ingeschakelde AntiAliasing-effect op of stelt het in |
| [setBlendMode(long value)](#setBlendMode-long-) | Haalt op of stelt de mengmodus in. |
| [setFillColor(IFillSettings value)](#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-) | Haalt de kleur op of stelt deze in. |
| [setIntensity(int value)](#setIntensity-int-) | Haalt de hoek op of stelt deze in graden. |
| [setJitter(int value)](#setJitter-int-) | Haalt de ruis op of stelt deze in. |
| [setNoise(int value)](#setNoise-int-) | Haalt de ruis op of stelt deze in. |
| [setOpacity(byte value)](#setOpacity-byte-) | Haalt op of stelt de dekking in. |
| [setRange(int value)](#setRange-int-) | Haalt de ruis op of stelt deze in. |
| [setSize(int value)](#setSize-int-) | Haalt de vervagingswaarde op in pixels. |
| [setSoftBlend(boolean value)](#setSoftBlend-boolean-) | Haalt op of stelt een waarde in die aangeeft of [knocks out]. |
| [setSpread(int value)](#setSpread-int-) | Haalt de intensiteit op of stelt deze in als een percentage. |
| [setVisible(boolean value)](#setVisible-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static OuterGlowEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[OuterGlowEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/outergloweffect)
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
### getFillColor() {#getFillColor--}
```
public final IFillSettings getFillColor()
```


Haalt de kleur op of stelt deze in.

Waarde: De kleur.

**Returns:**
[IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings)
### getIntensity() {#getIntensity--}
```
public final int getIntensity()
```


Haalt de hoek op of stelt deze in graden.

Waarde: De hoek.

**Returns:**
int
### getJitter() {#getJitter--}
```
public final int getJitter()
```


Haalt de ruis op of stelt deze in.

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
### getRange() {#getRange--}
```
public final int getRange()
```


Haalt de ruis op of stelt deze in.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


Haalt de vervagingswaarde op in pixels.

Waarde: De grootte.

**Returns:**
int
### getSpread() {#getSpread--}
```
public final int getSpread()
```


Haalt de intensiteit op of stelt deze in als een percentage.

Waarde: De spreiding.

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


Haalt het ingeschakelde AntiAliasing-effect op of stelt het in

Waarde: De afstand.

**Returns:**
boolean
### isSoftBlend() {#isSoftBlend--}
```
public final boolean isSoftBlend()
```


Haalt op of stelt een waarde in die aangeeft of [knocks out].

Waarde:  true  als [verwijdert]; anders,  false .

**Returns:**
boolean
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




### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public final void setAntiAliasing(boolean value)
```


Haalt het ingeschakelde AntiAliasing-effect op of stelt het in

Waarde: De afstand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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

### setFillColor(IFillSettings value) {#setFillColor-com.aspose.psd.fileformats.psd.layers.fillsettings.IFillSettings-}
```
public final void setFillColor(IFillSettings value)
```


Haalt de kleur op of stelt deze in.

Waarde: De kleur.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings) |  |

### setIntensity(int value) {#setIntensity-int-}
```
public final void setIntensity(int value)
```


Haalt de hoek op of stelt deze in graden.

Waarde: De hoek.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setJitter(int value) {#setJitter-int-}
```
public final void setJitter(int value)
```


Haalt de ruis op of stelt deze in.

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

### setRange(int value) {#setRange-int-}
```
public final void setRange(int value)
```


Haalt de ruis op of stelt deze in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Haalt de vervagingswaarde op in pixels.

Waarde: De grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### setSoftBlend(boolean value) {#setSoftBlend-boolean-}
```
public final void setSoftBlend(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [knocks out].

Waarde:  true  als [verwijdert]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setSpread(int value) {#setSpread-int-}
```
public final void setSpread(int value)
```


Haalt de intensiteit op of stelt deze in als een percentage.

Waarde: De spreiding.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

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

