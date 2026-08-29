---
title: "SolidGradient"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Instellingen voor gradientvullingseffect."
type: docs
weight: 13
url: /nl/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

Instellingen voor gradientvullingseffect.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | Initialiseert een nieuw exemplaar van de [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | Voegt het kleurpunt toe. |
| [addTransparencyPoint()](#addTransparencyPoint--) | Voegt het kleurpunt toe. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | Genereert de LFX2 resource‑knooppunten. |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | Haalt op of stelt de kleurpunten in. |
| [getGradientMode()](#getGradientMode--) | Haalt de modus op voor deze gradient. |
| [getGradientName()](#getGradientName--) | Haalt de naam van de gradient op of stelt deze in. |
| [getInterpolation()](#getInterpolation--) | Haalt op of stelt Interpolatie in. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Haalt op of stelt de transparantiepunten in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | Verwijdert het kleurpunt. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | Verwijdert het transparantiepunt. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Haalt op of stelt de kleurpunten in. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Haalt de naam van de gradient op of stelt deze in. |
| [setInterpolation(short value)](#setInterpolation-short-) | Haalt op of stelt Interpolatie in. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Haalt op of stelt de transparantiepunten in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


Initialiseert een nieuw exemplaar van de [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient) klasse.

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


Voegt het kleurpunt toe.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


Voegt het kleurpunt toe.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
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
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


Genereert de LFX2 resource‑knooppunten.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Gegenereerde lijst van [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Haalt op of stelt de kleurpunten in.

Waarde: De kleurpunten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


Haalt de modus op voor deze gradient. Bepaalt 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Haalt de naam van de gradient op of stelt deze in.

Waarde: De naam van de gradient.

**Returns:**
java.lang.String
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Haalt op of stelt Interpolatie in. Bepaalt Gladheid, wanneer 'Gradient Type' = 'Solid'. Waarde‑bereik: 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Haalt op of stelt de transparantiepunten in.

Waarde: De transparantiepunten.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeColorPoint(IGradientColorPoint point) {#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-}
```
public final void removeColorPoint(IGradientColorPoint point)
```


Verwijdert het kleurpunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Het punt. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


Verwijdert het transparantiepunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Het punt. |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Haalt op of stelt de kleurpunten in.

Waarde: De kleurpunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Haalt de naam van de gradient op of stelt deze in.

Waarde: De naam van de gradient.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Haalt op of stelt Interpolatie in. Bepaalt Gladheid, wanneer 'Gradient Type' = 'Solid'. Waarde‑bereik: 0-4096.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Haalt op of stelt de transparantiepunten in.

Waarde: De transparantiepunten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

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

