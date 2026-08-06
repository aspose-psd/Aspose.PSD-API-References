---
title: "ColorRangeHsl"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "contient 6 plages de couleur où vous pouvez modifier les paramètres HSV."
type: docs
weight: 22
url: /fr/java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | Initialise une nouvelle instance de la classe [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl). |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | Initialise une nouvelle instance de la classe [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | Obtient ou définit la teinte. |
| [getLeftBorder()](#getLeftBorder--) | Obtient ou définit la bordure gauche. |
| [getLightness()](#getLightness--) | Obtient ou définit la luminosité. |
| [getMostLeftBorder()](#getMostLeftBorder--) | Obtient ou définit la bordure la plus à gauche. |
| [getMostRightBorder()](#getMostRightBorder--) | Obtient ou définit la bordure la plus à droite. |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | Obtient le coefficient de plage. |
| [getRightBorder()](#getRightBorder--) | Obtient ou définit la bordure droite. |
| [getSaturation()](#getSaturation--) | Obtient ou définit la saturation. |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | Détermine si la teinte est dans une grande plage. |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | Détermine si la teinte est dans une petite plage. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Enregistre les données dans le conteneur de flux spécifié. |
| [setHue(short value)](#setHue-short-) | Obtient ou définit la teinte. |
| [setLeftBorder(short value)](#setLeftBorder-short-) | Obtient ou définit la bordure gauche. |
| [setLightness(short value)](#setLightness-short-) | Obtient ou définit la luminosité. |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | Obtient ou définit la bordure la plus à gauche. |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | Obtient ou définit la bordure la plus à droite. |
| [setRightBorder(short value)](#setRightBorder-short-) | Obtient ou définit la bordure droite. |
| [setSaturation(short value)](#setSaturation-short-) | Obtient ou définit la saturation. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


Initialise une nouvelle instance de la classe [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl).

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


Initialise une nouvelle instance de la classe [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données de la plage de couleur. |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mostLeft | short |  |
| left | short |  |
| right | short |  |
| mostRight | short |  |

**Returns:**
[ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl)
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


Obtient ou définit la teinte.

Valeur : La teinte.

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


Obtient ou définit la bordure gauche.

Valeur : La bordure gauche.

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Obtient ou définit la luminosité.

Valeur : La luminosité.

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


Obtient ou définit la bordure la plus à gauche.

Valeur : La bordure la plus à gauche.

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


Obtient ou définit la bordure la plus à droite.

Valeur : La bordure la plus à droite.

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


Obtient le coefficient de plage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | double | La valeur de la teinte. |

**Returns:**
double - Coefficient de plage de saturation.
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


Obtient ou définit la bordure droite.

Valeur : La bordure droite.

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Obtient ou définit la saturation.

Valeur: La saturation.

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


Détermine si la teinte est dans une grande plage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | double | La valeur de la teinte. |

**Returns:**
booléen -  vrai  si la teinte est dans une grande plage ; sinon,  faux .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


Détermine si la teinte est dans une petite plage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hue | double | La valeur de la teinte. |

**Returns:**
booléen -  vrai  si la teinte est dans une petite plage ; sinon,  faux .
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


Enregistre les données dans le conteneur de flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Obtient ou définit la teinte.

Valeur : La teinte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


Obtient ou définit la bordure gauche.

Valeur : La bordure gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Obtient ou définit la luminosité.

Valeur : La luminosité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


Obtient ou définit la bordure la plus à gauche.

Valeur : La bordure la plus à gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


Obtient ou définit la bordure la plus à droite.

Valeur : La bordure la plus à droite.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


Obtient ou définit la bordure droite.

Valeur : La bordure droite.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Obtient ou définit la saturation.

Valeur: La saturation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

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

