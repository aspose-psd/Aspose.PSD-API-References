---
title: "ColorRangeHsl"
second_title: "Aspose.PSD för Java API-referens"
description: "har 6 färgområden där du kan ändra HSV-parametrar."
type: docs
weight: 22
url: /sv/java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | Initierar en ny instans av [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) klassen. |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | Initierar en ny instans av [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | Hämtar eller anger nyansen. |
| [getLeftBorder()](#getLeftBorder--) | Hämtar eller anger den vänstra gränsen. |
| [getLightness()](#getLightness--) | Hämtar eller anger ljusstyrkan. |
| [getMostLeftBorder()](#getMostLeftBorder--) | Hämtar eller anger den mest vänstra gränsen. |
| [getMostRightBorder()](#getMostRightBorder--) | Hämtar eller anger den mest högra gränsen. |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | Hämtar intervallkoefficienten. |
| [getRightBorder()](#getRightBorder--) | Hämtar eller anger den högra gränsen. |
| [getSaturation()](#getSaturation--) | Hämtar eller anger mättnad. |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | Bestämmer om nyansen är i stort intervall. |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | Bestämmer om nyansen är i litet intervall. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Sparar data till den angivna strömbehållaren. |
| [setHue(short value)](#setHue-short-) | Hämtar eller anger nyansen. |
| [setLeftBorder(short value)](#setLeftBorder-short-) | Hämtar eller anger den vänstra gränsen. |
| [setLightness(short value)](#setLightness-short-) | Hämtar eller anger ljusstyrkan. |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | Hämtar eller anger den mest vänstra gränsen. |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | Hämtar eller anger den mest högra gränsen. |
| [setRightBorder(short value)](#setRightBorder-short-) | Hämtar eller anger den högra gränsen. |
| [setSaturation(short value)](#setSaturation-short-) | Hämtar eller anger mättnad. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


Initierar en ny instans av [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) klassen.

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


Initierar en ny instans av [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Färgområdesdata. |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mostLeft | short |  |
| vänster | short |  |
| höger | short |  |
| mostRight | short |  |

**Returns:**
[ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHue() {#getHue--}
```
public final short getHue()
```


Hämtar eller anger nyansen.

Värde: Nyansen.

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


Hämtar eller anger den vänstra gränsen.

Värde: Den vänstra gränsen.

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Hämtar eller anger ljusstyrkan.

Värde: Ljusstyrkan.

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


Hämtar eller anger den mest vänstra gränsen.

Värde: Den mest vänstra gränsen.

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


Hämtar eller anger den mest högra gränsen.

Värde: Den mest högra gränsen.

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


Hämtar intervallkoefficienten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyans | double | Nyansvärdet. |

**Returns:**
double - Mättnadsintervallkoefficient.
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


Hämtar eller anger den högra gränsen.

Värde: Den högra gränsen.

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Hämtar eller anger mättnad.

Värde: Mättnaden.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isHueInBigRange(double hue) {#isHueInBigRange-double-}
```
public final boolean isHueInBigRange(double hue)
```


Bestämmer om nyansen är i stort intervall.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyans | double | Nyansvärdet. |

**Returns:**
boolean -  true  om nyansen är i stort intervall; annars,  false .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


Bestämmer om nyansen är i litet intervall.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| nyans | double | Nyansvärdet. |

**Returns:**
boolean -  true  om nyansen är i litet intervall; annars,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save(StreamContainer streamContainer) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer streamContainer)
```


Sparar data till den angivna strömbehållaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Strömbehållaren. |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Hämtar eller anger nyansen.

Värde: Nyansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


Hämtar eller anger den vänstra gränsen.

Värde: Den vänstra gränsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Hämtar eller anger ljusstyrkan.

Värde: Ljusstyrkan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


Hämtar eller anger den mest vänstra gränsen.

Värde: Den mest vänstra gränsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


Hämtar eller anger den mest högra gränsen.

Värde: Den mest högra gränsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


Hämtar eller anger den högra gränsen.

Värde: Den högra gränsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Hämtar eller anger mättnad.

Värde: Mättnaden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | short |  |

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

