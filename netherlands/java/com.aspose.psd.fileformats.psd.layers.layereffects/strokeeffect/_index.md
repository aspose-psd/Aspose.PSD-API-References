---
title: "StrokeEffect"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Het Adobe Photoshop-streek-effect voor de PSD-laag."
type: docs
weight: 17
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layereffects.ILayerEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/ilayereffect), com.aspose.internal.fileformats.psd.layers.layereffects.IInternalLayerEffect
```
public class StrokeEffect implements ILayerEffect, IInternalLayerEffect
```

Het Adobe® Photoshop® lijn-effect voor de PSD-laag.
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
| [getFillSettings()](#getFillSettings--) | Haalt de vulinstellingen op of stelt ze in. |
| [getOpacity()](#getOpacity--) | Haalt op of stelt de dekking in. |
| [getOverprint()](#getOverprint--) | Haalt een waarde op of stelt een waarde in die aangeeft of dit [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) de streek zal mengen met de huidige laaginhoud. |
| [getPosition()](#getPosition--) | Haalt de positie van het streek-effect op of stelt deze in om de uitlijning van uw streek ten opzichte van de PSD-laaginhoud te regelen. |
| [getSize()](#getSize--) | Haalt de breedte van het streek-effect op of stelt deze in. |
| [hashCode()](#hashCode--) |  |
| [isVisible()](#isVisible--) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Haalt op of stelt de mengmodus in. |
| [setFillSettings(BaseFillSettings value)](#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-) | Haalt de vulinstellingen op of stelt ze in. |
| [setOpacity(byte value)](#setOpacity-byte-) | Haalt op of stelt de dekking in. |
| [setOverprint(boolean value)](#setOverprint-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of dit [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) de streek zal mengen met de huidige laaginhoud. |
| [setPosition(short value)](#setPosition-short-) | Haalt de positie van het streek-effect op of stelt deze in om de uitlijning van uw streek ten opzichte van de PSD-laaginhoud te regelen. |
| [setSize(int value)](#setSize-int-) | Haalt de breedte van het streek-effect op of stelt deze in. |
| [setVisible(boolean value)](#setVisible-boolean-) | Haalt een waarde op of stelt een waarde in die aangeeft of dit exemplaar zichtbaar is. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create_internalized(IEffectEntity entity) {#create-internalized-com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity-}
```
public static StrokeEffect create_internalized(IEffectEntity entity)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| entity | com.aspose.internal.fileformats.psd.layers.layereffects.effectentities.IEffectEntity |  |

**Returns:**
[StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect)
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
### getFillSettings() {#getFillSettings--}
```
public final BaseFillSettings getFillSettings()
```


Haalt de vulinstellingen op of stelt ze in.

Waarde: De vulinstellingen.

**Returns:**
[BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Haalt op of stelt de dekking in.

Waarde: De dekking.

**Returns:**
byte
### getOverprint() {#getOverprint--}
```
public final boolean getOverprint()
```


Haalt een waarde op of stelt een waarde in die aangeeft of dit [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) de streek zal mengen met de huidige laaginhoud.

Waarde:  true  als het de streek moet mengen met de huidige laaginhoud; anders,  false .

**Returns:**
boolean
### getPosition() {#getPosition--}
```
public final short getPosition()
```


Haalt de positie van het streek-effect op of stelt deze in om de uitlijning van uw streek ten opzichte van de PSD-laaginhoud te regelen. De waarde kan [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) zijn om de streek binnen de PSD-laaginhoud te tekenen, of [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) om de streek rondom de PSD-laaginhoud te tekenen, en [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) om de streek zowel binnen als buiten te tekenen.

**Returns:**
short
### getSize() {#getSize--}
```
public final int getSize()
```


Haalt de breedte van het streek-effect op of stelt deze in.

Waarde: De breedte van het streek-effect.

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

### setFillSettings(BaseFillSettings value) {#setFillSettings-com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings-}
```
public final void setFillSettings(BaseFillSettings value)
```


Haalt de vulinstellingen op of stelt ze in.

Waarde: De vulinstellingen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings) |  |

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

### setOverprint(boolean value) {#setOverprint-boolean-}
```
public final void setOverprint(boolean value)
```


Haalt een waarde op of stelt een waarde in die aangeeft of dit [StrokeEffect](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeeffect) de streek zal mengen met de huidige laaginhoud.

Waarde:  true  als het de streek moet mengen met de huidige laaginhoud; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

### setPosition(short value) {#setPosition-short-}
```
public final void setPosition(short value)
```


Haalt de positie van het streek-effect op of stelt deze in om de uitlijning van uw streek ten opzichte van de PSD-laaginhoud te regelen. De waarde kan [StrokePosition.Inside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Inside) zijn om de streek binnen de PSD-laaginhoud te tekenen, of [StrokePosition.Outside](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Outside) om de streek rondom de PSD-laaginhoud te tekenen, en [StrokePosition.Center](../../com.aspose.psd.fileformats.psd.layers.layereffects/strokeposition\#Center) om de streek zowel binnen als buiten te tekenen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Haalt de breedte van het streek-effect op of stelt deze in.

Waarde: De breedte van het streek-effect.

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

