---
title: "ColorRangeHsl"
second_title: "Aspose.PSD voor Java API-referentie"
description: "heeft 6 kleurbereiken waarin u HSV-parameters kunt wijzigen."
type: docs
weight: 22
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | Initialiseert een nieuw exemplaar van de [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) klasse. |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | Initialiseert een nieuw exemplaar van de [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | Haalt op of stelt de tint in. |
| [getLeftBorder()](#getLeftBorder--) | Haalt de linkerrand op of stelt deze in. |
| [getLightness()](#getLightness--) | Haalt de lichtheid op of stelt deze in. |
| [getMostLeftBorder()](#getMostLeftBorder--) | Haalt de meest linkerrand op of stelt deze in. |
| [getMostRightBorder()](#getMostRightBorder--) | Haalt de meest rechterrand op of stelt deze in. |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | Haalt de bereikcoëfficiënt op. |
| [getRightBorder()](#getRightBorder--) | Haalt de rechterrand op of stelt deze in. |
| [getSaturation()](#getSaturation--) | Haalt de verzadiging op of stelt deze in. |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | Bepaalt of de tint zich in een groot bereik bevindt. |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | Bepaalt of de tint zich in een klein bereik bevindt. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Slaat gegevens op in de opgegeven streamcontainer. |
| [setHue(short value)](#setHue-short-) | Haalt op of stelt de tint in. |
| [setLeftBorder(short value)](#setLeftBorder-short-) | Haalt de linkerrand op of stelt deze in. |
| [setLightness(short value)](#setLightness-short-) | Haalt de lichtheid op of stelt deze in. |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | Haalt de meest linkerrand op of stelt deze in. |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | Haalt de meest rechterrand op of stelt deze in. |
| [setRightBorder(short value)](#setRightBorder-short-) | Haalt de rechterrand op of stelt deze in. |
| [setSaturation(short value)](#setSaturation-short-) | Haalt de verzadiging op of stelt deze in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


Initialiseert een nieuw exemplaar van de [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) klasse.

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


Initialiseert een nieuw exemplaar van de [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] | De kleurbereikgegevens. |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mostLeft | short |  |
| links | short |  |
| rechts | short |  |
| mostRight | short |  |

**Returns:**
[ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl)
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


Haalt op of stelt de tint in.

Waarde: De tint.

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


Haalt de linkerrand op of stelt deze in.

Waarde: De linkerrand.

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Haalt de lichtheid op of stelt deze in.

Waarde: De lichtheid.

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


Haalt de meest linkerrand op of stelt deze in.

Waarde: De meest linkerrand.

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


Haalt de meest rechterrand op of stelt deze in.

Waarde: De meest rechterrand.

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


Haalt de bereikcoëfficiënt op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | double | De hue-waarde. |

**Returns:**
double - verzadigingsbereikcoëfficiënt.
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


Haalt de rechterrand op of stelt deze in.

Waarde: de rechterrand.

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Haalt de verzadiging op of stelt deze in.

Waarde: De verzadiging.

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


Bepaalt of de tint zich in een groot bereik bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | double | De hue-waarde. |

**Returns:**
boolean -  true  als hue in een groot bereik zit; anders,  false .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


Bepaalt of de tint zich in een klein bereik bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hue | double | De hue-waarde. |

**Returns:**
boolean -  true  als hue in een klein bereik zit; anders,  false .
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


Slaat gegevens op in de opgegeven streamcontainer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | De stream container. |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Haalt op of stelt de tint in.

Waarde: De tint.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


Haalt de linkerrand op of stelt deze in.

Waarde: De linkerrand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Haalt de lichtheid op of stelt deze in.

Waarde: De lichtheid.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


Haalt de meest linkerrand op of stelt deze in.

Waarde: De meest linkerrand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


Haalt de meest rechterrand op of stelt deze in.

Waarde: De meest rechterrand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


Haalt de rechterrand op of stelt deze in.

Waarde: de rechterrand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Haalt de verzadiging op of stelt deze in.

Waarde: De verzadiging.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | short |  |

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

