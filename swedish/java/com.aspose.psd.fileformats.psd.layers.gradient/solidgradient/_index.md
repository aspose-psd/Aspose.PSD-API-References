---
title: "SolidGradient"
second_title: "Aspose.PSD för Java API-referens"
description: "Inställningar för gradientfyllningseffekt."
type: docs
weight: 13
url: /sv/java/com.aspose.psd.fileformats.psd.layers.gradient/solidgradient/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.gradient.BaseGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/basegradient)
```
public class SolidGradient extends BaseGradient
```

Inställningar för gradientfyllningseffekt.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SolidGradient()](#SolidGradient--) | Initierar en ny instans av klassen [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addColorPoint()](#addColorPoint--) | Lägger till färgpunkten. |
| [addTransparencyPoint()](#addTransparencyPoint--) | Lägger till färgpunkten. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes()](#generateLfx2ResourceNodes--) | Genererar LFX2-resursnoderna. |
| [getClass()](#getClass--) |  |
| [getColorPoints()](#getColorPoints--) | Hämtar eller anger färgpunkterna. |
| [getGradientMode()](#getGradientMode--) | Hämtar läget för denna gradient. |
| [getGradientName()](#getGradientName--) | Hämtar eller anger namnet på gradienten. |
| [getInterpolation()](#getInterpolation--) | Hämtar eller anger Interpolation. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Hämtar eller anger transparenspunkterna. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeColorPoint(IGradientColorPoint point)](#removeColorPoint-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint-) | Tar bort färgpunkten. |
| [removeTransparencyPoint(IGradientTransparencyPoint point)](#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-) | Tar bort transparenspunkten. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Hämtar eller anger färgpunkterna. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Hämtar eller anger namnet på gradienten. |
| [setInterpolation(short value)](#setInterpolation-short-) | Hämtar eller anger Interpolation. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Hämtar eller anger transparenspunkterna. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidGradient() {#SolidGradient--}
```
public SolidGradient()
```


Initierar en ny instans av klassen [SolidGradient](../../com.aspose.psd.fileformats.psd.layers.gradient/solidgradient).

### addColorPoint() {#addColorPoint--}
```
public final GradientColorPoint addColorPoint()
```


Lägger till färgpunkten.

**Returns:**
[GradientColorPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) - Created color point
### addTransparencyPoint() {#addTransparencyPoint--}
```
public final GradientTransparencyPoint addTransparencyPoint()
```


Lägger till färgpunkten.

**Returns:**
[GradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) - Created transparency point
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### generateLfx2ResourceNodes() {#generateLfx2ResourceNodes--}
```
public static System.Collections.Generic.List<OSTypeStructure> generateLfx2ResourceNodes()
```


Genererar LFX2-resursnoderna.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Genererad lista över [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
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


Hämtar eller anger färgpunkterna.

Värde: färgpunkterna.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getGradientMode() {#getGradientMode--}
```
public int getGradientMode()
```


Hämtar läget för denna gradient. Bestämmer 'Gradient Type' = 'Solid/Noise' (0/1).

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Hämtar eller anger namnet på gradienten.

Värde: Gradientens namn.

**Returns:**
java.lang.String
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Hämtar eller anger Interpolation. Bestämmer jämnhet, när 'Gradient Type' = 'Solid'. Värdeintervall: 0-4096.

**Returns:**
short
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Hämtar eller anger transparenspunkterna.

Värde: transparenspunkterna.

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


Tar bort färgpunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [IGradientColorPoint](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Punkten. |

### removeTransparencyPoint(IGradientTransparencyPoint point) {#removeTransparencyPoint-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint-}
```
public final void removeTransparencyPoint(IGradientTransparencyPoint point)
```


Tar bort transparenspunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [IGradientTransparencyPoint](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Punkten. |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Hämtar eller anger färgpunkterna.

Värde: färgpunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Hämtar eller anger namnet på gradienten.

Värde: Gradientens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Hämtar eller anger Interpolation. Bestämmer jämnhet, när 'Gradient Type' = 'Solid'. Värdeintervall: 0-4096.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Hämtar eller anger transparenspunkterna.

Värde: transparenspunkterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

