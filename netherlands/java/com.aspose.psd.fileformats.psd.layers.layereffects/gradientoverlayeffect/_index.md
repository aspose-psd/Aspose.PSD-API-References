---
title: "GradientOverlayEffect"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Verlooplaag-effect"
type: docs
weight: 13
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class GradientOverlayEffect implements ILayerEffect, IInternalLayerEffect
```

Verlooplaag-effect
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
| [getOpacity()](#getOpacity--) | Haalt op of stelt de dekking in. |
| [getSettings()](#getSettings--) | Haalt de instellingen op of stelt ze in. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Haalt op of stelt de mengmodus in. |
| [setOpacity(byte value)](#setOpacity-byte-) | Haalt op of stelt de dekking in. |
| [setSettings(GradientFillSettings value)](#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings-) | Haalt de instellingen op of stelt ze in. |
| [setVisible(boolean value)](#setVisible-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static GradientOverlayEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[GradientOverlayEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/gradientoverlayeffect)
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
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Haalt op of stelt de dekking in.

Waarde: De dekking.

**Returns:**
byte
### getSettings() {#getSettings--}
```
public final GradientFillSettings getSettings()
```


Haalt de instellingen op of stelt ze in.

Waarde: De instellingen.

**Returns:**
[GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings)
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

### setSettings(GradientFillSettings value) {#setSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings-}
```
public final void setSettings(GradientFillSettings value)
```


Haalt de instellingen op of stelt ze in.

Waarde: De instellingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [GradientFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings) |  |

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

