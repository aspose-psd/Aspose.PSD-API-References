---
title: "ColorRangeHsl"
second_title: "Riferimento API Aspose.PSD per Java"
description: "ha 6 intervalli di colore dove è possibile modificare i parametri HSV."
type: docs
weight: 22
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Inheritance:**
java.lang.Object
```
public class ColorRangeHsl
```

[Hue2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/hue2resource) has 6 color ranges where you can change HSV parameters. Every range has 4 key points to identify range borders. And it's ColorRangeHsl
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorRangeHsl()](#ColorRangeHsl--) | Inizializza una nuova istanza della classe [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl). |
| [ColorRangeHsl(byte[] data)](#ColorRangeHsl-byte---) | Inizializza una nuova istanza della classe [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [create_internalized(short mostLeft, short left, short right, short mostRight)](#create-internalized-short-short-short-short-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHue()](#getHue--) | Ottiene o imposta la tonalità. |
| [getLeftBorder()](#getLeftBorder--) | Ottiene o imposta il bordo sinistro. |
| [getLightness()](#getLightness--) | Ottiene o imposta la luminosità. |
| [getMostLeftBorder()](#getMostLeftBorder--) | Ottiene o imposta il bordo più a sinistra. |
| [getMostRightBorder()](#getMostRightBorder--) | Ottiene o imposta il bordo più a destra. |
| [getRangeCoefficient(double hue)](#getRangeCoefficient-double-) | Ottiene il coefficiente dell'intervallo. |
| [getRightBorder()](#getRightBorder--) | Ottiene o imposta il bordo destro. |
| [getSaturation()](#getSaturation--) | Ottiene o imposta la saturazione. |
| [hashCode()](#hashCode--) |  |
| [isHueInBigRange(double hue)](#isHueInBigRange-double-) | Determina se la tonalità è nell'intervallo grande. |
| [isHueInSmallRange(double hue)](#isHueInSmallRange-double-) | Determina se la tonalità è nell'intervallo piccolo. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer)](#save-com.aspose.psd.StreamContainer-) | Salva i dati nel contenitore stream specificato. |
| [setHue(short value)](#setHue-short-) | Ottiene o imposta la tonalità. |
| [setLeftBorder(short value)](#setLeftBorder-short-) | Ottiene o imposta il bordo sinistro. |
| [setLightness(short value)](#setLightness-short-) | Ottiene o imposta la luminosità. |
| [setMostLeftBorder(short value)](#setMostLeftBorder-short-) | Ottiene o imposta il bordo più a sinistra. |
| [setMostRightBorder(short value)](#setMostRightBorder-short-) | Ottiene o imposta il bordo più a destra. |
| [setRightBorder(short value)](#setRightBorder-short-) | Ottiene o imposta il bordo destro. |
| [setSaturation(short value)](#setSaturation-short-) | Ottiene o imposta la saturazione. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorRangeHsl() {#ColorRangeHsl--}
```
public ColorRangeHsl()
```


Inizializza una nuova istanza della classe [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl).

### ColorRangeHsl(byte[] data) {#ColorRangeHsl-byte---}
```
public ColorRangeHsl(byte[] data)
```


Inizializza una nuova istanza della classe [ColorRangeHsl](../../com.aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati dell'intervallo di colore. |

### create_internalized(short mostLeft, short left, short right, short mostRight) {#create-internalized-short-short-short-short-}
```
public static ColorRangeHsl create_internalized(short mostLeft, short left, short right, short mostRight)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
| Parametro | Tipo | Descrizione |
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


Ottiene o imposta la tonalità.

Valore: La tonalità.

**Returns:**
short
### getLeftBorder() {#getLeftBorder--}
```
public final short getLeftBorder()
```


Ottiene o imposta il bordo sinistro.

Valore: Il bordo sinistro.

**Returns:**
short
### getLightness() {#getLightness--}
```
public final short getLightness()
```


Ottiene o imposta la luminosità.

Valore: La luminosità.

**Returns:**
short
### getMostLeftBorder() {#getMostLeftBorder--}
```
public final short getMostLeftBorder()
```


Ottiene o imposta il bordo più a sinistra.

Valore: Il bordo più a sinistra.

**Returns:**
short
### getMostRightBorder() {#getMostRightBorder--}
```
public final short getMostRightBorder()
```


Ottiene o imposta il bordo più a destra.

Valore: Il bordo più a destra.

**Returns:**
short
### getRangeCoefficient(double hue) {#getRangeCoefficient-double-}
```
public final double getRangeCoefficient(double hue)
```


Ottiene il coefficiente dell'intervallo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tonalità | double | Il valore della tonalità. |

**Returns:**
double - Coefficiente dell'intervallo di saturazione.
### getRightBorder() {#getRightBorder--}
```
public final short getRightBorder()
```


Ottiene o imposta il bordo destro.

Valore: Il bordo destro.

**Returns:**
short
### getSaturation() {#getSaturation--}
```
public final short getSaturation()
```


Ottiene o imposta la saturazione.

Valore: La saturazione.

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


Determina se la tonalità è nell'intervallo grande.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tonalità | double | Il valore della tonalità. |

**Returns:**
boolean -  true  se la tonalità è in un intervallo ampio; altrimenti,  false .
### isHueInSmallRange(double hue) {#isHueInSmallRange-double-}
```
public final boolean isHueInSmallRange(double hue)
```


Determina se la tonalità è nell'intervallo piccolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tonalità | double | Il valore della tonalità. |

**Returns:**
boolean -  true  se la tonalità è in un intervallo piccolo; altrimenti,  false .
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


Salva i dati nel contenitore stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di stream. |

### setHue(short value) {#setHue-short-}
```
public final void setHue(short value)
```


Ottiene o imposta la tonalità.

Valore: La tonalità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setLeftBorder(short value) {#setLeftBorder-short-}
```
public final void setLeftBorder(short value)
```


Ottiene o imposta il bordo sinistro.

Valore: Il bordo sinistro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setLightness(short value) {#setLightness-short-}
```
public final void setLightness(short value)
```


Ottiene o imposta la luminosità.

Valore: La luminosità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setMostLeftBorder(short value) {#setMostLeftBorder-short-}
```
public final void setMostLeftBorder(short value)
```


Ottiene o imposta il bordo più a sinistra.

Valore: Il bordo più a sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setMostRightBorder(short value) {#setMostRightBorder-short-}
```
public final void setMostRightBorder(short value)
```


Ottiene o imposta il bordo più a destra.

Valore: Il bordo più a destra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setRightBorder(short value) {#setRightBorder-short-}
```
public final void setRightBorder(short value)
```


Ottiene o imposta il bordo destro.

Valore: Il bordo destro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### setSaturation(short value) {#setSaturation-short-}
```
public final void setSaturation(short value)
```


Ottiene o imposta la saturazione.

Valore: La saturazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

